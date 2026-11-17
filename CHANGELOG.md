# 1.0.2 — 17/11/2026

- Proxy xoay và proxy tĩnh có giao diện cấu hình thống nhất; ưu tiên proxy xoay khi bật Sử dụng Proxy.
- Tách luồng gửi và luồng theo dõi; ưu tiên API đọc tiến độ, chỉ mở trình duyệt dự phòng khi cần.
- Giảm tải bằng cache tài nguyên công khai, upload/download dạng luồng; tải video kết quả trực tiếp, giữ nguyên chất lượng.
- Logs bắt đầu phiên mới mỗi lần mở ứng dụng, vẫn xuất được mã chẩn đoán để hỗ trợ.
- Lưu video theo thư mục YYYY-MM-DD/motion tính theo ngày tải kết quả.

Kiểm tra: 212 kiểm thử đạt; bản đóng gói khởi động với hồ sơ trống, preload/IPC và chặn license chưa kích hoạt đều đạt. Batch thực tế 6/6 video hoàn tất qua proxy, kiểm tra giải mã toàn bộ file không lỗi.

Bản Windows x64 chưa ký số. Chưa xác minh nâng cấp installer trên máy Windows sạch. Cài lần đầu cần Python 3.12 và gói Runtime Setup; máy đã đủ môi trường chạy không cần thiết lập lại.

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
