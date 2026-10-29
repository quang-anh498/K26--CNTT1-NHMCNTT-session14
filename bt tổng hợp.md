**Tên:** Đặng Quang Anh 
**Lớp:** CNTT1
**Môn:** NMCNTT
**Session:** 14
# Yêu cầu 
##  PHẦN 1 – THIẾT LẬP HYBRID WORKFLOW.
1. Sự cố mất file do hỏng ổ cứng:
- Sự cố mất file **sẽ không xảy ra** nếu nhóm đã áp dụng đúng Hybrid Workflow từ đầu.
- **Vì:** Hybrid Workflow kết hợp giữa làm việc trực tiếp trên thư mục đồng bộ tự động hoặc lưu trên Cloud.

2. 3 bước thiết lập Auto Sync hướng dẫn nhóm:

- **Bước 1:** Cài đặt và đăng nhập ứng dụng Cloud quản lý.
- **Bước 2:** Tạo thư mục chung của dự án SmartCampus nằm trực tiếp trong ổ đĩa ảo của Cloud.
- **Bước 3:** Kéo thả hoặc lưu toàn bộ file làm việc vào thư mục này và kiểm tra biểu tượng.

3. Thao tác khôi phục file:

-->    **Thao tác:** Mở file trên Google Drive trên nền web 
--> Nhấp vào mục **File** 
-->  Chọn **Version history** 
--> Chọn **See version history**  
--> Tìm mốc thời gian 10 phút trước khi xảy ra sự cố 
--> Nhấn **Restore this version** 


4. Xử lý sai lầm khi đồng bộ thư mục dự án:

- 2 sai lầm đã mắc phải: 
Đồng bộ thư mục chứa `node_modules`
Đồng bộ các file giải trí nặng như phim 4K

## PHẦN 2 – PHÂN QUYỀN CHIA SẺ AN TOÀN.
1. Bảng phân quyền chi tiết cho 4 file:

| File | Mức quyền | Phạm vi chia sẻ | Giải thích |
| :---: | :---: | :---: | :---|
| `BaoCao_CuoiKy_SmartCampus.docx`|Viewer | Restricted | Cho phép giảng viên đọc và chấm điểm dễ dàng nhưng  không có quyền chỉnh sửa, tránh rủi ro thao tác.|
| `Slide_BaoCao.pptx`|Editor| Restricted | Cả nhóm cần cùng nhau chỉnh sửa, bổ sung nội dung slide|
| `GopY_BanNhap.docx`|Commenter| Restricted | Cho phép anh khóa trên để lại các lời nhận xét, góp ý trực tiếp vào văn bản
|`ThongTin_CaNhan_NhomVien.xlsx`|Viewer| Restricted | Bảo vệ tuyệt đối thông tin nhạy cảm cá nhân.|


2. Quy tắc Cờ Đỏ Bảo mật với file chứa thông tin cá nhân:

- **Quy tắc Cờ Đỏ Bảo mật:** Là quy tắc cảnh báo nghiêm ngặt tuyệt đối không bao giờ kết hợp phạm vi.
- **Giải thích:** Nếu bật  Anyone với kết hợp "Editor", bất kỳ ai có đường link đều có thể truy cập.

## PHẦN 3 – TỔ CHỨC GIAO TIẾP NHÓM CHUẨN DOANH NGHIỆP.
1. Chỉ ra 3 vấn đề trong đoạn hội thoại Zalo:
- **No-Hello:** Nhắn câu chào cụ thể mà không đi thẳng vào vấn đề  công việc ngay từ đầu.
- Spam giờ khuya & Lạm dụng @all.
- **Tin nhắn không phân luồng :** Trộn lẫn thông báo tiến độ đồ án quan trọng với việc.
2. Đề xuất tối thiểu 2 Channel/Topic trên Lark/Slack:
- `01_thong-bao-chung`: Kênh độc quyền của trưởng nhóm để đăng thông báo  lịch họp và quyết định quan trọng.
- `02_tien-do-do-an`: Kênh chuyên thảo luận công việc, báo cáo tiến độ.
3. Viết lại tin nhắn của Lan theo tư duy Asynchronous.
-   "Chào mọi người, phần viết nội dung phần 'Kiến trúc hệ thống' trong báo cáo cuối kỳ mình đang gặp khó ở đoạn sơ đồ luồng dữ liệu. Bạn nào rảnh có thể nghía qua giúp mình đoạn này với nhé, mình cảm ơn mọi người trước."
## PHẦN 4 – THÔNG BÁO TỔNG HỢP.
**01_thong-bao-chung**

Chào cả nhóm, mình đã hoàn tất các việc chuẩn bị không gian làm việc theo chuẩn Workspace để nước rút về đích. Chúng ta sắp hết thời gian chuẩn bị rồi mong mọi người hoàn thành tất những gì mình còn thiếu trước ngày hạn.
Nếu có ai đang còn vấn đề khó khăn thì có thể nhờ mọi người giúp đỡ.
Vậy mong mọi người sớm hoàn thành để chúng ta có nhiều thời gian xem lại dự án, để đạt được kết quả cao nhất trong công việc.







