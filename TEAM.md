# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: AIphevat
- Candidate problem nhóm chọn (1 câu): C08. Người chạy quảng cáo phải kiểm tay lead trùng và khách đã thanh toán trên file tổng dùng chung trước khi bàn giao cho Sales, khiến Sales vẫn gọi trùng, gọi nhầm hoặc gọi vào số sai.
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Đinh Phúc Diên|2A202603876 | Điều phối thời gian, ghi chép | dinhphucdien179 |
| 2 | Lê Nguyễn Anh Nhân|2A202603838 | Viết Problem Statment, người phản biện chính | ying684 |
| 3 | Nguyễn Trọng Nghĩa| 2A202603835| Vẽ quy trình, viết Problem Statement | trongnghia2304 |
| 4 | Nguyễn Nghiêm Khánh Tiệp | 2A202603863| Phụ trách research, kiểm chứng | tiepnnk01-10 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Đinh Phúc Diên | Nguyễn Trọng Nghĩa| Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Nguyễn Nghiêm Khánh Tiệp | Đinh Phúc Diên | Assumption map, snapshot hoặc survey |
| CP4 — Research | Nguyễn Nghiêm Khánh Tiệp | Nguyễn Trọng Nghĩa | Bảng research có link |
| CP5 — Quy trình trước/sau | Nguyễn Trọng Nghĩa | không có | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Nguyễn Trọng Nghĩa | Nguyễn Nghiêm Khánh Tiệp | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Lê Nguyễn Anh Nhân | Nguyễn Nghiêm Khánh Tiệp | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Lê Nguyễn Anh Nhân | Đinh Phúc Diên | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### Đinh Phúc Diên-2A202603876

**Phần việc phụ trách:**

- Phụ trách CP3 — Hội tụ nhóm; điều phối thời gian và ghi chép theo phân công.
- Hỗ trợ CP4 — Kiểm chứng và CP6 — Quyết định theo bảng phân công; chưa có kết quả các phần này trong báo cáo hiện tại.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Cung cấp 5 vấn đề từ trải nghiệm cá nhân; chọn 3 vấn đề về phân tâm do điện thoại, tìm ghi chú toán và giấc ngủ để chuẩn bị Problem Card.
- Sử dụng AI hỗ trợ tổng hợp 12 candidate trong thư mục `tonghop`, lập bảng cluster, cây Opportunity Solution Tree và bảng đánh giá theo 7 tiêu chí trong `tieuchi.md`.
- Yêu cầu chỉnh sửa phần hội tụ theo mẫu ngắn gọn, trình bày candidate được đề xuất, lý do chọn/loại và mục xử lý bất đồng.
- Chuẩn bị bản tổng hợp đề xuất C08 — Kiểm tra lead trùng/đã thanh toán trước khi bàn giao Sales — để nhóm thảo luận. Chưa ghi nhận đây là quyết định đồng thuận cuối cùng.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo cá nhân — mục 2 và 3](report/individual/2A202603876_DinhPhucDien.md): bảng scan 5 vấn đề, 3 Problem Card và quy trình nháp.
- [Báo cáo nhóm — mục 2](report/team/group_report.md#2-hội-tụ-và-đánh-giá-12-candidate-cp3): danh mục candidate, cluster, cây OST, bảng điểm và lý do đề xuất C08.

**Điều mình học được từ phần nhóm:**

*Bản nháp rút ra từ phần tổng hợp, cần tự đọc lại và xác nhận theo trải nghiệm thực tế:*

- Cần phân biệt pain với giải pháp: “khó kiểm tra lead trùng” là vấn đề, còn bảng tính chung hoặc AI lọc lead là phương án giải quyết.
- Khi so sánh candidate, cần nhìn vào actor, bước nghẽn, số liệu và khả năng kiểm chứng; điểm cao chưa đủ để chốt nếu thiếu bằng chứng.
- Số liệu trong Problem Card là đầu vào để kiểm chứng, chưa thay thế phỏng vấn hoặc đo thực tế. Nên xem xét cách sửa quy trình và Rule trước khi chọn mức can thiệp cao hơn.

### NguyenNghiemKhanhTiep-2A202603863

**Phần việc phụ trách:**

- Người chính phần CP4: Kiểm chứng và Research.
- Hỗ trợ CP5 (Problem Statement v0) và CP6 (mức can thiệp, Problem Statement v1).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Lập Assumption Map cho candidate C08 gồm 6 giả định (Value, Feasibility, Usability, Viability), chọn 4 giả định quan trọng nhưng ít bằng chứng (#1–#4) để kiểm chứng trong buổi lab.
- Soạn bộ 8 câu hỏi phỏng vấn theo The Mom Test (hỏi về lần gần nhất đã xảy ra, không hỏi "có muốn dùng không").
- Phỏng vấn qua tin nhắn Messenger 2 người ngoài nhóm đang làm marketing và tự lọc lead: một người marketing ads (10–15 khách/ngày), một người Social Marketing (20–50 lead/ngày). Ghi lại thành 2 Interview Snapshot.
- Tổng hợp tín hiệu xác nhận và phản bác. Phát hiện chính: thời gian kiểm thực tế chỉ khoảng 20–50 phút/ngày, thấp hơn nhiều so với 2–3 giờ trong card; pain chính là khách bị gọi trùng, gọi nhầm hoặc gọi lỗi; file tổng dùng chung nên không áp được công thức hay script.
- Đề xuất 6 điểm sửa problem sau phỏng vấn: đổi metric chính sang số khách bị gọi trùng, gọi nhầm hoặc gọi lỗi mỗi tuần; thêm bước kiểm số điện thoại hợp lệ; Rule phải chạy trên bản sao hoặc sheet kiểm riêng, không ghi vào file chung.
- Research 3 nhóm giải pháp có sẵn (hàm Google Sheets REGEXREPLACE/COUNTIF/XLOOKUP, HubSpot Duplicates manager, Salesforce Matching/Duplicate rules), tự mở và kiểm tra từng link. Kết luận: dò trùng chính xác đã có cách làm sẵn, chưa có lý do dùng AI.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 3 (CP4): 3.1 Assumption Map, 3.2 Kiểm chứng (2 Interview Snapshot, bảng tổng hợp, các thay đổi sau phỏng vấn), 3.3 Research giải pháp đã có.
- `report/assets/cp4-interview-1.jpg`, `report/assets/cp4-interview-2.jpg`: ảnh chụp 2 đoạn phỏng vấn qua tin nhắn.

**Điều mình học được từ phần nhóm:**

-Nhóm làm việc nghiêm túc, tinh thần trao đổi nhóm sôi nổi nên mình cũng học được rất nhiều những ý tưởng từ các bạn.

### Nguyễn Trọng Nghĩa - 2A202603835

**Phần việc phụ trách:**

- Người chính phần CP5: Quy trình trước/sau và Problem Statement v0 (vai trò vẽ quy trình, viết Problem Statement).
- Hỗ trợ CP3 (hội tụ nhóm) và CP4 (research) theo bảng phân công.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đưa 3 candidate vào danh sách 12 candidate của nhóm (C10 tìm lại cách sửa lỗi lab trong kênh chat, C11 đối chiếu slide và báo cáo, C12 ghi lại pattern và lỗi sai khi luyện lập trình), từ 3 Problem Card trong báo cáo cá nhân.
- Dựng quy trình hiện tại 6 bước cho C08 theo lời kể của 2 người được phỏng vấn ở CP4, kèm bảng actor / input / output / thời gian; xác định bottleneck là bước 2–4 (kiểm tay từng lead với file tổng dùng chung và hệ thống thanh toán).
- Vẽ quy trình tương lai ở mức Rule: công thức chạy trên sheet kiểm riêng chỉ đọc file tổng, thêm bước kiểm số điện thoại hợp lệ, cờ "CHƯA RÕ" khi không tra được thanh toán, bước con người duyệt lead có cờ và phương án quay về kiểm tay. Xuất sơ đồ thành ảnh.
- Lập bảng before/after và viết Problem Statement v0 (6 trường), trong đó metric chính là số khách bị gọi trùng / nhầm / lỗi mỗi tuần, thời gian kiểm là metric phụ.
- Sau khi phần CP4 được cập nhật, đối chiếu và sửa lại mục 4–5 cho khớp kết quả phỏng vấn: bỏ số liệu cũ của card (2–3 giờ/ngày), đổi bottleneck, metric, boundary theo ràng buộc file dùng chung.
- Nhờ AI phản biện Problem Statement v0 và ghi lại 5 điểm phản biện kèm hướng xử lý. Có dùng AI (Claude) để hỗ trợ dựng sơ đồ và soạn nháp; đã tự đối chiếu từng bước với mục 3.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 4 (4.1 quy trình hiện tại, 4.2 quy trình tương lai, 4.3 before/after) và mục 5 (Problem Statement v0, bảng phản biện).
- `report/assets/cp5-workflow-future.png`: sơ đồ quy trình tương lai.
- `report/individual/2A202603835_NguyenTrongNghia.md`: mục 2–3 (scan problem và 3 Problem Card nguồn của C10–C12).

**Điều mình học được từ phần nhóm:**

- Số liệu trong card chỉ là giả thuyết: sau phỏng vấn, thời gian kiểm thực tế chỉ 20–50 phút/ngày chứ không phải 2–3 giờ, nên metric phải đổi từ "tiết kiệm thời gian" sang "giảm số khách bị gọi lỗi".
- Quy trình tương lai phải vẽ theo ràng buộc thật của người dùng (file tổng dùng chung, không được chạy công thức trên đó), không vẽ theo cách lý tưởng nhất.
