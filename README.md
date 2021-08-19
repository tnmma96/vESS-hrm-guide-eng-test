# Hướng dẫn cập nhật tài liệu sử dụng phần mềm quản trị - Ban CNTT

Repository này được tạo ra với mục đích xây dựng tài liệu hướng dẫn sử dụng phần mềm. Giúp người dùng dễ dàng tiếp cận các sản phẩm của Ban CNTT. Dưới đây là các lưu ý khi cập nhật hướng dẫn sử dụng phần mềm.

## 1. MkDocs
MkDocs là một phần mềm cực nhanh, dễ sử dụng hỗ trợ bạn generate ra site document theo ý của bạn.

Các dạng files document MkDocs hỗ trợ:

- Markdown (phổ biến nhất)
- Text (txt)
- Html
MkDocs sẽ dựng ra các trang html và bạn có thể host site document mọi nơi (Apache, Nginx, IIS,…) và ngay cả GitHub pages.

Trang chủ: https://www.mkdocs.org/

Hướng dẫn cài đặt MkDocs: https://www.mkdocs.org/#installation

## 2. Hướng dẫn cập nhật tài liệu hướng dẫn sử dụng

Sau đây là một số quy tắc cập nhật tài liệu hướng dẫn sử dụng lên thư mục chung:

## Lệnh cơ bản

* `mkdocs new [dir-name]` - Tạo project mới.
* `mkdocs serve` - Chạy thử trên máy cá nhân.
* `mkdocs build` - Build phục vụ deploy.
* `mkdocs -h` - Print help message and exit.

## Cấu trúc project

    mkdocs.yml    # File cấu hình.
    docs/
        index.md  # Trang chủ giới thiệu.
        viettelfamily-app         # Thư mục theo từng hệ thống phần mềm
            index.md              # Trang chủ giới thiệu chung về hệ thống
            huong-dan-dat-com.md  # Hướng dẫn sử dụng theo từng module chức năng
