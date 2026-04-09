Họ và tên: Phạm Ánh Tuyết
MSSV: 1871020643
Lớp/Nhóm: CNTT 18-02

## 1. Assets
Asset 1: Student grades (dữ liệu điểm)
Asset 2: Student accounts (tài khoản sinh viên)

## 2. Mapping CIA
Sự cố A -> Availability
Sự cố B -> Integrity
Sự cố C -> Confidentiality

## 3. Phân tích sự cố B
Threat: Unauthorized user thay đổi điểm trái phép

Vulnerability:
- Mật khẩu yếu
- Không phân quyền rõ
- Không có log

Mitigation:
- MFA
- RBAC
- Logging

## 4. Reflection
I would prioritize integrity because incorrect grades directly affect students and reduce trust in the system.

## 5. Bonus Flag
FIT4012{A-A-B-I-C-C}
