# Báo cáo cá nhân — Đinh Phúc Diên — 2A202603876

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

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

> Bản nháp phát triển từ trải nghiệm cá nhân đã cung cấp. Chọn các vấn đề số 3, 4, 5 của CP1; vấn đề 1 và 2 vẫn giữ ở bảng scan nhưng không đưa vào CP2. Thời gian chưa có số đo ghi “chưa đo”; target và phương án mới là đề xuất để cá nhân xem xét, chưa phải kết quả đã đạt.

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
| Success metric (baseline → target) | Baseline tự thuật: khoảng 30 phút lấy lại tập trung. Target đề xuất, cần xác nhận: tối đa 15 phút. Cách đo đề xuất: ghi thời điểm ngừng dùng điện thoại và thời điểm quay lại làm được bài, kèm số phút dùng điện thoại và số lần gián đoạn, trong 7 buổi học. |
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
| Quy trình hiện tại (3–7 bước) | Xác định công thức cần tìm → tìm trong vở và các trang ghi chú → nhận ra nội dung cần dùng. Đây là sơ đồ nháp từ lời kể, cần tự kiểm tra lại trình tự. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tìm thủ công trong ghi chú lộn xộn: khoảng 20 phút ở lần gần nhất; chưa tách thời gian lật tìm và xác nhận nội dung. |
| Impact (nếu không giải thì sao) | Mất khoảng 20 phút để có lại thông tin cần dùng, làm chậm việc tiếp tục học. |
| Success metric (baseline → target) | Baseline: khoảng 20 phút ở lần tìm gần nhất. Target đề xuất, cần xác nhận: tối đa 5 phút/lần. Cách đo đề xuất: bấm giờ từ lúc xác định nội dung cần tìm đến khi tìm đúng ghi chú trong 5 lần tra cứu tiếp theo, ghi cả lần không tìm được. |
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
| Success metric (baseline → target) | Baseline tự thuật: khoảng 120 phút vào giấc khi khó ngủ, khoảng 20 phút ngủ lại sau khi tỉnh. Target theo dõi đề xuất, cần xác nhận: ghi đủ nhật ký trong 7 đêm để xác định số đêm khó ngủ và thời gian ước lượng từng đêm; chưa chốt mục tiêu cải thiện giấc ngủ khi chưa đủ dữ liệu. |
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

- Card số: **Đề xuất #2 — Tìm lại ghi chú công thức toán; cá nhân cần xác nhận.**
- Vì sao: Có tình huống cụ thể, thời gian tìm khoảng 20 phút, quy trình dễ mô tả và có thể thử một phương án đơn giản trong phạm vi lab.
- Câu hỏi muốn nhóm phản biện: “Một lần mất 20 phút đã đủ cho thấy đây là vấn đề đáng giải chưa, hay cần kiểm tra thêm tần suất và hiệu quả của mục lục giấy?”

### AI đã phản biện card thế nào

Các nhận xét và chỉnh sửa dưới đây do AI đề xuất trong quá trình soạn bản nháp; cột đồng ý để cá nhân tự xác nhận.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 cần tách thời gian dùng điện thoại khỏi thời gian lấy lại tập trung. | Đã làm rõ bằng trải nghiệm trong trao đổi | Bản nháp tách 15–30 phút dùng điện thoại tùy lần và khoảng 30 phút lấy lại tập trung; chưa coi các số này là trung bình đã đo. |
| Card #2 dùng một lần tìm kiếm để suy ra mức độ phổ biến; chưa có bằng chứng cần AI. | Chờ cá nhân xác nhận | Ghi rõ baseline là một lần khoảng 20 phút; đề xuất đo thêm 5 lần và thử mục lục giấy trước. |
| Card #3 chưa xác định nguyên nhân; quan sát về việc không nghỉ trưa không chứng minh hiệu quả. | Chờ cá nhân xác nhận | Giữ cách tự xử lý ở mức quan sát cá nhân; chưa chốt target cải thiện hay giải pháp, đề xuất ghi nhật ký trước. |

### Thông tin cần cá nhân bổ sung để chốt CP2

- Xác nhận các bước của ba quy trình; bổ sung thời gian những bước đang ghi “chưa đo” bằng ghi nhận thực tế.
- Xác nhận hoặc điều chỉnh target đề xuất của card #1 và #2; card #3 hiện có mục tiêu thu thập dữ liệu, chưa có target cải thiện giấc ngủ.
- Tự chọn card muốn pitch và xác nhận phản biện nào đồng ý, điểm nào muốn sửa; không coi đề xuất của AI là quyết định cá nhân đã chốt.

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Chuẩn bị 3 card từ trải nghiệm cá nhân với AI hỗ trợ diễn đạt. Chưa cung cấp nội dung buổi pitch thực tế. | Có tài liệu chuẩn bị; chưa ghi kết quả pitch. |
| Phản biện bài của bạn khác | Chưa cung cấp câu hỏi đã tự đặt trong buổi thảo luận. | Cần ghi câu hỏi thật và phản hồi, không dùng câu hỏi AI đề xuất thay cho hoạt động đã làm. |
| Nhận phản biện | Làm rõ với AI: 30 phút là thời gian lấy lại tập trung, ngoài thời gian dùng điện thoại. Chưa có câu hỏi nhận từ thành viên nhóm. | Card điện thoại tách hai khoảng thời gian; phản biện nhóm cần bổ sung riêng. |
| Gom cluster / cây OST | Yêu cầu AI tổng hợp 12 candidate và chỉnh phần trình bày theo mẫu ngắn gọn. | Có bản tổng hợp ở mục 2 báo cáo nhóm; nhóm vẫn cần tự thực hiện pitch và phản biện CP3 theo quy định. |
| Chọn candidate problem | Yêu cầu so sánh candidate theo bản tổng hợp đề xuất C08. | Có bảng điểm và lý do chọn/loại; chưa có xác nhận đồng thuận nhóm. |
| Kiểm chứng / research | Được phân công hỗ trợ CP4; chưa cung cấp hoạt động đã thực hiện. | Chưa ghi nhận phỏng vấn, survey hoặc dữ liệu đã thu thập. |
| Quy trình nhóm | Chưa cung cấp đóng góp thực tế ở CP5. | Bổ sung nếu có tham gia. |
| Problem Statement | Chưa cung cấp đóng góp thực tế ở CP5–CP6. | Bổ sung nếu có tham gia. |
| Mức can thiệp AI | Chưa cung cấp ý kiến đã tự trình bày hoặc phản biện ở CP6. | Chưa ghi nhận kết quả. |
| Quyết định | Được phân công hỗ trợ CP6; chưa cung cấp hoạt động đã thực hiện. | Chưa ghi nhận quyết định cuối của nhóm. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ gợi ý hướng nhớ trải nghiệm, hỏi làm rõ và sắp xếp thành Job Story. | Tách tình huống, nhu cầu, actor và dấu hiệu thật. | Ban đầu phạm vi “kiểm tra logic/code tối ưu” còn quá rộng; bản diễn đạt cần làm rõ dung lượng lưu trữ khác RAM. | Tôi cung cấp MySQL, TileDB, 600 MB → 140 MB và xác định tối ưu code là phần mất thời gian nhất; không bổ sung số RAM chưa đo. |
| CP2 Problem Card | Nhờ phát triển bản nháp 3 card, sơ đồ và phản biện từ trải nghiệm đã kể. | Xác định bước nghẽn, tách baseline khỏi target đề xuất. | Target và card muốn pitch là AI đề xuất; nhiều thời gian từng bước chưa có số liệu. | Tôi chọn vấn đề 3–5, làm rõ 30 phút lấy lại tập trung khác thời gian dùng điện thoại; các target còn cần tôi xác nhận. |
| CP3 Tổng hợp tài liệu | Nhờ tổng hợp 12 card và đề xuất so sánh, sau đó yêu cầu rút gọn đúng mẫu. | Hỗ trợ sắp xếp tài liệu và cách trình bày. | Bản đầu dài hơn nhu cầu; điểm AI chấm chưa phải đồng thuận của nhóm. Quy định lab yêu cầu tự pitch và phản biện, không dùng AI ở CP3. | Tôi yêu cầu bỏ đoạn phân định điểm gần nhau, dùng các mục chọn/loại và mẫu ngắn gọn. Bản AI chỉ là tài liệu tham khảo; chưa ghi đã hoàn thành hoạt động nhóm. |
| CP4 Research | AI từng mở tài liệu hàm bảng tính khi soạn bản nhóm trước đó; chưa có hoạt động research cá nhân được xác nhận. | Gợi ý hướng tra nguồn chính thức. | Tra tài liệu công cụ không kiểm chứng được pain hay số liệu người dùng. | Chưa có sửa đổi cá nhân để ghi nhận; cần tự kiểm nguồn và phối hợp kiểm chứng theo phân công. |
| CP5 Quy trình | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Bổ sung sau nếu có sử dụng. |
| CP5–6 Problem Statement | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Bổ sung sau nếu có sử dụng. |
| CP6 Mức can thiệp / quyết định | Chưa ghi nhận sử dụng ở phần việc cá nhân. | Chưa đánh giá. | Chưa đánh giá. | Bổ sung sau nếu có sử dụng. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5).

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

> Gợi ý tự trả lời: chọn một vấn đề thật của bạn khác; kể trước đó bạn chưa biết gì và sau khi nghe bạn hiểu thêm điều gì.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

> Gợi ý tự trả lời: kể một phát biểu hoặc tình huống thật; nhóm đã quay lại hỏi về actor, bước nghẽn hay bằng chứng ra sao? Nếu chưa gặp, ghi đúng như vậy.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

> Gợi ý tự trả lời: ý kiến ban đầu của bạn là gì, ai hỏi câu gì và bạn đã đổi nội dung nào? Nếu chưa có phản biện nhóm, chưa ghi là đã có.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

> Gợi ý tự trả lời sau kiểm chứng: nguồn nào cho kết quả trái kỳ vọng, bằng chứng cụ thể là gì và nhóm đã sửa gì?

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

> Gợi ý tự trả lời: chọn khó khăn bạn thực sự gặp, chẳng hạn tách vấn đề khỏi giải pháp, chọn metric hoặc giới hạn phạm vi; kể ví dụ cụ thể.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

> Gợi ý tự trả lời: chọn một việc muốn làm khác, lý do và một câu hỏi bạn sẽ tự đặt cho nhóm.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- [Worksheet — hướng dẫn CP1–CP7](../../docs/01-worksheet.md).
- [Quy định sử dụng AI](../../RULES.md) và [Rubric](../../RUBRIC.md).
- [Bộ card cá nhân đã tổng hợp](../../tonghop/tonghop.md), [tiêu chí so sánh](../../tonghop/tieuchi.md) và [báo cáo nhóm](../team/group_report.md).
- Công cụ hỗ trợ: ChatGPT/Codex trong cuộc trao đổi làm bài; tình huống và số liệu cá nhân do tôi tự cung cấp.
