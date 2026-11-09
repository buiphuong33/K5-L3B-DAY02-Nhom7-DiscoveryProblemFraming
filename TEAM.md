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
| 4 | Phạm Minh Tâm | 2A202604097 | Phụ trách kiểm chứng (phỏng vấn cùng Nga); xây dựng Problem Card cho feedback và ôn tập | minhtama11qc-hash |

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

- Nhóm trưởng, phối hợp repo và ghi nhận tiến độ chung.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Fork repo nhóm và chuẩn hóa tên repo, tổ chức file báo cáo cá nhân và file گروه.
- Đóng góp phần ghi nhận mức độ đúng sai trong nhóm và hỗ trợ đồng bộ nội dung báo cáo nhóm.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` và `TEAM.md` trong repo nhóm.
- Báo cáo cá nhân `report/individual/2A202604080_BuiThuPhuong.md`.

**Điều mình học được từ phần nhóm:**

- Việc chọn candidate tốt cần căn cứ vào dữ liệu lặp lại và impact rõ hơn là độ “hay” của ý tưởng.

### HoangThiThanhNga-2A202604079

**Phần việc phụ trách:**

- CP4 — người chính phần kiểm chứng: Assumption Map, kế hoạch phỏng vấn, snapshot và điều chỉnh phạm vi sau rà soát nội bộ.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Thiết kế Assumption Map và gợi ý các câu hỏi kiểm chứng phù hợp với vấn đề soát bài trước khi nộp.
- Hỗ trợ rà soát dữ liệu nội bộ để xác định phần nào đã có bằng chứng và phần nào cần phỏng vấn người ngoài nhóm.
- Làm rõ kế hoạch phỏng vấn và tiêu chí xác nhận pain, hậu quả và phương án đơn giản.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 3.1–3.2.
- `report/individual/2A202604079_HoangThiThanhNga.md` phần CP2 và CP4.

**Điều mình học được từ phần nhóm:**

- Một giả định chưa chắc đúng cần được kiểm chứng bằng dữ liệu thực, không chỉ bằng trải nghiệm cá nhân của nhóm.

### PhamMinhTam-2A202604097

**Phần việc phụ trách:**

- CP4 — kiểm chứng và phản biện: tham gia phỏng vấn cùng Nga, góp ý cho Assumption Map và các candidate phản biện.
- CP2 — xây dựng Problem Card #1 và #2 cho các vấn đề về phản hồi giảng viên và ôn tập từ nhiều nguồn.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Ghi nhận 5 vấn đề scan ban đầu và chọn top 3 gồm: đối chiếu phản hồi giảng viên, ôn tập từ slide và ghi chú, xác định người phụ trách phần việc nhóm.
- Làm Problem Card #1 "Đối chiếu phản hồi của giảng viên" và Problem Card #2 "Ôn tập từ slide và ghi chú" trong báo cáo cá nhân.
- Góp phần xác định bottleneck thực tế: mất khoảng 180 phút đối chiếu phản hồi, và khoảng 45 phút để tổng hợp 4 nguồn tài liệu trước kiểm tra.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 2.1 (candidate #10, #11, #12) và mục 3.2.
- `report/individual/2A202604097_PhamMinhTam.md` mục 2 (scan problem), mục 3 (top 3 card + quy trình nháp).

**Điều mình học được từ phần nhóm:**

- Vấn đề cần tập trung là những việc lặp lại và tốn thời gian, không phải chỉ là câu hỏi chung. Mỗi candidate cần có actor, quy trình rõ và bằng chứng thời gian cụ thể trước khi chọn giải pháp.

### HoangThiThanhNga-2A202604079

**Phần việc phụ trách:**

- CP4 — người chính phần kiểm chứng: Assumption Map, kế hoạch phỏng vấn, snapshot và điều chỉnh phạm vi sau rà soát nội bộ.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Thiết kế Assumption Map và gợi ý các câu hỏi kiểm chứng phù hợp với vấn đề soát bài trước khi nộp.
- Hỗ trợ rà soát dữ liệu nội bộ để xác định phần nào đã có bằng chứng và phần nào cần phỏng vấn người ngoài nhóm.
- Làm rõ kế hoạch phỏng vấn và tiêu chí xác nhận pain, hậu quả và phương án đơn giản.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 3.1–3.2.
- `report/individual/2A202604079_HoangThiThanhNga.md` phần CP2 và CP4.

**Điều mình học được từ phần nhóm:**

- Số phút của từng người không cộng hay so trực tiếp được: card của mình là 70 phút (tính cả đọc đề), của Huyền là 40 phút (chỉ soát bài). Phải thống nhất phạm vi đo trước khi lấy làm baseline.
- Câu hỏi "checklist đã đủ chưa?" giúp nhóm không nhảy thẳng lên Workflow; phương án đơn giản nhất phải được thử và có ngưỡng dừng rõ ràng.





