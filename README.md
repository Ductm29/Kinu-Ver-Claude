# Kinu Fabric Studio — mã nguồn phiên bản 14

Đây là mã nguồn của phiên bản đang chạy trên Sites tại thời điểm xuất (28/10/2026).

## Cấu trúc
- `dist/index.html`: toàn bộ giao diện, CSS, JavaScript và tài nguyên nhúng của ứng dụng. Đây là mã nguồn triển khai hiện tại, không phải dự án React/Vite tách thành nhiều tệp.

## Chạy và sửa
1. Giải nén ZIP.
2. Trong thư mục đã giải nén, chạy `python3 -m http.server 8000 --directory dist`.
3. Mở `http://localhost:8000` trên trình duyệt.
4. Sửa `dist/index.html`; tải lại trang để xem thay đổi.

Có thể gửi ZIP này cho Claude và yêu cầu tiếp tục chỉnh `dist/index.html`, hoặc tách thành các tệp HTML/CSS/JS nếu muốn bảo trì dễ hơn. Trước khi triển khai lại, kiểm tra các chức năng chụp vải, chọn ảnh và lưu/xuất trên thiết bị thật.

Phiên bản: 14. Git commit nguồn: 0101c01ebdaa065e31ec94e28c6efd28dbf34bbe.
