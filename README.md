# solid_oop

#solid là gì,
#tại sao phải dùng solid
#solid qua từng ví dụ
#tác dụng của solid
# ĐẶT VẤN ĐỀ
  Ở đây mình sẽ lấy một mô hình MVC làm ví dụ, cụ thể là laravel. 
  Bạn sẽ gặp vấn đề gì, vấn đề phổ biến nhất đó là việt mọi logic vào trong controller, controller sẽ bị phình to
  Khó maintain hơn, khó phát triển thêm logic trong chức năng đó hơn.
  Ví dụ logic đặt đơn hàng: 
    - lấy item từ trong giỏ hàng,
    
    - lấy lại thông tin mới từ shop, 
    
    - lưu thông tin địa chỉ, 
    
    - lưu ghi chú của khách hàng,
    
    - logic mã giảm giá,
    
    - tính toán giá tiền,
    
    - Và cuối cùng là tạo đơn hàng mới.
    
Sẽ như thế nào khi những logic nhỏ bên trong thay đổi liên tục

