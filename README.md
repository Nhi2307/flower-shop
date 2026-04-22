## Flower Shop - Website Quản Lý Bán Hoa  

## Giới thiệu
Website quản lý bán hoa được xây dựng trong khuôn khổ đồ án môn Công nghệ phần mềm - Năm 3.  
Dự án tập trung vào việc phân tích yêu cầu, thiết kế hệ thống và xây dựng các chức năng quản lý bán hàng và khách hàng trong cửa hàng hoa.

## Công nghệ sử dụng
- ASP.NET MVC  
- SQL Server  
- Entity Framework  
- HTML / CSS / Bootstrap  

## Chức năng chính
- Quản lý sản phẩm (thêm, sửa, xóa hoa)  
- Quản lý đơn hàng  
- Quản lý khách hàng  
- Phân quyền người dùng (nhân viên, quản lý)  
- Thống kê doanh thu  

## Quy trình phát triển
- Phân tích yêu cầu hệ thống  
- Thiết kế cơ sở dữ liệu  
- Thiết kế chức năng và luồng xử lý  
- Xây dựng và kiểm thử hệ thống  
- Làm việc nhóm và phân chia công việc  

## Cấu trúc project
- `/code` : Chứa source code website  
- `/database.sql` : File script tạo database và dữ liệu mẫu  

## Nhóm thực hiện
- Nhóm 3 người  
- Môn: Công nghệ phần mềm - Đại học Công Thương TP.HCM  
- Năm học: 2025 - 2026  

## Cài đặt và chạy dự án

**Yêu cầu:** Visual Studio 2019/2022, SQL Server, SQL Server Management Studio (SSMS)

1. Clone repo về máy

2. Tạo database
- Mở SSMS, tạo database mới tên `FlowerShop`  
- Mở file `database.sql` trong repo  
- Chạy toàn bộ script để tạo bảng và dữ liệu  

3. Cập nhật connection string
- Mở file `Web.config` trong project  
- Tìm phần `<connectionStrings>`  
- Cập nhật `Data Source` theo SQL Server trên máy  
- Đảm bảo `Initial Catalog = FlowerShop`  

4. Mở và chạy project
- Mở file `.sln` bằng Visual Studio  
- Chuột phải vào Solution → Restore NuGet Packages  
- Nhấn `Ctrl + F5` để chạy  

## Định hướng phát triển
- Cải thiện giao diện người dùng (UI/UX)  
- Bổ sung chức năng giỏ hàng và thanh toán  
- Tối ưu hiệu năng hệ thống  
- Hoàn thiện phân quyền và bảo mật  

## Vai trò cá nhân
- Tham gia thiết kế giao diện website  
- Xây dựng một số chức năng cơ bản  
- Hỗ trợ thiết kế cơ sở dữ liệu  
