# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Student grades (dữ liệu điểm)
- Student accounts (tài khoản sinh viên)

**CIA mapping:**
- Sự cố A -> Availability
- Sự cố B -> Integrity
- Sự cố C -> Confidentiality

**Phân tích sự cố B:**
- Threat: Unauthorized user thay đổi điểm trái phép
- Vulnerability: Mật khẩu yếu, không phân quyền rõ, không có log
- Mitigation: MFA, RBAC, ghi log hệ thống

### 4. Kết luận ngắn
Qua bài lab này, em hiểu rõ hơn về bộ ba CIA và cách áp dụng vào phân tích hệ thống. Em nhận thấy việc xác định đúng tài sản và rủi ro là rất quan trọng. Phần khó nhất là phân biệt threat và vulnerability. Ngoài ra, em cũng học được cách sử dụng GitHub để quản lý và nộp bài.
