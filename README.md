# VideoHiggsfield — bản cài Windows

Tải bản mới tại [Releases](https://github.com/phuc-dep-trai/VideoHigg_release/releases/latest).

## Cài lần đầu

1. Tải `VideoHiggsfield-setup-1.0.11.exe` từ Releases.
2. Chạy bộ cài, mở ứng dụng và nhập license.

Bộ cài đã kèm Python, thư viện và Chromium riêng. Không cần cài Python, pip hay chạy Runtime Setup. Công cụ xử lý video còn thiếu sẽ được ứng dụng tự tải trực tiếp từ nhà phát hành và xác minh checksum khi cần. Cần kết nối Internet để sử dụng dịch vụ.

Dữ liệu tài khoản và tác vụ được giữ khi cập nhật. Sao lưu dữ liệu trước khi nâng cấp.

## Lưu ý

- Windows x64. Bản 1.0.11 chưa ký số; Windows có thể hiển thị cảnh báo nhà phát hành chưa xác định.
- License VideoHiggsfield độc lập hệ thống cũ; key cũ không dùng lẫn.
- Khi cần hỗ trợ, vào Logs → Export rồi gửi file Logs. Không gửi cookie/token hoặc toàn bộ database.
- `SHA256SUMS.txt` dùng để đối chiếu file tải về. `.blockmap` là dữ liệu hỗ trợ cập nhật; người dùng không cần mở file này.
- Repo công khai này chỉ chứa tài liệu và bản cài, không chứa source server, khóa bí mật hay dữ liệu tài khoản.

Thành phần media được tải trực tiếp từ [Gyan FFmpeg](https://www.gyan.dev/ffmpeg/builds/) bởi bộ thiết lập; các file giấy phép của nhà phát hành được giữ nguyên.
