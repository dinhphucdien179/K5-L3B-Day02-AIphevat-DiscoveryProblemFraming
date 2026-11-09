# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm và trạng thái báo cáo

- Tên nhóm: **AIphevat**.
- Thành viên và phân công: xem [TEAM.md](../../TEAM.md); 
- Candidate **đề xuất**: **C08 - Kiểm tra lead trùng và trạng thái đã thanh toán trước khi bàn giao cho Sales**.
- Quyết định phân tích sơ bộ: **Not Yet** với việc triển khai; ưu tiên kiểm chứng phương án **Rule**, chưa có căn cứ cần AI.

## 2. Hội tụ và đánh giá 12 candidate (CP3)

### 2.1. Danh mục chuẩn bị pitch

Cột cuối là **câu hỏi AI đề xuất**, chưa phải câu hỏi thành viên đã đặt trong buổi pitch. Chưa có dữ liệu người hỏi hoặc biên bản thảo luận.

| ID | Người đưa ra / nguồn | Candidate, actor và nhu cầu | Bottleneck / bằng chứng trong nguồn | Câu hỏi đề xuất để nhóm tự thảo luận |
|---|---|---|---|---|
| C01 | Đinh Phúc Diên | Người tự học cần quay lại tập trung sau khi dùng điện thoại. | Dùng điện thoại 15–30 phút tùy lần, sau đó khoảng 30 phút lấy lại tập trung; tần suất chưa đo. | Để điện thoại xa ngay từ đầu có đủ giải quyết không? |
| C02 | Đinh Phúc Diên | Người học cần tìm lại công thức toán ghi trong vở giấy. | Một lần tìm thủ công khoảng 20 phút. | Mất thời gian do không nhớ vở, trang hay chủ đề? |
| C03 | Đinh Phúc Diên | Người học cần vào giấc và duy trì giấc ngủ để tập trung hôm sau. | Đợt khó ngủ 3–4 ngày; khoảng 120 phút vào giấc, 20 phút ngủ lại. | Nhóm có đủ dữ liệu và năng lực để xác định phạm vi hỗ trợ không? |
| C04 | Lê Nguyễn Anh Nhân | Giáo viên cần chỉnh sửa nội dung tài liệu chỉ có bản scan. | Kịch bản nhập lại ước tính 35 phút/tài liệu; chưa có file thử. | Xin bản gốc hoặc công cụ đã có có đủ đáp ứng không? |
| C05 | Lê Nguyễn Anh Nhân | Giáo viên cần chuẩn bị giáo án điện tử sau buổi dạy. | Tổng ước tính 80 phút; soạn nội dung 25 phút và thao tác công cụ 10 phút. | Bước nghẽn là soạn chuyên môn hay học thao tác? |
| C06 | Lê Nguyễn Anh Nhân | Sinh viên mới đến Hà Nội cần chọn cách đi đến nơi chưa quen. | Ước tính 25 phút/lần tìm tuyến mới, bước 3–5 chiếm 18 phút. | Nguồn thông tin nào thực sự thiếu hoặc khó đối chiếu? |
| C07 | Nguyễn Nghiêm Khánh Tiệp | Kế toán xã cần tổng hợp dữ liệu khoảng 10 xóm để làm lương/BHXH. | Tổng nguồn nêu 2–3 ngày công/tháng; bước gõ lại nêu 7 giờ nhưng sơ đồ ghi 480 phút. | Mẫu chung xử lý được bao nhiêu và còn bao nhiêu ảnh viết tay? |
| C08 | Nguyễn Nghiêm Khánh Tiệp | Người chạy quảng cáo cần loại lead trùng/đã paid trước khi bàn giao Sales. | 2–3 giờ/ngày/người; dò trùng 70 phút, dò paid 50 phút; 9–15 cuộc gọi sai/nhầm mỗi tuần theo nguồn. | Có danh sách paid cập nhật và khóa nhận diện khách đáng tin cậy không? |
| C09 | Nguyễn Nghiêm Khánh Tiệp | Người làm content cần tìm trend phù hợp để chuẩn bị ít nhất 5 ý tưởng/ngày. | Tìm trend khoảng 60–90 phút/ngày; chất lượng ý tưởng chưa có baseline. | Tìm trend hay đánh giá độ phù hợp mới là bước nghẽn? |
| C10 | Nguyễn Trọng Nghĩa | Sinh viên cần tìm lại cách sửa lỗi lab đã được thảo luận. | Tìm 20–30 phút; lướt ngữ cảnh 15–20 phút; thời gian chờ trả lời chưa đo. | FAQ hoặc thread có tag có đủ thay cho tìm kiếm nâng cao không? |
| C11 | Nguyễn Trọng Nghĩa | Người làm slide cần thống nhất số liệu/luận điểm với báo cáo. | Nguồn nêu 60–75 phút/đợt; dò đối chiếu 40–50 phút. | Có cặp slide–báo cáo để xác nhận lỗi và thời gian không? |
| C12 | Nguyễn Trọng Nghĩa | Người luyện lập trình cần nhớ pattern và lỗi cũ để tránh lặp lại. | Nguồn nêu 3 bài từng AC nhưng làm lại WA; ghi chú bị bỏ qua. | WA có chắc do lỗi cũ và có lịch sử submission chứng minh không? |

### 2.2. Cluster theo pain

| Cluster | Candidate | Pattern chung |
|---|---|---|
| A — Duy trì trạng thái học tập | C01, C03 | Gián đoạn sự tập trung hoặc trạng thái nghỉ ngơi ảnh hưởng việc học. |
| B — Tìm lại và sử dụng kiến thức | C02, C10, C12 | Khó lấy lại thông tin hoặc kinh nghiệm đã có khi cần dùng. |
| C — Chuẩn bị và kiểm tra tài liệu | C04, C05, C11 | Chuyển đổi, soạn hoặc đối chiếu nội dung trước khi sử dụng. |
| D — Tổng hợp dữ liệu và kiểm tra sai lệch | C07, C08 | Đầu vào phân tán, cần chuẩn hóa và đối chiếu trước khi bàn giao. |
| E — Tìm và đánh giá thông tin mới | C06, C09 | Phải tìm nhiều nguồn và chọn thông tin phù hợp bối cảnh. |

### 2.3. Opportunity Solution Tree rút gọn

Cây dưới đây áp dụng cho **C08 được đề xuất**, không ép cả 12 vấn đề khác domain vào một outcome giả tạo.

```text
OUTCOME ĐỀ XUẤT: Giảm thời gian kiểm tra/bàn giao lead từ 2–3 giờ
xuống ≤30 phút/ngày/người và số cuộc gọi sai/nhầm từ 9–15 xuống ≤2/tuần
(baseline theo card, cần xác minh; target chưa được nhóm chốt).
├── Khó biết một khách đã xuất hiện trong các file khác hoặc file tổng chưa.
├── Khó đối chiếu trạng thái đã thanh toán vì thông tin nằm ở nguồn khác.
├── Cách ghi số điện thoại và tên không nhất quán gây khó đối chiếu.
└── Bàn giao gần đồng thời khiến khó phát hiện lead vừa được người khác thêm.
```

### 2.4. Bảng chấm điểm đầy đủ và xếp hạng

| Rank | Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức Lab | So sánh 4 mức | Hiểu domain | Tổng /35 |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | C08 — Kiểm tra lead trùng/đã paid | 4 | 5 | 3 | 4 | 4 | 5 | 3 | 28 |
| 2 | C10 — Tìm cách sửa lỗi lab trong chat | 4 | 4 | 3 | 4 | 4 | 4 | 3 | 26 |
| 3 | C11 — Đối chiếu slide và báo cáo | 4 | 4 | 3 | 4 | 4 | 4 | 3 | 26 |
| 4 | C02 — Tìm ghi chú công thức toán | 4 | 3 | 3 | 3 | 5 | 3 | 3 | 24 |
| 5 | C01 — Phân tâm vì điện thoại | 4 | 4 | 3 | 3 | 4 | 2 | 3 | 23 |
| 6 | C07 — Tổng hợp dữ liệu kế toán xã | 4 | 4 | 3 | 3 | 2 | 4 | 2 | 22 |
| 7 | C12 — Ôn pattern và lỗi lập trình | 4 | 4 | 3 | 3 | 3 | 2 | 3 | 22 |
| 8 | C04 — Tài liệu scan cần chỉnh sửa | 4 | 4 | 2 | 3 | 3 | 3 | 2 | 21 |
| 9 | C09 — Tìm trend để làm content | 4 | 4 | 3 | 2 | 2 | 3 | 2 | 20 |
| 10 | C05 — Chuẩn bị giáo án điện tử | 4 | 3 | 2 | 3 | 2 | 3 | 2 | 19 |
| 11 | C06 — Tìm thông tin đi lại Hà Nội | 3 | 4 | 2 | 3 | 2 | 3 | 2 | 19 |
| 12 | C03 — Khó ngủ, ngủ gián đoạn | 4 | 4 | 3 | 2 | 1 | 1 | 1 | 16 |

**Candidate được chọn:** C08 — Kiểm tra lead trùng và trạng thái đã thanh toán (paid) trước khi bàn giao cho Sales (đề xuất để nhóm xác nhận). Bối cảnh: nhiều người chạy quảng cáo cho cùng một sản phẩm, mỗi người có một file lead .xlsx riêng rồi tự copy vào một file tổng chung để Sales gọi. Điểm shortlist: **28/35**, cao nhất trong 3 candidate.

**Vì sao chọn:**

- **Actor và quy trình rõ:** người chạy quảng cáo → file tổng → Sales. Quy trình 6 bước vẽ được, bottleneck nằm ở **một bước cụ thể**: dò từng lead với file tổng để tìm trùng chéo với file của người khác (~70 phút/ngày/người), cộng thêm dò danh sách paid (~50 phút).
- **Pain có số liệu để kiểm chứng:** 2–3 giờ/ngày/người cho việc check + copy; Sales phản ánh gọi sai/gọi nhầm 9–15 lần/tuần. Cả hai đều đo lại được bằng bấm giờ và log cuộc gọi.
- **Impact nhân lên theo số người:** cùng một việc lặp lại ở từng người chạy quảng cáo; hậu quả dồn về Sales (gọi trùng) và khách hàng (bị gọi nhiều lần, bị gọi dù đã mua).
- **So sánh rõ được 4 mức No AI / Rule / Workflow / Agent:** gộp về một bảng tính chung (No AI), công thức COUNTIF/XLOOKUP đánh dấu trùng và paid (Rule), tự động đổ lead + người duyệt ngoại lệ (Workflow), còn Agent gần như không cần. Có thể thử Rule trước khi cân nhắc AI.
- **Vừa sức một buổi lab:** mô phỏng được bằng vài file mẫu đã ẩn danh, không cần quyền truy cập hệ thống thật.

**Vì sao loại các candidate còn lại:**

- **C10 — Tìm cách sửa lỗi lab trong chat (26/35):** cần quyền truy cập lịch sử chat và bộ câu hỏi–đáp án để đánh giá; pain chưa có số liệu đo, khó kiểm chứng trong thời gian lab.
- **C11 — Đối chiếu slide và báo cáo (26/35):** cần cặp slide–báo cáo đúng phiên bản và thống nhất cách đo thời gian đối chiếu nên khó đặt baseline.
- **C07 — Tổng hợp dữ liệu kế toán xã** (cùng cluster D với C08): chỉ xảy ra 1 lần/tháng với 1 người; dữ liệu lương/BHXH là dữ liệu cá nhân nhạy cảm, khó lấy mẫu để kiểm chứng.
- **C09 — Tìm trend content:** khó đo thế nào là "ý tưởng tốt"; chưa rõ bottleneck là bước tìm trend hay bước nghĩ ý tưởng.

**Xử lý bất đồng (nếu có):** Chưa có thông tin trong tài liệu nguồn; nhóm bổ sung sau khi thảo luận (ai đề xuất candidate khác, lý do, nhóm chốt bằng tiêu chí nào). Điểm nên đem ra phản biện: C08 chỉ hơn C10/C11 2 điểm, và tiêu chí "Nhóm hiểu domain" của C08 mới đạt 3/5.
---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

Candidate từ CP3: **C08. Kiểm tra lead trùng và trạng thái đã thanh toán (paid) trước khi bàn giao cho Sales.**

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người kiểm lead mất 2–3 giờ/ngày, chủ yếu ở bước dò trùng và dò paid; Sales gọi sai/nhầm 9–15 cuộc/tuần vì dữ liệu chưa kiểm. | Value | 5 | 2 | Có, phỏng vấn qua tin nhắn |
| 2 | Có một nguồn paid được cập nhật trước lúc bàn giao lead. | Feasibility | 5 | 1 | Có, phỏng vấn qua tin nhắn |
| 3 | Số điện thoại (đã chuẩn hóa) đủ làm khóa nhận diện khách; ca một người nhiều số hoặc nhiều người chung số là ít. | Feasibility | 5 | 1 | Có, phỏng vấn qua tin nhắn |
| 4 | Các cách đơn giản (sheet chung, công thức) chưa đủ hoặc chưa được thử, nên vẫn còn bước dò tay. | Value | 4 | 1 | Có, phỏng vấn qua tin nhắn |
| 5 | Người vận hành chấp nhận một nguồn bàn giao duy nhất và một người duyệt ngoại lệ. | Usability | 4 | 1 | Sau buổi lab, thử với file mẫu đã che |
| 6 | Được phép dùng dữ liệu mẫu (đã ẩn danh) để thử rule. | Viability | 5 | 1 | Sau buổi lab, xin xác nhận người quản lý dữ liệu |

Giả định nhóm kiểm chứng trong buổi này: #1, #2, #3, #4. Đây là các giả định quan trọng nhưng ít bằng chứng và hỏi được bằng phỏng vấn về các sự cố đã xảy ra. #5 và #6 cần file mẫu và người có thẩm quyền nên để sau buổi lab.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn qua tin nhắn (Zalo/Messenger) với 2 người ngoài nhóm, hỏi theo The Mom Test về những lần gần nhất đã xảy ra.

Interview snapshot 1:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhân viên marketing ads, lĩnh vực marketing. Khoảng 10–15 khách/ngày. |
| Thời điểm và kênh phỏng vấn | Tin nhắn Messenger |
| Người hỏi trong nhóm | |
| Câu nói đáng nhớ nhất (nguyên văn) | "Có thử chạy code tại apps script trên file .xlsx nhưng nó ảnh hưởng đến quyền lợi của người khác" |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | "Mỗi ngày chị đều nhập số khách hàng vào bảng số liệu cho sale chăm sóc khách hàng". Lần gọi lỗi gần nhất: "Cách đây 2 hôm." "Khi sale gọi ko đc số đt vì nó sai sót tầm 2 khách". |
| Hiện đang xử lý bằng cách nào (workaround)? | Kiểm trùng bằng tay: "Kiểm tra file tổng để check dữ liệu xem có trùng hợp hay không". Trạng thái thanh toán xem trên hệ thống: "Nằm trên web của hệ thống do hệ thống tự cập nhật khi nhận đc tiền". Đã thử Apps Script nhưng vướng vì file dùng chung. |
| Mất bao lâu, bao lần? | Bước lâu nhất là "Bước lọc dữ liệu", "mất 20p để check danh sách của toàn khách hàng" (mỗi ngày). Lần gọi lỗi gần nhất: khoảng 2 khách, cách đây 2 hôm. |
| Tín hiệu với giả định #1, #2, #3, #4 (xác nhận / phản bác / chưa rõ) | #1 phản bác một phần: lọc mất 20 phút/ngày, thấp hơn nhiều so với 2–3 giờ trong card; lần gọi lỗi gần nhất do số điện thoại sai, không phải do trùng hay đã thanh toán. #2 xác nhận: hệ thống tự cập nhật khi nhận tiền. #3 chưa rõ: chỉ nói kiểm với file tổng, chưa nói cách xử lý ca một người nhiều số hoặc chung số. #4 xác nhận: đã thử Apps Script nhưng không dùng được trên file chung. |
| Insight / opportunity rút ra | Thời gian không phải pain lớn nhất ở quy mô 10–15 khách/ngày; lỗi khiến Sales gọi hỏng là số điện thoại sai. Tự động hóa bị chặn vì file tổng dùng chung, sửa trên đó ảnh hưởng người khác. "Nếu ngày nào ít khách thì sẽ ít gặp trường hợp trên": pain tăng theo số lead. |
| Ảnh chụp đoạn chat (đã che tên, SĐT) | [cp4-interview-1.jpg](../assets/cp4-interview-1.jpg) |

Interview snapshot 2:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Nhân viên Social Marketing, tự chạy quảng cáo và lọc lead. "1 ngày anh xử lý 20-50 lead khách hàng". |
| Thời điểm và kênh phỏng vấn | Tin nhắn Messenger |
| Người hỏi trong nhóm | |
| Câu nói đáng nhớ nhất (nguyên văn) | "Team có làm nhưng đó là file chung dữ liệu nên ko dùng công thức hay thuật toán cho 1 người đc" |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Việc lặp lại mỗi ngày: "a sẽ phải lọc khách hàng từ dữ liệu chạy quảng cáo của anh", "Xong rồi anh sẽ check xem số liệu của khách đúng chưa? Khách đã thanh toán chưa ? Liệu khách đó đã có ai chạy quảng cáo có data khách đó chưa?" Không nêu ngày cụ thể của lần gọi nhầm gần nhất. |
| Hiện đang xử lý bằng cách nào (workaround)? | "Bằng việc check data trong file tổng bằng tay". Trạng thái thanh toán: "Thông tin khách hàng thanh toán do hệ thống cập nhật". |
| Mất bao lâu, bao lần? | "Bước lọc dữ liệu . Ước tính mất khoảng 10p cho 1 danh sách khách hàng khoảng 10 người" (tự ước lượng). Với 20–50 lead/ngày, nhóm quy đổi ra khoảng 20–50 phút/ngày. Gọi nhầm: "Chuyện này cũng thường xuyên tầm 1-2 hôm sẽ có 1-2 khách đã bị gọi trùng hoặc nhầm". |
| Tín hiệu với giả định #1, #2, #3, #4 (xác nhận / phản bác / chưa rõ) | #1 xác nhận về gọi trùng/nhầm lặp lại thường xuyên; phản bác một phần về thời gian (khoảng 20–50 phút/ngày, không phải 2–3 giờ). #2 xác nhận: hệ thống cập nhật trạng thái thanh toán; chưa rõ cập nhật trước hay sau lúc bàn giao. #3 chưa rõ: kiểm tay trong file tổng, chưa nói cách xử lý ca một người nhiều số hoặc chung số. #4 xác nhận: không áp được công thức vì file dùng chung. |
| Insight / opportunity rút ra | Quy trình người này mô tả khớp với C08: kiểm số liệu đúng chưa, đã thanh toán chưa, đã có người khác chạy quảng cáo có data khách chưa. Pain chính là gọi trùng/nhầm lặp lại, không phải thời gian. Ràng buộc giống người 1: file tổng dùng chung nên không áp được công thức hay script riêng. Tín hiệu phản bác: "Có nhưng thi thoảng sẽ kiểm rất nhanh". |
| Ảnh chụp đoạn chat (đã che tên, SĐT) | [cp4-interview-2.jpg](../assets/cp4-interview-2.jpg) |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Card nghiệp vụ C08 (card #2, bộ C07–C09) | 1 card | Nhiều file lead riêng; dò trùng khoảng 70 phút và dò paid khoảng 50 phút/ngày; 9–15 cuộc gọi sai/tuần. | Chính card thừa nhận một bảng chung kèm công thức có thể đủ; số liệu tự thuật, chưa có log. |
| Phỏng vấn qua tin nhắn | 2 | 2/2 kiểm trùng bằng tay với file tổng. 2/2 có gọi lỗi gần đây: khoảng 2 khách cách đây 2 hôm (người 1), 1–2 khách mỗi 1–2 hôm (người 2). 2/2 cho biết trạng thái thanh toán do hệ thống tự cập nhật. 2/2 đã thử hoặc muốn dùng công thức/script nhưng vướng vì file tổng dùng chung. | Thời gian thấp hơn nhiều so với card: 20 phút/ngày (người 1) và khoảng 10 phút cho 10 lead (người 2), so với 2–3 giờ/ngày. Lần gọi lỗi của người 1 do số điện thoại sai, không phải do trùng hay đã thanh toán. Ngày ít khách hoặc "thi thoảng" thì kiểm rất nhanh. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Trước phỏng vấn, từ việc đọc card và research (mục 3.3):

1. **Phạm vi:** thu hẹp từ "quản lý lead" xuống còn kiểm tra trùng và paid trước khi bàn giao. Không tự gộp khách mơ hồ, không tích hợp gọi điện hay thanh toán.
2. **Hướng xử lý:** ưu tiên kiểm trùng ngay lúc nhập thay vì dò lại cuối ngày, theo cách Salesforce cảnh báo trùng lúc nhập.
3. **Boundary:** chỉ gắn cờ, không tự gộp hay xóa lead, vì ngay cả HubSpot cũng để người duyệt quyết định gộp và không hoàn tác được thao tác gộp.

Các thay đổi sau phỏng vấn qua tin nhắn:

1. **Impact và Success Metric:** baseline thời gian hạ từ 2–3 giờ/ngày (card) xuống khoảng 20–50 phút/ngày theo 2 người được hỏi (tự ước lượng). Target ≤30 phút/ngày không còn đủ ý nghĩa, nên metric chính chuyển sang **số khách bị gọi trùng, gọi nhầm hoặc gọi lỗi mỗi tuần**; thời gian kiểm là metric phụ. Baseline lỗi vẫn phải đo bằng log, vì 2 người chỉ nêu số ước lượng.
2. **Bottleneck và phạm vi:** thêm bước **kiểm số điện thoại hợp lệ** trước bàn giao, vì lần gọi lỗi gần nhất của người 1 do số sai chứ không do trùng. Bottleneck viết lại thành: kiểm tay từng lead với file tổng dùng chung, dễ lọt khách trùng hoặc số sai sang Sales.
3. **Giả định #2:** 2/2 người xác nhận trạng thái thanh toán do hệ thống tự cập nhật khi nhận tiền. Rủi ro chuyển từ "không có nguồn paid" sang "phải mở hệ thống và đối chiếu bằng tay"; độ trễ cập nhật so với lúc bàn giao vẫn chưa rõ.
4. **Ràng buộc mới về file dùng chung:** cả 2 người không áp được công thức hay script vì file tổng dùng chung, sửa trên đó ảnh hưởng người khác. Phương án Rule ở CP5 phải chạy trên **bản sao hoặc một sheet kiểm riêng chỉ đọc file tổng**, không ghi vào file chung. Ràng buộc này bổ sung cho giả định #5 (Usability) và #6 (Viability).
5. **Giả định #3** vẫn chưa có bằng chứng: cả 2 người chưa mô tả cách xử lý ca một người nhiều số hoặc nhiều người chung số. Giữ boundary "không tự gộp, ca không chắc chuyển người duyệt".
6. **Mức can thiệp:** pain chính là lỗi bàn giao do kiểm tay trên file chung, quy mô 10–50 lead/ngày. Bằng chứng này nghiêng về No AI/Rule (quy định nhập, kiểm định dạng số, đánh dấu trùng), chưa có lý do dùng AI.


### 3.3. Research giải pháp đã có

Các link được mở kiểm tra ngày 09/11/2026. Nguồn chỉ xác nhận công cụ có khả năng làm gì, không xác nhận hiệu quả trên dữ liệu của nhóm.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Rule trên bảng tính: REGEXREPLACE (chuẩn hóa SĐT), COUNTIF (đếm trùng theo khóa), XLOOKUP (tra paid) | [REGEXREPLACE](https://support.google.com/docs/answer/3098245?hl=en), [COUNTIF](https://support.google.com/docs/answer/3093480?hl=en), [XLOOKUP](https://support.google.com/docs/answer/12405947?hl=en) | Chuẩn hóa SĐT/tên, dò trùng với file tổng, dò paid | Miễn phí, có sẵn; XLOOKUP có chế độ khớp chính xác và trả giá trị tùy chọn khi không tìm thấy | COUNTIF chỉ có một điều kiện, chỉ bắt trùng chính xác. Không tìm thấy trong danh sách paid không có nghĩa là chưa trả. Không giải quyết việc nhiều người nhập cùng lúc. | Dùng để gắn cờ, không tự xóa. Ca không tìm thấy đưa vào danh sách chờ, không mặc định là chưa paid. |
| HubSpot, Duplicates manager | [knowledge.hubspot.com](https://knowledge.hubspot.com/records/manage-duplicate-records) | Dò trùng contact | Mỗi ngày tự so các thuộc tính (tên, email, SĐT, công ty...) và đưa ra cặp nghi trùng để người duyệt gộp hoặc từ chối | Cần gói trả phí (Professional/Enterprise). Đã gộp thì không hoàn tác được. Chỉ dùng được khi lead đã nằm trong CRM, không xử lý nhiều file Excel rời. | Công cụ lớn cũng để người duyệt quyết định gộp. Nhóm giữ boundary không tự gộp, không tự xóa. |
| Salesforce, Matching rules và Duplicate rules | [Trailhead: Resolve and Prevent Duplicate Data](https://trailhead.salesforce.com/content/learn/modules/sales_admin_duplicate_management/sales_admin_duplicate_management_unit_2) | Cảnh báo hoặc chặn trùng ngay lúc nhập lead | Tách "so khớp thế nào" (chính xác hoặc gần đúng) khỏi "làm gì khi trùng" (cảnh báo hoặc chặn); có rule mẫu cho Lead | Chi phí và công cấu hình cao so với quy mô nhóm nhỏ. Người dùng vẫn bỏ qua được cảnh báo nên vẫn cần rà lại. | Kiểm trùng lúc nhập rẻ hơn dò lại cuối ngày. So khớp chính xác trước, so khớp gần đúng chỉ dùng cho ca cần người xem. |

**Kết luận research:** Dò trùng chính xác và tra trạng thái đã có cách làm sẵn trên bảng tính và CRM, nên không cần tự xây và chưa thấy lý do cần AI. Cả HubSpot và Salesforce đều để con người duyệt ca nghi trùng, nên nhóm giữ bước người duyệt như ở CP3. Hướng cho CP5: chuẩn hóa và kiểm trùng ngay lúc nhập bằng Rule, tra paid có ghi thời điểm, người duyệt ngoại lệ, rồi mới bàn giao. Phần công cụ có sẵn chưa giải được là nguồn paid chậm hoặc không thống nhất và ca một người nhiều số; phỏng vấn (mục 3.2) xác nhận trạng thái thanh toán do hệ thống tự cập nhật (#2), còn #3 vẫn chưa rõ.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-