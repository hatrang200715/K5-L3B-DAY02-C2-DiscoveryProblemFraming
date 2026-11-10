# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: C2
- Candidate problem nhóm chọn (1 câu): Học viên theo dõi thông báo từ nhiều nền tảng mất 15–30 phút/ngày để lọc thông báo cần hành động và có nguy cơ bỏ sót deadline.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 |Nguyễn Gia Nam |2A202603761 |phỏng vấn, phụ trách research |Basrot |
| 2 | Phùng Thị Nhài | 2A202603725 | Đề xuất candidate được chọn (Problem Card #1), cung cấp dữ liệu baseline, phỏng vấn 2 học viên (snapshot 02, 03) | nhaipt342k4 |
| 3 | | | | |
| 4 | | | | |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Phùng Thị Nhài | Nguyễn Gia Nam, Thành viên 3 | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Nguyễn Gia Nam | Phùng Thị Nhài | Assumption Map, Interview Snapshot, tổng hợp insight |
| CP4 — Research | Nguyễn Gia Nam | Thành viên 3 | Bảng research giải pháp hiện có kèm link |
| CP5 — Quy trình trước/sau | Thành viên 3 | Nguyễn Gia Nam | Quy trình As-Is/To-Be, bảng Before/After |
| CP5 — Problem Statement v0 | Phùng Thị Nhài | Thành viên 3 | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Gia Nam | Phùng Thị Nhài, Thành viên 3 | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Thành viên 3 | Nguyễn Gia Nam, Phùng Thị Nhài | Bốn rủi ro + quyết định Not Yet |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenGiaNam-2A202603761

**Phần việc phụ trách:**

- Tham gia phỏng vấn, tìm hiểu những khó khăn của học viên khi theo dõi thông báo và deadline từ nhiều nền tảng.
- Phụ trách research, tìm hiểu các giải pháp hiện có và hỗ trợ nhóm đánh giá hướng giải quyết vấn đề.

**Đóng góp cụ thể (mình đã làm gì, ra sản phẩm gì):**

- Trong buổi thảo luận, mình ủng hộ ý tưởng tổng hợp thông báo và deadline của chị Nhài, đồng thời đề xuất tập trung vào những học viên sử dụng từ 2 cổng thông tin trở lên.
- Tham gia phản biện các ý tưởng khác, trong đó có việc đặt câu hỏi về tính cần thiết của nhận diện khuôn mặt khi đã có thẻ NFC.
- Tìm hiểu các giải pháp như Google Calendar, Microsoft Outlook/To Do, Zapier và Notion Calendar để xem những chức năng nào đã có sẵn và những hạn chế cần kiểm chứng.
- Từ kết quả phỏng vấn, mình chú ý đến tình huống học viên suýt bỏ lỡ email Outlook cần xác nhận trước 18h, cho thấy việc có nhiều nguồn thông báo có thể gây ra bất tiện thực tế.
- Đề xuất nhóm nên bắt đầu với MVP nhỏ, kiểm tra khả năng phân loại thông báo và nhận diện deadline trước khi phát triển tích hợp nhiều nền tảng.

**Bằng chứng (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):**

- `report/team/group_report.md`: phần kiểm chứng người dùng, research các giải pháp hiện có và đề xuất hướng MVP.
- `report/individual/2A202603761_NguyenGiaNam.md`: phần tham gia CP3–CP7 và nhật ký sử dụng AI.
- Link commit hoặc file minh chứng phỏng vấn: bổ sung sau khi xác nhận trên GitHub.

**Điều mình học được từ phần nhóm:**

Qua buổi workshop, mình thấy một ý tưởng có thể nghe rất hay nhưng chưa chắc đã cần xây dựng thành một ứng dụng riêng. Khi thảo luận và nhận phản biện, mình hiểu hơn việc phải xác định đúng người dùng và vấn đề họ đang gặp trước khi chọn giải pháp. Với đề tài của nhóm, mình cũng nhận ra rằng không nên cố gắng kết nối tất cả các nền tảng ngay từ đầu. Trước mắt, nhóm nên thử một phiên bản nhỏ, đo xem nó có thực sự giúp học viên giảm thời gian kiểm tra và hạn chế bỏ sót thông báo hay không.
### PhungThiNhai-2A202603725

**Phần việc phụ trách:**

- Đề xuất candidate problem được nhóm chọn: thông báo và deadline nằm rải rác ở nhiều kênh (Problem Card #1).
- Cung cấp dữ liệu quy trình hiện tại và baseline cho Problem Statement.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 Problem Card (deadline nhiều kênh, gom báo cáo nhóm, tìm lại thông tin trong group chat); Card #1 được nhóm chọn.
- Cung cấp số liệu tự ghi nhận: ~30 phút/ngày (LMS 1', email 5', group chat 15', ghi lịch/hỏi bạn ~9'), hỏi bạn bè ~4 lần/tuần, lớp ~85 người.
- Chỉ ra bottleneck thật: thông báo của lead bị lẫn giữa tin hỏi đáp; và tín hiệu phản bác: lớp đã có kênh thông báo riêng nhưng ít được dùng.
- Phỏng vấn 2 học viên ngoài nhóm qua Zalo (snapshot 02, 03 trong mục 3.2), phát hiện pain cốt lõi là bỏ lỡ thay đổi deadline.
- Phản biện ý tưởng quản lý tiến độ nhóm của Nam: "Nhóm làm vài giờ có cần hệ thống này không? AI có cần thiết hơn checklist hoặc lịch nhắc?"

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1 (pitch #1–3, câu hỏi phản biện cho #4), mục 3.2 (dòng "Người đề xuất candidate", Interview snapshot 02 và 03).
- `report/individual/2A202603725_PhungThiNhai.md`: mục 2–3 (scan, Problem Card #1 và phản biện).

**Điều mình học được từ phần nhóm:**

Sau buổi workshop, mình hiểu rằng để xây dựng một giải pháp AI hiệu quả, điều quan trọng không phải là sử dụng công nghệ phức tạp mà là giải quyết được vấn đề thực tế. Qua quá trình làm việc nhóm và nhận góp ý, mình nhận ra cần nhìn nhận bài toán từ góc độ của cả tài xế và điều phối viên để hiểu rõ những khó khăn trong quá trình xử lý khi xe gặp tình trạng pin yếu. Đối với đề tài Xanh SM, mình nghĩ nhóm nên tập trung trước vào khả năng đưa ra gợi ý trạm sạc phù hợp và xác định những trường hợp cần điều phối viên can thiệp. Sau khi thử nghiệm và đánh giá kết quả, nhóm mới nên cân nhắc mở rộng thêm các chức năng khác. Điều này giúp tránh phát triển quá nhiều tính năng không cần thiết và đảm bảo giải pháp thực sự mang lại giá trị cho người sử dụng.
