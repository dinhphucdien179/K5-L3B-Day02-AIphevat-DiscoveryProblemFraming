# Báo cáo cá nhân — 2A202603835_NguyenTrongNghia

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Trọng Nghĩa
- MSSV: 2A202603835
- Email trường (không bắt buộc, repo có thể để public): nghiatrongnguyen2304@gmail.com
- Tên nhóm: AIphevat (Lớp L3B)
- Link repo nhóm: https://github.com/dinhphucdien179/K5-L3B-Day02-AIphevat-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi chuẩn bị nộp lab mỗi ngày, tôi muốn đối chiếu tên repo, tên file và các mục bắt buộc với SUBMISSION/RUBRIC, để không bị trừ điểm vì sai quy chuẩn | Nhóm trưởng, người tổng hợp bài | Mất 30 phút mỗi tuần vào tối Chủ nhật; nhóm bị không công nhận bài nộp hoặc trừ điểm do đặt sai cú pháp tên file nộp; có log tin nhắn nhắc nhau 3 lần trên Zalo |
| 2 | Lặp lại | Khi giải xong một bài LeetCode/Codeforces, tôi muốn ghi lại pattern và lỗi sai của mình, để lần sau gặp dạng tương tự không sai lại | Người luyện CP | Có 3 bài gần đây nhất từng AC rồi làm lại vẫn WA/TLE|
| 3 | Tốn thời gian | Khi bài bị WA/TLE ở test ẩn, tôi muốn tìm ra test phản ví dụ, để sửa đúng lỗi thay vì đoán mò | Người luyện CP | Trung bình 5 phút debug ở mỗi 3 bài WA/TLE gần nhất |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi gặp lỗi submit bài làm hoặc tìm kiếm lại tài liệu cho bài lab, tôi muốn tìm lại các giải pháp mà các bạn cùng lớp hoặc trợ giảng đã thảo luận trước đó trong kênh chat môn học, để tự khắc phục lỗi ngay thay vì phải chờ hỏi lại | Toàn bộ sinh viên trong lớp (khoảng 250–300 người) | Kênh Discord lớp có hơn 3000 tin nhắn mỗi tuần; mỗi lần tìm lỗi mất 20–30 phút dò từ khóa nhưng thường trôi mất ngữ cảnh hoặc link tài liệu đính kèm |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị thuyết trình bảo vệ đồ án cuối kỳ, tôi muốn đối chiếu giữa slide thuyết trình và nội dung báo cáo chi tiết, để đảm bảo các luận điểm và con số số liệu giữa slide và báo cáo hoàn toàn đồng nhất | Người làm slide, người thuyết trình chính | 60–75 phút mỗi đợt bảo vệ đồ án và ít nhất 2 buổi tập thuyết trình đồ án lại nếu số liệu, nội dung có thay đổi |
| 6 | Pain từ người khác | Khi nhận một pull request cần review trên repository nhóm, tôi với vai trò người review muốn nắm được mục đích thay đổi và danh sách các module bị ảnh hưởng, để review nhanh và merge code mà không gây xung đột (merge conflict) với nhánh của người khác | Người review code (chính), tác giả PR phải chờ được merge | Trung bình 6–8 PR/tuần trong giai đoạn nước rút; có 4 PR bị treo hơn 24 giờ vì reviewer không hiểu code sửa cái gì, dẫn tới conflict 2 nhánh vào ngày chót nộp bài |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý AI gợi ý mà tôi giữ lại:** dòng #1 (đối chiếu tên repo, tên file khi nộp lab), #2 (ghi lại pattern và lỗi sai sau khi giải bài) và #3 (tìm test phản ví dụ khi bị WA/TLE) bắt nguồn từ danh sách 10 problem do AI (Claude) gợi ý. Tôi giữ vì đây là việc tôi thật sự gặp, và đã tự viết lại bằng số liệu của mình (30 phút mỗi tuần, nhắc nhau 3 lần trên Zalo, 3 bài từng AC rồi làm lại vẫn WA, khoảng 5 phút debug mỗi bài).
- **Ý AI gợi ý mà tôi bỏ:** gom deadline từ nhiều kênh, dựng môi trường cho lab mới, đọc đề lab nhiều file, tìm lại thông báo của coach, đọc nhiều editorial, TA chấm nhiều repo, nhóm trưởng nhắc thành viên commit. Bỏ vì tôi không có dấu hiệu thật đo được cho các ý này, hoặc phải phỏng vấn người khác (ví dụ TA) mới có số liệu.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tìm lại lời giải đã được thảo luận trong kênh Discord lớp (#4) | Nhiều người gặp nhất (lớp 250–300 sinh viên), kênh có hơn 3000 tin nhắn/tuần, mỗi lần tìm mất 20–30 phút; quy trình tìm kiếm vẽ được rõ từng bước | Chưa biết mỗi sinh viên phải tìm lại bao nhiêu lần/tuần; chưa biết TA có đang phải trả lời lặp lại cùng một câu hỏi không |
| 2 | Đối chiếu số liệu giữa slide và báo cáo đồ án (#5) | Có baseline thời gian rõ (60–75 phút/đợt), lỗi lệch số liệu làm phải tập lại ít nhất 2 buổi; đầu vào (slide, báo cáo) có sẵn | Chỉ xảy ra vài lần mỗi kỳ (mỗi đợt bảo vệ), tần suất thấp |
| 3 | Ghi lại pattern và lỗi sai sau khi giải bài LeetCode/Codeforces (#2) | Pain thật của chính tôi: có 3 bài từng AC rồi làm lại vẫn WA (ví dụ LCS); tần suất nó xảy ra khá nhiều - hằng tuần | Chưa đo thời gian ghi chú mỗi bài; có thể vấn đề là thói quen chứ không phải thiếu công cụ |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi gặp lỗi submit bài làm hoặc cần tìm lại tài liệu cho bài lab, tôi muốn tìm lại các giải pháp mà các bạn cùng lớp hoặc trợ giảng đã thảo luận trước đó trong kênh chat môn học, để tự khắc phục lỗi ngay thay vì phải chờ hỏi lại |
| Actor | Sinh viên trong lớp (khoảng 250–300 người) gặp lỗi khi làm hoặc nộp lab; người bị ảnh hưởng gián tiếp: TA phải trả lời lại câu hỏi cũ |
| Thời điểm / bối cảnh | Trong giờ làm lab hoặc sát deadline nộp bài, khi gặp lỗi submit / lỗi môi trường mà nhiều khả năng đã có người hỏi trước đó |
| Quy trình hiện tại (3–7 bước) | 1. Gặp lỗi, copy thông báo lỗi · 2. Gõ từ khóa vào ô search của Discord · 3. Lướt danh sách kết quả, mở từng tin nhắn để đọc ngữ cảnh xung quanh · 4. Nếu không thấy: đăng câu hỏi mới vào kênh và chờ trả lời · 5. Áp dụng cách sửa và thử lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, lướt kết quả và mở từng tin nhắn để đọc ngữ cảnh: khoảng 15–20 phút, vì search theo từ khóa trả về tin nhắn rời rạc, câu trả lời thường nằm ở tin nhắn khác không chứa từ khóa, link tài liệu đính kèm bị trôi |
| Impact (nếu không giải thì sao) | Mỗi lần mất 20–30 phút; nếu bỏ cuộc thì phải hỏi lại và chờ, có thể trễ deadline; cùng một câu hỏi bị hỏi lại nhiều lần làm kênh càng nhiễu hơn |
| Success metric (baseline → target) | Thời gian từ lúc bắt đầu tìm đến lúc có cách sửa đã được thảo luận: 20–30 phút → dưới 5 phút. Đo bằng bấm giờ 5 lần tìm kiếm thật trong tuần tới |
| Phương án không dùng AI | Nhờ TA ghim tin nhắn / lập kênh FAQ hoặc Forum channel có tag theo lab (ví dụ `day02-submit`), mỗi lỗi phổ biến có 1 thread với câu trả lời đã chốt |
| Giả thuyết về AI (nếu có) | Tìm kiếm theo ý nghĩa trên lịch sử kênh, trả về tóm tắt cách sửa kèm link đến tin nhắn gốc để người hỏi tự kiểm lại |
| Cảm nhận nhanh | Workflow (nhưng cần so với phương án FAQ/Forum trước) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 20–30 phút/lần tìm

[1. Gặp lỗi, copy thông báo lỗi: 1']
→ [2. Gõ từ khóa vào search Discord: 2']
→ [3. Lướt kết quả, mở từng tin nhắn đọc ngữ cảnh: 15–20'] ← BOTTLENECK (kết quả rời rạc, câu trả lời không chứa từ khóa, link bị trôi)
→ [4. Không thấy → đăng câu hỏi mới, chờ trả lời: chưa đo]
→ [5. Áp dụng cách sửa, thử lại: 2–5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị thuyết trình bảo vệ đồ án cuối kỳ, tôi muốn đối chiếu giữa slide thuyết trình và nội dung báo cáo chi tiết, để đảm bảo các luận điểm và con số giữa slide và báo cáo hoàn toàn đồng nhất |
| Actor | Người làm slide (chính), người thuyết trình chính |
| Thời điểm / bối cảnh | Những ngày trước buổi bảo vệ, đặc biệt khi báo cáo vừa được cập nhật số liệu (chạy lại thực nghiệm, sửa bảng) mà slide đã làm xong từ trước |
| Quy trình hiện tại (3–7 bước) | 1. Nhận bản báo cáo mới nhất · 2. Mở slide và báo cáo song song · 3. Dò từng slide, tìm con số / luận điểm tương ứng trong báo cáo và so sánh · 4. Sửa các chỗ lệch trên slide · 5. Tập lại phần thuyết trình bị thay đổi |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, dò từng con số giữa slide và báo cáo: khoảng 40–50 phút, vì phải tự tìm vị trí tương ứng trong báo cáo dài, dễ bỏ sót số nằm trong bảng hoặc biểu đồ |
| Impact (nếu không giải thì sao) | 60–75 phút mỗi đợt bảo vệ; nếu sót lỗi thì phải tập lại ít nhất 2 buổi khi số liệu, nội dung thay đổi; rủi ro bị hội đồng chỉ ra số liệu lệch ngay trong buổi bảo vệ |
| Success metric (baseline → target) | Thời gian đối chiếu: 60–75 phút → dưới 20 phút; số chỗ lệch bị phát hiện trong buổi tập/bảo vệ → 0. Đo bằng bấm giờ ở đợt bảo vệ tới và ghi lại số chỗ lệch bị góp ý |
| Phương án không dùng AI | Lập một bảng "nguồn số liệu" duy nhất (Google Sheet), mỗi con số có một mã; cả slide và báo cáo đều lấy số từ bảng này, khi đổi số chỉ cần sửa và tìm theo mã |
| Giả thuyết về AI (nếu có) | Trích toàn bộ con số và luận điểm từ slide và báo cáo, ghép cặp theo ngữ cảnh rồi liệt kê các cặp không khớp để người làm slide kiểm tra |
| Cảm nhận nhanh | Rule (trích số bằng script và so khớp); chỉ cần AI nếu phải so khớp luận điểm bằng chữ |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 60–75 phút/đợt bảo vệ (chưa tính tập lại)

[1. Nhận bản báo cáo mới nhất: 2']
→ [2. Mở slide và báo cáo song song: 3']
→ [3. Dò từng con số / luận điểm giữa slide và báo cáo: 40–50'] ← BOTTLENECK (báo cáo dài, số nằm trong bảng/biểu đồ dễ sót)
→ [4. Sửa các chỗ lệch trên slide: 10–15']
→ [5. Tập lại phần thuyết trình bị thay đổi: ít nhất 2 buổi nếu số liệu đổi]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi giải xong một bài LeetCode/Codeforces, tôi muốn ghi lại pattern và lỗi sai của mình, để lần sau gặp dạng tương tự không sai lại |
| Actor | Tôi, người luyện competitive programming / LeetCode |
| Thời điểm / bối cảnh | Ngay sau khi bài được AC, nhất là các bài phải submit nhiều lần mới qua; và khi gặp lại dạng tương tự sau vài tuần |
| Quy trình hiện tại (3–7 bước) | 1. Đọc đề, nghĩ hướng giải · 2. Code và submit, sửa đến khi AC · 3. Đóng bài, không ghi lại hoặc chỉ ghi vài dòng rời rạc · 4. Vài tuần sau gặp lại dạng tương tự · 5. Không nhớ lỗi cũ, mắc lại lỗi và bị WA |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, bước ghi lại pattern và lỗi sai sau khi AC: bị bỏ qua (gần 0 phút), vì ghi chú đầy đủ mất thời gian trong khi muốn chuyển sang bài tiếp theo |
| Impact (nếu không giải thì sao) | Đã có 3 bài từng AC rồi làm lại vẫn WA (ví dụ LCS); mất lại thời gian debug cho lỗi mình đã từng gặp |
| Success metric (baseline → target) | Số bài dạng cũ làm lại bị WA vì lỗi đã từng mắc: 3 bài → 0 bài trong 1 tháng tới. Đo bằng lịch sử submission trên LeetCode/Codeforces và ghi chú của mình |
| Phương án không dùng AI | Template ghi chú 3 dòng ngay sau AC (Pattern · Lỗi đã mắc · Test bẫy) trong Notion hoặc Anki, ôn lại theo lịch lặp lại ngắt quãng |
| Giả thuyết về AI (nếu có) | Đọc code các lần submit WA và lần AC, gợi ý bản nháp "lỗi đã mắc" và "pattern" để tôi sửa lại trước khi lưu |
| Cảm nhận nhanh | No AI (thói quen + template có thể là đủ) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian mỗi bài: khoảng 30' giải + 0' ghi chú

[1. Đọc đề, nghĩ hướng giải: 10']
→ [2. Code và submit, sửa đến khi AC: 20']
→ [3. Ghi lại pattern và lỗi sai: 0' (bỏ qua)] ← BOTTLENECK (không có bước ghi chú nên không còn gì để ôn)
→ [4. Vài tuần sau gặp lại dạng tương tự: —]
→ [5. Mắc lại lỗi cũ, debug lại: 5' mỗi lần WA/TLE]
```

### Card muốn pitch nhất

- Card số: **Card #1** (Tìm lại lời giải đã được thảo luận trong kênh Discord lớp)
- Vì sao: Số người gặp nhiều nhất trong 3 card (cả lớp 250–300 sinh viên), cả nhóm cũng là người trong cuộc nên dễ kiểm chứng bằng phỏng vấn bạn ở nhóm khác; quy trình có bottleneck cụ thể (bước đọc ngữ cảnh 15–20 phút); có phương án không dùng AI rõ ràng (FAQ/Forum) để so sánh công bằng với Workflow.
- Câu hỏi muốn nhóm phản biện:
  *"Nếu TA chỉ cần lập một kênh FAQ có tag theo từng lab, thì phần còn lại của pain có còn đủ lớn để cần một bước tìm kiếm thông minh hơn không?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: "250–300 người" là quy mô lớp, chưa phải số người thật sự gặp pain; thiếu tần suất mỗi người phải tìm lại bao nhiêu lần/tuần nên chưa tính được impact tổng | Đồng ý | Ghi tần suất vào cột "Điều còn chưa chắc"; đổi metric sang đo bằng 5 lần tìm kiếm thật được bấm giờ; sẽ hỏi tần suất khi phỏng vấn ở CP4 |
| Card #1: phương án FAQ/Forum channel có thể giải được phần lớn pain mà không cần AI | Đồng ý một phần | Đổi cảm nhận thành "Workflow nhưng cần so với FAQ/Forum trước"; đưa câu này thành câu hỏi phản biện cho nhóm. Giữ card vì FAQ không bao phủ được các lỗi chưa ai ghim; hoặc có thể câu hỏi chúng ta cần tìm là một câu hỏi ngách |
| Card #2: baseline 60–75 phút gộp cả bước sửa slide, chưa tách riêng thời gian dò số liệu | Đồng ý | Tách bước 3 (dò số liệu, 40–50 phút) làm bottleneck riêng, bước sửa slide tính riêng |
| Card #3: pain có thể là thói quen chứ không phải thiếu công cụ; template ghi chú có thể là đủ | Đồng ý | Đổi cảm nhận nhanh thành "No AI" và xếp card này hạng 3 |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đưa 3 card vào danh sách candidate của nhóm: C10 (tìm lại cách sửa lỗi lab trong kênh chat), C11 (đối chiếu slide và báo cáo), C12 (ghi lại pattern và lỗi sai khi luyện lập trình) | C10 và C11 vào shortlist 3 candidate (26/35 điểm); C12 xếp hạng 7 |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>- Với Diên (C01 - Phân tâm điện thoại): *"Nếu chỉ cần để điện thoại ở phòng khác hoặc dùng app khóa màn hình (No AI) thì đã đủ giải quyết chưa, có thực sự cần một hệ thống theo dõi hành vi không?"*<br>- Với Tiệp (C07 - Kế toán xã): *"Dữ liệu lương/BHXH là dữ liệu nhạy cảm, bạn có xin được mẫu bảng biểu thật để kiểm chứng trong thời gian lab không?"*<br>- Với Tiệp (C08 - Lọc lead): *"Nếu nhiều người chạy ads cùng dán data vào file tổng gần như cùng một lúc thì làm sao tránh được việc 2 người cùng nhận 1 lead mới phát sinh?"* | Giúp nhóm nhận ra C07 có rủi ro bảo mật dữ liệu cao; C08 được đưa vào thảo luận kỹ về tính đồng thời và ràng buộc file dùng chung |
| Nhận phản biện | Câu hỏi tôi nhận được: Diên hỏi tôi về C10 (Discord): *"Nếu TA chỉ cần ghim tin nhắn hoặc lập Forum/FAQ tag theo từng bài lab thì phần pain tìm kiếm có còn đủ lớn để cần một giải pháp AI thông minh hơn không?"* | Tôi đã sửa gì: Tôi thừa nhận giải pháp No AI (FAQ/Forum có phân loại tag) giải quyết được phần lớn câu hỏi cơ bản; điều này giúp tôi nhận ra C10 chưa có số liệu đo lường cụ thể và khó kiểm chứng impact trong buổi lab. Tôi đã hạ thứ hạng C10 và đồng thuận cùng nhóm chọn C08 vì C08 có quy trình nghiệp vụ rõ ràng, bottleneck cụ thể và đo lường được bằng tiền/cuộc gọi lỗi |
| Gom cluster / cây OST | Cùng Diên gom 12 candidate thành 5 cluster; đưa C10 và C12 vào Cluster B (Tìm lại kiến thức), C11 vào Cluster C (Tài liệu). Góp ý xây dựng cây OST cho C08 tập trung vào 4 opportunity (khó biết lead trùng, khó tra paid, định dạng SĐT không chuẩn, bàn giao đồng thời) | Giúp nhóm tách bạch rõ ràng giữa pain và solution trong cây OST của nhóm (mục 2.3 báo cáo nhóm) |
| Chọn candidate problem | Cùng nhóm thảo luận và chấm điểm shortlist 3 candidate theo 7 tiêu chí; đồng thuận chọn C08 với số điểm cao nhất (28/35) | Nhóm thống nhất chọn C08 làm bài toán chính vì có quy trình rõ ràng và có thể kiểm chứng ngay bằng phỏng vấn người làm marketing thật |
| Kiểm chứng / research | Phần kiểm chứng và research do Tiệp làm chính. Tôi đọc kết quả 2 Interview Snapshot và bảng research để dùng cho CP5 | Phát hiện thời gian thật chỉ 20–50 phút/ngày (không phải 2–3 giờ như card) và ràng buộc file tổng dùng chung; đây là căn cứ để tôi sửa lại quy trình và metric ở mục 4–5 |
| Quy trình nhóm | Người chính CP5: dựng quy trình hiện tại 6 bước theo lời kể của 2 người được phỏng vấn, vẽ quy trình tương lai ở mức Rule, lập bảng before/after | Mục 4 báo cáo nhóm và ảnh `report/assets/cp5-workflow-future.png`. Quy trình tương lai chạy trên sheet kiểm riêng chỉ đọc file tổng, có bước kiểm số hợp lệ, bước người duyệt và phương án quay về |
| Problem Statement | Viết Problem Statement v0 (6 trường); nhờ AI phản biện và ghi lại 5 điểm kèm hướng xử lý | Mục 5 báo cáo nhóm. Metric chính đổi sang số khách bị gọi trùng / nhầm / lỗi mỗi tuần, thời gian kiểm thành metric phụ |
| Mức can thiệp AI | Đánh giá bài toán vào ma trận độ mơ hồ thấp × độ phức tạp thấp; lập luận rằng bước kiểm trùng và tra cứu trạng thái thanh toán chỉ cần Rule (công thức bảng tính), không cần và không nên dùng AI | Nhóm chốt chọn mức Rule, tránh sa đà vào việc xây dựng AI hay Agent phức tạp không cần thiết |
| Quyết định | Cùng nhóm đánh giá 4 rủi ro sản phẩm; đề xuất quyết định Go (pilot nhỏ với Rule) trên 1 nhân viên chạy ads trong 1 tuần và Not Yet với AI. Đề xuất ngưỡng dừng rõ ràng cho pilot | Mục 8 báo cáo nhóm có quyết định thực tế, an toàn và ngưỡng dừng đo lường được |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Sau khi tự scan, nhờ Claude phân tích đề và gợi ý thêm 10 problem theo 4 lăng kính; nhờ rà lại bảng scan theo checklist CP1 | Gợi ý các problem gắn với việc luyện LeetCode/Codeforces và việc nộp lab (dòng #1, #2, #3 bắt nguồn từ gợi ý này); chỉ ra lỗi trong bảng cũ: có chữ "AI" trong cột Job Story, Job Story #9 cũ bị lẫn actor ("tôi gửi PR" nhưng "reviewer muốn") | Các gợi ý chỉ có cột "dấu hiệu cần tự kiểm", không có số liệu thật; một số ý (ví dụ TA chấm repo) cần phỏng vấn người khác mới dùng được | Tự viết lại các dòng giữ lại bằng số liệu của mình (30 phút mỗi tuần, nhắc nhau 3 lần trên Zalo, 3 bài từng AC rồi làm lại vẫn WA như LCS, 5 phút debug mỗi bài WA/TLE, Discord lớp hơn 3000 tin/tuần); bỏ các dòng không có dấu hiệu thật; rút bảng còn 6 dòng |
| CP2 Problem Card | Nhờ Claude dựng 3 Problem Card từ 3 problem tôi chọn (#2, #4, #5) và đóng vai PM hoài nghi phản biện | Chỉ ra card Discord thiếu tần suất (250–300 người là quy mô lớp, chưa phải số người gặp pain); chỉ ra phương án FAQ/Forum có thể đủ mà không cần AI; tách riêng bước dò số liệu ở card slide–báo cáo | Số phút từng bước trong quy trình nháp là AI tự chia từ tổng thời gian tôi ghi, không dựa trên đo thật; AI tự điền cột "Đồng ý?" trong bảng phản biện | Tự chọn 3 problem; kiểm lại số phút từng bước theo trải nghiệm của mình; đưa câu hỏi về FAQ/Forum thành câu hỏi phản biện cho nhóm; giữ card LeetCode ở mức No AI |
| CP4 Research | Không dùng AI ở phần này; phần kiểm chứng và research do Tiệp làm chính | — | — | — |
| CP5 Quy trình | Nhờ Claude dựng bảng quy trình hiện tại / tương lai, viết sơ đồ Mermaid và xuất ảnh sơ đồ | Chuyển mô tả thành sơ đồ nhanh; khi đối chiếu với mục 3, chỉ ra 6 chỗ mục 4–5 chưa khớp kết quả phỏng vấn (baseline thời gian, metric chính, bước kiểm số hợp lệ, file dùng chung, nguồn thanh toán) | Bản đầu viết theo số liệu của card (2–3 giờ/ngày, dò trùng 70 phút) trước khi có phỏng vấn; quy trình tương lai ban đầu cho công thức chạy thẳng trên file tổng dùng chung, trái với ràng buộc người dùng nêu; ảnh sơ đồ đầu tiên quá dài, chữ quá nhỏ | Sửa lại theo kết quả phỏng vấn: baseline 20–50 phút/ngày, công thức chỉ chạy trên sheet kiểm riêng, thêm cờ "CHƯA RÕ" khi không tra được thanh toán; bước 1, 5, 6 ghi "chưa đo" thay vì để AI tự chia số phút; đổi sơ đồ sang bố cục dọc, chữ to hơn |
| CP5–6 Problem Statement | Nhờ Claude phản biện Problem Statement v0 (chỉ ra lỗ hổng, không viết lại) | Chỉ ra metric chính chưa có baseline đo thật, metric gộp 3 loại lỗi khác nguyên nhân, và metric phụ thuộc việc Sales ghi log | AI tự điền luôn cột "Nhóm có đồng ý không?" thay cho nhóm | Giữ target ở mức tạm, sẽ đo log Sales 1 tuần trước khi chốt; tách log theo loại lỗi; cột đồng ý cần cả nhóm xác nhận lại |
| CP6 Mức can thiệp / quyết định | Nhờ Claude phản biện lý do chọn Rule thay vì Workflow/AI và kiểm tra tính khả thi của 4 rủi ro sản phẩm | Chỉ ra rủi ro bản đọc file tổng có độ trễ (delay) và cảnh báo việc phụ thuộc vào sự hợp tác của Sales để có số liệu đo lường | AI có xu hướng "vẽ" thêm tính năng AI dự đoán độ tiềm năng của lead (lead scoring) dù bài toán nhóm chỉ là kiểm trùng và thanh toán | Bác bỏ hoàn toàn gợi ý lead scoring của AI; giữ vững phạm vi hẹp ở mức Rule cho việc chuẩn hóa SĐT, kiểm trùng và tra paid; đưa rủi ro độ trễ vào quy trình (làm mới sheet kiểm trước khi dán) |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi nhận ra các bài toán vận hành gắn với doanh nghiệp như lọc lead (C08) hay bảng lương kế toán (C07) có tính cấp thiết và thiệt hại thực tế lớn hơn nhiều so với các khó khăn học tập cá nhân (như lỗi Discord hay slide của tôi). Một problem tốt không chỉ đo bằng số người gặp, mà phải đo bằng "chi phí nếu không giải quyết" (impact).

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, ban đầu nhóm định viết script tự động hóa hoặc làm bot AI đẩy lead vào Telegram. Nhóm chỉ "tỉnh ngộ" khi phỏng vấn người thật và biết rằng: file tổng là tài nguyên dùng chung, nghiêm cấm chạy script trực tiếp vì sợ làm hỏng dữ liệu của người khác. Nhóm lập tức dừng bàn về AI, chuyển sang thiết kế sheet kiểm riêng chỉ đọc.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, tôi đã rút Card C10 (tìm lỗi Discord). Ban đầu tôi rất thích vì bản thân hay gặp, nhưng bạn Diên phản biện rằng một Forum channel hay FAQ ghim sẵn (No AI) có thể giải quyết 80% vấn đề mà không cần công cụ mới. Tôi nhận thấy C10 khó đo lường và thiếu impact bằng C08, nên đã đổi ý sang ủng hộ C08.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Bất ngờ nhất là thời gian lọc lead thực tế chỉ mất 20–50 phút/ngày chứ không phải 2–3 giờ như card ước lượng. Nỗi đau lớn nhất của họ là cuộc gọi lỗi (gọi trùng, nhầm khách đã mua, số sai) khiến Sales phàn nàn. Phát hiện này buộc tôi phải đổi toàn bộ trọng tâm ở CP5: đưa thời gian về metric phụ và lấy số cuộc gọi lỗi làm metric chính.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là viết Boundary và Success Metric. Rất dễ bị quán tính đưa giải pháp vào mô tả vấn đề. Ngoài ra, việc xác định rõ công cụ không được tự ý xóa lead hay đổi trạng thái thanh toán (Boundary) và tách biệt giữa metric chính (log cuộc gọi lỗi của Sales) với metric phụ (thời gian kiểm) đòi hỏi phải bám rất sát thực tế phỏng vấn.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ thúc đẩy nhóm đi phỏng vấn người thật sớm hơn để không tốn thời gian tranh luận trên số liệu giả định. Tôi cũng sẽ phản biện mạnh hơn về trường hợp một khách hàng dùng 2 số điện thoại khác nhau hoặc số người thân. Rule công thức chắc chắn bỏ sót ca này, nên cần quy trình duyệt ngoại lệ rõ ràng hơn.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

1. **Problem:** Người chạy quảng cáo phải tự kiểm tay lead trùng và khách đã thanh toán trên file dùng chung trước khi bàn giao cho Sales, dẫn đến việc Sales vẫn gọi trùng, gọi nhầm khách đã mua hoặc gọi vào số sai (1–2 khách mỗi 1–2 ngày).
2. **Quy trình:** Nhóm thiết lập quy trình mới gồm 8 bước, đưa việc chuẩn hóa số điện thoại, kiểm tra số hợp lệ, kiểm trùng và tra cứu trạng thái thanh toán sang một sheet kiểm riêng chỉ đọc dữ liệu từ file tổng chung.
3. **Metric:** Thành công được đo bằng việc giảm số khách bị gọi lỗi từ 1–2 khách/ngày xuống dưới 1 khách/tuần (đo bằng log phản hồi của Sales) và giảm thời gian kiểm tra dữ liệu xuống dưới 20 phút/ngày (đo bằng bấm giờ).
4. **Boundary:** Hệ thống chỉ được đọc dữ liệu file tổng chứ tuyệt đối không được ghi, sửa hay xóa trên file chung; không tự ý xóa lead; mọi lead có nghi vấn hoặc không tra được thanh toán phải gắn cờ "CHƯA RÕ" để con người duyệt trước khi bàn giao.
5. **Mức can thiệp AI:** Nhóm chọn mức **Rule** (dùng các hàm chuẩn hóa REGEXREPLACE, kiểm trùng COUNTIF và tra cứu XLOOKUP) vì bài toán thuần túy là đối chiếu logic xác định, hoàn toàn không cần AI dự đoán hay sinh nội dung.
6. **Quyết định:** Nhóm quyết định **Go cho pilot nhỏ dùng Rule** (thử nghiệm trên 1 nhân sự chạy quảng cáo trong 1 tuần) và **Not Yet đối với việc ứng dụng AI**, kèm ngưỡng dừng nếu sau 1 tuần tỉ lệ gọi lỗi không giảm thì quay về quy trình cũ để đánh giá lại nguyên nhân.

---

## 7. Tài liệu tham khảo

- Đề bài lab: `README.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `docs/01-worksheet.md`, `docs/02-deliverable-example.md`.
- Báo cáo nhóm `report/team/group_report.md`, mục 3 (kết quả phỏng vấn và research dùng cho CP5).
