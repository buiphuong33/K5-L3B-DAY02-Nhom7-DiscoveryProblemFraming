# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Nhom7
- Candidate problem nhóm chọn (1 câu): Học viên AI20k mất nhiều thời gian và dễ sót yêu cầu khi đối chiếu bài lab với rubric trước khi nộp.
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Bùi Thu Phương | 2A202604080 | Nhóm trưởng (fork repo, mời thành viên); viết Problem Statement v0 | buiphuong33 |
| 2 | Hoàng Thị Thanh Nga | 2A202604079 | Phụ trách kiểm chứng (Assumption Map, interview snapshot); viết Problem Statement v0; câu hỏi PAIR và tiêu chí đánh giá | Ngahoang2005 |
| 3 | Dương Thị Huyền | 2A202604077 | Vẽ quy trình trước/sau | duongthuyen |
| 4 | Phạm Minh Tâm | 2A202604097 | Phụ trách kiểm chứng (phỏng vấn cùng Nga) | minhtama11qc-hash |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Cả nhóm (mỗi người pitch top 3) | — | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Nga | Tâm | Assumption map, snapshot hoặc survey |
| CP4 — Research | Phương | Cả nhóm | Bảng research có link |
| CP5 — Quy trình trước/sau | Huyền | — | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Nga | Phương | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nga | Cả nhóm | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm | — | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### DuongThiHuyen-2A202604077

**Phần việc phụ trách:**

- CP5 — vẽ quy trình hiện tại và quy trình tương lai, bảng before/after.
- Làm rõ actor, input/output, thời gian, boundary và phương án quay về; cung cấp Problem Cards và số liệu cá nhân để nhóm đối chiếu baseline.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch Problem Card #1 "Kiểm tra bài lab trước khi nộp". Card này là nguồn của candidate A mà nhóm chọn.
- Cung cấp quy trình tham chiếu 6 bước, ~40 phút, có bottleneck ở bước đối chiếu tiêu chí (~15 phút). Nhóm dùng quy trình này cho mục 4.1 và cho baseline của Problem Statement.
- Vẽ quy trình tương lai 5 bước (Rule → AI → con người), có boundary, phương án quay về và bảng before/after.
- Chuyển sơ đồ quy trình hiện tại và tương lai sang Mermaid, bổ sung bảng actor/input/output/thời gian cho cả hai quy trình.
- Thể hiện target nhóm ~20 phút theo tổng thời gian các bước, so với mục tiêu ≤15 phút trong Card #1; giữ thời gian học viên kiểm lại và 10 phút sửa bài. Các mốc tương lai là kỳ vọng cần kiểm chứng.
- Làm rõ ranh giới Rule kiểm hình thức, AI đối chiếu nội dung, học viên kiểm lại/sửa/nộp trong sơ đồ; giữ checklist làm phương án quay về.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- [Báo cáo nhóm](report/team/group_report.md): mục 2.1 (candidate #1–#3), mục 3.2 (số liệu cá nhân), mục 4.1–4.3 (quy trình và before/after); mục 5, 7 và 8.2 sử dụng quy trình tham chiếu và target nhóm.
- Ảnh quy trình: [cp5-workflow-current.png](report/assets/cp5-workflow-current.png), [cp5-workflow-future.png](report/assets/cp5-workflow-future.png).
- [Báo cáo cá nhân](report/individual/2A202604077_DuongThiHuyen.md): mục 3 (Problem Card #1 và phản biện CP2), mục 4 (đóng góp), mục 6 (bài học).
- Commit `1ff1cb8` (báo cáo cá nhân), `9c250d3` (cập nhật group_report.md và TEAM.md).

**Điều mình học được từ phần nhóm:**

- Cùng gặp một pain chưa có nghĩa các số liệu so sánh được: mốc ~40 phút của mình chỉ là quy trình tham chiếu, cần thống nhất phạm vi đo trước khi suy rộng.
- Vẽ quy trình giúp kiểm tra target: tổng các bước tương lai là ~20 phút, vẫn dành thời gian kiểm lại và sửa bài; giảm số bước chưa chứng minh hiệu quả thực tế.
- Chọn mức can thiệp theo từng bước: thử checklist/Rule trước, chỉ dùng Workflow khi có bằng chứng cần AI đối chiếu nội dung.
- Not Yet phù hợp khi còn thiếu kiểm chứng ngoài nhóm; cần ghi rõ giả định, cách thử và ngưỡng dừng thay vì coi kỳ vọng là kết quả.

### BuiThuPhuong-2A202604080

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-

### HoangThiThanhNga-2A202604079

**Phần việc phụ trách:**

- CP4 — người chính phần kiểm chứng: Assumption Map, kế hoạch phỏng vấn và Interview Snapshot (Tâm hỗ trợ).
- CP5 — người chính Problem Statement v0 (Phương hỗ trợ).
- CP6 — người chính mức can thiệp AI và Problem Statement v1: hai câu hỏi Google PAIR và tiêu chí đánh giá đầu ra của AI.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Scan 10 problem theo 4 lăng kính (CP1) và viết 3 Problem Card có quy trình nháp, bấm giờ từng bước (CP2). Pitch 3 candidate #4–#6 ở CP3; candidate #4 (soát bài trước khi nộp, bottleneck 25 phút) cùng card của Huyền và Phương được gom vào cluster A mà nhóm chọn.
- Đặt câu hỏi "checklist tự lập từ RUBRIC đã đủ chưa?". Nhóm đưa câu này thành giả định #3 trong Assumption Map và giữ No AI (checklist) làm phương án thử trước, đồng thời là phương án quay về.
- Lập Assumption Map 6 giả định (Value / Usability / Feasibility / Viability) và bộ câu hỏi phỏng vấn về hành vi đã xảy ra, có câu tìm tín hiệu phản bác. Phỏng vấn người ngoài nhóm chưa thực hiện, nên snapshot chưa có số liệu.
- Problem Statement v0 → v1: thêm tỉ lệ báo nhầm vào metric, thêm boundary "phải chỉ ra vị trí trong bài, không viết reflection", thu hẹp actor về người soát báo cáo Markdown.
- Viết hai câu trả lời PAIR (augment; bỏ sót tệ hơn báo nhầm) và 4 tiêu chí đánh giá đầu ra: không bỏ sót, có vị trí kiểm được, không bịa yêu cầu, không làm thay.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 2.1 (candidate #4–#6), mục 3.1–3.2 (Assumption Map, kế hoạch phỏng vấn), mục 5 (Problem Statement v0), mục 6.4 (PAIR), mục 7 (v1 và tiêu chí đánh giá).
- `report/individual/2A202604079_HoangThiThanhNga.md` mục 2–4.
- Commit `0bbeba5`, `cf4ca47`, `138a9a6`, `783f138` (báo cáo cá nhân).

**Điều mình học được từ phần nhóm:**

- Số phút của từng người không cộng hay so trực tiếp được: card của mình là 70 phút (tính cả đọc đề), của Huyền là 40 phút (chỉ soát bài). Phải thống nhất phạm vi đo trước khi lấy làm baseline.
- Câu hỏi "checklist đã đủ chưa?" giúp nhóm không nhảy thẳng lên Workflow; phương án đơn giản nhất phải được thử và có ngưỡng dừng rõ ràng.

### PhamMinhTam-2A202604097

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-
