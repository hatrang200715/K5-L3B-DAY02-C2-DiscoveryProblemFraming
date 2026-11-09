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
| **Google Calendar + Google Tasks** | [Google Calendar Help](https://support.google.com/calendar/answer/9901136) | Ghi nhận deadline, lập lịch học, tạo nhiệm vụ và theo dõi thời hạn hoàn thành. | Giao diện lịch trực quan; quản lý công việc theo ngày; hỗ trợ ngày đến hạn và nhắc việc. | Người học vẫn có thể phải tự đọc thông báo và nhập deadline thủ công. Không mặc định tổng hợp thông báo từ Discord, Phoenix, Outlook và Zalo. | Cần có giao diện lịch và danh sách deadline tập trung, đồng thời giảm thao tác nhập liệu thủ công. |
| **Microsoft Outlook + Microsoft To Do** | [Microsoft Support](https://support.microsoft.com/en-us/todo/using-microsoft-to-do-with-flagged-email-from-outlook) | Tiếp nhận email, đánh dấu email cần xử lý, chuyển email được gắn cờ thành nhiệm vụ và theo dõi công việc. | Tích hợp email và quản lý nhiệm vụ; phù hợp với thông báo học tập được gửi qua Outlook. | Phụ thuộc vào loại tài khoản và thao tác đánh dấu email; không tự giải quyết việc theo dõi thông báo phân tán trên Phoenix, Discord và Zalo. | Cần hỗ trợ phát hiện những thông báo yêu cầu hành động, đặc biệt là email xác nhận thông tin và thông báo có hạn chót. |
| **Zapier — Workflow Automation** | [Zapier Help Center](https://help.zapier.com/hc/en-us/articles/8495982223629-How-to-get-started-with-Google-Calendar-on-Zapier) | Kết nối các ứng dụng được hỗ trợ, tự động chuyển dữ liệu và tạo sự kiện lịch khi có điều kiện kích hoạt. | Giảm thao tác lặp lại; hỗ trợ xây dựng workflow tự động giữa các dịch vụ có tích hợp. | Cần cấu hình kết nối, quyền truy cập và điều kiện kích hoạt. Khả năng lấy dữ liệu từ Phoenix, Zalo và các kênh Discord cụ thể chưa được xác minh. | Nên ưu tiên kiểm tra khả năng tự động hóa bằng workflow và rule trước khi quyết định sử dụng AI. |
| **Notion + Notion Calendar** | [Notion Help Center](https://www.notion.com/help/use-notion-calendar-with-notion) | Tổng hợp công việc, quản lý trạng thái, ngày đến hạn và theo dõi tiến độ trên lịch. | Cho phép tổ chức thông tin linh hoạt; có thể quản lý nhiều nhiệm vụ và deadline trong một không gian làm việc. | Cần có dữ liệu đầu vào phù hợp; chưa xác minh khả năng tự động thu thập toàn bộ thông báo học tập từ các nền tảng mà nhóm sử dụng. | Có thể tham khảo cách thiết kế dashboard tập trung, hiển thị nguồn thông báo, nội dung, deadline, mức độ ưu tiên và trạng thái hoàn thành. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):
**Actor chính:** Sinh viên/học viên đang tham gia chương trình đào tạo và phải theo dõi thông báo học tập từ nhiều nền tảng.

**Mô tả:** Hiện tại, người học phải chủ động mở từng nền tảng để tìm kiếm thông báo, đọc nội dung, xác định deadline và tự ghi nhớ hoặc tạo nhắc lịch. Quá trình này phụ thuộc vào thói quen kiểm tra thông báo của từng cá nhân.
```
[BẮT ĐẦU]
     |
     v
[Phát sinh thông báo học tập]
     |
     v
[Thông báo phân tán trên nhiều nền tảng]
     |
     +----> Phoenix: Lịch học, workshop, standup
     |
     +----> Discord: Lab-code, lab-coach, thông báo nhóm
     |
     +----> Outlook: Email trường, xác nhận thông tin
     |
     +----> Gmail: Thông báo và tin tức
     |
     +----> Zalo: Trao đổi, phân chia công việc nhóm
     |
     v
[Sinh viên mở và kiểm tra thủ công từng nền tảng]
     |
     v
[Đọc thông báo, tìm thông tin liên quan]
     |
     v
{Thông báo có việc cần làm hoặc deadline?}
     |
     +---- KHÔNG ----> [Bỏ qua hoặc ghi nhớ thông tin]
     |                           |
     |                           v
     |                    [Tiếp tục kiểm tra]
     |
     +---- CÓ
           |
           v
    {Deadline có rõ ràng?}
           |
           +---- KHÔNG ----> [Tìm lại tin nhắn,
           |                  hỏi nhóm hoặc lab-coach]
           |                         |
           |                         v
           |                  [Xác định deadline]
           |
           +---- CÓ
                 |
                 v
      [Tự ghi nhớ hoặc nhập lịch nhắc thủ công]
                 |
                 v
      [Theo dõi và thực hiện công việc]
                 |
                 v
      {Có bỏ sót thông báo/deadline?}
                 |
          +------+------+
          |             |
         CÓ           KHÔNG
          |             |
          v             v
 [Phát hiện muộn,   [Hoàn thành
  xử lý gấp hoặc     đúng hạn]
  có nguy cơ trễ]
          |             |
          +------+------+
                 |
                 v
             [KẾT THÚC]

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Giảng viên, lab-coach, nhà trường, thành viên nhóm | Lịch học, thông báo, bài tập, yêu cầu xác nhận và deadline | Thông báo được đăng hoặc gửi trên Phoenix, Discord, Outlook, Gmail, Zalo | Phát sinh tùy hoạt động học tập | Thông tin nằm ở nhiều nguồn khác nhau. |
| 2 | Sinh viên/học viên | Thông báo từ các nền tảng | Danh sách thông báo đã đọc hoặc phát hiện | Kiểm tra hằng ngày; riêng Discord khoảng 7–8 phút/ngày theo người tham gia 01 | Phải chuyển đổi giữa nhiều ứng dụng và kênh thông báo. |
| 3 | Sinh viên/học viên | Nội dung thông báo, tin nhắn, email | Xác định thông báo quan trọng, việc cần làm và deadline | Chưa đo riêng từng bước | Có thể phải đọc nhiều tin nhắn hoặc tìm lại nội dung cũ. |
| 4 | Sinh viên/học viên, bạn học, lab-coach | Thông báo thiếu deadline hoặc chưa rõ yêu cầu | Deadline được làm rõ hoặc thông tin được xác nhận | Khi có thông tin chưa rõ; chưa có số liệu tần suất | Người học phải hỏi cộng đồng hoặc chờ người phụ trách phản hồi. |
| 5 | Sinh viên/học viên | Thông báo đã xác định là quan trọng, deadline | Ghi nhớ, tạo lịch nhắc thủ công hoặc thực hiện công việc | Tổng thời gian kiểm tra và tổng hợp được người tham gia 01 ước tính khoảng 15–20 phút/ngày, đôi khi 30 phút | Ít sử dụng công cụ nhắc lịch vì phải nhập thủ công; có nguy cơ bỏ sót thông báo. |

**Bottleneck chính:**
1. **Thông tin phân tán:** Thông báo và deadline xuất hiện trên nhiều nền tảng, khiến người học phải kiểm tra thủ công từng nguồn.

2. **Khó xác định thông tin ưu tiên:** Thông báo quan trọng có thể bị lẫn với tin nhắn trao đổi thông thường, khiến người học không phát hiện kịp yêu cầu cần xử lý.

*Mục tiêu:** Xây dựng quy trình hỗ trợ sinh viên tổng hợp thông báo học tập từ nhiều nền tảng, tự động nhận diện những thông báo cần hành động, trích xuất deadline và hiển thị tại một nơi. Giảm thời gian kiểm tra thủ công và nguy cơ bỏ sót thông tin quan trọng.

**Phạm vi đề xuất:** Discord, Gmail, Outlook, Phoenix và Zalo. Trong MVP, chỉ xử lý các nguồn có thể truy cập hợp lệ hoặc dữ liệu mẫu do người dùng cung cấp; chưa giả định hệ thống có quyền kết nối tự động với toàn bộ nền tảng.

**Sơ đồ quy trình To-Be:**

```text
[BẮT ĐẦU]
     |
     v
[Thông báo học tập được phát sinh]
     |
     v
[WORKFLOW: Tiếp nhận dữ liệu từ nguồn được phép]
     |
     +----> Gmail / Outlook (nếu được cấp quyền)
     |
     +----> Discord (nếu được cấp quyền)
     |
     +----> Phoenix / Zalo (nếu có tích hợp hợp lệ)
     |
     +----> Nhập thủ công / Dán nội dung thông báo (MVP)
     |
     v
[RULE: Chuẩn hóa dữ liệu]
- Nguồn thông báo
- Nội dung gốc
- Thời gian nhận
- Đường dẫn tham chiếu (nếu có)
     |
     v
[RULE: Loại bỏ thông báo trùng lặp rõ ràng]
     |
     v
{Thông báo có dấu hiệu liên quan học tập?}
     |
     +---- KHÔNG
     |       |
     |       v
     |  [Lưu vào danh sách thông báo khác]
     |       |
     |       v
     |  [Cho phép người dùng xem lại]
     |
     +---- CÓ
           |
           v
[AI: Phân tích nội dung thông báo]
- Tóm tắt nội dung
- Nhận diện việc cần làm
- Trích xuất deadline nếu có
- Đề xuất mức độ ưu tiên
           |
           v
[RULE: Kiểm tra đầu ra AI]
- Có nội dung nguồn để đối chiếu?
- Deadline có xuất hiện trong nguồn?
- Định dạng ngày giờ có hợp lệ?
- Có thông tin mâu thuẫn hoặc thiếu?
           |
           v
{Kết quả rõ ràng và hợp lệ?}
     |
     +---- KHÔNG
     |       |
     |       v
     |  [Gắn cờ: CẦN XÁC MINH]
     |       |
     |       v
     |  [CON NGƯỜI: Kiểm tra nguồn gốc,
     |   chỉnh sửa hoặc bỏ qua]
     |
     +---- CÓ
           |
           v
[WORKFLOW: Đưa vào dashboard tập trung]
- Thông báo quan trọng
- Công việc cần thực hiện
- Deadline đề xuất
- Nguồn thông báo gốc
           |
           v
[CON NGƯỜI: Xem và xác nhận deadline]
           |
           v
{Người dùng xác nhận?}
     |
     +---- KHÔNG
     |       |
     |       v
     |  [Sửa / Bỏ qua / Xem thông báo gốc]
     |
     +---- CÓ
           |
           v
[RULE: Tạo nhiệm vụ và nhắc lịch]
           |
           v
[WORKFLOW: Hiển thị deadline đã xác nhận]
           |
           v
[CON NGƯỜI: Thực hiện công việc,
 đánh dấu hoàn thành]
           |
           v
[KẾT THÚC]
```

#### Phân chia trách nhiệm

| Thành phần | Vai trò trong quy trình | Giới hạn |
|---|---|---|
| **Workflow** | Tiếp nhận thông báo, chuyển dữ liệu giữa các bước, cập nhật dashboard và danh sách công việc. | Chỉ xử lý nguồn dữ liệu được phép truy cập; không tự vượt qua cơ chế xác thực của nền tảng. |
| **Rule** | Chuẩn hóa thông báo, lọc trùng, kiểm tra định dạng deadline, áp dụng quy tắc nhắc lịch. | Không tự suy đoán thời hạn khi nguồn không cung cấp đủ thông tin. |
| **AI** | Tóm tắt thông báo, trích xuất việc cần làm, đề xuất deadline và mức độ ưu tiên. | Không được tự tạo deadline, thay đổi nội dung gốc hoặc khẳng định thông tin chưa được xác minh. |
| **Con người (HITL)** | Kiểm tra thông báo quan trọng, xác nhận/chỉnh sửa deadline, quyết định tạo nhiệm vụ và hoàn thành công việc. | Giữ quyền quyết định cuối cùng, có thể bỏ qua mọi đề xuất của AI. |

#### Boundary — Ranh giới an toàn

1. **AI không được tự ý tạo hoặc thay đổi deadline.** Nếu không xác định được thời hạn từ nguồn, hệ thống phải hiển thị "Chưa xác định" hoặc "Cần xác minh".
2. **AI không được tự động xác nhận thông tin, nộp bài tập, gửi email hoặc nhắn tin thay người dùng.**
3. **Mọi deadline do AI trích xuất phải có thông báo gốc để đối chiếu.**
4. **Chỉ tạo lịch nhắc chính thức sau khi người dùng xác nhận.**
5. **Không truy cập tin nhắn, email hoặc dữ liệu cá nhân khi chưa được cấp quyền.**
6. **Thông báo bị AI đánh giá là không quan trọng vẫn phải có cách xem lại**, tránh bỏ sót thông tin.
7. **Thông báo có thời gian mơ hồ hoặc mâu thuẫn phải được gắn cờ**, không tự chọn một deadline.

#### Phương án quay về (Fallback) khi AI sai hoặc không hoạt động

| Tình huống | Phương án xử lý |
|---|---|
| AI trích xuất sai deadline | Hiển thị nội dung gốc, cho phép người dùng chỉnh sửa và xác nhận lại. |
| AI không tìm thấy deadline | Đánh dấu "Chưa xác định", không tự tạo thời hạn. |
| AI phân loại sai thông báo quan trọng | Cho phép xem toàn bộ thông báo, tìm kiếm và đánh dấu quan trọng thủ công. |
| AI tạo nội dung không có trong nguồn | Không chấp nhận thông tin không thể đối chiếu; yêu cầu kiểm tra thủ công. |
| AI không hoạt động hoặc API lỗi | Chuyển sang chế độ Rule + Manual: lọc theo từ khóa, hiển thị thông báo gốc và nhập deadline thủ công. |
| Không thể kết nối một nền tảng | Thông báo lỗi đồng bộ, giữ dữ liệu đã có và cho phép người dùng dán nội dung thủ công. |
| Hai nguồn cung cấp deadline mâu thuẫn | Hiển thị cả hai nguồn, đánh dấu "Cần xác minh" và yêu cầu người dùng quyết định. |

**Điểm can thiệp AI:** Sau bước chuẩn hóa và lọc thông báo, trước khi đưa thông tin vào dashboard và tạo lịch nhắc.

**Quyền quyết định cuối cùng:** Sinh viên/học viên sử dụng hệ thống.

**Nguyên tắc thiết kế:** AI đóng vai trò hỗ trợ (augment), không tự động thay thế (automate) quyết định của người dùng.

**Trạng thái:** Đây là quy trình To-Be đề xuất, chưa phải hệ thống đã triển khai hoặc được kiểm chứng thực tế. Các tích hợp nền tảng và hiệu quả giảm thời gian cần được thử nghiệm trong MVP.

### 4.3. Before / after

**Mục tiêu so sánh:** Đánh giá sự thay đổi kỳ vọng giữa quy trình hiện tại (As-Is) và quy trình đề xuất (To-Be) trong việc theo dõi thông báo học tập, xác định deadline và quản lý công việc.

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
| :--- | :--- | :--- | :--- |
| **Số bước** | 5 bước chính | 4 bước người dùng cần thực hiện | Trước: kiểm tra từng nền tảng → đọc và tìm thông tin → xác minh deadline → ghi nhớ/tạo nhắc lịch → thực hiện công việc. Sau: mở dashboard → xem thông báo đã phân tích → xác nhận/chỉnh sửa deadline → thực hiện công việc. Chỉ tính các bước người dùng trực tiếp thực hiện, không tính các bước xử lý nội bộ của hệ thống. |
| **Tổng thời gian** | Khoảng 15–20 phút/ngày, có ngày lên tới 30 phút | Mục tiêu 5–10 phút/ngày | Baseline ban đầu dựa trên ước tính của người tham gia 01, chưa đại diện cho toàn bộ sinh viên. Mục tiêu sau triển khai cần được kiểm chứng bằng thử nghiệm MVP trên cùng loại tác vụ. |
| **Số bước thủ công** | 5 bước có sự tham gia thủ công | 3–4 bước tùy trường hợp | Hệ thống đề xuất tự động tiếp nhận, chuẩn hóa, lọc và trích xuất thông tin. Người dùng vẫn cần xem, xác nhận/chỉnh sửa deadline và thực hiện công việc. |
| **Bottleneck chính** | Thông báo phân tán trên Discord, Gmail, Outlook, Phoenix và Zalo; phải tự tìm thông tin quan trọng và ghi nhớ deadline | Giảm việc chuyển đổi nền tảng; tập trung thông báo cần hành động và deadline vào một dashboard | Hiệu quả phụ thuộc vào khả năng tiếp nhận dữ liệu hợp lệ và độ chính xác của quá trình phân tích thông báo. |
| **Rủi ro mới phát sinh** | Chủ yếu là bỏ sót thông báo, ghi nhớ sai hoặc quên nhập lịch nhắc | AI trích xuất sai deadline, phân loại sai mức độ ưu tiên, lỗi đồng bộ, lộ dữ liệu cá nhân | Giảm rủi ro bằng cách giữ nguồn gốc thông báo, yêu cầu người dùng xác nhận deadline, giới hạn quyền truy cập và cho phép quay về chế độ Rule + Manual. |

**Nhận xét:**

Quy trình To-Be được kỳ vọng giảm thao tác kiểm tra thủ công và thời gian tìm kiếm thông báo, nhưng không loại bỏ hoàn toàn vai trò của người học.

Việc ứng dụng Workflow và Rule giúp tự động hóa những thao tác có quy tắc rõ ràng, trong khi AI chỉ hỗ trợ tóm tắt, phân loại và trích xuất deadline. Người dùng vẫn giữ quyền xác nhận thông tin trước khi tạo lịch nhắc.

**Success Metrics đề xuất cho MVP:**

1. **Thời gian xử lý thông báo:** Giảm thời gian kiểm tra và tổng hợp từ mức baseline ban đầu 15–20 phút/ngày xuống mục tiêu 5–10 phút/ngày.
2. **Deadline Extraction Accuracy:** Ít nhất 90% deadline được trích xuất chính xác trên tập dữ liệu thử nghiệm có nhãn.
3. **Important Notification Recall:** Phát hiện ít nhất 95% thông báo quan trọng trong tập thử nghiệm, ưu tiên hạn chế bỏ sót.
4. **User Confirmation:** 100% deadline do AI đề xuất phải được người dùng xác nhận trước khi tạo lịch nhắc chính thức.

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên/học viên tham gia chương trình đào tạo có nhiều hoạt động như workshop, standup, lab và teamwork; thường xuyên nhận thông báo từ Discord, Gmail, Outlook, Phoenix và Zalo. |
| **Quy trình** | Người học phải chủ động mở từng nền tảng để kiểm tra thông báo, đọc và xác định nội dung quan trọng, tìm deadline, hỏi lại bạn học hoặc lab-coach nếu thông tin chưa rõ, sau đó tự ghi nhớ hoặc nhập lịch nhắc thủ công. |
| **Bottleneck** | Thông báo học tập và deadline bị phân tán trên nhiều nền tảng, không có điểm tổng hợp thống nhất. Người học phải chuyển đổi giữa các ứng dụng, tự lọc thông tin quan trọng và nhập deadline thủ công. Những thông báo yêu cầu hành động gấp có nguy cơ bị bỏ sót. |
| **Impact** | Tốn thời gian kiểm tra và tổng hợp thông báo; tăng tải nhận thức khi phải theo dõi nhiều nguồn; có nguy cơ bỏ lỡ email quan trọng, deadline hoặc yêu cầu xác nhận. Trong phỏng vấn ban đầu, một người tham gia cho biết mất khoảng 15–20 phút/ngày, đôi khi 30 phút, và từng suýt bỏ lỡ email Outlook có hạn xác nhận lúc 18h. |
| **Success Metric (baseline → target, cách đo)** | **Metric 1 — Thời gian kiểm tra và tổng hợp:** Baseline ban đầu 15–20 phút/ngày (ước tính của 1 người tham gia) → mục tiêu 5–10 phút/ngày. Đo bằng nhật ký thời gian hoặc quan sát người dùng thực hiện cùng một tập tác vụ trước/sau MVP. <br><br> **Metric 2 — Độ chính xác trích xuất deadline:** Baseline chưa đo → mục tiêu ≥90% deadline được trích xuất chính xác. Đo trên tập thông báo được gán nhãn thủ công, so sánh ngày, giờ và ngữ cảnh deadline với kết quả hệ thống. <br><br> **Metric 3 — Khả năng phát hiện thông báo quan trọng:** Baseline chưa đo → mục tiêu Recall ≥95%. Đo bằng số thông báo quan trọng được hệ thống phát hiện chia cho tổng số thông báo quan trọng trong tập kiểm thử đã gán nhãn. <br><br> **Metric 4 — Kiểm soát của người dùng:** Baseline chưa đo → mục tiêu 100% deadline do AI đề xuất được người dùng xác nhận trước khi tạo lịch nhắc chính thức. Đo bằng log thao tác xác nhận trên MVP. |
| **Boundary (AI không được làm gì; khi nào cần con người kiểm tra — HITL)** | AI chỉ hỗ trợ tóm tắt, phân loại thông báo, trích xuất deadline và đề xuất mức độ ưu tiên. **Không được** tự bịa hoặc thay đổi deadline, tự gửi email/tin nhắn, xác nhận thông tin, nộp bài hoặc truy cập dữ liệu chưa được cấp quyền. **HITL:** Người dùng phải kiểm tra và xác nhận deadline trước khi tạo lịch nhắc; khi thông tin thiếu, mơ hồ, mâu thuẫn hoặc AI không xử lý được, hệ thống hiển thị thông báo gốc và chuyển sang xác minh thủ công. MVP chỉ sử dụng dữ liệu được cung cấp hoặc truy cập hợp lệ, không giả định tích hợp được toàn bộ 5 nền tảng. |

### Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không

**Phản biện đề xuất từ AI (nhóm cần thảo luận và xác nhận):**

- **Phản biện 1:** Phạm vi tích hợp cả Discord, Gmail, Outlook, Phoenix và Zalo có thể quá lớn đối với MVP, đặc biệt khi một số nền tảng chưa xác minh được khả năng truy cập dữ liệu hợp lệ.
  - **Đề xuất xử lý:** Đồng ý thu hẹp MVP. Trước tiên thử nghiệm với dữ liệu thông báo do người dùng dán hoặc nhập thủ công; sau đó mở rộng sang những nền tảng có phương thức tích hợp được phép.

- **Phản biện 2:** Mục tiêu giảm thời gian từ 15–20 phút xuống 5–10 phút/ngày chưa đủ bằng chứng, vì hiện chỉ có dữ liệu tự ước tính của một người tham gia.
  - **Đề xuất xử lý:** Giữ đây là mục tiêu giả thuyết, không trình bày như kết quả đã đạt được. Tiếp tục phỏng vấn và đo thời gian thực tế trong thử nghiệm MVP.

- **Phản biện 3:** AI có thể nhận diện sai deadline, đặc biệt với những thông báo dùng cách diễn đạt mơ hồ như "cuối ngày", "trước buổi học tiếp theo" hoặc không ghi rõ ngày.
  - **Đề xuất xử lý:** Đồng ý cần cơ chế Human-in-the-loop. AI chỉ đề xuất deadline; người dùng xác nhận trước khi tạo lịch nhắc. Nếu thông tin không rõ, hệ thống đánh dấu "Cần xác minh".

- **Phản biện 4:** Nếu chỉ tổng hợp thông báo và tạo lịch nhắc, giải pháp có thể trùng với Google Calendar, Microsoft To Do hoặc Notion.
  - **Đề xuất xử lý:** Làm rõ giá trị khác biệt cần kiểm chứng: giảm công sức đọc, tìm kiếm và chuyển đổi thông báo học tập thành các công việc cần hành động, thay vì chỉ cung cấp thêm một ứng dụng lịch.

**Trạng thái phản biện:** Các nội dung trên là phản biện do AI đề xuất và hướng xử lý gợi ý, chưa phải ý kiến chính thức được nhóm thống nhất. Nhóm cần xác nhận mức độ đồng ý trước khi đưa vào bản nộp cuối cùng.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**1. Độ mơ hồ cao (High Ambiguity):**

- Thông báo học tập được viết dưới nhiều hình thức khác nhau: email, tin nhắn, thông báo hệ thống và trao đổi nhóm.
- Deadline không phải lúc nào cũng được ghi rõ. Ví dụ: "Nộp trước buổi học tiếp theo", "Hoàn thành trong hôm nay", "Xác nhận trước 18h".
- Một thông báo có thể chứa nhiều yêu cầu, nhiều mốc thời gian hoặc thông tin chưa đầy đủ.
- Mức độ quan trọng của thông báo phụ thuộc vào ngữ cảnh học tập và vai trò của từng sinh viên.
- Cần phân biệt thông báo chính thức, trao đổi thông thường và những nội dung yêu cầu hành động.

**2. Độ phức tạp cao (High Complexity):**

- Thông tin phân tán trên Discord, Gmail, Outlook, Phoenix và Zalo, mỗi nền tảng có cách tổ chức và khả năng truy cập dữ liệu khác nhau.
- Cần thực hiện nhiều công đoạn: tiếp nhận dữ liệu, chuẩn hóa, lọc trùng, phân loại, trích xuất deadline và hiển thị kết quả.
- Có thể xuất hiện thông báo trùng lặp, cập nhật deadline hoặc mâu thuẫn giữa các nguồn.
- Hệ thống cần bảo đảm quyền riêng tư, kiểm soát quyền truy cập và khả năng truy vết về thông báo gốc.
- Khi AI xử lý sai hoặc không hoạt động, hệ thống vẫn phải cho phép người dùng kiểm tra và nhập thông tin thủ công.

**Kết luận:**

Bài toán có cả độ mơ hồ và độ phức tạp cao nếu xét toàn bộ quy trình đa nền tảng. Tuy nhiên, không phải mọi công đoạn đều cần AI.

- **Workflow:** Tiếp nhận và chuyển dữ liệu giữa các bước.
- **Rule:** Chuẩn hóa, lọc trùng rõ ràng, kiểm tra định dạng và tạo nhắc lịch.
- **AI:** Phân tích nội dung ngôn ngữ tự nhiên, tóm tắt, phân loại và đề xuất deadline.
- **Human-in-the-loop:** Xác minh những thông tin quan trọng, mơ hồ hoặc có nguy cơ sai lệch.

Vì vậy, nhóm đề xuất mô hình kết hợp **Workflow + Rule + AI + Human-in-the-loop**, thay vì sử dụng AI để tự động hóa toàn bộ quy trình.

**Lưu ý về MVP:** Khi thu hẹp phạm vi sang xử lý thông báo do người dùng cung cấp thủ công, độ phức tạp tích hợp sẽ giảm. Nhóm cần đánh giá lại ma trận sau khi xác định phạm vi MVP và kiểm chứng các giả định kỹ thuật.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Thống nhất một kênh thông báo chính, yêu cầu sinh viên tự ghi deadline vào Google Calendar, Notion hoặc bảng theo dõi chung. | Khi số lượng thông báo ít, nguồn thông tin ổn định và người học có thể tự tổng hợp mà không mất nhiều thời gian. | Vẫn phải kiểm tra nhiều nền tảng, nhập deadline thủ công và phụ thuộc vào thói quen cá nhân; có nguy cơ bỏ sót thông báo. | **Không chọn làm giải pháp chính**, nhưng sử dụng làm phương án đối chứng (baseline). |
| **Rule** | Lọc thông báo theo từ khóa như "deadline", "nộp bài", "xác nhận", "trước ngày"; nhận diện định dạng ngày giờ rõ ràng và tạo danh sách thông báo cần kiểm tra. | Khi thông báo có cấu trúc tương đối thống nhất, từ khóa rõ ràng và deadline được viết theo định dạng cố định. | Dễ bỏ sót cách diễn đạt không chứa từ khóa; khó hiểu ngữ cảnh, thời hạn tương đối hoặc nhiều yêu cầu trong cùng một thông báo. | **Chọn làm thành phần hỗ trợ**, dùng để lọc, kiểm tra định dạng và xử lý những trường hợp đơn giản. |
| **Workflow** | Xây dựng quy trình tiếp nhận thông báo từ nguồn hợp lệ hoặc dữ liệu người dùng cung cấp → chuẩn hóa → lọc bằng Rule → dùng AI để tóm tắt, phân loại và đề xuất deadline → người dùng xác nhận → hiển thị trên dashboard và tạo lịch nhắc. | Khi cần xử lý nhiều công đoạn theo trình tự xác định, có thể kiểm soát đầu vào/đầu ra và yêu cầu người dùng xác nhận trước hành động quan trọng. | Phụ thuộc vào chất lượng dữ liệu, khả năng tích hợp, độ chính xác của AI và thiết kế các bước kiểm tra. | **CHỌN — Mức can thiệp chính**, kết hợp Rule + AI + Human-in-the-loop. |
| **Agent** | Sử dụng AI Agent tự lựa chọn công cụ, truy cập các nền tảng được cấp quyền, tìm kiếm thông báo, lập kế hoạch và chủ động thực hiện các hành động liên quan đến deadline. | Khi bài toán có nhiều bước thay đổi linh hoạt, không thể xác định trước luồng xử lý và thực sự cần AI tự quyết định cách sử dụng công cụ. | Khó kiểm soát hành động, có thể suy luận sai deadline, truy cập dữ liệu ngoài phạm vi, tạo tác vụ sai; chi phí và độ phức tạp triển khai cao. | **Chưa chọn**, vì MVP chưa cần quyền tự chủ cao và rủi ro vượt quá lợi ích kỳ vọng. |

**Mức chọn:** **Workflow kết hợp Rule + AI hỗ trợ + Human-in-the-loop (HITL).**

**Vì sao chọn mức này:**

1. Quy trình tổng hợp thông báo có các bước tương đối rõ ràng: tiếp nhận dữ liệu, chuẩn hóa, lọc, phân tích, xác nhận và tạo lịch nhắc. Vì vậy, Workflow có thể điều phối các bước mà không cần Agent tự chủ.
2. Rule phù hợp để xử lý những thông báo có cấu trúc rõ ràng, giúp giảm số trường hợp phải sử dụng AI.
3. AI có giá trị ở những bước cần hiểu ngôn ngữ tự nhiên như tóm tắt nội dung, nhận diện yêu cầu cần hành động và trích xuất deadline.
4. Human-in-the-loop giúp người dùng kiểm tra và xác nhận các thông tin quan trọng trước khi tạo lịch nhắc chính thức.
5. Workflow cho phép theo dõi từng bước, kiểm thử riêng từng thành phần và quay về chế độ Rule + Manual khi AI không hoạt động.

**Vì sao không chọn mức đơn giản hơn:**

- **No AI:** Có thể cải thiện cách tổ chức thông tin nhưng chưa giải quyết đầy đủ thao tác đọc, tìm kiếm và tổng hợp thông báo từ nhiều nguồn. Đây là phương án đối chứng cần thử nghiệm, không phải phương án bị loại bỏ hoàn toàn.
- **Chỉ dùng Rule:** Khó xử lý thông báo viết bằng ngôn ngữ tự nhiên, deadline tương đối hoặc những yêu cầu không chứa từ khóa cố định.
- **Workflow không có AI:** Có thể tự động hóa việc chuyển và hiển thị dữ liệu, nhưng khả năng trích xuất thông tin từ các thông báo phi cấu trúc vẫn hạn chế. Nhóm cần thử nghiệm để xác định AI có thực sự cải thiện kết quả so với Rule-only hay không.

**Vì sao không chọn Agent:**

Bài toán hiện tại chưa yêu cầu AI tự lập kế hoạch hoặc tự quyết định chuỗi hành động phức tạp. Việc sử dụng Agent có thể làm tăng chi phí, độ phức tạp và rủi ro đối với thông tin quan trọng như deadline.

**Định hướng MVP:**

- Đầu vào: Thông báo mẫu do người dùng cung cấp.
- Rule: Lọc từ khóa, chuẩn hóa dữ liệu và kiểm tra định dạng.
- AI: Tóm tắt, nhận diện công việc và trích xuất deadline đề xuất.
- HITL: Người dùng xác nhận hoặc chỉnh sửa kết quả.
- Đầu ra: Danh sách công việc và deadline trên dashboard.
- Fallback: Khi AI lỗi hoặc không chắc chắn, hiển thị thông báo gốc và cho phép nhập thủ công.

**Kết luận:** Nhóm lựa chọn mức Workflow vì phù hợp với quy trình có thể xác định trước, đồng thời tích hợp AI tại những bước cần xử lý ngôn ngữ tự nhiên. Đây là phương án đề xuất để kiểm chứng trong MVP, chưa phải kết luận rằng AI chắc chắn hiệu quả hơn các giải pháp đơn giản.

### 6.3. AI Canvas rút gọn


### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | AI phân tích nội dung thông báo học tập để: (1) phân loại thông báo có yêu cầu hành động hay không; (2) tóm tắt nội dung chính; (3) trích xuất công việc cần thực hiện và deadline nếu có; (4) đề xuất mức độ ưu tiên; (5) đánh dấu thông tin thiếu hoặc mơ hồ cần xác minh. Kết quả phải kèm nội dung nguồn để người dùng đối chiếu, không tự tạo deadline khi không có đủ căn cứ. |
| **Judgment** — con người cân nhắc, quyết định gì? | Sinh viên/học viên kiểm tra xem thông báo có liên quan đến mình không, nội dung AI trích xuất có chính xác không, deadline có đúng với thông báo gốc không và có cần tạo lịch nhắc hay không. Với thông tin mâu thuẫn, thiếu ngày giờ hoặc yêu cầu quan trọng, người dùng phải xác minh trước khi quyết định. |
| **Action** — hành động cuối cùng là gì, ai làm? | Sau khi người dùng xác nhận, hệ thống tạo nhiệm vụ và lịch nhắc theo quy tắc đã thiết lập, hiển thị trên dashboard tập trung. Người dùng quyết định thực hiện, chỉnh sửa, bỏ qua hoặc đánh dấu hoàn thành công việc. AI không tự gửi email, xác nhận thông tin, nộp bài hoặc thực hiện hành động thay người dùng. |
| **Outcome** — đo kết quả bằng gì? | **(1)** Thời gian kiểm tra và tổng hợp thông báo: baseline ban đầu 15–20 phút/ngày theo 1 người phỏng vấn → mục tiêu 5–10 phút/ngày. **(2)** Deadline Extraction Accuracy ≥90% trên tập dữ liệu có nhãn. **(3)** Important Notification Recall ≥95% trên tập thông báo được gán nhãn. **(4)** 100% deadline do AI đề xuất được người dùng xác nhận trước khi tạo lịch nhắc chính thức. Các ngưỡng này là mục tiêu thử nghiệm, chưa phải kết quả đạt được. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | **Dữ liệu cần thiết:** Nội dung thông báo gốc, nguồn gửi (Discord, Gmail, Outlook, Phoenix, Zalo), thời gian gửi/nhận, ngữ cảnh liên quan nếu được phép sử dụng và đường dẫn tham chiếu nếu có. **Tình trạng dữ liệu:** Có thể thu thập dữ liệu mẫu do người dùng tự cung cấp hoặc dán thủ công để thử nghiệm MVP. Chưa xác minh khả năng truy cập tự động hợp lệ với cả 5 nền tảng. Cần tạo tập dữ liệu thử nghiệm được gán nhãn về mức độ quan trọng, công việc và deadline để đánh giá AI. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Thu thập phản hồi từ thao tác xác nhận, chỉnh sửa hoặc từ chối kết quả AI của người dùng; ghi nhận trường hợp trích xuất sai deadline, bỏ sót thông báo quan trọng hoặc phân loại sai. Trong thử nghiệm MVP, so sánh đầu ra AI với nhãn do con người kiểm tra để tính Accuracy và Recall. Phân tích các lỗi thường gặp để cải thiện prompt, rule và quy trình. Chỉ sử dụng dữ liệu phản hồi cho mục đích cải thiện khi có sự đồng ý phù hợp của người dùng. |

#### Luồng ra quyết định theo AI Canvas

1. **Input:** Người dùng cung cấp thông báo học tập hoặc hệ thống nhận dữ liệu từ nguồn được cấp quyền.
2. **Prediction:** AI phân tích thông báo, xác định công việc, deadline và mức độ ưu tiên đề xuất.
3. **Judgment:** Người dùng kiểm tra thông báo gốc, xác nhận hoặc chỉnh sửa kết quả.
4. **Action:** Workflow tạo nhiệm vụ và lịch nhắc sau khi được xác nhận.
5. **Outcome:** Đánh giá thời gian xử lý, khả năng phát hiện thông báo quan trọng và độ chính xác deadline.
6. **Feedback:** Ghi nhận lỗi và chỉnh sửa để cải thiện hệ thống trong những lần thử nghiệm tiếp theo.

**Nguyên tắc thiết kế:** AI hỗ trợ người dùng ra quyết định (augment), không thay thế quyền quyết định của người dùng (automate). Mọi deadline quan trọng phải được xác minh trước khi tạo lịch nhắc chính thức.

**Phạm vi MVP:** Thử nghiệm trước với thông báo mẫu được cung cấp thủ công. Tích hợp tự động với các nền tảng sẽ được xem xét sau khi xác minh tính khả thi kỹ thuật, quyền truy cập và yêu cầu bảo vệ dữ liệu.

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
