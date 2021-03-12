# Ethernet

***using in Lan***

Các thành phần:

- Hardware: card, connector, cable(độ dài, chất lượng, giá thành)
  - Thiết bị kết nối (hub, repeater, switch, router, bridge)
- Sofware: Dịch vụ : (Google)
  - Protocol (HTTP)
  - Services (Web)
  - Interfaces: Giao diện tiếp xúc (Browsers )
---
Email:
- Gửi (SMTP / IMAP)
- Nhận (POP3)
---
- Backbone : trục chính
- Segment: Phân đoạn mạng (thiết bị tập trung - thiết bị tập trung)
- Reapter: Bộ lặp lại
- Hub: Bộ tập trung
- Switch: Bộ chuyển mạch 
- Server: Máy chủ
- Workstation: Trạm làm việc

---
### Lan Protocol

Random Access: **CSMA/CD (Star)** , Slotted ring
Control Access: **Token Ring, Token Bus**, Conllision Avoidance 

---
NIC card : Bộ giao tiếp mạng
Khe cắm: ISA, PCI, USB
10/100/1000 Mbps
---
Reapter (Lặp lại):
Khôi phục , khuếch đại tín hiệu
Tầng Physical, tốc độ nhanh 
- Không thể mở rộng theo chiều ngang (1 in 1 out)
---
flood 


Hub (bộ tập trung)
- Tầng physical
- Tính chất broadcast
- Dễ xảy ra nghẽn thông tin => số lượng máy tính ít  
- Không dùng cáp đồng trục, chủ yếu dùng cáp xoắn


Access Point như hub nhưng phát sóng


- The Congestion Problem

---

Bride:

- Cầu  nối giữ các mạng
- Chia mạng thành các đoạn nhỏ hơn
- Lớp Datalink
- Cho phép mở rộng cùng 1 mạng logic với nhiều kiểu cáp khác nhau
- Nhược ddieemr: chậm hơn Repeater

---
Switch
- như bridge nhưng nhiều port hơn
- Tầng Datalink
- Lưu chuyển frame ether
- Xem xét header frame và chọn chuyển tiếp frame dựa theo địa chỉ MAC
- Khi frame chuyển tiếp trên đoanh, dùng CSMA/CD để truy cập đoạn
- 2960-X: 
  - Tầng 2
  - X tốc độ 1Gbps
  - 0 X tốc độ 100 Mbps
  
  switch hoc các interface
  Time stamp <= 60p
  Phân chia độc lập các subnet trở thành vùng tranh chấp

  Truy cập độc quyeenf:
  Cut-through switching: Cắt nhỉ các frame 