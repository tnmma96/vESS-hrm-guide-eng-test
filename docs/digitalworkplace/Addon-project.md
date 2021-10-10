### Quy trình nghiệp vụ

Là phần mềm quản lý dự án và các chức năng liên quan đến dự án. Thực hiện quản lý: Thông tin dự án, công việc trong dự án, tài liệu dự án, các báo cáo và các chức năng tích hợp như: Quản lý nhân viên, Thảo luận, Bảng chấm công,...Cung cấp bức tranh toàn cảnh về quản lý dự án. Hỗ trợ quản lý dự án hiệu quả.

#### Quy trình

![Flow](pictures\PIC_Pro_Flow.png)

**Các luồng quy trình**

* Quản lý dự án
* Quản lý tài liệu dự án
* Quản lý công việc trong dự án
* Báo cáo

#### Mô tả nghiệp vụ

Khi người sử dụng muốn quản lý dự án thì quy trình thực hiện như sau:

1. Tại ứng dụng **Dự án**, người dùng sẽ thực hiện tạo mới dự án: thêm thành viên, quản trị dự án, tính nỗ lực thực hiện dự án,...
2. Sau khi tạo mới dự án: người dùng sẽ thực hiện tạo các giai đoạn trong dự án (tùy vào mô hình dự án cần thực hiện ví dụ: Agile Scrum; Waterfall,...)
3. Người dùng tiếp tục tạo các công việc, nhiệm vụ hay còn gọi là các tasks trong từng giai đoạn
4. Các thành viên được phân công làm theo từng công việc sẽ vào cập nhật trạng thái công việc mình làm
5. Một dự án được **Đóng** khi tất cả các công việc trong dự án ở trạng thái hoàn thành

**Luồng chức năng chính**

* Quản lý Dự án. Chi tiết nghiệp vụ <u>[tại đây](#quản-lý-dự án)</u>.
* Quản lý tài liệu dự án. Chi tiết nghiệp vụ <u>[tại đây](#quản-lý-tài-liệu-dự-án)</u>.
* Quản lý công việc trong dự án. Chi tiết nghiệp vụ <u>[tại đây](#công-việc)</u>.
* Báo cáo. Chi tiết nghiệp vụ <u>[tại đây](#báo-cáo)</u>.

### Quản lý dự án

#### Tạo mới dự án

Chức năng này cho phép tạo mới dự án 

**Đối tượng thực hiện**: Quản trị hệ thống

**Các bước thực hiện**

1. Vào ứng dụng **"Dự án"**, hiển thị màn hình danh sách dự án

   ![Project-List](Pictures\PIC_Pro_Project_List.png)

2. Nhấn chọn **Tạo** => Hiển thị màn hình nhập liệu các thông tin của dự án

   ![image-20211008110502782](Pictures\PIC_Pro_Create_Form.png)

3. Khai báo Thông tin chung dự án
   - Khai báo Tên dự án
   - Khai báo Nhãn công việc trong dự án
4. Khai báo thiết lập
   * Khai báo các thông tin cần thiết
   * Chọn Phân loại dự án: Dự án nội bộ/ Dự án làm việc với khách hàng
     * Nếu chọn "Dự án làm việc với khách hàng" sẽ hiển thị 1 field Khách hàng để người dùng chọn
   * Chọn Ngày bắt đầu: phải nhỏ hơn hoặc bằng Ngày hết hạn
   * Chọn Ngày hết hạn: phải lớn hơn hoặc bằng Ngày bắt đầu
   * Chọn cấu hình:
     * Webhook
     * Timesheets: Người dùng chọn sẽ thực hiện được chức năng Timesheet
     * Nhiệm vụ con: Người dùng chọn, dự án sẽ có thêm chức năng thêm nhiệm vụ con
     * Công việc định kỳ

5. Khai báo Mô tả

   Thực hiện thêm mô tả cho dự án

6. Nhấn **Lưu** dự án

7. Sau khi Dự án được lưu lại, người dùng có thể thực hiện:

   * Cập nhật thông tin dự án [Chi tiết](####Cập nhật thông tin dự án)

   * Thêm/Sửa/Xóa Nhiệm vụ 

   * Thêm/Xóa tài liệu

   * Chia sẻ tài liệu dự án

     ...


#### Cập nhật thông tin dự án

Chức năng này cho phép thực hiện cập nhật thông tin dự án 

**Đối tượng thực hiện**: Quản trị hệ thống, Quản lý dự án

**Các bước thực hiện**

1. Vào ứng dụng **"Dự án"**, hiển thị màn hình danh sách dự án

![Project-List](Pictures\PIC_Pro_Project_List.png)

2. Tại 1 dự án, chọn tên dự án => Hiển thị màn hình Cập nhật thông tin dự án

![image-20211008134437766](Pictures\PIC_Pro_Update_Form.png)

#### Xóa dự án

Chức năng này cho phép người dùng thực hiện xóa dự án chưa tồn tại công việc nào

**Đối tượng thực hiện**: Quản trị hệ thống, Quản lý dự án

**Các bước thực hiện:**

1. Vào ứng dụng **"Dự án"**, hiển thị màn hình danh sách dự án

![Project-List](Pictures\PIC_Pro_Project_List.png)

2. Tại 1 dự án chọn Thao tác - **Xóa** 

   ![PIC_Pro_Dialog_Delete](Pictures\PIC_Pro_Dialog_Delete.png)

3. Người dùng thực hiện **Đồng ý** => Xóa thành công dự án

   Lưu ý: Chỉ xóa thành công dự án khi dự án chưa có công việc

#### Lưu trữ/Bỏ lưu trữ dự án

Chức năng này cho phép người dùng Lưu trữ hoặc Bỏ lưu trữ dự án

**Đối tượng thực hiện:** Quản trị hệ thống, Quản lý dự án

**Các bước thực hiện:**

1. Vào menu **"Dự án"**, Hiển thị màn hình danh sách dự án

![Project-List](Pictures\PIC_Pro_Project_List.png)

2. Tại 1 dự án chọn Thao tác - **Lưu trữ**  => Dự án được lưu trữ thành công, không hiển thị dự án lên danh sách các dự án
3. Muốn thực hiện **Bỏ lưu trữ** 1 dự án đã bị lưu trữ người dùng thực hiện tìm kiếm bằng Bộ lọc "Dự án - Đã lưu" , sau đó chọn Thao tác - **Khôi phục**

Hệ thống thực hiện bỏ lưu trữ thành công, hiển thị dự án lên màn hình Danh sách dự án

#### Chia sẻ tài liệu dự án

Chức năng này cho phép người dùng chia sẻ tài liệu dự án 

**Đối tượng thực hiện**: Quản trị hệ thống, Quản lý dự án

**Các bước thực hiện**

1. Vào ứng dụng **"Dự án"**, hiển thị màn hình danh sách dự án
2. Tại 1 dự án chọn thao tác: ***Chia sẻ*** => Hiển thị Chia sẻ tài liệu

![image-20211008135618622](Pictures\PIC_Pro_share_document.png)

3. Chọn người nhận để chia sẻ tài liệu

4. Thêm ghi chú

5. Nhấn **Gửi** => Thực hiện chia sẻ thành công tài liệu của dự án đến người nhận



### Quản lý tài liệu dự án

#### Tạo tài liệu

Chức năng này cho phép người dùng thêm tài liệu dự án

**Đối tượng thực hiện:** Quản trị hệ thống, quản lý dự án

**Các bước thực hiện:** 

1. Mở màn hình Cập nhật thông tin dự án

2. Chọn Tài liệu => Hiển thị màn hình danh sách tài liệu của dự án

   ![image-20211009134351478](Pictures\PIC_Pro_List_file.png)

3. Nhấn chọn Tạo => Hiển thị màn hình Tạo tài liệu

   ![PIC_Pro_create_file](Pictures\PIC_Pro_create_file.png)

   4. Khai báo các thông tin sau:

   * Tên file
   * Loại file: Tập tin/Liên kết
     * Nếu chọn Loại file là "Tập tin" thì thực hiện tải file
     * Nếu chọn Loại file là "Liên kết" thì thực hiện nhập URL

   5. Thực hiện **Lưu** => Thêm thành công tệp đính kèm

#### Xóa tài liệu

Chức năng này cho phép người dùng xóa tài liệu dự án

**Đối tượng thực hiện:** Quản trị hệ thống, quản lý dự án 

**Các bước thực hiện:** 

1. Mở màn hình Cập nhật thông tin dự án
2. Chọn phần Tệp đính kèm
3. Tại 1 file chọn thao tác - **Xóa**

![PIC_Pro_Delete_file](Pictures\PIC_Pro_Delete_file.png)

4. Thực hiện "Đồng ý", Xóa thành công file đính kèm

### Công việc 

#### Danh sách công việc

Cho phép người dùng xem danh sách công việc đã tạo cho dự án

**Đối tượng thực hiện**: Quản trị hệ thống và người tham gia dự án

1. Tại màn hình view kanban dự án, chọn dự án muốn xem danh sách công việc. 
Sau khi chọn dự án muốn xem, màn hình hiển thị danh sách chi tiết công việc của dự án đó theo view **kanban**, người sử dụng có thể phân loại công việc bằng cách di chuyển công việc tới một giai đoạn bất kì trong dự án.

![](Pictures/PIC_Pro_Viewkanban.png)

Hoặc có thể chọn hiển thị danh sách công việc View theo **list**: 

![](Pictures/PIC_Pro_Viewlist.png)

Ngoài ra, có thể xem danh sách công việc view theo **Calendar**, **Pivot **, **Grap **, **activity** bằng cách chọn icon tương ứng ở phía bên phải màn hình.  

![](Pictures/PIC_Pro_View.png)

#### Tạo giai đoạn

Chức năng này cho phép người dùng Tạo giai đoạn trong dự án

**Đối tượng thực hiện**: Quản trị hệ thống, Quản lý dự án

**Các bước thực hiện:**

1. Mở màn hình Nhiệm vụ dự án

![PIC_Pro_nhiemvu](Pictures\PIC_Pro_nhiemvu.png)

2. Tạo giai đoạn bằng 2 cách:
   * Thêm cột: Nhập tên cột => Enter
   * Tạo bằng Mẫu giai đoạn: Chọn Mẫu => Nhấn chọn "Sử dụng cái này cho Kanban của tôi"

![PIC_Pro_template_phase](Pictures\PIC_Pro_template_phase.png)

#### **Sửa giai đoạn**

**Đối tượng thực hiện:** Quản trị hệ thống và người sử dụng được phân quyền

**Các bước thực hiện:**

1. Tại màn hình danh sách công việc chọn sửa giai đoạn. 

![](Pictures/PIC_Pro_GiaiDoan.png)

2. Người dùng khai báo các thông tin: 

- Khai báo tên giai đoạn (bắt buộc)

- Chọn loại giai đoạn: Đóng Kanban, Kết thúc, Hủy bỏ. Người sử dụng có thể chọn thêm hơn một Loại giai đoạn. 

  - Đóng kanban: Giai đoạn chọn đóng kanban sẽ được thu gọn lại trên danh sách công việc view kanban
  - Kết thúc: Giai đoạn chọn kết thúc thì toàn bộ công việc trong giai đoạn này được coi là kết thúc
  - Hủy bỏ: Giai đoạn chọn hủy bỏ thì toàn bộ công việc trong giai đoạn này được coi là hủy

- Chọn trạng thái cho giai đoạn:

  - Màu xám: Trạng thái công việc đang làm 
  - Màu đỏ: Trạng thái công việc đã khóa
  - Màu Xanh: Trạng thái công việc hoàn thành 

   Người dùng có thể mô tả chú thích rõ thêm cho từng trạng thái giai đoạn

- Khai báo thông tin mô tả chi tiết cho từng giai đoạn

3. Nhấn chọn **Lưu**

#### Tạo công việc

**Đối tượng thực hiện:** Quản trị hệ thống và người sử dụng được phân quyền

**Các bước thực hiện:**

1. Tại màn hình danh sách dự án, chọn dự án muốn tạo công việc.

2. Nhấn chọn **Tạo**

   ![](Pictures/PIC_Pro_TaoCongViec.png)

3. Người dùng khai báo các thông tin: 

- Khai báo Tên công việc (Bắt buộc)
- Chọn công việc chính
- Khai báo nhiệm vụ con: Người dùng chọn nhiệm vụ con, hệ thống điều hướng đến màn hình khai báo chi tiết công việc con. Trong đó có các thông tin bắt buộc:
  - Tên công việc con
  - Người thực hiện
  - Ngày bắt đầu
  - Ngày kết thúc
- Chọn mức độ ưu tiên
- Chọn ngày bắt đầu (Bắt buộc)
  - Lưu ý: Người sử dụng chọn ngày bắt đầu phải lớn hơn hoặc bằng ngày hiện tại    

- Chọn thời hạn (Bắt buộc)
  - Lưu ý: Người sử dụng chọn ngày kết thúc phải lớn hơn hoặc bằng ngày bắt đầu 

- Khai báo các thông tin cần thiết khác

3. Nhấn chọn **Lưu** công việc

   ![](Pictures/PIC_Pro_TaoCongViec2.png)

   

#### Sửa công việc

**Đối tượng thực hiện:** Quản trị hệ thống và người sử dụng được phân quyền

**Các bước thực hiện:**

   1. Tại màn hình danh sách công việc, chọn công việc muốn sửa

   2. Hệ thống hiển thị màn hình chi tiết công việc, chọn **Sửa**

      ![](Pictures/PIC_Pro_Suacongviec.png)

   3. Người sử dụng chỉnh sửa các thông tin muốn thay đổi

   4. Nhấn chọn **Lưu**


#### Xóa công việc

1. Tại màn hình danh sách công việc, chọn công việc muốn xóa

2. Hệ thống hiển thị màn hình chi tiết công việc, chọn **Thực hiện** => Nhấn chọn **Xóa**

![](Pictures/PIC_Pro_Xoacongviec.png)

3. Hệ thống hiển thị hỏi xác nhận

   - Chọn đồng ý: Xóa công việc thành công

   - Chọn hủy: Thao tác xóa công việc được hủy bỏ

#### Xem hoạt động của dự án

1. Tại màn hình nhiệm vụ, nhấn chọn Hoạt động dự án

![PIC_Pro_activities_project](Pictures\PIC_Pro_activities_project.png)

Hiển thị màn hình Hoạt động của dự án

### Báo cáo

#### Báo cáo theo dự án

Chức năng này được sử dụng để thống kê hiện trạng công việc theo từng dự án gồm:

- Số lượng công việc, mục tiêu, thành viên và thời lượng của dự án

- Báo cáo công việc: Biểu đồ thống kê theo trạng thái; Công việc không đúng hạn; Thành viên xuất sắc trong dự án

- Quá trình thực hiện theo ngày – tuần

- Trạng thái công việc của cá nhân, công việc tồn đọng và cảnh báo hạn xử lý

**Các bước thực hiện:**

1. Tại màn hình nhiệm vụ, nhấn xem Dashboard

   => Hiển thị màn hình Dashboard

   Bao gồm các biểu đồ thống kê sau:

   * Thống kê task
   * Thống kê thành viên
   * Thống kê thời lượng
   * Báo cáo trạng thái tasks
   * Công việc không đúng hạn
   * Thành viên xuất sắc
   * Tổng hợp công việc theo tuần
   * Báo cáo công việc tuần
   * Thành viên còn nhiều việc nhất
   * Thành viên hoàn thành muộn nhất
   * Báo cáo thời gian làm việc
   * Thống kê dự án

![PIC_pro_dashboard1](Pictures\PIC_pro_dashboard1.png)

![PIC_Pro_Dashboard2](Pictures\PIC_Pro_Dashboard2.png)

![PIC_Pro_Dashboard3](Pictures\PIC_Pro_Dashboard3.png)

![PIC_Pro_Dashboard4](Pictures\PIC_Pro_Dashboard4.png)

![PIC_Pro_Dashboard5](Pictures\PIC_Pro_Dashboard5.png)



#### Báo cáo tổng hợp

Chức năng này được sử dụng để thống kê hiện trạng tất cả các dự án gồm:

- Số dự án đang running

- Nhân sự tham gia từng dự án

- Nỗ lực của từng cá nhân theo từng dự án

**Các bước thực hiện**:

1. Mở ứng dụng dự án

2. Nhấn chọn **"Báo cáo"**, chọn **Phân tích nhiệm vụ**

   => Hiển thị màn hình Báo cáo tổng hợp

![PIC_Pro_Report1](Pictures\PIC_Pro_Report1.png)

<p align="center">Biểu đồ cột</p>

![PIC_Pro_Report2](Pictures\PIC_Pro_Report2.png)

<p align="center">Biểu đồ đường</p>

![PIC_Pro_Report3](Pictures\PIC_Pro_Report3.png)

<p align="center">Biểu đồ tròn</p>

