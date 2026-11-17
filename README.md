# VideoHiggsfield — bản cài Windows

Tải bản mới tại [Releases](https://github.com/phuc-dep-trai/VideoHigg_release/releases/latest).

## Cài lần đầu

1. Tải `VideoHiggsfield-setup-1.0.4.exe` và `VideoHiggsfield-Runtime-Setup-1.0.4.zip` từ cùng release.
2. Cài **Python 3.12 x64** từ [Python.org](https://www.python.org/downloads/windows/), bật Python Launcher và thêm Python vào PATH.
3. Giải nén gói Runtime Setup, chạy `Setup-Runtime.cmd` một lần. Cần Internet để tải thư viện, Chromium và công cụ xử lý video.
4. Chạy bộ cài VideoHiggsfield rồi nhập license mới nhận từ nhà cung cấp.

Nếu máy đã có đủ môi trường chạy thì không cần thiết lập lại mỗi lần cập nhật. Bộ cài không xóa dữ liệu app khi gỡ/cài lại theo thiết lập mặc định. Sao lưu dữ liệu trước khi nâng cấp.

## Lưu ý

- Windows x64. Bản 1.0.4 chưa ký số; Windows có thể hiển thị cảnh báo nhà phát hành chưa xác định.
- License VideoHiggsfield độc lập hệ thống cũ; key cũ không dùng lẫn.
- Khi cần hỗ trợ, vào Logs → Export rồi gửi file Logs. Không gửi cookie/token hoặc toàn bộ database.
- `SHA256SUMS.txt` dùng để đối chiếu file tải về. `.blockmap` là dữ liệu hỗ trợ cập nhật; người dùng không cần mở file này.
- Repo công khai này chỉ chứa tài liệu và bản cài, không chứa source server, khóa bí mật hay dữ liệu tài khoản.

Thành phần media được tải trực tiếp từ [Gyan FFmpeg](https://www.gyan.dev/ffmpeg/builds/) bởi bộ thiết lập; các file giấy phép của nhà phát hành được giữ nguyên.
