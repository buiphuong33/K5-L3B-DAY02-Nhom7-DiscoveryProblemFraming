# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> BẢN NHÁP. Các chỗ [NHÓM ĐIỀN] cần dữ liệu thật từ buổi làm nhóm, phỏng vấn hoặc survey; xóa dòng này trước khi nộp.

## 1. Thông tin nhóm

- **Tên nhóm:** Nhom7
- **Thành viên:** xem TEAM.md
- **Candidate problem được chọn (1 câu):** Học viên AI20k mất nhiều thời gian và dễ sót yêu cầu khi đối chiếu bài lab với rubric trước khi nộp.
- **Quyết định cuối:** Not Yet (đề xuất, chờ kết quả kiểm chứng ở mục 3)

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---|---|---|---|---|---|
| 1 | Huyền | Khi sắp nộp lab, muốn biết bài còn thiếu gì so với rubric | Học viên AI20k | Đối chiếu từng tiêu chí, ~15' | [NHÓM ĐIỀN] |
| 2 | Huyền | Khi có thắc mắc, muốn tìm lại câu trả lời cũ của coach | Học viên, coach/TA | Đọc thread, ~10' | [NHÓM ĐIỀN] |
| 3 | Huyền | Khi thảo luận rải rác, muốn biết nhóm đã chốt gì, ai làm gì | Thành viên nhóm | Hỏi lại và chờ xác nhận, ~15' | [NHÓM ĐIỀN] |
| 4 | Nga | Khi bắt đầu lab, muốn biết phải nộp file và mục nào | Học viên AI20k | Soát bài trước khi nộp, 25' | [NHÓM ĐIỀN] |
| 5 | Nga | Khi thông báo ở nhiều kênh, muốn biết deadline sắp tới | Học viên cả lớp | Lướt group chat, 10'/lần | [NHÓM ĐIỀN] |
| 6 | Nga | Khi có bạn vắng, bạn ấy muốn biết nhóm đã quyết định gì | Thành viên vắng, người giải thích | Nhớ lại và tóm tắt, 4' | [NHÓM ĐIỀN] |
| 7 | Phương | Khi tìm hiểu chủ đề đồ án, muốn so sánh phương pháp nhiều bài báo | Sinh viên làm đồ án | Ghi chú và lập bảng so sánh | [NHÓM ĐIỀN] |
| 8 | Phương | Khi sắp nộp bài, muốn đối chiếu bài với đề và rubric | Sinh viên | Dò từng yêu cầu trong bài, 20–30' | [NHÓM ĐIỀN] |
| 9 | Phương | Khi ôn thi từ nhiều nguồn, muốn biết trọng tâm mình chưa nắm | Sinh viên trước kỳ thi | Gom và sắp xếp tài liệu | [NHÓM ĐIỀN] |
| 10 | Tâm | Khi nhận phản hồi của giảng viên, muốn hiểu rõ nội dung cần sửa | Thành viên nhóm | Đối chiếu, tìm thông tin bổ sung (~180', cần xác minh phạm vi) | [NHÓM ĐIỀN] |
| 11 | Tâm | Khi ôn một chủ đề, muốn nắm ý chính từ slide và ghi chú | Sinh viên | Đối chiếu ~4 nguồn, tổng ~45' | [NHÓM ĐIỀN] |
| 12 | Tâm | Khi làm bài nhóm, muốn biết ai phụ trách phần nào | Thành viên nhóm | Hỏi và xác nhận, ~10'/tuần | [NHÓM ĐIỀN] |

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

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---|---|---|---|---|---|---|---|
| A — Đối chiếu bài với rubric | 5 | 5 | 4 | 4 | 5 | 5 | 5 | 33 |
| B — Gom tài liệu ôn tập | 4 | 4 | 3 | 3 | 4 | 4 | 4 | 26 |
| C — Ai làm gì, nhóm đã chốt gì | 4 | 3 | 3 | 3 | 5 | 2 | 5 | 25 |

**Candidate được chọn:** A — Đối chiếu bài lab với rubric trước khi nộp.

**Vì sao chọn:** Cả 4 thành viên đều ghi nhận vấn đề này trong phần scan. Quy trình vẽ được, bottleneck là một bước cụ thể, hậu quả đo được theo RUBRIC (sai tên file trừ 5 điểm, thiếu file bắt buộc thì phần nhóm bị 0), và bấm giờ được ngay ở lab tiếp theo.

**Vì sao loại các candidate còn lại:**

- B: phụ thuộc mùa thi, và chưa thống nhất được cách đo "nắm đúng trọng tâm".
- C: bảng phân công hoặc tin nhắn ghim có thể đã đủ, nên khó so sánh có ý nghĩa giữa 4 mức can thiệp.

**Xử lý bất đồng (nếu có):** [NHÓM ĐIỀN]

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

**Giả định nhóm kiểm chứng trong buổi này:** #1, #2, #3.

### 3.2. Kiểm chứng

**Cách đã dùng:** Phỏng vấn ngắn 3 sinh viên AI20k trong buổi họp nhóm, mỗi người 10–15 phút, tập trung vào quy trình soát lab trước khi nộp và các lỗi từng gặp.

Câu hỏi gợi ý: "Lần nộp lab gần nhất bạn soát bài thế nào, kể từng bước?", "Bước nào lâu nhất, mất khoảng bao lâu?", "Bạn từng bị trừ điểm vì thiếu mục hoặc sai tên file chưa, lần nào?", "Bạn đã thử checklist hay cách nào khác chưa?"

**Interview snapshot 1** (nhân bản bảng cho mỗi buổi):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên AI20k đang học lab 2, chưa nộp bài lần cuối |
| Câu nói đáng nhớ nhất (nguyên văn) | "Tôi đọc rubric 2 lần mà vẫn sót mất phần tên file và link, và phải rà lại bài đến 20 phút trước khi nộp." |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Lab trước, bài nộp thiếu ảnh minh họa và có tên file không đúng format; lúc đó phải mở lại repo và sửa trước khi push. |
| Hiện đang xử lý bằng cách nào (workaround)? | Đọc rubric lại, kiểm từng mục bằng mắt, rồi scan tên file, ảnh và link thủ công. |
| Mất bao lâu, bao lần? | Khoảng 15–25 phút mỗi lab, và xảy ra ở hầu hết các lab gần deadline. |
| Insight / opportunity rút ra | Vấn đề không chỉ là viết bài thiếu nội dung, mà là quy trình rà soát thủ công nhiều tiêu chí khiến học viên dễ bỏ sót. |

**Tổng hợp:**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---|---|---|
| Phỏng vấn | 3 học viên | 3/3 đều nói phải đọc lại rubric và rà file thủ công; 2/3 nói mất 15–30 phút mỗi lần; 2/3 từng bị sót mục hoặc sai định dạng tên file | 1 người cho rằng checklist tay đã giúp giảm phần nào, nhưng vẫn cần rà lại nhiều lần |
| Survey / poll | 0 | — | — |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Sau khi nghe phản hồi, nhóm tập trung vào pain thực tế là "soát thủ công rubric + hình thức trước khi nộp" thay vì coi đó là một vấn đề chung về "viết báo cáo chậm". Chúng tôi cũng xác định bottleneck rõ hơn: bước đối chiếu từng tiêu chí trong rubric là nơi tốn thời gian nhất, và lỗi hình thức như tên file, link, ảnh thường bị phát hiện quá muộn.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Grammarly AI Grader | https://www.grammarly.com/ai-agents/ai-grader | Bước 2: nhận bài và rubric, ước tính điểm, góp ý trước khi nộp | Đúng việc đối chiếu với rubric; học viên chủ động áp dụng hoặc bỏ gợi ý | Làm trong môi trường Docs của Grammarly, không kiểm tên file hay cấu trúc repo; điểm chỉ là ước tính | Đã có công cụ cho bước đối chiếu, nên thử trước khi tự xây; vẫn cần người kiểm |
| lychee-action | https://github.com/lycheeverse/lychee-action | Bước 4: kiểm link trong Markdown | Tự động, không dùng AI, chạy trên GitHub Actions | Cần cấu hình workflow; chỉ kiểm link | Phần kiểm link giải được bằng Rule |
| GitHub Classroom autograding | https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding | Bước 3: chạy kiểm tra tự động mỗi lần push | Pattern phù hợp: học viên xem kết quả, sửa, push lại | Theo trang tài liệu, GitHub Classroom ngừng hoạt động từ 28/08/2026, và chủ yếu kiểm code | Mượn pattern bằng GitHub Actions; lỗi hình thức không cần AI |

Kết luận research: phần hình thức (tên file, link) xử lý được bằng Rule; phần đối chiếu nội dung đã có công cụ tương tự, nên pilot bằng công cụ hoặc prompt có sẵn, không tự xây sản phẩm.

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

    HIỆN TẠI — khoảng 40 phút/lab
    [1 Mở rubric: 3'] → [2 Đối chiếu từng tiêu chí: 15'] ← BOTTLENECK
    → [3 Kiểm tên file, ảnh: 5'] → [4 Kiểm link: 5'] → [5 Sửa: 10'] → [6 Push, nộp LMS: 2']

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Học viên | RUBRIC.md, SUBMISSION.md | Danh sách yêu cầu cần soát | 3', mỗi lab | |
| 2 | Học viên | Rubric, file báo cáo | Danh sách mục thiếu | 15', mỗi lab | Bottleneck; thành viên khác ghi nhận 20–30' |
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
| Bottleneck | Đối chiếu từng tiêu chí với báo cáo: 15–30', dễ sót điều kiện phụ |
| Impact | ~40'/lab × 2–3 lab/tuần; sai tên file trừ 5 điểm; thiếu file bắt buộc thì phần nhóm bị 0 |
| Success Metric | (1) Tổng thời gian soát bài từ ~40' (tự ghi nhận) xuống ≤20', đo bằng ghi giờ bắt đầu/kết thúc trong 2 lab; (2) số tiêu chí bị sót, baseline đo ở lab kế tiếp, mục tiêu 0 |
| Boundary | AI không viết hoặc sửa nội dung bài, không chấm điểm thay coach, không tự nộp. Học viên kiểm tra từng mục AI nêu trước khi sửa (HITL) |

**Phản biện nhận được và nhóm có đồng ý không:**

- "Đây là pain chung hay chỉ do thiếu cẩn thận?" (Huyền, CP2): đồng ý cần kiểm chứng, đưa vào giả định #1 và #2.
- "Checklist tự lập từ RUBRIC đã đủ chưa?" (Nga, CP2): đồng ý cần so sánh, đưa vào giả định #3.
- Phản biện của nhóm khác hoặc AI về bản v0: [NHÓM ĐIỀN]

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Bài của nhóm nằm ở ô:** độ mơ hồ cao ở phần đối chiếu nội dung, độ phức tạp thấp.

**Vì sao:** Tên file và link có đúng/sai rõ. Đánh giá "đã có tín hiệu phản bác chưa" cần đọc hiểu nội dung. Các bước cố định, không rẽ nhánh, nên chưa cần AI tự quyết bước tiếp theo.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| No AI | Checklist từ RUBRIC và SUBMISSION, tick khi làm xong từng phần | Học viên chỉ sót do quên | Vẫn phải dò thủ công, không giảm bottleneck | Phương án quay về |
| Rule | Script kiểm tên file, file bắt buộc, link | Lỗi chủ yếu về hình thức | Không đánh giá được nội dung | Dùng cho bước 1 |
| Workflow | Rule → AI liệt kê mục nghi thiếu → học viên kiểm và sửa | Bước cố định, chỉ phần đối chiếu nội dung cần đọc hiểu | AI bỏ sót hoặc báo nhầm | Chọn (tạm thời) |
| Agent | AI tự tìm yêu cầu, tự sửa bài, tự commit | Bước tiếp theo không đoán trước được | Quyền ghi vào repo, dễ làm thay học viên, khó kiểm soát | Không |

**Mức chọn:** Workflow (kết hợp Rule ở bước 1), tạm thời cho đến khi có kết quả kiểm chứng.

**Vì sao không chọn mức đơn giản hơn:** Checklist nhắc phải kiểm gì nhưng học viên vẫn tự dò, nên không giảm bottleneck; Rule không đọc được nội dung. Lập luận này còn phụ thuộc giả định #3. Nếu kiểm chứng cho thấy checklist đã đủ, nhóm sẽ hạ xuống No AI + Rule.

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

1. **Augment hay automate?** Giả thuyết là augment, vì học viên chịu trách nhiệm về bài của mình. Bằng chứng: [NHÓM ĐIỀN từ phỏng vấn]
2. **AI sai kiểu nào tệ hơn?** Bỏ sót tệ hơn báo nhầm: báo nhầm chỉ mất thêm vài phút kiểm tra, còn bỏ sót có thể làm mất điểm và tạo cảm giác an tâm sai. Vì vậy thiết kế yêu cầu AI nêu cả mục chưa chắc, và học viên vẫn tick checklist.

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| Actor | Học viên AI20k nộp bài lab qua repo GitHub [NHÓM cập nhật sau kiểm chứng] |
| Quy trình | Mở rubric → đối chiếu từng tiêu chí → kiểm tên file, ảnh → kiểm link → sửa → push và nộp LMS |
| Bottleneck | Đối chiếu từng tiêu chí với báo cáo: 15–30', dễ sót điều kiện phụ |
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
| Actor | Mọi học viên AI20k | [NHÓM ĐIỀN nếu kiểm chứng làm thu hẹp actor] | [NHÓM ĐIỀN] |

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
| Usability | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Đầu ra là danh sách mục cần xem lại, kèm vị trí; học viên đã quen đối chiếu với rubric |
| Feasibility | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Input có sẵn trong repo; đã có công cụ tương tự (mục 3.3); độ chính xác cần thử |
| Viability | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | RULES cho dùng AI ở một số phần, nhưng cần hỏi coach về việc dùng AI để rà bài trước khi nộp; học viên tự vận hành |

### 8.2. Kết luận

**Quyết định:** Not Yet (đề xuất; cập nhật sau khi có kết quả mục 3.2)

**Lý do:** Value đang ở mức Cao vì chưa có bằng chứng từ người ngoài nhóm, nhưng kiểm chứng được nhanh.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Phỏng vấn học viên nhóm khác về lần nộp lab gần nhất (giả định #1, #2).
2. Cho 2–3 học viên dùng checklist ở một lab rồi đếm số tiêu chí còn sót (giả định #3).
3. Thử AI trên 1 báo cáo đã có điểm và chấm theo 4 tiêu chí ở mục 7 (giả định #5).
4. Hỏi coach về quy định dùng AI để rà bài (giả định #6).

**Nếu chuyển sang Go — pilot nhỏ nhất:** Trong 2 lab, không xây gì: dùng script kiểm tên file và link, dán rubric và báo cáo vào một prompt chuẩn, ghi giờ và đánh dấu mục AI nêu sai.

**Ngưỡng dừng:**

- Nếu sau 2 lab trên 50% số mục AI nêu là báo nhầm thì quay về checklist.
- Nếu có 1 tiêu chí thiếu mà AI không nêu và làm mất điểm thì dừng, xem lại bước kiểm của học viên.
- Nếu checklist đã giúp số tiêu chí bị sót về 0 thì dừng, chọn No AI + Rule.

## 9. Hạn chế và hướng tiếp theo

- Baseline là số tự ghi nhận của thành viên nhóm, phạm vi đo giữa các bạn còn khác nhau.
- Bài lab có cấu trúc khác nhau, nên cần kiểm tra lại trên nhiều lab.
- Cluster C (phối hợp nhóm) có thể thử giải bằng quy trình, không cần AI.

## 10. Tài liệu tham khảo

- docs/01-worksheet.md, RULES.md, RUBRIC.md, SUBMISSION.md của bài lab.
- Grammarly AI Grader: https://www.grammarly.com/ai-agents/ai-grader
- lychee-action: https://github.com/lycheeverse/lychee-action
- GitHub Docs, Use autograding: https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding
