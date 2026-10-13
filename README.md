# Lịch VN 4G – bản phát hành

Kho này do máy build tự cập nhật từ kho riêng `lichvannien-abin`. Đừng sửa tay.

- **Tải app**: vào mục [Releases](../../releases/latest), tải `LichVN-4G.apk` rồi cài đè lên bản cũ. Sự kiện, ngày giỗ và cài đặt vẫn giữ nguyên.
- `manifest.json`: app đọc file này để biết có bản app mới, bộ công thức mới hay bảng quy tắc mới không.
- `engine/engine-<số bản>.js`: bộ công thức (âm lịch, tiết khí, can chi, thần sao, chấm điểm ngày). Có chữ ký số.
- `rules/rules-<số bản>.json`: bảng quy tắc, trọng số chấm điểm, ngày lễ. Có chữ ký số.

App chỉ dùng file tải về khi chữ ký đúng. Nếu bản mới chạy lỗi, app tự quay về bản có sẵn.
Dữ liệu cá nhân (sự kiện, ngày giỗ, sinh nhật) chỉ lưu trong máy và không bao giờ được gửi lên mạng.
