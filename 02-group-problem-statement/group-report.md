# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
                   
1   Nguyễn Minh Kiệt    2A202602373 Lead
2   Đào Minh Hiếu   2A202602561    writer
3   Nguyễn Gia Khánh    2A202602851 workflow
4     Phạm Khắc Tú    2A202602866 research
5   Thân THị Kim Chi    2A202602797 writer
6   Đông Mạnh Hùng  2A202602412 writer

**Candidate problem nhóm chọn (1 câu):**



## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)
| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Đồng Mạnh Hùng | Thẩm định và tóm tắt review thật/ảo khi mua hàng giá trị cao trên Shopee | Người mua đồ công nghệ/gia dụng online | Tốn 30–45' đọc lọc review seeding, rác và so khớp giá sau voucher giữa các shop | Ý tưởng gần gũi; thách thức lớn ở tầng crawl dữ liệu và anti-bot của Shopee; nên làm browser extension |
| 2 | Đồng Mạnh Hùng | Quét và phát hiện thành phần gây dị ứng/kích ứng trên bao bì mỹ phẩm qua ảnh | Người có da nhạy cảm / dễ kích ứng | Gõ tay từng tên hóa học khó nhớ lên Google để tra cứu mức độ an toàn | Điểm nghẽn gọn gàng, workflow rõ (OCR + Database tra cứu); giá trị tức thì, dễ demo |
| 3 | Đồng Mạnh Hùng | Đối chiếu tài liệu đặc tả (spec) với mã nguồn API thực tế trước khi release/demo | Lập trình viên, sinh viên làm đồ án phần mềm | Mất 45–60' lật giở từng trang spec để dò từng field, status code trong file controller/schema | Bài toán kỹ thuật rõ ràng, input/output text/code chuẩn; cần thu hẹp vào 1-2 file schema thay vì cả repo |
| 4 | Nguyễn Minh Kiệt | Theo dõi tiến độ và quản trị thay đổi đa nguồn (staff, nhà thầu, cổ đông, cơ quan quản lý) | Project Coordinator, Quản lý dự án | Mất 2–3h/tuần đối soát thủ công nhiều định dạng báo cáo không đồng nhất để gom tiến độ | Pain thật của doanh nghiệp/dự án lớn; dữ liệu đa nguồn khó chuẩn hóa, phụ thuộc nhiều vào quy trình nhập liệu |
| 5 | Nguyễn Minh Kiệt | Theo dõi thay đổi thủ tục, quy chuẩn pháp lý và giấy phép chuyên ngành | Cán bộ pháp chế, điều phối viên xin cấp phép | Khó rà soát sự thay đổi của quy trình, biểu mẫu sau khi cơ quan ban ngành sáp nhập/tái cơ cấu | Giá trị compliance cao nhưng tần suất xảy ra thấp; thiếu log số liệu cụ thể để đo lường ROI |
| 6 | Nguyễn Minh Kiệt | Thất lạc ngữ cảnh, tri thức dự án khi nhân sự bàn giao hoặc nghỉ việc | Nhân sự mới tiếp nhận dự án, PM | Mất nhiều giờ đào bới hàng chục biên bản họp tuần, email cũ để tìm lại một quyết định then chốt | Bài toán Knowledge Base kinh điển; giải quyết tốt bằng RAG trên tài liệu nội bộ, ranh giới AI rõ ràng |
| 7 | Phạm Khắc Tú | Tự động kiểm tra repository mã nguồn đã đủ điều kiện nộp/bàn giao hay chưa | Sinh viên làm đồ án, lập trình viên nộp bài | Mất thời gian rà soát checklist thủ công (cấu trúc thư mục, test coverage, file bắt buộc) | Cực kỳ rõ ràng, dễ đo baseline; rule engine xử lý được 80% cấu trúc, LLM chỉ cần đọc hiểu README/semantic |
| 8 | Phạm Khắc Tú | Tìm kiếm và xác minh yêu cầu nằm rải rác trong tài liệu quy chế/hướng dẫn dài hàng nghìn dòng | Sinh viên, nhân viên tra cứu quy chế nội bộ | Lạc lối giữa hàng chục trang/heading, mất 15–30' chỉ để kiểm chứng một điều kiện tín chỉ/chính sách | Bằng chứng rõ (1.305 dòng/83 heading); có nguy cơ chỉ cần mục lục/search tốt là đủ, cần chứng minh giá trị của AI |
| 9 | Phạm Khắc Tú | Tổng hợp quyết định và phân bổ đầu việc nhóm bị phân tán sau các buổi thảo luận | Thành viên làm việc nhóm, nhóm trưởng | Mất thời gian recap, dễ sót việc hoặc lệch phiên bản task khi copy qua lại giữa chat và task board | Pain rất phổ biến; human boundary tự nhiên (AI chỉ soạn dự thảo task, người bấm giao), dễ thử nghiệm ngay |
| 10 | Nguyễn Gia Khánh|Tự luyện Speaking một mình, dễ bị bí ý tưởng và không phát hiện được lỗi sai về phát âm hay ngữ điệu | Actor và impact rõ, đo được bằng thời gian nghĩ (10-15 phút) và số lần thu âm vô ích; nút thắt nằm ở việc nghe lại record nhưng không biết sai chỗ nào để sửa | Công cụ AI có nhận diện chính xác được lỗi phát âm và nhấn âm đặc thù (accent) của người Việt hay không, hay chỉ sửa được ngữ pháp bề mặt |
| 11 | Nguyễn Gia Khánh| Tinh chỉnh các tham số xử lý ảnh (thresholding, Canny, contour) trên nhiều điều kiện sáng khác nhau | Workflow rõ ràng (sửa tham số -> chạy code -> kiểm tra mắt thường); tiết kiệm 2-3 giờ/ngày cho việc thử sai lặp lại | Thuật toán auto-tuning hoặc heuristic có bao quát được mọi trường hợp nhiễu sáng thực tế hay vẫn cần người can thiệp |
| 12 |Nguyễn Gia Khánh| Mất quá nhiều thời gian tìm từ đồng nghĩa và cấu trúc để paraphrase khi viết luận | Workflow rõ, nút thắt ở khâu tra cứu từ điển nhiều lần làm ngắt quãng mạch viết; đo được bằng thời gian 10-15 phút cho một đoạn mở bài | Nếu công cụ làm thay việc paraphrase hoàn toàn thì người học có ghi nhớ được từ vựng không, văn phong có bị máy móc |
| 13 | Thân Thị Kim Chi| Soát lỗi và đối chiếu bài làm với rubric/checklist tiêu chí nộp bài trước deadline | Workflow rõ ràng, lặp lại hàng tuần; nút thắt đối chiếu thủ công dễ bấm giờ; tránh bị trừ điểm oan do thiếu mục hình thức | Cách đánh giá chất lượng các câu hỏi tự luận mở có thể cần tiêu chí linh hoạt hơn là so khớp cứng |
| 14 | Thân Thị Kim Chi|Tạo bộ câu hỏi trắc nghiệm và tình huống ôn tập từ slide bài giảng | Nhu cầu ôn thi thực tế cao; nút thắt ở khâu chuyển đổi lý thuyết thành câu hỏi tình huống; đo được bằng độ phủ kiến thức trong tài liệu | Cần kiểm soát để AI không tạo câu hỏi quá dễ hoặc bịa thêm kiến thức ngoài phạm vi bài học |
| 15 | Thân Thị Kim Chi|Tìm kiếm câu trả lời chính thức, tài liệu và quyết định cũ bị trôi trong kênh chat Discord/Zalo | Tần suất xảy ra cao (3-4 lần/tuần); giải quyết hạn chế của tìm kiếm từ khóa thông thường nhờ khả năng hiểu ngữ cảnh | Vấn đề phân quyền truy cập dữ liệu cá nhân và giới hạn API trích xuất tin nhắn của các nền tảng |
| 16 | Đào Minh Hiếu| Khách chờ 20-30 phút không biết bếp làm tới đâu, liên tục gọi nhân viên hỏi dồn | Pain point hàng ngày, actor rõ ràng; đo được bằng số lần hỏi/ca và phản ánh trên review Google Maps | Ước tính thời gian chờ bằng AI có thực sự khả thi không, hay chỉ cần bảng trạng thái đơn giản (đã nhận / đang nấu / sắp xong) |
| 17 | Đào Minh Hiếu|Khách quét mã QR gọi món đã hết, phải chọn lại do quản lý quên cập nhật | Trải nghiệm gọi món bị đứt gãy ngay từ đầu; bằng chứng rõ qua review 1-2 sao; workflow ngắn | Rule đơn giản như bếp bấm nút hết món có thể đã giải quyết xong, chưa chắc cần đến giải pháp AI phức tạp |
| 18 | Đào Minh Hiếu|Bếp tự quyết thứ tự làm order, dẫn đến bàn đến trước lại ra món sau | Nguyên nhân gốc rễ khiến khách chờ lâu; workflow khu vực chế biến rõ ràng; đo được thời gian lệch đơn | Thuật toán xếp hàng chuẩn FIFO đã giải quyết được phần lớn vấn đề chưa, hay cần tối ưu lộ trình nấu phức tạp |
### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Hỗ trợ học tập & Ôn luyện cá nhân | #10 (Luyện Speaking), #12 (Paraphrase Writing), #14 (Tạo câu hỏi trắc nghiệm ôn thi) | Tự học gặp nút thắt ở khâu phản hồi sửa sai (feedback loop) và tạo tư liệu tự kiểm tra (active recall) từ tài liệu sẵn có. | Phù hợp làm công cụ trợ giảng AI; rủi ro nằm ở việc AI đánh giá phát âm tiếng Anh chưa chuẩn hoặc bịa kiến thức ngoài slide. |
| B. Quản trị tri thức, Quy chế & Phối hợp nhóm | #4 (Tiến độ đa nguồn), #5 (Thay đổi thủ tục pháp lý), #6 (Bàn giao tri thức), #8 (Tra cứu quy chế dài), #9 (Recap task từ thảo luận), #15 (Tìm tin trôi trên Discord/Zalo) | Dữ liệu văn bản phi cấu trúc bị phân tán nhiều nơi; tốn nhiều giờ đọc lướt, đào bới để tìm đúng quyết định/quy định cũ hoặc tổng hợp đầu việc. | Ứng dụng RAG và tóm tắt văn bản rất tự nhiên; rào cản chính là quyền truy cập dữ liệu (chat/file nội bộ) và chuẩn hóa input. |
| C. Đối soát kỹ thuật, Kiểm tra chuẩn nộp bài & Tối ưu Dev | #3 (Đối chiếu Spec với API), #7 (Kiểm tra repo đủ điều kiện nộp), #11 (Tinh chỉnh tham số Computer Vision), #13 (Soát lỗi bài làm theo Rubric) | Đối chiếu tự động giữa 1 bộ tiêu chuẩn định trước (spec/checklist/rubric/ground truth) với sản phẩm thực tế (code/bài làm/ảnh). | Điểm nghẽn cực rõ, đo lường được baseline thời gian; kết hợp hoàn hảo giữa Rule Engine (kiểm tra cứng) và AI (kiểm tra semantic). |
| D. Tối ưu vận hành & Trải nghiệm dịch vụ thực tế | #1 (Thẩm định review Shopee), #2 (Quét thành phần mỹ phẩm), #16 (Khách đợi món gọi NV), #17 (QR hết món), #18 (Thứ tự ra món ở bếp) | Tối ưu các điểm chạm thực tế giữa khách hàng và dịch vụ; giảm thời gian chờ đợi hoặc tra cứu thông tin sản phẩm. | Nhiều ý tưởng trong cụm này có thể giải quyết dứt điểm bằng quy trình hoặc Rule-based (như KDS, nút bấm hết món) mà chưa cần đến AI. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #1. Thẩm định & tóm tắt review thật/ảo khi mua hàng giá trị cao trên Shopee | 1. Tác động lớn và gần gũi với số đông người dùng; giải quyết trực tiếp tình trạng quá tải thông tin và bẫy seeding review. 2. Nút thắt đo lường được bằng thời gian (cắt giảm từ 45-60 phút lướt tab xuống dưới 5-8 phút xem tóm tắt). 3. Khung phân tích rõ ràng: trích xuất lỗi thực tế của sản phẩm từ review 1-3 sao và so khớp giá sau voucher chéo shop. | Cơ chế anti-bot và chặn crawl dữ liệu của Shopee rất gắt gao (cần giải quyết bằng Browser Extension thay vì server crawl); khó bóc tách review khen/chê tinh vi dùng tiếng lóng. |
| #7. Tự động kiểm tra repository mã nguồn đã đủ điều kiện nộp/bàn giao hay chưa | 1. Actor và ranh giới bài toán cực kỳ rõ ràng; input là repo Git, output là checklist đạt/không đạt kèm nguyên nhân. 2. AI-Fit hợp lý và thực tế: Rule engine quét 80% cấu trúc thư mục, test coverage, file bắt buộc; LLM chỉ đọc hiểu semantic ở file README và tài liệu hướng dẫn. 3. Dễ dựng test dataset (các repo sinh viên cố tình cài lỗi) để đo đạc và kiểm thử ground truth. | Baseline đo lường thực tế còn ít mẫu; cần xác định rõ ranh giới lỗi nào thực sự cần LLM đọc hiểu ngữ nghĩa thay vì chỉ dùng regex/linter cứng. |
| #13. Soát lỗi và đối chiếu bài làm với rubric/checklist tiêu chí nộp bài trước deadline | 1. Nhu cầu thực tế cao, lặp lại hàng tuần theo từng đồ án/assignment của sinh viên. 2. Nút thắt nằm ở việc so sánh đối chiếu từng tiêu chí định lượng/định tính, dễ đo thời gian tiết kiệm được. 3. Giảm thiểu rủi ro mất điểm oan do thiếu mục, sai format quy định. | Khó chuẩn hóa việc chấm các câu trả lời tự luận mở (open-ended); LLM dễ bị thiên vị (bias) hoặc quá khắt khe/quá lỏng lẻo nếu rubric viết chung chung. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1. Thẩm định & tóm tắt review thật/ảo trên Shopee | 5 | 5 | 5 | 5 | 4 | 5 | 5 | 34 |
| #7. Tự động kiểm tra repo đủ điều kiện nộp | 5 | 5 | 4 | 4 | 5 | 4 | 5 | 32 |
| #13. Soát lỗi bài làm theo Rubric/Checklist | 4 | 4 | 4 | 4 | 4 | 4 | 5 | 29 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Thẩm định và tóm tắt review thật/ảo trên Shopee
```

**Vì sao chọn (4-5 câu):**

```text
Ý tưởng thẩm định sản phẩm Shopee giải quyết nỗi đau nhức nhối và xảy ra liên tục của tất cả thành viên trong nhóm mỗi khi mua sắm các mặt hàng giá trị cao. 
Nút thắt của quy trình thể hiện rất tập trung tại khâu mở hàng chục cửa hàng để đọc lọc review seeding, rác và tính nhẩm giá thực tế sau các tầng voucher. 
Chỉ số thành công đo lường được trực tiếp bằng thời gian ra quyết định mua hàng, cắt giảm từ 45-60 phút lướt tab xuống dưới 5-8 phút đọc bảng tóm tắt lỗi thực tế. 
Đề tài này cho phép so sánh ranh giới Rule - Workflow - Agent vô cùng rõ nét (Rule lọc từ khóa rác -> Workflow trích xuất ưu nhược điểm -> Agent hỗ trợ đối chiếu giá chéo shop). 
Nhóm có thể triển khai khả thi trong khuôn khổ lab bằng hình thức Browser Extension để đọc dữ liệu DOM trực tiếp, vừa né được rào cản anti-bot vừa cá nhân hóa được voucher theo tài khoản người dùng.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Candidate #7 (Kiểm tra repo đủ điều kiện nộp): 
Phần lớn các tiêu chí kiểm tra (cấu trúc thư mục, test coverage, file bắt buộc) giải quyết triệt để và hiệu quả hơn bằng bash script hoặc GitHub Actions linter truyền thống. 
Giá trị thực sự của AI chỉ chiếm một phần rất nhỏ ở việc đọc hiểu semantic file README, khiến bài toán có xu hướng over-engineering và không làm nổi bật được sức mạnh cốt lõi của LLM/Workflow.

Candidate #13 (Soát lỗi bài làm theo Rubric/Checklist): 
Các tiêu chí chấm điểm trong rubric thực tế thường chứa nhiều yêu cầu định tính, mở và trừu tượng (như tính sáng tạo, độ mạch lạc), dẫn đến khó xây dựng tập ground-truth để đánh giá mức độ chính xác của AI trong lab. 
Ngoài ra, rủi ro AI bị bias hoặc hallucination khi chấm các câu hỏi tự luận có thể gây hiểu lầm tai hại cho người học trước thời điểm nộp bài chính thức.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Không có
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 người (mua đồ công nghệ, gia dụng online) | - "Mình lướt 10 shop thấy review khen y hệt nhau từng dấu chấm phẩy, phải mò xuống tận mấy cái 1-2 sao đọc xem hỏng vặt gì mới dám mua." (Nam, 22 tuổi) - "Nhiều khi áp mã xong bên shop A tưởng rẻ hơn nhưng cộng phí ship với bẫy voucher ảo lại đắt hơn bên shop Mall kia." (Nam, 21 tuổi) | Có 1 người phản hồi: Nếu món đồ dưới 60k (như ốp lưng, tất vớ) thì cứ bấm mua shop rẻ nhất hoặc nhiều lượt bán nhất chứ không bao giờ tốn quá 2 phút để đọc review. | Thu hẹp phạm vi bài toán: Chỉ tập trung giải quyết phân khúc sản phẩm có rủi ro cao (giá trị từ 300.000 VNĐ trở lên như đồ gia dụng, tai nghe/chuột máy tính, mỹ phẩm) thay vì mọi mặt hàng tạp phẩm. |
| Survey / poll | 6 người (sinh viên, người đi làm) | 5/6 người (83.3%) xác nhận mất trung bình từ 30-45 phút mỗi lần cân nhắc một món đồ công nghệ/gia dụng trên sàn TMĐT; 4/6 người có thói quen lọc thẳng vào mục "1 sao" và "Có hình ảnh/video" để đọc lỗi. | 2/6 người không quan tâm đến tính năng so sánh voucher chéo sàn vì họ chỉ có thói quen tích lũy voucher ở một shop quen hoặc tài khoản phụ. | Định vị ưu tiên hàng đầu là tính năng "Bóc tách lỗi thực tế & lọc review seeding" trước, tính năng so khớp giá sau voucher xếp ở mức phụ trợ (secondary). |
| Log / ticket / review (nếu có) | 20 bài thảo luận trên group Facebook "Hội săn sale Shopee / Cháy túi vì Shopee" | Hơn 15 bài đăng hỏi dạng: "Mọi người cho em hỏi bàn phím/nồi chiên này dùng lâu có bị lỗi pin/bong tróc không chứ review trên sàn toàn khen lấy xu, đánh giá 5 sao giao nhanh chứ chưa dùng thử." | Người dùng có xu hướng tin tưởng review của KOL/KOC trên TikTok hoặc hội nhóm chuyên môn hơn là tự đọc review trên sàn TMĐT. | AI không chỉ tóm tắt review tại trang sản phẩm đó mà cần trích xuất theo các thuộc tính độ bền (độ bền sau 1-3 tháng, lỗi phần cứng hay gặp) để trả lời đúng băn khoăn của người mua. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain point lớn nhất không phải là thiếu thông tin mà là khủng hoảng niềm tin: người mua bị ngợp trước hàng nghìn đánh giá 5 sao rác "nhận xu/giao hàng nhanh", buộc phải tốn 30-45 phút đào bới review 1-3 sao để tìm lỗi hỏng thực tế của sản phẩm trước khi dám xuống tiền.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

### 4.2. Research giải pháp đã có

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| SureVett – Amazon Fake Review Checker | [Chrome Web Store](https://chromewebstore.google.com/detail/surevett-%E2%80%94…e-re/mnalgdledjhghibknfpodihinoajiehi) | Phân tích độ tin cậy của review Amazon và phát hiện các tín hiệu review bất thường. | Trust Grade A–F trực quan; giải thích lý do chấm điểm; phân tích rating distribution, review velocity, seller trust và các tín hiệu sản phẩm. | Chỉ tập trung vào Amazon; chủ yếu dựa trên tín hiệu thống kê/heuristic và chưa chuyên sâu cho ngữ nghĩa review tiếng Việt hoặc Shopee/Lazada. | Học mô hình review reliability score có giải thích, nhưng cần kết hợp NLP/LLM để xử lý review tiếng Việt và các hành vi review bất thường đặc thù TMĐT Việt Nam. |
| Shopee Price & Review Tracker | [Chrome Web Store](https://chromewebstore.google.com/detail/shopee-price-revie…rack/loenjcjcpdohihgejhobodfdccjlbkgo) | Theo dõi lịch sử giá và hỗ trợ phân tích đánh giá sản phẩm trực tiếp trên Shopee. | Tích hợp trực tiếp dưới dạng Browser Extension; hoạt động ngay trên trang Shopee; kết hợp thông tin giá và review trong cùng trải nghiệm mua sắm. | Quy mô người dùng còn nhỏ; chưa công khai rõ phương pháp phân tích review và chưa thể hiện khả năng phát hiện review đáng ngờ hoặc trích xuất lỗi sản phẩm chuyên sâu. | Học kiến trúc Browser Extension tích hợp trực tiếp vào product page, nhưng bổ sung pipeline NLP/LLM để phân tích review sâu hơn và đưa ra insight rõ ràng. |
| Amazon Alexa for Shopping (formerly Rufus) | [About Amazon](https://www.aboutamazon.com/news/retail/alexa-for-shopping-ai-assistant) | AI assistant hỗ trợ tìm hiểu, so sánh, hỏi đáp và tổng hợp thông tin sản phẩm dựa trên catalog, review, lịch sử mua sắm và các nguồn web. | Có khả năng tổng hợp lượng lớn thông tin sản phẩm; tạo product insight, so sánh sản phẩm, cá nhân hóa recommendation và hỗ trợ người dùng ra quyết định mua hàng. | Khép kín trong hệ sinh thái Amazon; thiên về conversational shopping assistant và không được thiết kế riêng cho việc phát hiện review đáng ngờ trên Shopee/Lazada Việt Nam. | Học khả năng review summarization + aspect extraction + product comparison, nhưng nên đưa insight ra widget trực tiếp để người dùng xem kết luận nhanh mà không cần hội thoại nhiều bước. |


**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nên build một Browser Extension gọn nhẹ, tự động đọc DOM trang Shopee hiện tại để phân tích và hiển thị trực tiếp một thẻ tóm tắt gồm 2 mục cốt lõi: tỷ lệ review nghi vấn seeding và danh sách các lỗi hỏng/nhược điểm thực tế gom từ đánh giá 1-3 sao. 
Không build chatbot trò chuyện hỏi đáp qua lại rườm rà, không dựng hệ thống server crawl tập trung dễ bị Shopee chặn IP, và không cố ôm đồm tính năng so sánh voucher phức tạp ở giai đoạn MVP.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
CURRENT WORKFLOW — 45 phút

[1 Tìm kiếm & lọc sơ bộ: 2' - Người mua] → [2 Mở 5-7 tab so sánh: 5' - Người mua] → [3 Lướt qua bẫy seeding/review nhận xu: 15' - Người mua] → [4 Đào bới review 1-3 sao tìm lỗi thực tế: 20' - Người mua (bottleneck)] → [5 Tính giá và chốt: 3' - Người mua]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Người mua hàng | Từ khóa sản phẩm cần mua (100k) | Danh sách kết quả tìm kiếm trên sàn TMĐT | 2' / mỗi đợt mua | Dễ bị nhiễu bởi các vị trí tài trợ (quảng cáo) và shop đặt giá mồi |
| 2 | Người mua hàng | Danh sách kết quả tìm kiếm | 5–7 tab sản phẩm từ các shop khác nhau | 5' / mỗi đợt mua | Mở nhiều tab để đối chiếu lượt bán, nhãn Mall và đánh giá sao trung bình |
| 3 | Người mua hàng | Đánh giá 5 sao tại từng tab sản phẩm | Ấn tượng sơ bộ về sản phẩm | 15' (3' x 5 tab) | Bị ngợp bởi đánh giá seeding rác, copy-paste bài hát/ký tự lạ để nhận xu Shopee |
| 4 | Người mua hàng | Bộ lọc đánh giá 1-3 sao, đánh giá có ảnh/video | Danh sách nhược điểm, lỗi hỏng thực tế của sản phẩm | 20' (4' x 5 tab) | Bottleneck chính: Phải đọc từng dòng để phân biệt lỗi sản phẩm thực tế hay do vận chuyển |
| 5 | Người mua hàng | Giá niêm yết, voucher shop, voucher sàn, phí ship | Lựa chọn shop tối ưu nhất và chốt đơn | 3' / mỗi đợt mua | Quyết định mua hoặc bỏ cuộc nếu phát hiện lỗi nghiêm trọng ở bước 4 |

**Bottleneck chính (2-3 câu):**

```text
Nút thắt cổ chai nằm ở Bước 4 khi người mua phải tốn tới 30-40 phút lội qua hàng chục trang đánh giá 1-3 sao để bóc tách lỗi kỹ thuật và độ bền thực tế của sản phẩm. Người dùng bị quá tải thông tin vì phải tự mình phân biệt đâu là lỗi hỏng do chất lượng linh kiện, đâu là đánh giá tiêu cực cảm tính do bên vận chuyển giao chậm hoặc khách không đọc kỹ hướng dẫn sử dụng. Việc phải lặp lại thao tác đào bới thủ công này trên 5-7 tab khác nhau gây mệt mỏi và làm tê liệt khả năng ra quyết định mua sắm.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 Người mua mở 1 trang sản phẩm Shopee: 10s - Người] 
→ [2 Rule parse DOM trích xuất text/ảnh review & lọc rác cơ bản: 5s - Máy (Rule)] 
→ [3 LLM phân loại review seeding và gom cụm lỗi thực tế: 15s - AI] 
→ [4 Người mua duyệt bảng tóm tắt lỗi & điểm tin cậy: 2' - Người (Human boundary)] 
→ [5 Quyết định chốt đơn hoặc bỏ qua: 30s - Người]

Fallback: Nếu Shopee đổi class DOM không parse được hoặc LLM fail/trả kết quả rỗng, extension tự động hạ cấp (fallback) về chế độ hiển thị danh sách trích xuất thô của 10 đánh giá 1-3 sao gần nhất mà không qua xử lý tóm tắt.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 45 phút | 3-4 phút | Bấm giờ từ lúc mở trang sản phẩm đến khi đưa ra quyết định mua hay đổi shop |
| Số bước | 5 bước | 5 bước | Đếm số bước theo sơ đồ quy trình |
| Số bước thủ công | 5 bước | 3 bước | Đếm số bước cần người dùng thao tác trực tiếp |
| Bottleneck chính | 20 phút | 2 phút | Đo riêng thời gian đọc hiểu, bóc tách lỗi từ tập review 1-3 sao |
| Risk mới | Không có (chỉ mất thời gian cá nhân) | AI tóm tắt sót lỗi phần cứng nghiêm trọng hoặc bịa lỗi không có thật | So sánh ngẫu nhiên 20 kết quả tóm tắt của AI với nội dung review gốc |
### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người mua sắm trực tuyến cá nhân trên Shopee có nhu cầu mua các mặt hàng giá trị từ 100.000 VNĐ trở lên (đồ điện tử, gia dụng, mỹ phẩm). Đây là nhóm người dùng nhạy cảm với rủi ro hàng lỗi, hàng giả và có thói quen đọc kỹ đánh giá trước khi chi tiền. |
| **Workflow** | Người dùng tìm kiếm sản phẩm, mở 5-7 gian hàng tương tự để so sánh, sau đó lướt qua hàng trăm review để phân biệt đánh giá seeding ảo với trải nghiệm thực tế. Cuối cùng, họ lọc riêng review 1-3 sao nhằm tìm ra các lỗi hỏng phổ biến trước khi tính giá và chốt đơn. |
| **Bottleneck** | Điểm nghẽn nằm ở khâu đọc và thẩm định thủ công hàng loạt đánh giá bị nhiễu loạn bởi review rác lấy xu và bẫy seeding thuê. Người mua mất 20-30 phút chỉ để lọc ra vài đánh giá tiêu cực thực chất nhằm phân biệt lỗi sản phẩm hay lỗi do vận chuyển. |
| **Impact** | Gây lãng phí từ 45 đến 60 phút cho mỗi phiên mua sắm, dẫn đến tâm lý mệt mỏi và tê liệt khả năng ra quyết định. Đáng lo ngại hơn, người dùng vẫn có nguy cơ mua phải sản phẩm kém chất lượng do tin nhầm vào các cụm đánh giá 5 sao ảo được dàn dựng tinh vi. |
| **Success Metric** | Cắt giảm thời gian thẩm định đánh giá và ra quyết định mua hàng từ 45 phút xuống dưới 5 phút cho mỗi sản phẩm. Bảng tóm tắt lỗi của AI đạt độ chính xác trên 85% khi đối chiếu với nội dung thực tế của tập review 1-3 sao gốc. |
| **Boundary** | AI chỉ đóng vai trò trợ lý trích xuất dữ liệu, gắn nhãn độ tin cậy và gom cụm các nhược điểm thực tế thành bảng checklist. AI tuyệt đối không tự động thêm sản phẩm vào giỏ, không tự chốt đơn thay người dùng; quyền quyết định mua sắm hoàn toàn thuộc về con người. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
- Tôi sửa gì:

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Nhận xét của người mua dùng nhiều tiếng lóng, từ địa phương, lỗi chính tả và các biểu đạt cảm xúc khác nhau; không có một nhãn đúng/sai tuyệt đối cho từng câu từ mà phụ thuộc vào việc gom nhóm ngữ nghĩa (khía cạnh lỗi sản phẩm, dịch vụ hay vận chuyển).
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Quy trình xử lý gồm chuỗi liên hoàn từ cào dữ liệu DOM client, lọc nhiễu thống kê, phân tích ngữ nghĩa (NLP), phân cụm chủ đề lỗi (aspect extraction), đến định dạng hiển thị thẻ tóm tắt.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: Độ mơ hồ cao + Độ phức tạp cao (Góc trên bên phải)
```

**Vì sao (2-3 câu):**

```text
Dữ liệu đầu vào là văn bản tiếng Việt phi cấu trúc với nhiều nhiễu (review copy-paste, vote 5 sao nhưng chê, tiếng lóng) nên không thể dùng bộ lọc từ khóa tĩnh để giải quyết triệt để. 
Đồng thời, quy trình xử lý trải qua nhiều công đoạn phụ thuộc dữ liệu nối tiếp nhau (trích xuất DOM -> lọc rác sơ bộ -> phân cụm ngữ nghĩa -> tổng hợp insight), đòi hỏi sự phối hợp nhịp nhàng giữa xử lý dữ liệu và mô hình ngôn ngữ.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng RegEx và lọc ngưỡng: loại bỏ review dưới 10 ký tự, chuỗi copy-paste nhận xu (bài hát, ký tự vô nghĩa), lọc cứng các từ khóa quảng cáo. | Chỉ đủ để dọn dẹp các mẫu rác hiển nhiên hoặc phân loại sao cứng (1–3 sao). | Bỏ sót các review seeding viết dài tinh vi; không hiểu được tiếng lóng, mỉa mai, hoặc đánh giá vote 5 sao nhưng nội dung chê hỏng. | Chọn một phần (Dùng cho bước tiền xử lý lọc rác thô và giảm tải token). |
| **Workflow** | Pipeline tuyến tính: Parse DOM client -> Rule tiền xử lý lọc rác -> LLM trích xuất khía cạnh (aspect extraction) & gom cụm lỗi -> Render widget checklist có dẫn nguồn. | Đủ khi quy trình xử lý theo một đường thẳng cố định, các bước sau nhận input từ bước trước, không cần hệ thống tự lập kế hoạch rẽ nhánh. | Pipeline nghẽn nếu Shopee đổi cấu trúc DOM khiến parser lấy thiếu text, hoặc LLM trả về format sai cấu trúc JSON schema. | CHỌN CHÍNH (Áp dụng cho toàn bộ luồng xử lý từ lúc người dùng mở trang đến khi render thẻ tóm tắt). |
| **Agent** | Hệ thống tự động quyết định mở thêm tab phụ, tự gọi API lịch sử giá, tự so khớp voucher giữa 5 shop rồi tự đề xuất giỏ hàng tối ưu. | Khi bài toán yêu cầu trợ lý phải tự lập kế hoạch đa bước và tự động hành động trên nhiều nền tảng mà không cần người dùng can thiệp. | Độ trễ rất cao (15–30s), tốn token, dễ rơi vào vòng lặp (infinite loop) hoặc hallucinate khi gọi tool; khó kiểm soát chất lượng đầu ra. | Không chọn (Quá phức tạp, over-engineering cho một tiện ích cần hiển thị kết quả trong vài giây). |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?** 
   Rule không giải được 70-80% trường hợp vì chỉ loại bỏ được khoảng 30-40% review rác copy-paste thô sơ, hoàn toàn bất lực trước review seeding viết tự nhiên hoặc các câu chê trách ngữ cảnh phức tạp.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** 
   Các bước đi thẳng một đường cố định từ trích xuất DOM, làm sạch dữ liệu, đưa vào LLM phân tích ngữ nghĩa, đến hiển thị kết quả lên widget mà không cần rẽ nhánh động.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** 
   Không thật sự cần Agent vì mục tiêu bài toán là phân tích và tóm tắt dữ liệu của chính trang sản phẩm người dùng đang xem, không cần mô hình tự lập kế hoạch tìm kiếm ngoài lề.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** 
   Người mua hàng sẽ phát hiện đầu tiên khi bấm vào trích dẫn gốc đối chiếu (fallback view) ngay dưới mỗi gạch đầu dòng lỗi, chỉ mất khoảng 5–10 giây để kiểm chứng.
5. **Có hạ được từ Agent → Workflow → Rule không?** 
   Có, hệ thống hoàn toàn hạ được từ kiến trúc Agent phức tạp xuống một Workflow pipeline ổn định, trong đó khâu tiền xử lý được hạ cấp về Rule-based để tối ưu tốc độ và chi phí.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Kiến trúc Workflow là điểm cân bằng hoàn hảo giữa khả năng hiểu ngữ nghĩa tiếng Việt của LLM và tính ổn định, dễ kiểm soát của luồng xử lý phần mềm truyền thống. 
Luồng dữ liệu đi thẳng theo một pipeline tuần tự rõ ràng (Trích xuất DOM -> Lọc rác bằng Rule -> Trích xuất lỗi bằng LLM -> Hiển thị widget), không đòi hỏi mô hình phải tự lập kế hoạch phức tạp như Agent. 
Mô hình này giúp duy trì thời gian phản hồi nhanh dưới 5 giây trên Browser Extension, tối ưu hóa chi phí token và đảm bảo cấu trúc dữ liệu đầu ra luôn chuẩn xác để render giao diện.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nếu chỉ dùng thuần Rule-based, hệ thống không thể xử lý được ngữ nghĩa phức tạp của người dùng Việt Nam như đánh giá 5 sao để nhận xu nhưng nội dung chê bai, hoặc dùng từ châm biếm, viết tắt. 
Rule cũng không thể gom cụm các biểu đạt lỗi khác nhau (ví dụ: "chập chờn", "không nhận pin", "nhanh sụt nguồn") về cùng một nhóm khía cạnh sản phẩm như LLM.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người mua sắm trực tuyến cá nhân trên Shopee có nhu cầu mua các mặt hàng giá trị từ 300.000 VNĐ trở lên (đồ điện tử, gia dụng, mỹ phẩm). Nhóm này nhạy cảm với rủi ro hàng lỗi/kém chất lượng và luôn có thói quen đọc kỹ đánh giá trước khi xuống tiền. |
| **Workflow** | Người dùng mở trang sản phẩm trên trình duyệt; tiện ích mở rộng tự động cào tập review hiển thị trên DOM; hệ thống chạy rule lọc rác rồi đưa qua LLM để gom cụm lỗi thực tế và đánh giá độ tin cậy; người dùng đọc thẻ tóm tắt lỗi và quyết định chốt đơn hoặc chuyển shop. |
| **Bottleneck** | Khâu đọc và phân loại thủ công hàng trăm review bị nhiễu loạn bởi seeding và bài đăng nhận xu. Người mua mất 20–30 phút chỉ để lội qua các đánh giá 1–3 sao nhằm phân biệt đâu là lỗi hỏng hóc kỹ thuật của sản phẩm, đâu là phàn nàn do bên vận chuyển giao chậm. |
| **Impact** | Gây lãng phí từ 45 đến 60 phút cho mỗi phiên mua sắm, dẫn đến tâm lý kiệt sức vì quá tải thông tin. Nghiêm trọng hơn, người mua dễ mất tiền oan vào hàng kém chất lượng do bị đánh lừa bởi hàng nghìn đánh giá 5 sao ảo được tạo tự động. |
| **Success Metric** | Giảm thời gian thẩm định đánh giá từ 45 phút xuống dưới 3–5 phút cho mỗi sản phẩm. Bảng trích xuất nhược điểm của AI đạt độ chính xác trên 85% khi đối chiếu với nội dung thực tế của tập review 1–3 sao gốc. |
| **Boundary** (làm / không làm) | **LÀM:** Tự động parse DOM tại client, lọc rác bằng Rule, dùng LLM tóm tắt top 3–5 lỗi thực tế từ review 1–3 sao, chấm điểm tin cậy tổng thể (Trust Score) kèm dẫn chứng review gốc.<br>**KHÔNG LÀM:** Không tự động thêm sản phẩm vào giỏ, không tự chốt đơn, không xây dựng chatbot hội thoại lan man, không so sánh voucher chéo sàn ở giai đoạn MVP. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay **sau bước Rule làm sạch dữ liệu DOM thô** và **trước bước Người dùng xem giao diện tóm tắt & đưa ra quyết định mua hàng**. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **Workflow:** Vì bài toán có luồng xử lý dữ liệu tuần tự, khép kín từ trích xuất đến hiển thị, cần khả năng hiểu ngôn ngữ tự nhiên của LLM nhưng không cần tính tự chủ rẽ nhánh của Agent. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI bịa lỗi kỹ thuật không có thật (hallucination) hoặc bỏ sót lỗi nghiêm trọng; **Người mua hàng** kiểm tra trực tiếp bằng cách bấm vào link dẫn chứng mở xem review gốc được ghim kèm mỗi dòng tóm tắt. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Chân dung người mua đồ giá trị trên 300k trên Shopee và quy trình 5 bước trên Browser Extension đã được định nghĩa chi tiết. |
| Baseline + metric đo được chưa? | Yes | Baseline 45 phút giảm xuống dưới 5 phút và độ chính xác trích xuất lỗi >85% hoàn toàn đo đạc được bằng thực nghiệm. |
| Data/input đủ dùng chưa? | Yes | Dữ liệu review, số sao và nội dung văn bản có sẵn trên giao diện trang chi tiết sản phẩm Shopee, truy xuất trực tiếp qua client DOM. |
| AI sai, hậu quả chấp nhận được không? | Yes | Hậu quả ở mức thấp (người dùng tốn thêm 1-2 phút đọc lại review gốc nếu nghi ngờ), không gây rủi ro tài chính hay an toàn trực tiếp vì AI không can thiệp đặt hàng. |
| Có người review/owner không? | Yes | Người mua hàng trực tiếp đóng vai trò là human-in-the-loop để kiểm tra bảng tóm tắt trước khi bấm mua. |
| Có cách non-AI đơn giản hơn không? | No | Rule-based thông thường không thể hiểu được ngữ nghĩa phức tạp của tiếng lóng tiếng Việt, hiện tượng vote 5 sao nhưng chê, hoặc gom cụm các lỗi kỹ thuật tương đồng. |

**Decision:**

```text
Go
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Đề tài giải quyết đúng nỗi đau có thực và tần suất cao của người mua sắm trực tuyến, đã được chứng minh qua phỏng vấn và khảo sát thực tế (83.3% người dùng gặp khó khăn khi lọc review). 
Phương án giải quyết theo hướng Browser Extension giải quyết triệt để rào cản anti-bot của Shopee bằng cách parse dữ liệu trực tiếp tại máy client. 
Ranh giới kỹ thuật được xác định rõ ràng ở mức Workflow pipeline (kết hợp Rule tiền xử lý và LLM trích xuất), vừa kiểm soát được chi phí token vừa đảm bảo tốc độ phản hồi nhanh. 
Mức độ rủi ro của hệ thống thấp và người dùng hoàn toàn có thể kiểm chứng kết quả thông qua các trích dẫn review gốc được ghim kèm.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: Thu thập thủ công tập dữ liệu gồm toàn bộ text review của 10 sản phẩm đồ công nghệ/gia dụng (từ 300k - 2 triệu VNĐ) có từ 100 đến 500 lượt đánh giá trên Shopee.
- Chạy tay: Dùng script Python lọc sạch rác theo bộ Rule định sẵn, sau đó đưa prompt chuẩn vào LLM để xuất ra JSON chứa Top lỗi thực tế và tỷ lệ seeding.
- Đo 3 số: 
  1. Độ chính xác trích xuất lỗi (% lỗi AI nêu xuất hiện thực tế trong review gốc, mục tiêu >85%).
  2. Thời gian xử lý của mô hình (tính từ lúc nạp prompt đến khi ra kết quả, mục tiêu <5 giây).
  3. Thời gian con người đọc hiểu và ra quyết định (bấm giờ người dùng đọc bảng tóm tắt, mục tiêu <3 phút).
```

**Nếu Not Yet — cần validate gì trước:**

```text
Không áp dụng (Dự án đã đủ điều kiện Go).
```

**Nếu No-Go — làm gì thay AI:**

```text
Không áp dụng (Dự án đã đủ điều kiện Go).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng sử dụng AI và quay về cơ chế đọc review thủ công khi:
1. Shopee thay đổi cơ chế hiển thị khiến DOM hoàn toàn bị mã hóa hoặc che giấu nội dung review ở tầng client, làm tỷ lệ trích xuất text thất bại vượt quá 30%.
2. Tỷ lệ hallucination của LLM vượt quá 20% (bịa ra các lỗi sản phẩm không có trong review gốc gây hoang mang cho người mua).
3. Chi phí API vượt quá ngưỡng chịu đựng hoặc độ trễ phản hồi của LLM kéo dài trên 15 giây khiến người dùng không muốn chờ đợi.
```

---

### Self-check nộp phần 02 (nhóm)
- [v] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [v] Có validation (quote thật) + research (link kiểm được)
- [v] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [v] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [v] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
