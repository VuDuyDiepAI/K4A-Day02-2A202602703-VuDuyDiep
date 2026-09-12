# 03 — Individual Reflection

## Thông tin cá nhân

- Họ và tên: Vũ Duy Điệp
- Mã học viên: 2A202602703
- Nhóm: C3
- Candidate problem nhóm chọn: Từ 12 ý tưởng của cả nhóm, chọn ra 4 ý tưởng hay nhất, sau đó chốt 1 ý tưởng tốt nhất là "theo dõi tin/sự kiện theo sở thích", rồi mở rộng thành lọc và ưu tiên nội dung theo chủ đề/người dùng quan tâm.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đưa ra 3 candidate về sắp xếp lịch học, lập kế hoạch tập luyện/dinh dưỡng, và lọc tin công nghệ/ngành liên quan công việc. | Candidate "lọc tin công nghệ" (candidate 12) gần với hướng nhóm sau này chọn, góp phần hình thành Cluster A. |
| Pitch Problem Card | Trình bày Card về lập lịch tập luyện và chế độ ăn uống hằng tuần, nêu bottleneck ở bước ghép lịch tập với thực đơn phù hợp mục tiêu. | Card này thuộc Cluster B (Lập kế hoạch cá nhân), giúp nhóm phân biệt rõ hơn giữa nhóm bài lọc thông tin (Cluster A) và nhóm bài lập kế hoạch (Cluster B) khi gom cụm. |
| Challenge bài của bạn khác | Đặt câu hỏi cho bài "theo dõi tin theo sở thích" của Hãn: nếu dùng extension để lọc feed thì có làm mất đi các nội dung khác mà người dùng không chủ động tìm nhưng vẫn muốn xem không. | Giúp nhóm cân nhắc thêm về mức độ lọc, tránh tạo filter bubble, góp phần đưa rủi ro này vào bảng before/after impact của workflow nhóm. |
| Gom trùng / cluster | Đề xuất gộp candidate "theo dõi tin theo sở thích" (Hãn) và "lọc tin công nghệ" (của tôi) vào chung Cluster A vì cùng pattern: lọc nội dung liên quan giữa nhiều nguồn nhiễu. | Nhóm nhìn rõ Cluster A là nhóm bài toán gần nhau nhất, dễ hội tụ về 1 candidate. |
| Chọn candidate problem | Cùng nhóm lọc 12 ý tưởng xuống còn 4 ý tưởng hay nhất, sau đó ủng hộ chốt "theo dõi tin theo sở thích" là ý tưởng tốt nhất thay vì giữ riêng bài lọc tin công nghệ của mình, vì phạm vi rộng hơn và áp dụng được cho nhiều actor, không chỉ dân kỹ thuật. | Nhóm hội tụ từ 12 ý tưởng về 1 candidate chung, sau đó mở rộng thành "lọc nội dung theo topic" thay vì dừng ở "theo dõi tin theo sở thích". |
| Validation / research | Đóng góp tìm hiểu thêm về các công cụ lọc feed hiện có (Instagram, TikTok, YouTube) để làm rõ khoảng trống chưa ai giải. | Có thêm evidence nền cho phần 4.2 Research giải pháp đã có. |
| Workflow nhóm | Góp ý thêm bước "người dùng chọn topic/nguồn" ở đầu future workflow, dựa trên kinh nghiệm cá nhân tự chọn nguồn tin công nghệ. | Future workflow có bước khởi đầu rõ ràng thay vì AI tự quyết định nguồn. |
| Problem Statement | Giúp làm rõ boundary "không fact-check, luôn hiển thị link gốc", dựa trên non-AI alternative đã nêu ở Problem Card cá nhân của mình. | Boundary trong PS v1 cụ thể và tránh AI tự quyết định tin đúng/sai. |
| Rule / Workflow / Agent | Ban đầu nghĩ Rule là đủ cho bài lọc tin cá nhân, nhưng sau khi so sánh với nhu cầu chung của nhóm, đồng thuận Workflow vì cần AI xếp hạng/gom trùng. | Nhóm thống nhất chọn Workflow, không lệch về Rule quá đơn giản hoặc Agent quá rộng. |
| Decision | Ủng hộ Not Yet vì chưa có validation trực tiếp từ người dùng mục tiêu, dựa trên kinh nghiệm tự nhận thấy số liệu impact ở bài cá nhân cũng chỉ là ước lượng. | Nhóm không vội chốt Go khi baseline chưa được đo thật. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
 Tôi đặt ra câu hỏi về nguy cơ dùng extension lọc feed sẽ làm mất đi các nội dung khác người dùng vẫn muốn xem, góp phần đưa rủi ro "filter bubble" vào workflow và boundary của nhóm.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ AI brainstorm thêm candidate và giúp diễn đạt các ý thành problem rõ ràng. | Giúp mở rộng góc nhìn và chuẩn hoá cách viết theo cấu trúc actor + điểm nghẽn + dấu hiệu thật. | Một số candidate AI gợi ý ban đầu quá chung, chưa gắn với actor cụ thể. | Giữ lại các ý có workflow rõ, bỏ ý chung chung. |
| Problem Card | Dùng AI phản biện Card #3 (Lọc tin công nghệ) sau khi chọn pitch. | AI chỉ ra chưa định nghĩa rõ "bài liên quan" là gì, nên khó biết lọc đúng hay sai; impact 15-20 phút/ngày cũng mới là ước lượng. | AI không tự đề xuất được cách đo cụ thể nếu không hỏi thêm. | Bổ sung: cần ghi log 7 ngày thật và liệt kê 3-5 tiêu chí cụ thể để xác định "liên quan" trước khi giao cho AI lọc. |
| Workflow | Hỏi AI gợi ý các bước future workflow cho bài lọc tin cá nhân (Rule lọc → AI xếp hạng → review). | Giúp hình dung rõ ranh giới máy/người trước khi đóng góp vào workflow chung của nhóm. | AI đề xuất để AI tự động mở/lưu bài luôn, không cần người review. | Giữ nguyên bước người dùng tự mở link gốc, không để AI quyết định thay. |
| Research | Nhờ AI tìm nhanh các tính năng kiểm soát feed hiện có trên Instagram/TikTok/YouTube. | Tiết kiệm thời gian tổng hợp, có link chính thức để kiểm chứng. | AI ban đầu liệt kê một số tính năng không có link xác thực được. | Chỉ giữ lại các mục có link chính thức từ chính nền tảng. |
| Problem Statement | Nhờ AI phản biện field "impact" và "boundary" trong Problem Card cá nhân. | Buộc phải định nghĩa rõ hơn thay vì để chung chung. | AI có xu hướng chấp nhận số liệu ước lượng như đã đo thật. | Ghi rõ "chưa đo thật, cần log" thay vì trình bày như số liệu chắc chắn. |
| Rule / Workflow / Agent | Hỏi AI so sánh 3 mức cho bài lọc tin cá nhân trước khi mang ý kiến vào nhóm. | Giúp thấy rõ Rule đơn thuần (chỉ theo nguồn cố định) không xử lý được các bài cùng nghĩa khác từ khóa. | Ban đầu AI hơi thiên về đề xuất Agent cho "linh hoạt hơn". | Không chọn Agent; giữ Workflow với Rule làm fallback rõ ràng. |
| Decision | Dùng AI kiểm tra lại xem 6 câu hỏi Final Decision đã được trả lời đủ chưa. | Phát hiện 2 câu (baseline/metric và data/input) vẫn ở mức "Not Yet". | AI có xu hướng muốn kết luận Go nếu diễn đạt tích cực. | Giữ quan điểm Not Yet vì chưa có bằng chứng trực tiếp từ người dùng mục tiêu. |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text 
Làm AI không phải là thi xem mô hình nào "xịn" hơn, mà là xem bài toán đó có đáng để ai đó bỏ tiền hoặc bỏ thời gian ra dùng hay không. Một tính năng AI có thể chạy mượt về mặt kỹ thuật nhưng nếu không giải đúng nỗi đau thật của người dùng thì cũng chỉ là demo đẹp rồi chết yểu. Trải nghiệm người dùng mới là thứ quyết định họ có quay lại lần hai hay không, chứ không phải việc AI "thông minh" đến đâu ở phía sau. Nhiều team làm AI hay mải mê tối ưu độ chính xác mà quên mất một bước sai lệch nhỏ trong trải nghiệm cũng đủ khiến người dùng mất niềm tin ngay lập tức. Góc nhìn business buộc mình phải trả lời câu hỏi khó chịu hơn nhiều so với câu hỏi kỹ thuật: ai sẽ trả tiền cho cái này, và họ trả vì lý do gì. Nếu không định hình được mô hình vận hành hoặc giá trị kinh tế ngay từ đầu, sản phẩm AI dù hay đến mấy cũng khó sống quá giai đoạn thử nghiệm trong lab. Mình nhận ra lằn ranh giữa một sản phẩm AI "làm được" và một sản phẩm AI "đáng làm" nằm chính ở chỗ có ai thật sự cần nó đến mức sẵn sàng đổi thời gian hoặc tiền bạc để lấy nó không.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI