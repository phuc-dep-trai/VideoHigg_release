# 1.0.1 — 16/11/2026

- Genjutsu 720p và Genjutsu Lite 1080p.
- Prompt riêng từng job, tham chiếu nhiều ảnh/video bằng @, kéo thả vào từng job.
- Proxy HTTP có xác thực, chọn/xoay proxy và giữ proxy khi tiếp tục job.
- Tự lấy 30 giây đầu nếu video tham chiếu dài hơn 30 giây, giữ nguyên file gốc.
- Luồng gửi nhường ngay khi lưu được mã job; theo dõi và tải kết quả chạy riêng.
- Giới hạn trình duyệt đọc trạng thái dự phòng để tránh mở dồn.
- License mới và Logs hỗ trợ có mã lỗi/Ref.
- Icon mới theo VideoHiggsfield.

Đã kiểm tra: 167 kiểm thử ứng dụng; bản đóng gói khởi động với profile trống, kiểm tra preload/IPC và chặn khi chưa kích hoạt license.

Giới hạn: chưa ký số; chưa kiểm thử nâng cấp từ installer cũ hoặc toàn bộ thiết lập runtime trên máy Windows sạch; không tạo video trả phí trong kiểm thử phát hành này. Máy cài lần đầu cần Python 3.12 và bộ Runtime Setup.
