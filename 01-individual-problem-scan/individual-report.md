# 01 — Individual Problem Scan

## Thông tin cá nhân

| Trường | Nội dung |
|---|---|
| Họ và tên | Vũ Duy Điệp |
| Mã học viên | 2A202602703 |
| Vai trò / bối cảnh | Intern AI Engineer |

**Công việc hằng tuần:**
- Đi làm ~8 tiếng/ngày, phải tự sắp xếp lịch tự học ngoài giờ làm sao cho không chồng chéo.
- Tự lên lịch tập luyện và thực đơn dinh dưỡng hằng tuần, không có PT hỗ trợ.
- Đọc và lọc tin công nghệ/ngành hằng ngày để cập nhật kiến thức cho công việc.
- Tự mua sắm nhu yếu phẩm, đồ ăn cho sinh hoạt cá nhân.
- Tự ghi chép và quản lý chi tiêu cá nhân hằng tháng.

---

## Phase 1 — Bảng scan 5 vấn đề

Mỗi hàng là một problem độc lập; các số liệu là baseline cần kiểm chứng bằng log thực tế.

| # | Problem quan sát được | Actor | Điểm nghẽn | Dấu hiệu thật |
|:---:|---|---|---|---|
| 1 | Sắp xếp lịch làm và tự học để không chồng chéo | Người tự học ngoài giờ làm | Dò slot rảnh và cân nhắc ưu tiên chủ đề | 15–25 phút/tuần; lịch làm thay đổi liên tục |
| 2 | Lên lịch tập luyện và thực đơn hằng tuần | Người tự tập, không có PT | Ghép lịch tập với thực đơn phù hợp mục tiêu | Mất thời gian, dễ lặp món hoặc lệch lịch |
| 3 | Lọc tin công nghệ/ngành liên quan công việc | Người cần cập nhật ngành | Đọc tiêu đề, mở bài và đánh giá độ liên quan | 15–20 phút/ngày; phải mở bài mới biết có đáng đọc |
| 4 | Mua nhu yếu phẩm không theo lịch cố định | Người tự mua sắm cá nhân | Không có lịch mua cố định nên dễ hết đồ | 2–3 lần/tháng mua gấp; tốn thêm 20–30 phút mỗi lần |
| 5 | Tổng hợp chi tiêu cuối tháng | Người tự quản lý chi tiêu cá nhân | Không ghi chép ngay lúc chi nên khó tổng hợp | 30–40 phút/tháng; thường bỏ sót 3–5 khoản nhỏ |

**AI đã dùng ở Phase 1:** *(chưa sử dụng)*

### 1.1. Ba Candidate Problems

| Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|
| Sắp xếp khung giờ học đầu tuần (15–25 phút, dễ chồng chéo) | Bản thân — tự học ngoài giờ làm | Có nhiều mục tiêu học nhưng chưa có cách ưu tiên và ghép vào khung giờ cố định | **Rule** — template cố định có thể đủ, trừ khi lịch làm biến động mạnh |
| Lập lịch tập luyện + thực đơn dinh dưỡng hàng tuần | Bản thân — tự xây kế hoạch tập, không có PT | Phải ghép hai nguồn thông tin (lịch tập + dinh dưỡng); kế hoạch đổi theo tiến độ mỗi tuần | **Workflow** — cần phối hợp lịch tập, mục tiêu và thực đơn; dễ sai nếu thiếu dữ liệu |
| Lọc tin công nghệ liên quan mỗi ngày | Bản thân — intern AI engineer cần cập nhật tin ngành | Phải đọc tiêu đề và mở thử nhiều bài để đánh giá mức liên quan | **Workflow** — cần lọc/tóm tắt từ nhiều nguồn, người dùng vẫn quyết định đọc bài nào |

**Self-check Phase 1**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn Top 3

Tiêu chí giữ lại: actor cụ thể, workflow vẽ được 3–7 bước, bottleneck ở 1 bước, impact đo được.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|:---:|---|---|---|
| 1 | Sắp xếp lịch học đầu tuần | Xảy ra đều đặn mỗi tuần; actor rõ; đo được thời gian lập lịch và số lần chồng chéo | Chưa chắc template cố định đã đủ, hay lịch làm biến động cần gợi ý linh hoạt |
| 2 | Lập kế hoạch tập luyện & dinh dưỡng | Hai workflow liên quan cần phối hợp; impact thể hiện qua lịch tập lệch và thực đơn mất cân đối | Chưa có dữ liệu đủ dài để xác định mức độ lệch lịch và chất lượng dinh dưỡng |
| 3 | Lọc tin công nghệ liên quan | Xảy ra mỗi ngày, mất thời gian rõ; AI có thể hỗ trợ lọc và tóm tắt từ nhiều nguồn | Cần định nghĩa "liên quan" và cách đo chất lượng gợi ý |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Sắp xếp lịch học đầu tuần

| Trường | Nội dung |
|---|---|
| **Problem (1 câu)** | Mỗi đầu tuần, intern AI engineer mất 15–25 phút sắp xếp lịch học và dễ chọn các buổi bị chồng chéo. |
| **Actor** | Bản thân — intern AI engineer, tự học ngoài giờ làm |
| **Thời điểm / bối cảnh** | Đầu tuần, trước khi bắt đầu các buổi học ngoài giờ làm |
| **Bottleneck** | Bước 4 — ưu tiên chủ đề và ghép vào khung giờ cố định mà không chồng chéo |
| **Impact** | 15–25 phút/tuần để lập lịch; lịch chồng chéo tăng nguy cơ bỏ/dời buổi học |
| **Success metric** | Lập lịch dưới 10 phút, không buổi nào chồng chéo trong 4 tuần liên tiếp |
| **Non-AI alternative** | Template lịch học cố định theo tuần + checklist kiểm tra xung đột |
| **AI hypothesis** | AI đọc mục tiêu, lịch làm việc và thời lượng từng chủ đề để đề xuất lịch học không chồng chéo |
| **Quick gut** | ☐ No AI/process fix ☐ Rule ☑ **Workflow** ☐ Agent ☐ Chưa biết |

**Current workflow (3–7 bước):**
1. Liệt kê chủ đề và mục tiêu cần học trong tuần
2. Kiểm tra khung giờ rảnh sau giờ làm
3. Ước lượng thời lượng và độ khó từng chủ đề
4. Ghép chủ đề vào lịch học *(bottleneck)*
5. Kiểm tra các buổi có chồng chéo hoặc quá tải không

**Draft workflow:**

```
CURRENT STATE — 15–25 phút
[1 Liệt kê mục tiêu: 4'] → [2 Kiểm tra lịch rảnh: 5'] → [3 Ghép lịch thủ công: 10']* → [4 Kiểm tra: 5']
                                                          *bottleneck

FUTURE STATE — 8 phút
[1 Nạp mục tiêu + lịch: 1'] → [2 AI đề xuất lịch: 2'] → [3 Review/chỉnh: 5']†
                                                          †human boundary
```

**Fallback:** Nếu AI xếp lịch sai, dùng template tuần trước và tự điều chỉnh các buổi bị xung đột.

File đính kèm: `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Lập kế hoạch tập luyện và dinh dưỡng

| Trường | Nội dung |
|---|---|
| **Problem (1 câu)** | Mỗi tuần, người tập gym tự lập lịch tập và thực đơn nhưng khó cân đối nhóm cơ với bữa ăn hỗ trợ. |
| **Actor** | Bản thân — tự xây kế hoạch tập, không có PT |
| **Thời điểm / bối cảnh** | Cuối tuần hoặc đầu tuần, trước chu kỳ tập luyện và chuẩn bị bữa ăn |
| **Bottleneck** | Bước 4 — ghép lịch tập, mục tiêu và thực đơn phù hợp trong cùng một kế hoạch |
| **Impact** | 20–30 phút/tuần để lập kế hoạch; 2–3 lần/tuần lệch lịch tập hoặc lặp món |
| **Success metric** | Lập kế hoạch dưới 15 phút; hoàn thành ≥80% buổi tập, không lặp món quá 2 lần/tuần |
| **Non-AI alternative** | Template lịch tập theo nhóm cơ + thực đơn cố định theo tuần |
| **AI hypothesis** | AI kết hợp mục tiêu tập, lịch cá nhân và thực đơn để đề xuất kế hoạch tuần cân đối hơn |
| **Quick gut** | ☐ No AI/process fix ☐ Rule ☑ **Workflow** ☐ Agent ☐ Chưa biết |

**Current workflow (3–7 bước):**
1. Xác định mục tiêu tập luyện trong tuần
2. Chọn nhóm cơ và bài tập cho từng buổi
3. Chọn thực đơn và thực phẩm cần mua
4. Đối chiếu lịch tập với dinh dưỡng và thời gian chuẩn bị *(bottleneck)*
5. Điều chỉnh kế hoạch khi lịch làm việc thay đổi

**Draft workflow:**

```
CURRENT STATE — 20–30 phút
[1 Chọn bài tập: 8'] → [2 Chọn thực đơn: 8'] → [3 Ghép hai kế hoạch: 10']*
                                                 *bottleneck

FUTURE STATE — 12 phút
[1 Nạp mục tiêu + lịch: 2'] → [2 AI đề xuất kế hoạch: 3'] → [3 Review/chỉnh: 7']†
                                                              †human boundary
```

**Fallback:** Nếu kế hoạch chưa phù hợp, giữ lịch tập cố định và dùng thực đơn tuần trước.

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Lọc tin công nghệ liên quan

| Trường | Nội dung |
|---|---|
| **Problem (1 câu)** | Mỗi ngày, intern AI engineer mất 15–20 phút lướt tin công nghệ nhưng chỉ tìm được 3–5 bài thực sự liên quan. |
| **Actor** | Bản thân — intern AI engineer cần cập nhật tin ngành |
| **Thời điểm / bối cảnh** | Mỗi ngày, lúc nghỉ hoặc sau giờ làm, khi cần cập nhật tin AI/công nghệ |
| **Bottleneck** | Bước 2–4 — đọc nhiều tiêu đề và mở thử bài để đánh giá mức liên quan |
| **Impact** | 15–20 phút/ngày; chỉ 3–5 bài/tuần thực sự hữu ích, giảm thời gian cho công việc và học tập |
| **Success metric** | Giảm thời gian lọc tin xuống dưới 5 phút/ngày, chọn được ≥3 bài liên quan mỗi ngày |
| **Non-AI alternative** | Theo dõi một số nguồn tin cố định + danh sách chủ đề cần đọc |
| **AI hypothesis** | AI lọc, tóm tắt và xếp hạng tin theo công việc, kỹ năng và chủ đề người dùng quan tâm |
| **Quick gut** | ☐ No AI/process fix ☑ **Rule** ☐ Workflow ☐ Agent ☐ Chưa biết |

**Current workflow (3–7 bước):**
1. Mở nhiều nguồn tin công nghệ
2. Đọc tiêu đề và mô tả bài viết *(bottleneck)*
3. Mở thử các bài có vẻ liên quan *(bottleneck)*
4. Đọc nội dung và đánh giá mức hữu ích *(bottleneck)*
5. Lưu lại các bài phù hợp để đọc sâu hơn

**Draft workflow:**

```
CURRENT STATE — 15–20 phút/ngày
[1 Mở nguồn tin: 3'] → [2 Đọc tiêu đề: 5'] → [3 Mở thử bài: 10']*
                                               *bottleneck

FUTURE STATE — 5 phút
[1 Nạp chủ đề quan tâm: 1'] → [2 AI lọc + tóm tắt: 2'] → [3 Review bài muốn đọc: 2']†
                                                           †human boundary
```

**Fallback:** Nếu AI lọc sai, quay lại danh sách nguồn tin cố định và tự chọn bài từ tiêu đề gốc.

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất

**Card:** Lọc tin công nghệ liên quan

**Vì sao:** Đây là workflow lặp lại mỗi ngày với actor và thời điểm rõ ràng. Bottleneck nằm ở việc phải đọc tiêu đề và mở thử nhiều bài mới đánh giá được mức liên quan; có thể đo trực tiếp thời gian lọc tin và số bài hữu ích mỗi ngày trong 1 tuần, đồng thời so sánh với việc chỉ theo dõi nguồn tin cố định không cần AI.

**Câu hỏi muốn nhóm challenge:**
1. Việc đọc chậm là do quá nhiều nguồn tin, hay do chưa có tiêu chí rõ ràng để xác định "liên quan"?
2. AI tóm tắt/xếp hạng có thực sự đáng tin để bỏ qua bước tự đọc tiêu đề, hay chỉ nên hỗ trợ rút ngắn bước lọc?

**AI phản biện Card:**
- Điểm yếu AI chỉ ra: Chưa định nghĩa rõ "bài liên quan" là gì, nên khó biết AI lọc đúng hay sai. Ngoài ra impact 15-20 phút/ngày chỉ là ước lượng, chưa đo thực tế bằng log.
- Tôi sửa gì: Ghi log 7 ngày về thời gian lọc tin và số bài hữu ích thật, đồng thời liệt kê 3-5 tiêu chí cụ thể để xác định "liên quan" trước khi đưa cho AI làm.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge