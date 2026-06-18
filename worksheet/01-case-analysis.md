---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** Stack Overflow  
**Người làm:** Phạm Thanh Hằng  
**Bàn / nhóm bàn:** (Điền sau khi thảo luận)  
**Ngày:** 18/06/2026

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [ ] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [ ] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [ ] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [ ] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** Stack Overflow
- **AI / platform / sản phẩm mới tạo áp lực:** ChatGPT, GitHub Copilot, Claude
- **Vì sao tôi chọn case này?**  
  > Vì đây là ví dụ kinh điển về việc một sản phẩm có "hiệu ứng mạng" (network effect) cực mạnh và SEO top 1 nhưng vẫn bị phá vỡ nhanh chóng khi hành vi người dùng (entry point) chuyển dịch sang AI.

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | Traffic giảm ~14-16% vào đầu 2023 | Dấu hiệu đầu tiên sau khi ChatGPT ra mắt | Similarweb báo cáo tháng 4/2023 |
| E2 | Lượng câu hỏi mới trên nền tảng giảm ~50% | Cộng đồng mất đi nguồn cung cấp nội dung (oxygen) cốt lõi | Phân tích data cộng đồng (Reddit/Tech) |
| E3 | Công ty sa thải 28% nhân sự vào tháng 10/2023 | Sự thừa nhận khó khăn về tài chính và phải tái cấu trúc | Thông báo chính thức của Stack Overflow |
| E4 | Ra mắt OverflowAI và tập trung hợp tác API (VD: OpenAI) | Động thái xoay trục từ B2C Ads sang bán Data (B2B) | Tin công nghệ / Thông cáo báo chí |
| E5 | | | |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > Hiệu ứng mạng vô địch (nhiều câu hỏi -> nhiều người trả lời -> nhiều người dùng), SEO thống trị Google cho mọi lỗi lập trình, và hệ thống gamification.
2. **AI shock làm thay đổi...**  
   > Cách dev tìm giải pháp: không cần search Google rồi đọc forum nữa, mà hỏi thẳng AI trong IDE để được sinh code và sửa lỗi luôn.
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > Lượng câu hỏi mới (New Questions) sụt giảm mạnh, chứng tỏ không ai còn kiên nhẫn đi hỏi người thật rồi chờ đợi nữa.

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> Giả định cốt lõi: Khi dev gặp lỗi, họ phải tra cứu các trường hợp tương tự do người khác đã gặp. Job-to-be-done là "Giúp tôi tìm cách sửa đoạn code bị lỗi". 
> Trước AI, cách duy nhất là gom kiến thức nhân loại vào một kho Q&A. Stack Overflow thắng nhờ cộng đồng đồ sộ và tính năng upvote giúp câu trả lời tốt nhất nổi lên.

**Bằng chứng đỡ nhận định này:** E1, E2

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** Làm xong giúp tôi (tự viết/sửa code thay vì chỉ đưa hướng dẫn)
**Competitive dynamic quan trọng nhất:** Entry point thay đổi (chuyển sang thao tác trong IDE với Copilot)

**Trả lời của tôi:**  
> Kỳ vọng chuyển từ "chỉ cho tôi cách làm" sang "viết và sửa lỗi cho tôi ngay lập tức dựa trên codebase của tôi". 
> Entry point: thay vì phải mở trình duyệt web tìm Stack Overflow, người dùng giờ thao tác thẳng trong IDE hoặc trò chuyện với ChatGPT.

**Bằng chứng đỡ nhận định này:** E1, E4

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> Workflow truyền thống "Gặp lỗi -> Copy lỗi -> Lên Google -> Đọc Stack Overflow -> Thử nghiệm" đã bị phá vỡ vĩnh viễn. 
> Trải nghiệm Q&A thủ công không còn là chuẩn mực. User không còn muốn tốn thời gian đọc các thread dài để lắp ráp context nữa.

**Bằng chứng đỡ nhận định này:** E2, E3

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh

**Trả lời của tôi:**  
> Cứu được nhưng không thể ở mô hình B2C thu hút traffic bán ads như xưa. Họ đang chuyển sang B2B: bán quyền truy cập API dữ liệu chất lượng cao cho các công ty AI (như OpenAI) và phát triển OverflowAI cho nội bộ doanh nghiệp. App layer mở sẽ thu hẹp lại thành nguồn cấp data.

**Bằng chứng đỡ nhận định này:** E3, E4

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì entry point của developer chuyển dịch từ trình duyệt web sang IDE và chatbot, làm gãy hiệu ứng mạng cộng đồng.
2. Điều thay đổi vĩnh viễn là kỳ vọng của user từ "tự tìm cách qua thảo luận" sang "AI trực tiếp sửa mã dựa trên ngữ cảnh cá nhân".
3. Verdict của tôi là Stack Overflow phải chấp nhận mất traffic B2C và xoay trục hoàn toàn sang việc trở thành nhà cung cấp dữ liệu (Data API) cho AI và giải pháp B2B nội bộ.

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Trần Quang Thanh | Stack Overflow | Lượng Traffic giảm ~14-16% vào đầu 2023 | Đa phần là vibecode, không dùng stack overflow nhiều nữa | Bán Data lại cho công ty AI lớn |
| Hoàng Trọng Vĩnh | VioEdu | Lượng Traffic giảm | Học sinh không cần học theo lộ trình nữa mà có thể học theo nhu cầu, học theo bài viết trên mạng.  | Tổ chức đấu trường VioEdu thay vì học theo duy nhất lộ trình, thêm sự kiện mới |
| Hoàng Phương Thảo | Grammarly| Tháng 2/2024, Grammarly cắt giảm 230 nhân sự để tái cấu trúc | Trước đây người dùng viết và grammarly sửa, thì bây giờ người dùng có thể viết cùng AI luôn | Chuyển từ sửa lỗi ngữ pháp sang tham gia toàn bộ quá trình viết |
| Bạn 4 | | | | |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> Bàn tôi thấy case Grammarly và Stack Overflow có bằng chứng mạnh nhất. Cả hai case này đều có sự kiện hoặc số liệu sụt giảm thực tế rõ rệt (Stack Overflow giảm ~15% traffic, Grammarly cắt giảm 230 nhân sự) ngay sau khi GenAI bùng nổ, cho thấy tác động trực diện của AI shock lên mô hình kinh doanh cốt lõi.

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> Pattern lặp lại là sự thay đổi kỳ vọng người dùng từ "công cụ hỗ trợ/chỉ dẫn" sang "AI làm cùng/làm thay từ đầu đến cuối". (Ví dụ: VioEdu học theo nhu cầu cá nhân hóa thay vì lộ trình cứng; Grammarly viết cùng AI thay vì chỉ sửa lỗi cuối cùng; Stack Overflow được AI sinh và sửa code thay vì phải tự tìm lỗi).

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> Nếu dự án chỉ đóng vai trò là một "bước trung gian" hoặc "nơi tra cứu", thì nó rất dễ bị bypass khi AI có thể can thiệp trực tiếp vào toàn bộ quá trình (end-to-end workflow) của người dùng. Sản phẩm cần tiến sát vào "nơi người dùng làm việc" và thực hiện trọn vẹn công việc cho họ.

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [x] Giữ nguyên
- [ ] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Tôi giữ nguyên verdict. Việc chia sẻ từ các bạn cho thấy pattern chuyển dịch từ "hỗ trợ" sang "làm thay/làm cùng" xuất hiện ở mọi ngành (viết lách, giáo dục, lập trình). Điều này củng cố luận điểm Stack Overflow không thể quay lại làm một cộng đồng hỏi đáp đơn thuần, mà bắt buộc phải chuyển mình thành nguồn cấp data B2B (như bạn Thanh trong bàn cũng đồng tình).

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> Entry point của quy trình lập trình đã chuyển từ trình duyệt sang IDE và chatbot. Người dùng không còn cần công cụ trung gian để tìm kiếm sự trợ giúp mà muốn AI giải quyết lỗi trực tiếp trên codebase của họ.

**Điều thay đổi vĩnh viễn là:**  
> Hành vi tìm kiếm giải pháp của người dùng đã thay đổi: từ việc tốn thời gian tìm đọc và tự tổng hợp ngữ cảnh trên diễn đàn sang kỳ vọng AI hiểu sẵn ngữ cảnh cá nhân và đưa ra giải pháp ngay lập tức.

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Đừng xây dựng sản phẩm dựa trên giả định rằng người dùng sẽ tự tìm kiếm và chắp vá thông tin. Hãy thiết kế sản phẩm len lỏi vào quy trình làm việc của người dùng và giúp họ hoàn thành công việc một cách tự động (done-for-me).

---

## Checklist trước khi nộp

- [x] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [x] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [x] Tôi đã ghi lại phần share trong bàn.
- [x] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

- Bổ sung thêm một case "đối thủ phản ứng tốt hơn" để so.
- Thêm một đoạn ngắn: **nếu tôi là PM của case này trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?**
- Kiểm lại xem case này yếu vì expectation shift, competitive dynamics, hay cả hai cùng lúc.
