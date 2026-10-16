# Bài 3 : Giảm chi phí vận hành Chatbot AI
## Phần 1. Phân tích bài toán: Giải thích tại sao Markdown lại giúp AI xử lý nhanh hơn dựa trên cơ chế chia nhỏ Token.
AI không đọc từng chữ cái hay nguyên vẹn một từ, mà chia văn bản thành các đoạn mã nhỏ gọi là Token (có thể là một từ, một phần của từ, hoặc ký tự đặc biệt).
Mỗi token đều tốn chi phí tính toán.
Markdown sử dụng các ký tự đại diện cực kỳ ngắn gọn và trực quan (ví dụ: **in đậm**, # tiêu đề, - danh sách).
Các ký tự này thường được gom nhóm hoặc chiếm số lượng token tối thiểu, giúp tiết kiệm số lượng token so với việc dùng HTML tương đương. Nhờ đó, AI tạo văn bản nhanh hơn, giảm độ trễ và tiết kiệm chi phí vận hành đáng kể cho hệ thống GreenTech.
## Phần 2. So sánh & Đánh giá:Lập bảng so sánh Markdown và HTML. Đưa ra giải pháp tối ưu cho hệ thống "GreenTech" và lập luận lý do.
---
| Tiêu chí | Markdown | HTML |
|  :---  |  :---  |  :---  |
| ki hiêu | đơn giản như: (##,**) | phức tạp hơn (<tag>...</tag>) 
Tiêu thụ Token | tiết kiệm hơn có thể tái sử dụng | tốn kém hơn do lãng phí Token cho các thẻ cú pháp
độ dễ đọc | dễ hơn tại sài văn bản thô |những kí hiệu phức tập  gây rối mắt0 
tốc độ xử lí AI | nhanh hơn | chậm hơn tại có nhiều kí tự phức tạp hơn
---
Giải pháp tối ưu cho hệ thống "GreenTech":là Markdown để giúp tiết kiệm chi phí Token và thời gian,dùng văn bản thô nên dễ hơn