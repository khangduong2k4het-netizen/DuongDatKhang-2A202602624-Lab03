# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Dương Đạt Khang
- Mã học viên:2A202602624
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): sinh viên năm cuối
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Tốn thời gian |số hồ sơ xử lý bệnh án còn tồn đọng| Bác sĩ| Thiếu phiếu sơ kết 15 ngày điểu trị  |
| 2 |Tốn thời gian |Các luận án, tiểu luận sinh viên dài mà các giáo sư phải chấm trong thời gian ngắn| Giáo sư, tiến sĩ | Quy định của trường HUS phải chấm trong 3 ngày mà rất nhiều bài dài hơn 40 trang, các giảng viên thường trễ hạn |
| 3 |Tốn thời gian |Phải tốn thời gian, thức trắng đêm để săn tìm giá máy bay hoặc các ưu đãi dịch vụ giá rẻ nhưng chất lượng| Người dùng |rất nhiều người dùng thức đến 2h sáng để săn vẽ máy bay ( 140 - 180 người/ chuyến) |
| 4 |AI có thể tốt hơn |Quản lý quỹ thời gian tệ khiến ảnh hưởng đến sức khỏe| Người dùng |Bản thân em cảm thấy sức khỏe mình đi xuống trong công việc và nhận ra quá nhiều thời gian lãng phí trong ngày |
| 5 |Pain của người khác |Các cuộc họp kéo dài mà không thể tóm tắt được  | | |
| 6 |Lặp lại|Trả lời khách hàng của ngân hàng về lãi xuất, tín dụng mà rule có thể thay đổi hàng ngày | | |
| 7 |Pain của người khác |Giao tiếp với các phòng ban về vấn để còn tồn đọng của khách | Nhân viên, PM |Trong công ty, phòng ban đã giao tiếp với khách hàng nhưng không có thời gian giao tiếp với phòng ban khách khi được hỏi |
| 8 |Pain của người khác |Các nhân viên mới có nhiều vấn đề trong nội bộ công ty mà chỉ có tài liệu của công ty hoặc mentor có thể giải thích | PM, Mentor |rất nhiều công ty có framework nội bộ(em không được tiết lộ) và chỉ có các mentor lâu năm mới giải quyết được |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Quản lý quỹ thời gian tệ khiến ảnh hưởng đến sức khỏe|Rất thiết thực với giới trẻ, có thể tích hợp với các mặt hàng( đồng hộ, điện thoại) |Về sức khỏe sẽ liên quan đến nhịp tim, mức độ stress, cần số liệu người dùng để train và cần dữ liệu streaming để cập nhập sau khi đặt lịch |
| 2 |Các nhân viên mới có nhiều vấn đề trong nội bộ công ty mà chỉ có tài liệu của công ty hoặc mentor có thể giải thích |Vì có sẵn tài liệu, người để thực hiện human in loop |khả năng xây dựng một local AI với chi phí train |
| 3 |Phải tốn thời gian, thức trắng đêm để săn tìm giá máy bay hoặc các ưu đãi dịch vụ giá rẻ nhưng chất lượng |có sẵn API để cào data, người dùng có thể cung cấp địa chỉ, mong muốn |số lượng data cào được có thể nhiều các ưu đãi sẽ cập nhập liên tục |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

> Các thời gian trước/sau là ước lượng minh họa và mục tiêu thử nghiệm, chưa phải số liệu thực tế; cần đo baseline để kiểm chứng.

---

#### Problem Card #1 — Khó điều chỉnh lịch cá nhân theo tình trạng sức khỏe

```text
Problem 1 câu: Sinh viên hoặc người đi làm trẻ có lịch công việc và dữ liệu theo dõi sức khỏe nhưng chưa kết hợp được các thông tin này để điều chỉnh việc làm và nghỉ ngơi, dẫn đến quá giờ hoặc thức khuya bù tiến độ.

Actor: Sinh viên hoặc người đi làm trẻ tự quản lý lịch cá nhân, sử dụng đồng hồ thông minh hoặc điện thoại để theo dõi sức khỏe.

Thời điểm / bối cảnh: Đầu ngày và trong quá trình học/làm việc, khi lịch công việc thay đổi hoặc người dùng cập nhật tình trạng sức khỏe.

Current workflow 3-7 bước:
1. Ghi nhớ hoặc ghi rời rạc các việc cần làm.
2. Kiểm tra deadline và lịch cố định trên điện thoại.
3. Sử dụng các công cụ đo đạc sức khỏe (đồng hồ thông minh, điện thoại) để theo dõi dữ liệu theo thời gian thực trong phạm vi thiết bị hỗ trợ.
4. Cung cấp thông tin về bệnh nền, tình trạng tâm lý và sức khỏe hiện tại.
5. Bắt đầu làm nhưng bị gián đoạn hoặc quá giờ.
6. Bỏ sót việc hoặc thức khuya để bù tiến độ.

Bottleneck: Bước 5 — Khi bắt đầu và tiếp tục công việc, người dùng chưa có cách kết hợp lịch, dữ liệu thiết bị và tình trạng tự khai để điều chỉnh thời lượng làm/nghỉ kịp thời. Đây là giả thuyết cần kiểm chứng qua quan sát workflow thực tế.

Impact: Tốn thời gian tự đối chiếu thông tin, công việc kéo dài, bỏ sót deadline và lấn vào giờ nghỉ. Đo bằng thời gian chỉnh lịch, tỷ lệ việc hoàn thành đúng hạn và số đêm thức khuya để bù việc.

Success metric: Sau hai tuần thử nghiệm, mục tiêu giảm ít nhất 30% thời gian lập/chỉnh lịch so với tuần đo baseline; theo dõi tỷ lệ hoàn thành đúng hạn và số đêm thức khuya để bù việc. Ghi nhận thêm tỷ lệ gợi ý điều chỉnh lịch được người dùng chấp nhận.

Non-AI alternative: Kết hợp lịch điện tử, checklist, nhắc nghỉ theo giờ cố định và ứng dụng sức khỏe của thiết bị; người dùng tự điều chỉnh lịch theo tình trạng của mình.

AI hypothesis: Nếu được người dùng cho phép, hệ thống tổng hợp danh sách việc, deadline, dữ liệu thiết bị còn mới và tình trạng sức khỏe/tâm lý tự khai để AI gợi ý đổi thứ tự việc hoặc thời điểm nghỉ theo các ràng buộc người dùng đã xác nhận. Khi có dữ liệu mới, hệ thống có thể đề xuất điều chỉnh tiếp; người dùng duyệt trước khi thay đổi lịch. Cần kiểm chứng khả năng truy cập dữ liệu, độ trễ và giá trị bổ sung so với nhắc nghỉ theo rule; thông tin bệnh nền không được dùng để tự suy ra chẩn đoán hoặc chỉ định điều trị.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — Chưa đo; cần ghi nhận phút thao tác/ngày

[1 Ghi việc] → [2 Kiểm tra deadline và lịch]
→ [3 Theo dõi dữ liệu sức khỏe từ thiết bị]
→ [4 Cung cấp bệnh nền, tình trạng tâm lý và sức khỏe]
→ [5 Làm việc nhưng chưa điều chỉnh lịch kịp, bị gián đoạn/quá giờ] <-- bottleneck
→ [6 Bỏ sót việc hoặc thức khuya bù tiến độ]

FUTURE STATE — Mục tiêu giảm ít nhất 30% phút lập/chỉnh lịch so với baseline
Không cộng thời gian đo tự động của thiết bị vào thời gian thao tác của người dùng.

[1 Nhập việc, deadline và giờ nghỉ mong muốn]
→ [2 Cho phép kết nối thiết bị, cung cấp thông tin sức khỏe cần thiết]
→ [3 Hệ thống kiểm tra dữ liệu mới/cũ; AI đề xuất lịch theo ràng buộc đã xác nhận]
→ [4 Người dùng review, sửa và chốt lịch] <-- human boundary
→ [5 Làm việc; hệ thống tiếp nhận tiến độ và dữ liệu thiết bị cập nhật]
→ [6 AI gợi ý điều chỉnh; người dùng duyệt trước khi áp dụng] <-- human boundary

Fallback: Nếu mất kết nối, dữ liệu cũ hoặc thiếu thông tin sức khỏe,
hiển thị rõ tình trạng dữ liệu và dùng lịch, tiến độ cùng thông tin người dùng
xác nhận để gợi ý; không tự đoán tình trạng sức khỏe.
Nếu gợi ý không phù hợp, giữ lịch hiện tại và cho phép chỉnh thủ công.
```

File đính kèm (nếu vẽ riêng): Không có; workflow đã trình bày trực tiếp ở trên.

---

#### Problem Card #2 — Nhân viên mới khó tìm hướng dẫn nội bộ

```text
Problem 1 câu: Nhân viên mới mất thời gian tìm hướng dẫn về framework nội bộ và phải chờ mentor giải thích trước khi tiếp tục công việc.

Actor: Nhân viên kỹ thuật mới trong ba tháng đầu tại công ty sử dụng framework nội bộ; mentor là người hỗ trợ.

Thời điểm / bối cảnh: Khi nhận nhiệm vụ đầu tiên hoặc gặp lỗi chưa biết cách xử lý bằng công cụ nội bộ.

Current workflow 3-7 bước:

1. Nhận nhiệm vụ và xác định vấn đề cần giải đáp.
2. Tìm hướng dẫn liên quan trong tài liệu nội bộ.
3. Đọc hướng dẫn và thử áp dụng.
4. Gửi câu hỏi cho mentor nếu chưa giải quyết được.
5. Chờ phản hồi, thực hiện và xác nhận kết quả.

Bottleneck: Bước 2 — Nhân viên mới chưa biết tìm ở đâu và tài liệu nào áp dụng cho phiên bản framework đang dùng.

Impact: Công việc bị chậm; mentor phải giải thích lại các vấn đề tương tự. Đo bằng thời gian tìm hướng dẫn và số lượt mentor phải hỗ trợ câu hỏi lặp lại mỗi tuần.

Success metric: Mục tiêu giảm 50% thời gian tìm được hướng dẫn đúng; giảm 30% câu hỏi lặp lại gửi mentor; ít nhất 90% câu trả lời trong bộ câu hỏi thử nghiệm được mentor đánh giá đúng và đủ. Mọi câu trả lời hướng dẫn phải có nguồn tham chiếu.

Non-AI alternative: Chuẩn hóa wiki theo chủ đề và phiên bản, bổ sung FAQ, cải thiện tìm kiếm và tổ chức giờ hỗ trợ nhân viên mới.

AI hypothesis: AI có thể tìm nội dung trong tài liệu được cấp quyền rồi trả lời kèm nguồn. Giả thuyết cần kiểm chứng là cách này giúp nhân viên tìm đúng hướng dẫn nhanh hơn tìm kiếm thông thường. Việc chạy mô hình local và chi phí triển khai cần đánh giá riêng.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 30 phút/câu hỏi (ước lượng cần kiểm chứng)
Phạm vi đo: từ khi xác định câu hỏi đến khi có hướng dẫn có thể áp dụng;
không tính thời gian thực hiện nhiệm vụ sau đó.

[1 Mô tả vấn đề: 3'] → [2 Tìm đúng tài liệu và phiên bản: 15'] <-- bottleneck
→ [3 Đọc, đối chiếu hướng dẫn: 7'] → [4 Hỏi và chờ mentor xác nhận: 5']

FUTURE STATE — 15 phút/câu hỏi (mục tiêu thử nghiệm)

[1 Nhập câu hỏi và phiên bản framework: 3']
→ [2 Hệ thống tìm tài liệu được cấp quyền, AI trả lời kèm nguồn: 2']
→ [3 Nhân viên review nguồn; mentor xác nhận trường hợp khó: 10'] <-- human boundary

Fallback: Nếu không có nguồn phù hợp, nguồn mâu thuẫn hoặc hướng dẫn không
áp dụng được, nêu rõ phần chưa xác định và chuyển câu hỏi cho mentor.
Thời gian chờ mentor thực tế phải được tính vào kết quả đo, kể cả khi vượt mục tiêu.
```

File đính kèm (nếu vẽ riêng): Không có; workflow đã trình bày trực tiếp ở trên.

---

#### Problem Card #3 — Người tự đặt vé phải kiểm tra giá nhiều lần

```text
Problem 1 câu: Người tự đặt vé máy bay cho chuyến đi cá nhân phải kiểm tra giá nhiều lần để tìm vé trong ngân sách và đúng điều kiện, đôi khi thức khuya để chờ ưu đãi.

Actor: Sinh viên hoặc người đi làm tự đặt vé, có ngân sách giới hạn và khoảng ngày bay xác định.

Thời điểm / bối cảnh: Từ lúc lên kế hoạch chuyến đi đến trước khi mua vé, khi chưa tìm được phương án đáp ứng yêu cầu.

Current workflow 3-7 bước:

1. Xác định chặng bay, khoảng ngày, ngân sách và hành lý.
2. Tìm chuyến bay trên các nguồn bán vé.
3. So sánh tổng giá và điều kiện của các lựa chọn.
4. Quay lại kiểm tra nhiều lần để chờ giá phù hợp.
5. Xác nhận giá cuối cùng và thanh toán.

Bottleneck: Bước 4 — Phải chủ động kiểm tra lại vì chưa biết khi nào xuất hiện vé đáp ứng đủ tiêu chí.

Impact: Tốn thời gian theo dõi, gián đoạn sinh hoạt và có thể bỏ lỡ vé phù hợp. Đo bằng tổng phút theo dõi và số lần kiểm tra thủ công cho mỗi chuyến đi.

Success metric: Mục tiêu giảm 50% số lần kiểm tra thủ công và thời gian theo dõi mỗi chuyến; ít nhất 90% cảnh báo đáp ứng đúng tiêu chí đã nhập tại thời điểm kiểm tra dữ liệu.

Non-AI alternative: Bộ lọc chuyến bay và cảnh báo theo ngưỡng giá, kèm thời gian nhận thông báo do người dùng chọn.

AI hypothesis: AI có thể chuyển yêu cầu tự nhiên thành tiêu chí tìm kiếm và giải thích các đánh đổi giữa giá, giờ bay, hành lý và quá cảnh. Việc kiểm tra định kỳ và gửi cảnh báo có thể dùng rule. Cần xác minh nguồn dữ liệu, quyền truy cập, chi phí và độ trễ cập nhật trước khi triển khai.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 60-120 phút/lần tìm

[1 nhập tiêu chí: 5'] → [2 mở nhiều nguồn: 20-40'] → [3 so sánh tổng chi phí và điều kiện: 20-40'] → [4 kiểm tra lại giá: 15-35']  <-- bottleneck

FUTURE STATE — 10-15 phút/lần tìm

[1 nhập yêu cầu: 2'] → [2 hệ thống lấy và chuẩn hóa kết quả: 5-8'] → [3 người dùng review điều kiện và đặt vé: 3-5']  <-- human boundary

Fallback: Nếu API lỗi, dữ liệu cũ hoặc ưu đãi hết hạn, hệ thống hiển thị thời điểm cập nhật và đánh dấu không chắc chắn. Người dùng phải xác nhận trực tiếp trên website của hãng trước khi thanh toán; hệ thống không tự đặt vé.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Quản lý lịch cá nhân và sức khỏe.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi chọn Card #1 vì đây là vấn đề ưu tiên hàng đầu trong bảng scan, xuất phát từ việc bản thân nhận thấy thời gian trong ngày bị lãng phí và sức khỏe đi xuống.
Workflow cần cải thiện là ghi việc, kiểm tra lịch, ước lượng thời lượng và xếp ưu tiên; điểm nghẽn nằm ở bước ước lượng và xếp lịch khi có việc phát sinh.
Tôi dự kiến đo thời gian lập/chỉnh lịch mỗi ngày, tỷ lệ việc hoàn thành đúng hạn và số đêm thức khuya để bù việc; mục tiêu ban đầu là giảm ít nhất 30% thời gian lập/chỉnh lịch so với tuần đo baseline.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm sao xác định nguyên nhân chính là xếp lịch chưa phù hợp, thay vì quá nhiều việc hoặc thói quen trì hoãn?
2. AI giúp cải thiện bước nào hơn lịch điện tử và checklist, và có thể kiểm chứng giá trị đó chỉ bằng lịch cùng nhật ký công việc trước khi tích hợp đồng hồ thông minh không?
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: Actor người trẻ còn rộng; ảnh hưởng sức khỏe mới là quan sát cá nhân, chưa có số đo; chưa chứng minh cần dữ liệu nhịp tim/stress hoặc train mô hình; cần so sánh với lịch và checklist trước khi chọn AI.
- Tôi sửa gì: Với sự hỗ trợ của AI, xác định phạm vi thử nghiệm ban đầu là sinh viên năm cuối; đo thời gian lập/chỉnh lịch và tiến độ bằng nhật ký; dùng mục tiêu giảm 30% so với baseline; để người dùng duyệt lịch và sửa thủ công khi gợi ý không phù hợp.

> Phần chuẩn bị pitch và challenge do AI hỗ trợ soạn từ ý tưởng đã chọn; người học cần tự rà soát và trình bày bằng hiểu biết của bản thân.

### Self-check nộp phần 01

- [ ] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

> Chưa đánh dấu mục đầu vì một số dòng trong Phase 1 còn thiếu actor hoặc số đo/bằng chứng.
