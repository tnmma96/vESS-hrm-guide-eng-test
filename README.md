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
        hrm       # Thư mục theo từng phân hệ (Nhân sự, Kế toán, SaaS Portal, Digital Workplace, Văn phòng...)
            introduction.md             # Giới thiệu chung về phân hệ
            initialization.md           # Thiết lập và khai báo ban đầu
            abbreviations.md            # Thuật ngữ và từ viết tắt
            master-datas.md             # Khai báo danh mục 
            log-histories.md            # Lịch sử phát triển phân hệ
            employee.md,recruitment.md  # Mô tả các module trong phân hệ
            images/                     # Lưu trữ hình ảnh đính kèm

## Cấu trúc Menu một phân hệ

File cấu hình: mkdocs.yml

    - 'Nhân sự': 
            - 'Giới thiệu về phân hệ Quản lý nhân sự': 'hrm/introduction.md'
            - 'Thiết lập và khai báo ban đầu': 'hrm/initialization.md'
            - 'Các thuật ngữ và từ viết tắt': 'hrm/abbreviations.md'
            - 'Hướng dẫn sử dụng chức năng':
                - 'Khai báo danh mục': 'hrm/master-datas.md'
                - 'Tuyển dụng': 'hrm/recruitment.md'
                - 'Nhân viên': 'hrm/employee.md'
           	- 'Lịch sử phát triển sản phẩm': 'hrm/log-histories.md'
## 3. Sử dụng công cụ Typora 

Trang chủ: [https://typora.io/](https://typora.io/)

Hướng dẫn sử dụng Markdown cơ bản: [https://support.typora.io/Markdown-Reference/](https://support.typora.io/Markdown-Reference/)

Một số thao tác với hình ảnh với Typora: [https://support.typora.io/Images/](https://support.typora.io/Images/)

### Cấu hình phân vùng lưu trữ hình ảnh  đính kèm

> **Cấu hình cho phép end user chỉ cần paste hoặc Drag & Drop 1 ảnh bất kỳ, Typora sẽ tự copy ảnh vào phân vùng lưu trữ & gắn path đến phân vùng đó.**
>
> **Với mỗi file .md, bắt buộc cấu hình phân vùng lưu trữ hình ảnh đính kèm tại folder trong phân hệ đó. **

Chọn: Format → Image → When Insert Local Images → Copy Image File to Folder, chọn folder **images** của phân hệ đang thao tác (VD: \ESS-System-Guide\docs\hrm\images).

Sau khi chọn xong, trên đầu file .md có xuất hiện cấu hình sau là thành công. 

```
typora-copy-images-to: images
```

### Cấu hình  đường dẫn tương đối hình ảnh đính kèm 

> **Tất cả các đường dẫn hình ảnh đính kèm bắt buộc cấu hình ở dạng tương đối.**

Chọn: Format` → `Image` → `Use Image Root Path, chọn folder của phân hệ thao tác (VD: \ESS-System-Guide\docs\)

Sau khi chọn xong, trên đầu file .md có xuất hiện cấu hình sau là thành công

```
typora-root-url: ..
```

### 

