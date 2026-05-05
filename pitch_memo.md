# Pitch Memo - SpeakMate AI

## 1. Audience

Pitch này dành cho **Seed VC**, cụ thể là **Touchstone Partners**. Trọng tâm không phải là khoe công nghệ voice AI, mà là chứng minh một insight thị trường: sinh viên Việt Nam không thiếu app học tiếng Anh; họ thiếu một môi trường đủ an toàn để nói sai trước khi nói đúng.

## 2. Problem

Sinh viên Việt Nam học tiếng Anh nhiều năm nhưng vẫn đứng hình khi phải nói. Vấn đề không chỉ là thiếu từ vựng hay grammar, mà là bị đánh giá quá sớm: mỗi lần nói sai trước bạn bè hoặc giáo viên đều làm họ càng né speaking. Trong Day 17, giả định rủi ro nhất là: sinh viên chỉ thực sự luyện speaking nếu trải nghiệm đủ an toàn và không khiến họ cảm thấy bị chấm điểm.

## 3. Solution

**SpeakMate AI** là app luyện speaking realtime với AI companion cho sinh viên sợ nói tiếng Anh. Người dùng nói chuyện bằng giọng nói với AI, nhận feedback nhẹ sau mỗi đoạn nói, và có context memory ngắn để cuộc trò chuyện cảm giác cá nhân hơn. MVP chỉ tập trung vào 3 việc: realtime voice conversation, feedback đơn giản sau khi nói, và ghi nhớ 3-5 thông tin trong session.

## 4. Aha Moment & Traction Logic

Aha Moment là khi một sinh viên nói được ít nhất **60 giây tiếng Anh liên tục** và nhận feedback đủ hữu ích mà không cảm thấy bị judge. MVP sẽ được beta với **1.000 sinh viên** qua CLB tiếng Anh và cộng đồng IELTS Speaking. Metric pass/fail là **>= 40% user hoàn thành một đoạn speaking >= 60 giây trong 7 ngày**, và retention target là **D7 >= 25%**. Đây là hành vi thật, không phải vanity metric như download hay page view.

## 5. Business Model & Unit Economics

Sản phẩm dùng mô hình subscription B2C với ARPU cơ sở **129.000 VND/tháng**. Với thị trường ban đầu **50.000 sinh viên có thể tiếp cận**, CAC cơ sở **250.000 VND**, churn giả định **5%/tháng**, LTV dự phóng đạt **1.580.000 VND**. LTV/CAC là **6,32x** và payback CAC khoảng **3,16 tháng**. Rủi ro lớn nhất là API voice cost, nên MVP sẽ giới hạn số phút voice theo plan và dùng text feedback rẻ hơn sau session.

## 6. Differentiator, Moat & Ask

Nếu OpenAI hoặc Duolingo thêm voice practice, SpeakMate AI không thắng bằng model tốt hơn. Moat ban đầu là **workflow + distribution + localized data**: onboarding được thiết kế để giảm cảm giác bị chấm điểm, tình huống luyện nói gần đời sống đại học Việt Nam, kênh phân phối qua CLB tiếng Anh/trường đại học, và learning loop từ transcript lỗi speaking phổ biến của sinh viên Việt Nam.

**Ask:** Gọi **3 tỷ VND seed** cho 12 tháng để hoàn thiện MVP realtime voice, beta test với **1.000 sinh viên**, chứng minh **>= 40% user nói được 60 giây/session** và **D7 retention >= 25%** trước khi mở rộng sang 50.000 sinh viên đầu tiên.
