Lab 01 Answers  
CIA & Risk: Hệ thống lưu điểm  

Họ và tên: Phạm Ánh Tuyết 
MSSV: 1871020643 
Lớp/Nhóm: CNTT 18-02


## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

Asset 1: Student grades (dữ liệu điểm)  
Asset 2: Student accounts (tài khoản sinh viên)  
Asset 3 (nếu có): Database và hệ thống đăng nhập  

## 2. Mapping CIA
Ghép từng sự cố với CIA.

Sự cố A -> Availability  
Sự cố B -> Integrity  
Sự cố C -> Confidentiality  

## 3. Phân tích sự cố B

Threat:  
Unauthorized user hoặc insider thay đổi điểm trái phép.  

Vulnerability:  
- Mật khẩu yếu  
- Không có phân quyền rõ ràng  
- Không có hệ thống log  
- Không có xác thực nhiều lớp (MFA)  

Mitigation:  
- Áp dụng MFA  
- Phân quyền theo vai trò (RBAC)  
- Ghi log tất cả thay đổi điểm  
- Yêu cầu phê duyệt khi sửa điểm  


## 4. Reflection

If I were a system administrator, I would prioritize fixing the integrity issue first because incorrect grades can directly affect students’ academic results and trust in the system. Ensuring data accuracy is critical. After that, I would improve availability and confidentiality by strengthening authentication and monitoring systems.


## 5. Bonus Flag
FIT4012{A-?-B-?-C-?}

Flag của em: FIT4012{A-A-B-I-C-C}
