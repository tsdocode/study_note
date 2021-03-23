# Điều phối tiến trình 

## 1. Giới thiệu
Đa phương:
- Cấp Phát CPU cho tiến trình
- Bảo vệ hoạt động của tiến trình
- Cấp phát tài nguyên 
- Thu hồi CPU và tài nguyên

## 2. Tổ chức điều phối:
- Ready List: đợi cấp phát CPU
- Waiting List: Blocked
- DS tiến trình đợi cấp phát tài nguyên


Phân loại tiến trình :
- Tiên trình hướng I/O
- Tiên trình hướng xử lý


- Điều phối tác vụ: chọn tác vụ
- Điều phối tiến trình : chọn tiến trình
- Điêu phối trung gian: CHọn tác vụ và tiến trình

## 3. CT điều phối :
Chức năng :
    Tạo và quản lý các DS điều phối
    Đưa ra quyết định điều phối

Đk Kích hoatj:
- Tạo, chuyển, kết thúc TT
- TT yêu cầu TN
- Giải phóng TN
- Yêu cầu của TT


## 4. CT phân phối

Chức năng :
- Chuyển ngữ cảnh
- Thu hồi và cấp CPu cho tiến trình


ĐK :
Tiên trình chuyển trạng thái

## 5. Chiên lược điều phối - Thuật toán lập lịch
Mục đích :
- Sử dụng tối đa công xuất CPU
- Đáp ứng tối đa các tác vụ trong 1 đơn thị thời gian
- Tối thiểu thời gian chờ
- Tối thiểu thời gian đáp ứng

Đánh giá :
- Thời gian chờ của tiến trình
- Thời gian hoạt động của TT
- Hiệu xuất sửa dụng CPU
  

- Giải thuật điều phối


### 1. FCFS (First Come First Server):
- Cấp CPU theo thứ tự trong Ready List, tả lại CPU khi thực hiện xong

### 2.SJF:
- Ngắn thực hiện trước
- Đặt quyeenf: TT xong mới trả lại CPU
- Không đặc quyền : TT bị thu hồi CPU khi hết quyền ưu tiên hoặc thực hiện xong

### Round Robin

Mỗi tiến trình được cấp CPU theo thứ tự co trong ready list được cấp 1 khaongr thời gian nhỏ quantum.
TT bị thu hồi khi hết Quantum hoặc thực thi xong


