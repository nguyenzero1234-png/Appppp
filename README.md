# Tu Tiên Học Đạo – đóng gói APK

1. Tạo repo mới trên GitHub (để Private cũng được).
2. Giải nén zip này, đẩy TOÀN BỘ nội dung (kể cả thư mục .github) lên nhánh main.
3. Vào tab **Actions** → workflow **Build APK** (tự chạy sau khi push, hoặc bấm *Run workflow*).
4. Đợi ~5–8 phút → mở lần chạy xong → mục **Artifacts** → tải `tu-tien-hoc-dao-apk` (zip chứa app-debug.apk).
5. Chép APK vào điện thoại, cho phép "cài từ nguồn không xác định" rồi cài.

Đổi tên app / package id: sửa `capacitor.config.json` (appName, appId).
Cập nhật nội dung game: thay `www/index.html` rồi push lại.
Dữ liệu chơi nằm trong app, hãy dùng Cài đặt → Xuất để sao lưu trước khi gỡ app.
