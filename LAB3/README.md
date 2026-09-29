# LAB 3 - Hệ thống quản lý khách sạn

## 1. Thông tin sinh viên

* Họ và tên: Nguyễn Huỳnh Huy
* MSSV: 1250080073
* Tên bài Lab: LAB 3 - Hệ thống quản lý khách sạn

## 2. Môi trường thực hiện

* Visual Studio 2022
* C#
* Windows Forms (WinForms)
* Microsoft SQL Server
* SQL Server Management Studio (SSMS)
* GitHub

## 3. Nội dung đã thực hiện

Trong bài Lab 3, em thực hiện xây dựng hệ thống quản lý khách sạn bằng C# WinForms và SQL Server.

Các nội dung đã thực hiện gồm:

* Phân tích các nghiệp vụ của hệ thống quản lý khách sạn.
* Xác định Actor, Use Case, Class, Association và Multiplicity.
* Thiết kế cơ sở dữ liệu SQL Server với các bảng, khóa chính, khóa ngoại và các ràng buộc cần thiết.
* Xây dựng giao diện và các chức năng quản lý bằng WinForms.
* Xử lý các nghiệp vụ liên quan đến phòng, tiện nghi, đặt phòng, dịch vụ, đền bù, hóa đơn, thanh toán và thống kê.
* Kiểm thử một số quy tắc nghiệp vụ như kiểm tra sức chứa phòng, trùng lịch đặt phòng, lắp đặt tiện nghi, cộng dồn dịch vụ, lập hóa đơn và thanh toán.

## 4. Kết quả

Đã hoàn thành các phần chính của bài Lab và chạy thử chương trình trên máy cá nhân.

Các chức năng đã xây dựng và kiểm tra gồm:

* Quản lý danh mục.
* Quản lý phòng và tiện nghi.
* Đặt phòng và nhận phòng.
* Ghi nhận dịch vụ.
* Xử lý đền bù.
* Lập hóa đơn.
* Thanh toán.
* Trả phòng.
* Thống kê.

## 5. Lỗi gặp phải và cách khắc phục

Trong quá trình thực hiện, em gặp một số lỗi liên quan đến kết nối cơ sở dữ liệu, câu lệnh SQL và xử lý dữ liệu giữa Form và Service.

Một số lỗi được khắc phục bằng cách kiểm tra lại chuỗi kết nối SQL Server, câu lệnh truy vấn, tên bảng/tên cột và điều kiện xử lý nghiệp vụ trong các lớp Service.

Ngoài ra, trong quá trình chạy thử các chức năng, em kiểm tra lại dữ liệu đầu vào và điều kiện nghiệp vụ để xử lý các trường hợp không hợp lệ.

## 6. Hướng dẫn kiểm tra và chạy lại

### Bước 1: Cơ sở dữ liệu

Mở SQL Server Management Studio và chạy file SQL được lưu trong thư mục `Database` để tạo cơ sở dữ liệu và các bảng cần thiết.

### Bước 2: Mở chương trình

Mở file `QuanLyKhachSan.sln` bằng Visual Studio 2022.

### Bước 3: Kiểm tra kết nối

Kiểm tra lại thông tin kết nối SQL Server trong file cấu hình của chương trình. Nếu SQL Server trên máy kiểm tra có tên Server/Instance khác thì chỉnh lại cho phù hợp.

### Bước 4: Chạy chương trình

Build Solution và chạy chương trình bằng `F5` hoặc `Ctrl + F5`.

Sau khi chương trình chạy, có thể kiểm tra lần lượt các chức năng quản lý phòng, đặt phòng, dịch vụ, trả phòng, hóa đơn, thanh toán và thống kê.

Các hình ảnh trong `Evidence` là ảnh chụp quá trình thực hiện trên máy cá nhân, dùng làm minh chứng cho bài Lab.

