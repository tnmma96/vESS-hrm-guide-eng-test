# Quản lý hồ sơ nhân viên

## Mô tả nghiệp vụ

##### Quy trình nghiệp vụ

- Công ty có nhân sự mới, đã được Trưởng bộ phận quản lý nhân sự cùng Ban Giám đốc phê duyệt đồng ý tuyển dụng.
- Nhân viên nhân sự thực hiện việc chuyển trạng thái từ Ứng viên sang Nhân viên công ty.
- Nhân viên nhân sự thực hiện tạo tài khoản đăng nhập cho nhân viên mới, tạo hợp đồng, nhập các thông tin liên quan đến nhân sự mới.
- Nhân viên mới thực hiện quy trình Onboarding, cập nhật thông tin cá nhân vào ngày đầu làm việc.
- Nhân viên nhân sự kiểm tra và hoàn thiện hồ sơ nhân viên mới, thực hiện cập nhật thông tin trong quá trình làm việc của nhân viên.

##### Luồng chức năng chính

- Tuyển dụng nhân viên mới. Chi tiết [tại đây](#)
- Tạo tài khoản đăng nhập. Chi tiết [tại đây](#Tạo tài khoản)
- Thêm mới hồ sơ nhân viên. Chi tiết [tại đây](#Thêm mới hồ sơ nhân viên).
- Cập nhật thông tin trong quá trình làm việc của nhân viên. Chi tiết [tại đây](#Cập nhật hồ sơ nhân viên).

## Tạo tài khoản

**Các bước thực hiện**

**Bước 1:** Vào phân hệ **Thiết lập**>**Người dùng & công ty**>**Người dùng**.

![image-20211004094007844](images/image-20211004094007844.png)

**Bước 2:** Khai báo thông tin tài khoản đăng nhập

- Tại mục **Loại người dùng** chọn **Người sử dụng nội bộ**

- Tại **Nguồn lực nhân sự>Nhân viên** chọn:
  - **Cán bộ:** Nếu tài khoản là của nhân viên quản lý nhân sự
  - **Người quản trị:** Nếu tài khoản là của trưởng phòng quản lý nhân sự hoặc Ban Giám đốc
  - **Bỏ trống:** Nếu tài khoản của nhân viên không có phận sự liên quan đến phân hệ Nhân viên.

**Lưu ý:** Để sử dụng được phân hệ Nhân viên, tài khoản đăng nhập vào hệ thống phải được cấp quyền truy cập, tùy thuộc vào vị trí công việc của nhân viên mà tài khoản đăng nhập của họ được gán quyền tương ứng.

**Bước 3**: Sau khi “Đăng ký sử dụng thành công”, khách hàng mở hòm thư được khai báo khi đăng ký để lấy thông tin tài khoản truy cập. Khách hàng sử dụng thông tin này để đăng nhập vào chương trình (hướng dẫn đăng ký tại đây)

![image-20211004094034200](images/image-20211004094034200.png)

**Bước 4**: Chọn ứng dụng **Nhân viên**.

![image-20211004094207988](images/image-20211004094207988.png)

## Thêm mới hồ sơ nhân viên

**Đối tượng thực hiện:** Nhân viên nhân sự.

**Bước 1:** Nhân viên quản trị nhân lực vào phân hệ **Nhân viên>Tạo**

![image-20211004104809471](images/image-20211004104809471.png)

Sau đó thực hiện khai báo thông tin của nhân viên:

- Khai báo thông tin cá nhân cơ bản về nhân viên (căn cứ vào Sơ yếu lý lịch) như: họ tên, giới tính, ngày sinh, nơi sinh, nguyên quán, hộ khẩu thường trú, số CMND, ngày cấp, nơi cấp, trình trạng hôn nhân, dân tộc, tôn giáo, trình độ văn hóa, trình độ đào tạo, trường đào tạo…
- Khai báo thông tin công việc của nhân viên: chức danh, phòng ban, người quản lý, tài khoản đăng nhập của nhân viên.  

![image-20211004110010849](images/image-20211004110010849.png)

**Lưu ý:** Mã nhân viên sẽ được hệ thống tự sinh sau khi người dùng hoàn thành thao tác thêm mới hồ sơ nhân viên.

**Bước 2:** Tại tab **Hợp đồng**, người dùng chọn **Tạo** để thêm mới hợp đồng cho nhân viên. Hợp đồng sau khi tạo và duyệt tại đây sẽ được tự động sinh dữ liệu ở tab **Quá trình làm việc**

![image-20210930171146814](images/image-20210930171146814.png)



Nhân viên mới sau khi được thêm sẽ được sinh dữ liệu tại màn hình Hợp đồng, trạng thái là **Chưa có**, nhân viên nhân sự chọn **Đề xuất**, hệ thống chuyển đến màn hình tạo hợp đồng mới.

![image-20210930171009027](images/image-20210930171009027.png)

- Tại mục **Nhân viên** chọn nhân viên cần tạo hợp đồng, sau khi chọn nhân viên, hệ thống sẽ tự động lấy các thông tin đi kèm của nhân viên như **Chức vụ, Phòng ban**

- Tại phần **Thông tin hợp đồng**, nhập các thông tin về hợp đồng với nhân viên đó, các thông tin về lương và bảo hiểm nhập tại phần **Thông tin hợp đồng**

- Hợp đồng sau khi tạo và duyệt tại đây sẽ được tự động sinh dữ liệu ở tab **Quá trình làm việc**

**Bước 3:** Khai báo thông tin về gia đình tại tab **Quan hệ gia đình** và **Giảm trừ gia cảnh**

- Tại tab **Quan hệ gia đình** , cho phép khai báo thông tin những người thân của nhân viên. Đồng thời theo dõi được những đối tượng thuộc diện giảm trừ gia cảnh của nhân viên để phục vụ cho công tác tạm tính thuế TNCN hàng tháng của nhân viên.

  Người dùng chọn **Thêm một dòng**, và thực hiện khai báo thông tin

![image-20210930141358725](images/image-20210930141358725.png)

​		Sau khi người dùng chọn **Lưu**, các thông tin này được lưu và sẽ được sử dụng tiếp tại tab **Giảm trừ gia cảnh**

- Tại tab **Giảm trừ gia cảnh**, người dùng bấm **Sửa>Thêm một dòng**, để thêm người phụ thuộc, người sử dụng chọn dữ liệu có sẵn đã được khai báo trước đó trong thanh dữ liệu. 

  ![image-20210930142133256](images/image-20210930142133256.png)

**Bước 4:** Khai báo các khoản phụ cấp mà nhân viên có thể được nhận trong quá trình công tác tại Công ty. Nếu không có phụ cấp, nhân viên nhân sự có thể bỏ trống không nhập dữ liệu

- Tại tab **Phụ cấp**, người dùng bấm **Sửa>Thêm một dòng**, khai báo các khoản phụ cấp và khoảng thời gian nhân viên được nhận phụ cấp.

![image-20210930142357301](images/image-20210930142357301.png)

**Lưu ý:** Một nhân viên trong một quá trình có thể được nhận nhiều loại phụ cấp, tuy nhiên, một loại phụ cấp không được trùng lặp quá trình. 

- Ví dụ: Nhân viên được nhận phụ cấp điện thoại từ ngày 01/01/2021 - 31/12/2021 là 120.000 VNĐ, thì trong khoảng thời gian này nhân viên có thể nhận phụ cấp khác (ăn trưa, xăng xe, nhà ở) nhưng không được nhận thêm khoản phụ cấp điện thoại nào nữa. 

**Bước 5:** Khai báo thông tin liên quan đến BHXH tại tab **Thông tin BHXH**

Người dùng bấm **Sửa>Thêm một dòng**, khai báo các thông tin lương BHXH của nhân viên

![image-20210930151214083](images/image-20210930151214083.png)

Hệ thống tự động tính ra khoản NSDLD đóng cho nhân viên và NLD đóng, các trường thông tin này có thể được cập nhật trong quá trình nhân viên làm việc có sự biến đổi về mức lương cơ bản bằng cách chọn **Thêm một dòng**.

Sau khi hoàn thiện, người dùng bấm **Lưu** để hệ thống lưu lại toàn bộ dữ liệu về nhân viên đã được khai báo.

Với doanh nghiệp có sử dụng nền tảng Digital Workplace, việc tạo hồ sơ nhân viên sẽ nhanh hơn, chuẩn xác nếu các thông tin cá nhân do chính nhân viên tự nhập thông qua điện thoại thông minh. 

Nhân viên chủ động nhập hồ sơ của mình, thì làm theo **Bước 1b**

**Bước 1b:** Nhân viên quản trị nhân lực vào phân hệ **Thiết lập>Người dùng & công ty>Công ty** để tạo tài khoản đăng nhập cho nhân viên mới, cách làm tương tự như **Tạo tài khoản** 

Nhân viên nhân sự tiếp tục chọn **Tạo nhân viên** để thực hiện tạo mới một hồ sơ nhân viên trên hệ thống, nhập các thông tin về chức vụ, phòng/ban, người quản lý của nhân viên mới và bấm **Lưu**

Đến đây, nhân viên sẽ dùng tài khoản được cấp, và thực hiện đăng nhập lên phần mềm VESS trên điện thoại, và thực hiện nhập các thông tin cá nhân của mình. Sau khi nhân viên ấn **Cập nhật** hệ thống sẽ tự động đồng bộ vào hồ sơ nhân viên. Các dữ liệu này sẽ được nhân viên nhân sự kiểm tra và có thể chỉnh sửa nếu sau này nhân viên có nhu cầu thay đổi về thông tin cá nhân.

Các bước tiếp theo vui lòng [quay lại **Bước 2**](#Bước 2)

## Cập nhật hồ sơ nhân viên

Trong quá trình công tác tại Công ty, nhân viên sẽ có các thông tin thay đổi và cần cập nhật trên hệ thống như biến động về Thông tin cá nhân, Hợp đồng, Lương, Thành tích, Quá trình làm việc. Những sự thay đổi này đều được nhân viên nhân sự ghi lại bằng cách cập nhật thông tin hồ sơ nhân viên trong phân hệ Nhân viên.

### Cập nhật thành tích của nhân viên

**Đối tượng thực hiện**: Nhân viên nhân sự

**Các bước thực hiện**

**Bước 1:** Tìm kiếm nhân viên cần cập nhật thông tin tại màn hình **Danh sách nhân viên**

**Bước 2:** Tại tab **Thành tích** chọn **Sửa>Thêm một dòng**, thực hiện cập nhật thông tin thành tích mà nhân viên đó đã đạt được trong quá trình công tác.

![image-20210930165959740](images/image-20210930165959740.png)

### Cập nhật hợp đồng, quá trình làm việc của nhân viên

Nhân viên ký hợp đồng có thời hạn trước khi đến hạn kết thúc hợp đồng cũ, hệ thống sẽ đưa ra cảnh báo các hợp đồng sắp hết hạn để nhân viên nhân sự thực hiện đề xuất hợp đồng lên cấp trên nếu nhân viên có ý định ký tiếp hợp đồng với công ty.

**Quy trình nghiệp vụ:**

- Nhân viên có hợp đồng sắp đến ngày hết hạn, nhân viên nhân sự sẽ thực hiện đề xuất hợp đồng.
- Trưởng phòng nhân sự vào thực hiện phê duyệt/từ chối hợp đồng đề xuất. Sau khi hợp đồng được phê duyệt, dữ liệu sẽ được cập nhật vào quá trình làm việc của nhân viên.
- Nhân viên không muốn ký tiếp hợp đồng với công ty hoặc nhân viên có hợp đồng vô thời hạn muốn nghỉ việc, nhân viên nhân sự thực hiện cập nhật trạng thái là nghỉ việc.

#### Đề xuất hợp đồng

**Đối tượng thực hiện**: Nhân viên nhân sự

**Bước 1:** Vào phân hệ **Nhân viên>Cảnh báo hợp đồng**

![cảnh báo hợp đồng](images/cảnh báo hợp đồng.png)

**Bước 2:** Tại đây hệ thống sẽ hiển thị toàn bộ danh sách các nhân viên chưa có hợp đồng hoặc hợp đồng sắp đến hạn kết thúc hợp đồng hiện tại. 

![image-20210930170508173](images/image-20210930170508173.png)

- Nhân viên nhân sự thực hiện đề xuất hợp đồng mới, bằng cách chọn nút **Đề xuất**. 

![image-20210930171439795](images/image-20210930171439795.png)

- Hợp đồng sau khi Lưu sẽ chuyển sang trạng thái **Mới**, chờ Trưởng phòng nhân sự vào duyệt.

#### Phê duyệt/Từ chối hợp đồng được đề xuất

**Đối tượng thực hiện:** Trưởng phòng nhân sự

**Các bước thực hiện**

**Bước 1:** Đăng nhập hệ thống, vào phân hệ **Nhân viên>Hợp đồng**

![image-20210930173425088](images/image-20210930173425088.png)

- Tại cột **Mới**, Trưởng phòng nhân sự thực hiện review hợp đồng, nếu đồng ý phê duyệt thì chọn **Phê duyệt**, nếu không đồng ý thì chọ **Hủy**
  - Hợp đồng được phê duyệt sẽ chuyển sang cột **Đã duyệt**.
    - Nếu ngày phê duyệt là ngày hợp đồng có hiệu lực thì hợp đồng sẽ chuyển sang cột **Đang chạy** luôn.
    - Nếu ngày phê duyệt < ngày hợp đồng có hiệu lực thì hợp đồng sẽ tự động chuyển sang cột **Đang chạy** vào ngày hợp đồng có hiệu lực.
  - Hợp đồng không được duyệt sẽ chuyển vào cột **Đã hủy**

#### Kết thúc hợp đồng (Nhân viên nghỉ việc)

Nếu nhân viên không có ý định ý tiếp với công ty, khi hợp đồng đến ngày hết hạn, hoặc nhân viên có hợp đồng vô thời hạn muốn nghỉ việc, nhân viên nhân sự sẽ thực hiện cập nhật trạng thái nghỉ việc của nhân viên trong màn hình **Quá trình làm việc**

**Đối tượng thực hiện**: Nhân viên nhân sự

**Các bước thực hiện**

**Bước 1:** Tìm kiếm nhân viên muốn cập nhật trạng thái **Nghỉ việc**

**Bước 2**: Chọn nhân viên và chọn **Sửa>Quá trình làm việc**

![image-20210930175053866](images/image-20210930175053866.png)

**Bước 3:** Chọn **Lưu và đóng**, nhân viên này sẽ có trạng thái là Nghỉ việc, nhân viên nhân sự thực hiện Lưu trữ nhân viên nghỉ việc.
