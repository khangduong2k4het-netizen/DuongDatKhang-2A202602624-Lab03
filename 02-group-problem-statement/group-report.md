# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Tạ Việt Cường | 2A202602560 | Nhóm trưởng / Phân tích Workflow tài chính & Metric |
| 2   | Dương Đạt Khang | 2A202602624 | Chịu trách nhiệm Research giải pháp & Kiến trúc công nghệ |
| 3   | Phạm Quân | 2A202602890| Phân tích Data, Đánh giá rủi ro & Boundary |
| 4   | Nguyễn Đỗ Chiến Thắng | 2A202602442 | Khảo sát thực tế (Validation), Thư ký tổng hợp tài liệu |

**Candidate problem nhóm chọn (1 câu):**
Người vay tiêu dùng cá nhân bị quá tải nhận thức trước hợp đồng tín dụng dài 15–25 trang, không tính được lãi suất thực tế (APR) và không nhận biết được các bẫy phí phạt ẩn, dẫn đến chịu chi phí vay thực tế vọt lên 35%–50%/năm và mất oan tiền phí mà không hề hay biết trước khi ký.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Tạ Việt Cường | Đọc hiểu điều khoản ẩn & tính lãi suất thực (APR) hợp đồng tín dụng tiêu dùng | Người vay tiêu dùng cá nhân (mua xe, điện thoại, vay tiền mặt) | Không có thời gian và công cụ bóc tách phí ẩn, bẫy lãi suất phẳng vs APR | Pain point xã hội lớn, có bằng chứng chính thức từ VCC, workflow rõ ràng, metric định lượng rất sắc. |
| 2 | Tạ Việt Cường | Đối soát sao kê đa tài khoản ngân hàng và quản lý dòng tiền tức thời cho SME | Chủ doanh nghiệp SME & Kế toán nội bộ | Đọc hiểu và phân loại thủ công các dòng giao dịch ngân hàng viết tắt, mập mờ | Nỗi đau sống còn về dòng tiền của SME, tuy nhiên phạm vi hẹp trong nội bộ kế toán doanh nghiệp. |
| 3 | Tạ Việt Cường | Tra cứu chính sách tín dụng nội bộ phức tạp & lập checklist hồ sơ vay cho RM | Chuyên viên tín dụng ngân hàng (RM) & Thẩm định | Tra cứu chéo hàng chục file PDF công văn chính sách phân tán, dễ sót điều kiện | Bài toán RAG kinh điển trong enterprise, nhưng khó tiếp cận kho dữ liệu chính sách bảo mật nội bộ ngân hàng. |
| 4 | Dương Đạt Khang | Quản lý quỹ thời gian tệ gây ảnh hưởng tiêu cực đến sức khỏe | Người đi làm, sinh viên | Chưa có cách kết hợp tự động giữa lịch làm việc, thiết bị đo và trạng thái tự khai | Nhu cầu có thật nhưng giải pháp phụ thuộc nặng vào phần cứng/API thiết bị đeo thông minh, khó tự chủ dữ liệu. |
| 5 | Dương Đạt Khang | Nhân viên mới gặp khó khăn khi tra cứu tài liệu onboarding nội bộ | Nhân viên mới (onboarding) & Mentor | Không biết tìm tài liệu ở đâu và tài liệu nào áp dụng cho phiên bản framework đang dùng | Công ty nhỏ chưa có tài liệu quy chuẩn; công ty lớn thường đã có wiki/Notion nội bộ tự giải quyết. |
| 6 | Dương Đạt Khang | Tốn thời gian, thức trắng đêm săn tìm vé máy bay hoặc ưu đãi giá rẻ | Người tiêu dùng du lịch | Phải chủ động canh giờ, refresh liên tục vì không biết khi nào vé rẻ xuất hiện | Đã có nhiều nền tảng OTA và aggregator giải quyết (Traveloka, Google Flights); phụ thuộc API hãng bay. |
| 7 | Phạm Quân | Tìm và kiểm tra đầy đủ yêu cầu nộp bài từ nhiều nguồn (LMS, Teams, Discord) | Sinh viên, học viên | Thông tin deadline và tiêu chí nộp bài rải rác nhiều kênh, dễ bỏ sót mục quan trọng | Workflow và bottleneck rất rõ, đo được theo thời gian và số mục sót; tuy nhiên impact giới hạn trong phạm vi học tập. |
| 8 | Phạm Quân | Chẩn đoán nguyên nhân lỗi từ file log build/test dài hàng nghìn dòng | Lập trình viên phần mềm | Đọc log lỗi dài, khó định vị đúng dòng lỗi cốt lõi và ngữ cảnh phát sinh | Pain cụ thể nhưng các công cụ lập trình (IDE Copilot, Sentry) đã giải quyết tương đối tốt phần này. |
| 9 | Phạm Quân | Tổng hợp và cập nhật phân công công việc nhóm sau các buổi họp trao đổi chat | Thành viên nhóm dự án | Trôi tin nhắn trong group chat, không có người chủ động note lại action items | Handoff rõ ràng, nhưng các ứng dụng như Slack AI, Notion AI, Zoom Summary đã tích hợp sẵn tính năng này. |
| 10 | Nguyễn Đỗ Chiến Thắng | Công dân không biết đúng giấy tờ cần chuẩn bị trước khi đến làm thủ tục CCCD | Công dân & Cán bộ tiếp nhận một cửa | Bước tự tìm thông tin rải rác trên mạng, không nhất quán giữa các địa phương | Rất thiết thực, impact lớn cho xã hội, đo được bằng tỷ lệ hồ sơ bị trả về; tuy nhiên khó can thiệp quy trình nhà nước. |
| 11 | Nguyễn Đỗ Chiến Thắng | Cán bộ phải nhập tay thủ công thông tin công dân từ hồ sơ giấy vào hệ thống | Cán bộ một cửa & Công dân chờ đợi | Bước gõ tay từng trường thông tin từ nhiều tờ giấy mờ/chữ xấu, mất 10-15 phút/hồ sơ | Workflow 1 chiều rõ, AI OCR khả thi, tiết kiệm thời gian lớn; rủi ro là khó tích hợp vào mạng nội bộ ngành công an. |
| 12 | Nguyễn Đỗ Chiến Thắng | Không biết thiết bị điện/nước nào tiêu thụ nhiều nhất, chỉ nhận hóa đơn tổng | Hộ gia đình muốn tiết kiệm điện | Không có dữ liệu đo đạc chi tiết từng thiết bị, phải đoán mò và chờ hóa đơn cuối tháng | Vấn đề nhiều người gặp nhưng phụ thuộc bắt buộc vào phần cứng IoT (Smart Plug) để đo, dễ trượt khỏi phạm vi phần mềm AI. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Pháp lý, Thủ tục & Quyền lợi người tiêu dùng | #1 (Hợp đồng vay tiêu dùng), #10 (Thủ tục giấy tờ CCCD) | Người dân bình thường bị bất cân xứng thông tin, khó đọc hiểu văn bản hành chính/pháp lý phức tạp, thiếu công cụ hỗ trợ trước khi ký kết/nộp hồ sơ. | Impact xã hội cực lớn, dữ liệu văn bản công khai, phù hợp mạnh với khả năng đọc hiểu & trích xuất của AI. |
| B. Năng suất nội bộ Doanh nghiệp & Chuyên môn | #2 (Sao kê dòng tiền SME), #3 (Tra cứu chính sách RM), #5 (Onboarding tài liệu), #11 (Nhập liệu hồ sơ giấy) | Nhân viên mất nhiều giờ tra cứu, nhập liệu hoặc phân loại thủ công từ kho dữ liệu phân tán. | Giá trị kinh tế rõ nhưng rào cản truy cập hệ thống nội bộ/bảo mật thông tin của doanh nghiệp và nhà nước cao. |
| C. Năng suất cá nhân & Học tập / Lập trình | #7 (Checklist deadline bài nộp), #8 (Chẩn đoán log lỗi build), #9 (Tổng hợp việc nhóm) | Quá tải thông tin từ các kênh trao đổi (Discord, Chat, Terminal) cần tổng hợp thành hành động cụ thể. | Dễ thử nghiệm ngay trong lab nhưng impact hẹp, đã có nhiều tool có sẵn của các Big Tech giải quyết một phần. |
| D. Tối ưu chi phí sinh hoạt & Đời sống | #4 (Quản lý thời gian & sức khỏe), #6 (Săn vé máy bay giá rẻ), #12 (Theo dõi điện nước gia đình) | Tối ưu hóa chi tiêu và sinh hoạt cá nhân dựa trên dữ liệu biến động. | Phụ thuộc nặng vào bên thứ 3 (hãng bay, thiết bị phần cứng IoT/wearable), khó kiểm soát luồng dữ liệu trong phạm vi bài lab. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **1. Đọc hiểu điều khoản ẩn & tính lãi suất thực (APR) hợp đồng tín dụng tiêu dùng** (Tạ Việt Cường) | • Actor cực kỳ rõ ràng (người vay mua trả góp cá nhân).<br>• Có số liệu chứng minh nỗi đau thực tế từ cơ quan quản lý (Báo cáo VCC 2025).<br>• Metric đo lường định lượng chính xác (thời gian đọc, tỷ lệ tính đúng APR, tiền phạt tránh mất oan).<br>• Workflow tuyến tính, phân định rõ ràng giữa AI và con người. | Khả năng xử lý OCR đối với ảnh chụp hợp đồng bị mờ/nghiêng tại quầy giao dịch và việc tiếp cận các mẫu hợp đồng tín dụng đa dạng trên thị trường. |
| **2. Chuẩn bị giấy tờ thủ tục đổi CCCD tránh bị trả về** (Nguyễn Đỗ Chiến Thắng) | • Nỗi đau rất thực tế của đông đảo người dân khi đi làm thủ tục hành chính.<br>• Nút thắt rõ ràng (bước chuẩn bị giấy tờ bị sai lệch/thiếu).<br>• Tiết kiệm thời gian đi lại cho người dân và giảm tải cho cán bộ một cửa. | Quy định thủ tục hành chính thay đổi thường xuyên theo từng đợt của Bộ Công an; rủi ro pháp lý nếu AI hướng dẫn sai lệch dẫn đến công dân bị trễ hạn. |
| **3. Đối soát sao kê đa tài khoản & quản lý dòng tiền tức thời cho SME** (Tạ Việt Cường) | • Nỗi đau sống còn về dòng tiền của doanh nghiệp SME.<br>• Tần suất lặp lại cao (3–4 lần/tuần), kế toán mất 2–3 tiếng lọc tay.<br>• Giải quyết đúng điểm nghẽn nhận diện ngữ cảnh nội dung chuyển khoản mập mờ. | Tại Việt Nam chưa có Open Banking mở rộng nên phải tải file sao kê Excel thủ công; dữ liệu tài chính nhạy cảm khó xin mẫu thật để kiểm chứng trong lab. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Hợp đồng tín dụng tiêu dùng (AI Financial Translator)** | 5 | 5 | 5 | 5 | 5 | 5 | 4.5 | **34.5** |
| **Thủ tục giấy tờ CCCD** | 5 | 4 | 4 | 4 | 4 | 4 | 3.5 | **28.5** |
| **Sao kê dòng tiền SME** | 4.5 | 4.5 | 4 | 4.5 | 3.5 | 4 | 4 | **29.0** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
AI Financial Translator — Đọc hiểu điều khoản ẩn, bẫy phí phạt & tính lãi suất thực (APR) hợp đồng tín dụng tiêu dùng.
```

**Vì sao chọn (4-5 câu):**

```text
Bài toán này đạt điểm đồng thuận cao nhất (34.5/35) vì giải quyết một vấn đề xã hội có thật, nhức nhối với bằng chứng đanh thép từ Báo cáo năm 2025 của Ủy ban Cạnh tranh Quốc gia (chiếm 6,7% tổng số phản ánh tiếp nhận). Actor là người vay cá nhân rất cụ thể, trải nghiệm quy trình ký hợp đồng dưới áp lực thời gian tại điểm bán (POS) nên nhu cầu có công cụ đối soát độc lập trong 60 giây là cực kỳ cấp thiết. Workflow của bài toán đi thẳng một đường (Upload -> Understand -> Calculate -> Detect -> Ask), có ranh giới con người kiểm soát rõ ràng (Human Boundary) và phương án dự phòng (Fallback) chặt chẽ. Đặc biệt, tác động đo lường hoàn toàn định lượng: rút ngắn thời gian đọc hiểu từ 50 phút xuống dưới 2 phút, đảm bảo tính đúng lãi suất thực APR và giúp người vay tránh mất oan 1-3 triệu đồng tiền phí/phạt ẩn.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Bài toán thủ tục CCCD: Mặc dù chạm đến số đông nhưng thông tin quy định hành chính phụ thuộc chặt chẽ vào cơ chế cập nhật của cơ quan công an, nếu AI đưa thông tin sai sẽ gây rủi ro pháp lý lớn và rất khó triển khai thực tế nếu không có sự cấp phép chính thức từ cơ quan nhà nước.
- Bài toán sao kê dòng tiền SME: Nỗi đau rất thật nhưng dữ liệu sao kê ngân hàng doanh nghiệp có tính bảo mật cao, các thành viên trong nhóm khó tiếp cận đầy đủ dữ liệu thực tế để kiểm chứng sâu trong phạm vi buổi lab.
- Các bài toán quản lý thời gian/vé máy bay/tiêu thụ điện: Bị phụ thuộc nặng nề vào phần cứng đo đạc (IoT, Smart Watch) hoặc API bên thứ 3 (hãng bay), dễ làm nhóm sa đà vào việc xây dựng hạ tầng kỹ thuật thay vì tập trung vào giải thuật phân tích và giải quyết nút thắt nhận thức bằng AI.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Trong phiên thảo luận, bạn Khang và bạn Thắng lo ngại rằng: "Liệu khi đưa vào tài chính tiêu dùng, AI có bị vi phạm trách nhiệm pháp lý nếu tính sai tiền hoặc bị coi là hành nghề tư vấn tài chính trái phép không?".
Nhóm đã chốt giải pháp tháo gỡ: Thiết lập Boundary tuyệt đối chặt chẽ ngay từ thiết kế sản phẩm — AI chỉ đóng vai trò 'Công cụ hỗ trợ nhận thức' (Cognitive Support), dùng Deterministic Code để tính toán công thức dòng tiền chính xác 100%, bắt buộc trích dẫn số trang/điều khoản gốc (Citation 100%), và tuyên bố miễn trừ: AI không đưa ra quyết định 'Nên vay hay Không' và không thay thế tư vấn pháp lý của luật sư.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview trực tiếp | 3 người từng vay trả góp mua xe/điện thoại | • Anh T. (26 tuổi, HN): *"Lúc mua xe máy nhân viên bấm máy tính bảo mỗi tháng trả 1,8 triệu, nghe êm tai nên ký luôn. Về sau có tiền muốn tất toán sớm mới biết bị phạt 4% dư nợ gốc gần 1 triệu mà hợp đồng không ai nói rõ."*<br>• Chị H. (23 tuổi): *"Bị trừ thẳng 1,5 triệu tiền bảo hiểm khoản vay vào tiền giải ngân, nhân viên bảo đây là phí bắt buộc của hệ thống."* | 1 người vay qua ứng dụng ngân hàng lớn cho biết ứng dụng đã hiển thị khá rõ lịch trả nợ từng tháng nên không thấy quá bỡ ngỡ. | Nhóm thu hẹp đối tượng trọng tâm: Tập trung mạnh vào phân khúc **Consumer Installment Loans tại các điểm bán (POS)** và các công ty tài chính tiêu dùng, nơi áp lực chốt hợp đồng tại quầy diễn ra nhanh nhất. |
| Mini survey trong lớp | 8 học viên | 6/8 người (75%) thừa nhận chưa từng đọc hết quá 3 trang hợp đồng vay/mở thẻ tín dụng; 7/8 người không tự tính được lãi suất thực tế APR khác gì so với lãi suất phẳng quảng cáo. | 2 bạn cho rằng nếu cần kiểm tra thì dùng ChatGPT tóm tắt chụp ảnh cũng tạm đủ. | Bổ sung luận điểm phản biện: Generic AI (ChatGPT) tính toán số học dòng tiền hay bị sai và không có công cụ tính APR chuẩn mực theo dòng tiền thực tế. |
| Dữ liệu chính thức từ cơ quan nhà nước | Báo cáo năm 2025 của Ủy ban Cạnh tranh Quốc gia (VCC) | Ghi nhận 14.864 cuộc gọi hotline; 896 đơn khiếu nại chính thức trong đó **60 phản ánh thuộc lĩnh vực tín dụng tiêu dùng (chiếm 6,7%)**, tập trung vào lãi suất mập mờ, phí dịch vụ không rõ ràng và thu hồi nợ. | Không có phản bác; số liệu chứng minh đây là vấn đề nổi cộm được cơ quan nhà nước tiếp nhận xử lý hằng ngày. | Giữ nguyên tỷ lệ chuẩn 6,7% từ báo cáo chính thức của VCC, không dùng các con số ước tính cảm tính chưa kiểm chứng. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Nỗi đau thật không phải là người vay thiếu thông tin (hợp đồng có đủ 20 trang), mà là sự bất cân xứng thông tin cực lớn diễn ra dưới áp lực thời gian tại quầy: người vay không có công cụ độc lập để dịch các điều khoản pháp lý phức tạp thành số tiền thực trả và các bẫy phí phạt ẩn trước khi đặt bút ký.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-research-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Công cụ tính lãi vay trực tuyến (TopCV, Timo, Ngân hàng) | https://timo.vn/cong-cu-tinh-lai-vay/ | Tính lịch trả nợ theo dư nợ giảm dần hoặc dư nợ gốc ban đầu. | Tính toán toán học nhanh, giao diện đơn giản, miễn phí. | Bắt buộc người dùng phải tự đọc hợp đồng để gõ các con số vào; hoàn toàn không đọc được văn bản hợp đồng phi cấu trúc và bỏ qua các loại phí ẩn. | Phần tính toán toán học cần dùng Deterministic Engine (Code), không phụ thuộc vào LLM để tính nhẩm. |
| Generic Legal AI / Contract Review (Robin AI, Casetext) | https://www.robinai.com/ | Tóm tắt và rà soát điều khoản rủi ro trong hợp đồng pháp lý doanh nghiệp. | Xử lý ngôn ngữ tự nhiên tốt, highlight các điều khoản sai lệch chuẩn mực. | Thiết kế cho luật sư B2B, không tính toán dòng tiền tài chính cá nhân, chi phí rất đắt và không hiểu đặc thù tín dụng tiêu dùng tại Việt Nam. | Moat của nhóm không phải là 'AI đọc hợp đồng' chung chung, mà là 'Financial Translator' chuyên biệt hóa cho tín dụng tiêu dùng Việt Nam. |
| Cổng thông tin & Khuyến cáo của Ủy ban Cạnh tranh Quốc gia | https://vcc.gov.vn/ | Đăng tải các khuyến cáo, hướng dẫn người tiêu dùng nhận biết bẫy tín dụng và tiếp nhận đơn khiếu nại. | Căn cứ pháp lý chính thống, uy tín cao, bảo vệ quyền lợi người dân. | Chỉ xử lý hậu kiểm (khi người tiêu dùng đã ký hợp đồng và xảy ra tranh chấp); người dân vẫn thiếu công cụ tiền kiểm để phòng ngừa ngay tại thời điểm ký. | Sản phẩm cần đóng vai trò công cụ tiền kiểm soát (Pre-signing Verification Tool) ngay tại điểm bán. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm KHÔNG build một chatbot AI tư vấn pháp lý chung chung (dễ hallucinate và vi phạm quy định tư vấn luật). Nhóm tập trung xây dựng kiến trúc lai (Hybrid Workflow): dùng AI OCR bóc tách thực thể hợp đồng, dùng Code Engine tính toán dòng tiền/APR chính xác 100%, dùng Rule Engine phát hiện 50+ điều khoản bẫy phạt và dùng LLM diễn đạt dễ hiểu kèm 3 câu hỏi chất vấn trước khi ký.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

![Group Workflow](02-group-problem-statement-workflow.png)

```text
[1 Nhận HĐ 15-25 trang: 2' - Nhân viên đưa] 
→ [2 Đọc lướt chữ nhỏ: 10' - Người vay] 
→ [3 Tự nhẩm tính / bỏ qua phụ lục: 15' - NÚT THẮT] 
→ [4 Ký hợp đồng mù mờ: 3' - Người vay ký giấy/OTP] 
→ [5 Phát hiện bị trừ phí oan/phạt nặng sau đó: 20' - Người vay chịu trận]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Nhận hợp đồng | Nhân viên tín dụng / Sales | Hồ sơ duyệt vay thành công | Bản hợp đồng in chữ nhỏ 15–25 trang (hoặc PDF trên app) | 2 phút | Nhân viên hối thúc ký nhanh để kịp làm thủ tục giải ngân tại quầy. |
| 2. Đọc lướt tại quầy | Người vay cá nhân | Hợp đồng 15–25 trang | Cảm nhận ban đầu về số tiền nhận & số tiền góp hàng tháng | 5–10 phút | Quá tải nhận thức, chữ nhỏ, người vay chỉ lướt qua trang đầu có ghi số tiền. |
| 3. Tự nhẩm tính & bỏ qua phụ lục | Người vay cá nhân | Lời tư vấn miệng (lãi 18%/năm) | Hiểu sai về chi phí thực tế của khoản vay | 15 phút | **BOTTLENECK CHÍNH:** Không biết cách tính APR, không phân biệt lãi phẳng vs lãi giảm dần, bỏ qua phụ lục phí phạt. |
| 4. Ký kết hợp đồng | Người vay cá nhân | Hợp đồng chưa được hiểu rõ | Chữ ký xác nhận / Nhập mã OTP điện tử | 3 phút | Ký hợp đồng trong trạng thái 'mù mờ điều khoản', hoàn tất thủ tục vay. |
| 5. Phát sinh tranh chấp/phạt | Người vay & Tổ chức cho vay | Yêu cầu tất toán sớm hoặc trễ hạn 2–3 ngày | Bị phạt 150% lãi suất, trừ 1–3 triệu phí bảo hiểm | Kéo dài nhiều ngày/tháng | Người vay ngã ngửa vì số tiền phạt quá lớn, dẫn đến khiếu nại gửi VCC hoặc dính nợ xấu CIC. |

**Bottleneck chính (2-3 câu):**

```text
Nút thắt nghiêm trọng nhất nằm ở Bước 3: Người vay hoàn toàn bất lực trước việc tính toán chi phí vốn hiệu dụng (APR) và bóc tách các loại phí ẩn từ văn bản hợp đồng phức tạp dài hàng chục trang. Sự bất cân xứng thông tin và áp lực thời gian khiến người vay phó mặc cho lời tư vấn một chiều của nhân viên sales.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Upload ảnh/PDF hợp đồng: 1' - Người dùng] 
→ [2 AI OCR bóc tách thực thể tài chính: 1' - AI Workflow] 
→ [3 Code Engine tính dòng tiền & APR chuẩn: 1' - Rule/Code] 
→ [4 AI xuất tóm tắt 1 trang & 3 câu hỏi chất vấn: 1' - AI Workflow] 
→ [5 Người vay đối chất tư vấn & chốt quyết định: 3' - HUMAN BOUNDARY]

Fallback: Nếu ảnh chụp mờ hoặc AI quét lỗi -> Hệ thống yêu cầu chụp lại trang bảng tính nợ & phụ lục; cảnh báo người dùng kiểm tra thủ công các dòng nghi vấn.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian đọc hiểu & rà soát | 50 phút | 7 phút | Bấm giờ thực nghiệm từ lúc nhận văn bản đến khi nắm rõ nghĩa vụ tài chính. |
| Thời gian bóc tách điều khoản hợp đồng | 45 phút | Dưới 2 phút | Thời gian xử lý tự động của hệ thống từ lúc upload file đến lúc trả về kết quả. |
| Độ chính xác tính toán dòng tiền & APR | Dưới 10% (tự đoán mò) | $\ge$ 99,5% | Đối chiếu công thức tính APR của Code Engine với bảng khấu hao tài chính chuẩn. |
| Tỷ lệ nhận diện bẫy phí phạt & bảo hiểm | Dưới 20% (thường bỏ sót) | $\ge$ 95% | So khớp danh mục phí do AI bóc tách với toàn bộ điều khoản thực tế trong 50 hợp đồng mẫu. |
| Rủi ro mất tiền phạt / phí oan ngoài ý muốn | 1.000.000 – 3.000.000 VNĐ | 0 VNĐ | Đo lường số người dùng phát hiện và từ chối/thương lượng lại khoản phí trước khi ký. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người tiêu dùng cá nhân vay tiêu dùng/trả góp (mua xe, điện thoại, đồ gia dụng, vay tiền mặt) tại các công ty tài chính và ngân hàng. |
| **Workflow** | Người vay nhận hợp đồng 15–25 trang tại điểm bán (POS), đọc lướt trong 5–10 phút, tự nhẩm tính theo lời tư vấn miệng của sales, ký hợp đồng mù mờ và sau đó ngã ngửa khi phát sinh phí phạt hoặc lãi suất thực tế quá cao. |
| **Bottleneck** | Bước đọc hiểu văn bản pháp lý và tính toán dòng tiền thực tế: người vay bị quá tải nhận thức, không thể bóc tách các loại phí ẩn và không biết cách tính lãi suất hiệu dụng (APR). |
| **Impact** | Người vay chịu lãi suất thực tế lên tới 35%–50%/năm (cao gấp 2–2.5 lần lãi suất quảng cáo), mất oan từ 1–3 triệu đồng tiền phí bảo hiểm/phí phạt và phát sinh hàng nghìn vụ khiếu nại gửi cơ quan bảo vệ người tiêu dùng (VCC). |
| **Success Metric** | Rút ngắn thời gian đọc hiểu từ 50 phút xuống dưới 2 phút; đạt độ chính xác tính toán APR $\ge$ 99,5%; 100% người dùng nắm rõ tổng số tiền thực trả và có 3 câu hỏi chất vấn trước khi ký. |
| **Boundary** | AI không quyết định thay người dùng có nên vay hay không; AI không cung cấp tư vấn pháp lý thay luật sư; mọi kết luận của AI bắt buộc phải dẫn chiếu số trang và điều khoản trong hợp đồng gốc. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Metric 'người dùng hiểu hợp đồng' đo bằng cách nào để không mang tính cảm tính?
- Tôi sửa gì: Nhóm đã cụ thể hóa bằng bài test trắc nghiệm 3 câu hỏi sau khi đọc (hỏi đúng tổng tiền thực trả, tiền thực nhận và mức phí phạt tất toán); chỉ coi là đạt nếu trả lời đúng 100%.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Cao (nhiều cách diễn đạt hợp đồng pháp lý khác nhau) — Vì sao: Mỗi công ty tài chính có cách dùng từ, đặt tên khoản phí và cấu trúc văn bản hoàn toàn khác nhau; không thể dùng regex cứng để bắt từ khóa.
- Độ phức tạp: [x] Thấp (pipeline 5 bước tuyến tính, đi thẳng một đường) — Vì sao: Quy trình đi thẳng từ file đầu vào -> trích xuất -> tính toán -> xuất báo cáo; không cần rẽ nhiều nhánh phức tạp.

**Bài toán nhóm nằm ở ô nào:**

```text
Nằm ở ô: Độ phức tạp thấp - Độ mơ hồ cao (Góc trên bên phải của ma trận đơn giản).
```

**Vì sao (2-3 câu):**

```text
Văn bản hợp đồng là dữ liệu phi cấu trúc với ngôn ngữ pháp lý biến thiên liên tục (độ mơ hồ cao về mặt ngôn ngữ), do đó cần LLM để đọc hiểu và trích xuất. Tuy nhiên luồng xử lý của bài toán lại đi thẳng một mạch cố định (tuyến tính), không đòi hỏi hệ thống phải tự lập kế hoạch hành động hay phân nhánh phức tạp.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng biểu thức mẫu (Regex) quét từ khóa phí + Bảng tính Excel cố định. | Đủ nếu tất cả các công ty tài chính dùng chung 1 biểu mẫu hợp đồng quy chuẩn duy nhất. | Thất bại hoàn toàn khi gặp mẫu hợp đồng mới, các biến thể tên gọi phí biến tướng và lỗi định dạng ảnh chụp. | **Chỉ dùng cho bước tính toán toán học (Deterministic Financial Engine).** |
| **Workflow** | Pipeline kết hợp: OCR bóc tách thực thể -> Code Engine tính tiền -> Rule Engine quét bẫy -> LLM diễn giải và sinh câu hỏi. | Hoàn hảo cho bài toán này vì các bước xác định rõ ràng, kết hợp được thế mạnh ngôn ngữ của LLM và tính chính xác tuyệt đối của Code. | LLM có thể trích xuất thiếu nếu ảnh chụp quá mờ (khắc phục bằng cơ chế Human Boundary và Fallback). | **CHỌN LÀM PHƯƠNG ÁN CHÍNH CHO TOÀN BỘ SẢN PHẨM.** |
| **Agent** | Agent tự trị tự động tìm kiếm, lập kế hoạch, tự thương lượng hoặc tự gửi khiếu nại thay người dùng. | Chỉ cần thiết nếu hệ thống phải tự động tương tác qua lại đa vòng với cổng dịch vụ công hoặc tự động chat với bot của ngân hàng. | Quá phức tạp, chi phí vận hành cao, dễ mất kiểm soát hành vi (overkill) và tạo ra rủi ro pháp lý nghiêm trọng. | **KHÔNG CHỌN.** |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Không, vì hợp đồng tín dụng tiêu dùng tại Việt Nam không có mẫu chuẩn bắt buộc, ngôn ngữ và tên gọi phí cài cắm rất đa dạng.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Đi thẳng một đường: Upload -> Understand -> Calculate -> Detect -> Ask.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Không cần, vì mục tiêu là hỗ trợ người dùng hiểu văn bản tại thời điểm ký, không cần AI tự quyết định hành động tiếp theo.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Người dùng phát hiện khi đối chiếu với 3 câu hỏi chất vấn nhân viên tư vấn tại quầy; sửa trong vòng 1-2 phút bằng cách đối chiếu số trang hợp đồng được AI trích dẫn sẵn.
5. Có hạ được từ Agent → Workflow → Rule không? Có, nhóm đã chủ động hạ từ Agent xuống **Workflow kết hợp Deterministic Code Engine** để đảm bảo an toàn và tính toán chính xác 100%.

**Mức chọn:**

```text
Workflow (AI Pipeline kết hợp Deterministic Engine).
```

**Vì sao chọn (3-4 câu):**

```text
Workflow là giải pháp tối ưu nhất vì tận dụng đúng thế mạnh của từng công nghệ: AI OCR và LLM giải quyết bài toán đọc hiểu ngôn ngữ pháp lý phi cấu trúc; Deterministic Code Engine giải quyết bài toán tính toán dòng tiền và APR chính xác tuyệt đối mà không sợ hallucination; Rule Engine kiểm tra đối soát 50+ điều khoản bẫy phạt theo danh mục định sẵn. Luồng xử lý có con người kiểm soát (Human-in-the-loop) ở bước cuối giúp triệt tiêu hoàn toàn rủi ro trách nhiệm pháp lý.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không thể hạ xuống mức Rule thuần túy vì văn bản hợp đồng tín dụng thực tế có hàng trăm biến thể tên gọi (ví dụ: 'phí bảo hiểm tín dụng', 'khoản thu bảo an khoản vay', 'chi phí dịch vụ quản lý hồ sơ'). Quy tắc Rule cứng sẽ bị gãy ngay khi gặp một công ty tài chính mới cập nhật mẫu biểu.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người tiêu dùng cá nhân vay tiêu dùng/trả góp (mua xe, điện thoại, đồ gia dụng, vay tiền mặt) tại các công ty tài chính và ngân hàng. |
| **Workflow** | Upload ảnh/PDF hợp đồng -> AI bóc tách các trường tài chính -> Code Engine tính toán tổng tiền thực trả và APR -> AI phát hiện bẫy phí phạt -> Xuất báo cáo tóm tắt 1 trang và 3 câu hỏi chất vấn -> Người vay dùng câu hỏi đối chất với sales tại quầy -> Tự quyết định ký hoặc từ chối. |
| **Bottleneck** | Bước đọc hiểu văn bản pháp lý 15–25 trang và tính toán chi phí vốn hiệu dụng (APR) dưới áp lực thời gian tại quầy giao dịch POS. |
| **Impact** | Giúp người vay không bị sốc lãi suất thực (35%–50%/năm), tránh mất oan từ 1–3 triệu đồng tiền phí bảo hiểm/phạt ẩn, giảm áp lực khiếu nại tài chính tiêu dùng cho cơ quan quản lý (VCC). |
| **Success Metric** | Thời gian xử lý tài liệu < 60 giây; độ chính xác tính APR và dòng tiền $\ge$ 99,5%; độ nhạy phát hiện phí ẩn $\ge$ 99%; 100% kết luận đều có trích dẫn số trang và số điều khoản hợp đồng gốc. |
| **Boundary** (làm / không làm) | **LÀM:** Trích xuất thực thể, tính toán toán học chuẩn, phát hiện điều khoản rủi ro, sinh câu hỏi chất vấn.<br>**KHÔNG LÀM:** Không khuyên người dùng nên vay hay không; không đưa ra kết luận pháp lý thay luật sư; không đại diện đi kiện tụng. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay sau bước người vay nhận văn bản hợp đồng từ nhân viên tư vấn, và TRƯỚC KHI người vay đặt bút ký hợp đồng hoặc nhập mã OTP xác thực. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow:** Kết hợp OCR + LLM bóc tách + Deterministic Math Code Engine + Rule Engine để đảm bảo tốc độ và độ chính xác toán học 100%. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là ảnh chụp hợp đồng bị mờ dẫn đến trích xuất thiếu phí. Người thật kiểm tra: Người vay đối chiếu kết quả với 3 câu hỏi chất vấn nhân viên tư vấn tại quầy; hệ thống hiển thị dẫn chiếu số trang để người dùng tự kiểm tra dòng tiền thực nhận. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Người vay cá nhân tại quầy POS; quy trình 5 bước tuyến tính rất rõ ràng. |
| Baseline + metric đo được chưa? | Yes | Baseline 50 phút đọc mò -> Target < 2 phút; APR tính đúng $\ge$ 99,5%. |
| Data/input đủ dùng chưa? | Yes | Hợp đồng vay tiêu dùng mẫu (PDF/ảnh chụp) có sẵn nhiều trên thị trường và từ người dùng thật. |
| AI sai, hậu quả chấp nhận được không? | Yes | Hậu quả kiểm soát được nhờ tính toán bằng Code và có Human Boundary chất vấn lại trước khi ký. |
| Có người review/owner không? | Yes | Người vay là chủ thể trực tiếp review và quyết định cuối cùng. |
| Có cách non-AI đơn giản hơn không? | No | Các công cụ Excel/Rule cứng không thể tự động bóc tách văn bản hợp đồng phi cấu trúc. |

**Decision:**

```text
Go với scope nhỏ (Pilot Consumer Installment Loans).
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Dự án giải quyết một vấn đề có thật, nhức nhối với bằng chứng chính thức từ Báo cáo VCC 2025 và quy định của Luật Bảo vệ quyền lợi người tiêu dùng 2023. Kiến trúc kỹ thuật dạng Workflow đã tách bạch rõ ràng giữa phần việc của LLM và Code tính toán xác định, đảm bảo loại bỏ hoàn toàn rủi ro sai sót toán học. Ranh giới sản phẩm (Boundary) minh bạch, đặt quyền quyết định vào tay người tiêu dùng. Nhóm có lộ trình pilot rõ ràng, đo lường được và có phương án dự phòng (fallback) an toàn.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Tập dữ liệu pilot: Thu thập 50–100 hợp đồng vay tiêu dùng/trả góp thật đã được ẩn danh hóa (anonymized) từ các công ty tài chính phổ biến (FE Credit, Home Credit, HD Saison, Mirae Asset).
- Vận hành pilot: Chạy workflow bán tự động — đưa hợp đồng qua OCR + LLM trích xuất -> Code Engine tính toán -> Kiểm tra chéo kết quả thủ công bởi chuyên gia tài chính.
- Đo 3 chỉ số then chốt:
  1. Thời gian xử lý từ lúc tải hợp đồng đến khi ra kết quả (< 60 giây).
  2. Độ chính xác trích xuất danh mục phí và tính APR (đạt $\ge$ 99%).
  3. Tỷ lệ người dùng thử nghiệm hiểu đúng tổng nợ và phát hiện được bẫy phí ẩn (đạt $\ge$ 85%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn GO; tuy nhiên nếu mở rộng sang mảng Vay thế chấp Bất động sản thì cần validate tính pháp lý của các loại tài sản bảo đảm trước).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì quyết định là GO).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Nếu trên tập dữ liệu kiểm thử 50 hợp đồng, tỷ lệ trích xuất sai hoặc bỏ sót phí ẩn vượt quá 5%, hệ thống sẽ lập tức dừng chế độ tự động phân tích và chuyển sang hiển thị Checklist câu hỏi thủ công để người dùng tự hỏi nhân viên tư vấn.
- Nếu người dùng phản hồi rằng việc chụp ảnh hợp đồng tại quầy gặp khó khăn do nhân viên ngăn cấm, sản phẩm sẽ bổ sung tính năng 'Nhập nhanh 3 con số' (Số tiền vay, Số tiền góp/tháng, Kỳ hạn) để tự động tính ngược ra APR và cảnh báo chênh lệch mà không cần quét cả hợp đồng.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

