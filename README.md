## Building Management - Hệ thống quản lý tòa nhà

## Giới thiệu
Hệ thống quản lý tòa nhà được xây dựng trong khuôn khổ đồ án môn Công nghệ phần mềm - Năm 3.  
Dự án tập trung vào việc phân tích yêu cầu, thiết kế hệ thống và xây dựng các chức năng hỗ trợ quản lý tòa nhà, cư dân và các dịch vụ liên quan.

## Công nghệ sử dụng
- C# / ASP.NET (hoặc WinForms - tùy bạn chỉnh lại)
- SQL Server
- Entity Framework (nếu có)
- HTML / CSS / Bootstrap (nếu là web)
- Visual Studio

## Chức năng chính
- Quản lý thông tin tòa nhà, tầng và căn hộ  
- Quản lý cư dân  
- Quản lý hợp đồng thuê / sở hữu  
- Quản lý chi phí (điện, nước, phí dịch vụ)  
- Phân quyền người dùng (quản lý, nhân viên)  
- Thống kê và báo cáo  

## Quy trình phát triển
- Phân tích yêu cầu hệ thống  
- Thiết kế cơ sở dữ liệu  
- Thiết kế chức năng và luồng xử lý  
- Xây dựng và kiểm thử hệ thống  
- Làm việc nhóm và phân chia công việc  

## Cấu trúc project
- `/code` : Chứa source code hệ thống  
- `/database.sql` : File tạo database và dữ liệu mẫu  

## Nhóm thực hiện
- Nhóm: [Số lượng thành viên]  
- Môn: Công nghệ phần mềm  
- Trường: [Tên trường của bạn]  
- Năm học: 2025 - 2026  

## Cài đặt và chạy dự án

**Yêu cầu:** Visual Studio 2019/2022, SQL Server, SQL Server Management Studio (SSMS)

1. Clone repo về máy
   
3. Tạo database
- Mở SSMS, tạo database mới (ví dụ: BuildingManagement)  
- Mở file `database.sql` trong repo  
- Chạy toàn bộ script để tạo bảng và dữ liệu  

3. Cập nhật connection string
- Mở file cấu hình (Web.config / App.config)  
- Tìm phần `<connectionStrings>`  
- Cập nhật Data Source theo SQL Server trên máy  
- Đảm bảo đúng tên database  

4. Mở và chạy project
- Mở file `.sln` bằng Visual Studio  
- Restore NuGet Packages  
- Nhấn Ctrl + F5 để chạy  

## Định hướng phát triển
- Cải thiện giao diện người dùng (UI/UX)  
- Tối ưu hiệu năng hệ thống  
- Mở rộng chức năng quản lý  
- Hoàn thiện phân quyền và bảo mật  
