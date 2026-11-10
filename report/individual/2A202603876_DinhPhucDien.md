# Báo cáo cá nhân — Đinh Phúc Diên — 2A202603876

## 1. Thông tin học viên

- Họ tên: Đinh Phúc Diên
- MSSV: 2A202603876
- Tên nhóm: AIphevat
- Link repo nhóm: https://github.com/dinhphucdien179/K5-L3B-Day02-AIphevat-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi xây dựng luồng lưu trữ và đọc dữ liệu thời tiết dạng ndarray phục vụ training mô hình time series, tôi muốn xác định các thao tác sao chép bộ nhớ và chuyển đổi dữ liệu không cần thiết, để giảm thời gian xử lý và mức sử dụng bộ nhớ. | Tôi, người triển khai luồng dữ liệu phục vụ training mô hình time series thời tiết. | Lần gần nhất, tôi mất khoảng 2 ngày kiểm tra thiết kế, lựa chọn database và tối ưu code; phần tốn thời gian nhất là tránh sao chép bộ nhớ và chuyển đổi dữ liệu không cần thiết. Tôi dùng draw.io để vẽ logic, rà soát khả năng lưu trữ và đo hiệu năng, bộ nhớ. Sau khi chuyển từ MySQL lưu bằng bảng quan hệ sang TileDB lưu ndarray, dung lượng lưu trữ giảm từ khoảng 600 MB xuống 140 MB. Chưa ghi số đo cụ thể về tốc độ truy vấn và RAM trong báo cáo. |
| 2 | Tốn thời gian; cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị dữ liệu thời tiết để training mô hình time series mà API hiện tại không cung cấp dữ liệu độ ẩm, tôi muốn tìm và kiểm tra nguồn bổ sung phù hợp, để có đủ dữ liệu đầu vào theo yêu cầu trước khi training. | Tôi, người thu thập và chuẩn bị dữ liệu training. | Lần gần nhất, tôi mất một buổi tối tìm và thử các nguồn API khác vì nguồn đang dùng thiếu dữ liệu độ ẩm. Tôi đã lấy được dữ liệu bổ sung; phần tốn thời gian nhất là tìm nguồn và thử API. Tôi không còn nhớ tên các API đã dùng. |
| 3 | Tốn thời gian | Khi đang tự học nhưng bị phân tâm vì sử dụng điện thoại, tôi muốn lấy lại sự tập trung, để tiếp tục học mà không mất nhiều thời gian gián đoạn. | Tôi trong lúc tự học. | Đôi lúc khi học, tôi nghịch điện thoại khoảng 15, 20 hoặc 30 phút tùy lần, rồi mất thêm khoảng 30 phút để lấy lại sự tập trung; tổng thời gian gián đoạn không cố định. Tôi xử lý bằng cách để điện thoại lên giường, ra xa chỗ học và bật chế độ im lặng. Tôi nhận thấy để điện thoại xa giúp mình tập trung lại tốt hơn so với để gần. Chưa ghi nhận tần suất cụ thể. |
| 4 | Tốn thời gian | Khi cần sử dụng lại công thức toán học đã học và ghi trong vở giấy, tôi muốn tìm được phần ghi chú liên quan, để tiếp tục việc học mà không mất nhiều thời gian lục tìm. | Tôi khi cần tra cứu lại kiến thức đã học. | Lần gần nhất, tôi cần tìm lại ghi chú về công thức toán học trong vở giấy. Do ghi chú để lộn xộn, tôi phải lục tìm thủ công khoảng 20 phút mới tìm được nội dung cần dùng. |
| 5 | Tốn thời gian | Khi đến giờ ngủ buổi tối nhưng khó vào giấc hoặc tỉnh giữa đêm, tôi muốn ngủ đúng giờ và ít bị gián đoạn, để có đủ thời gian nghỉ ngơi và tập trung học vào ngày hôm sau. | Tôi trong sinh hoạt và học tập hằng ngày. | Tôi có những đợt khó ngủ kéo dài khoảng 3–4 ngày liên tục. Khi khó ngủ, tôi thường nằm khoảng 2 tiếng mới có thể vào giấc. Nếu tỉnh giữa đêm để đi vệ sinh, tôi mất khoảng 20 phút để ngủ lại khi lên giường ngay và không làm việc khác. Sáng hôm sau tôi thường mệt và khó tập trung học. Tôi đang tự xử lý bằng cách không nghỉ trưa, thức suốt ban ngày và nhận thấy tối dễ ngủ đúng giờ hơn; đây là quan sát cá nhân, chưa được kiểm chứng. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

Chọn các vấn đề số 3, 4, 5 của CP1. Các thời gian nêu trong card là ước lượng từ trải nghiệm cá nhân; mục tiêu cải thiện chưa phải kết quả đã đạt.

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Phân tâm vì điện thoại khi tự học (CP1 #3) | Có trải nghiệm trực tiếp, bước gián đoạn rõ, đã quan sát việc để điện thoại xa giúp tập trung hơn. | Chưa ghi tần suất, thời gian từng buổi và mức cải thiện khi để điện thoại xa. |
| 2 | Khó tìm lại ghi chú công thức toán trong vở giấy (CP1 #4) | Actor và quy trình rõ; lần gần nhất mất khoảng 20 phút tìm kiếm; có thể thử cách tổ chức ghi chú đơn giản. | Chưa rõ tần suất, số vở và cách sắp xếp hiện tại; 20 phút là một lần ghi nhận, chưa phải trung bình. |
| 3 | Khó vào giấc, tỉnh giữa đêm làm giảm tập trung học (CP1 #5) | Có trải nghiệm khó ngủ trong đợt 3–4 ngày liên tục, thời gian vào giấc khoảng 2 tiếng và ảnh hưởng ban ngày. | Chưa có nhật ký ngủ hay nguyên nhân được xác định; khó quy tác động cho một yếu tố và khó kiểm chứng trong một buổi lab. |

### Problem Card #1 — Phân tâm vì điện thoại khi tự học

| Trường | Nội dung |
|---|---|
| Job Story | Khi đang tự học nhưng bị phân tâm vì sử dụng điện thoại, tôi muốn lấy lại sự tập trung, để tiếp tục học mà không mất nhiều thời gian gián đoạn. |
| Actor | Tôi, người đang tự học. |
| Thời điểm / bối cảnh | Trong buổi học, khi chuyển từ bài học sang nghịch điện thoại. |
| Quy trình hiện tại (3–7 bước) | Bắt đầu học → dùng điện thoại → để điện thoại lên giường, ra xa và bật im lặng → lấy lại tập trung → tiếp tục học. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Lấy lại tập trung sau khi ngừng dùng điện thoại: khoảng 30 phút. Bước dùng điện thoại trước đó cũng làm gián đoạn, khoảng 15, 20 hoặc 30 phút tùy lần. |
| Impact (nếu không giải thì sao) | Thời gian dành cho học bị gián đoạn bởi cả việc dùng điện thoại và quá trình quay lại tập trung; chưa đo ảnh hưởng tới kết quả học. |
| Success metric (baseline → target) | Baseline tự thuật: khoảng 30 phút lấy lại tập trung. Target dự kiến: tối đa 15 phút. Cách đo đề xuất: ghi thời điểm ngừng dùng điện thoại và thời điểm quay lại làm được bài, kèm số phút dùng điện thoại và số lần gián đoạn, trong 7 buổi học. |
| Phương án không dùng AI | Tiếp tục cách đã thử: để điện thoại xa chỗ học và bật im lặng. Đề xuất thử chuẩn bị việc này từ đầu buổi, rồi ghi lại mức gián đoạn để so sánh. |
| Giả thuyết về AI (nếu có) | Chưa có bằng chứng cần AI; ưu tiên kiểm tra cách bố trí chỗ học và điện thoại trước. |
| Cảm nhận nhanh | No AI — nhận định ban đầu, chưa phải kết luận của nhóm. |

Quy trình nháp hiện tại:

```text
[Bắt đầu tự học: chưa đo]
→ [Nghịch điện thoại: khoảng 15 / 20 / 30 phút tùy lần]
→ [Để điện thoại ra xa, bật im lặng: chưa đo]
→ [Lấy lại tập trung: khoảng 30 phút] ← BOTTLENECK CHÍNH
→ [Tiếp tục học: chưa đo]

Chưa đo tổng thời gian cả buổi; các bước chưa có số liệu cần ghi nhận thêm.
```

### Problem Card #2 — Khó tìm lại ghi chú công thức toán

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần sử dụng lại công thức toán học đã học và ghi trong vở giấy, tôi muốn tìm được phần ghi chú liên quan, để tiếp tục việc học mà không mất nhiều thời gian lục tìm. |
| Actor | Tôi, người cần tra cứu kiến thức đã ghi trong vở. |
| Thời điểm / bối cảnh | Khi cần dùng lại công thức toán đã học nhưng không nhớ vị trí ghi chú. |
| Quy trình hiện tại (3–7 bước) | Xác định công thức cần tìm → tìm trong vở và các trang ghi chú → nhận ra nội dung cần dùng.  |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tìm thủ công trong ghi chú lộn xộn: khoảng 20 phút ở lần gần nhất; chưa tách thời gian lật tìm và xác nhận nội dung. |
| Impact (nếu không giải thì sao) | Mất khoảng 20 phút để có lại thông tin cần dùng, làm chậm việc tiếp tục học. |
| Success metric (baseline → target) | Baseline: khoảng 20 phút ở lần tìm gần nhất. Target dự kiến: tối đa 5 phút/lần. Cách đo đề xuất: bấm giờ từ lúc xác định nội dung cần tìm đến khi tìm đúng ghi chú trong 5 lần tra cứu tiếp theo, ghi cả lần không tìm được. |
| Phương án không dùng AI | Đề xuất đánh số trang, tạo mục lục theo chủ đề và đánh dấu những phần thường tra cứu; thử trên vở hiện có trước. Chưa thực hiện hoặc đo hiệu quả. |
| Giả thuyết về AI (nếu có) | Chưa cần AI ở bước đầu. Chỉ cân nhắc hỗ trợ nhận dạng hoặc tìm kiếm ghi chú nếu thử nghiệm cho thấy mục lục và đánh dấu trang chưa đủ. |
| Cảm nhận nhanh | No AI — ưu tiên cải thiện cách tổ chức ghi chú. |

Quy trình nháp hiện tại:

```text
[Xác định công thức cần tìm: chưa đo]
→ [Lục tìm trong vở, nhận ra đúng ghi chú: khoảng 20 phút] ← BOTTLENECK
→ [Có ghi chú để tiếp tục học: chưa đo]

20 phút là thời gian tự thuật của một lần tìm, chưa phải số trung bình.
```

### Problem Card #3 — Khó vào giấc và ngủ gián đoạn

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến giờ ngủ buổi tối nhưng khó vào giấc hoặc tỉnh giữa đêm, tôi muốn ngủ đúng giờ và ít bị gián đoạn, để có đủ thời gian nghỉ ngơi và tập trung học vào ngày hôm sau. |
| Actor | Tôi trong sinh hoạt và học tập hằng ngày. |
| Thời điểm / bối cảnh | Có những đợt khó ngủ khoảng 3–4 ngày liên tục; có lúc tỉnh giữa đêm để đi vệ sinh. |
| Quy trình hiện tại (3–7 bước) | Lên giường → nằm chờ vào giấc → ngủ → nếu tỉnh để đi vệ sinh thì trở lại giường, không làm việc khác → ngủ lại → thức dậy. Nhánh tỉnh giữa đêm không nhất thiết xảy ra mỗi đêm. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Nằm chờ vào giấc ban đầu: khoảng 120 phút khi khó ngủ. Nếu tỉnh giữa đêm và trở lại giường ngay, thời gian ngủ lại khoảng 20 phút. |
| Impact (nếu không giải thì sao) | Sáng hôm sau thường mệt, khi cần làm việc dễ mệt và khả năng tập trung học không cao, theo cảm nhận cá nhân. |
| Success metric (baseline → target) | Baseline tự thuật: khoảng 120 phút vào giấc khi khó ngủ, khoảng 20 phút ngủ lại sau khi tỉnh. Mục tiêu theo dõi: ghi đủ nhật ký trong 7 đêm để xác định số đêm khó ngủ và thời gian ước lượng từng đêm; chưa chốt mục tiêu cải thiện giấc ngủ khi chưa đủ dữ liệu. |
| Phương án không dùng AI | Đề xuất ghi nhật ký giấy về giờ lên giường, thời gian ước lượng vào giấc, các lần tỉnh, nghỉ trưa và mức mệt/tập trung hôm sau. Cách đang tự làm là không nghỉ trưa; chỉ ghi nhận quan sát này, chưa xác lập quan hệ nguyên nhân hay đưa thành khuyến nghị. |
| Giả thuyết về AI (nếu có) | Chưa có bằng chứng cần AI. Nếu cần công cụ hỗ trợ thì trước hết chỉ xem xét ghi chép và tổng hợp nhật ký; không giao việc chẩn đoán hay quyết định điều trị cho công cụ. |
| Cảm nhận nhanh | Chưa biết — cần thêm dữ liệu, chưa rõ nguyên nhân và phạm vi can thiệp. |

Quy trình nháp hiện tại:

```text
[Lên giường: chưa đo]
→ [Chờ vào giấc: khoảng 120 phút khi khó ngủ] ← BOTTLENECK CHÍNH
→ [Ngủ: chưa đo]
→ Nếu tỉnh giữa đêm:
   [Đi vệ sinh, trở lại giường ngay: chưa đo]
   → [Ngủ lại: khoảng 20 phút]
→ [Thức dậy: chưa đo; thường cảm thấy mệt và khó tập trung]

Các mốc là ước lượng cá nhân, chưa có nhật ký đo liên tục.
```

### Card muốn pitch nhất

- Card số: **#2 — Tìm lại ghi chú công thức toán.**
- Vì sao: Có tình huống cụ thể, thời gian tìm khoảng 20 phút, quy trình dễ mô tả và có thể thử một phương án đơn giản trong phạm vi lab.
- Câu hỏi muốn nhóm phản biện: “Một lần mất 20 phút đã đủ cho thấy đây là vấn đề đáng giải chưa, hay cần kiểm tra thêm tần suất và hiệu quả của mục lục giấy?”

### AI đã phản biện card thế nào

Các điểm được rà soát tập trung vào độ chính xác của số liệu và giới hạn bằng chứng.

| Điểm yếu AI chỉ ra | Kết luận rà soát | Đã sửa gì |
|---|---|---|
| Card #1 cần tách thời gian dùng điện thoại khỏi thời gian lấy lại tập trung. | Đã làm rõ bằng trải nghiệm trong trao đổi | Tách 15–30 phút dùng điện thoại tùy lần và khoảng 30 phút lấy lại tập trung; chưa coi các số này là trung bình đã đo. |
| Card #2 dùng một lần tìm kiếm để suy ra mức độ phổ biến; chưa có bằng chứng cần AI. | Chỉ có bằng chứng cho một lần tìm kiếm | Ghi rõ baseline là một lần khoảng 20 phút; đề xuất đo thêm 5 lần và thử mục lục giấy trước. |
| Card #3 chưa xác định nguyên nhân; quan sát về việc không nghỉ trưa không chứng minh hiệu quả. | Chưa đủ bằng chứng kết luận nguyên nhân | Giữ cách tự xử lý ở mức quan sát cá nhân; chưa chốt target cải thiện hay giải pháp, đề xuất ghi nhật ký trước. |

### Giới hạn số liệu và kế hoạch đo

- Các bước ghi “chưa đo” chưa có dữ liệu, không gán thêm thời gian ước đoán.
- Card #1 đặt mục tiêu từ khoảng 30 phút lấy lại tập trung xuống tối đa 15 phút, theo dõi trong 7 buổi học.
- Card #2 đặt mục tiêu từ khoảng 20 phút tìm ghi chú xuống tối đa 5 phút, theo dõi trong 5 lần tra cứu.
- Card #3 ưu tiên ghi đủ nhật ký 7 đêm để xác định baseline; chưa chốt mục tiêu cải thiện giấc ngủ hoặc nguyên nhân.

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Chuẩn bị 3 card từ trải nghiệm cá nhân với AI hỗ trợ diễn đạt. Chưa có biên bản pitch trong tài liệu hiện có. | Có tài liệu chuẩn bị; chưa ghi kết quả pitch. |
| Phản biện bài của bạn khác | Chưa ghi nhận câu hỏi phản biện trực tiếp với thành viên nhóm. | Chưa có kết quả phản biện nhóm để báo cáo. |
| Nhận phản biện | Làm rõ với AI: 30 phút là thời gian lấy lại tập trung, ngoài thời gian dùng điện thoại. Chưa có câu hỏi nhận từ thành viên nhóm. | Card điện thoại tách hai khoảng thời gian; phản biện nhóm cần bổ sung riêng. |
| Gom cluster / cây OST | Yêu cầu AI tổng hợp 12 candidate và chỉnh phần trình bày theo mẫu ngắn gọn. | Có bản tổng hợp ở mục 2 báo cáo nhóm; nhóm vẫn cần tự thực hiện pitch và phản biện CP3 theo quy định. |
| Chọn candidate problem | Yêu cầu so sánh candidate theo bản tổng hợp đề xuất C08. | Có bảng điểm và lý do chọn/loại; chưa có xác nhận đồng thuận nhóm. |
| Kiểm chứng / research | Được phân công hỗ trợ CP4; tài liệu hiện có chưa ghi nhận hoạt động kiểm chứng đã thực hiện. | Chưa ghi nhận phỏng vấn, survey hoặc dữ liệu đã thu thập. |
| Quy trình nhóm | Không có đóng góp CP5 được ghi nhận trong tài liệu hiện tại. | Chưa có sản phẩm cá nhân được ghi nhận ở phần này. |
| Problem Statement | Không có đóng góp CP5–CP6 được ghi nhận trong tài liệu hiện tại. | Chưa có sản phẩm cá nhân được ghi nhận ở phần này. |
| Mức can thiệp AI | Chưa ghi nhận ý kiến cá nhân ở CP6. | Chưa ghi nhận kết quả. |
| Quyết định | Được phân công hỗ trợ CP6; chưa có kết luận cuối trong báo cáo nhóm. | Chưa ghi nhận quyết định cuối của nhóm. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ gợi ý hướng nhớ trải nghiệm, hỏi làm rõ và sắp xếp thành Job Story. | Tách tình huống, nhu cầu, actor và dấu hiệu thật. | Ban đầu phạm vi “kiểm tra logic/code tối ưu” còn quá rộng; bản diễn đạt cần làm rõ dung lượng lưu trữ khác RAM. | Tôi cung cấp MySQL, TileDB, 600 MB → 140 MB và xác định tối ưu code là phần mất thời gian nhất; không bổ sung số RAM chưa đo. |
| CP2 Problem Card | Nhờ phát triển 3 card, sơ đồ và phản biện từ trải nghiệm đã kể. | Xác định bước nghẽn, tách baseline khỏi target đề xuất. | AI đề xuất target và card ưu tiên, nhưng chưa có dữ liệu thử nghiệm để khẳng định hiệu quả. | Tôi chọn vấn đề 3–5, làm rõ 30 phút lấy lại tập trung khác thời gian dùng điện thoại; các target được tách khỏi kết quả đo thực tế. |
| CP3 Tổng hợp tài liệu | Nhờ tổng hợp 12 card và đề xuất so sánh, sau đó yêu cầu rút gọn đúng mẫu. | Hỗ trợ sắp xếp tài liệu và cách trình bày. | Bản đầu dài hơn nhu cầu; điểm AI chấm chưa phải đồng thuận của nhóm. Quy định lab yêu cầu tự pitch và phản biện, không dùng AI ở CP3. | Tôi yêu cầu bỏ đoạn phân định điểm gần nhau, dùng các mục chọn/loại và mẫu ngắn gọn. Bản AI chỉ là tài liệu tham khảo; chưa ghi đã hoàn thành hoạt động nhóm. |
| CP4 Research | AI từng mở tài liệu hàm bảng tính khi soạn bản nhóm trước đó; chưa có hoạt động research cá nhân được xác nhận. | Gợi ý hướng tra nguồn chính thức. | Tra tài liệu công cụ không kiểm chứng được pain hay số liệu người dùng. | Chưa có sửa đổi cá nhân để ghi nhận; cần tự kiểm nguồn và phối hợp kiểm chứng theo phân công. |
| CP5 Quy trình | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Chưa có nội dung sử dụng cá nhân được ghi nhận. |
| CP5–6 Problem Statement | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Chưa có nội dung sử dụng cá nhân được ghi nhận. |
| CP6 Mức can thiệp / quyết định | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Chưa có nội dung sử dụng cá nhân được ghi nhận. |
| CP7 Reflection | Nhờ hỗ trợ diễn đạt từ cuộc trao đổi và báo cáo hiện có. | Sắp xếp các nhận xét theo câu hỏi 6.1–6.7. | Tài liệu chưa có kết quả pitch, phỏng vấn và quyết định cuối để phản ánh đầy đủ trải nghiệm nhóm. | Giữ riêng nhận xét từ việc đọc tài liệu với kết quả kiểm chứng; không thêm người hỏi, lời trích hoặc số liệu chưa có. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua việc tổng hợp các Problem Card của các thành viên, tôi thấy vấn đề không chỉ nằm trong những trải nghiệm học tập của mình. Card về kiểm tra lead cho thấy dữ liệu phân tán có thể khiến nhiều người cùng mất thời gian đối chiếu và khiến Sales gọi trùng khách. Card về tìm cách sửa lỗi lab và đối chiếu slide–báo cáo cũng cho thấy cần mô tả đúng bước nghẽn thay vì chỉ nói chung là “tốn thời gian”. Phần tôi có căn cứ trình bày ở đây là đọc và tổng hợp tài liệu; chưa có biên bản để kể lại một buổi pitch trực tiếp.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Tôi chưa có tình huống thảo luận cụ thể để khẳng định nhóm đã mắc lỗi này. Tuy nhiên, khi chuẩn bị cây OST, tôi phân biệt được “khó phát hiện lead trùng giữa nhiều file” là pain, còn “dùng bảng tính chung” hay “AI lọc lead” là giải pháp. Khi trình bày, cần đặt nhu cầu và trở ngại ở tầng opportunity, sau đó mới so sánh cách can thiệp. Điểm cần tiếp tục kiểm tra là một bảng chung và công thức có đủ giải quyết vấn đề hay chưa.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Một thay đổi có căn cứ trong quá trình làm bài là cách mô tả vấn đề phân tâm do điện thoại. Khi được AI hỏi làm rõ, tôi xác nhận khoảng 30 phút là thời gian lấy lại tập trung sau khi ngừng dùng điện thoại, còn thời gian dùng điện thoại có thể là 15, 20 hoặc 30 phút tùy lần. Nhờ vậy, card tách hai khoảng thời gian và không coi 30 phút là toàn bộ gián đoạn. Đây là việc làm rõ và sửa mô tả sau câu hỏi của AI, chưa phải ví dụ đổi ý do một thành viên nhóm phản biện.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Tài liệu hiện tại chưa có kết quả phỏng vấn, survey hoặc thử nghiệm để tôi nêu một phát hiện bất ngờ đã được kiểm chứng. Điều tôi rút ra khi đọc card C08 là một vấn đề có nhiều thao tác và tác động tới nhiều người vẫn có thể bắt đầu bằng sửa quy trình hoặc Rule. Tuy nhiên, đây mới là nhận xét từ tài liệu, chưa chứng minh phương án đó hiệu quả. Tôi cần hỗ trợ kiểm chứng nguồn paid, cách xác định lead trùng và số liệu thời gian theo phân công CP4 trước khi kết luận.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Qua quá trình viết các card, tôi thấy phần cần làm rõ nhất là biến mô tả chung thành bước nghẽn và metric cụ thể. Ban đầu tôi nói “kiểm tra logic và code có tối ưu không”; sau các câu hỏi, tôi xác định phần tốn thời gian nhất là tránh sao chép bộ nhớ và chuyển đổi dữ liệu không cần thiết. Tôi cũng cần tách dung lượng lưu trữ 600 MB xuống 140 MB khỏi mức RAM chưa có số đo. Với các card được chọn, baseline tự thuật và target đề xuất phải được ghi riêng, không coi mục tiêu là kết quả đã đạt.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ ghi thời gian và hoàn cảnh ngay khi gặp vấn đề, thay vì chỉ dựa vào trí nhớ khi viết báo cáo. Tôi sẽ ghi rõ nguồn của từng con số và kiểm tra xem các thành viên đang so sánh cùng phạm vi công việc hay không. Tôi cũng sẽ giữ phần tổng hợp ngắn gọn ngay từ đầu, vì bản tổng hợp đầu tiên dài hơn nhu cầu và tôi đã phải yêu cầu chỉnh theo mẫu. Khi phản biện, tôi muốn hỏi: “Bằng chứng nào cho thấy đây là bước nghẽn?” và “Nếu chỉ sửa quy trình hoặc dùng Rule thì phần vấn đề còn lại là gì?”.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài nhóm đang đề xuất C08: người chạy quảng cáo phải kiểm tra lead trùng và trạng thái đã thanh toán trước khi bàn giao cho Sales. Quy trình hiện tại gồm mở file riêng, dò file tổng, dò danh sách paid, chuẩn hóa dữ liệu, copy và báo Sales; bước dò trùng khoảng 70 phút và dò paid khoảng 50 phút theo card. Metric đề xuất là giảm tổng thời gian từ 2–3 giờ xuống tối đa 30 phút/ngày/người và giảm cuộc gọi sai hoặc nhầm từ 9–15 xuống tối đa 2 lần/tuần, nhưng baseline còn cần xác minh. Boundary đề xuất là không tự xóa hay gộp khách chưa chắc chắn, không tự sửa trạng thái thanh toán và để con người duyệt trước khi bàn giao. Mức ưu tiên kiểm chứng là Rule để chuẩn hóa và đối chiếu theo điều kiện rõ ràng, chưa có bằng chứng cần Workflow có AI hoặc Agent. Báo cáo nhóm đang ghi nhận định sơ bộ Not Yet vì dữ liệu và kiểm chứng chưa đầy đủ, trong khi phần quyết định CP6 chưa được chốt. Bước tiếp theo là kiểm chứng với người dùng thật, xác nhận dữ liệu được phép dùng và cập nhật quyết định theo kết quả đo.

