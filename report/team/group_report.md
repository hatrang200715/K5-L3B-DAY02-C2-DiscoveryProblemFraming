# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: C2
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nhài Phùng | Khi cần theo dõi deadline, tôi muốn tổng hợp thông báo từ nhiều kênh để tiết kiệm thời gian. | Sinh viên| Thông báo phân tán nhiều nơi. | Bạn đã từng bỏ lỡ deadline chưa? |
| 2 |Nhài Phùng  | Khi làm báo cáo nhóm, tôi muốn tự động tổng hợp nội dung để tiết kiệm thời gian. |Thu thập và chỉnh sửa báo cáo thủ công. |Mỗi lần chỉ mất 20 phút, có đáng giải quyết không?  |
| 3 | Nhài Phùng |Khi cần tìm lại thông tin trong group chat, tôi muốn tìm nhanh nội dung cũ. | Sinh viên| Tin nhắn quá nhiều, khó tìm kiếm. | Tính năng tìm kiếm và ghim tin nhắn có đủ chưa? |
| 4 |Nguyễn Gia Nam | Khi quản lý dự án nhóm, tôi muốn nắm tiến độ và điều chỉnh kế hoạch kịp thời mà không phải liên tục hỏi từng thành viên. |Trưởng nhóm dự án, nhóm sinh viên  |Thành viên ít chủ động cập nhật; trưởng nhóm phải hỏi thủ công và khó đánh giá tiến độ tổng thể.  |Câu hỏi của Nhài Phùng :Nhóm làm vài giờ có cần hệ thống này không? AI có cần thiết hơn checklist hoặc lịch nhắc?   |
| 5 | Nguyễn Gia Nam | Khi học từ nhiều tài liệu khác nhau, tôi muốn tổng hợp kiến thức thành ghi chú có cấu trúc thống nhất để dễ hiểu và ôn tập. | Sinh viên, người tự học |Tài liệu có cấu trúc khác nhau, khó đối chiếu và kết nối nội dung thành ghi chú nhất quán.  |Câu hỏi của abc: AI tổng hợp có làm giảm khả năng tự học không? Dùng mẫu ghi chú cố định có đủ không?  |
| 6 |Nguyễn Gia Nam  |Khi tìm tài liệu cho một chủ đề, tôi muốn nhanh chóng xác định nguồn phù hợp và đáng tin cậy để phục vụ học tập, nghiên cứu.  |Sinh viên, người nghiên cứu  |Phải tìm kiếm, đọc sơ bộ và đánh giá nhiều nguồn trước khi lựa chọn tài liệu phù hợp.  |Câu hỏi của bcx: Vấn đề có thực sự nghiêm trọng không? Công cụ tìm kiếm hiện có chưa giải quyết được ở bước nào?  |
| 7 |Hạnh Lương |khi ra vào vinhomes vào giờ giới nghiêm, tôi muốn việc xác minh danh tính được thực hiện nhanh chóng và chính xác hơn để không phải tốn nhiều thời gian đứng chờ ngoài cổng |Cư dân vinhomes|Dữ liệu cá nhân truy cập khó và cần sự phối hợp của cư dân |Có thực sự đang để đầu tư nhiều chi phí tới vậy không? |
| 8 |Hạnh Lương |khi đến bữa ăn trưa, tôi muốn biết còn bao nhiêu bàn ăn còn trống dưới căn tin để không mất thời gian đi xuống rồi lại chờ đợi| học viên VinUni |Học viên VinUni |Chi phí của solution cao hơn lợi ích thu được |Người dùng có chịu trả phí không? Có quan trọng không? |
| 9 |Hạnh Lương |khi sáng thức dậy, cư dân Vinhomes muốn biết những tiện ích nào đang sẵn sàng và những cảnh báo sớm từ trước để bố trí lịch cá nhân phù hợp như nên tập thể dục ở công viên vào khung giờ nào để tránh mưa hay ảnh hưởng cực đoan từ thời tiết |Cư dân vinhomes |Chi phí của solution cao hơn lợi ích thu được | |


### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A-Học tập / tổng hợp |Tổng hợp deadline, Gom báo cáo nhóm,Tổng hợp kiến thức |Tổng hợp, tìm kiếm và tổ chức thông tin phục vụ học tập |
| B— Tìm kiếm thông tin |Tìm thông tin trong group chat |Tìm đúng thông tin trong nhiều nguồn rời rạc |
| C— Quản lý công việc |Theo dõi tiến độ nhóm |Theo dõi tiến độ, cập nhật công việc và giảm quản lý thủ công |
| D — Tiện ích sinh hoạt |Xác minh ra vào VinHomes; Tìm bàn trống căn tin |Giảm thời gian chờ đợi và cải thiện trải nghiệm sinh hoạt |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

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
