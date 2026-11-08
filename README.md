# BÀI 3: SỬ DỤNG AI AN TOÀN KHI XỬ LÝ LỖI PHẦN MỀM

## 1. Mục tiêu

Biết cách sử dụng AI để hỗ trợ xử lý lỗi phần mềm, đồng thời kiểm tra lại thông tin trước khi thực hiện các câu lệnh trên máy tính.

## 2. Phân tích theo mô hình IPO

### 2.1. Input (Đầu vào)

- Lỗi gặp phải: `Path not found` khi cài đặt Python.
- AI đưa ra một câu lệnh yêu cầu người dùng sao chép và dán vào Terminal.
- Câu lệnh có dấu hiệu lạ, có thể thay đổi cấu hình hoặc can thiệp vào hệ thống.

### 2.2. Process (Quá trình xử lý)

Em sẽ không thực hiện ngay câu lệnh AI đưa ra mà tiến hành kiểm chứng theo các bước:

**Bước 1: Kiểm tra câu lệnh**

- Đọc và tìm hiểu từng thành phần của câu lệnh.
- Xác định câu lệnh có xóa dữ liệu, thay đổi hệ thống hay yêu cầu quyền quản trị không.

**Bước 2: Tìm kiếm thông tin**

Sử dụng Google với toán tử tìm kiếm:

`site:stackoverflow.com "Path not found" Python`

Hoặc truy cập trang chủ Python để kiểm tra hướng dẫn cài đặt chính thức:

https://www.python.org/

**Bước 3: So sánh thông tin**

- Kiểm tra câu lệnh có được đề xuất bởi nguồn đáng tin cậy không.
- Đối chiếu với phiên bản Windows và phiên bản Python đang sử dụng.
- Nếu không tìm thấy thông tin xác thực, không thực hiện câu lệnh.

**Bước 4: Đánh giá độ an toàn**

- Nếu lệnh rõ ràng, đúng mục đích và được kiểm chứng: Có thể xem xét thực hiện.
- Nếu lệnh không rõ chức năng hoặc có nguy cơ gây mất dữ liệu: Không thực hiện.

### 2.3. Output (Đầu ra)

Kết quả mong muốn:

- Xác định được câu lệnh AI đưa ra có an toàn hay không.
- Tránh thực hiện những câu lệnh có thể gây ảnh hưởng đến máy tính.
- Tìm được cách sửa lỗi phù hợp từ nguồn đáng tin cậy.

**Kết luận:** Không nên tin tưởng và thực hiện ngay mọi câu lệnh do AI cung cấp. Cần kiểm tra trước khi sử dụng.

## 3. Thiết kế Prompt hỏi ngược lại AI

Khi AI đưa ra một câu lệnh lạ, em sử dụng Prompt sau để yêu cầu AI giải thích:

"Bạn hãy phân tích câu lệnh sau trước khi tôi thực hiện trên Windows Terminal:

[Dán câu lệnh AI đã đưa ra]

Yêu cầu:
1. Giải thích chức năng của từng thành phần trong câu lệnh.
2. Câu lệnh có xóa dữ liệu hoặc thay đổi cấu hình hệ thống không?
3. Câu lệnh có yêu cầu quyền Administrator không?
4. Có rủi ro bảo mật hoặc gây ảnh hưởng đến máy tính không?
5. Câu lệnh có phù hợp với phiên bản Windows và Python của tôi không?
6. Đề xuất cách sửa lỗi an toàn hơn nếu có.

Nếu chưa đủ thông tin để xác nhận độ an toàn, hãy yêu cầu tôi cung cấp thêm thông tin. Không được khẳng định câu lệnh an toàn khi chưa có căn cứ."

## 4. Kết luận

Qua bài tập, em hiểu rằng AI chỉ là công cụ hỗ trợ, không phải lúc nào cũng đưa ra thông tin chính xác. Hiện tượng AI Hallucination có thể khiến AI cung cấp lệnh sai hoặc không phù hợp với hệ điều hành.

Vì vậy, em cần kiểm chứng thông tin từ Stack Overflow hoặc trang chủ phần mềm, hiểu rõ câu lệnh và đánh giá độ an toàn trước khi thực hiện để bảo vệ máy tính và dữ liệu cá nhân.
