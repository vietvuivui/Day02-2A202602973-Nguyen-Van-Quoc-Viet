# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn Quốc Việt
- Mã học viên: 2A202602973
- Nhóm: Brave - Zone2
- Candidate problem nhóm chọn: Hỗ trợ bác sĩ chẩn đoán hình ảnh khoanh vùng bất thường trên ảnh MRI (não) nhanh và nhất quán hơn so với đọc phim hoàn toàn thủ công, trong khi bác sĩ vẫn là người quyết định chẩn đoán cuối cùng.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 6 problems từ công việc chẩn đoán hình ảnh và số hóa bệnh án (khoanh vùng tổn thương, ưu tiên ca nguy kịch, đo RECIST, tìm tiền sử, số hóa bệnh án, vận hành bệnh viện), chọn top 3 làm Problem Card. | Nhóm có 3 candidate thuộc domain y tế (#7 khoanh vùng MRI, #8 số hóa bệnh án, #9 bệnh nhân tái khám) — cụm D trong bảng cluster. |
| Pitch Problem Card | Pitch đề tài phân đoạn (khoanh vùng) tổn thương trên ảnh y tế MRI. | Đề tài được đưa vào danh sách candidate và trở thành candidate chính nhóm chọn. |
| Challenge bài của bạn khác | Challenge candidate #11 (tổng hợp tin tức nhiều kênh): công cụ tổng hợp thông tin đã có quá nhiều và đang phổ biến trên thực tế, vậy nhóm làm thì có gì khác? | Nhóm bớt topic này khỏi lựa chọn cuối (lý do ghi ở phần "Vì sao không chọn": ít mang tính công nghệ mới). |
| Gom trùng / cluster | Đưa 3 candidate cùng domain y tế (#7 khoanh vùng MRI, #8 số hóa bệnh án, #9 bệnh nhân tái khám) vào cùng một cụm và chỉ ra #9 liên quan trực tiếp đến bước "đối chiếu hồ sơ cũ" trong workflow của #7. | Nhóm gom thành cụm D (hỗ trợ chẩn đoán / hồ sơ y tế): #7 làm candidate chính, #8 và #9 giữ làm hướng mở rộng. |
| Chọn candidate problem | Đề xuất nhóm chọn đề tài khoanh vùng MRI dù điểm chấm thấp hơn 2 candidate còn lại (20 so với 33 và 31). | Nhóm chấp nhận có điều kiện: phải validate ở Phase 4, nếu không được thì rollback về candidate "ghi chép + tóm tắt bài giảng". |
| Validation / research | Tìm hiểu các mô hình AI phân đoạn ảnh y tế — đây là bài toán quan trọng nên đã có rất nhiều phương pháp có thể ứng dụng. | Nhóm có cơ sở để chọn model pretrained (MONAI / nnU-Net) làm PoC thay vì tự train từ đầu. |
| Workflow nhóm | Đưa ý tưởng workflow hiện tại (đọc và khoanh vùng MRI thủ công) và workflow tương lai (AI khoanh vùng, bác sĩ review). | Nhóm vẽ được flow current 6 bước và future 4 bước dùng trong Phase 5. |
| Problem Statement | Cung cấp nội dung domain từ Problem Card #1 của tôi cho các field Actor (bác sĩ chẩn đoán hình ảnh), Workflow (6 bước đọc / khoanh vùng MRI) và Bottleneck (khoanh vùng thủ công, phụ thuộc kinh nghiệm, dễ bỏ sót). | Ba field Actor, Workflow, Bottleneck trong Problem Statement v0 / v1 của nhóm được xây dựng từ nội dung này. |
| Rule / Workflow / Agent | Dựa trên quick gut "Workflow" và phương án non-AI (ước lượng ABC/2, công cụ khoanh bán tự động) trong Card #1 của tôi để góp ý khi so sánh: AI chỉ khoanh sơ bộ, bác sĩ luôn review và quyết định cuối. | Nhóm chọn mức Workflow với bác sĩ review là human boundary; Rule chỉ dùng cho bước tiền xử lý ảnh. |
| Decision | Cùng nhóm thảo luận và quyết định Not Yet cho đề tài của mình; đại diện nhóm trình bày nội dung bài làm và quyết định này với các nhóm khác. | Nhóm chốt Not Yet kèm điều kiện rõ: phỏng vấn ít nhất 1 actor thật và chạy thử model pretrained trước khi Go; nếu không validate được thì rollback về candidate "ghi chép + tóm tắt bài giảng". |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

Đề tài khoanh vùng tổn thương trên ảnh MRI mà cả nhóm theo đuổi là do tôi đề xuất và thuyết phục các thành viên chọn, dù điểm chấm ban đầu thấp hơn hai candidate còn lại. Tôi cũng là người đại diện nhóm trình bày nội dung bài làm với các nhóm khác.

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự nghĩ 5 problem, nhờ AI gợi ý thêm theo 4 lăng kính (kèm actor, workflow sơ bộ, cách đo). | Chỉ ra 3 ý "segmentation / quantification / longitudinal tracking" của tôi là tên kỹ thuật chứ chưa phải problem; gợi ý tách ý "bệnh án thủ công" thành 2 problem riêng (tìm tiền sử, nhập thiếu trường). | 7 problem AI gợi ý thêm là suy luận chung về khoa CĐHA, không dựa trên quan sát tại khoa tôi; AI không có số đo thật nên cột "Dấu hiệu thật" ban đầu để trống toàn bộ. | Bỏ cả 7 gợi ý của AI, chỉ giữ 5 ý của mình (đã viết lại thành problem) và tự bổ sung thêm ý #6 về vận hành bệnh viện. |
| Problem Card | Nhờ AI viết nháp 3 Problem Card đủ field theo template và phản biện điểm yếu từng card. | Card đủ field, có workflow trước/sau; phần phản biện chỉ ra điểm yếu cụ thể: tần suất ca có đủ nhiều không, ước lượng ABC/2 có thể đã đủ, Card #2 và #3 dùng chung pipeline. | AI tự chọn top 3 là ca nguy kịch, RECIST và tìm tiền sử — không phải lựa chọn của tôi. | Tự chọn lại top 3 là #5 (khoanh vùng), #1 (tìm tiền sử), #2 (số hóa bệnh án) và yêu cầu AI viết lại card theo lựa chọn đó. |
| Workflow | Nhờ AI chuyển workflow Card #1 theo ảnh workflow của nhóm (current 6 bước, future 4 bước) sang dạng ASCII. | Chuyển nhanh, đánh dấu rõ bottleneck, human boundary, fallback; phát hiện ảnh không khớp khi tôi nói nhầm là Card #3 và hỏi lại. | Chép quá sát ảnh (người làm từng bước, ghi chú thời gian, tên công cụ MONAI / nnU-Net) làm workflow rối, không đúng mức cần thiết. | Yêu cầu chỉ giữ đúng tên các bước, bỏ chi tiết thừa. |
| Research | Nhờ AI tìm số liệu tham khảo cho cột "Dấu hiệu thật" và baseline trong card vì tôi chưa có số đo tại khoa. | Tìm được 8 nguồn có link kiểm được (PubMed / PMC, số liệu Bộ Y tế) và đối chiếu số với abstract gốc trước khi dùng. | Tóm tắt từ công cụ tìm kiếm có lúc lệch với abstract gốc (thời gian chờ ở nghiên cứu O'Neill: 15,75 so với 15,45 phút) nên phải kiểm lại; số liệu đều là quốc tế, khác bối cảnh khoa tôi; không có nguồn nào cho tần suất ca tại khoa. | Giữ nhãn "tham khảo, chưa phải số đo tại khoa" cho mọi số; yêu cầu bổ sung lại danh sách nguồn cuối bài để mọi trích dẫn [R1]–[R8] đều kiểm được. |
| Pitch (2.3) | Tự viết ý cho 3 ô pitch, nhờ AI sửa câu chữ. | Câu gọn hơn, sửa lỗi gõ, điền số tham khảo [R2] vào chỗ tôi còn để trống. | AI thêm vế "nếu thiếu điều kiện thì thu hẹp phạm vi thế nào" vào câu hỏi challenge — ngoài ý ban đầu của tôi. | Giữ vế đó vì giúp nhóm không chỉ chỉ ra điểm yếu mà còn đề xuất hướng thu hẹp phạm vi; ý chính của câu hỏi (khó triển khai do thiếu tài nguyên, phần cứng, chuyên gia AI, dữ liệu) vẫn là của tôi. |
| Problem Statement | (Nhóm) Nhờ AI phản biện Problem Statement v0. | Chỉ ra field Impact mơ hồ vì chưa có số liệu thật, chỉ dựa trên suy luận. | AI đưa ra những bài toán đơn giản, không có chiều sâu. | Nhóm bổ sung research định lượng có link (thời gian khoanh vùng thủ công, % giảm khi có AI, benchmark Dice) để viết Impact ở v1, và vẫn ghi rõ đó là số liệu thứ cấp. 

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

Những phần tôi không sử dụng AI là Rule/Workflow/Agent do tôi chọn mức giải pháp phải cân nhắc rủi ro của bài toán y tế và điều kiện thực tế của nhóm (dataset công khai, model pretrained, thời gian 1 buổi lab)
Về phần decision, tự đánh giá dựa trên thực tế và tiềm năng trển khai trong tương lai.
---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

Khi nghe top 3 problems của các bạn khác, tôi nhận ra AI có thể được ứng dụng vào rất nhiều vấn đề, và mỗi bài toán là một cơ hội để tôi hiểu hơn về những khó khăn thực tế ở các lĩnh vực khác nhau. Trong quá trình thảo luận, tôi nhận được nhiều câu hỏi challenge từ các bạn và qua đó nhận ra nhiều điểm trong bài của mình vẫn chưa ổn. Ví dụ, đề tài của tôi bị chấm điểm thấp hơn hai candidate còn lại (20 so với 33 và 31) vì còn thiếu bằng chứng thực tế và số liệu đo được. Từ những góp ý đó, tôi đã cải thiện và thay đổi cách tiếp cận của mình. Đóng góp chính của tôi là đề xuất hướng ứng dụng AI vào phân đoạn ảnh y tế, giúp bác sĩ chẩn đoán trong thời gian ngắn hơn — đây cũng là đề tài cả nhóm chọn. Bên cạnh đó, tôi đại diện nhóm thuyết trình và giải thích bài làm cho các bạn ở các nhóm khác. Điều khó nhất khi viết Problem Statement là metric: chúng tôi chưa thể đo và đưa ra những con số chính xác trong thực tế, nên phải dùng số liệu tham khảo từ các nghiên cứu quốc tế. Những con số này giúp ước lượng impact nhưng không thay được số đo thật trong bối cảnh bệnh viện Việt Nam. Nếu làm lại, tôi muốn research kỹ hơn về thực tế ngay từ đầu, để bài toán AI này có thể thực sự được ứng dụng vào các bệnh viện.

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

