# Relation Model

- Miền giác trị là 1 khoảng giá trị mà thuộc tính có thể lấy

$$Dom(grades) = |grades| = [0..10]$$

- Giá trị của thuộc tính là giá trị nguyên tố 

- null : không/chưa có giá trị

# Relation Schema and Instance
instructor(ID,name,...)


instance = current value

Relation is unorderd

## Relation Database

Tập hợp những quan hệ có liên quan với nhau 

Mối quan hệ thể hiện sự liên kết giữa 2 hay nhiều mối quan hệ (1 hoặc nhiều khóa chung)

## Keys 
$$K \subseteq R(A1, A2,...,)$$

- K là siêu khóa (superkey) nếu K miêu tả duy nhất 1 dòng trong bảng
- Khóa ứng viên là những khóa mà ta có thể chọn làm khóa chính (siêu khóa nhỏ nhất)
- Khóa chính : mỗi quan hệ có duy nhất một khóa chính, chọn trong khóa ứng viên, underline , có thể có nhiều thuộc tính 
- Khóa ngoại :Primary key or unique , appeared in other table, stike underline 
- Ràng buộc là những quy định áp đặc lên CSDL, đảm bảo tính toàn vẹn của dữ liệu 
  - ex : primary key != null && unique
  - ràng buộc kiểu dữ liệu 



