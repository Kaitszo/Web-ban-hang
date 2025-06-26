🧑‍🎓 Thông tin sinh viên

Họ và tên: Trần Xuân Thành

Mã sinh viên: 23010160

Lớp: K17_CNTT-2

Môn học: Web nâng cao (TH3)

🎯 Giới thiệu dự án (Giữa kỳ)

Website bán quần áo thời trang là một hệ thống thương mại điện tử cơ bản được xây dựng bằng Laravel Framework, cho phép người dùng duyệt, tìm kiếm và mua các sản phẩm thời trang như áo, quần, phụ kiện Ngoài ra, admin có thể quản lý sản phẩm, đơn hàng và người dùng.

Sơ đồ khối

![Image](https://github.com/user-attachments/assets/d0e30983-3a9d-4e03-bc3e-95a7c3a0400d)


⚙️ Sơ đồ chức năng

![Image](https://github.com/user-attachments/assets/25b73820-f476-4382-ac0d-37e81f600cb8)

Sơ đồ thuật toán

Guest browse product

![Image](https://github.com/user-attachments/assets/ad345b93-c7a1-453a-a97f-7edd46a37788)


Add to cart

![Image](https://github.com/user-attachments/assets/77bdb994-a7c1-46dc-bf63-61a24d67e1e6)


View cart

![Image](https://github.com/user-attachments/assets/51a6d015-6b30-4c1c-b336-01a82c75a406)


Login

![Image](https://github.com/user-attachments/assets/ed3590ca-f518-4add-884b-9f849ba51090)


Admin Crud Products

![Image](https://github.com/user-attachments/assets/9c644580-a6f8-4ee3-b53c-83a306524a9d)


--Một số Code chính minh họa

--Model: Cart

![Image](https://github.com/user-attachments/assets/6caed8c5-d2ee-4ada-8095-d47c8c98b2db)

--Model:Product

![Image](https://github.com/user-attachments/assets/6e5be94a-2cdc-40d9-b20d-beb111b741e8)

--Model:Custumer

![Image](https://github.com/user-attachments/assets/def6adad-c14e-4ca5-ab43-4e7048e33c93)

--Chức năng định danh và xác thực (User) 

![Image](https://github.com/user-attachments/assets/1d6d4a5b-ed81-44ea-904e-705e20f20b0c)

--Controller: Phương thức CRUD cho Cart

![Image](https://github.com/user-attachments/assets/fb3ad720-8ed6-40c0-8000-f2f67134eedb)
--View: Blade template Cart
![Image](https://github.com/user-attachments/assets/769e5af6-f1c7-41b8-8be2-c04ccd276d35)
--Authentication/Authorisation: LoginController 
![Image](https://github.com/user-attachments/assets/29fa8500-e501-4e4b-bc02-f412cff260af)

--Bảo mật

CSRF

![Image](https://github.com/user-attachments/assets/8e2a390a-441d-42c0-b077-b62d7f760e31)

--Kiểm tra đầu vào ( Ví dụ trong LoginController)

![Image](https://github.com/user-attachments/assets/a1c8638e-d46c-4a0e-b98d-b9f53ba27338)

-- Authentication ( Ví dụ trong LoginController)

![Image](https://github.com/user-attachments/assets/3520dd64-cd36-4095-b555-326434045d98)

![Image](https://github.com/user-attachments/assets/12b06698-9725-46d0-b5df-2eed2c0388ba)

--SQL INJECTION ( Ví dụ trong SliderService)

![Image](https://github.com/user-attachments/assets/4918c77e-d780-4c1c-b816-77ac659e53ad)

-- Session & Cookie

![Image](https://github.com/user-attachments/assets/9aedd7d4-a03a-41ca-a9c4-c35b03a1b262)


--Hướng dẫn cài đặt
 YÊU CẦU CÀI ĐẶT HỆ THỐNG
1. Phần mềm

-Laragon để chạy trên một server riêng biệt

-Trình duyệt: Chrome, Firefox, Safari, Edge

 Phần cứng
RAM ≥ 8GB
 
--Cách sử dụng

-tạo một folder 

-đặt tên folder ví dụ là shop

-git clone từ link https://github.com/Kaitszo/Web-ban-hang.git về folder
-sao chép thư mục rồi dán vào folder chứa laragon với đường dẫn Vị trí cài phần mềm laragon :\laragon\www

-Khởi chạy laragon

![Image](https://github.com/user-attachments/assets/8544f312-4361-44bd-85e9-8608e7d2ca30)
-vào google chọn đường dẫn như cấu hình đã hiển thị ví dụ shop.test

--Hướng dẫn sử dụng

1. Đăng ký & Đăng nhập

2.Người dùng truy cập trang chủ, nhấn Đăng ký để tạo tài khoản mới hoặc Đăng nhập nếu đã có tài khoản.

3. Sau khi đăng nhập thành công, người dùng có thể truy cập các chức năng mua sắm.

4. Xem & Tìm kiếm sản phẩm
Trên trang chủ, người dùng có thể xem danh sách các sản phẩm quần áo thời trang.
Có thể tìm kiếm sản phẩm theo tên, danh mục, giá hoặc các bộ lọc khác.


5. Thêm sản phẩm vào giỏ hàng
Tại trang chi tiết sản phẩm, chọn số lượng và nhấn Thêm vào giỏ hàng.
Sản phẩm sẽ được thêm vào giỏ hàng của người dùng.

6. Quản lý giỏ hàng
Nhấn vào biểu tượng Giỏ hàng để xem các sản phẩm đã chọn.
Tại đây, người dùng có thể:
Thay đổi số lượng sản phẩm.
Xóa sản phẩm khỏi giỏ hàng.
Nhấn Cập nhật giỏ hàng để lưu thay đổi.

7. Đặt hàng
Sau khi kiểm tra giỏ hàng, nhấn Thanh toán.
Nhập thông tin giao hàng, xác nhận đơn hàng.
Hệ thống sẽ lưu đơn hàng và gửi thông báo xác nhận.

8. Quản lý tài khoản
Người dùng có thể cập nhật thông tin cá nhân, đổi mật khẩu trong mục Tài khoản.

9. Quản trị viên
Đăng nhập bằng tài khoản admin để truy cập trang quản trị.

Quản trị viên có thể:

Thêm/sửa/xóa sản phẩm, danh mục.

Quản lý đơn hàng, người dùng.

Xem thống kê bán hàng.

📸 Một số hình ảnh

--Giao diện người dùng sản phẩm

![Image](https://github.com/user-attachments/assets/cf961097-430f-4bbb-a55e-787f88627c9f)

![Image](https://github.com/user-attachments/assets/ff92878e-b852-490f-b58d-2781695b5781)

![Image](https://github.com/user-attachments/assets/588d3efe-18b8-495b-80db-6684e7ec3c0d)

![Image](https://github.com/user-attachments/assets/82e3abe2-8515-4a78-931a-e847729ff3de)

![Image](https://github.com/user-attachments/assets/8a917e3c-f164-4bf8-8d2c-f242f8232b81)


![Image](https://github.com/user-attachments/assets/58470f90-c84e-42a9-8291-8c90b6ad0a1d)

--Giỏ hàng
![Image](https://github.com/user-attachments/assets/7aa68f43-6918-4166-b472-70dc6c50b5f8)

![Image](https://github.com/user-attachments/assets/b3253566-e805-4060-b736-b8f104c5b844)

--Trang quản lý admin
![Image](https://github.com/user-attachments/assets/7099e600-cf0f-43ea-8b6c-43b9b8f54285)

![Image](https://github.com/user-attachments/assets/ae878ea1-3add-49b8-9dc5-177a89e04f92)

![Image](https://github.com/user-attachments/assets/290b9b27-cf4d-469a-9d94-a8f210749b3e)

![Image](https://github.com/user-attachments/assets/4c2a8719-72c3-4243-908c-d649a885ff2c)

![Image](https://github.com/user-attachments/assets/eeb1798a-5b8e-4d8b-9a6b-4cef57fab55e)

![Image](https://github.com/user-attachments/assets/99cf6bc0-43f3-486f-af2c-ec12b7587f0b)

![Image](https://github.com/user-attachments/assets/c1818a44-c646-43ee-97cc-11f7b83c8af9)

![Image](https://github.com/user-attachments/assets/14e08522-fa4e-4031-9d8b-d8beb46d2af0)

--Giao diện đăng nhập 

![Image](https://github.com/user-attachments/assets/2a5d81d9-30ae-4198-80ef-cb085e8ece95)

--Giao diện database

![Image](https://github.com/user-attachments/assets/1a1b23af-092a-4302-854c-67445bdf1cd3)

![Image](https://github.com/user-attachments/assets/ade757d0-1fc2-43d7-b9bd-bceef395f467)



🌐 Public Link

Link GitHub repo: https://github.com/Kaitszo/Web-ban-hang

Link video https://youtu.be/O2PVyXlikCM

Mọi thắc mắc vui lòng liên hệ email:thanhtb2005@gmail.com






















