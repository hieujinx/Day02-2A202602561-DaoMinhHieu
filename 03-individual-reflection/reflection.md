# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đào Minh Hiếu
- Mã học viên: 2A202602561
- Nhóm: (điền tên/số nhóm)
- Candidate problem nhóm chọn: Khách order xong ngồi chờ 20-30 phút không biết bếp đã làm tới đâu, liên tục gọi NV hỏi — NV cũng không biết, phải chạy vào bếp hỏi rồi quay ra, tốn thời gian cả hai bên.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan được 10 problems từ bối cảnh quản lý quán ăn, dùng 4 lăng kính (tốn thời gian, lặp lại, pain từ người khác, AI có thể tốt hơn). Mỗi dòng có actor, số đo, bằng chứng cụ thể (review Google Maps, log POS). | Nhóm có thêm nguồn problems phong phú từ domain F&B thực tế, đặc biệt chuỗi pain khách chờ → NV chạy hỏi bếp → bàn bỏ về. |
| Pitch Problem Card | Pitch Card #1 — "Khách chờ mù mịt, không biết món tới đâu". Trình bày workflow 7 bước current state, chỉ ra bottleneck bước 4-6 (khách không có thông tin → hỏi NV → NV chạy bếp), metric: 10-15 lần hỏi/ca, 1-2 bàn bỏ về/tuần. | Nhóm thấy pain rõ ràng, có evidence (review Google Maps), metric đo được. Card này được nhóm đưa vào shortlist. |
| Challenge bài của bạn khác | Hỏi challenge về tính khả thi: "Bếp giờ đông bận lắm rồi, liệu có chịu bấm thêm nút cập nhật trạng thái không?" và "Rule đơn giản có giải quyết 80% pain chưa hay cần AI?" | Giúp nhóm suy nghĩ kỹ hơn về fallback và tránh over-engineer. Một số bạn điều chỉnh lại phương án sau câu hỏi này. |
| Gom trùng / cluster | Đề xuất gom Card #1 (khách chờ mù mịt) và Card #3 (bếp tự quyết thứ tự) thành 1 cluster vì cùng liên quan đến trải nghiệm chờ đợi của khách — bếp không có rule → khách chờ lâu → không có thông tin. | Nhóm nhận ra 2 problem này có mối quan hệ nhân quả, giúp thu hẹp shortlist hiệu quả hơn. |
| Chọn candidate problem | Bỏ phiếu cho Card #1 vì pain lớn nhất, actor rõ, evidence mạnh nhất (review Google Maps, bàn bỏ về). Giải thích vì sao Card #2 (món hết) có thể giải bằng rule đơn giản nên nên ưu tiên bài có room cho AI hơn. | Nhóm đồng thuận chọn bài "khách chờ mù mịt" làm candidate chính. |
| Validation / research | Phỏng vấn 2 NV phục vụ tại quán: cả 2 xác nhận "mỗi ca tối mất gần nửa tiếng chỉ chạy vào bếp hỏi rồi chạy ra trả lời khách". Thu thập 3 review Google Maps có đề cập "chờ lâu", "không biết bao giờ có đồ ăn". | Cung cấp quote thật cho nhóm, xác nhận pain không phải do tưởng tượng mà có evidence rõ ràng từ cả NV lẫn khách. |
| Workflow nhóm | Vẽ current workflow 7 bước chi tiết (từ order → hiện bếp → bếp làm → khách chờ → hỏi NV → NV chạy bếp → lặp lại) và future workflow 7 bước (thêm AI ước tính thời gian + trạng thái tự động trên QR). | Workflow trước/sau được nhóm dùng làm nền cho Problem Statement, có thời gian mỗi bước + bottleneck + fallback. |
| Problem Statement | Viết draft PS v0 phần Actor và Workflow, chỉ rõ 3 actor (khách, NV, quản lý) và mô tả workflow bottleneck. Đề xuất success metric: giảm số lần hỏi NV từ 10-15/ca xuống dưới 3. | Phần Actor và Workflow trong PS v0 giữ nguyên cấu trúc tôi đề xuất, nhóm bổ sung thêm boundary và metric. |
| Rule / Workflow / Agent | Phân tích so sánh: Rule (hiện trạng thái cố định) giải 60-70% — đủ cho khách biết "đang nấu" nhưng không biết "còn bao lâu". Workflow (AI ước tính thời gian) giải 80-90%. Agent quá phức tạp cho bài này. Đề xuất chọn Workflow. | Nhóm đồng ý chọn Workflow, dùng lập luận của tôi về việc Rule thiếu khả năng ước tính thời gian cá nhân hóa. |
| Decision | Đề xuất Go với pilot: thử 1 tuần tại 1 ca tối, đo 3 số (số lần khách hỏi NV, thời gian NV mất cho việc hỏi bếp, số bàn bỏ về). Đề xuất exit criteria: nếu sau 2 tuần không giảm ≥50% số lần hỏi → rollback về Rule đơn giản. | Nhóm chấp nhận pilot plan và exit criteria, đưa vào artifact cuối. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Workflow trước/sau 7 bước với thời gian cụ thể và fallback là phần tôi vẽ và defend xuyên suốt. Ngoài ra, success metric "giảm số lần hỏi NV từ 10-15/ca xuống dưới 3" và exit criteria cho pilot cũng do tôi đề xuất dựa trên dữ liệu thực tế từ quán.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI gợi ý thêm problems theo 4 lăng kính sau khi tự scan được 8 bài. Prompt: "Tôi là quản lý quán ăn, dùng QR + NV nhập POS. Pain lớn nhất giờ cao điểm là khách chờ quá lâu. Gợi ý thêm problem liên quan." | AI gợi ý được 2 ý hay: khách không biết thời gian chờ ước tính (#10) và dự đoán lượng khách (#9) — cả hai đều đúng pain thực tế ở quán. | AI gợi ý "chatbot Zalo" — quán chưa có kênh online. Gợi ý "robot bưng đồ" — quá xa vời với quy mô quán nhỏ. AI không biết context thực tế nên đề xuất solution quá high-tech. | Loại bỏ 2 ý không thực tế (chatbot Zalo, robot). Giữ 2 ý phù hợp (#9, #10) và tự bổ sung bằng chứng số liệu từ kinh nghiệm vận hành thực tế. |
| Problem Card | Hỏi AI phản biện Card #1: "Điểm yếu nào trong workflow này?" | AI chỉ đúng: bếp bận thêm bước bấm cập nhật → có thể tạo bottleneck mới. Và: cần dữ liệu lịch sử mà quán mới dùng POS thì chưa có. | AI không đề cập chi phí triển khai và khả năng bếp tuân thủ lâu dài — 2 yếu tố quan trọng trong thực tế vận hành. | Thêm phương án fallback: nếu bếp không kịp bấm, dùng rule thời gian tự động (order vào 5' → "đang nấu", 15' → "sắp xong"). AI ước tính chính xác là bước nâng cấp sau khi có đủ data. |
| Workflow | Hỏi AI gợi ý cách vẽ future workflow cho bài "ước tính thời gian chờ". | AI gợi ý đúng flow: order → AI tính thời gian → hiển thị trên QR → bếp bấm xong → AI cập nhật. Logic hợp lý. | AI vẽ workflow quá lý tưởng, bỏ qua trường hợp bếp quên bấm, wifi QR lag, hoặc khách không quen dùng QR. | Thêm fallback cho mỗi bước: bếp quên bấm → NV nhắc; QR lag → NV thông báo miệng; AI sai → hiện trạng thái đơn giản không có số phút. |
| Research | Hỏi AI tìm tool/case study về kitchen display system (KDS) và order tracking. | AI giới thiệu đúng các tool: Toast KDS, Square KDS, FreshKDS — đều có tính năng hiển thị trạng thái order cho bếp. | AI đưa ra số liệu "giảm 30% thời gian chờ" nhưng không có link source verify được. Một số tool AI nói có tính năng ước tính thời gian nhưng kiểm tra thực tế thì chưa có. | Chỉ giữ thông tin verify được từ website chính thức của các tool. Bỏ số liệu không có nguồn. Ghi rõ "giả định chưa chắc" cho các claim chưa kiểm chứng. |
| Problem Statement | Hỏi AI review PS v0: "Field nào mơ hồ, cần sửa gì?" | AI chỉ ra boundary chưa rõ: "Làm gì / không làm gì" cần cụ thể hơn (VD: không làm recommendation món, chỉ làm tracking). | AI gợi ý thêm quá nhiều metric phụ (NPS score, retention rate) — không phù hợp với pilot nhỏ ở 1 quán ăn. | Giữ lại góp ý về boundary, bổ sung rõ "làm: tracking trạng thái + ước tính thời gian; không làm: recommendation, loyalty, payment". Bỏ metric phụ, chỉ giữ 3 metric chính đo được ngay. |
| Rule / Workflow / Agent | Hỏi AI so sánh 3 mức cho bài toán ước tính thời gian chờ. | AI phân tích đúng: Rule đơn giản (trạng thái cố định) giải 60-70%, Workflow (AI ước tính) giải 80-90%, Agent quá phức tạp cho bài này. | AI có xu hướng đẩy lên Agent ("dùng Agent để tự điều phối bếp") — giải pháp quá phức tạp và rủi ro cao cho quán ăn nhỏ. | Kéo về Workflow, lập luận: bài toán có input rõ (số order, độ phức tạp, tốc độ bếp), output rõ (thời gian ước tính), không cần Agent tự lập kế hoạch hay gọi tool. |
| Decision | Hỏi AI kiểm tra logic Go/Not Yet/No-Go. | AI xác nhận logic Go hợp lý: có actor rõ, metric đo được, pilot plan khả thi, exit criteria rõ. | AI không challenge đủ mạnh: không hỏi "nếu pilot fail thì sao?", không đề cập rủi ro bếp phản đối thay đổi quy trình. | Tự thêm exit criteria: nếu sau 2 tuần không giảm ≥50% số lần hỏi → rollback. Thêm mitigation: training bếp 30 phút trước khi pilot, cho bếp thử 2 ngày trước khi đo chính thức. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?

**Reflection:**

```text
Khi nghe top 3 problems của các bạn khác, tôi nhận ra một điều thú vị: dù
domain khác nhau (quán ăn, bán lẻ, dịch vụ), nhưng pattern pain rất giống
nhau — đều xoay quanh việc thông tin không đến đúng người, đúng lúc, và con
người phải làm cầu nối thủ công. Điều này giúp tôi tự tin hơn rằng bài toán
"khách chờ mù mịt" không phải chỉ là pain riêng của quán tôi mà là pattern
chung, nghĩa là solution có thể scale được.

Nhóm tôi có một lúc bị solution-first khá rõ: khi mới bắt đầu Phase 3, có
bạn đề xuất luôn "xây Agent tự điều phối bếp, tự nhắn tin khách qua Zalo"
— nghe rất ngầu nhưng khi hỏi lại "bước nào là bottleneck, đo bằng gì" thì
chưa trả lời được. Tôi đã challenge bằng câu hỏi: "Rule đơn giản — bếp bấm
nút, khách thấy trạng thái — có giải 80% pain chưa?" Câu hỏi này kéo nhóm
quay lại đúng quy trình: pain trước, solution sau.

Tôi có thay đổi ý kiến sau khi bị challenge. Ban đầu tôi muốn AI ước tính
thời gian chờ chính xác từng phút, nhưng một bạn hỏi: "Bếp bận lắm rồi,
thêm bước bấm cập nhật, liệu có làm không?" Câu hỏi này đúng chỗ yếu. Tôi
suy nghĩ lại và thêm fallback: dùng rule thời gian tự động (5' → đang nấu,
15' → sắp xong) để không phụ thuộc 100% vào bếp bấm. Nhờ bị challenge mà
solution thực tế hơn nhiều.

Điều khó nhất khi viết Problem Statement là boundary — xác định "làm gì" thì
dễ, nhưng "không làm gì" mới khó. Tôi phải tự hỏi: "Nếu thêm feature này
vào scope thì pilot có chạy được trong 1 tuần không?" để giữ scope nhỏ. Cuối
cùng boundary rõ: chỉ làm tracking trạng thái + ước tính thời gian, không làm
recommendation, loyalty, hay payment. Metric cũng mất công: phải chọn số đo
được ngay (số lần hỏi NV/ca, thời gian NV mất, số bàn bỏ về) thay vì metric
hay nhưng không đo nổi (customer satisfaction score).
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
