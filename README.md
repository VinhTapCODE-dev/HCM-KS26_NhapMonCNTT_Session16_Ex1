# HCM-KS26_NhapMonCNTT_Session16_Ex1
# Sơ đồ luồng dữ liệu từ Local SSD
Ấn tổ hợp ctrl + S -> file system watcher phát hiện thay đổi -> hàng đợi đồng bộ -> cloud storage
> khi designer bấm ctrl + S , file sẽ đi cực tiếp vào ổ SSD
# cách hệ thống xử lý khi có xung đột phiên bản (File Version Conflict)
- phát hiện xung đột : hệ thống nhận diện sự trùng lặp thời gian khi ghi đè lên một đường dẫn
- tạo bản sao độc lập : tránh làm mất dữ liệu
- giải quyết : 2 người mở cả hai file để kiểm tra , tổng hợp các ý tốt nhất vào file chính và xóa file coflict
# Danh sách 3 bước thiết lập phần mềm đồng bộ chuẩn cho một Designer.
- Bước 1 : tạo thư mục đồng bộ và cố định local 
- Bước 2 : bật auto-save và backup phòng sập nguồn
- Bước 3 : + kiểm tra cloud ở thanh taskbar đã hiện `up to date` để xác nhận rằng đã nhận bản mới nhất từ nhóm
           + Khôi phục version history : truy cập vào onrdrive -> click chuột phải vào file 3D bị lỗi -> chọn version history -> sau đó chọn mốc thời gian xảy ra lỗi -> nhấn restore để khôi phục lại
