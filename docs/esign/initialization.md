## Thiết lập và khai báo dữ liệu ban đầu

Việc thiết lập và khai báo ban đầu được thực hiện khi lần đầu cài đặt ứng dụng, giúp khởi tạo dữ liệu và bắt đầu cho việc thực hiện các nghiệp vụ ký số. 

### Loại văn bản trình ký

Cho phép khai báo và quản lý thông tin về các loại văn bản  trên hệ thống, các quy tắc tự sinh số văn bản khi được ban hành. 

**Đối tượng thực hiện: Quản trị hệ thống (Admin)**

**Các bước thực hiện:** 

1. Vào **Cấu hình** > chọn **Loại tài liệu trình ký**

​	![img](images/clip_image050.jpg)

- Hiển thị danh sách các loại văn bản trình ký được khai báo trên hệ thống.
- Thông tin hiển thị: Tên, Mã văn bản

2.  Để khai báo loại văn bản mới, người dùng kích nút **Tạo**. Trên màn hình tạo mới, khai báo các thông tin chi tiết của **Loại văn bản trình ký**

![](images/clip_image052.jpg)

- Nhập Tên loại văn bản trình ký
- Nhập Quy tắc đánh mã: Nhập quy tắc sẽ đánh số văn bản khi được ban hành. Quy tắc sinh mã có sử dụng các tham số được định nghĩa ở danh sách tham số cấu hình ở bên dưới theo cấu trúc khai báo {tên tham số}. 
- Danh sách tham số cấu hình: Định nghĩa các tham số sẽ được sử dụng để sinh mã. 
  - Tên tham số phải duy nhất trong danh sách tham số
  - Kiểu: hỗ trợ một số kiểu như số, ngày, tháng, năm, văn bản.  Tương ứng với mỗi kiểu dữ liệu có cho phép định nghĩa giá trị khởi tạo hoặc định dạng hiển thị. 
  - Cho phép cập nhật hoặc không giá trị tham số khi thực hiện ban hành văn bản. 

### Vai trò ký

Cho phép khai báo và quản lý thông tin về các vai trò khi ký của người dùng  trên ứng dụng. 

**Đối tượng thực hiện: Quản trị hệ thống (Admin)**

**Các bước thực hiện:** 

1.  Người dùng chọn **Cấu hình** >Kích chọn **Vai trò kí**

![img](images/clip_image062.jpg)

- Hiển thị danh sách các vai trò ký được khai báo trên hệ thống.
- Thông tin hiển thị: Tên vai trò và lựa chọn Có người xem xét 

2. Click **Tạo** để khai báo các thông tin vai trò ngay trên danh sách: 

![img](images/clip_image064.jpg)

- Tích chọn Có người xem xét với những vai trò cần có người xét duyệt văn bản trước khi trình tới người ký. 


3. Kích**Lưu**


### Tài khoản ký

Cho phép khai báo và quản lý thông tin về các tài khoản được thực hiện ký  trên hệ thống.

**Đối tượng thực hiện: **

·     **Người quản trị hệ thống:** khai báo các tài khoản ký cho người dùng

·     **Người dùng: ** Chỉ xem thông tin tài khoản của mình và có quyền chỉnh sửa ảnh chân ký và thông tin ký CA 

**Các bước thực hiện:** 

1. Chọn **Cấu hình** > Kích**Tài khoản kí**

![img](images/clip_image056.jpg)

- Hiển thị danh sách các tài khoản ký đã khai báo trên hệ thống.
- Các thông tin hiển thị: Tên tài khoản, email, số điện thoại, có ký số, vai trò...

2. Để khai báo tài khoản ký mới, kích nút **Tạo**:

   ​	![image-20211013122404429](images/image-20211013122404429.png)



- Nhập **Tài khoản kí**: Nhập @ tìm kiếm và chọn người dùng để tạo tài khoản kí. Mỗi người dùng tồn tại duy nhất trong danh sách tài khoản kí. 

- Chọn **vai trò**: Mỗi người dùng có thể có một hoặc kiêm nhiệm nhiều vai trò. 

- Chọn **Người xem xét**: với vai trò có người xem xét thì bắt buộc phải cấu hình người xem xét từ danh sách người dùng. 

- Có ký điện tử: Nếu tích chọn thì người dùng có thể sử dụng chữ ký số, ngược lại thì chỉ ký duyệt thông thường. 

- Tab Ảnh chân ký: Người dùng tải lên hệ thống ảnh chữ ký mộc dùng cho cá nhân để thêm vào văn bản sau khi ký duyệt (nếu yêu cầu). Mỗi tài khoản ký có thể cấu hình tối đa 3 loại chữ ký.  Kích thước ảnh chân ký phải thỏa mãn tỷ lệ 3:2 . Ngày hiệu lực mặc định là ngày tải ảnh chân ký tương ứng lên hệ thống. 

- Tab Chứng thư số: Cấu hình chứng thư số để xác thực khi người dùng ký duyệt các văn bản. 	

  ![image-20211013123042271](images/image-20211013123042271.png)

  Để lấy serial chứng thư số khi người dùng sử dụng USB token thì có thể cắm usb token rồi kích nút **Tải chứng thư số**. Hệ thống sẽ tự động điền serial lấy được. 

3. Click **Lưu**


### Lưu mẫu trình ký văn bản

Chức năng cho phép mỗi người dùng tạo và quản lý những mẫu trình ký thường xuyên sử dụng. 

**Các bước để tạo mẫu trình ký**

Có 2 cách để tạo mẫu trình ký

**<u>Cách 1</u>:** 

1. Vào **Cấu hình** > chọn **Mẫu tài khoản kí**

![img](images/clip_image066.jpg)

- Hiển thị danh sách tất cả mẫu tài khoản kí đã tạo trong hệ thống
- Các chức năng có trong màn hình danh sách bao gồm: Tạo mới, chỉnh sửa, xóa, xuất danh sách mẫu tài khoản kí
- Nhập thông tin muốn tìm kiếm vào thanh tìm kiếm

2. Click **Tạo** > Khai báo thông tin tạo mới mẫu tài khoản kí

![img](images/clip_image068.jpg)

- Nhập tên mẫu danh sách ký

- Chọn phạm vi 

- Nhập tên và chọn Tài khoản kí

3. Click **Lưu**

4. Thực hiện yêu cầu tạo mới Mẫu kí: Kiểm tra thông tin dữ liệu trên màn hình và tùy chính thông tin Tạo mới

**<u>Cách 2</u>:**  Tạo mẫu trình ký nhanh trong khi tạo văn bản trình ký 



