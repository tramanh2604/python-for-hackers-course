# API là gì?
API (application programming interface) - giao diện giúp các ứng dụng giao tiếp được với nhau.
Lý do sử dụng API:
+ Gửi và nhận data 
+ Tự động hóa quy trình
+ Kết nối giữa các dịch vụ và ứng dụng

# Các loại API phổ biến
### 1. RESTful API
- Sử dụng HTTP, tuân theo chuẩn REST
- Là dạng phổ biến nhất hiện nay

### 2. SOAP API
- Dựa trên XML, dùng trong ứng dụng doanh nghiệp

### 3. GraphQL API
- Cho phép client yêu cầu chính xác, linh hơn data hơn REST

### 4. WebSocket API:
- Dùng cho giao tiếp thời gian thực: game online, chat...

# HTTP
### 1. Phương thức (HTTP methods)
- GET: lấy data
- POST: gửi data mới
- PUT: cập nhật data
- DELETE: xóa data

### 2. HTTP status code
- 200: ok
- 400: yêu cầu k hợp lệ
- 401: k đc phép
- 404: not found
- 500: error server

# Định dạng data
- Phổ biến nhất để truyền qua API là JSON
- XML: thường dùng trong SOAP API

# FUFF
FUFF là 1 API fuzzers, là công cụ dùng để kiểm tra bảo mật API bằng cách tự động gửi các request với data bất thường, k hợp lệ để xác định lỗi, lỗ hỏng.

# Project
Tuy nhiên FUFF chỉ thực hiện việc gửi, mà không trả các kết quả của request.

Project là đoạn source code đơn giản bằng Python để xem kết quả trả về của request và các endpoint.

Trong video clip, dùng api từ box backend của Hackthebox, nhưng mình sẽ dùng API từ JSONPlaceholder (bạn có thể dùng bất kì API nào bạn muốn)

**Mình sẽ tìm hiểu phần này sau, vì clip nói khá nhanh**
