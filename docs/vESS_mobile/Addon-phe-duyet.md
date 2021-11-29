### Quy trình nghiệp vụ

Phân hệ Phê duyệt có chức năng quản lý toàn bộ quá trình phê duyệt: Từ thiết lập loại yêu cầu, lập yêu cầu phê duyệt gửi lên quản lý phê duyệt đến xử lý yêu cầu phê duyệt.

#### Quy trình

![](picture/PIC_DW_PheDuyet_QuyTrinhChung.png)

**Các luồng quy trình**

* Lập yêu cầu phê duyệt. Chi tiết nghiệp vụ <u>[tại đây](#lap-yeu-cau-phe-duyet)</u>.

* Yêu cầu phê duyệt. Chi tiết nghiệp vụ <u>[tại đây](#yeu-cau-phe-duyet)</u>.

* Xử lý yêu cầu phê duyệt. Chi tiết nghiệp vụ <u>[tại đây](#xu-ly-yeu-cau-phe-duyet)</u>.

#### Mô tả nghiệp vụ

Khi có nhu cầu tạo dựng một phê duyệt, người dùng thực hiện các bước theo quy trình sau:

1. Người dùng truy cập hệ thống để lập yêu cầu phê duyệt theo loại phê duyệt đã có trên hệ thống.

2. Gửi yêu cầu đến cán bộ có quyền phê duyệt loại yêu cầu đó.

3. Người được cấp quyền phê duyệt loại yêu cầu thực hiện chấp thuận, từ chối yêu cầu.

**Luồng chức năng chính**

* Lập yêu cầu phê duyệt. Chi tiết nghiệp vụ <u>[tại đây](#lap-yeu-cau-phe-duyet)</u>.

* Gửi yêu cầu phê duyệt. Chi tiết nghiệp vụ <u>[tại đây](#gui-yeu-cau-phe-duyet)</u>.

* Phê duyệt yêu cầu. Chi tiết nghiệp vụ <u>[tại đây](#phe-duyet-yeu-cau)</u>.

### Lập yêu cầu phê duyệt

Người dùng thực hiện lập yêu cầu phê duyệt

**Đối tượng thực hiện:** Người dùng có quyền sử dụng phân hệ Yêu cầu

1. Thực hiện truy cập vào app mobile, chọn phân hệ **Yêu cầu**
    
    ![](picture/PIC_DW_PheDuyet_Phanheyeucau.png)

2. Để tạo mới yêu cầu phê duyệt người dùng có thể thực hiện bằng một trong hai cách:
    
    * Chọn **Tạo mới** từ màn hình danh sách loại yêu cầu
    
    ![](picture/PIC_DW_PheDuyet_DanhSachLoaiYeuCauPheDuyet%20.png)
    
    * Người dùng cũng có thể nhấn vào loại yêu cầu rồi chọn **icon +** (icon Tạo phê duyệt) để tạo mới yêu cầu
    
    ![](picture/PIC_DW_PheDuyet_Danhsachpheduyet.png)
     
3.  Tiến hành nhập các nội dung cho yêu cầu

    * Người dùng thực hiện nhập **Thông tin yêu cầu**
    
    ![](picture/PIC_DW_PheDuyet_Thongtinyeucau.png)
    
    * Nhấn **Tiếp tục** để di chuyển đến màn hình **Thông tin bổ sung**
    
    * Nhập thông tin bổ sung cho yêu cầu phê duyệt
    
    ![](picture/PIC_DW_PheDuyet_Thongtinbosung.png)
    
    * Nhấn **Tiếp tục** để di chuyển đến màn hình **Mô tả yêu cầu**
    
    * Nhập mô tả cho yêu cầu phê duyệt
    
    ![](picture/PIC_DW_PheDuyet_Motayeucau.png)
   
4. Nhấn **Lưu**.

    * **Lưu ý:** Sau khi lưu, trạng thái của yêu cầu là **Nháp**

### Yêu cầu phê duyệt

#### Gửi yêu cầu phê duyệt

Người dùng thực hiện gửi yêu cầu phê duyệt. 

**Đối tượng thực hiện:** Người dùng đã tạo yêu cầu phê duyệt

1. Thực hiện truy cập vào app mobile, chọn phân hệ **Yêu cầu**

2. Để gửi yêu cầu phê duyệt người dùng có thể thực hiện bằng một trong các cách:
    
    * Khi tạo yêu cầu phê duyệt, chọn **Gửi** để gửi luôn yêu cầu
    
    ![](picture/PIC_DW_PheDuyet_Guiyeucau.png)
    
    * Hoặc sau khi đã tạo mới yêu cầu, tại màn hình danh sách thực hiện nhấn vào **icon Menu**, chọn **Gửi**
    
    ![](picture/PIC_DW_PheDuyet_Guiyeucautudanhsach.png)
    
    * Người dùng cũng có thể truy cập vào chi tiết yêu cầu từ màn hình danh sách rồi nhấn **Gửi**
    
    ![](picture/PIC_DW_PheDuyet_Guiyeucautuchitiet.png)

3. Sau khi gửi yêu cầu, trạng thái của yêu cầu chuyển thành **Chờ duyệt**
    
    * **Lưu ý:**
        
        * Nếu loại yêu cầu được cấu hình **Tài liệu** là bắt buộc thì khi nhấn **Gửi** sẽ hiển thị thông báo yêu cầu đính kèm tài liệu. Người dùng cần đính kèm tài liệu mới có thế gửi yêu cầu đi.
        
        * Nếu loại yêu cầu được cấu hình **Tài liệu** là tùy chọn thì khi nhấn **Gửi** yêu cầu sẽ được gửi đi luôn.

#### Hủy yêu cầu phê duyệt 

Người dùng sau khi tạo xong yêu cầu phê duyệt có thể hủy yêu cầu nếu không muốn gửi đi

**Đối tượng thực hiện:** Người dùng đã tạo yêu cầu phê duyệt và trạng thái yêu cầu là nháp

**Điều kiện sử dụng:** Chỉ có thể hủy khi yêu cầu khi phê duyệt ở trạng thái **Nháp**

1. Thực hiện truy cập vào app mobile, chọn phân hệ **Yêu cầu**

2. Chọn loại yêu cầu phê duyệt

3. Chọn **Nháp** tại màn hình danh sách yêu cầu

4. Tại yêu cầu muốn hủy, nhấn **icon Menu**, chọn **Hủy bỏ**

    ![](picture/PIC_DW_PheDuyet_Guiyeucautudanhsach.png)
    
5. Sau khi hủy yêu cầu, trạng thái của yêu cầu chuyển thành **Hủy bỏ**

### Xử lý yêu cầu phê duyệt

#### Phê duyệt yêu cầu

Người dùng thực hiện phê duyệt yêu cầu

**Đối tượng thực hiện:** Người dùng được cấp quyền phê duyệt loại yêu cầu

1. Thực hiện truy cập vào app mobile, phân hệ **Yêu cầu**

2. Để đi đến danh sách yêu cầu phê duyệt người dùng có thể thực hiện bằng một trong hai cách:
    
    * Nhấn nút **Chờ duyệt** từ màn hình danh sách loại yêu cầu để di chuyển trực tiếp đến màn hình danh sách yêu cầu cần duyệt
    
    ![](picture/PIC_DW_PheDuyet_DanhSachLoaiYeuCauPheDuyet%20.png)
    
    * Hoặc nhấn vào loại yêu cầu phê duyệt rồi chọn **Chờ duyệt**
    
    ![](picture/PIC_DW_PheDuyet_Yeucaucanpheduyet.png)
      
3. Người dùng thực hiện phê duyệt yêu cầu
    
    * Tại yêu cầu muốn phê duyệt thực hiện nhấn vào **icon Menu**, chọn **Duyệt**
    
    ![](picture/PIC_DW_PheDuyet_Duyetyeucau.png)
    
    * Người dùng cũng có thể truy cập vào chi tiết yêu cầu rồi nhấn **Phê duyệt**
    
    ![](picture/PIC_DW_PheDuyet_Chitietyeucau.png)
    
    * **Lưu ý:**
        
        * Nếu loại yêu cầu chỉ có một người phê duyệt thì trạng thái yêu cầu sẽ đổi thành **Đã duyệt** sau khi người đó phê duyệt
        
        * Nếu loại yêu cầu có nhiều người phê duyệt thì trạng thái yêu cầu chỉ đổi thành **Đã duyệt** khi tất cả những người thuộc danh sách phê duyệt đã phê duyệt yêu cầu đó

#### Từ chối yêu cầu
    
Người dùng thực hiện từ chối yêu cầu phê duyệt

**Đối tượng thực hiện:** Người dùng được cấp quyền phê duyệt loại yêu cầu

1. Thực hiện truy cập vào app mobile, chọn phân hệ **Yêu cầu**

2. Để di chuyển đến danh sách yêu cầu phê duyệt người dùng có thể thực hiện bằng một trong hai cách:

    * Nhấn nút **Chờ duyệt** từ màn hình danh sách loại yêu cầu
    
    ![](picture/PIC_DW_PheDuyet_DanhSachLoaiYeuCauPheDuyet%20.png)
    
    * Hoặc nhấn vào loại yêu cầu phê duyệt rồi chọn **Chờ duyệt**
    
    ![](picture/PIC_DW_PheDuyet_Yeucaucanpheduyet.png)
      
3. Người dùng thực hiện từ chối yêu cầu phê duyệt
    
    * Tại yêu cầu muốn từ chối thực hiện nhấn vào **icon Menu** chọn **Từ chối**
    
    ![](picture/PIC_DW_PheDuyet_Duyetyeucau.png)
    
    * Người dùng cũng có thể truy cập vào chi tiết yêu cầu rồi nhấn **Từ chối**
    
    ![](picture/PIC_DW_PheDuyet_Chitietyeucau.png)
    
    * **Lưu ý:**
        
        * Nếu loại yêu cầu chỉ có một người phê duyệt thì trạng thái yêu cầu sẽ đổi thành **Từ chối** sau khi người đó từ chối yêu cầu phê duyệt.
        
        * Nếu loại yêu cầu có nhiều người phê duyệt thì trạng thái yêu cầu sẽ đổi thành **Từ chối** khi một trong những người thuộc danh sách bắt buộc **Từ chối** yêu cầu đó.



