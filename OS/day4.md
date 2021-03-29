## Liên lạc giữa các tiến trình
1. Bảng tín hiệu 
2. Truyền thông điệp 
- Send and recieve
- Điều kiện:
    - dùng bộ nhớ dùng chung 
    - Trao đổi thông báo trên cơ sở Send - recieve

- Truyền trực tiếp :
+   Send(P1, msg)
+   Recieve(msg, P2)

- Gián tiếp:
+ Tạo hộp thư, hủy, gửi nhận
- Vấn đề dùng chung hợp thư, mất tính trực tiếp (bảo mật)
+ Biện pháp: 
    - chỉ cho phép 1 tiến trình nhận thông báo
    - ...

---

Các dạng truyền thông điệp:
    chuẩn hóa
- Blocking send
- Blocking recieve

Thông điệp gửi nhận hoàn chỉnh 

---
Bất đồng bộ:
- Non Blocking send
- Non Blocking recieve

Thông điệp nhận/gửi không hoàn chỉnh, có thể thất bại

---
Client - Server

- Máy cung cấp dịch vụ = server 

- **Socket** , RPC, RMI

- Cấp độ 1: Máy A gửi nhận thông báo máy B
- 2: Máy A nhìn thấy hoạt động máy B
- 3: máy A can thiệp hoạt động máy B

--- 

Socket:
- TCP/IP
- Cấu trúc socket: IP:Port(16 bit)
- TT liên lạc giữa 1 cặp socket 


---
## Đồng bộ tiến trình
truy xuất độc quyền:
- TN không dùng chung
- TN dùng chung nhưng không truy xuất đồng thời

Phối hợp để hoàn thành tác vụ

---
- Tranh đoạt điều khiển
- Miền găng : đoạn chương trình có khả năng xảy ra mâu thuẩn khi truy xuất đến TN dùng chung
- Cấu trúc lại chương trình 

- Giải pháp: Peterson, test and set, Wakeup, Semaphore, Monitor

---
### Semaphore : cờ hiệu 
S là một số nguyên không âm 


Sinal(S) : S++;
Wait(S: (S > 0)? S-- : S > 0 => S = 0;

- Truy xuất độc quyền
Thực hiện đan xen đến khi S > 0 thì đổi tiến trình 
- Hoạt động phối hợp:
    - Tác vụ 1 -> tác vụ 2 -> ....


---

Deadlock

Nguyên nhân: 
- Truy xuất đọc quyền
- Đang giữ Tn và yêu câù thêm TN
- TT chỉ trả
- Tồn tại chu trình trong đồ thị cấp phát TN
