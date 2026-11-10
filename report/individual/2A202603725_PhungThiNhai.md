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

> Điền sau khi làm nhóm, bằng việc bạn đã thực sự làm.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (deadline rải rác nhiều kênh) kèm câu hỏi "chỉ cần ghim bảng deadline là xong?" | Card #1 được nhóm chọn làm candidate |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt cho ý tưởng quản lý tiến độ nhóm của Nam: "Nhóm làm vài giờ có cần hệ thống này không? AI có cần thiết hơn checklist hoặc lịch nhắc?" | Giúp nhóm thấy dự án ngắn chỉ cần bảng phân công + lịch nhắc; ý tưởng này bị loại khỏi shortlist |
| Nhận phản biện | Câu hỏi tôi nhận được: "Bạn đã từng bỏ lỡ deadline chưa?" (Card #1); "Mỗi lần chỉ mất 20 phút, có đáng giải quyết không?" (Card #2); "Tính năng tìm kiếm và ghim tin nhắn có đủ chưa?" (Card #3) | Tôi đã sửa gì: thừa nhận chưa lỡ deadline nào → đổi pain thành mất thời gian + phụ thuộc bạn bè, đổi metric sang phút/ngày và số lần hỏi bạn |
| Gom cluster / cây OST | | |
| Chọn candidate problem | Đề xuất candidate #1, cung cấp số liệu baseline | Nhóm thống nhất chọn chủ đề của tôi |
| Kiểm chứng / research | Cung cấp số liệu tự ghi nhận và tín hiệu phản bác (lớp đã có kênh thông báo riêng nhưng ít dùng); thêm bộ lọc Gmail vào bảng research | Mục 3.2 và 3.3 báo cáo nhóm |
| Quy trình nhóm | Cung cấp quy trình hiện tại 4 bước kèm số phút từ Card #1 | Bổ sung dữ liệu cho mục 3.2 báo cáo nhóm |
| Problem Statement | Cung cấp Actor, Bottleneck, Impact từ Card #1 | Góp phần xác định pain là mất thời gian + lo bỏ sót, không phải đã lỡ hạn |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Dùng Claude gợi ý môi trường , ngữ cảnh và viết dạng Job Story | Gợi ý nhiều lăng kính, viết đúng mẫu Job Story | Không biết số liệu thật của tôi; một số ý là giả định chung chung của sinh viên (vd. "hẹn lịch họp nhóm" tôi không thực sự gặp) | Tự điền số liệu thật cho 3 problem chính (30 phút/ngày, lớp 85 người; 20 phút × 15 lần/tháng; 20–30 lần/tuần × 2–3 phút); bỏ "hẹn lịch họp nhóm". Số liệu của #4 (ôn thi) và #5 (chia tiền phòng) do AI ước lượng, tôi kiểm tra lại cho khớp trải nghiệm của mình |
| CP2 Problem Card | Nhờ Claude dựng khung card, quy trình nháp và đóng vai PM hoài nghi phản biện | Chỉ ra metric thiếu baseline, phương án không dùng AI có thể đã đủ | Đặt metric chính là "không lỡ deadline", trong khi tôi chưa lỡ lần nào; giả định pain là thiếu thông tin, thật ra là quá nhiều kênh và nhiễu; gợi ý kênh thông báo riêng mà không biết lớp đã có nhưng ít dùng | Đổi metric sang thời gian kiểm tra (30 → ≤ 5 phút/ngày) và số lần hỏi bạn bè (4 → ≤ 1 lần/tuần); sửa bottleneck thành "lọc thông báo của lead khỏi câu hỏi học viên"; ghi rõ kênh thông báo riêng đã có nhưng không hiệu quả. Số phút từng bước của Card #2, #3 là ước lượng, ghi rõ trong file |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md)
- The Mom Test — Rob Fitzpatrick
