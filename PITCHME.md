### Đặc tả phần mềm( Specifications )
#### Giới thiệu

- Đặc tả phần mềm kết nối khách hàng với đội ngũ phát triển lại với nhau:
    -  Khách hàng có thể chắc chắn phần mềm làm ra sẽ có những tính năng một cách chi tiết mà họ muốn
    -  Đội phát triển sử dụng tài liệu này để triển khai thiết kế và cài đặt những tính năng mà khách hàng yêu cầu
---
- Trong các phương thức theo kiểu agile, tài liệu đặc tả một hệ thống sẽ được hoàn tất trong giai đoạn cuối của quá trình xây dựng hệ thống vì:
    - Khi lập trình viên bắt tay vào xây dựng chi tiết ở các tầng phía dưới sẽ nảy sinh một số vấn đề không lường trước
    => Phải chỉnh sửa tài liệu đặc tả và cập nhật với khách hàng.
---

#### Xử lý các yêu cầu (Requirements Process)
- Các yêu cầu quy trình được chia ra làm 2 nhánh chính:
    - Các yêu cầu chức năng (Những gì hệ thống có thể thực hiện ?)
        + vd: người dùng có thể đăng xuất với 1 click
    - Các yêu cầu phi chức năng (Những gì hệ thống nên có ?):
        + vd: người dùng có thể đăng nhập bằng tài khoản google, phần mềm có khả năng chạy trên cả điện thoại lẫn máy tính,..
---
- Mỗi bên liên quan( stackholders) có thể có các yêu cầu phi chức năng khác nhau
    - Khách hàng quan tâm đến tính dễ sử dụng, hiệu năng, khả năng nâng cấp,..
    - Đội phát triển quan tâm đến độ tin cậy, độ phức tạp, khả năng kiểm thử, bảo trì,...
---
- Các yêu cầu phi chức năng có thể mâu thuẫn với nhau
    - VD: đội phát triển cần 1 phần mềm có ít cài đặt phức tạp nhưng khách hàng lại muốn phần mềm có hiệu năng cao( cần phải cài đặt phức tạp)
    - => Các bên liên quan cần phải thống nhất với nhau về độ ưu tiên của các yêu cầu phi chức năng
- Lưu ý: Khi làm tài liệu về yêu cầu ta chỉ cần chỉ rõ những việc hệ thống sẽ làm chứ không cần quan tâm hệ thống sẽ làm những điều đó bằng cách nào

---
#### Đặc điểm của các yêu cầu( Requirements Properties)
- Các yêu cầu phải đảm bảo 4 điều kiện:
	- Hoàn thiện
	- Nhất quán
	- Chính xác
	- Xúc tích	
	
---
#### Thu thập yêu cầu( Requirements Elicitation)
Quá trình đặc tả phần mềm là lặp đi lặp lại các bước:
- Thu thập(Elicitation): Các bên liên quan cùng nhau đưa ra các yêu cầu cho phần mềm và chỉ rõ những yêu cầu nào sẽ được thực hiện/không được thực hiện
- Phân tích(Analysis): Kiểm tra những yêu cầu đã được thu thập để chắc chắn các yêu cầu là nhất quán và không ảnh hưởng đến các yêu cầu còn lại
- Cụ thể hóa(Reification): Thể hiện yêu cầu dưới dạng ngôn ngữ quy chuẩn đã có ( vd: user cases hoặc user stories )
- Thẩm định(Validation): Mang danh sách các yêu cầu để xác nhận lại với khách hàng
--- 

#### Các yêu cầu khác (Additional Requirements)
- Giàng buộc thiết kế (Design Constraints) 
- Giàng buộc về môi trường(Environmental Constraints)
- Sở thích của khách hàng( Preference)

---

## Xác nhận yêu cầu (Validating Requirements)

- Yêu Cầu

- Lợi ích

- Nội dung

---

## Yêu Cầu

- Việc đưa ra các yêu cầu phải dựa vào các thông tin có ý nghĩa.

- Phù hợp với yêu cầu khác hàng.

- Xác định được giá trị mà chức năng nó mang lại.

- Xác nhận yêu cầu là 1 bước quan trọng quá trình làm phần mêm !!!

---

## Lợi ích

- Trên thực tế các yêu cầu rõ ràng dễ thành công hơn các yêu cầu mơ hồ.

- Lập trình viên có thể hiểu và đánh giá các chức năng được yêu cầu.

- Lập trình viên và khách hàng có cùng một mục tiêu.

---

## Nội Dung 

- Chúng ta thường tìm thấy vấn đề trong quá trình làm phần mềm 

- Một số yêu cầu dễ thấy ta có thể viết thành 1 danh sách và làm theo danh sách

- Thực tế thì các yêu cầu phức tạp hơn nên ta xác định và đánh giá các yêu cầu bằng cách đánh giá hiệu suất.

---

## Nội Dung 
### Hiệu suất

- Có thể hiểu theo nhiều cách khác nhau nhưng có thể hiểu theo 2 cách:

   + Thời Gian

   + Lưu trữ hoặc không gian

---

## Hiệu suất
### Thời gian
- Thời gian phản ứng( Thông lượng):

   + Giờ cao điểm: vd hệ thống có thể xử lí 50 người / giây.

   + Bình thường: 10 giao dịch / giây
    
- Thời gian trả lời:

   Vd: Hệ thống trả lời người dùng trong 150 mili giây.

---

## Hiệu suất
### Lưu trữ

- Bộ nhớ

- Ổ đĩa

---

# **USER STORIES**
---
1. ROLE - GOAL - BENEFIT 
2. LIMITATIONS
3. DEFINITION OF DONE
4. ENGINEERING TASKS
5. EFFORT ESTIMATE

---
# ROLE - GOAL - BENEFIT 
	- 	Hiểu được mục tiêu, lợi ích những gì họ đang làm.
	-   Thêm, bớt tính năng có làm tăng giá trị sản phẩm?

---
# LIMITATIONS
	-	Những hạn chế của tính năng.

---
# DEFINITION OF DONE
	-	Xác nhận tính hoàn thiện của tính năng.	

---
# ENGINEERING TASKS
	-	Có giá trị cho đội ngũ phát triển.
	-	Theo dõi các tính năng tương tác với nhau trong hệ thống.

---
# EFFORT ESTIMATE
	-	ước tính chi phí tổng thể của một sản phẩm.
	-	Có nên thêm tính năng cho sản phẩm? chi phí so với hiệu quả của tính năng?


