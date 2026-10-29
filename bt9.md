**Tên:** Đặng Quang Anh 
**Lớp:** CNTT1
**Môn:** NMCNTT
**Session:** 14
# Yêu cầu 
## Phần 1 : Phân tích bài toán (I/O)
1. Xác định đầu vào và đầu ra.
**Đầu vào:** 
- **Vai trò người dùng:** Ban Kỹ thuật (3 người), Ban Thiết kế (2 người), Ban Kinh doanh (2 người), và Nhà đầu tư tiềm năng (1 người ngoài tổ chức).
- **Cấp độ tài liệu & Dữ liệu:** Tài liệu dự án chung, tài liệu riêng, tải liệu chia sẻ chéo.
- **Ràng buộc bảo mật:** Chống rò ri thông tin mật, kiểm soát quyền truy cập và tải xuống.
**Đầu ra:**


- Cấu trúc thư mục Google Drive phân cấp rõ ràng, trực quan.
- Các bước cấu hình hệ thống từ khởi tạo đến vận hành và thu hồi quyền.
2. Đề xuất giải pháp cấu trúc thư mục Google Drive.
- Thư mục gốc: CAMPUSPAY - ROOT
- Thư mục chứ tài liệu chung: 01_General & Public
- Thư mục của ban kĩ thuật: 02_Ban Ky Thuat
- Thư mục của ban thiết kế : 03_Ban Thiet Ke
- Thư mục của ban kinh doanh: 04_Ban Kinh Doanh
- Thư mục chứa các tài liệu chia sẻ chéo: 05_Cross-Functional
3. Các bước thiết kế và cấu hình hệ thống tuần tự.
- **Bước 1: Khởi tạo cấu trúc thư mục**
- **Bước 2: Cài đặt quyền chia sẻ ở cấp thư mục gốc**
- **Bước 4: Kiểm tra và giả lập truy cập**
- **Bước 5: Vận hành, thu hồi và cập nhật**
## Phần 2: **_Triển khai & Chống lỗi_**
4. Bảng:
5. 
| Loại tài liệu | Ban Kỹ thuật | Ban Thiết kế | Ban Kinh doanh | Nhà đầu tư | Ghi chú bảo mật | 
| :---: | :---: | :---: | :---: | :---: | :---: | 
| 1. Mã nguồn & Tài liệu kỹ thuật |Full Access | No Accessn | No Access| No Access | Chứa dữ liệu tối mật, tuyệt đối , bật tính năng chặn tải xuống với người ngoài nếu có.| 
| 2. Tài sản đồ họa & UI/UX | No Access | Full Access | Viewer | No Access | Ban Kinh doanh chỉ xem để lấy hình ảnh đưa vào Pitch Slide, không chỉnh sửa file thiết kế gốc.|
| 3. Business Plan chi tiết & Dữ liệu khách hàng | Viewer | No Access | Full Access | No Access | Giúp Kỹ thuật hiểu context  nhưng không được phép chỉnh sửa nội dung cốt lõi.|
| 4. Pitch Slide gọi vốn | Viewer | Viewer | Editor | Viewer | Tài liệu dùng chung để gọi vốn, cần kiểm soát chặt quyền chỉnh sửa cấu trúc slide.
| 5. Tài liệu chung dự án | Viewer | Viewer | Viewer | No Access | Nội quy, lịch trình chung.

6. Giải pháp xử lý 3 bẫy dữ liệu 
**Xử lý Bẫy1:**
-  Cấp quyền Viewer cho các thành viên ban kỹ thuật.
- Tuyệt đối không cấp quyền Editor.
- Đảm bảo kỹ thuật đọc và nắm bắt được logic nghiệp vụ để viết code đúng.
**Xử lý bẫy2:**
- Cấp quyền **Viewer** cho Nhà đầu tư đối với file Slide Pitch.
- Đáp ứng nhu cầu nghiệp vụ của nhà đầu tư.

**Xử lý bẫy 3:**
7. Truy cập vào Google Workspace.
8. Xóa hoặc vô hiệu hóa tài khoản email công ty của nhân sự đó ngay lập tức.
9. Thay đổi mật khẩu các tài khoản chung.


