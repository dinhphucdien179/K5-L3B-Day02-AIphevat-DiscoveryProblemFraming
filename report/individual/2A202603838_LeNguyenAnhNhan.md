# Báo cáo cá nhân — 2A202603838_LeNguyenAnhNhan

> Tham chiếu thống nhất: [báo cáo nhóm](../team/group_report.md) cho candidate, số liệu và quyết định; [TEAM.md](../../TEAM.md) cho vai trò và phân công. C04–C06 là ba card cá nhân; C08 là bài toán nhóm được dùng cho CP6. Các thời gian của card là ước lượng, chưa phải số đo thực nghiệm.

## 1. Thông tin học viên

- Họ tên: Lê Nguyễn Anh Nhân
- MSSV: 2A202603838
- Tên nhóm: AIphevat
- Tài khoản GitHub: ying684
- Vai trò theo TEAM.md: người chính CP6 — mức can thiệp, Problem Statement v1, eval và quyết định; bổ sung mục 9 — hạn chế và hướng tiếp theo.
- Link repo nhóm: https://github.com/dinhphucdien179/K5-L3B-Day02-AIphevat-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Bảng chính giữ 8 problem có mô tả trải nghiệm và dấu hiệu định lượng ước tính. Hai ý bổ sung chưa có dấu hiệu thật được tách bên dưới, không dùng để tính đủ 10 problem hoặc nhận bonus B1.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại · Pain từ người khác | Khi kết thúc buổi dạy, tôi muốn chuẩn bị giáo án và tài liệu cho buổi tiếp theo, để hoàn tất công việc giảng dạy đúng hạn | Giáo viên, đặc biệt là người đang chuyển sang công cụ số | Quan sát công việc của mẹ: diễn ra sau buổi dạy. Kịch bản C05 thống nhất với báo cáo nhóm: ước tính 80 phút/buổi, trong đó soạn nội dung 25 phút và thao tác công cụ 10 phút; chưa bấm giờ. |
| 2 | Tốn thời gian | Khi nhận PDF scan cần chỉnh sửa, tôi muốn lấy được bản Word có thể biên tập, để tránh nhập lại nội dung | Giáo viên thường xử lý tài liệu học tập | Mẹ gặp tình huống này nhiều lần. Kịch bản C04 thống nhất với báo cáo nhóm: ước tính 35 phút/tài liệu ngắn khi phải nhập lại; chưa có file thử hoặc nhật ký thời gian. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi soạn bài, tôi muốn tìm và chắt lọc tài liệu tham khảo phù hợp, để dành thời gian cho việc chuẩn bị nội dung | Giáo viên | Quan sát mẹ thường tìm tài liệu sau mỗi buổi dạy. Ước tính 15–25 phút/lần; chưa đo thực tế. |
| 4 | Tốn thời gian | Khi cần đến một nơi chưa quen ở Hà Nội, tôi muốn chọn được tuyến và phương tiện phù hợp, để chủ động di chuyển | Sinh viên mới chuyển đến Hà Nội | Trải nghiệm cá nhân sau khi chuyển từ TP.HCM ra Hà Nội. Kịch bản C06 thống nhất với báo cáo nhóm: ước tính 25 phút/lần tìm tuyến mới, cụm bước 3–5 chiếm 18 phút; chưa bấm giờ. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi cần làm thủ tục ở trường, tôi muốn biết đúng phòng ban và địa điểm, để tránh đi nhầm hoặc phải hỏi nhiều nơi | Sinh viên mới nhập học, sinh viên ngoại tỉnh | Từng phải tìm hiểu nơi liên hệ trong môi trường mới. Ước tính 10–20 phút/lần; chưa có log hoặc số đo. |
| 6 | Tốn thời gian | Khi tìm chỗ ăn phù hợp ngân sách ở thành phố mới, tôi muốn so sánh giá và vị trí, để chọn nhanh hơn | Sinh viên mới chuyển đến thành phố | Ước tính 10–15 phút/lần tìm và so sánh; cần ghi nhận thực tế. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm chỗ ở, tôi muốn đối chiếu các tin đăng từ nhiều nền tảng, để đánh giá giá thuê và vị trí trước khi liên hệ | Sinh viên ngoại tỉnh, người mới chuyển đến thành phố | Tin đăng nằm trên nhiều kênh; người tìm phải tự đối chiếu. Ước tính 30–60 phút/phiên; chưa ghi nhận tần suất. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi mới chuyển đến thành phố, tôi muốn tìm tiện ích thiết yếu gần nơi ở, để sớm ổn định sinh hoạt | Sinh viên ngoại tỉnh, người mới chuyển đến thành phố | Dựa trên trải nghiệm tự tìm tiện ích ở Hà Nội. Ước tính 10–20 phút/lần; chưa bấm giờ. |

---

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

Tôi dùng AI để mở rộng scan từ công việc của mẹ và trải nghiệm chuyển đến Hà Nội. Tôi giữ các gợi ý về địa điểm làm thủ tục và tiện ích trong phạm vi trải nghiệm đã mô tả; số phút vẫn là ước lượng, không phải kết quả phỏng vấn hay bấm giờ. Tôi bỏ hướng “ứng dụng tổng hợp mọi thứ” vì chưa có một tác vụ ưu tiên hoặc nguồn dữ liệu rõ ràng.

Hai ý chưa đưa vào bảng scan chính:

| Ý gợi mở | Vì sao chưa giữ làm problem đủ bằng chứng? | Cần kiểm chứng gì? |
|---|---|---|
| Người hỗ trợ sinh viên mới phải hướng dẫn lại thủ tục hoặc địa điểm nhiều lần. | AI gợi ý mở rộng từ nhu cầu tìm địa điểm; chưa có số lần hỏi lại hoặc thời gian hướng dẫn. | Hỏi người hỗ trợ về tình huống gần nhất và ghi số lần/thời gian thực tế. |
| Người đi chơi cần đối chiếu giờ hoạt động, giao thông và lượng khách trước chuyến đi. | Chưa có baseline hoặc nguồn dữ liệu được kiểm tra cho tình huống này. | Ghi lại một lần lên kế hoạch thật, nguồn đã dùng và phần thông tin gây khó quyết định. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

Đối chiếu theo mục 2.1 và 2.4 báo cáo nhóm. Rank bên dưới là thứ tự ba card cá nhân; hạng trong 12 candidate của nhóm là một bảng xếp hạng khác.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | C04 — Chuyển PDF scan thành tài liệu có thể chỉnh sửa | Mẹ gặp tình huống này; có thể đo thời gian xử lý và lỗi nội dung. | Kịch bản 35 phút/tài liệu; chưa có file thử, chưa xác nhận tần suất và độ dài điển hình. |
| 2 | C05 — Chuẩn bị giáo án điện tử sau buổi dạy | Công việc lặp lại; có thể quan sát và chia thời gian theo từng bước. | Kịch bản 80 phút/buổi, soạn nội dung 25 phút và thao tác công cụ 10 phút; chưa đo trực tiếp. |
| 3 | C06 — Tìm tuyến đường khi mới đến Hà Nội | Xuất phát từ trải nghiệm cá nhân; các bước tìm tuyến và đối chiếu phương tiện có thể quan sát. | Kịch bản 25 phút/lần, cụm bước 3–5 là 18 phút; chưa xác nhận mức phổ biến. |

| Card cá nhân | ID trong báo cáo nhóm | Baseline ước lượng thống nhất | Điểm / hạng trong 12 candidate |
|---|---|---|---|
| #1 — PDF scan sang Word | C04 | 35 phút/tài liệu ngắn | 21/35, hạng 8 |
| #2 — Giáo án điện tử | C05 | 80 phút/buổi; soạn nội dung 25 phút, thao tác công cụ 10 phút | 19/35, hạng 10 |
| #3 — Tìm tuyến mới | C06 | 25 phút/lần; bước 3–5 tổng 18 phút | 19/35, hạng 11 |

Các mốc 60–120 phút/tài liệu và 120–180 phút/buổi trong bản cá nhân trước được thay bằng kịch bản C04–C05 ở báo cáo nhóm để tránh hai baseline song song. Đây là thống nhất tài liệu theo nguồn nhóm, không phải kết quả đo mới. Target ở từng card dưới đây là đề xuất cá nhân, chưa phải target C08 của nhóm.

### Problem Card #1 — C04: Chuyển đổi tài liệu PDF scan sang Word

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận PDF scan cần chỉnh sửa, tôi muốn chuyển nội dung sang Word có thể biên tập, để tránh nhập lại từ đầu |
| Actor | Giáo viên, cụ thể là mẹ tôi |
| Thời điểm / bối cảnh | Khi nhận tài liệu scan phục vụ soạn giáo án hoặc tham khảo. Tần suất cụ thể chưa ghi lại. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận/mở scan (2 phút). 2. Tìm công cụ (3 phút). 3. Thử chuyển đổi (2 phút). 4. Kiểm khả năng chỉnh sửa (3 phút). 5. Nhập lại khi không xuất được hoặc bản chuyển không dùng được (18 phút). 6. Kiểm tra, định dạng và lưu (7 phút). Tổng ước lượng 35 phút. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5 — nhập lại nội dung: 18 phút, dài nhất trong kịch bản 35 phút; bước kiểm tra/định dạng sau đó là 7 phút, được tính riêng. |
| Impact (nếu không giải thì sao) | Thời gian nhập liệu lặp lại làm giảm thời gian chuẩn bị nội dung. Lỗi OCR hoặc nhập tay có thể làm sai chữ, số liệu và định dạng. |
| Success metric (baseline → target) | Baseline ước lượng 35 phút/tài liệu ngắn → target đề xuất ≤20 phút. Bấm giờ trên cùng loại tài liệu từ lúc mở file đến khi DOCX được duyệt; đối chiếu chữ, số và bảng với bản gốc, ghi lỗi còn sót. Chưa có kết quả đo hoặc file thử. |
| Phương án không dùng AI | Xin file Word gốc; nếu không có, nhập tay theo mẫu Word có sẵn và kiểm đối chiếu. Công cụ OCR được xem xét riêng ở giả thuyết AI, không coi OCR là phương án chắc chắn không dùng AI. |
| Giả thuyết về AI (nếu có) | OCR có thể tạo bản nháp DOCX từ scan. Thử trên bản sao đã được phép xử lý; kiểm tra chữ tiếng Việt, số liệu, bảng và bố cục. Người dùng phải duyệt trước khi sử dụng; nếu lỗi vượt mức chấp nhận thì quay lại nhập/sửa thủ công. |
| Cảm nhận nhanh | **Workflow có OCR; chưa có cơ sở để dùng LLM.** |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ƯỚC TÍNH KHOẢNG 35 PHÚT/TÀI LIỆU

[1. Nhận và mở PDF scan: 2']
                 |
                 v
[2. Tìm công cụ chuyển đổi: 3']
                 |
                 v
[3. Tải PDF và chuyển đổi: 2']
                 |
                 v
[4. Kiểm tra file và khả năng chỉnh sửa: 3']
                 |
                 v
[5. Công cụ miễn phí không hỗ trợ xuất DOCX
    => Tự nhập lại nội dung: 18']  <-- BOTTLENECK
                 |
                 v
[6. Kiểm tra, chỉnh sửa và định dạng: 7']

TỔNG: 35 PHÚT/TÀI LIỆU

Lưu ý: Đây là kịch bản ước tính cho tài liệu ngắn khi phải nhập lại, thống nhất với CP1 và C04 trong báo cáo nhóm; cần đo trên tài liệu mẫu.
```

### Problem Card #2 — C05: Giáo viên thích nghi với quy trình soạn giáo án điện tử

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết thúc buổi dạy, tôi muốn chuẩn bị giáo án và tài liệu cho buổi tiếp theo, để hoàn tất công việc đúng hạn |
| Actor | Giáo viên, cụ thể là mẹ tôi |
| Thời điểm / bối cảnh | Sau buổi dạy, khi chuẩn bị cho bài tiếp theo và hoàn thiện tài liệu số. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định nội dung (5 phút). 2. Tìm tài liệu (15 phút). 3. Đọc/ghi chú (15 phút). 4. Soạn giáo án (25 phút). 5. Thao tác công cụ trực tuyến (10 phút). 6. Kiểm tra/sửa (7 phút). 7. Hoàn thiện/tải lên (3 phút). Tổng ước lượng 80 phút. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 — soạn nội dung giáo án: 25 phút, dài nhất trong kịch bản 80 phút. Bước thao tác công cụ là 10 phút, cần đo riêng để phân biệt khó khăn chuyên môn với khó khăn thao tác. |
| Impact (nếu không giải thì sao) | Thời gian chuẩn bị kéo dài ngoài giờ dạy; nội dung vẫn cần đáp ứng yêu cầu chuyên môn và định dạng nộp bài. |
| Success metric (baseline → target) | Baseline ước lượng 80 phút/buổi → target đề xuất ≤60 phút/buổi. Bấm giờ từng bước trên các bài có mức độ tương đương, tính cả công kiểm/sửa; giáo viên xác nhận đủ mục chuyên môn và định dạng bắt buộc. Target chưa được kiểm chứng hoặc nhóm chốt. |
| Phương án không dùng AI | Dùng mẫu giáo án thống nhất, thư viện tài liệu có phân loại và checklist nộp bài; chuẩn hóa thao tác trên nền tảng. |
| Giả thuyết về AI (nếu có) | Có thể thử AI để tìm ý chính trong tài liệu được phép dùng và tạo nháp theo mẫu. Chỉ dùng nguồn đã kiểm tra, giữ liên kết nguồn; giáo viên duyệt và chỉnh sửa trước khi nộp. So sánh với quy trình template không AI; dừng nếu không giảm thời gian hoặc làm giảm chất lượng. |
| Cảm nhận nhanh | **Workflow hỗ trợ soạn nháp; giáo viên chịu trách nhiệm duyệt.** |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ƯỚC TÍNH KHOẢNG 80 PHÚT/BUỔI CHUẨN BỊ

[1. Xác định nội dung bài học: 5']
                 |
                 v
[2. Tìm tài liệu tham khảo: 15']
                 |
                 v
[3. Đọc tài liệu và take note: 15']
                 |
                 v
[4. Soạn nội dung giáo án: 25']  <-- BOTTLENECK
                 |
                 v
[5. Thao tác công cụ trực tuyến: 10']
                 |
                 v
[6. Kiểm tra và chỉnh sửa: 7']
                 |
                 v
[7. Hoàn thiện, tải tài liệu lên: 3']

TỔNG: 80 PHÚT

Lưu ý: Thời gian là baseline ước tính từ mô tả công việc,
chưa được đo trực tiếp bằng đồng hồ.
```

### Problem Card #3 — C06: Sinh viên mới đến Hà Nội khó tìm kiếm thông tin đi lại

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần đến nơi chưa quen ở Hà Nội, tôi muốn so sánh tuyến đường và phương tiện, để chọn cách đi phù hợp với thời gian và chi phí |
| Actor | Sinh viên từ TP.HCM hoặc các tỉnh/thành phố khác chuyển đến Hà Nội |
| Thời điểm / bối cảnh | Khi mới đến Hà Nội hoặc đi đến một địa điểm chưa quen. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định điểm đi/đến (2 phút). 2. Tra địa điểm trên bản đồ (4 phút). 3. Tìm tuyến xe buýt/metro (7 phút). 4. So sánh thời gian, chi phí, chuyển tuyến (6 phút). 5. Kiểm tra thông tin phương tiện và đường đi (5 phút). 6. Chọn tuyến (1 phút). Tổng ước lượng 25 phút. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — tìm tuyến: 7 phút, dài nhất trong kịch bản. Cả cụm bước 3–5 (tìm, so sánh, xác minh) là 7 + 6 + 5 = 18 phút, đúng với C06 trong báo cáo nhóm; 13 phút chỉ là bước 3–4, không đại diện cả cụm. |
| Impact (nếu không giải thì sao) | Người mới đến có thể mất thêm thời gian chọn tuyến hoặc phải đổi kế hoạch khi thông tin chưa rõ. Mức độ xảy ra chưa được thống kê. |
| Success metric (baseline → target) | Ước tính 25 → tối đa 15 phút/lần tìm tuyến mới. Đo trên các chuyến đi tương đương; kiểm tra tuyến, giờ hoạt động và nguồn dữ liệu trước khi sử dụng. |
| Phương án không dùng AI | Dùng bản đồ và ứng dụng/website chính thức của đơn vị vận tải; lưu các tuyến đã xác minh để dùng lại. |
| Giả thuyết về AI (nếu có) | Chưa có lý do rõ để AI thay thế bộ định tuyến. Nếu thử AI, giới hạn vai trò ở việc diễn giải yêu cầu và trình bày các tuyến lấy từ nguồn cập nhật; không tự sinh thông tin tuyến hoặc tình trạng giao thông. Hiển thị nguồn và thời điểm cập nhật, có phương án quay về bản đồ khi dữ liệu thiếu hoặc cũ. |
| Cảm nhận nhanh | **Rule / Workflow; chưa cần Agent.** |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ƯỚC TÍNH KHOẢNG 25 PHÚT/LẦN TÌM TUYẾN MỚI

[1. Xác định điểm xuất phát và điểm đến: 2']
                 |
                 v
[2. Tìm địa điểm trên bản đồ: 4']
                 |
                 v
[3. Tìm tuyến xe buýt / metro: 7']  <-- BOTTLENECK
                 |
                 v
[4. So sánh thời gian, chi phí, phương tiện: 6']
                 |
                 v
[5. Kiểm tra thông tin và tình trạng đường đi: 5']
                 |
                 v
[6. Chọn phương án di chuyển: 1']

TỔNG: 25 PHÚT

Lưu ý: Đây là ước tính cho một chuyến đi đến địa điểm chưa quen,
không phải thời gian tìm kiếm cho mọi chuyến đi hằng ngày.
```

### Card muốn pitch nhất

- Card số: **3**
- Vì sao:

Tôi chọn card #3 vì đây là khó khăn tôi từng gặp khi chuyển từ TP.HCM ra Hà Nội. Tôi muốn kiểm tra xem thời gian chủ yếu mất ở bước tìm tuyến, so sánh phương tiện hay xác minh thông tin. Trước mắt, phạm vi chỉ là tìm tuyến cho một chuyến đi; chưa mở rộng sang ăn uống, lưu trú hay tiện ích.

- Câu hỏi muốn nhóm phản biện:

Khó khăn nằm ở việc thiếu tuyến phù hợp hay ở thông tin bị phân tán/khó xác minh? Dùng bản đồ và nguồn vận tải hiện có đã đủ giải quyết chưa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline ban đầu chưa được đo và có số liệu lệch giữa card, sơ đồ, báo cáo nhóm | Đồng ý | Thống nhất C04 = 35 phút, C05 = 80 phút và C06 = 25 phút theo báo cáo nhóm; sửa bottleneck C05 thành 25 phút, cụm bước 3–5 C06 thành 18 phút; tất cả vẫn ghi là ước lượng cần đo. |
| Card giáo án gộp nhiều bước | Đồng ý | Tách các bước và xem thời gian soạn là giả thuyết bottleneck, chưa phải kết luận. |
| Card đi lại quá rộng | Đồng ý | Giới hạn vào tìm và chọn tuyến cho một chuyến đi chưa quen. |
| AI không tự có dữ liệu giao thông trực tiếp | Đồng ý | Chỉ xem xét dữ liệu có nguồn và thời điểm cập nhật; không để mô hình tự tạo thông tin vận hành. |
| Chưa chứng minh AI tốt hơn cách hiện tại | Đồng ý | Bổ sung phương án không AI và tiêu chí so sánh; ưu tiên giải pháp đơn giản nếu đạt mục tiêu. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Chuẩn bị 3 card ở mục 3: chuyển PDF scan sang Word, soạn giáo án điện tử và tìm tuyến khi mới đến Hà Nội; card ưu tiên là #3. | Ba candidate tương ứng C04–C06 trong mục 2.1 báo cáo nhóm. Đây là nội dung chuẩn bị có trong hồ sơ, không bổ sung diễn biến buổi pitch. |
| Phản biện bài của bạn khác | Câu hỏi rà soát CP6 đối với hướng Rule ở CP5: “Nếu chỉ chuẩn hóa cách nhập và dùng checklist thì đã đủ chưa? Vì sao cần Rule?” | Mục 6.2 bổ sung No AI + checklist làm đối chứng; mục 8 quy định quay về No AI nếu đạt cùng target với ít công hơn. Câu hỏi này thuộc lượt rà soát CP6, không gán thành câu đã hỏi một thành viên tại CP3. |
| Nhận phản biện | Sử dụng 5 điểm phản biện v0 đã ghi ở mục 5 báo cáo nhóm: baseline chưa đo, gộp loại lỗi, phụ thuộc log Sales, khả năng No AI đủ và bản đọc file tổng trễ. | V1 tách nhãn lỗi, quy định mẫu số/cách đo, giới hạn của kiểm định dạng, người duyệt và điều kiện nguồn dữ liệu; không tự nhận các phản biện v0 là do mình tạo ra. |
| Gom cluster / cây OST | Đọc kết quả hội tụ CP3 để hiểu nguồn candidate và outcome của C08; không chỉnh sửa phần này trong lượt làm CP6. | Giữ CP6 tập trung vào kiểm lead trước bàn giao, không mở rộng sang CRM, lead scoring hoặc tự động gọi. |
| Chọn candidate problem | Dùng C08 đã có trong báo cáo nhóm làm đầu vào cho CP6; đối chiếu lại với kết quả CP4. | Không chọn lại candidate hoặc sửa bảng chấm điểm của CP3. |
| Kiểm chứng / research | Sử dụng hai Interview Snapshot và bảng research do Tiệp phụ trách ở CP4 làm căn cứ phân tích; lượt rà soát đã mở lại 5 trang tài liệu chính thức trong bảng research, không thực hiện thêm phỏng vấn. | Phân biệt số liệu card với số tự thuật sau phỏng vấn; kiểm tra link và chức năng công cụ không thay thế việc xác nhận quyền dữ liệu, độ trễ nguồn và hiệu quả pilot. |
| Quy trình nhóm | Đọc quy trình và v0 do Nghĩa phụ trách ở CP5; xác định các điểm kiểm được bằng Rule và phần vẫn cần người duyệt để viết CP6. | V1 bám mô tả sheet kiểm riêng chỉ đọc ở mục 4.2; không sửa mục 4–5 hoặc ảnh của CP5. |
| Problem Statement | Phụ trách v1 tại mục 7: đủ 9 trường, bảng thay đổi từ v0, quy ước đo và 5 tiêu chí đánh giá đầu ra Rule. | Làm rõ lỗi định dạng khác lỗi đúng chủ số; thêm tỷ lệ lỗi, điều kiện đo và người kiểm tra; AI intervention point ghi Không có kèm lý do. |
| Mức can thiệp AI | Phụ trách mục 6: ma trận, so sánh 4 mức, lý do chọn Rule và chưa cần mức cao hơn; áp dụng ngoại lệ No AI/Rule của worksheet/rubric. | Chọn Rule để kiểm chứng; không thêm AI dự đoán vào bài toán đối chiếu xác định. |
| Quyết định | Phụ trách mục 8: đánh giá 4 rủi ro, chọn Not Yet cho triển khai thật, nêu việc cần kiểm chứng, pilot có điều kiện và ngưỡng dừng. | Tách lựa chọn Rule khỏi quyền triển khai; chỉ xét Go sau khi chốt quyền dữ liệu, nguồn hiện hành, người duyệt/ghi log và kiểm thử mẫu. |
| Hạn chế và hướng tiếp theo | Bổ sung mục 8.3 và mục 9 theo phần việc mở rộng: cách xét lại quyết định, giới hạn bằng chứng, rủi ro nhập đồng thời và thứ tự kiểm chứng. | Đầu ra tiếp theo được ghi thành kế hoạch có điều kiện; không coi pilot một người là bằng chứng đã giải quyết việc nhiều người cùng bàn giao. |
| Rà soát tính nhất quán và dẫn chứng | Dùng báo cáo nhóm và TEAM.md làm chuẩn để đồng bộ C04–C06, vai trò CP6, quyết định và lịch kiểm chứng; bổ sung sơ đồ CP6 và bảng truy nguồn. | Báo cáo cá nhân thống nhất các mốc 35/80/25 phút; phần CP6 liên kết trực tiếp tới snapshot, ảnh phỏng vấn và căn cứ rubric. |

**Dẫn chứng đối chiếu:**

- [Báo cáo nhóm — danh mục C04–C06 và xếp hạng](../team/group_report.md#21-danh-mục-chuẩn-bị-pitch): nguồn chuẩn cho ba card cá nhân; điểm/hạng ở mục 2.4.
- [TEAM.md — phần của Nhân](../../TEAM.md#lenguyenanhnhan-2a202603838): vai trò người chính CP6, người hỗ trợ và phần bổ sung mục 9.
- [Báo cáo nhóm — hai Interview Snapshot](../team/group_report.md#32-kiểm-chứng), kèm [ảnh 1](../assets/cp4-interview-1.jpg) và [ảnh 2](../assets/cp4-interview-2.jpg): dữ liệu đầu vào cho phân tích, do phần CP4 cung cấp.
- [Sơ đồ CP6](../team/group_report.md#65-sơ-đồ-phạm-vi-rule-và-người-kiểm-tra): hình minh họa Rule/người duyệt, không phải kết quả triển khai.
- [V1 và bảng truy nguồn](../team/group_report.md#7-problem-statement-v1--tiêu-chí-đánh-giá-cp6), [quyết định](../team/group_report.md#8-quyết-định-cp6), [hạn chế và hướng tiếp theo](../team/group_report.md#9-hạn-chế-và-hướng-tiếp-theo): sản phẩm phần việc được giao.

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Theo nhật ký đã có ở mục 2, dùng AI mở rộng scan từ công việc của mẹ và trải nghiệm chuyển đến Hà Nội; sau đó đối chiếu số liệu theo báo cáo nhóm. | Gợi thêm góc nhìn và phát hiện baseline không thống nhất giữa scan/card/bài nhóm. | Một số candidate chưa có dấu hiệu đo thật; hướng “ứng dụng tổng hợp mọi thứ” quá rộng. | Giữ trạng thái cần xác minh cho ý chưa có bằng chứng; chuẩn hóa ba kịch bản C04–C06 theo báo cáo nhóm thành 35/80/25 phút, không tự coi là số đo mới. |
| CP2 Problem Card | Dùng AI phản biện baseline, phạm vi và nhu cầu dùng AI; rà lại từng trường theo C04–C06 trong bài nhóm. | Phát hiện card giáo án ghi 120 phút soạn/180 phút tổng nhưng sơ đồ là 25/80; card đi lại chưa tách cụm 18 phút. | Số liệu AI diễn đạt không nhất quán; đề xuất dùng AI chưa chứng minh tốt hơn công cụ sẵn có. | Sửa C05 thành 25 phút soạn/80 phút tổng, C06 thành bước 3–5 tổng 18 phút; thống nhất số bước bảng/sơ đồ và giữ target là đề xuất cần kiểm chứng. |
| CP4 Research | Dùng Codex đọc research và snapshot có sẵn; lượt rà soát mở lại 5 trang chính thức được liên kết ở mục 3.3. | Xác nhận các link truy cập được, đối chiếu chức năng công thức và quy tắc xử lý trùng để củng cố CP6. | Có công thức hoặc công cụ CRM không chứng minh đã có quyền lấy dữ liệu hay giải pháp đã chạy ở môi trường người dùng. | Không tự nhận thực hiện phỏng vấn CP4; giữ quyền đọc, nguồn cập nhật và thử mẫu là điều kiện trước pilot. |
| CP5 Quy trình | Dùng Codex đọc quy trình và v0 làm đầu vào CP6; không tạo lại sản phẩm CP5. | Xác định điểm đặt Rule và phần con người kiểm tra. | Ảnh sơ đồ CP5 và mô tả mục 4.2 khác nhau về sheet riêng/cách bàn giao; không thể coi cả hai là đặc tả triển khai đồng nhất. | CP6 nêu rõ phạm vi theo mô tả mục 4.2: sheet riêng chỉ đọc, con người nhập theo thao tác hiện hành; giữ nguyên sản phẩm CP5 trong lượt này. |
| CP5–6 Problem Statement | Dùng Codex hỗ trợ rà v0, soạn v1 và tiêu chí đánh giá trong phạm vi CP6 được giao. | Làm rõ cách đếm khách, tách loại lỗi, mẫu số, thời gian kiểm và giới hạn Rule. | Dễ xem số hợp lệ là đúng khách, lấy ước lượng phỏng vấn làm baseline đã đo hoặc viết mục tiêu như kết quả đạt được. | Nội dung v1 ghi rõ số ước lượng, kế hoạch đo baseline, target tạm và không có AI intervention point; không bổ sung số liệu thực nghiệm. |
| CP6 Mức can thiệp / quyết định | Giao Codex hỗ trợ phân tích, tự rà soát và soạn mục 6–9; đối chiếu worksheet/rubric, thêm sơ đồ Mermaid và bảng truy nguồn. | So sánh mức đơn giản hơn, kiểm tra sự nhất quán giữa rủi ro, Not Yet, điều kiện pilot và ngưỡng dừng. | Không thể từ hồ sơ hiện tại suy ra người quản lý đã cấp quyền, Sales đã nhận ghi log hoặc pilot đã thành công. | Bản báo cáo ghi các việc đó là điều kiện tương lai; không ghi thành cam kết/kết quả đã có. Việc giao AI soạn nội dung được khai rõ, không mô tả là chỉ hỏi phản biện. |
| CP7 Hồ sơ cá nhân | Theo yêu cầu trong lượt làm này, dùng Codex hỗ trợ soạn mục 4–6 từ tài liệu sẵn có và phân tích CP6. | Tổng hợp đóng góp, bài học về metric, boundary và quyết định. | AI không biết trải nghiệm trao đổi hoặc cảm xúc cá nhân ngoài thông tin đã cung cấp. | Chỉ viết nhận xét dựa trên hồ sơ, không dựng đối thoại, người hỏi, buổi họp hoặc phỏng vấn mới; mục 6 là nội dung có AI hỗ trợ soạn. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Từ việc đọc top 3 problems của các bạn, tôi thấy các bối cảnh rất khác nhau nhưng đều cần làm rõ actor, một bước nghẽn cụ thể và bằng chứng về impact. Với C08, quy trình bàn giao sang Sales giúp nhìn thấy hậu quả của lỗi dữ liệu, thay vì chỉ quan tâm người lọc lead mất bao lâu. Điều tôi rút ra cho CP6 là không chọn mức can thiệp theo mức hấp dẫn của ý tưởng; phải xem cách đơn giản nhất có thể xử lý đúng phần nghẽn hay chưa.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Điểm cần tránh khi hoàn thiện CP6 là thấy việc kiểm trùng rồi lập tức thêm AI hoặc tự động hóa toàn bộ bàn giao. Kết quả CP4 cho biết người dùng đang vướng file tổng dùng chung; thêm công cụ mà không xét quyền đọc và tác động tới người khác sẽ chưa giải đúng ràng buộc. Vì vậy, phần CP6 giới hạn Rule trên sheet riêng, chỉ gắn cờ và để người vận hành quyết định. Không bổ sung lead scoring hoặc giao Agent tự tìm và sửa dữ liệu.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Điểm tôi điều chỉnh trong lập luận CP6 là tách “Rule phù hợp” khỏi “đủ điều kiện Go”. Phản biện v0 đã ghi rõ baseline chưa đo và kết quả phụ thuộc Sales ghi log. Khi đối chiếu với các giả định về quyền dữ liệu còn chưa xác nhận ở CP4, phương án nhất quán hơn là Not Yet với triển khai thật, đồng thời giữ Rule để kiểm chứng. Đây là điều chỉnh trong phân tích từ tài liệu, không phải một cuộc đối thoại được bổ sung cho buổi pitch.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điểm nổi bật khi đối chiếu là thời gian từ card 2–3 giờ/ngày chuyển xuống khoảng 20–50 phút/ngày theo phỏng vấn và quy đổi của nhóm. Nếu CP6 vẫn lấy số cũ, lợi ích thời gian sẽ bị phóng đại. Một điểm nữa là số điện thoại sai trong lần gọi lỗi gần nhất không đồng nghĩa với số sai định dạng. Rule có thể kiểm cách ghi và khớp khóa nhưng không bảo đảm số đó thuộc đúng khách; vì vậy cần giữ lỗi này trong log và ghi rõ giới hạn giải pháp.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là viết metric đủ chặt khi chưa có baseline đo bằng log. V1 cần giữ rõ điều đã biết, ước lượng và việc sẽ đo, đồng thời không đếm trùng một khách có nhiều loại lỗi. Tôi bổ sung tỷ lệ lỗi theo số khách đã gọi để tránh kết luận tốt hơn chỉ vì Sales gọi ít hơn. Boundary cũng phải cụ thể: không tìm thấy paid là CHƯA RÕ, cờ phải có người xử lý và không được tự ghi vào file tổng.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ ưu tiên chốt cách đo và quyền dữ liệu trước khi đầu tư vào phương án công cụ. Câu hỏi cần đặt mạnh hơn là: checklist chuẩn hóa đã đủ chưa, ai xác nhận nguồn paid mới nhất, ai duyệt lead có cờ và ai ghi log Sales? Tôi cũng sẽ yêu cầu so sánh Rule với No AI trên cùng cách phân loại lỗi và cùng phạm vi bấm giờ. Nếu No AI đạt cùng mục tiêu với ít công hơn, kết luận phù hợp là giữ No AI; nếu thiếu dữ liệu đánh giá thì tiếp tục Not Yet thay vì suy đoán hiệu quả.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

1. **Problem:** Người chạy quảng cáo kiểm tay lead trước khi bàn giao trên file tổng dùng chung nhưng vẫn để lọt khách trùng, đã thanh toán hoặc có số sai sang Sales.
2. **Quy trình:** Hướng thử là đưa chuẩn hóa số, kiểm định dạng và kiểm trùng sang sheet riêng chỉ đọc file tổng, giữ tra paid bằng tay khi chưa có bản xuất phù hợp và có người duyệt trước bàn giao.
3. **Metric:** Số 1–2 khách bị gọi trùng/nhầm mỗi 1–2 hôm và 20–50 phút kiểm/ngày là ước lượng đầu vào; cần đo baseline 5 ngày với No AI + checklist, sau đó thử Rule 5 ngày với target tạm ≤1 khách gọi lỗi, tỷ lệ lỗi không tăng và thời gian kiểm trung bình ≤20 phút/ngày.
4. **Boundary:** Công cụ không tự ghi/sửa/xóa file chung, không tự gộp khách hoặc đổi paid; ca thiếu nguồn hay chưa tra rõ thanh toán phải có cờ CHƯA RÕ và người xác minh.
5. **Mức can thiệp:** Toàn bộ quy trình có độ mơ hồ thấp và độ phức tạp cao do nhiều bước/nguồn, nhưng từng phép kiểm xác định vẫn dùng Rule được, không cần AI dự đoán hoặc tự quyết bước tiếp theo.
6. **Quyết định:** Not Yet với triển khai thật vì quyền dữ liệu, nguồn đối chiếu và trách nhiệm duyệt/ghi log chưa xác nhận; chỉ xét pilot nhỏ khi vượt các điều kiện mục 8 báo cáo nhóm.
7. **Ngưỡng dừng:** Sau 5 ngày thử Rule đủ log mà vượt một trong các ngưỡng lỗi/thời gian thì quay về No AI + checklist; vi phạm boundary thì dừng ngay, còn thiếu log thì chưa kết luận thành công.

---

## 7. Tài liệu tham khảo

- [CHECKPOINTS.md](../../CHECKPOINTS.md): đầu ra và tự kiểm CP6.
- [Worksheet — CP6](../../docs/01-worksheet.md#cp6--mức-can-thiệp-ai--problem-statement-v1--quyết-định-25--define): ma trận, ngoại lệ No AI/Rule và quyết định theo 4 rủi ro.
- [RUBRIC.md](../../RUBRIC.md): tiêu chí C9, C10, C11 và cách đánh giá giải pháp Rule.
- [RULES.md](../../RULES.md): yêu cầu khai cách dùng AI và nguồn bằng chứng.
- [Báo cáo nhóm](../team/group_report.md): mục 2–5 là đầu vào đã có; mục 6–8 là sản phẩm CP6, mục 9 là phần bổ sung được giao; mục 6.5 có sơ đồ và mục 7 có bảng truy nguồn dẫn chứng.
- [TEAM.md](../../TEAM.md): phân công CP6 và phần đóng góp cá nhân.
- Công cụ hỗ trợ lượt hoàn thiện CP6 và hồ sơ cá nhân: ChatGPT/Codex; phạm vi hỗ trợ được ghi ở mục 5.
