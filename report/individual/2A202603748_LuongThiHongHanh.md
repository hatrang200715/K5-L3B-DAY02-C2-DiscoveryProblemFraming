# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Lương Thị Hồng Hạnh
- MSSV: 2A202603748
- Email trường (không bắt buộc, repo có thể để public): 26ai.hanhlth@vinuni.edu.vn
- Tên nhóm: C2
- Link repo nhóm: https://github.com/hatrang200715/K5-L3B-DAY02-C2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại| khi ra vào vinhomes vào giờ giới nghiêm, tôi muốn việc xác minh danh tính được thực hiện nhanh chóng và chính xác hơn để không phải tốn nhiều thời gian đứng chờ ngoài cổng| cư dân vinhomes| mỗi ngày 15 phút|
| 2 | Tốn thời gian| khi đến bữa ăn trưa, tôi muốn biết còn bao nhiêu bàn ăn còn trống dưới căn tin để không mất thời gian đi xuống rồi lại chờ đợi| học viên VinUni| mỗi ngày 30 phút|
| 3 | Tốn thời gian| khi di chuyển bằng xe buýt tôi muốn biết những cảnh báo về thời tiết tại tuyến đường của mình để chủ động thời gian di chuyển từ nhà đến trường| người dân đi xe buýt| 30 phút mỗi chặng, 2 lần/ ngày|
| 4 | Cần đọc, tổng hợp nhiều thông tin| Khi bắt đầu một ngày học, tôi muốn biết chính xác tất cả thông báo hay lịch học có liên quan đến tôi thay vì phải đọc quá nhiều kênh giao tiếp để tìm ra thông tin nào thật sự quan trọng với mình| học viên VinUni| mỗi ngày 30 phút|
| 5 | Pain từ người khác| khi sáng thức dậy, cư dân Vinhomes muốn biết những tiện ích nào đang sẵn sàng và những cảnh báo sớm từ trước để bố trí lịch cá nhân phù hợp như nên tập thể dục ở công viên vào khung giờ nào để tránh mưa hay ảnh hưởng cực đoan từ thời tiết| cư dân vinhomes| mỗi ngày 30 phút|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | xác minh danh tính (#1) | Giảm tải cho nhân viên an ninh, phối hợp nhiều hình thức check mà vẫn đạt được sự hài lòng của cư dân| Dữ liệu cá nhân truy cập khó và cần sự phối hợp của cư dân|
| 2 | tìm chỗ ăn trưa (#2) | Giảm thiểu thời gian tìm chỗ ăn trưa và giúp học viên kịp lịch học giữa buổi| Chi phí bỏ ra có nhiều hơn lợi ích đạt được|
| 3 | tổng hợp thông tin (#3)| Tránh bị miss những thông báo quan trọng khi tương tác trên các kênh chính thống quá nhiều| Yêu cầu dữ liệu bảo mật của chương trình học|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi ra vào vinhomes vào giờ giới nghiêm, tôi muốn việc xác minh danh tính được thực hiện nhanh chóng và chính xác hơn để không phải tốn nhiều thời gian đứng chờ ngoài cổng |
| Actor | Cư dân Vinhomes|
| Thời điểm / bối cảnh | Giờ giới nghiêm sau 23h mỗi ngày|
| Quy trình hiện tại (3–7 bước) | người dân xếp hàng đợi đến lượt -> xuất trình hợp đồng thuê nhà/chứng minh cư trú -> nhân viên an ninh xác nhận thông tin là đúng -> cho cư dân được vào cổng|
| Bottleneck (bước nào, mất bao nhiêu phút) | người dân xếp hàng đợi đến lượt, mất khoảng 15 - 20 phút|
| Impact (nếu không giải thì sao) | Gây ra rủi ro sai sót khi 1 nhân viên an ninh phải soi chiếu thông tin cho hàng đợi nhiều người trong môi trường trời tối thông tin nhìn lướt qua không rõ ràng|
| Success metric (baseline → target) | thời gian mỗi người phải đợi từ 23h - 3h giảm bao nhiêu phần trăm, số ca sai sót gây hậu quả mất mát được báo cáo|
| Phương án không dùng AI | đăng ký khi vào ở và quét CCCD để ra vào giờ giới nghiêm|
| Giả thuyết về AI (nếu có) | trích xuất camera an ninh để xác minh danh tính và những góc khuất bên trong khu cư dân có thể theo dõi cả hành vi trộm cắp tài sản|
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text
Người dân xếp hàng đợi đến lượt -> xuất trình hợp đồng thuê nhà/chứng minh cư trú -> nhân viên an ninh xác nhận thông tin là đúng -> cho cư dân được vào cổng
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến bữa ăn trưa, tôi muốn biết còn bao nhiêu bàn ăn còn trống dưới căn tin để không mất thời gian đi xuống rồi lại chờ đợi lỡ buổi học tiếp theo|
| Actor | Học viên VinUni|
| Thời điểm / bối cảnh | Giữa buổi học sáng và buổi học chiều tầm 13h - 14h|
| Quy trình hiện tại (3–7 bước) | Học viên tìm quanh khuôn viên trường nơi ăn trưa phù hợp (tầm 5-10 phút) -> Mua đồ ăn trưa (tầm 5-10 phút) -> Đợi có bàn trống (tầm 15-20 phút) -> ăn trưa|
| Bottleneck (bước nào, mất bao nhiêu phút) | Đợi có bàn trống (tầm 15-20 phút)|
| Impact (nếu không giải thì sao) | Học viên có thể phải nhịn bữa trưa nếu không kịp ăn và phải vào điểm danh đầu buổi|
| Success metric (baseline → target) | số lượng học viên điểm danh buổi sáng - số lượng học viên kịp điểm danh buổi chiều, số lượng học viên phải nhịn bữa trưa|
| Phương án không dùng AI | Mở rộng khu ăn uống bên trong tòa nhà nhất là vào mùa mưa|
| Giả thuyết về AI (nếu có) | Đưa AI vào hỗ trợ học viên tìm được giải pháp ăn uống phù hợp với lịch học và thời tiết, lượng người ăn trưa ở trường ngày càng lớn, điều hướng người ăn đến khu ăn uống mới tránh tắc ngẽn ở 1 nơi|
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
Học viên tìm quanh khuôn viên trường nơi ăn trưa phù hợp (tầm 5-10 phút) -> Mua đồ ăn trưa (tầm 5-10 phút) -> Đợi có bàn trống (tầm 15-20 phút) -> ăn trưa
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một ngày học, tôi muốn biết chính xác tất cả thông báo hay lịch học có liên quan đến tôi thay vì phải đọc quá nhiều kênh giao tiếp để tìm ra thông tin nào thật sự quan trọng với mình| học viên VinUni |
| Actor | Học viên VinUni|
| Thời điểm / bối cảnh |Mỗi đầu ngày hoặc khi có thông báo quan trọng có deadline cụ thể|
| Quy trình hiện tại (3–7 bước) | Học viên truy cập vào Discord, mở hết những channel đang có thông báo mới, đọc từ trên xuống hoặc từ dưới lên để tìm ra thông tin liên quan đến mình hoặc hữu ích -> ghi chú ra sổ tay -> học viên tiếp tục truy cập vào Phoenix, xem thông báo trên các kênh cho team và cho các buổi online, đọc từ trên xuống hoặc từ dưới lên để tìm ra thông tin liên quan đến mình hoặc hữu ích -> học viên tiếp tục truy cập vào Mail Office, xem những thông báo quan trọng từ nhà trường|
| Bottleneck (bước nào, mất bao nhiêu phút) | Học viên truy cập vào Discord, mở hết những channel đang có thông báo mới, đọc từ trên xuống hoặc từ dưới lên để tìm ra thông tin liên quan đến mình hoặc hữu ích, mất tầm 30 phút|
| Impact (nếu không giải thì sao) | nhiều thông tin/thông báo quan trọng bị sót, làm cho bố trí việc học không hiệu quả, gây ra hậu quả kết quả học tập không đạt yêu cầu|
| Success metric (baseline → target) | số thông báo quan trọng bị miss / tổng số học viên, kết quả học tập liên quan đến các bài có deadline|
| Phương án không dùng AI | xây dựng 1 kênh kết nối 3 nền tảng và nơi trao đổi tách biệt với thông báo và người review/coach lab có vai trò đưa những thông tin / thông báo quan trọng từ trong nhóm ra trang thông báo để pin cho học viên nắm được|
| Giả thuyết về AI (nếu có) | liên kết webhook với 3 nền tảng và xác định trong những trao đổi của nhóm kênh để biết thông tin nào liên quan đến tài liệu, deadline, nơi submit bài, thay đổi giờ giấc... là thông tin hữu ích và quan trọng cho nhiều học viên để đưa lên trang thông báo|
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
Học viên truy cập vào Discord, mở hết những channel đang có thông báo mới, đọc từ trên xuống hoặc từ dưới lên để tìm ra thông tin liên quan đến mình hoặc hữu ích -> ghi chú ra sổ tay -> học viên tiếp tục truy cập vào Phoenix, xem thông báo trên các kênh cho team và cho các buổi online, đọc từ trên xuống hoặc từ dưới lên để tìm ra thông tin liên quan đến mình hoặc hữu ích -> học viên tiếp tục truy cập vào Mail Office, xem những thông báo quan trọng từ nhà trường
```

### Card muốn pitch nhất

- Card số: #1
- Vì sao: việc an ninh luôn được đặt lên hàng đầu trong khu dân cư, outcome rõ ràng và value mang lại cao, giảm rủi ro an ninh cho cư dân Vinhomes
- Câu hỏi muốn nhóm phản biện: chi phí lắp đặt hệ thống (phần cứng và phần mềm) có quá cao so với quy trình hiện tại không? dân cư có hoàn toàn đồng ý lắp camera trước cửa nhà không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Thời gian chờ 15–20 phút mới là ước tính; chưa có bằng chứng về thời điểm, tần suất và số cư dân thực sự gặp tình trạng này. | Đồng ý | Ghi rõ đây là ước tính chưa đo; bổ sung việc cần ghi nhận thời gian chờ ở các khung giờ và hỏi cư dân, nhân viên an ninh để kiểm chứng baseline. |
| Card đang gộp bài toán xác minh cư dân lúc vào cổng với việc dùng camera theo dõi trộm cắp; đây là mở rộng phạm vi và giả định giải pháp trước khi xác nhận nhu cầu. | Đồng ý | Thu hẹp giả thuyết AI vào hỗ trợ đối chiếu thông tin tại cổng; bỏ mục tiêu theo dõi hành vi và giữ nhân viên an ninh là người quyết định cuối cùng. |
| Success metric chưa có baseline/target cụ thể, đồng thời trộn thời gian chờ với số vụ mất mát nên khó biết giải pháp có cải thiện đúng vấn đề hay không. | Đồng ý | Đổi metric chính thành trung vị thời gian từ lúc vào hàng đến lúc qua cổng, đặt mục tiêu thử nghiệm giảm ít nhất 50% sau khi đo baseline; theo dõi riêng tỷ lệ xác minh nhầm/từ chối nhầm và không để tỷ lệ này tăng. |
| Dữ liệu định danh và camera nhạy cảm; card chưa nêu giới hạn dữ liệu, quyền truy cập, sự đồng thuận hay thời hạn lưu trữ. | Đồng ý | Bổ sung các điều kiện cần làm rõ trước khi thử nghiệm: chỉ dùng dữ liệu cần thiết, xác định quyền truy cập và thời hạn lưu trữ; không theo dõi liên tục trong khu dân cư. |


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Thảo luận để đưa ra ý kiến cá nhân và tổng hợp ý của thành viên nhóm, làm tài liệu tổng hợp| Nhóm đã được cộng điểm thuyết trình và nộp bài đúng quy định|
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | tôi đã đặt ra câu hỏi liệu đưa AI vào kênh học tập có được phép từ nhà trường không? điều này có khả thi không?|
| Nhận phản biện | Câu hỏi tôi nhận được: tôi không muốn trả tiền cho ứng dụng vì tính năng chưa mang nhiều giá trị về tiền bạc, không có cũng không sao| Tôi đã sửa gì: tôi đã sửa về phần điểm impact của đề tài|
| Gom cluster / cây OST | tôi đã họp nhóm với team để gom những bài toán có chung vào 1 cluster| chúng tôi đã có bảng tổng hợp 4 cluster|
| Chọn candidate problem | tôi đã tham gia đánh giá, chấm điểm cho ác yếu tố và chọn ra candidate có điểm cao nhất| chúng tôi đã chọn được candidate để triển khai dựa trên trọng số|
| Kiểm chứng / research | đóng vai vào người dùng vì ứng dụng cho chính nhóm mình| nhận được nhiều ý kiến từ các học viên khác|
| Quy trình nhóm | mỗi thành viên đưa ra từ 5 bài toán thực tế mà mang lại giá trị / giải quyết khó khăn của người dùng -> chọn ra 3 bài toán mà việc áp dụng AI là cần thiết -> mỗi người tự phân tích cá nhân từng bài toán, quy trình hiện tại -> thuyết trình trước nhóm cho từng bài toán -> nhóm đưa ra phản biện và chọn ra 3 / 9 bài toán để đánh trọng số -> nhóm chấm điểm cho từng bài toán dựa trên nhiều yếu tố như impact, khả năng lab.. -> nhóm chọn ra 1 bài toán để thuyết trình -> ghi nhận phản biện và cập nhật tài liệu -> nộp bài| |
| Problem Statement | tham gia viết và tổng hợp| hoàn thiện bài report của team|
| Mức can thiệp AI | tham gia viết và tổng hợp| hoàn thiện bài report của team|
| Quyết định | tham gia viết và tổng hợp| hoàn thiện bài report của team |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Tôi nhận thấy việc chọn problems nên gần với hàng ngày hơn những bài toán khó kiểm chứng

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Cũng có đôi khi vấn đề gặp phải của chính mình nên hay bị đi theo hướng tìm giải pháp thay vì hiểu vấn đề cốt lõi và có nhất thiết phải đưa AI vào không

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Ban đầu tôi muốn chọn bài toán xác minh danh tính vì tính hữu ích của nó sau khi nhận được phản biện về các chi phí để xây dựng nên tôi đã đồng ý chọn bài toán tổng hợp thông báo trong môi trường học tập hơn

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
các bạn học viên cùng gặp vấn đề như chúng tôi nhưng họ không muốn trả tiền cho một ứng dụng hỗ trợ việc học, tôi khá bất ngờ về việc này

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
do chưa có kinh nghiệm thực tế nhiều nên dễ bị viết theo hướng suy luận

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
tôi sẽ khảo sát các bạn học viên trước thay vì chỉ lấy ý kiến của bản thân và nhóm, dù nhìn thấy pain của nhóm mình cùng 1 vấn đề nhưng với lượng người khảo sát lớn hơn sẽ cho kết quả khác

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Học viên tham gia khóa học AI thực chiến nhận các loại tin nhắn và thông báo hàng ngày qua nhiều nền tảng. Khi số lượng học viên và bài giảng thêm mỗi ngày, học viên rất khó để nắm bắt được các thông tin quan trọng / thông báo để đảm bảo việc học và kết quả học tập.
Mỗi ngày học viên cần mở nhiều ứng dụng để ghi chú những việc mình cần làm.
Để số lượng tin nhắn/thông báo quan trọng không bị bỏ qua, một trợ lý ảo kết nối và tổng hợp thông tin đưa thông báo/thông tin quan trọng lên 1 kênh duy nhất là lựa chọn của nhóm

---

## 7. Tài liệu tham khảo

-
