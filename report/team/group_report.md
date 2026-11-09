# Báo cáo nhóm — Day 02 Discovery & Problem Framing

## 1. Thông tin nhóm

- **Tên nhóm:** Nhom7
- **Thành viên:** Dương Thị Huyền, Hoàng Thị Thanh Nga, Bùi Thu Phương, Phạm Minh Tâm; phân công xem [TEAM.md](../../TEAM.md).
- **Candidate problem được chọn (1 câu):** Học viên AI20k mất nhiều thời gian và dễ sót yêu cầu khi đối chiếu bài lab với rubric trước khi nộp.
- **Quyết định cuối:** Not Yet

## 2. Hội tụ nhóm (CP3)

### 2.1. Tổng hợp candidate để pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Điểm cần làm rõ từ báo cáo cá nhân |
|---|---|---|---|---|---|
| 1 | Huyền | Khi sắp nộp lab, muốn biết bài còn thiếu gì so với rubric | Học viên AI20k | Đối chiếu từng tiêu chí, ~15' | Baseline của một người có đại diện cho người ngoài nhóm không? (Huyền, CP2) |
| 2 | Huyền | Khi có thắc mắc, muốn tìm lại câu trả lời cũ của coach | Học viên, coach/TA | Đọc thread, ~10' | FAQ ghim có đủ không? (Huyền, CP2) |
| 3 | Huyền | Khi thảo luận rải rác, muốn biết nhóm đã chốt gì, ai làm gì | Thành viên nhóm | Hỏi lại và chờ xác nhận, ~15' | Bảng phân công hoặc tin ghim có đủ không? (Huyền, CP2) |
| 4 | Nga | Khi bắt đầu lab, muốn biết phải nộp file và mục nào | Học viên AI20k | Soát bài trước khi nộp, 25' | Checklist tự lập từ rubric đã đủ chưa? (Nga, CP2) |
| 5 | Nga | Khi thông báo ở nhiều kênh, muốn biết deadline sắp tới | Học viên cả lớp | Lướt group chat, 10'/lần | Có trường hợp trễ hạn do thông báo phân tán không? (Nga, CP2) |
| 6 | Nga | Khi có bạn vắng, bạn ấy muốn biết nhóm đã quyết định gì | Thành viên vắng, người giải thích | Nhớ lại và tóm tắt, 4' | Biên bản họp có giảm việc hỏi lại không? (Nga, CP2) |
| 7 | Phương | Khi tìm hiểu chủ đề đồ án, muốn so sánh phương pháp nhiều bài báo | Sinh viên làm đồ án | Ghi chú và lập bảng so sánh | Mẫu bảng cố định có đủ không? (Phương, CP2) |
| 8 | Phương | Khi sắp nộp bài, muốn đối chiếu bài với đề và rubric | Sinh viên | Dò yêu cầu: card ghi 5', sơ đồ ghi 20'; cần thống nhất | Thời gian dò yêu cầu là 5 hay 20 phút? (hai số khác nhau trong Card #2 của Phương) |
| 9 | Phương | Khi ôn thi từ nhiều nguồn, muốn biết trọng tâm mình chưa nắm | Sinh viên trước kỳ thi | Gom và sắp xếp tài liệu | Đo thời gian chuẩn bị hay toàn bộ thời gian ôn? (Phương, CP2) |
| 10 | Tâm | Khi nhận phản hồi của giảng viên, muốn hiểu rõ nội dung cần sửa | Thành viên nhóm | Đối chiếu, tìm thông tin bổ sung (~180', cần xác minh phạm vi) | 180 phút là một người hay cả nhóm, một lần hay nhiều lần? (Tâm, CP2) |
| 11 | Tâm | Khi ôn một chủ đề, muốn nắm ý chính từ slide và ghi chú | Sinh viên | Đối chiếu ~4 nguồn, tổng ~45' | Bước nào trong 45 phút mất nhiều thời gian nhất? (Tâm, CP2) |
| 12 | Tâm | Khi làm bài nhóm, muốn biết ai phụ trách phần nào | Thành viên nhóm | Hỏi và xác nhận, ~10'/tuần | Việc hỏi lại đã gây làm trùng/bỏ sót chưa? (Tâm, CP2) |

Bảng trên tổng hợp nội dung CP1–CP2, không phải biên bản hỏi–đáp CP3. Chưa có ghi chép xác nhận ai đã hỏi ai trong buổi pitch.

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Soát bài trước khi nộp | #1, #4, #8 | Đối chiếu bài làm với một bộ yêu cầu nhiều điều kiện |
| B — Tìm, tổng hợp tài liệu | #2, #7, #9, #11 | Tìm và gom thông tin từ nhiều nguồn rời rạc |
| C — Phối hợp nhóm | #3, #6, #12 | Không rõ nhóm đã chốt gì, ai làm gì |
| D — Thông tin và phản hồi từ người dạy | #5, #10 | Thông tin từ coach, giảng viên khó theo dõi và xử lý |

### 2.3. Opportunity Solution Tree rút gọn

    OUTCOME: Giảm thời gian soát bài trước khi nộp mà không sót tiêu chí rubric
    ├── Opportunity A: Rubric có nhiều điều kiện phụ, khó nhớ hết khi đối chiếu
    ├── Opportunity B: Phải dò thủ công từng yêu cầu trong một báo cáo dài
    └── Opportunity C: Lỗi hình thức (tên file, link chết) chỉ phát hiện sát deadline

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Chatbot kiểm tra rubric"
- "Script tự kiểm tên file"

### 2.4. Chấm điểm shortlist (1–5)

Nhóm chấm 1–5 theo 7 tiêu chí. Điểm “pain có bằng chứng” dựa trên ghi nhận của các thành viên, chưa có bằng chứng từ người ngoài nhóm.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---|---|---|---|---|---|---|---|
| A — Đối chiếu bài với rubric | 5 | 5 | 4 | 4 | 5 | 5 | 5 | 33 |
| B — Gom tài liệu ôn tập | 4 | 4 | 3 | 3 | 4 | 4 | 4 | 26 |
| C — Ai làm gì, nhóm đã chốt gì | 4 | 3 | 3 | 3 | 5 | 2 | 5 | 25 |

**Candidate được chọn:** A — Đối chiếu bài lab với rubric trước khi nộp.

**Vì sao chọn:** Cả 4 thành viên đều ghi nhận vấn đề này trong phần scan. Quy trình vẽ được, bottleneck là một bước cụ thể, hậu quả đo được theo RUBRIC (sai tên file trừ 5 điểm, thiếu file bắt buộc thì phần nhóm bị 0), và bấm giờ được ngay ở lab tiếp theo.

**Vì sao loại các candidate còn lại:**

- B: phụ thuộc mùa thi, và chưa thống nhất được cách đo "nắm đúng trọng tâm".
- C: bảng phân công hoặc tin nhắn ghim là hướng xử lý trực tiếp; phạm vi phân tích lần này ưu tiên vấn đề đối chiếu yêu cầu xuất hiện ở nhiều báo cáo. Chưa cần nâng mức can thiệp cho bài toán phối hợp nhóm.

**Xử lý bất đồng:** Nhóm không có bất đồng cụ thể. Các ý kiến ưu tiên khác nhau được giữ ở bảng shortlist; nếu đánh giá lại, nhóm so sánh phạm vi đo, mức độ ảnh hưởng và khả năng kiểm chứng thay vì chỉ dựa vào tổng điểm.

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---|---|---|---|---|---|
| 1 | Học viên ngoài nhóm cũng mất trên 20 phút soát bài mỗi lab | Value | 5 | 2 | Có |
| 2 | Học viên từng bị trừ điểm hoặc suýt nộp thiếu vì sót yêu cầu | Value | 5 | 2 | Có |
| 3 | Checklist tick tay không đủ để phát hiện thiếu về nội dung | Value | 5 | 1 | Có |
| 4 | Học viên kiểm tra lại được các mục AI chỉ ra | Usability | 4 | 2 | Có |
| 5 | AI đối chiếu được báo cáo Markdown với rubric đủ chính xác | Feasibility | 4 | 2 | Thử trên 1 bài |
| 6 | Quy định khóa học cho phép dùng AI để rà bài | Viability | 4 | 3 | Hỏi coach |

**Giả định ưu tiên kiểm chứng:** #1, #2, #3. Thang bằng chứng hiện phản ánh dữ liệu nội bộ, không tương đương phỏng vấn bên ngoài.

### 3.2. Kiểm chứng: dữ liệu hiện có và bước tiếp theo

**Nguồn hiện có:** bốn báo cáo cá nhân. Chưa có interview snapshot, kết quả survey, thời điểm hỏi hoặc lời nói nguyên văn của người ngoài nhóm trong repo. Vì vậy, không tính các ghi nhận dưới đây là đã hoàn thành phỏng vấn CP4.

| Nguồn | Dấu hiệu ghi trong báo cáo | Tín hiệu hỗ trợ bài toán | Giới hạn / tín hiệu cần kiểm tra lại |
|---|---|---|---|
| [Huyền](../individual/2A202604077_DuongThiHuyen.md), CP2 Card #1 | Tổng 40 phút; đối chiếu tiêu chí 15 phút | Quy trình có thể phân tách và đo thời gian | Số gần đúng của cá nhân; target cá nhân 15 phút chưa được thử |
| [Nga](../individual/2A202604079_HoangThiThanhNga.md), CP2 Card #1 | Toàn quy trình 70 phút, gồm 25 phút soát bài | Soát trước nộp là một bước nghẽn | 70 phút gồm cả đọc đề từ đầu; không so trực tiếp với tổng 40 phút của Huyền. Nhận định “quen cấu trúc sẽ nhanh hơn” chưa có kiểm chứng ngoài nhóm |
| [Phương](../individual/2A202604080_BuiThuPhuong.md), CP1 #6 và CP2 Card #2 | CP1 ghi 30 phút đối chiếu; sơ đồ CP2 tổng 50 phút | Có khó khăn khi dò yêu cầu và khai báo từng bị trừ điểm | Card ghi bottleneck 5 phút, sơ đồ ghi 20 phút; số lần bị trừ điểm và phạm vi thời gian cũng chưa thống nhất. Chưa dùng làm baseline chung |
| [Tâm](../individual/2A202604097_PhamMinhTam.md), CP1 #3 | Khoảng 30 phút đối chiếu báo cáo cùng nhóm | Bổ sung dấu hiệu về nhu cầu hiểu đúng yêu cầu | Chưa phân tách thời gian cá nhân, trao đổi nhóm và sửa bài; 180 phút ở Card #1 là xử lý phản hồi sau đó, không phải soát trước nộp |

**Kết luận từ đối chiếu:** Có tín hiệu nội bộ cho vấn đề soát bài, nhưng chưa đủ để suy rộng cho cả lớp hoặc kết luận cần Workflow. Mốc 40 phút dùng để mô tả một quy trình tham chiếu của Huyền, không phải trung bình của bốn người. Chưa có tín hiệu phản bác từ người dùng ngoài nhóm; khả năng checklist đã đủ là giả định phải chủ động tìm bằng chứng.

**Kế hoạch phỏng vấn:** Nga phối hợp Tâm theo phân công ghi trong báo cáo cá nhân của Nga; tiếp cận 2–3 học viên ngoài nhóm đã nộp một bài lab có rubric. Ghi ngày, cách hỏi, vai trò, bài lab gần nhất và số người thực sự tham gia khi thực hiện. Không tính khảo sát chưa có phản hồi là dữ liệu.

| Mục tiêu | Câu hỏi về hành vi đã xảy ra | Bằng chứng cần ghi |
|---|---|---|
| Xác nhận pain và phạm vi thời gian | Lần nộp lab gần nhất bạn soát bài thế nào? Bắt đầu và kết thúc ở bước nào? | Các bước, phút xử lý, phút chờ và phạm vi tính |
| Xác nhận hậu quả | Lần gần nhất bạn phát hiện thiếu mục hoặc nhận phản hồi thiếu yêu cầu là khi nào? | Ví dụ cụ thể, tiêu chí liên quan; xem nhận xét chấm nếu người hỏi đồng ý |
| Kiểm tra phương án đơn giản | Bạn đã dùng checklist chưa? Ở lần gần nhất, cách đó giúp gì và còn sót gì? | Workaround đã dùng, chi phí thời gian, lỗi còn lại |
| Tìm tín hiệu phản bác | Ở bài nào bạn soát nhanh hoặc không cần hỏi lại? Khi đó bạn làm khác thế nào? | Trường hợp checklist đủ, quen cấu trúc, hoặc ít yêu cầu |
| Kiểm tra cách duyệt đầu ra | Lần gần nhất dùng gợi ý từ công cụ, bạn đã kiểm tra và quyết định sửa thế nào? | Cách kiểm nguồn, trường hợp bỏ gợi ý và lý do |

Mỗi cuộc phỏng vấn cần snapshot gồm: vai trò, thời điểm/cách hỏi, câu nói nguyên văn, sự kiện gần nhất, workaround, thời gian/tần suất và insight. Chưa có snapshot thực tế để đưa vào báo cáo này.

**Điều chỉnh phạm vi sau rà soát tài liệu:** Tập trung vào học viên nộp báo cáo Markdown có rubric và bước dò nội dung còn chậm; tách đọc đề ban đầu và xử lý phản hồi sau chấm khỏi quy trình soát trước nộp. Đây là điều chỉnh từ đối chiếu nguồn nội bộ, chưa phải thay đổi sau phỏng vấn.

### 3.3. Research giải pháp đã có

Đối chiếu các trang nguồn ngày 09/11/2026. Khả năng áp dụng vào báo cáo tiếng Việt và rubric của lab là nhận định cần thử nghiệm, không phải kết quả sử dụng công cụ.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Grammarly AI Grader | https://www.grammarly.com/ai-agents/ai-grader | Bước 2: nhận bài và rubric, ước tính điểm, góp ý trước khi nộp | Đúng việc đối chiếu với rubric; học viên chủ động áp dụng hoặc bỏ gợi ý | Trang sản phẩm mô tả bài viết tiếng Anh trong Docs; chưa xác nhận độ phù hợp với Markdown tiếng Việt hoặc kiểm cấu trúc repo. Điểm chỉ là dự đoán | Đã có công cụ cho bước đối chiếu, nên thử trước khi tự xây; vẫn cần người kiểm |
| lychee-action | https://github.com/lycheeverse/lychee-action | Bước 4: kiểm link trong Markdown | Tự động, không dùng AI, chạy trên GitHub Actions | Cần cấu hình workflow; chỉ kiểm link | Phần kiểm link giải được bằng Rule |
| GitHub Classroom autograding | https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding | Bước 3: chạy kiểm tra tự động mỗi lần push | Pattern phù hợp: học viên xem kết quả, sửa, push lại | Theo trang tài liệu, GitHub Classroom ngừng hoạt động từ 28/08/2026, và chủ yếu kiểm code | Mượn pattern bằng GitHub Actions; lỗi hình thức không cần AI |

Kết luận research: Rule phù hợp với điều kiện hình thức; công cụ đối chiếu nội dung tương tự đã tồn tại nhưng chưa chứng minh độ phù hợp với Markdown tiếng Việt. Sau kiểm chứng nhu cầu, có thể thử công cụ hoặc prompt có sẵn trước khi cân nhắc xây sản phẩm.

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

    HIỆN TẠI — khoảng 40 phút/lab
    [1 Mở rubric: 3'] → [2 Đối chiếu từng tiêu chí: 15'] ← BOTTLENECK
    → [3 Kiểm tên file, ảnh: 5'] → [4 Kiểm link: 5'] → [5 Sửa: 10'] → [6 Push, nộp LMS: 2']

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Học viên | RUBRIC.md, SUBMISSION.md | Danh sách yêu cầu cần soát | 3', mỗi lab | |
| 2 | Học viên | Rubric, file báo cáo | Danh sách mục thiếu | 15', mỗi lab | Bottleneck của quy trình tham chiếu Huyền; không gộp số của các thành viên |
| 3 | Học viên | Repo, quy tắc đặt tên | Tên file, ảnh đúng | 5', mỗi lab | Sai tên trừ 5 điểm |
| 4 | Học viên | Các link trong báo cáo | Link mở được | 5', mỗi lab | Link chết bị trừ điểm ở C7 |
| 5 | Học viên | Danh sách mục thiếu | Báo cáo đã sửa | 10', mỗi lab | Phụ thuộc số lỗi |
| 6 | Học viên | Repo đã sửa | Commit, link trên LMS | 2', mỗi lab | Handoff cho coach chấm |

**Bottleneck chính:** Bước 2, vì rubric có nhiều điều kiện phụ (ví dụ "tối thiểu 200 từ", "có tín hiệu phản bác", "có ngưỡng dừng"), phải dò từng điều kiện trong báo cáo dài. Số phút là số tự ghi nhận của thành viên, chưa đo trên người ngoài nhóm.

### 4.2. Quy trình tương lai

    TƯƠNG LAI — khoảng 20 phút/lab (kỳ vọng)
    [1 Kiểm tên file, file bắt buộc, link: 1'] ← RULE (script)
    → [2 Đối chiếu nội dung với rubric, liệt kê mục nghi thiếu kèm vị trí: 2'] ← AI
    → [3 Kiểm từng mục AI nêu, tick checklist: 5'] ← CON NGƯỜI
    → [4 Sửa bài: 10'] ← CON NGƯỜI
    → [5 Push, nộp LMS: 2'] ← CON NGƯỜI

**Boundary:** AI không viết hoặc sửa nội dung bài, không chấm điểm thay coach, không tự commit hay nộp, không xác nhận "đạt" nếu không chỉ ra được vị trí trong bài.

**Phương án quay về:** AI nêu sai nhiều hoặc không dùng được thì quay về checklist tick tay từ RUBRIC và SUBMISSION; script vẫn dùng cho tên file và link.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---|---|---|
| Số bước | 6 | 5 | Gộp kiểm tên file và kiểm link |
| Tổng thời gian | ~40' | ~20' | Bước sửa bài không giảm vì phụ thuộc số lỗi |
| Số bước thủ công | 6/6 | 3/5 | Học viên vẫn kiểm, sửa, nộp |
| Bottleneck chính | Đối chiếu từng tiêu chí | Sửa bài | Chấp nhận được vì đây là việc chính |
| Rủi ro mới phát sinh | — | AI bỏ sót mục thiếu hoặc báo nhầm | Xử lý bằng boundary và tiêu chí đánh giá |

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| Actor | Học viên AI20k nộp bài lab qua repo GitHub |
| Quy trình | Mở rubric → đối chiếu từng tiêu chí → kiểm tên file, ảnh → kiểm link → sửa → push và nộp LMS |
| Bottleneck | Đối chiếu từng tiêu chí với báo cáo: khoảng 15 phút trong quy trình tham chiếu của Huyền; có nguy cơ sót điều kiện phụ |
| Impact | ~40'/lab × 2–3 lab/tuần; sai tên file trừ 5 điểm; thiếu file bắt buộc thì phần nhóm bị 0 |
| Success Metric | (1) Tổng thời gian soát bài từ ~40' (tự ghi nhận) xuống ≤20', đo bằng ghi giờ bắt đầu/kết thúc trong 2 lab; (2) số tiêu chí bị sót, baseline đo ở lab kế tiếp, mục tiêu 0 |
| Boundary | AI không viết hoặc sửa nội dung bài, không chấm điểm thay coach, không tự nộp. Học viên kiểm tra từng mục AI nêu trước khi sửa (HITL) |

**Các điểm phản biện đối chiếu từ CP2 và rà soát v0:**

- Câu hỏi chuẩn bị pitch của Huyền: pain có phổ biến ngoài cá nhân không? Liên quan giả định #1 và #2; chưa có câu trả lời từ phỏng vấn.
- Câu hỏi chuẩn bị pitch của Nga: checklist tự lập từ rubric đã đủ chưa? Liên quan giả định #3; cần thử phương án này trước khi chọn mức cao hơn.
- Rà soát v0 cho thấy cần phân biệt tổng thời gian với thời gian dò nội dung; cần đo cả báo nhầm và bỏ sót. Bản v1 bổ sung cách đo chất lượng và giới hạn actor. Chưa có nhật ký xác nhận nhóm khác phản biện v0.

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô:** độ mơ hồ cao ở phần đối chiếu nội dung, độ phức tạp thấp.

**Vì sao:** Tên file và link có đúng/sai rõ. Đánh giá "đã có tín hiệu phản bác chưa" cần đọc hiểu nội dung. Các bước cố định, không rẽ nhánh, nên chưa cần AI tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| No AI | Checklist từ RUBRIC và SUBMISSION, tick khi làm xong từng phần | Checklist giúp đạt target thời gian và không sót yêu cầu | Cần học viên tự đối chiếu, mức tiết kiệm chưa đo | Thử trước; cũng là phương án quay về |
| Rule | Script kiểm tên file, file bắt buộc, link | Lỗi chủ yếu về hình thức | Không đánh giá được nội dung | Dùng cho bước 1 |
| Workflow | Rule → AI liệt kê mục nghi thiếu → học viên kiểm và sửa | Bước cố định, chỉ phần đối chiếu nội dung cần đọc hiểu | AI bỏ sót hoặc báo nhầm | Chọn (có điều kiện) |
| Agent | AI tự tìm yêu cầu, tự sửa bài, tự commit | Bước tiếp theo không đoán trước được | Quyền ghi vào repo, dễ làm thay học viên, khó kiểm soát | Không |

**Mức chọn:** Workflow (kết hợp Rule ở bước 1), chỉ triển khai khi kiểm chứng cho thấy checklist/Rule không đủ.

**Vì sao chưa chốt mức cao hơn:** Chưa có bằng chứng checklist không đủ. Checklist có thể giảm việc bỏ quên, Rule xử lý điều kiện hình thức; Workflow chỉ đáng thử nếu vẫn còn thiếu sót nội dung hoặc mất nhiều thời gian đối chiếu. Vì vậy No AI/Rule là phương án so sánh trước, Workflow là hướng thử có điều kiện; chưa triển khai Agent.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| Prediction — AI dự đoán / tạo ra gì? | Danh sách tiêu chí nghi chưa đạt, kèm vị trí trong bài và lý do |
| Judgment — con người cân nhắc, quyết định gì? | Học viên quyết định mục nào thật sự thiếu và cần sửa thế nào |
| Action — hành động cuối cùng là gì, ai làm? | Học viên sửa bài, commit và nộp LMS |
| Outcome — đo kết quả bằng gì? | Thời gian soát bài, số tiêu chí bị sót, tỉ lệ mục AI nêu sai |
| Input — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | RUBRIC.md, SUBMISSION.md, file báo cáo; đều có sẵn trong repo |
| Feedback — lấy phản hồi ở đâu để cải thiện? | Mục AI nêu sai do học viên đánh dấu; điểm và nhận xét của coach sau khi chấm |

### 6.4. Hai câu hỏi của Google PAIR

1. **Augment hay automate?** Giả thuyết là augment, vì học viên chịu trách nhiệm về bài của mình. Chưa có phỏng vấn xác nhận mong muốn này; cần hỏi về cách người dùng đã kiểm tra gợi ý ở lần gần nhất. Boundary hiện là lựa chọn thiết kế theo trách nhiệm học viên, không phải kết quả phỏng vấn
2. **AI sai kiểu nào tệ hơn?** Bỏ sót tệ hơn báo nhầm: báo nhầm chỉ mất thêm vài phút kiểm tra, còn bỏ sót có thể làm mất điểm và tạo cảm giác an tâm sai. Vì vậy thiết kế yêu cầu AI nêu cả mục chưa chắc, và học viên vẫn tick checklist.

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| Actor | Học viên AI20k đang soát báo cáo Markdown theo rubric trên GitHub, còn gặp khó ở việc đối chiếu nội dung; chưa xác nhận quy mô nhóm người dùng này |
| Quy trình | Mở rubric → đối chiếu từng tiêu chí → kiểm tên file, ảnh → kiểm link → sửa → push và nộp LMS |
| Bottleneck | Đối chiếu từng tiêu chí với báo cáo: khoảng 15 phút trong quy trình tham chiếu của Huyền; có nguy cơ sót điều kiện phụ |
| Impact | ~40'/lab × 2–3 lab/tuần; sai tên file trừ 5 điểm; thiếu file bắt buộc thì phần nhóm bị 0 |
| Success Metric | (1) Tổng thời gian từ ~40' xuống ≤20', ghi giờ trong 2 lab; (2) số tiêu chí bị sót về 0, đối chiếu sau khi có điểm; (3) dưới 30% số mục AI nêu là báo nhầm, do học viên đánh dấu |
| Boundary | AI không viết hoặc sửa nội dung bài, không chấm điểm thay coach, không tự commit hay nộp, không dùng để viết reflection; không xác nhận "đạt" nếu không chỉ ra vị trí trong bài |
| AI intervention point | Sau khi Rule đã kiểm hình thức, trước khi học viên kiểm và sửa nội dung |
| Mức chọn | Workflow (có Rule ở bước 1) |
| Rủi ro & người kiểm tra | AI bỏ sót, báo nhầm hoặc nêu vị trí sai → học viên kiểm từng mục và tick checklist trước khi nộp |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Thời gian và số tiêu chí bị sót | Thêm tỉ lệ báo nhầm | Nhanh hơn nhưng báo sai nhiều thì học viên mất thêm thời gian kiểm |
| Boundary | Không viết bài, không chấm, không nộp | Thêm không dùng để viết reflection, phải chỉ ra vị trí trong bài | RULES cấm AI viết thay reflection; có vị trí thì học viên mới kiểm tra được |
| Actor | Học viên AI20k nộp qua GitHub | Người soát báo cáo Markdown còn khó ở bước dò nội dung | Thu hẹp từ đối chiếu các quy trình cá nhân; chờ phỏng vấn kiểm tra phạm vi |

**Cách đo chất lượng:** Trên bản báo cáo cố định trước khi sửa, học viên lập danh sách thiếu sót tham chiếu theo rubric và nhờ một người khác đối chiếu; nhận xét coach dùng để cập nhật sau chấm. Báo nhầm = số mục công cụ nêu nhưng đối chiếu không xác nhận / tổng mục công cụ nêu. Không có mục nào được nêu thì tỉ lệ báo nhầm là “không áp dụng”, vẫn phải kiểm bỏ sót. Bỏ sót = số thiếu sót tham chiếu không được công cụ nêu. Chưa có kết quả thử hoặc baseline chất lượng.

**Tiêu chí đánh giá đầu ra của AI:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---|---|---|---|
| 1 | Không bỏ sót | Mọi tiêu chí thật sự thiếu đều được nêu | Có tiêu chí thiếu mà AI không nêu |
| 2 | Có vị trí kiểm được | Mỗi mục nêu rõ phần nào của bài và tiêu chí nào của rubric | Nhận xét chung chung, không chỉ ra chỗ |
| 3 | Không bịa yêu cầu | Mọi mục truy được về RUBRIC hoặc SUBMISSION | Nêu yêu cầu không có trong tài liệu |
| 4 | Không làm thay | Chỉ nêu thiếu gì, không viết nội dung thay | Viết sẵn đoạn văn để dán vào bài |

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro | Lý do / bằng chứng |
|---|---|---|---|
| Value | Người dùng có thật sự cần và sẽ dùng không? | Cao | Mới có số liệu của 4 thành viên trong nhóm; chưa kiểm chứng với người ngoài và chưa so với checklist |
| Usability | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | Có thể đọc danh sách kèm vị trí nhưng chưa quan sát người dùng phân biệt góp ý đúng/sai; cần thử tác vụ kiểm lại |
| Feasibility | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Trung bình | Input có sẵn; chưa đo độ chính xác với rubric và Markdown tiếng Việt. Công cụ tương tự không chứng minh giải pháp đạt tiêu chí |
| Viability | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | RULES cho dùng AI ở một số phần, nhưng cần hỏi coach về việc dùng AI để rà bài trước khi nộp; học viên tự vận hành |

### 8.2. Kết luận

**Quyết định:** Not Yet — chưa chuyển sang triển khai Workflow khi chưa kiểm chứng Value và chất lượng đối chiếu.

**Lý do:** Value đang ở mức Cao vì chưa có bằng chứng từ người ngoài nhóm, nhưng kiểm chứng được nhanh.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Phỏng vấn học viên nhóm khác về lần nộp lab gần nhất (giả định #1, #2).
2. Cho 2–3 học viên dùng checklist ở một lab rồi đếm số tiêu chí còn sót (giả định #3).
3. Thử AI trên 1 báo cáo đã có điểm và chấm theo 4 tiêu chí ở mục 7 (giả định #5).
4. Hỏi coach về quy định dùng AI để rà bài (giả định #6).

**Điều kiện xem xét Go:** Có dữ liệu từ 2–3 người ngoài nhóm; so sánh cho thấy checklist/Rule chưa đạt mục tiêu; thử trên báo cáo có bộ thiếu sót tham chiếu đạt tiêu chí mục 7; phạm vi dùng công cụ phù hợp quy định. Khi đó đánh giá lại cả bốn rủi ro, không còn rủi ro Cao mới cân nhắc Go.

**Nếu chuyển sang Go — pilot nhỏ nhất:** Trong 2 lab, thử trên 2–3 học viên. Ghi rõ người thực hiện, thời gian kiểm tra/sửa/nộp, số cảnh báo đúng/sai và lỗi còn sót. So sánh checklist/Rule với quy trình có công cụ hỗ trợ trên các báo cáo có độ khó tương đương; tránh chạy lần hai trên cùng bài đã sửa rồi coi thời gian giảm là hiệu quả công cụ. Dùng công cụ sẵn có; chưa xây sản phẩm. Quy trình dán prompt thủ công chỉ mô phỏng thiết kế Workflow, chưa phải Workflow điều phối bằng code.

**Target nhóm:** ≤20 phút cho toàn bộ quy trình, thay vì ≤15 phút trong card cá nhân: 1 phút Rule + 2 phút đối chiếu + 5 phút kiểm lại + 10 phút sửa + 2 phút nộp = 20 phút. Bước sửa vẫn được giữ đủ thời gian. Đây là target thiết kế, sẽ đo lại trong pilot.

**Ngưỡng dừng:**

- Nếu sau 2 lab trên 50% số mục AI nêu là báo nhầm thì quay về checklist.
- Nếu có 1 tiêu chí thiếu mà AI không nêu và làm mất điểm thì dừng, xem lại bước kiểm của học viên.
- Nếu checklist/Rule đạt ≤20 phút và không sót tiêu chí trong cả 2 lab thử thì dừng hướng Workflow, chọn mức đơn giản hơn.
- Nếu không được phép xử lý dữ liệu hoặc rà soát phần tương ứng bằng AI thì không chạy bước đó; dùng checklist và người kiểm.
- Tỉ lệ báo nhầm 30–50% chưa đạt target <30%: chưa Go, sửa cách đối chiếu và đánh giá lại; >50% sau 2 lab thì dừng.

## 9. Hạn chế và hướng tiếp theo

- Chưa có kiểm chứng ngoài nhóm; phần CP4 hiện là tổng hợp nội bộ và kế hoạch, chưa đáp ứng đủ bằng chứng phỏng vấn/survey của rubric.
- Các thời gian cá nhân khác phạm vi; không lấy trung bình 40, 70, 50 và 30 phút. Phương cần thống nhất số phút và số lỗi trong CP1–CP2 trước khi dùng làm dữ liệu định lượng.
- Câu hỏi phản biện CP3 mới ghi theo người nêu, chưa ghi đầy đủ ai hỏi ai trong buổi pitch.
- Cluster C có thể giải bằng bảng phân công và biên bản ngắn; việc không cần AI không làm candidate kém giá trị, chỉ không phải trọng tâm phân tích lần này.

## 10. Tài liệu tham khảo

- [Worksheet](../../docs/01-worksheet.md), [bài mẫu](../../docs/02-deliverable-example.md), [framework](../../docs/03-international-frameworks.md).
- [RULES](../../RULES.md), [RUBRIC](../../RUBRIC.md), [SUBMISSION](../../SUBMISSION.md).
- [Huyền](../individual/2A202604077_DuongThiHuyen.md), [Nga](../individual/2A202604079_HoangThiThanhNga.md), [Phương](../individual/2A202604080_BuiThuPhuong.md), [Tâm](../individual/2A202604097_PhamMinhTam.md): nguồn tổng hợp candidate và ghi nhận nội bộ.
- [Grammarly AI Grader](https://www.grammarly.com/ai-agents/ai-grader): đối chiếu bài viết với rubric, dự đoán điểm; phạm vi trang mô tả là bài viết tiếng Anh.
- [lychee-action](https://github.com/lycheeverse/lychee-action): kiểm link trong Markdown, HTML và text.
- [GitHub Docs — Use autograding](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding): pattern chạy kiểm tra bằng GitHub Actions; trang có thông báo ngừng GitHub Classroom ngày 28/08/2026.

**Ghi nhận hỗ trợ:** Codex và Claude hỗ trợ đối chiếu nguồn cá nhân, rà soát lập luận và trình bày; quyết định cuối do nhóm thực hiện.
