# Báo cáo cá nhân — 2A202603725_PhungThiNhai

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Phùng Thị Nhài
- MSSV: 2A202603725
- Email trường (không bắt buộc, repo có thể để public): nhaipthe186985@fpt.edu.vn
- Tên nhóm: C2
- Link repo nhóm: https://github.com/hatrang200715/K5-L3B-DAY02-C2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi thông báo deadline, đổi lịch học nằm rải rác ở LMS, email, nhóm Zalo/Discord lớp, tôi muốn biết chắc tuần này phải nộp gì, hạn khi nào, để không phải lúc nào cũng lo bỏ sót và hỏi lại bạn bè | Tôi và các bạn cùng lớp (~85 người) | Mất ~30 phút/ngày (~3,5 giờ/tuần) xem LMS, email, group chat. Chưa lỡ deadline nào, nhưng phải hỏi bạn bè xác nhận hạn nộp ~4 lần/tuần |
| 2 | Tốn thời gian | Khi làm báo cáo nhóm, tôi muốn gom phần của mọi thành viên vào một file thống nhất định dạng, để nộp đúng hạn mà không phải sửa lại cả đêm | Người tổng hợp báo cáo trong nhóm (thường là tôi) | Lần gần nhất mất ~20 phút để ghép, sửa định dạng; ~15 lần/tháng → ~300 phút (~5 giờ)/tháng |
| 3 | Lặp lại | Khi cần tìm lại một file/link/quyết định cũ trong group chat nhóm, tôi muốn tìm ra trong vài giây, để không phải hỏi lại cả nhóm | Thành viên các nhóm học tập | 20–30 lần/tuần, mỗi lần 2–3 phút → ~40–90 phút/tuần |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi ôn thi một môn có nhiều slide và tài liệu đọc thêm, tôi muốn biết phần nào trọng tâm, để ôn đủ trong thời gian ngắn | Sinh viên ôn thi | (Ước lượng) Mỗi môn ~10–15 bộ slide; mất ~2–3 giờ/môn chỉ để lọc phần trọng tâm; ~4 môn/kỳ → ~8–12 giờ/kỳ |
| 5 | Pain từ người khác | Khi chi tiêu chung với bạn cùng phòng (điện, nước, đi chợ), chúng tôi muốn biết ai nợ ai bao nhiêu, để cuối tháng không tranh cãi | ~4 người ở chung phòng | (Ước lượng) Cuối tháng mất ~30 phút đối chiếu hóa đơn, tin nhắn chuyển khoản; thỉnh thoảng phải tính lại vì thiếu khoản |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Giữ: deadline rải rác nhiều kênh, gom báo cáo nhóm, tìm lại thông tin trong group chat (vì tôi gặp thường xuyên, ước lượng được thời gian); ôn thi, chia tiền phòng (có gặp nhưng ít thường xuyên hơn).
- Bỏ: "hẹn lịch họp nhóm" (tôi không gặp thường xuyên, không có dấu hiệu đo được).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 Deadline/thông báo nằm rải rác nhiều kênh | Tốn nhiều thời gian nhất (~3,5 giờ/tuần), lớp 85 người cùng gặp | Tôi chưa lỡ deadline nào → pain là tốn thời gian + phụ thuộc bạn bè, không phải lỡ hạn. Bạn khác có giống không? |
| 2 | #2 Gom báo cáo nhóm | Lặp lại nhiều (~15 lần/tháng), tổng ~5 giờ/tháng, quy trình rõ | Mỗi lần chỉ 20 phút — có đủ đau để giải không? |
| 3 | #3 Tìm lại thông tin trong group chat | Rất thường xuyên (20–30 lần/tuần), dễ kiểm chứng | Có thể đã được giải bằng tính năng ghim/tìm kiếm sẵn có |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi thông báo deadline, đổi lịch nằm rải rác ở LMS, email, nhóm Zalo/Discord, tôi muốn biết chắc tuần này phải nộp gì, hạn khi nào, để không phải lúc nào cũng lo bỏ sót và hỏi lại bạn bè |
| Actor | Sinh viên đang học nhiều môn/khóa cùng lúc |
| Thời điểm / bối cảnh | Đầu tuần và mỗi tối trước khi học; khi có thông báo đổi hạn |
| Quy trình hiện tại (3–7 bước) | 1) Mở LMS xem bài tập → 2) Mở email trường → 3) Lướt nhóm Zalo/Discord lớp → 4) Đối chiếu, chép hạn vào lịch/ghi chú → 5) Kiểm tra lại khi có tin đổi hạn |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: lướt group chat để lọc thông báo chính thức của lead ra khỏi rất nhiều câu hỏi của học viên, ~15 phút/ngày (ước lượng, sẽ đo log 1 tuần; một nửa tổng thời gian) |
| Impact (nếu không giải thì sao) | Mất ~3,5 giờ/tuần; luôn trong trạng thái lo bỏ sót thông tin; phụ thuộc bạn bè xác nhận (~4 lần/tuần); nguy cơ lỡ hạn khi bạn bè cũng không nhớ |
| Success metric (baseline → target) | Thời gian kiểm tra deadline: 30 phút/ngày → ≤ 5 phút/ngày. Số lần phải hỏi bạn bè về hạn nộp: ~4 lần/tuần → ≤ 1 lần/tuần. Đo bằng tự ghi log 1 tuần |
| Phương án không dùng AI | Lớp trưởng ghim 1 tin "bảng deadline" cập nhật; tạo Google Calendar chung của lớp; quy ước mọi thông báo hạn có hashtag `#deadline`. Lưu ý: lớp đã có kênh thông báo riêng nhưng ít được dùng, đa số vẫn đăng ở nhóm đông người → phương án này phụ thuộc thói quen của người đăng |
| Giả thuyết về AI (nếu có) | Trích hạn nộp từ tin nhắn/email vào một danh sách để người kiểm tra xác nhận |
| Cảm nhận nhanh | Rule (hashtag + lịch chung) có thể đã đủ; Workflow nếu thông báo viết tự do |

Quy trình nháp hiện tại:

```text
Tổng ~30 phút/ngày
[1] Mở LMS (1 phút)
   → [2] Đọc email trường (5 phút)
   → [3] Lướt group Zalo/Discord, lọc thông báo của lead khỏi câu hỏi học viên (15 phút)  ◀── BOTTLENECK
   → [4] Chép hạn vào lịch/ghi chú, hỏi bạn bè xác nhận (~9 phút; hỏi bạn ~4 lần/tuần)
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm báo cáo nhóm, tôi muốn gom phần của mọi thành viên vào một file thống nhất định dạng, để nộp đúng hạn mà không phải sửa lại cả đêm |
| Actor | Người tổng hợp báo cáo trong nhóm sinh viên |
| Thời điểm / bối cảnh | 1–2 ngày trước hạn nộp báo cáo nhóm |
| Quy trình hiện tại (3–7 bước) | 1) Chia phần → 2) Nhắc thành viên nộp → 3) Nhận nhiều file/định dạng khác nhau → 4) Ghép vào 1 file, sửa font, heading, đánh số, trích dẫn → 5) Đọc lại cho mạch lạc → 6) Nộp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: ghép và chỉnh định dạng, ~12/20 phút mỗi lần (ước lượng) |
| Impact (nếu không giải thì sao) | ~15 lần/tháng → ~300 phút (~5 giờ)/tháng; dễ nộp trễ, lỗi định dạng |
| Success metric (baseline → target) | Thời gian ghép + định dạng: 20 phút → ≤ 5 phút/báo cáo (~5 giờ → ~1,25 giờ/tháng). Đo bằng bấm giờ 5 báo cáo tiếp theo |
| Phương án không dùng AI | Dùng 1 template chung (Google Docs/Markdown) từ đầu; quy định deadline nội bộ sớm hơn 1 ngày; checklist định dạng |
| Giả thuyết về AI (nếu có) | Kiểm tra tính nhất quán văn phong/thuật ngữ giữa các phần |
| Cảm nhận nhanh | No AI / Rule (template + checklist là đủ cho phần định dạng) |

Quy trình nháp hiện tại:

```text
Tổng ~20 phút/lần, ~15 lần/tháng
Số phút từng bước là ước lượng
[1] Chia phần (3 phút)
   → [2] Nhắc nộp (2 phút)
   → [3] Nhận file rời (Word/Docs/ảnh)
   → [4] Ghép + sửa định dạng (12 phút)  ◀── BOTTLENECK
   → [5] Đọc lại (3 phút)
   → [6] Nộp
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần tìm lại một file/link/quyết định cũ trong group chat nhóm, tôi muốn tìm ra trong vài giây, để không phải hỏi lại cả nhóm |
| Actor | Thành viên nhóm học tập dùng Zalo/Discord |
| Thời điểm / bối cảnh | Khi bắt đầu làm bài, cần link tài liệu/quyết định đã chốt trước đó |
| Quy trình hiện tại (3–7 bước) | 1) Nhớ mang máng "hình như ai đã gửi" → 2) Dùng ô tìm kiếm thử vài từ khóa → 3) Kéo ngược lịch sử chat → 4) Không thấy thì nhắn hỏi nhóm → 5) Chờ người trả lời |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: kéo ngược lịch sử chat, ~1,5–2 phút trong 2–3 phút mỗi lần (ước lượng) |
| Impact (nếu không giải thì sao) | 20–30 lần/tuần → ~40–90 phút/tuần bị gián đoạn; làm phiền cả nhóm, có lúc dùng nhầm bản cũ |
| Success metric (baseline → target) | Thời gian tìm 1 thông tin: 2–3 phút → ≤ 30 giây (~40–90 → ≤ 15 phút/tuần). Đo bằng tự ghi log 1 tuần |
| Phương án không dùng AI | Ghim tin; 1 file "Tài nguyên nhóm" (Notion/Docs) ghi link + quyết định; quy ước đặt tên file |
| Giả thuyết về AI (nếu có) | Tóm tắt các quyết định đã chốt trong chat cuối mỗi buổi |
| Cảm nhận nhanh | No AI / Rule |

Quy trình nháp hiện tại:

```text
Tổng 2–3 phút/lần, 20–30 lần/tuần
Số phút từng bước là ước lượng
[1] Nhớ ra cần tìm
   → [2] Tìm bằng từ khóa (~30 giây)
   → [3] Kéo ngược lịch sử chat (~1,5–2 phút)  ◀── BOTTLENECK
   → [4] Không thấy thì nhắn hỏi nhóm (thỉnh thoảng)
   → [5] Chờ trả lời (vài phút đến vài giờ)
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Tốn thời gian nhất (~30 phút/ngày), lớp 85 người cùng dùng nhiều cổng thông tin, quy trình rõ và đo được.
- Câu hỏi muốn nhóm phản biện: "Đây có thật là bài toán cần giải, hay chỉ cần lớp trưởng ghim một bảng deadline là xong?"

### AI đã phản biện card thế nào

Prompt: "Đóng vai PM hoài nghi, chỉ ra lỗ hổng trong Problem Card #1, đừng viết lại."

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Success metric "không lỡ deadline" chưa có baseline thật; chưa biết học kỳ này đã lỡ bao nhiêu lần | Đồng ý | Tôi chưa lỡ deadline nào, nên đổi metric sang thời gian kiểm tra (30 → ≤ 5 phút/ngày) và số lần phải hỏi bạn bè |
| Có thể không phải vấn đề thiếu thông tin mà là thói quen trì hoãn; giải pháp tổng hợp thông báo không giải quyết được | Đồng ý một phần | Vấn đề thật không phải thiếu thông tin mà là **quá nhiều cổng + nhiễu**: trong nhóm, thông báo chính thức của lead bị lẫn giữa rất nhiều câu hỏi của học viên, nên tôi luôn sợ bỏ sót. Đã sửa bottleneck thành "lọc thông báo chính thức khỏi tin hỏi đáp" và thêm "luôn lo bỏ sót" vào Impact |
| Phương án không dùng AI (bảng deadline ghim + lịch chung) có thể giải 80% vấn đề; cần giải thích vì sao chưa ai làm | Không đồng ý hoàn toàn | Lớp đã có kênh thông báo riêng nhưng ít được dùng, đa số thông báo vẫn đăng ở nhóm đông người. Phương án không dùng AI vẫn giữ, nhưng ghi rõ điểm yếu: phụ thuộc thói quen của người đăng thông báo |
| Bottleneck "lướt group chat" cần đo bằng số phút thật, không phải cảm giác | Đồng ý | Ghi rõ 15 phút là ước lượng; sẽ tự ghi log 1 tuần để có baseline thật |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (deadline rải rác nhiều kênh) kèm câu hỏi "chỉ cần ghim bảng deadline là xong?" | Card #1 được nhóm chọn làm candidate |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt cho ý tưởng quản lý tiến độ nhóm của Nam: "Nhóm làm vài giờ có cần hệ thống này không? AI có cần thiết hơn checklist hoặc lịch nhắc?" | Giúp nhóm thấy dự án ngắn chỉ cần bảng phân công + lịch nhắc; ý tưởng này bị loại khỏi shortlist |
| Nhận phản biện | Câu hỏi tôi nhận được: "Bạn đã từng bỏ lỡ deadline chưa?" (Card #1); "Mỗi lần chỉ mất 20 phút, có đáng giải quyết không?" (Card #2); "Tính năng tìm kiếm và ghim tin nhắn có đủ chưa?" (Card #3) | Tôi đã sửa gì: thừa nhận chưa lỡ deadline nào → đổi pain thành mất thời gian + phụ thuộc bạn bè, đổi metric sang phút/ngày và số lần hỏi bạn |
| Gom cluster / cây OST | Tham gia nhóm các ý tưởng theo nhu cầu phía sau thay vì theo tên giải pháp. Các ý về deadline, thông báo lớp và tìm lại nội dung cũ đều liên quan đến việc người học phải tự tìm thông tin ở nhiều nơi, nhưng mức độ ảnh hưởng khác nhau | Nhóm tập trung vào cluster "thông báo học tập phân tán"; các ý "xây app/dashboard/chatbot" bị gạch khỏi cây OST vì là solution đội lốt opportunity |
| Chọn candidate problem | Đề xuất candidate #1, cung cấp số liệu baseline | Nhóm thống nhất chọn chủ đề của tôi |
| Kiểm chứng / research | Phỏng vấn 2 học viên ngoài nhóm qua Zalo (snapshot 02, 03); cung cấp số liệu tự ghi nhận và tín hiệu phản bác (lớp đã có kênh thông báo riêng nhưng ít dùng); thêm bộ lọc Gmail vào bảng research | Cả 2 người đều suýt lỡ vì deadline bị đổi → nhóm xác định pain cốt lõi là bỏ lỡ thay đổi deadline; 1 người chỉ mất 5–7 phút → tín hiệu phản bác về pain "tốn thời gian" |
| Quy trình nhóm | Cung cấp quy trình hiện tại 4 bước kèm số phút từ Card #1 | Bổ sung dữ liệu cho mục 3.2 báo cáo nhóm |
| Problem Statement | Cung cấp Actor, Bottleneck, Impact từ Card #1 | Góp phần xác định pain là mất thời gian + lo bỏ sót, không phải đã lỡ hạn |
| Mức can thiệp AI | Cùng nhóm cân nhắc phần nào xử lý được bằng Rule (lọc email, lọc theo người gửi), phần nào cần AI đọc thông báo viết tự do. Đề xuất AI không tự tạo deadline mà phải hiển thị nội dung và nguồn gốc để học viên kiểm tra | Nhóm chọn Workflow (Rule + AI + người xác nhận), không dùng Agent; boundary "mọi deadline phải có thông báo gốc để đối chiếu" |
| Quyết định | Đồng ý quyết định Not Yet; đề xuất giới hạn MVP vào thông báo mẫu/nội dung người dùng dán vào, chưa tích hợp toàn bộ nền tảng | Nhóm tránh cam kết tích hợp Discord, Gmail, Outlook, Phoenix, Zalo ngay từ đầu; ưu tiên kiểm tra khả năng nhận diện thông báo cần hành động và deadline |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Dùng Claude gợi ý danh sách problem ban đầu và viết dạng Job Story | Gợi ý nhiều lăng kính, viết đúng mẫu Job Story | Không biết số liệu thật của tôi; một số ý là giả định chung chung của sinh viên (vd. "hẹn lịch họp nhóm" tôi không thực sự gặp) | Tự điền số liệu thật cho 3 problem chính (30 phút/ngày, lớp 85 người; 20 phút × 15 lần/tháng; 20–30 lần/tuần × 2–3 phút); bỏ "hẹn lịch họp nhóm". Số liệu của #4 (ôn thi) và #5 (chia tiền phòng) do AI ước lượng, tôi kiểm tra lại cho khớp trải nghiệm của mình |
| CP2 Problem Card | Nhờ Claude dựng khung card, quy trình nháp và đóng vai PM hoài nghi phản biện | Chỉ ra metric thiếu baseline, phương án không dùng AI có thể đã đủ | Đặt metric chính là "không lỡ deadline", trong khi tôi chưa lỡ lần nào; giả định pain là thiếu thông tin, thật ra là quá nhiều kênh và nhiễu; gợi ý kênh thông báo riêng mà không biết lớp đã có nhưng ít dùng | Đổi metric sang thời gian kiểm tra (30 → ≤ 5 phút/ngày) và số lần hỏi bạn bè (4 → ≤ 1 lần/tuần); sửa bottleneck thành "lọc thông báo của lead khỏi câu hỏi học viên"; ghi rõ kênh thông báo riêng đã có nhưng không hiệu quả. Số phút từng bước của Card #2, #3 là ước lượng, ghi rõ trong file |
| CP4 Research | Nhờ Claude soạn bộ câu hỏi phỏng vấn theo The Mom Test và gợi ý công cụ để research (Gmail filter, Google Calendar) | Câu hỏi tập trung vào hành vi đã xảy ra ("lần gần nhất…", "tuần này…"), tránh hỏi "bạn có muốn dùng app không" | AI liệt kê công cụ nhưng không biết lớp đã có kênh thông báo riêng và kênh đó ít được dùng; không biết người dùng thực tế mất bao lâu | Tự phỏng vấn 2 học viên ngoài nhóm qua Zalo; ghi cả tín hiệu ủng hộ (2 người suýt lỡ vì đổi hạn) lẫn phản bác (1 người chỉ mất 5–7 phút); tự mở kiểm tra từng link research |
| CP5 Quy trình | Dùng AI hỗ trợ diễn đạt quy trình As-Is: mở LMS, đọc email, lướt nhóm chat, lọc thông tin rồi ghi deadline | Trình bày luồng công việc thành các bước dễ thảo luận, nhận ra bước lướt nhóm chat chiếm nhiều thời gian nhất | Quy trình AI đề xuất ban đầu quá chung, không phản ánh việc thông báo chính thức bị chìm giữa câu hỏi trong group chat | Điều chỉnh quy trình theo cách tôi thực sự làm, giữ số phút là ước lượng và ghi kế hoạch đo log 1 tuần |
| CP5–6 Problem Statement | Nhờ AI kiểm tra cách sắp xếp Actor, Bottleneck, Impact, Metric và Boundary | Giúp kiểm tra mô tả đã tập trung vào một người dùng và một vấn đề cụ thể chưa | AI có xu hướng diễn đạt pain thành "người học đã bỏ lỡ deadline", trong khi tôi chưa từng lỡ hạn và phỏng vấn chỉ cho thấy các trường hợp suýt bỏ lỡ | Giữ cách diễn đạt thận trọng: mất thời gian kiểm tra, lo bỏ sót, phải hỏi bạn bè xác nhận; tách rõ trải nghiệm của tôi với kết quả phỏng vấn |
| CP6 Mức can thiệp / quyết định | Dùng AI so sánh No AI, Rule, Workflow và Agent cho bài toán thông báo học tập | Thấy có thể bắt đầu bằng bộ lọc/quy tắc và luồng tổng hợp có bước xác nhận, chưa cần Agent | AI đề xuất kết nối nhiều nền tảng nhưng chưa chứng minh được khả năng truy cập và độ chính xác với mọi nguồn | Đề xuất MVP giới hạn ở thông báo mẫu hoặc nguồn khả thi; AI chỉ trích xuất để người học xác nhận, không tự quyết deadline |
| CP7 Reflection | Dùng AI hỗ trợ viết nháp phần Reflection | Gợi ý cách sắp xếp ý theo từng câu hỏi | Bản nháp đầu viết nhầm sang đề tài khác (Xanh SM) và có chi tiết không khớp dữ liệu (vd. "5–7 phút mỗi ngày" trong khi người được hỏi nói 5–7 phút cho lần kiểm tra gần nhất) | Đối chiếu lại với báo cáo nhóm và ghi chép phỏng vấn, sửa các chi tiết sai; giữ lại những ý đúng với trải nghiệm của tôi |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các bạn trình bày, em nhận ra mỗi người có một cách nhìn khác nhau về những bất tiện trong học tập và sinh hoạt. Nam đưa ra các vấn đề về theo dõi tiến độ nhóm, tổng hợp kiến thức từ nhiều tài liệu và tìm nguồn đáng tin; Hạnh đưa ra các vấn đề như xác minh ra vào Vinhomes giờ giới nghiêm hay biết căn tin còn bàn trống. Có vấn đề nghe qua tưởng rất cần một ứng dụng mới, nhưng khi bị hỏi "chi phí của giải pháp có cao hơn lợi ích không?" hoặc "nhóm chỉ làm vài giờ thì có cần hệ thống riêng không?", nhóm thấy một bảng phân công, lịch nhắc hay tính năng có sẵn đã giải quyết được phần lớn.

Em cũng học được rằng không nên chỉ chọn vấn đề vì bản thân thấy nó phiền. Cần xác định ai gặp vấn đề, gặp trong hoàn cảnh nào, tần suất ra sao và hậu quả cụ thể là gì. Khi nghe các bạn phản biện card của em, em thấy các con số về thời gian giúp cuộc trao đổi rõ hơn, nhưng số liệu tự ước lượng vẫn cần được kiểm tra. Vì vậy, em cần phân biệt trải nghiệm của mình với kết luận có thể áp dụng cho cả lớp.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Theo em, nhóm có lúc solution-first khi bắt đầu nói về một hệ thống kết nối LMS, email, Zalo và Discord để gom tất cả thông báo về một nơi. Đây là hướng giải pháp dễ hình dung nên mọi người nhanh chóng bàn đến dashboard, chatbot và cách tích hợp. Tuy nhiên, nếu chưa hiểu rõ người học đang gặp khó khăn ở bước nào thì việc kết nối nhiều nền tảng có thể khiến phạm vi lớn hơn cần thiết.

Nhóm nhận ra điều này khi làm cây OST: các ý như "xây ứng dụng AI tổng hợp thông báo", "tạo chatbot quản lý deadline" hay "xây dashboard" đều bị gạch vì là giải pháp, không phải nhu cầu. Khi quay lại quy trình hiện tại, nhóm thấy người học không chỉ mở nhiều ứng dụng mà còn phải lọc thông báo chính thức khỏi tin trao đổi, xác định nội dung cần hành động rồi tự ghi nhớ deadline.

Cách xử lý là quay lại hỏi người dùng và xem xét các giải pháp đơn giản như bộ lọc email, lịch chung hoặc quy ước đăng thông báo. Nếu một quy tắc hoặc thay đổi thói quen đã giải quyết được vấn đề thì chưa chắc phải dùng AI. AI chỉ nên được cân nhắc ở phần nội dung viết tự do khó xử lý bằng quy tắc cố định.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Với Problem Card #1, ban đầu em khá tập trung vào việc phải kiểm tra nhiều kênh và lo rằng mình có thể bỏ lỡ deadline. Khi được hỏi "Bạn đã từng bỏ lỡ deadline chưa?", em phải thừa nhận là chưa. Câu hỏi này khiến em nhận ra nếu viết vấn đề thành "sinh viên thường xuyên bỏ lỡ deadline" thì không đúng với trải nghiệm của mình và cũng chưa có đủ bằng chứng.

Sau đó, em điều chỉnh cách mô tả pain point. Vấn đề đã xác nhận ở bản thân em là phải dành khoảng 30 phút mỗi ngày để xem nhiều kênh và hỏi bạn bè khoảng 4 lần mỗi tuần để xác nhận hạn nộp. Vì vậy, metric chính nên là thời gian kiểm tra thông báo và số lần phải hỏi lại, thay vì số deadline bị bỏ lỡ. Em cũng ghi rõ các con số này là tự ước lượng và cần ghi log để có baseline đáng tin cậy hơn.

Khi nhờ AI đóng vai PM hoài nghi, em nhận thêm một phản biện: lớp có thể chỉ cần một bảng deadline ghim sẵn. Em bổ sung thông tin rằng lớp đã có kênh thông báo riêng nhưng ít được sử dụng, còn thông báo vẫn thường xuất hiện trong nhóm đông người. Dù vậy, em không kết luận giải pháp đơn giản chắc chắn thất bại mà giữ nó như phương án No AI để nhóm so sánh.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều làm em chú ý nhất là cả hai học viên ngoài nhóm mà em phỏng vấn đều kể về tình huống suýt bỏ lỡ do deadline bị thay đổi: một bạn không để ý giảng viên đổi hạn trên LMS, bạn còn lại không biết deadline đã được dời vì giảng viên chỉ báo qua Zalo nhóm mà LMS không có thông báo mới. Trước đó, em tập trung vào việc phải mở nhiều kênh và mất thời gian đọc thông báo. Kết quả này cho thấy điểm gãy thật có thể là thông tin thay đổi nằm ở kênh mà người học không kiểm tra đúng lúc. Tuy vậy, hai trường hợp chưa đủ để kết luận tất cả học viên đều thường xuyên gặp tình trạng này.

Kết quả phỏng vấn cũng khiến em phải xem lại giả định ban đầu. Một bạn chỉ mất khoảng 5–7 phút cho lần kiểm tra gần nhất, thấp hơn nhiều so với khoảng 30 phút mỗi ngày em tự ước lượng, vì bạn ấy đã có thói quen ghim tin, ghi vào Google Keep và bật thông báo LMS về mail. Điều đó cho thấy trải nghiệm của em không đại diện cho tất cả.

Qua research, em cũng thấy Gmail filter, Google Calendar hay Microsoft To Do đã hỗ trợ lọc email hoặc ghi nhớ lịch. Vì vậy, nhóm cần làm rõ khoảng trống còn lại thay vì nói rằng chưa có công cụ nào. Em nghĩ cần phỏng vấn thêm người dùng có thói quen khác nhau và ghi nhận thời gian thực tế trước khi đặt mục tiêu giảm thời gian.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất với em là giới hạn vấn đề sao cho đủ cụ thể nhưng không làm sai những gì đã được kiểm chứng. Ban đầu, em muốn mô tả rằng sinh viên có thể bỏ lỡ deadline vì thông báo nằm rải rác ở LMS, email và nhóm chat. Nhưng khi được hỏi về trải nghiệm thực tế, em nhận ra bản thân chưa từng lỡ deadline. Nếu vẫn viết như vậy thì Problem Statement sẽ phóng đại mức độ nghiêm trọng.

Em phải tách ba lớp thông tin: điều bản thân đã trải nghiệm, điều người được phỏng vấn chia sẻ và điều nhóm mới đang giả thuyết. Khoảng 30 phút mỗi ngày và 4 lần hỏi bạn bè mỗi tuần là số liệu tự ước lượng của em; hai trường hợp suýt bỏ lỡ vì deadline thay đổi là thông tin từ phỏng vấn; còn việc AI có thể nhận diện chính xác deadline vẫn chỉ là giả thuyết cần thử nghiệm.

Một phần khó nữa là chọn metric. "Không bỏ lỡ thông báo" nghe là mục tiêu tốt nhưng khó đo nếu chưa có baseline. Em chuyển sang thời gian kiểm tra thông báo và số lần phải hỏi bạn bè, đặt mục tiêu 5 phút mỗi ngày và tối đa một lần hỏi mỗi tuần như target thử nghiệm, không phải kết quả đã đạt. Em hiểu rằng Problem Statement tốt cần mô tả đúng người dùng, đúng điểm nghẽn và có cách kiểm chứng.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, em sẽ ghi lại thời gian kiểm tra thông báo ngay từ đầu thay vì dựa vào trí nhớ và ước lượng. Em cũng sẽ phỏng vấn nhiều người hơn, cả những bạn chỉ dùng một hai nền tảng và những bạn theo dõi nhiều group chat, để nhóm không chọn giải pháp chỉ phù hợp với một kiểu người dùng.

Em cũng muốn hỏi sâu hơn về từng tình huống: thông báo nào bị chìm, ai gửi, deadline có thay đổi không, người học phát hiện bằng cách nào. Những câu hỏi đó giúp phân biệt ba vấn đề liên quan nhưng không giống nhau: tốn thời gian kiểm tra, không biết thông báo nào quan trọng, và bỏ sót thay đổi deadline.

Với nhóm, em sẽ phản biện mạnh hơn về tính khả thi của việc kết nối các nền tảng. Không nên mặc định lấy được dữ liệu từ mọi hệ thống như Phoenix hay Zalo. Em cũng muốn nhóm so sánh MVP với Gmail filter, Google Calendar hoặc một bảng deadline chung; nếu cách đơn giản đã đủ tốt thì phải giải thích rõ giá trị tăng thêm của AI. Ngoài ra, sau phỏng vấn em nghĩ Problem Statement v1 nên đưa tiêu chí "bắt được thông báo đổi hạn" lên ưu tiên cao hơn.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán nhóm chọn là học viên phải kiểm tra nhiều kênh như LMS, email, Discord và Zalo để tìm thông báo học tập, nên mất thời gian và có thể không nhận ra kịp những thay đổi deadline. Quy trình hiện tại gồm mở từng kênh, đọc và lọc thông báo, đối chiếu rồi tự ghi nhớ hoặc nhập deadline vào lịch; bước nghẽn là lọc thông báo quan trọng giữa rất nhiều tin trao đổi. Nhóm đo bằng thời gian kiểm tra mỗi ngày, tỷ lệ phát hiện thông báo quan trọng và độ chính xác khi trích xuất deadline. Boundary là AI không được tự tạo hay sửa deadline, không tự gửi tin hay xác nhận thay người dùng, và mọi deadline phải kèm thông báo gốc để người học kiểm tra trước khi tạo nhắc việc. Nhóm chọn mức Workflow: Rule lọc trước, AI chỉ đọc nội dung viết tự do để trích xuất, con người xác nhận; không dùng Agent vì các bước đã cố định. Quyết định hiện tại là Not Yet, vì bằng chứng mới từ vài người và chưa thử MVP; nhóm sẽ phỏng vấn thêm, thử trên bộ thông báo mẫu và so sánh với cách làm thủ công trước khi quyết định có mở rộng hay không.

---

## 7. Tài liệu tham khảo

- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md)
- The Mom Test — Rob Fitzpatrick
- Báo cáo nhóm C2: [report/team/group_report.md](../team/group_report.md)
