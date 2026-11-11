# 📖 CẨM NANG HƯỚNG DẪN SỬ DỤNG: XƯỞNG TẠO SKILL GIÁO DỤC (AI AGENT SKILL STUDIO)

Chào mừng bạn đến với **Xưởng tạo Skill Giáo dục**. Đây là công cụ chuyên nghiệp giúp giáo viên, giảng viên và các chuyên gia thiết kế học liệu số xây dựng các **AI Agent Skill (Kỹ năng gia sư trí tuệ nhân tạo)** chuẩn phương pháp sư phạm, tương thích hoàn toàn với Claude, Google Antigravity và ChatGPT.

---

## 🎯 1. TỔNG QUAN VỀ AI SKILL TRONG GIÁO DỤC

### 1.1. AI Skill là gì?
AI Skill không phải là một câu prompt đơn lẻ. Nó là một **bộ quy tắc hành vi, năng lực sư phạm và kho ngộ nhận học sinh** được đóng gói dưới định dạng chuẩn `SKILL.md`. Khi nạp Skill vào các trợ lý AI:
- AI **không giải bài hộ** học sinh.
- AI đóng vai trò như một **gia sư tâm huyết**: kiên nhẫn gợi mở, nhận diện đúng chỗ học sinh bị hiểu sai, điều chỉnh ngôn từ theo lứa tuổi và khích lệ người học tự tìm ra đáp án.

### 1.2. Ba chế độ giảng dạy (Modes)
* **Gia sư giải bài tập (`tutor`)**: Học sinh mang bài tập đến. AI đóng vai người dẫn đường, dùng câu hỏi Socratic và giàn giáo 3 mức để học sinh tự hoàn thành bài.
* **Khám phá bài học mới (`unit`)**: Học sinh bắt đầu một chuyên đề mới. AI kiểm tra lỗ hổng kiến thức nền → đưa ví dụ khám phá → chốt lý thuyết → bài tập mẫu giảm dần.
* **Đa năng (`both`)**: AI tự động nhận diện học sinh đang muốn học bài mới hay đang kẹt ở một bài tập cụ thể.

---

## 🤖 1.3. TÍNH NĂNG ĐỘC QUYỀN: AI TRỢ LÝ SƯ PHẠM TOÀN DIỆN & TÍCH HỢP GEMINI CLOUD

Hệ thống được trang bị **Engine Trí tuệ Sư phạm EduCore v3.5** kết hợp với **Google Gemini Cloud AI**:
1. **🪄 Tự động thiết lập tất cả (Smart Auto-Fill All)**: 
   - Tại Bước 1, bạn chỉ cần gõ tên môn (Toán, Vật lí, Hóa học, Tiếng Anh...) hoặc tên một chuyên đề.
   - Bấm nút **"✨ Tự động thiết lập tất cả"**, AI sẽ tự động phân tích và sinh ra trọn bộ thiết lập chuẩn sư phạm cho cả 8 bước (Mục tiêu chuẩn Bloom, Phương pháp, Ngộ nhận 3 vế, Rubric tròn 100%, Câu kích hoạt, Kịch bản test cases).
2. **✨ AI Trợ lý Sư phạm phủ kín toàn bộ 8 bước**:
   - **Bước 1**: Gợi ý Bài học & Kiến thức tiên quyết chuẩn mạch chương trình.
   - **Bước 2**: `✨ AI Đề xuất Bloom` (Chọn phối hợp các bậc nhận thức phù hợp cấp học) và `✨ AI Gợi ý` Mục tiêu học tập đo lường được.
   - **Bước 3**: `✨ AI Gợi ý` Phương pháp sư phạm phối hợp và Giọng điệu tối ưu.
   - **Bước 4**: `✨ AI Gợi ý` Bảng ngộ nhận chuẩn 3 vế và `✨ AI Đề xuất Phân hóa` (chọn nhóm đối tượng người học).
   - **Bước 5**: `✨ AI Gợi ý` Kiểu phản hồi sư phạm và Rubric đánh giá tròn 100%.
   - **Bước 6**: `✨ AI Gợi ý` Câu lệnh kích hoạt thực tế từ học sinh.
   - **Bước 7**: `✨ AI Gợi ý Kịch bản Kiểm thử Chuyên sâu` (tạo bộ 4 tình huống sát hạch gia sư).
   - **Bước 8**: `🪄 Tự sửa toàn bộ` đưa 100% tiêu chí đạt chuẩn Socratic tối đa (11/11 Tiêu chí).
3. **✨ Tích hợp Google Gemini Cloud AI ngay trong Modal gợi ý**:
   - Trong cửa sổ AI Sư phạm, ngoài các phương án chuẩn mực suy luận tức thì từ Engine cục bộ, bạn có thể bấm **`✨ Gọi Gemini AI sinh mới`**.
   - Gemini AI sẽ sinh thêm các phương án sư phạm sáng tạo, mới lạ và phong phú không giới hạn theo đúng ngữ cảnh môn học bạn đang thiết kế.
4. **💡 Hiệu ứng Trực quan Flash Highlight**:
   - Khi áp dụng bất kỳ gợi ý nào từ AI (Thay thế hoặc Chèn thêm), hệ thống sẽ tự động cuộn màn hình đến ô nhập liệu tương ứng và nháy sáng viền tím nổi bật (`ai-highlight-flash`) giúp bạn nhận biết ngay nội dung đã được cập nhật ở đâu.
5. **🧭 Thanh Cảnh báo Đồng bộ Thời gian thực (#quickStatus)**:
   - Ở chân trang bên cạnh nút *Tiếp tục*, thanh trạng thái luôn hiển thị chính xác tiến độ và lý do cụ thể nếu nút Tiếp tục chưa sáng (ví dụ: *"⚠️ Vui lòng nhập tên bài học"* hoặc *"⚠️ Vui lòng điền tên kỹ năng"*).
   - Khi đạt chuẩn, thanh chuyển màu xanh: *"✓ Bước X/8: Hợp lệ • Bấm Tiếp tục →"*, mang lại trải nghiệm mượt mà, thông suốt.

---

## 📐 1.4. NGÂN HÀNG KỸ NĂNG TOÁN HỌC CHUẨN GDPT 2018 (12 CHUYÊN ĐỀ CỐT LÕI)

Dựa trên nghiên cứu chuẩn chương trình môn Toán GDPT 2018 (cả cấp THCS & THPT), hệ thống đã xây dựng sẵn **12 kỹ năng toán học thiết yếu** bao phủ các mạch: **Đại số & Giải tích**, **Hình học & Đo lường**, **Thống kê & Xác suất**, và **Mô hình hóa toán học**.

Bạn có thể **bấm chọn sẵn một kỹ năng** để tải toàn bộ thiết lập chuẩn, hoặc **tự do chỉnh sửa / tự nhập mới** theo nhu cầu:

| STT | Tên Kỹ năng Toán học | Cấp học | Mạch kiến thức cốt lõi |
| :---: | :--- | :---: | :--- |
| **1** | **Phương trình bậc hai & Hệ thức Vi-ét** | Toán 9-10 | Đại số: Biệt thức delta, nhẩm nghiệm, đối xứng |
| **2** | **Giải toán bằng cách lập PT / Hệ PT** | Toán 8-9 | Mô hình hóa: Chuyển động, năng suất, phần trăm |
| **3** | **Tứ giác nội tiếp & Góc với đường tròn** | Toán 9 | Hình học: 4 dấu hiệu chứng minh, góc nội tiếp |
| **4** | **Hệ thức lượng & Tỉ số lượng giác** | Toán 9-10 | Hình học & Lượng giác: Tam giác vuông, đo đạc thực tế |
| **5** | **Bất đẳng thức Cauchy (AM-GM) & Cực trị** | Toán 9-10 | Đại số: Kỹ thuật chọn điểm rơi, tìm Min/Max |
| **6** | **Hàm số bậc hai Parabol & Tương giao** | Toán 10 | Đại số & Hàm số: Tọa độ đỉnh, bảng biến thiên |
| **7** | **Phương trình chứa căn thức & ĐKXĐ** | Toán 10 | Đại số: Biến đổi tương đương, đặt ẩn phụ |
| **8** | **Phương pháp tọa độ Oxy: Đường thẳng, Đường tròn** | Toán 10 | Hình học giải tích: Vectơ pháp tuyến, khoảng cách |
| **9** | **Quy tắc đếm, Tổ hợp - Chỉnh hợp & Xác suất** | Toán 10-11 | Đại số tổ hợp: Sắp thứ tự vs chọn nhóm |
| **10** | **Quan hệ Vuông góc Không gian & Góc, Khoảng cách**| Toán 11-12 | Hình học không gian: Đường vuông góc mặt, hình chiếu |
| **11** | **Ứng dụng Đạo hàm khảo sát hàm số & Tối ưu** | Toán 12 | Giải tích: Cực trị, GTLN/GTNN, bài toán thực tiễn |
| **12** | **Nguyên hàm, Tích phân & Ứng dụng hình phẳng** | Toán 12 | Giải tích: Đổi biến, từng phần, diện tích, thể tích |

---

## ⚡ 1.5. KIẾN TRÚC ĐỘNG CƠ SƯ PHẠM HOÀN CHỈNH EDUCORE v3.5 (AI PEDAGOGICAL ENGINE)

Hệ thống được vận hành bởi **Động cơ Sư phạm Toàn diện EduCore v3.5** tích hợp 4 phân hệ cốt lõi hoạt động nhịp nhàng:

### 1. Phân hệ Suy luận Tri thức (Inference Core) - 10 Phân môn GDPT 2018
Động cơ sở hữu Cơ sở Tri thức chuyên sâu cho **10 phân môn trọng yếu** của Chương trình GDPT 2018:
- **Toán học (Đại số & Giải tích)**: Hàm số, phương trình bậc hai, hệ thức Vi-ét, bất đẳng thức, tích phân...
- **Toán học (Hình học & Đo lường)**: Tứ giác nội tiếp, góc đường tròn, hệ thức lượng, hình học không gian...
- **Vật lí (Cơ học & Động lực học)**: Định luật Newton, bảo toàn cơ năng, phân tích lực, mặt phẳng nghiêng...
- **Hóa học (Oxi hóa - Khử & Cấu tạo chất)**: Thăng bằng electron, bảng tuần hoàn, liên kết hóa học...
- **Sinh học (Di truyền & Tế bào)**: Quy luật Menđen, phân li độc lập, cấu trúc ADN, đột biến gen...
- **Tin học & Lập trình (C++ / Python / Thuật toán)**: Mảng cộng dồn, hai con trỏ, quy hoạch động, cấu trúc lặp...
- **Ngữ văn (Đọc hiểu & Nghị luận)**: Luận điểm, thao tác lập luận, hình tượng nghệ thuật, biện pháp tu từ...
- **Lịch sử & Địa lí (Tư duy Nhân quả & Atlat)**: Quan hệ nhân quả lịch sử, phân tích số liệu địa lí, kỹ năng Atlat...
- **Tiếng Anh (Ngữ pháp & Giao tiếp Socratic)**: Câu điều kiện (Conditional), mệnh đề quan hệ, thì hoàn thành...
- **Tiểu học (Toán có lời văn & Tiếng Việt)**: Phương pháp sơ đồ đoạn thẳng, tìm hai số khi biết tổng-tỉ/tổng-hiệu...

### 2. Cỗ máy Trạng thái Sư phạm Socratic (Socratic Runtime State Machine)
Tiến trình học tập không phải là hỏi đáp ngẫu nhiên mà được điều phối tự động qua **5 giai đoạn sư phạm chuẩn mực**:
1. **Pha 1 - Khám phá & Chẩn đoán (Diagnostic)**: Khảo sát mục tiêu, thăm dò kiến thức nền tảng và khó khăn ban đầu.
2. **Pha 2 - Bẻ nhỏ bài toán (Deconstruct)**: Tách bài toán phức tạp thành các mắt xích nhỏ, xác định rõ "Đề bài cho gì" và "Cần tìm gì".
3. **Pha 3 - Giàn giáo 3 mức (Scaffolding L1 → L2 → L3)**: 
   - *Mức 1 (Định hướng)*: Đặt câu hỏi gợi mở tư duy tổng quát.
   - *Mức 2 (Nhắc quy tắc)*: Cung cấp từ khóa công thức hoặc gợi ý định luật liên quan.
   - *Mức 3 (Làm mẫu bước đầu)*: Làm mẫu bước khởi đầu (tóm tắt/đặt điều kiện), sau đó trao quyền cho học sinh tiếp nối.
4. **Pha 4 - Tự luyện & Tự giải thích (Independent Practice & Metacognition)**: Học sinh tự tay giải quyết và giải thích lý do tại sao lại chọn hướng đi đó.
5. **Pha 5 - Đánh giá cuối buổi (Exit Ticket)**: Phiếu kiểm tra nhanh 2 câu hỏi củng cố và đối chiếu Rubric chất lượng.

### 3. Phân hệ Giám sát Chất lượng & Tự sửa 1-Click (Quality Core & 1-Click Auto-Fix)
- Tự động kiểm tra **11 tiêu chí khoa học sư phạm khắt khe** theo chuẩn kiểm định quốc tế.
- **Nút "🪄 Tự sửa toàn bộ"**: Tại Bước 8, chỉ cần 1 cú nhấp chuột, Động cơ sẽ tự động bù đắp và tối ưu toàn bộ các mục còn thiếu hoặc chưa đạt chuẩn để đưa điểm số đạt ngay **100% (11/11 Tiêu chí)**!
- **Nút "🪄 Tự sửa" cho từng tiêu chí**: Cho phép giáo viên sửa nhanh từng lỗi cụ thể (như tự chuẩn hóa Rubric về tròn 100%, bổ sung quy tắc 3 vế ngộ nhận `Lỗi → Nguyên nhân → Cách sửa`, cân đối phương pháp sư phạm...).

### 4. Phân hệ Điều phối Kép (Hybrid Dispatcher)
- **Ngoại tuyến (Offline Local Simulator)**: Chạy trơn tru 100% mà không cần kết nối mạng hay khóa API, tự động phản xạ theo đúng tâm lý học sinh và bắt ngộ nhận.
- **Trực tuyến (Cloud AI Dispatcher)**: Tự động đóng gói và tinh chỉnh System Prompt tối ưu khi kết nối **Google Gemini 2.5 Flash / 1.5 Flash** hoặc **OpenAI GPT-4o-mini**.

---

## 🚀 2. QUY TRÌNH 8 BƯỚC THIẾT KẾ SKILL

### Bước 1: Thiết lập Nền tảng (Foundation)
1. **Chọn chế độ**: Chọn *Gia sư giải bài*, *Khám phá bài mới* hoặc *Đa năng*.
2. **Điền nhanh từ ngân hàng mẫu**: Bấm vào các nút **Toán**, **Vật lí**, **Hóa học**, **Tiếng Anh** để tải khung bài học chuẩn mực, sau đó bạn chỉ cần chỉnh sửa lại theo ý mình.
3. **Phạm vi & Bối cảnh**: Nêu rõ chương trình (ví dụ: *GDPT 2018*), các khó khăn tâm lý thường gặp của học sinh (ngại tính toán, sợ phân số, hay quên công thức...).

### Bước 2: Mục tiêu học tập & Thang Bloom (Objectives)
* **Thang nhận thức Bloom**: Chọn các bậc tư duy bạn muốn rèn luyện cho học sinh (từ *Nhớ, Hiểu, Vận dụng* đến *Phân tích, Đánh giá, Sáng tạo*). **Lưu ý**: Nên chọn ít nhất 1 mức từ Phân tích trở lên để AI rèn tư duy phản biện.
  - Bấm nút **`✨ AI Đề xuất Bloom`** để AI tự động chọn bộ thang Bloom tối ưu theo môn học và cấp lớp.
* **Quy tắc viết mục tiêu**:
  - Dùng **động từ hành động đo lường được**: *Giải được, vẽ được sơ đồ, phân biệt được, tìm ra lỗi sai...*
  - **Tránh** các từ chung chung: *Hiểu được, nắm được, biết được*.
  - Bấm nút **`✨ AI Gợi ý`** để nhận các mục tiêu học tập mẫu chuẩn hóa đo lường được.

### Bước 3: Phương pháp Sư phạm & Giọng điệu (Pedagogy)
* Chọn từ **2 đến 4 phương pháp** nghiên cứu sư phạm đã được lập trình sẵn:
  - *Socratic Questioning*: Đặt câu hỏi gợi mở, mỗi lượt chỉ hỏi 1 câu ngắn.
  - *Scaffolding 3 mức (Vygotsky)*: Gợi ý phương pháp → Nhắc công thức → Làm mẫu bước đầu.
  - *Faded Worked Examples (Sweller)*: Ví dụ mẫu đầy đủ → Bài làm dở dang → Bài tự làm.
  - *Retrieval Practice (Roediger)*: Hỏi nhanh nhớ lại kiến thức đầu/cuối buổi học.
* **Nguyên tắc "Không đưa đáp án trực tiếp"**: Bật tính năng này để AI kiên quyết từ chối giải hộ, ép học sinh phải tư duy.
* **Giọng điệu**: Chọn giọng điệu phù hợp (*Thân thiện, khích lệ*, *Vui nhộn*, *Học thuật*...).
* Bấm nút **`✨ AI Gợi ý Chiến lược`** để AI đề xuất gói phương pháp và giọng điệu chuẩn theo bộ môn.

### Bước 4: Lỗi sai & Chiến lược Phân hóa (Misconceptions)
* **Quy tắc 3 vế (bắt buộc có 2 mũi tên `→`)**:
  `[Tên lỗi sai điển hình] → [Nguyên nhân ngộ nhận bản chất] → [Câu hỏi/Ví dụ phản bác giúp tự sửa]`
  *Ví dụ:* `Quên đổi dấu khi chuyển vế → xem chuyển vế như đổi chỗ tự do → cho học sinh cộng hai vế cùng một số để tự kiểm chứng.`
* Bấm nút **"+ Thêm mẫu mũi tên"** để chèn nhanh cấu trúc chuẩn hoặc bấm **`✨ AI Gợi ý Ngộ nhận`** để lấy các bảng lỗi kinh điển kèm giải pháp phản bác.
* Chọn các nhóm đối tượng phân hóa (Học sinh mất gốc, học sinh khá giỏi, học sinh lo âu...). Bấm **`✨ AI Đề xuất Phân hóa`** để thiết lập nhóm học sinh cần trợ giúp theo môn.

### Bước 5: Đánh giá & Phản hồi (Assessment)
* **Kiểu phản hồi**: Khuyên dùng *Nêu một điểm làm tốt và một bước cải thiện*.
* **Phiếu thoát lớp (Exit Ticket)**: Chọn số câu hỏi kiểm tra nhanh cuối buổi (2-3 câu).
* **Tiêu chí chấm (Rubric)**: Liệt kê các tiêu chí kèm tỷ lệ phần trăm (Tổng tỷ lệ % phải bằng đúng **100%**).
* Bấm **`✨ AI Gợi ý`** để nhận Rubric chuẩn hóa đã cân đối sẵn 100%.

### Bước 6: Câu lệnh kích hoạt (Triggers)
* Liệt kê các câu học sinh thường nói trong thực tế (ít nhất 3 câu, mỗi câu dài trên 10 ký tự).
* Ví dụ: *"Thầy/cô kiểm tra bài giải này giúp em với"*, *"Em chưa hiểu chỗ này"*...
* Bấm **`✨ AI Gợi ý Câu kích hoạt`** để sinh danh sách câu hỏi kích hoạt tự nhiên từ học sinh.

### Bước 7: Kiểm thử Năng lực (Test Cases)
* Hệ thống tự động tạo 4 tình huống kiểm thử (Học sinh đòi đáp án, học sinh gửi bài giải có lỗi sai, học sinh hỏi lạc đề, học sinh chưa có nền tảng).
* Bấm nút **`✨ AI Gợi ý Kịch bản Kiểm thử Chuyên sâu`** để xem phân tích kỳ vọng sư phạm và các bài toán thử nghiệm chuyên sâu.
* Bấm **"Sao chép câu hỏi"** để dán vào AI và đối chiếu xem AI có phản ứng đúng như mong đợi không.

### Bước 8: Hoàn tất & Xuất bản (Export)
* **Bảng điểm sư phạm**: Đạt tối thiểu 80% (từ 9/11 tiêu chí trở lên) là đạt chuẩn xuất sắc.
* Lựa chọn xuất khẩu & sử dụng:
  - **🚀 Giao diện Gia sư AI (Interactive Runner)**: Bấm nút *"🚀 Mở Giao diện Gia sư AI"* để chat thử nghiệm trực tiếp theo đúng kịch bản và chuẩn sư phạm vừa thiết kế.
  - **🌐 Web App Gia sư (.html độc lập)**: Tải về một file Web duy nhất (Single-file HTML) để gửi cho học sinh/giáo viên sử dụng ngay trên điện thoại hoặc máy tính mà không cần cài đặt bất kỳ phần mềm nào.
  - **Claude Skill (SKILL.md)**: Chuẩn cho Claude Projects hoặc đóng gói file `.skill`.
  - **Google Antigravity**: Chuẩn đặc tả Agent Skill dành cho hệ sinh thái Antigravity.
  - **ChatGPT System Prompt**: Hướng dẫn hành vi tối ưu cho OpenAI Custom GPTs.

---

## 💻 3. HƯỚNG DẪN CÀI ĐẶT & SỬ DỤNG SKILL

### 3.1. Cài đặt vào Claude (Claude.ai)
1. Tại Bước 8, chọn tab **Claude Skill (SKILL.md)**.
2. Bấm nút **"📦 Sao chép lệnh tạo .skill cho Claude"**.
3. Mở một cuộc hội thoại mới trên Claude, dán toàn bộ nội dung vừa sao chép vào. Claude sẽ tự động tạo thư mục và đóng gói file `.skill` để bạn tải về cài đặt.
4. *Cách đơn giản hơn (Claude Projects)*: Bấm **"📥 Tải file SKILL.md"**, mở Project trên Claude.ai và tải file này vào mục **Project Knowledge**, hoặc dán nội dung vào ô **Project Instructions**.

### 3.2. Cài đặt vào Google Antigravity
1. Tại Bước 8, chọn tab **Google Antigravity Agent**.
2. Bấm nút **"📥 Tải file SKILL.md"**.
3. Lưu file này vào thư mục dự án của bạn theo đường dẫn:
   `skills/<ten-skill>/SKILL.md`
4. Antigravity sẽ tự động nhận diện skill này qua các câu kích hoạt (triggers).

### 3.3. Cài đặt vào ChatGPT (Custom GPTs)
1. Tại Bước 8, chọn tab **ChatGPT System Prompt**.
2. Bấm nút **"📋 Sao chép nội dung"**.
3. Truy cập **ChatGPT → Explore GPTs → Create a GPT**.
4. Chuyển sang tab **Configure**, dán nội dung vào ô **Instructions**.

### 3.4. Sử dụng Giao diện Web Gia sư tương tác & Trung tâm Động cơ EduCore
1. **Trung tâm Quản trị Động cơ Sư phạm (Engine Hub Modal `⚡ Động cơ AI`)**:
   - Bấm nút **"⚡ Động cơ AI"** trên thanh tiêu đề chính.
   - Quản lý trạng thái 4 phân hệ cốt lõi.
   - **Nạp nhanh khung thiết lập bài học**: Click chọn 1 trong 10 phân môn GDPT 2018 (Toán Đại số, Hình học, Vật lí, Hóa học, Sinh học, Tin học, Ngữ văn, Lịch sử - Địa lí, Tiếng Anh, Tiểu học) để nạp trọn bộ giáo án mẫu chuẩn hóa.
   - **Thử nghiệm phản xạ Động cơ (Diagnostic Sandbox)**: Nhập câu học sinh nói bất kỳ và bấm "Phân tích phản xạ" để kiểm tra cách Động cơ bóc tách ý định, xác định mức giàn giáo và tạo ra câu hỏi gợi mở tức thì.

2. **Trải nghiệm trực tiếp ngay trên công cụ (Interactive Runner)**:
   - Tại Bước 8 (hoặc nút **🚀 Chạy Gia sư** trên thanh tiêu đề), bấm **"🚀 Mở Giao diện Gia sư AI"**.
   - **Dải viễn trắc Sư phạm thời gian thực (Pedagogy Progression Ribbon)**:
     * Hiển thị trực quan 5 pha Socratic: `Khám phá` → `Bẻ nhỏ bài` → `Giàn giáo 3 mức` → `Tự luyện` → `Phiếu thoát lớp`.
     * Tự động nhảy pha hoặc cho phép giáo viên/học sinh click trực tiếp để chuyển pha sư phạm.
     * Hiển thị chỉ số viễn trắc trực tiếp: Mức giàn giáo hiện tại (`L1/L2/L3`), số lượt hỏi Socratic, và huy hiệu cảnh báo khi phát hiện ngộ nhận (`⚠️ Đã bắt ngộ nhận`).
   - Cột bên trái hiển thị danh sách **Câu kích hoạt nhanh** và **4 Tình huống kiểm thử sư phạm** (Học sinh đòi đáp án, Học sinh làm sai, Hỏi lạc đề, Quên kiến thức nền).
   - Tự động hiển thị công thức Toán học sắc nét bằng **KaTeX**.
   - Hỗ trợ nút **🔊 Đọc to** (Text-to-Speech) và **📋 Sao chép**.

3. **Cấu hình AI**:
   - Bấm nút **⚙️ Cài đặt AI** trên thanh tiêu đề của giao diện Gia sư:
     * **Google Gemini API (Khuyên dùng - Miễn phí)**: Nhập khóa API miễn phí từ [Google AI Studio](https://aistudio.google.com/app/apikey) để trò chuyện với mô hình `gemini-2.5-flash` hoặc `gemini-1.5-flash`.
     * **OpenAI API**: Nhập khóa OpenAI để sử dụng `gpt-4o-mini`.
     * **Chế độ Thử nghiệm Sư phạm (Offline Demo)**: Không cần API key, Động cơ EduCore tự động điều phối tiến trình 5 pha và phản hồi sư phạm chuẩn mực.

4. **Xuất file HTML Web App gửi cho học sinh**:
   - Bấm nút **"🌐 Tải Web App (.html)"**.
   - Trình duyệt sẽ tải về 1 file HTML duy nhất (ví dụ: `toan-9-he-thuc-vi-et-web-app.html`).
   - File độc lập này chứa **toàn bộ Động cơ Sư phạm Socratic**, dải đo đạc viễn trắc 5 pha, cơ chế bắt ngộ nhận và rendering công thức Toán KaTeX.
   - Giáo viên chỉ cần gửi file này qua Zalo, Google Drive, Microsoft Teams hoặc tải lên Google Sites/LMS. Học sinh click đúp chuột là mở ra học được ngay trên điện thoại hoặc máy tính mà không cần bất kỳ cài đặt nào!

---

## 💾 4. QUẢN LÝ DỰ ÁN & TIỆN ÍCH HỖ TRỢ

* **Lưu dự án (`.json`)**: Bấm nút **"💾 Lưu dự án"** trên thanh tiêu đề để tải file `.json` về máy tính. Bạn có thể lưu trữ các bài giảng khác nhau thành từng file riêng biệt.
* **Nạp lại dự án (`Import JSON`)**: Bấm nút **"📂 Nạp dự án"** và chọn file `.json` đã lưu trước đó để tiếp tục chỉnh sửa.
* **Xem trước thời gian thực**: Bấm nút **"👁️ Xem trước"** bất kỳ lúc nào để xem ngay file `SKILL.md` và kiểm tra điểm chuẩn hóa sư phạm hiện tại.
* **Chế độ Sáng / Tối**: Bấm nút **"🌓"** để đổi màu giao diện phù hợp với mắt khi làm việc buổi tối.

---

## ☁️ 5. TRUNG TÂM QUẢN TRỊ KHO SKILL & ĐỒNG BỘ GOOGLE DRIVE (APP SKILL)

Hệ thống đã được tích hợp liên kết trực tiếp với thư mục lưu trữ đám mây Google Drive **APP SKILL**:

- **Đường dẫn thư mục Google Drive**: [Thư mục APP SKILL](https://drive.google.com/drive/folders/1tzL_WVnrangPqcSSeiWK7x4v7AGjKjuG?lfhs=2)
- **Mã thư mục (Folder ID)**: `1tzL_WVnrangPqcSSeiWK7x4v7AGjKjuG`
- **Giao diện Quản trị Chuyên biệt**: Mở file `quan_ly_skill.html` hoặc bấm nút **🗂️ Kho Skill Drive** trên thanh tiêu đề của Xưởng tạo Skill.

### Các Tính năng Quản trị Cốt lõi:
1. **Quản lý Tập trung Toàn bộ Kỹ năng Sư phạm**:
   - Hiển thị trực quan theo dạng lưới thẻ (Grid) hoặc bảng chi tiết (Table).
   - Bộ lọc thông minh theo **Môn học** (Toán, Lí, Hóa, Sinh, Tin, Văn, Anh...), **Cấp học** (Tiểu học, THCS, THPT) và chuyên đề mạch kiến thức.
   - Tìm kiếm thời gian thực theo tên kỹ năng, mục tiêu đầu ra hoặc lỗi ngộ nhận.

2. **12 Kỹ năng Toán học Cốt lõi Chuẩn GDPT 2018 Đã Đóng Gói Sẵn**:
   - Đã được khởi tạo và đồng bộ đầy đủ lên thư mục Google Drive `APP SKILL` dưới dạng các file Markdown (`SKILL.md`) và tệp danh mục `DANH_MUC_SKILL.json`.
   - Bao phủ các chuyên đề trọng tâm: Phương trình bậc hai & Vi-ét, Lập PT/Hệ PT, Tứ giác nội tiếp, Hệ thức lượng, Bất đẳng thức Cauchy AM-GM, Parabol, Phương trình chứa căn, Tọa độ Oxy, Tổ hợp & Xác suất, Hình học không gian vuông góc, Ứng dụng đạo hàm & tối ưu, Tích phân & diện tích hình phẳng.

3. **Thao tác 1-Click Tiện lợi**:
   - ✏️ **Mở trong Xưởng để sửa**: Tự động nạp toàn bộ cấu hình vào Xưởng tạo Skill (`index.html`) để tiếp tục tinh chỉnh 8 bước.
   - 👁️ **Xem chi tiết / SKILL.md**: Xem trước nội dung chuẩn cho Claude, Google Antigravity hoặc System Prompt cho ChatGPT.
   - 🚀 **Phòng Thử nghiệm Gia sư AI (Interactive Playground)**: Trò chuyện và kiểm tra phản xạ Socratic của gia sư ngay trên trình duyệt mà không cần cài đặt.
   - ☁️ **Mở trực tiếp trên Google Drive**: Nhấp mở nhanh từng tệp trên Google Drive.
   - 💾 **Lưu từ Xưởng lên Drive**: Tại Bước 8 của Xưởng, bấm nút *"☁️ Lưu vào Kho Skill Drive (APP SKILL)"* để đưa skill mới thiết kế vào kho quản trị.
