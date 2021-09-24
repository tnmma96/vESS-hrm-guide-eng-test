# 1      HƯỚNG DẪN SỬ DỤNG CÁC CHỨC NĂNG - Chấm công và Đăng ký công

## 1.1     Giới thiệu về phân hệ Chấm công và Đăng ký công

Là nơi tập hợp tất cả dữ liệu chấm công của nhân viên trong Công ty. Phân hệ chấm công sẽ xử lý tổng thể việc quản lý việc thời gian làm việc, tăng ca, các loại ngày nghỉ phép. Cung cấp bức tranh toàn cảnh về quản lý công của nhân viên. Hỗ trợ quản lý chấm công hiệu quả.

![image-20210924154220889](images\image-20210924154220889.png)

## 1.2     Thiết lập và khai báo ban đầu

#### 1.2.1 Phân quyên tác động của người dùng

Quy định phạm vi sử dụng các tính năng trên hệ thống của tài khoản người dùng

#### 1.2.2 Ký hiệu công

Là nơi quản lý danh sách ký hiệu trên bảng tổng hợp công. Quy định ký hiệu cho từng loại công, khi đăng ký công được duyệt các thông tin này sẽ được hiển thị trên bảng tổng hợp công dưới dạng ký hiệu công.

#### 1.2.3 Loại đăng kí 

Là nơi thiết lập các loại đăng ký công, mỗi loại yêu cầu được tùy chỉnh theo nhu cầu của người dùng.

#### 1.2.4 Kiểu hoạt động

Là nơi thiết lập các kiểu hoạt động trên hệ thống như cuộc hợp, email, gọi,... được sử dụng để định nghĩa các hoạt động của người dùng 

## 1.3     Các thuật ngữ và từ viết tắt



| **Thuật ngữ** | **Định nghĩa** | **Ghi chú** |
| :-----------: | :------------: | :---------: |
|      DB       |    Database    |             |
|               |                |             |
|               |                |             |
|               |                |             |
|               |                |             |

## 1.4     Hướng dẫn sử dụng chức năng

### *1.4.1    Khai báo danh mục*

#### *1.4.1.1    Chấm công*

##### ***1.4.1.1.1 Khai báo ký hiệu công***

Chức năng này cho phép người dùng khai báo ký hiệu công sử dụng trên hệ thống.

**Các bước thực hiện**

1. Vào phân hệ **Chấm công**, chọn **Cấu hình** , sau đó chọn **Ký hiệu công**, nhấn **Tạo**![image-20210924090553996](images\image-20210924090553996.png)

2. Khai báo các thông tin chi tiết của **Ký hiệu công**![image-20210924090755055](images\image-20210924090755055.png)

   - Tên : Thông tin để quản lý
   - Mã : Không trùng với Mã đã khai báo
   - Loại công : Lấy giữ liệu từ DB
   - Ghi chú : Ghi rõ loại ký hiệu công

   3.Nhấn nút Lưu.



#### *1.4.1.2    Đăng ký công*

##### ***1.4.1.2.1  Khai báo loại nghỉ phép***

1. Vào phân hệ **Đăng ký công**, chọn **Cấu hình** , sau đó chọn **Loại đăng ký**, nhấn **Tạo**![image-20210924091036564](images\image-20210924091036564.png)

2. Khai báo các thông tin chi tiết của **Loại đăng ký**![image-20210924091223193](images\image-20210924091223193.png)

   

   - Tên loại đăng ký : Nhãn cột Tên hiển thị.
   - Loại ngày làm : Nhãn cột Loại ngày làm.
   - Ngày xác nhận : Thời gian xác nhận yêu cầu.
   - Người phụ trách : Người chịu trách nhiệm phê duyệt yêu cầu.
   - Phê duyệt : 
     + Bởi thời gian nghỉ của công ty : Phê duyệt yêu cầu nghỉ phép bởi người phụ trách thời gian nghỉ của công ty.
     + Bởi quản lý của nhân viên : Phê duyệt yêu cầu nghỉ phép bởi quản lý của nhân viên.
     + Bởi người quản lý của nhân viên và thời gian nghỉ của công ty : Phê duyệt yêu cầu nghỉ phép bởi người phụ trách thời gian nghỉ của công ty.
     + Không xác thực : Mặc định là không phê duyệt thời gian nghỉ phép.

   3.Nhấn nút Lưu.

   

##### ***1.4.1.2.2  Khai báo cấp phát ngày nghỉ***

1. Vào phân hệ **Đăng ký công**, chọn **Người quản lý** , sau đó chọn **Đăng ký phân bổ**, nhấn **Tạo**![image-20210924091422407](images\image-20210924091422407.png)

2. Khai báo các thông tin chi tiết của **Phân bổ công**![image-20210924091756740](C:\Users\nguye\Desktop\Attendance\images\image-20210924091756740.png)

   - Tên phân bổ : Nhập tên phân bổ (Hoặc chọn Dữ liệu được lấy từ bảng hr_leave_allocation)
   - Loại đăng ký : lấy từ loại nghỉ phép được cấu hình sẵn
   - Thời lượng : Dữ liệu thuộc kiểu số.
   - Chế độ : 
     - Theo nhân viên : Áp dụng với 1 nhân viên được chọn.
     - Bởi công ty : Áp dụng với cả công ty. Hiển thị thêm trường chọn công ty, ẩn trường nhân viên và phòng/ban đi.
     - Theo phòng/ ban : Áp dụng với phòng/ ban được chọn. Ẩn trường nhân viên đi.
     - Theo tag nhân viên : Áp dụng với từ khóa nhân sự. Hiển thị thêm trường chọn từ khóa nhân sự, ẩn trường nhân viên và phòng/ ban đi.

   3.Nhấn nút Lưu.

### *1.4.2	Khái quát về bảng tổng hợp công*

Dữ liệu của bảng **Tổng hợp công** được lấy từ bên **Đăng ký công** khi thực hiện **Đồng bộ** 

#### 1.4.2.1 Thêm bản ghi tại bảng Tổng hợp công

1. Vào bảng Tổng hợp công, chọn 1 trạng thái chưa được chấm công bất kì, điền Thời gian làm việc, nhấn Lưu![image-20210924092222531](images\image-20210924092222531.png)

#### 1.4.2.2 Sửa bản ghi tại bảng Tổng hợp công

1. Vào bảng Tổng hợp công, chọn 1 trạng thái đươc chấm công bất kì, sửa bản ghi, nhấn Lưu.![image-20210924094539883](images\image-20210924094539883.png)



#### 1.4.2.3 Xóa bản ghi trên bảng Tổng hợp công

1. Vào bảng Tổng hợp công, chọn 1 trạng thái được chấm công bất kì, nhấn X![image-20210924093103040](images\image-20210924093103040.png)

### *1.4.3.  Cách tạo và phê duyệt Đăng ký công*

#### 1.4.3.1 Tạo một bản ghi Đăng ký công

1.4.3.1.1 Đăng ký công không có Cấp phát

1. Thiết lập loại nghỉ phép bởi Chế độ : Không giới hạn![image-20210924100801711](images\image-20210924100801711.png)
2. Vào Quản lý, chọn Đăng ký công, nhấn Tạo![image-20210924104723538](images\image-20210924104723538.png)

1.4.3.1.2 Yêu cầu chấm công có Cấp phát

1. Thiết lập loại nghỉ phép bởi Chế độ : Thiết lập bởi người quản lý nghỉ phép ![image-20210924104833639](images\image-20210924104833639.png)
2. Vào Quản lý, chọn Đăng ký phân bổ, nhấn Tạo![image-20210924105033809](images\image-20210924105033809.png)
3. Vào Quản lý , chọn Đăng ký công, nhấn Tạo ![image-20210924095718579](images\image-20210924095718579.png)

#### 1.4.3.2 Cán bộ vào phê duyệt/hủy Đăng ký công

1.4.3.2.1 Cán bộ phê duyệt Đăng ký công

1. Vào Quản lý, chọn Đăng ký công, thực hiện Duyệt một bản ghi bất kì ở trạng thái Chờ duyệt, khi đó trạng thái của bản ghi là Đã phê duyệt![image-20210924105853015](images\image-20210924105853015.png)

1.4.3.2.2 Cán bộ hủy Đăng ký công

1. Vào Quản lý, chọn Đăng ký công, thực hiện Từ chối một bản ghi bất kì ở trạng thái Chờ duyệt, thực hiện Từ chối.![image-20210924105954820](images\image-20210924105954820.png)

