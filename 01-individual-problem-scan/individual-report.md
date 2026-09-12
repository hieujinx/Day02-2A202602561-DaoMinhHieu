# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- **Họ và tên:** Đào Minh Hiếu
- **Mã học viên:** 2A202602561
- **Vai trò / bối cảnh:** Quản lý cửa hàng ăn uống (~40-60 món), chịu trách nhiệm vận hành toàn bộ từ nhận order, điều phối bếp đến phục vụ khách. Quán dùng 2 kênh order: khách tự quét QR hoặc NV hỏi khách rồi nhập vào máy POS. Tất cả order đều vào hệ thống POS chung → hiện trên màn hình bếp.
- **Công việc hằng tuần:**
  - Điều phối NV phục vụ và bếp trong ca
  - Xử lý phàn nàn khách hàng (chờ lâu, sai món)
  - Quản lý tồn kho nguyên liệu, cập nhật trạng thái món
  - Tổng hợp doanh thu, đối soát cuối ngày
  - Xếp lịch NV, đào tạo NV mới

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian + Pain từ người khác | Khách order xong (QR hoặc qua NV) rồi ngồi chờ 20-30 phút không biết bếp đã bắt đầu làm chưa, liên tục gọi NV hỏi "Món tôi tới đâu rồi?" — NV cũng không biết, phải chạy vào bếp hỏi | Khách hàng, NV phục vụ, quản lý | Giờ cao điểm khách hỏi "món tới đâu" 10-15 lần/ca; NV mất 2-3'/lần chạy vào bếp hỏi rồi quay ra trả lời; khách bực bội, có bàn bỏ về |
| 2 | Lặp lại | Giờ cao điểm, bếp nhận quá nhiều order cùng lúc (20-30 order), bếp tự quyết định làm order nào trước theo cảm tính → bàn đến trước có khi được phục vụ sau | Bếp, khách hàng | 2 lần/ngày (trưa + tối) × ~2 tiếng; bàn order sớm nhưng chờ lâu hơn bàn order sau: 3-5 lần/ca; quản lý phải can thiệp bằng miệng |
| 3 | Pain từ người khác | Khách order qua QR nhưng không biết món đã hết — chỉ phát hiện khi bếp từ chối, phải chọn lại | Khách hàng, NV phục vụ | 4-6 lần/ngày; mỗi lần mất 3-5' khách chọn lại; có review 1-2 sao trên Google Maps nói "order rồi mới bảo hết" |
| 4 | Lặp lại | Mỗi ngày phải cập nhật trạng thái món (còn/hết) lên QR menu thủ công khi bếp báo hết nguyên liệu — quản lý hay quên khi bận | Quản lý, bếp | 3-5 lần/ngày phải cập nhật; hay quên → khách order món đã hết (liên quan #3); mỗi lần mất 2-3' |
| 5 | AI có thể tốt hơn | Quản lý tự ước lượng nguyên liệu cần mua dựa trên kinh nghiệm, hay mua thừa hoặc thiếu | Quản lý, bếp | Lãng phí ~500k-1tr/tuần mua thừa; thiếu nguyên liệu hết món 2-3 lần/tuần; không có dữ liệu lịch sử phân tích |
| 6 | Tốn thời gian | NV mới nhập order vào POS chậm vì phải tìm từng món trong danh sách ~40-60 món trên máy, khách ngồi chờ NV nhập | NV mới, khách hàng | NV mới mất 2-3'/order để tìm đúng món; tuần đầu sai 5-8 order/ngày do chọn nhầm món; khách thấy thiếu chuyên nghiệp |
| 7 | Lặp lại | NV mới phải nhớ menu, giá, combo, khuyến mãi — hay tư vấn sai hoặc quên gợi ý combo cho khách | NV mới, khách hàng | NV mới cần 1-2 tuần thuộc menu; mất cơ hội upsell combo ~3-5 lần/ngày; khách hỏi về combo NV không trả lời được |
| 8 | Tốn thời gian | Khách muốn tách/gộp bill hoặc thay đổi order giữa chừng — NV phải sửa trên POS, nếu bếp đã làm thì phải báo bếp hủy/đổi | Quản lý, NV, khách | 3-5 lần/ngày; mỗi lần mất 5-7' (sửa POS + liên hệ bếp); giờ đông gây ùn |
| 9 | AI có thể tốt hơn | Không biết trước giờ nào đông khách để chuẩn bị nhân sự và nguyên liệu — có ngày bất ngờ đông, có ngày vắng | Quản lý, NV | Có ngày đông gấp đôi (lễ, sự kiện gần quán) → thiếu người + thiếu đồ; có ngày vắng → thừa NV, lãng phí |
| 10 | Pain từ người khác | Khách không biết thời gian chờ ước tính khi order — nếu biết phải chờ 30' có thể sẽ chọn mua mang về hoặc đi chỗ khác, thay vì ngồi chờ rồi bực | Khách hàng | Khách ngồi chờ 25-30' mới được phục vụ ở giờ cao điểm; 1-2 bàn/tuần bỏ về vì chờ quá lâu; phàn nàn trên Google Maps |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- **Prompt đã hỏi:** "Tôi là quản lý quán ăn, dùng QR + NV nhập POS. Pain lớn nhất giờ cao điểm là khách chờ quá lâu không biết bao giờ có món. Gợi ý thêm problem liên quan theo 4 lăng kính."
- **Ý dùng được:** AI gợi ý vấn đề khách không biết thời gian chờ ước tính khi order (#10) và vấn đề dự đoán lượng khách (#9) — cả hai đều thực tế.
- **Ý bỏ vì không phải pain thật:** AI gợi ý "xây chatbot trả lời khách trên Zalo" — quán chưa có kênh online. AI gợi ý "robot bưng đồ" — quá xa vời với quy mô quán.

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
| 1 | (#1) Khách chờ 20-30' không biết bếp làm tới đâu, gọi NV hỏi liên tục | Pain lớn nhất, xảy ra hằng ngày, actor rõ (khách + NV), metric đo được (số lần hỏi/ca, thời gian NV mất), có evidence (review Google Maps, bàn bỏ về) | Ước tính thời gian chờ chính xác bằng AI có khả thi không? Hay chỉ cần hiện trạng thái đơn giản (đã nhận / đang nấu / sắp xong)? |
| 2 | (#3 + #4) Khách order QR món đã hết → phải chọn lại + quản lý quên cập nhật | Actor rõ (khách), workflow ngắn, pain evidence rõ (review 1-2 sao), liên quan trực tiếp đến trải nghiệm chờ đợi | Rule đơn giản (bếp bấm nút hết món) có thể đủ, chưa chắc cần AI |
| 3 | (#2) Bếp tự quyết thứ tự làm order → bàn đến trước có khi phục vụ sau | Liên quan trực tiếp đến #1 (nguyên nhân gốc khách chờ lâu), workflow rõ, metric đo được | FIFO đơn giản có giải quyết 80% chưa? Hay cần ưu tiên thông minh hơn? |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Khách chờ mù mịt, không biết món tới đâu

```text
Problem 1 câu:
Giờ cao điểm, khách order xong (QR hoặc qua NV) rồi ngồi chờ 20-30 phút
mà không biết bếp đã bắt đầu làm chưa, liên tục gọi NV hỏi "Món tôi tới
đâu rồi?", NV cũng không biết, phải chạy vào bếp hỏi rồi quay ra — tốn
thời gian cả hai bên và khách càng bực.

Actor:
Khách hàng (người chờ đợi, không có thông tin), NV phục vụ (bị hỏi liên
tục, phải chạy đi chạy lại), quản lý (phải xử lý phàn nàn).

Thời điểm / bối cảnh:
Giờ cao điểm hằng ngày: trưa 11h-13h, tối 18h-20h. Quán khoảng 30-50
khách/giờ. Bếp mất 15-25' làm một order tuỳ độ phức tạp, nhưng khi đông
thì chồng chất, thời gian chờ thực tế lên 25-35'.

Current workflow 3-7 bước:
1. Khách order (QR / NV nhập POS) → order vào hệ thống
2. Order hiện trên màn hình bếp → bếp nhận
3. Bếp làm theo thứ tự tự chọn (không có rule rõ)
4. Khách ngồi chờ, không có thông tin gì về tiến trình
5. Khách bắt đầu sốt ruột → gọi NV hỏi "Món tới đâu rồi?"
6. NV không biết → chạy vào bếp hỏi → quay ra trả lời khách
7. Lặp lại bước 5-6 cho nhiều bàn, NV bị kéo khỏi công việc khác

Bottleneck:
Bước 4-6 — Khách không có bất kỳ thông tin nào về trạng thái order sau khi
đặt. Không biết order đã được bếp nhận chưa, đang nấu chưa, còn bao lâu.
Dẫn đến lo lắng → hỏi NV → NV mất thời gian → các bàn khác bị thiếu phục
vụ → hiệu ứng domino.

Impact:
Giờ cao điểm khách hỏi "món tới đâu" 10-15 lần/ca. NV mất 2-3'/lần đi
hỏi bếp, tổng ~30-45'/ca chỉ để trả lời câu hỏi này. Trong lúc đó NV
không phục vụ được bàn khác. Có 1-2 bàn/tuần bỏ về vì chờ quá lâu không
có thông tin. Review Google Maps nhiều lần đề cập "chờ lâu", "không biết
bao giờ có đồ ăn".

Success metric:
Giảm số lần khách hỏi NV "món tới đâu" từ 10-15 lần/ca xuống dưới 3
lần/ca. Giảm thời gian NV mất cho việc hỏi bếp từ 30-45'/ca xuống dưới
10'. Không còn bàn bỏ về vì chờ mà không có thông tin.

Non-AI alternative:
1. Bếp bấm cập nhật trạng thái thủ công trên POS (đã nhận → đang nấu →
   sắp xong) → hiện trên màn hình ở quầy hoặc trên QR menu của khách.
2. Dùng bảng số thứ tự + ước tính thời gian cố định (VD: "15' cho cơm,
   20' cho lẩu") thông báo khách lúc order.
3. NV chủ động ra cập nhật miệng cho bàn chờ lâu.

AI hypothesis:
AI ước tính thời gian chờ cho từng order dựa trên: số order đang chờ trong
hàng đợi bếp + độ phức tạp món + tốc độ bếp hiện tại. Hiển thị cho khách
trên QR (VD: "Ước tính còn ~12 phút") và tự cập nhật khi bếp bấm xong
từng món. Khách thấy tiến trình → bớt lo → ít hỏi NV.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — NV mất ~35-45 phút/ca chỉ để trả lời "món tới đâu"

[1 Khách order (QR / NV nhập POS): 2']
→ [2 Order hiện màn hình bếp: tự động]
→ [3 Bếp làm (không báo tiến trình): 15-25']
→ [4 Khách chờ mù mịt, sốt ruột: 5-15']  <-- pain chính
→ [5 Khách gọi NV hỏi: 0.5']
→ [6 NV chạy vào bếp hỏi → quay ra trả lời: 2-3']  <-- bottleneck
→ [7 Lặp lại bước 5-6 cho nhiều bàn]

FUTURE STATE — NV mất <10 phút/ca cho việc này

[1 Khách order (QR / NV nhập POS): 2']
→ [2 Order vào POS + AI ước tính thời gian chờ: tự động]
→ [3 Khách thấy trạng thái trên QR: "Đã nhận → Đang nấu → Sắp xong
   (~12 phút)": tự động]
→ [4 Bếp bấm cập nhật khi xong từng món: 0.5']  <-- bước thêm cho bếp
→ [5 AI cập nhật thời gian ước tính cho khách: tự động]
→ [6 Khách tự theo dõi → ít gọi NV: 0']  <-- giải phóng NV
→ [7 NV chỉ can thiệp khi có vấn đề thật: 1-2']  <-- human boundary

Fallback: nếu AI ước tính sai quá nhiều → hiện trạng thái đơn giản (đã
nhận / đang nấu / xong) mà không hiện số phút, để khách vẫn có thông tin
cơ bản. Nếu bếp quên bấm cập nhật → NV nhắc hoặc quay lại trả lời miệng.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Khách order QR món đã hết, phải chọn lại

```text
Problem 1 câu:
Khách quét QR order nhưng menu không cập nhật trạng thái hết món kịp thời,
khách chọn món đã hết, bị bếp từ chối, phải chờ thêm để chọn lại — kéo
dài thời gian chờ tổng thể và tạo trải nghiệm xấu.

Actor:
Khách hàng (người đặt món), NV phục vụ (người thông báo và xin lỗi),
quản lý (người cập nhật hệ thống).

Thời điểm / bối cảnh:
Xảy ra liên tục trong ngày, đặc biệt sau giờ cao điểm khi nguyên liệu một
số món cạn. Quán có ~40-60 món, mỗi ngày có 3-5 món bị hết ở các thời
điểm khác nhau.

Current workflow 3-7 bước:
1. Bếp phát hiện nguyên liệu sắp hết → báo miệng cho quản lý
2. Quản lý vào admin panel QR → tìm món → đánh dấu "hết"
3. Trong khoảng delay (bếp báo → quản lý cập nhật), khách đã order món đó
4. Order vào POS → bếp từ chối
5. NV ra bàn thông báo khách, khách chọn lại

Bottleneck:
Bước 2 — Quản lý cập nhật thủ công chậm (delay 5-15' từ lúc bếp báo).
Giờ đông quản lý bận, hay quên.

Impact:
4-6 lần/ngày khách order món đã hết. Mỗi lần mất thêm 3-5' chờ. Có 2-3
review 1-2 sao Google Maps trong 3 tháng nói "order rồi mới bảo hết".

Success metric:
Giảm số lần khách order món đã hết từ 4-6 lần/ngày xuống dưới 1.
Thời gian cập nhật trạng thái món từ 5-15' xuống dưới 1'.

Non-AI alternative:
Bếp bấm nút "hết món" trực tiếp trên màn hình bếp → hệ thống tự ẩn món
trên QR menu. Đây là rule/automation đơn giản, không cần AI.

AI hypothesis:
AI theo dõi lượng order trong ngày + tồn kho ước tính → cảnh báo "món X
sắp hết trong 30 phút" để quản lý/bếp chuẩn bị. Hoặc AI hiển thị "còn
ít" trên QR menu.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~25 phút lãng phí/ngày

[1 Bếp báo miệng: hết món X: 0.5']
→ [2 Quản lý vào admin cập nhật: 5-15']  <-- bottleneck (delay)
→ [3 Khách đã order món hết trong lúc chờ: 2']
→ [4 Bếp từ chối: 0.5']
→ [5 NV thông báo khách, khách chọn lại: 3-5']

FUTURE STATE — ~3 phút lãng phí/ngày

[1 Bếp bấm nút "hết món" trên màn hình bếp: 0.5']
→ [2 Hệ thống tự ẩn/đánh dấu món trên QR menu: tự động (rule)]
→ [3 Khách thấy "hết" trước khi order: 0']
→ [4 Quản lý review cuối ngày: 2']  <-- human boundary

Fallback: nếu bếp quên bấm nút → NV thông báo khách và xin lỗi như cũ.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Bếp tự quyết thứ tự, bàn đến trước phục vụ sau

```text
Problem 1 câu:
Giờ cao điểm, bếp nhận 20-30 order cùng lúc trên màn hình nhưng tự chọn
thứ tự làm theo cảm tính (thường chọn món dễ/quen trước), dẫn đến bàn
order sớm lại được phục vụ sau bàn order muộn hơn.

Actor:
Bếp (người quyết định thứ tự), khách hàng (người chờ không công bằng),
quản lý (phải can thiệp điều phối bằng miệng).

Thời điểm / bối cảnh:
Giờ cao điểm hằng ngày. Bếp có 2-3 người, 1 màn hình hiện tất cả order.
Khi ít order (<10), bếp xử lý tốt. Khi 20-30 order chồng chất, bếp bắt
đầu chọn sai thứ tự.

Current workflow 3-7 bước:
1. Order vào POS → hiện trên màn hình bếp (cả QR lẫn NV nhập)
2. Bếp nhìn danh sách order, tự chọn làm cái nào trước
3. Bếp thường chọn order dễ/nhanh trước (cơm trước, lẩu sau)
4. Bàn order lẩu (khó) phải chờ dù order trước bàn order cơm (dễ)
5. Quản lý nhận ra sai thứ tự → can thiệp bằng miệng
6. Bếp phải đổi lại → làm gián đoạn món đang nấu

Bottleneck:
Bước 2 — Bếp không có quy tắc ưu tiên rõ ràng. Khi order chồng chất, bếp
dựa vào cảm tính → thứ tự không công bằng → quản lý phải can thiệp thủ
công.

Impact:
3-5 lần/ca bàn order sớm phục vụ muộn hơn bàn order sau. Quản lý mất
15-20'/ca điều phối bếp bằng miệng. Khách chờ lâu hơn mong đợi → phàn
nàn.

Success metric:
Giảm số lần bàn order sớm phục vụ sau bàn order muộn từ 3-5 lần/ca xuống
dưới 1. Giảm thời gian quản lý can thiệp điều phối từ 15-20'/ca xuống
dưới 5'.

Non-AI alternative:
Quy tắc FIFO (first in first out) bắt buộc trên hệ thống POS — bếp phải
làm theo thứ tự order vào, không được nhảy cóc. Hoặc chia bếp theo zone
(bếp A lo bàn 1-10, bếp B lo bàn 11-20).

AI hypothesis:
AI sắp xếp hàng đợi theo: thời gian chờ thực tế + độ phức tạp + nhóm
(cùng bàn ra cùng lúc). Hiển thị rõ "bàn X đã chờ 18 phút" trên màn hình
bếp. Quản lý vẫn có thể override.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — quản lý mất 15-20 phút/ca điều phối bếp

[1 Order vào POS → hiện màn hình bếp: tự động]
→ [2 Bếp tự chọn thứ tự (cảm tính): 1']
→ [3 Bếp làm món: 15-25']
→ [4 Bàn order sớm phục vụ muộn: xảy ra 3-5 lần/ca]  <-- pain
→ [5 Quản lý can thiệp bằng miệng: 3-5']  <-- bottleneck
→ [6 Bếp đổi lại, gián đoạn: 2-3']

FUTURE STATE — quản lý mất <5 phút/ca điều phối

[1 Order vào POS: tự động]
→ [2 AI / rule sắp xếp thứ tự ưu tiên trên màn hình bếp: tự động]
→ [3 Bếp làm theo thứ tự đề xuất: 15-25']
→ [4 Quản lý override nếu cần: 1-2']  <-- human boundary

Fallback: nếu rule/AI sắp xếp sai → quản lý override thủ công, hoặc
chuyển về FIFO đơn giản.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Khách chờ mù mịt, không biết món tới đâu
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là pain mà khách chịu trực tiếp mỗi ngày — order xong rồi ngồi chờ
20-30' mà không biết bếp đã làm chưa, liên tục gọi NV hỏi. NV mất 30-45
phút/ca chỉ để trả lời câu hỏi này, không kịp phục vụ bàn khác. Metric rõ:
10-15 lần hỏi/ca, 1-2 bàn bỏ về/tuần, review xấu trên Google Maps. Đây là
bài toán có thể so sánh rõ giữa Rule (hiện trạng thái cố định) và Workflow
(AI ước tính thời gian chờ).
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Chỉ cần bếp bấm cập nhật trạng thái thủ công (đã nhận / đang nấu /
   xong) là đủ hay cần AI ước tính thời gian cụ thể? Rule có giải quyết
   80% pain chưa?
2. Bếp giờ đông đã bận lắm rồi, liệu có chịu bấm thêm nút cập nhật
   trạng thái không? Bước thêm cho bếp có tạo ra bottleneck mới?
```

**AI phản biện Card (nếu có):**
- **Điểm yếu AI chỉ ra:** "Bếp giờ cao điểm đã bận, thêm bước bấm cập nhật trạng thái có thể tạo bottleneck mới — cần tính xem liệu bếp có tuân thủ không." Và: "Ước tính thời gian chờ bằng AI cần dữ liệu lịch sử, quán mới dùng POS thì chưa có đủ data."
- **Tôi sửa gì:** Thêm phương án fallback: nếu bếp không kịp bấm, chỉ hiện trạng thái tự động dựa trên thời gian order vào (VD: "đã nhận" khi mới order, "đang chế biến" sau 5 phút, "sắp xong" sau 15 phút) — không cần bếp làm gì thêm, chỉ dùng rule thời gian. AI ước tính chính xác hơn là bước nâng cấp sau khi có đủ data.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
