# Phần 1:
1. In-Context Learning là khả năng giúp AI học thông qua hướng dẫn bạn đưa vào mà không cần huấn luyện lại mô hình.
2. Cơ chế hoạt động:
- Bạn cung cấp ví dụ và yêu cầu cho AI.
- AI phân tích các ví dụ và phân tích được quy luật.
- AI áp dụng quy luật đó vào các tài liệu mới bạn đưa vào.
- AI đưa ra kết quả phù hợp với quy luật bạn cung cấp
3. Ưu điểm của Few-shot:
- Few-shot giúp AI hiểu ngữ cảnh tốt hơn nhờ có ví dụ cụ thể.
# Phần 2: Prompt cho AI
```
Phân loại cảm xúc đánh giá sản phẩm công nghệ thành TÍCH CỰC hoặc TIÊU CỰC. Chú ý phát hiện các câu nói mỉa mai, khen đểu.

Ví dụ 1 (Nhiệt độ):
Input: "Máy đẹp mê ly, mùa đông ôm chơi game khỏi cần lò sưởi vì CPU lên tận 98 độ!"
Output: TIÊU CỰC (Lý do: Khen đểu máy quá nóng, nhiệt độ 98 độ là mức nguy hiểm).

Ví dụ 2 (Pin):
Input: "Pin trâu cực kỳ, ngày sạc có 3 lần giúp mình đi lại vận động rèn sức khỏe luôn."
Output: TIÊU CỰC (Lý do: Mỉa mai pin yếu, phải cắm sạc liên tục).
---
Hãy phân loại đánh giá sau:
Input: "Màn hình nét căng, mỗi tội vừa mở máy lên quạt đã kêu như máy bay phản lực."
```
Output:
Kết quả AI sẽ trả về:

TIÊU CỰC (Lý do: Mỉa mai quạt tản nhiệt kêu quá to và ồn).
