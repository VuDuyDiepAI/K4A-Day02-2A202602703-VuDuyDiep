# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   |   Võ Phú Hãn        |       2A202602628      |                                                               |
| 2   |       Võ Minh Quân    |       2A202602429      |                                                               |
| 3   |      Vũ Duy Điệp     |       2A202602703      |                                                               |
| 4   |     Vũ Văn Hà      |        2A202602589     |                                                               |

**Candidate problem nhóm chọn (1 câu):**

Người dùng muốn hạn chế lướt mạng xã hội nhưng vẫn cập nhật được tin và sự kiện đúng sở thích.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Võ Phú Hãn | Chuyển lịch/chuyến bay/hạn bảo hành từ email hoặc text sang calendar và nhắc việc | Người có nhiều lịch và mốc cần nhớ | Trích thông tin và nhập tay | Workflow rõ, có thể Rule là đủ |
| 2 | Võ Phú Hãn | Theo dõi tin/sự kiện theo sở thích mà không phải lướt mạng xã hội nhiều | Người theo dõi sách, phim, thể thao | Lọc tin liên quan giữa feed nhiều nội dung nhiễu | Có pain rõ, cần kiểm tra nguồn dữ liệu |
| 3 | Võ Phú Hãn | Gom nhóm comment/feedback về một bài đăng hoặc chủ đề | Người đăng bài, quản trị cộng đồng | Đọc và phân nhóm comment thủ công | AI có thể hỗ trợ, cần kiểm tra chất lượng nhóm ý |
| 4 | Võ Minh Quân | Cài đặt và setup môi trường cho mỗi project | Developer bắt đầu project mới | Nhiều bước và lỗi dependency/version | 30–120 phút/project; cần xem mức tự động hóa an toàn |
| 5 | Võ Minh Quân | Chạy test thủ công lặp lại sau mỗi lần sửa code | Developer | Sửa → chạy → kiểm tra lặp nhiều vòng | 2–10 phút/lần, 5–20 lần/task; phù hợp Rule/CI |
| 6 | Võ Minh Quân | Chuyển lỗi terminal qua AI/Google rồi copy cách sửa về IDE | Developer và teammate debug cùng | Copy log, thử giải pháp và lặp lại nhiều vòng | 3–10 phút/lỗi, 5–15 lần/ngày; cần kiểm tra IDE/tool integration |
| 7 | Vũ Văn Hà | Kiểm tra thời gian học hằng ngày qua email | Sinh viên | Lịch học nằm trong email, phải tự kiểm tra | Cần đo tần suất và thời gian kiểm tra |
| 8 | Vũ Văn Hà | Xếp hàng chờ ở nhà ăn tòa E1 | Sinh viên ăn tại nhà ăn E1 | Không biết thời điểm hàng đợi đông | Cần quan sát thời gian chờ và khung giờ cao điểm |
| 9 | Vũ Văn Hà | Đi chợ mua đồ cho một tuần, 2 lần vào buổi sáng | Người tự chuẩn bị bữa ăn | Lập danh sách và chọn thời điểm mua | Cần làm rõ pain cụ thể và thời gian mất |
| 10 | Vũ Duy Điệp | Sắp xếp lịch làm và tự học để không chồng chéo | Người tự học ngoài giờ làm | Dò slot rảnh và cân nhắc ưu tiên chủ đề | 15–25 phút/tuần; lịch làm thay đổi liên tục |
| 11 | Vũ Duy Điệp | Lên lịch tập luyện và thực đơn hằng tuần | Người tự tập, không có PT | Ghép lịch tập với thực đơn phù hợp mục tiêu | Mất thời gian, dễ lặp món hoặc lệch lịch |
| 12 | Vũ Duy Điệp | Lọc tin công nghệ/ngành liên quan công việc | Người cần cập nhật ngành | Đọc tiêu đề, mở bài và đánh giá độ liên quan | 15–20 phút/ngày; phải mở bài mới biết có đáng đọc |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Lọc và tổng hợp thông tin | 2, 3, 12 | Tìm tin/ý kiến liên quan giữa nhiều nội dung nhiễu | Candidate 2 và 12 gần nhau nhất |
| B. Lập kế hoạch cá nhân | 1, 7, 10, 11 | Chuyển thông tin rời rạc thành lịch/kế hoạch | Có thể giải bằng Rule/Workflow |
| C. Workflow phát triển phần mềm | 4, 5, 6 | Giảm thời gian setup, test và debug | Có tool sẵn, cần tránh trùng tính năng IDE/CI |
| D. Sinh hoạt hằng ngày | 8, 9 | Tối ưu chờ đợi và mua sắm | Cần thêm evidence và data thực tế |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Theo dõi tin/sự kiện theo sở thích | Pain rõ, có workflow lọc tin; pilot được với nguồn công khai | Nguồn dữ liệu và nguy cơ lọc sót tin quan trọng |
| Hỗ trợ debug từ lỗi terminal | Tần suất và impact cao; input/output rõ | Scope dễ trùng với IDE/AI tool hiện có |
| Chuyển lịch/mốc nhắc việc vào calendar | Workflow và metric rất rõ; pilot đơn giản | Rule có thể đủ, AI chưa chắc cần thiết |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Theo dõi tin/sự kiện theo sở thích | 5 | 4 | 3 | 5 | 5 | 5 | 4 | 31 |
| Hỗ trợ debug từ lỗi terminal | 5 | 4 | 4 | 5 | 3 | 5 | 4 | 30 |
| Chuyển lịch/mốc nhắc việc vào calendar | 5 | 5 | 3 | 3 | 5 | 5 | 5 | 31 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Theo dõi tin/sự kiện theo sở thích mà không phải lướt mạng xã hội nhiều.
```

**Vì sao chọn (4-5 câu):**

```text
Problem gần với nhu cầu thực tế: muốn giảm lướt feed nhưng không bỏ lỡ tin quan trọng. Workflow có thể thu hẹp thành theo dõi vài nguồn công khai, lọc tin nhiễu và gửi link bài gốc. Pilot làm được trong lab và có metric thời gian/lượng tin liên quan. Nhóm sẽ kiểm chứng trước khi quyết định mức AI phù hợp.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Hỗ trợ debug có impact lớn nhưng dễ trùng với AI trong IDE hiện có và cần scope kỹ hơn. Chuyển lịch vào calendar rõ ràng nhưng Rule/parser có thể giải phần lớn nhu cầu, nên AI không phải trọng tâm. Các candidate còn lại thiếu evidence hoặc cần data/điều kiện vận hành khó thu thập trong lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Có cân nhắc bài debug vì metric rõ và tần suất cao. Nhóm chọn theo dõi tin theo sở thích vì có thể pilot nhỏ với nguồn công khai, đồng thời giải đúng nhu cầu giảm lướt mạng xã hội.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 0 | Chưa thực hiện; không có quote để ghi. | Chưa biết nhu cầu có đủ mạnh. | Cần phỏng vấn 2–3 người. |
| Survey / poll | 0 | Chưa thực hiện; không có kết quả để ghi. | Chưa biết chủ đề/nguồn người dùng muốn theo dõi. | Cần poll 5–10 người. |
| Research thứ cấp | 587 người dùng social media tại Anh | 70,4% từng khó tìm post quan trọng; 55,6% từng muốn công cụ lọc post không liên quan. | Không phải mẫu Việt Nam và không riêng nhóm sinh viên. | Dùng làm evidence nền, không thay validation nhóm. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Research cho thấy pain về feed nhiễu và khó tìm tin quan trọng tồn tại. Tuy nhiên nhóm chưa có bằng chứng trực tiếp từ người dùng mục tiêu, nên chưa thể khẳng định problem/metric tại nhóm này.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Instagram | https://about.fb.com/news/2022/03/two-new-ways-to-control-your-instagram-feed/ | Favorites, Following, Not Interested | Cho xem tài khoản đã chọn và giảm gợi ý không muốn xem | Phải thao tác từng feed/post | Người dùng cần quyền chọn nguồn và feedback rõ. |
| TikTok Manage Topics | https://newsroom.tiktok.com/tiktok-trending-summer-2025-plus-new-ways-to-shape-your-feed | Tăng/giảm topic, lọc keyword | Điều chỉnh lượng content theo chủ đề | Không loại bỏ hoàn toàn topic; chỉ trong TikTok | Dùng topic + keyword, nhưng phải cho người dùng review. |
| YouTube controls | https://support.google.com/youtube/answer/6342839?hl=en | Not interested, không đề xuất kênh, xem ít Shorts | Feedback trực tiếp cải thiện recommendation | Không gom tin trùng hoặc tạo brief đa nguồn | Kết hợp feedback và link nội dung gốc. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không xây mạng xã hội hoặc crawler toàn bộ feed. Pilot dùng vài nguồn công khai/RSS do người dùng chọn; Rule lọc keyword, AI xếp hạng và gom nội dung trùng, người dùng luôn mở được nguồn gốc.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Mở nhiều feed: 5'] → [2 Lướt/tìm: 15–30'] → [3 Mở bài để đánh giá: 5'] → [4 Lưu/nhớ tin: 2']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Người dùng | Feed từ nhiều nền tảng | Danh sách post | Hằng ngày | Nhiều nguồn. |
| 2 | Người dùng | Post/feed | Tin có vẻ liên quan | 15–30 phút | Bottleneck: tự lọc. |
| 3 | Người dùng | Tiêu đề/thumbnail | Bài gốc đã mở | 3–5 phút | Phải mở mới biết chất lượng. |
| 4 | Người dùng | Bài gốc | Tin đã đọc/lưu | 2–5 phút | Có thể bỏ sót tin khác. |
| 5 | — | — | — | — | Không áp dụng. |
| 6 | — | — | — | — | Không áp dụng. |
| 7 | — | — | — | — | Không áp dụng. |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck là bước lướt và mở nhiều nội dung để tự đánh giá mức liên quan. Feed có nội dung trùng/nhiễu nên thời gian tìm không tỉ lệ với số tin hữu ích nhận được.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Người dùng chọn topic/nguồn: 2' - người] → [2 Lấy RSS/public links: 1' - máy] → [3 Rule lọc keyword: <1' - máy] → [4 AI xếp hạng/gom trùng: <1'] → [5 Người dùng mở link gốc: 5' - boundary]

Fallback: tắt AI, dùng danh sách nguồn theo thời gian và bộ lọc keyword.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | Ước lượng 20–40 phút/ngày | Dưới 10 phút/ngày | Bấm giờ 7 ngày trước/sau. |
| Số bước | 4 | 5 | Đếm bước; thêm bước review để kiểm soát. |
| Số bước thủ công | 4 | 2 | Người dùng chọn và mở bài gốc. |
| Bottleneck chính | Tự lọc feed | Review kết quả | Log thời gian review. |
| Risk mới | Bỏ sót tin chưa đo được | Lọc nhầm/tạo filter bubble | Ghi tin bị lọc nhầm. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người dùng nhận tin qua social media và muốn giảm lướt feed. |
| **Workflow** | Mở nhiều feed → lướt → mở bài để đánh giá → lưu/đọc. |
| **Bottleneck** | Tự lọc nội dung không liên quan, trùng hoặc chất lượng thấp. |
| **Impact** | Ước lượng 20–40 phút/ngày; baseline cần đo lại bằng người dùng mục tiêu. |
| **Success Metric** | Dưới 10 phút/ngày, nhưng chưa chốt trước validation. |
| **Boundary** | Không kiểm chứng sự thật của tin; không tự đăng/bình luận; luôn có link gốc. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: "tin nhảm" và baseline thời gian.
- Tôi sửa gì: định nghĩa là không liên quan/trùng/lower-quality theo feedback; yêu cầu đo baseline trước pilot.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Cao (nhiều cách trả lời vẫn OK) — Vì mức liên quan phụ thuộc topic và người dùng.
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì có chọn nguồn, lọc, gom trùng và review.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô phức tạp cao, mơ hồ cao → Workflow có human review.
```

**Vì sao (2-3 câu):**

```text
Rule giải keyword và nguồn cố định; AI hữu ích ở xếp hạng theo ngữ nghĩa/gom trùng. Tuy vậy AI không được tự quyết tin nào là "đúng" hoặc tự thay người dùng chọn nội dung.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | RSS + allowlist nguồn + keyword blocklist | Khi topic/keyword rõ | Lọc sót ngữ cảnh, không gom tin trùng tốt | Dùng cho lấy và lọc sơ bộ. |
| **Workflow** | Rule lấy tin → AI xếp hạng/gom trùng → người dùng mở link gốc | Hợp với pilot tuyến tính, ít nguồn | Lọc nhầm hoặc tạo echo chamber | Chọn cho pilot. |
| **Agent** | Tự tìm nguồn mới, đổi tiêu chí, gửi tin | Chỉ khi cần nhiều nhánh/tool | Scope, quyền truy cập và lỗi cao | Không chọn. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule giải được nguồn cố định và keyword, nhưng không đủ cho relevance/gom trùng.
2. Pilot đi theo đường thẳng: lấy → lọc → xếp hạng → review.
3. Không cần Agent vì không cần tự lập kế hoạch hay mở rộng nguồn.
4. Người dùng phát hiện khi review; đánh dấu sai ngay trong phiên dùng.
5. Có: nếu AI không giúp, quay về RSS + keyword filter.

**Mức chọn:**

```text
Workflow.
```

**Vì sao chọn (3-4 câu):**

```text
Workflow giữ các bước máy ở phạm vi rõ và chỉ dùng AI cho xếp hạng/gom trùng. Người dùng vẫn chọn topic, nguồn và tự mở bài gốc. Cách này đủ để test giả thuyết mà không cần quyền truy cập hay hành vi tự chủ của Agent.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule không xử lý tốt các bài cùng nghĩa nhưng khác keyword, hoặc nhiều bài trùng về cùng một sự kiện. Tuy nhiên Rule vẫn là fallback và cần đo xem AI có cải thiện đủ nhiều hay không.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người dùng muốn nhận tin phù hợp mà giảm thời gian lướt feed. |
| **Workflow** | Chọn topic/nguồn → lấy nội dung công khai → Rule lọc → AI xếp hạng/gom trùng → người dùng mở link gốc. |
| **Bottleneck** | Tự tìm và đánh giá độ liên quan của nhiều post trong feed. |
| **Impact** | Baseline 20–40 phút/ngày chỉ là ước lượng; phải đo lại trong validation. |
| **Success Metric** | Giảm thời gian tìm tin xuống dưới 10 phút/ngày, không bỏ lỡ tin người dùng tự đánh giá quan trọng. |
| **Boundary** (làm / không làm) | Làm: lọc/xếp hạng/gom trùng nội dung từ nguồn công khai. Không làm: fact-check, crawl feed riêng tư, tự đăng hoặc tự thay đổi follow. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau Rule lấy/lọc tin, trước khi người dùng review và mở bài gốc. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow: AI chỉ hỗ trợ semantic relevance và gom trùng trong flow cố định. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Lọc nhầm tin quan trọng/thiên lệch. Người dùng review từng danh sách, mở link gốc và đánh dấu sai. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor và flow đã xác định. |
| Baseline + metric đo được chưa? | Not Yet | 20–40 phút/ngày là ước lượng, chưa có log. |
| Data/input đủ dùng chưa? | Not Yet | Chưa chốt topic và 3–5 nguồn công khai cho pilot. |
| AI sai, hậu quả chấp nhận được không? | Yes, có điều kiện | Chỉ gợi ý; người dùng review và link gốc luôn hiện. |
| Có người review/owner không? | Yes | Người dùng pilot là reviewer. |
| Có cách non-AI đơn giản hơn không? | Yes | RSS + keyword filter là baseline so sánh. |

**Decision:**

```text
Not Yet.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Research xác nhận pain rộng về feed nhiễu và thiếu control, đồng thời cho thấy các nền tảng đã có control từng phần. Nhưng nhóm chưa có survey/interview thật của người dùng mục tiêu, chưa có baseline thời gian và chưa chốt nguồn dữ liệu pilot. Vì vậy chưa đủ bằng chứng để Go.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Chưa áp dụng vì decision hiện tại là Not Yet.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Phỏng vấn 2–3 người và poll 5–10 người: họ theo dõi chủ đề nào, mất bao lâu để tìm tin, tin nào từng bỏ lỡ, và có dùng brief kèm link gốc không. Sau đó chọn 1 topic + 3–5 nguồn công khai, đo 7 ngày baseline.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu No-Go, dùng RSS reader/Following feed và keyword filter thủ công.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng AI nếu người dùng đánh giá hơn 20% tin bị lọc sai hoặc vẫn mất trên 10 phút/ngày trong 1 tuần pilot; quay về RSS + keyword filter.
```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
