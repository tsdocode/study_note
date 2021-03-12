# Tổng quan chức năng hệ điều hành
 ## Hệ điều hành : hệ thống các chương trình:
 -  Ở giữa phần cứng và môi trường giao tiếp với user
 -  Quản lý cấp phát tài nguyên
 -  Cung cấp các dịch vụ
 -  Môi trường sử  dụng các dịch vụ 

----

## Mode hoạt động:
-   User mode
-   Kernel mode: Điều khiển của HĐh


## Chức năng

### 1. Tổ chức quan lý phân phối tài nguyên:
- MS-DOS : 1mb
- XP x86: 4GB

### 2. Giả lập máy tính mở rộng: (hệ thống mà user dùng)
- Cung cấp các dịch vụ
-  Cung cấp các giao tiếp logic cho user sử dụng các dịch vụ
-  Biến đổi các yêu cầu của user thành tín hiệu điều khiển phần cứng
-  Che giấu hoạt động và data hệ thống


## Thành phần:
- Quản lý tiến trình
- Quản lý bộ nhớ
- Hệ thống tập tin
- Nhập xuất I/O
- Quản lý thiết bị lưu trữ
- Quản lý mạng
- Hệ thống bảo vệ
- Hệ thống dịch lệnh


## Các dịch vụ :
- Giao tiếp với người dungf: (Ui)
    
    CLI (command line), GUI

- Thực thi chương trình
    Nạp CT, thực thi CT, hủy CT

- Hoạt động xuất nhập

- Quản lý hệ thống file
- truyền thông tin
- Xác định là xử lý lỗi


Dịch vị hệ thống:
- Cấp phát tài nguyên
- Kiểm toán
- Bảo vệ an toàn hệ thống

---

## System Call
k/n : Lời gọi thệ thống phát sinh khi tiên trình sử dụng các dịch vụ do OS cung cấp

Chương trình con cộng 2 số lấy từ stack sau đó đưa lại stack

---

## Cấu trúc hệ điều hành 