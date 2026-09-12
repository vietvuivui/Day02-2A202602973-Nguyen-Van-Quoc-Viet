# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyen Van Quoc Viet
- Mã học viên: 2A202602973
- Vai trò / bối cảnh: Bác sĩ chẩn đoán hình ảnh (Radiologist), Khoa Chẩn đoán hình ảnh
- Công việc hằng tuần:
  - Đọc phim X-quang, CT, MRI và viết báo cáo chẩn đoán hình ảnh
  - Đánh giá phim theo dõi cho bệnh nhân đang điều trị (so sánh với phim cũ)
  - Trao đổi kết quả với bác sĩ lâm sàng, báo kết quả nguy kịch
  - Tham gia số hóa bệnh án (nhập / tóm tắt hồ sơ giấy vào hệ thống)
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Bệnh nhân tái khám / nhập viện lại: bác sĩ phải lật bệnh án giấy hoặc file scan PDF (không tìm kiếm được) để tìm tiền sử quan trọng — dị ứng, thuốc đang dùng, chẩn đoán cũ | BS điều trị, BS CĐHA, bệnh nhân | Tham khảo: ngay cả khi đã có EHR, BS dành trung bình 16 phút 14 giây/lượt khám cho hồ sơ điện tử, trong đó 33% (≈5 phút) là xem lại hồ sơ [R6]. Với bệnh án giấy / PDF không tìm kiếm được chưa có số công bố → đo tại khoa trong pilot |
| 2 | Lặp lại | Số hóa bệnh án hiện chỉ nhập bản tóm tắt, thiếu các trường quan trọng (dị ứng, thuốc, kết quả cận lâm sàng cũ) | BS, điều dưỡng, phòng KHTH | Tham khảo: audit 88 hồ sơ ở một bệnh viện dùng hồ sơ giấy — chỉ 25% ghi chép lâm sàng có ghi tình trạng dị ứng thuốc; 0/9 ca có tiền sử dị ứng được ghi đủ 5 yếu tố (thuốc, phản ứng, mức độ, thời điểm, xử trí) [R7] |
| 3 | AI có thể tốt hơn | Ca nguy kịch (xuất huyết não, tràn khí màng phổi...) nằm chung worklist sắp theo thời gian chụp, phải chờ đến lượt mới được đọc | BS CĐHA, BS cấp cứu, bệnh nhân | Tham khảo: ở một khoa CĐHA thần kinh, khi AI gắn cờ và đẩy ca xuất huyết nội sọ lên đầu worklist, thời gian chờ đọc (hiệu chỉnh theo hàng đợi) là 12,02 phút so với 15,45 phút ở ca không có cờ [R4] |
| 4 | Tốn thời gian | Đánh giá đáp ứng điều trị ung thư: phải tìm lại từng tổn thương đích trên phim cũ và phim mới, đo tay theo RECIST, tính % thay đổi | BS CĐHA, BS ung bướu | Tham khảo: đánh giá iRECIST trên 30 BN — đo tay mất trung vị 4,00 phút/BN so với 2,50 phút khi có phần mềm hỗ trợ; tỷ lệ phân loại đáp ứng sai ở lần theo dõi thứ 2: 10% (đo tay) so với 1,7% (phần mềm) [R5] |
| 5 | Tốn thời gian | Khoanh vùng, tính thể tích tổn thương (khối u, ổ xuất huyết) làm tay trên từng lát cắt khi lâm sàng cần số liệu | BS CĐHA, BS phẫu thuật | Tham khảo: khoanh tay thể tích u não có thể mất tới ~1 giờ/BN, phương pháp tự động ~5 phút/BN [R2] (nghiên cứu cũ hơn: 3–5 giờ tay so với 5–10 phút tự động [R1]); ước lượng ABC/2 cho xuất huyết não chỉ mất vài phút nhưng lệch nhiều so với chuẩn tham chiếu [R3] |
| 6 | Pain từ người khác / AI có thể tốt hơn | Ban quản lý phân bổ giường bệnh, phòng mổ, thiết bị và xếp ca trực chủ yếu theo kinh nghiệm và lịch cố định, không dựa trên dự báo lưu lượng nhập viện / cấp cứu → ngày đông thì thiếu giường, thiếu người trực, bệnh nhân phải chờ; ngày vắng thì thừa nhân lực | Ban giám đốc, phòng KHTH, điều dưỡng trưởng; nhân viên trực bị quá tải; bệnh nhân chờ giường | Tham khảo: công suất sử dụng giường bệnh tuyến tỉnh tăng từ 92% (2014) lên 129% (2022), tuyến trung ương giảm từ 100% xuống 80% — theo số liệu Bộ Y tế [R8] |

> **Ghi chú về số liệu:** cột `Dấu hiệu thật` đang dùng số tham khảo từ nghiên cứu / báo cáo đã công bố (xem mục **Nguồn tham khảo** cuối file), chưa phải số đo tại khoa tôi. Tần suất tại khoa (số ca, số lần/tuần) sẽ được đếm trong tuần đầu pilot.

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là bác sĩ trong bệnh viện. Công việc hằng tuần gồm: chẩn đoán hình ảnh (Radiologist), và việc số hóa bệnh án. Tôi đã nghĩ ra các vấn đề sau: [5 ý]. Hãy gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác. Với mỗi gợi ý, ghi actor, workflow sơ bộ và cách đo. Đừng đưa ý tưởng quá rộng."
- Ý dùng được: dòng #1–#5 đến từ 5 ý tôi tự nghĩ ban đầu; dòng #6 là ý tôi tự bổ sung sau. AI chỉ ra ý "segmentation / quantification / longitudinal tracking" là tên kỹ thuật, chưa phải problem → tôi viết lại thành việc bác sĩ đang làm tay (#4, #5); tách ý "bệnh án thủ công" thành 2 problem (#1 tìm tiền sử, #2 nhập thiếu trường).
- Ý bỏ vì không phải pain thật: AI gợi ý thêm 7 problem (template báo cáo ca bình thường, kiểm chất lượng ảnh tại máy, lỗi báo cáo trái/phải, theo dõi phát hiện tình cờ, đọc lại ca trực đêm, lâm sàng gọi hỏi kết quả, phiếu chỉ định thiếu thông tin). Tôi không đưa vào scan vì muốn giữ các problem xuất phát từ quan sát của chính mình trong công việc; 7 gợi ý này hợp lý nhưng tôi chưa kiểm chứng được mức độ xảy ra tại khoa.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #5 — Khoanh vùng, tính thể tích tổn thương làm tay | Bottleneck nằm ở đúng 1 bước (khoanh viền từng lát cắt); đo được cả thời gian/ca và độ lệch thể tích giữa 2 bác sĩ; có phương án non-AI rõ để so sánh | Số ca cần tính thể tích/tháng có đủ nhiều không; lâm sàng cần số chính xác hay số ước lượng là đủ; workstation hiện tại đã có công cụ khoanh bán tự động chưa |
| 2 | #1 — Tìm tiền sử trong bệnh án giấy / file scan | Gắn với việc số hóa bệnh án tôi đang làm; ảnh hưởng nhiều bác sĩ ngoài khoa CĐHA; bỏ sót dị ứng / thuốc có hậu quả rõ | OCR chữ viết tay có đủ chính xác không; dữ liệu bệnh nhân không được ra khỏi hệ thống viện |
| 3 | #2 — Số hóa bệnh án chỉ nhập tóm tắt, thiếu trường | Là việc tôi làm hằng tuần; là nguyên nhân gốc của #1; đo nhanh bằng cách kiểm 20 hồ sơ | Có thể chỉ cần mẫu nhập có trường bắt buộc (No AI); dùng chung pipeline OCR với #1 → có thể gộp #1 và #2 thành 1 bài |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Khoanh vùng, tính thể tích tổn thương

```text
Problem 1 câu:
Khi lâm sàng cần số liệu thể tích tổn thương (khối u trước phẫu thuật, ổ xuất huyết não...),
BS CĐHA phải khoanh viền tổn thương bằng tay trên từng lát cắt CT/MRI; việc này tốn thời gian
và 2 bác sĩ khoanh cùng một ca có thể ra thể tích khác nhau.

Actor:
BS CĐHA. Người chịu ảnh hưởng: BS phẫu thuật / lâm sàng dùng số liệu thể tích để lên kế hoạch
điều trị, theo dõi tiến triển.

Thời điểm / bối cảnh:
Khi phiếu chỉ định hoặc lâm sàng yêu cầu số liệu thể tích, thường ở ca cần lên kế hoạch
phẫu thuật hoặc theo dõi kích thước tổn thương.

Current workflow 3-7 bước:
1. Chụp MRI, lưu vào PACS
2. Tải ảnh lên workstation
3. Khoanh vùng nghi ngờ bằng tay
4. Đối chiếu hồ sơ cũ (nếu tái khám)
5. Viết báo cáo chẩn đoán
6. Gửi báo cáo cho bác sĩ điều trị

Bottleneck:
Bước 3: khoanh tay trên từng lát cắt, tốn thời gian và là nguồn gây lệch số liệu giữa các bác sĩ.

Impact:
Tham khảo: khoanh tay u não có thể mất tới ~60 phút/BN, phương pháp tự động ~5 phút/BN [R2].
Tần suất tại khoa: đếm trong tuần đầu pilot.
Số liệu thể tích lệch có thể làm sai đánh giá tiến triển (to lên / nhỏ đi) → ảnh hưởng
quyết định điều trị. Khi bận, bác sĩ có xu hướng ước lượng nhanh thay vì khoanh đầy đủ.

Success metric:
- Thời gian/ca: từ baseline đo trên 5 ca đầu pilot (tham khảo: tới ~60 phút/BN với u não [R2])
  giảm ≥50%.
- Độ lệch thể tích giữa 2 BS: baseline đo trong pilot bằng cách cho 2 BS khoanh tay độc lập
  cùng 10 ca, tính chênh lệch thể tích (%); mục tiêu: chênh lệch khi dùng AI + BS chỉnh
  thấp hơn baseline.
- Tỷ lệ lát cắt BS phải chỉnh lại đường viền AI: ≤30% (đếm trong pilot).

Non-AI alternative:
- Ước lượng bằng công thức 3 trục (ví dụ ABC/2 cho xuất huyết não) khi lâm sàng chỉ cần
  số gần đúng.
- Công cụ khoanh bán tự động có sẵn trên workstation (region growing, threshold).

AI hypothesis:
Model segmentation tự khoanh sơ bộ tổn thương trên mọi lát cắt; BS review và chỉnh viền
ở những lát sai, rồi mới viết báo cáo.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
(Nếu ước lượng 3 trục hoặc công cụ bán tự động đã đủ cho nhu cầu lâm sàng thì hạ xuống Rule.)
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 6 bước (tham khảo: khoanh tay u não tới ~60 phút/BN [R2])

[1 Chụp MRI, lưu vào PACS]
→ [2 Tải ảnh lên workstation]
→ [3 Khoanh vùng nghi ngờ bằng tay]   <-- bottleneck
→ [4 Đối chiếu hồ sơ cũ (nếu tái khám)]
→ [5 Viết báo cáo chẩn đoán]
→ [6 Gửi báo cáo cho bác sĩ điều trị]

FUTURE STATE — 4 bước, mục tiêu giảm ≥50% phút/ca

[1 Ảnh MRI vào hệ thống]              -- Rule
→ [2 AI khoanh vùng]                  -- Workflow step
→ [3 Bác sĩ review + chỉnh sửa]       <-- human boundary
→ [4 Viết báo cáo, gửi đi]

Fallback: AI khoanh sai hoặc bác sĩ không đồng ý → quay lại khoanh tay như hiện tại.
```

File đính kèm: `../02-group-problem-statement/images/workflow-current.png`, `../02-group-problem-statement/images/workflow-future.png`

---

#### Problem Card #2 — Tìm tiền sử trong bệnh án giấy / file scan

```text
Problem 1 câu:
Khi bệnh nhân tái khám hoặc nhập viện lại, bác sĩ phải lật bệnh án giấy hoặc file scan PDF
không tìm kiếm được để tìm tiền sử quan trọng, vì bản số hóa hiện tại chỉ là tóm tắt
và thường thiếu dị ứng, thuốc đang dùng, kết quả cũ.

Actor:
BS điều trị và BS CĐHA cần ngữ cảnh lâm sàng. Liên quan: phòng lưu trữ / KHTH.

Thời điểm / bối cảnh:
Khi tiếp nhận bệnh nhân cũ, trước khi chỉ định hoặc đọc phim.

Current workflow 3-7 bước:
1. Yêu cầu hồ sơ cũ từ lưu trữ
2. Chờ lấy hồ sơ giấy / tìm file scan
3. Lật từng trang tìm dị ứng, thuốc, chẩn đoán cũ
4. Ghi lại vào bệnh án hiện tại

Bottleneck:
Bước 3: đọc lướt nhiều trang (thường là chữ viết tay) để tìm vài thông tin cụ thể.

Impact:
Tham khảo: ngay cả khi có EHR, 33% trong 16 phút 14 giây/lượt khám là xem lại hồ sơ (≈5 phút) [R6];
với bệnh án giấy / PDF không tìm kiếm được chưa có số công bố — đo 5 lần tìm đầu pilot.
Bỏ sót tiền sử dị ứng / thuốc đang dùng có thể gây sai sót khi chỉ định (ví dụ thuốc cản quang).

Success metric:
- Thời gian tìm 1 thông tin tiền sử: từ baseline đo trên 5 lần tìm đầu pilot giảm ≥50%.
- Số lần tìm mà không thấy thông tin cần (phải hỏi lại bệnh nhân / bỏ qua): ghi nhận trong
  2 tuần trước và 2 tuần sau pilot; mục tiêu giảm so với trước pilot.

Non-AI alternative:
Scan có OCR để tìm kiếm được (nhiều máy scan có sẵn); đánh chỉ mục hồ sơ theo mã bệnh nhân;
trang tóm tắt tiền sử đặt ở đầu mỗi hồ sơ.

AI hypothesis:
OCR (kể cả chữ viết tay) + AI trích xuất thông tin vào các trường cố định, kèm số trang nguồn
để bác sĩ bấm vào kiểm lại.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
(Nếu scan OCR + tìm theo từ khóa đã đủ thì hạ xuống Rule.)
```

**Draft workflow Card #2:**

```text
CURRENT STATE — baseline đo trong pilot (bấm giờ tách riêng bước 2 và bước 3)

[1 Yêu cầu hồ sơ cũ từ lưu trữ]
→ [2 Chờ lấy hồ sơ giấy / tìm file scan]
→ [3 Lật từng trang tìm dị ứng, thuốc, chẩn đoán cũ]   <-- bottleneck
→ [4 Ghi lại vào bệnh án hiện tại]

FUTURE STATE — mục tiêu giảm ≥50% thời gian tìm

[1 Hồ sơ đã scan + OCR, tìm theo mã bệnh nhân]              -- Rule
→ [2 AI trích xuất trường cố định, kèm số trang nguồn]      -- Workflow step
→ [3 BS xem bảng tóm tắt, bấm vào trang nguồn để kiểm]     <-- human boundary
→ [4 BS ghi vào bệnh án hiện tại]

Fallback: trường AI để trống hoặc độ tin cậy thấp → BS mở trang gốc đọc như hiện tại.
Boundary: AI không tự ghi vào bệnh án chính thức; thông tin dị ứng thuốc luôn phải hỏi lại
bệnh nhân; dữ liệu không ra khỏi hệ thống của bệnh viện.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Số hóa bệnh án chỉ nhập tóm tắt, thiếu trường quan trọng

```text
Problem 1 câu:
Khi số hóa bệnh án giấy, người nhập chỉ gõ bản tóm tắt vì gõ lại toàn bộ quá lâu và không có
mẫu trường bắt buộc, nên hồ sơ điện tử thường thiếu dị ứng, thuốc đang dùng, kết quả
cận lâm sàng cũ.

Actor:
Người nhập liệu: BS / điều dưỡng / nhân viên KHTH. Người chịu ảnh hưởng: bác sĩ dùng hồ sơ
ở lần khám sau (dẫn tới problem Card #2).

Thời điểm / bối cảnh:
Khi bệnh án ra viện được số hóa, hoặc khi chuyển hồ sơ giấy cũ vào hệ thống.

Current workflow 3-7 bước:
1. Nhận bệnh án giấy
2. Đọc toàn bộ hồ sơ (phần lớn chữ viết tay)
3. Tự chọn thông tin nào quan trọng và gõ bản tóm tắt
4. Scan bản giấy lưu PDF (nếu có)
5. Lưu vào hệ thống

Bottleneck:
Bước 3: gõ tay lâu nên người nhập cắt bớt; không có mẫu trường bắt buộc nên mỗi người
tóm tắt một kiểu, dễ bỏ sót trường quan trọng.

Impact:
Tham khảo: ở một bệnh viện dùng hồ sơ giấy, chỉ 25% ghi chép lâm sàng có ghi tình trạng dị ứng thuốc [R7].
Thời gian nhập/hồ sơ và số hồ sơ/tuần tại khoa: đo trong pilot.
Hồ sơ thiếu thông tin → lần khám sau bác sĩ phải lật lại bản giấy (Card #2) hoặc bỏ sót tiền sử.

Success metric:
- Thời gian nhập/hồ sơ: từ baseline đo trên 5 hồ sơ đầu pilot giảm ≥50%.
- Tỷ lệ hồ sơ thiếu trường bắt buộc: từ baseline (kiểm 20 hồ sơ đã số hóa; tham khảo: 75% ghi
  chép lâm sàng không ghi tình trạng dị ứng [R7]) xuống 0/20 (mẫu không cho lưu khi trường
  bắt buộc để trống).

Non-AI alternative:
Mẫu nhập có trường bắt buộc (dị ứng, thuốc, chẩn đoán, kết quả chính — không lưu được nếu
để trống, cho phép chọn "không có"); checklist khi nhập; phân công nhân viên nhập liệu
chuyên trách.

AI hypothesis:
OCR + AI điền sẵn các trường bắt buộc từ bản scan, kèm số trang nguồn; người nhập chỉ kiểm
và sửa thay vì gõ từ đầu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
(Nếu thiếu trường chủ yếu do không có mẫu bắt buộc chứ không do gõ lâu thì chỉ cần Rule /
process fix.)
```

**Draft workflow Card #3:**

```text
CURRENT STATE — baseline đo trong pilot (5 hồ sơ đầu)

[1 Nhận bệnh án giấy]
→ [2 Đọc toàn bộ hồ sơ]
→ [3 Chọn thông tin + gõ bản tóm tắt]   <-- bottleneck
→ [4 Scan lưu PDF]
→ [5 Lưu vào hệ thống]

FUTURE STATE — mục tiêu giảm ≥50% thời gian nhập, không còn hồ sơ thiếu trường bắt buộc

[1 Scan bệnh án giấy]                                         -- Rule
→ [2 OCR + AI điền sẵn các trường bắt buộc, kèm trang nguồn]  -- Workflow step
→ [3 Người nhập kiểm, sửa, xác nhận từng trường]              <-- human boundary
→ [4 Mẫu kiểm tra đủ trường bắt buộc rồi mới cho lưu]         -- Rule

Fallback: OCR không đọc được (chữ khó đọc, bản scan mờ) → trường để trống, người nhập
gõ tay như hiện tại.
Boundary: AI không tự lưu vào bệnh án; mọi trường phải được người nhập xác nhận;
dữ liệu không ra khỏi hệ thống của bệnh viện.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
[TODO: tự viết — không dùng AI]
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
[TODO: tự viết — không dùng AI]
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
[TODO: tự viết — không dùng AI]
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
  - Card #1 (thể tích): chưa rõ tần suất — nếu chỉ vài ca/tháng thì tổng thời gian tiết kiệm
    nhỏ dù thời gian/ca giảm mạnh. Chưa chứng minh lâm sàng cần số chính xác; nếu ước lượng
    ABC/2 đủ cho quyết định điều trị thì không cần AI. Model segmentation dùng trong chẩn đoán
    thường phải được cấp phép như thiết bị y tế, và model huấn luyện trên dữ liệu nước ngoài
    có thể kém hơn trên máy / protocol chụp của viện.
  - Card #2 (tìm tiền sử): bottleneck có thể nằm ở bước 2 (chờ lưu trữ lấy hồ sơ) chứ không
    phải bước 3 — cần bấm giờ tách riêng từng bước. Nếu hồ sơ gốc đã thiếu thông tin (Card #3)
    thì AI trích xuất cũng không tìm ra → Card #2 phụ thuộc Card #3. Scan OCR + tìm từ khóa
    (non-AI) có thể đã giải phần lớn case.
  - Card #3 (số hóa thiếu trường): chưa rõ nguyên nhân thiếu trường là do gõ lâu hay do không
    có mẫu bắt buộc — nếu do không có mẫu thì Rule đủ, AI thừa. Nếu OCR đọc chữ viết tay sai
    nhiều, việc kiểm từng trường AI điền có thể không nhanh hơn gõ tay. Card #2 và #3 dùng
    chung pipeline → nhóm có thể yêu cầu gộp.
- Tôi sửa gì:
  - Card #1: đổi metric chủ quan ("BS tự đánh giá sửa ít") thành chỉ số đếm được (% lát cắt phải
    chỉnh lại); bổ sung số tham khảo thời gian khoanh tay [R1][R2] làm cơ sở cho impact.
  - Card #2: ghi rõ trong workflow là phải bấm giờ tách riêng bước 2 (chờ hồ sơ) và bước 3
    (lật tìm) để xác định đúng bottleneck.
  - Card #3: giữ điều kiện "nếu thiếu trường do không có mẫu bắt buộc thì hạ xuống Rule" trong
    Quick gut.
  - Card #2 và #3: giữ tách riêng ở phần cá nhân, ghi rõ ở bảng top 3 là có thể gộp để nhóm quyết định.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge

---


