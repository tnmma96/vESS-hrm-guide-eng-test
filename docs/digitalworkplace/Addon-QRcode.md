### Quy trình nghiệp vụ

Khách hàng đăng nhập vào hệ thống bằng mã QR đã được đăng ký để thực hiện xem, cập nhật thông tin cá nhân, xem thông báo, tin tức và các nội dung khác.

#### Quy trình

![](picture/PIC_DW_Addon_QRcode-QuyTrinh.jpg)

**Các luồng quy trình**

* Đăng nhập bằng QR code. Chi tiết nghiệp vụ <u>[tại đây](#ang-nhap-bang-qr-code)</u>.

#### Mô tả nghiệp vụ

Khi người sử dụng muốn đăng nhập vào hệ thống bằng QR code thì quy trình thực hiện như sau:

1. Tại màn hình đăng nhập, người dùng chọn chức năng đăng nhập bằng mã QR

2. Thực hiện quét QR code để đăng nhập hoặc xem Hướng dẫn quét mã QR


**Luồng chức năng chính**


* Đăng nhập bằng QR code. Chi tiết nghiệp vụ <u>[tại đây](#ang-nhap-bang-qr-code)</u>.


**Video hướng dẫn**


### Đăng nhập bằng QR code

Người dùng đăng nhập nhanh vào hệ thống bằng QR code

**Đối tượng thực hiện:** Người dùng

Điều kiện trước: Người dùng đã đăng nhập trên ứng dụng của điện thoại

1. Tại màn hình đăng nhập

    ![](picture/PIC_DW_Addon_QRcode-DangNhap.jpg)

2. Người dùng chọn chức năng đăng nhập bằng mã QR bằng cách nhấn vào biểu tượng ![](picture/PIC_DW_Addon_QRcode-IconLoginScanQR.jpg). Màn hình sẽ hiển thị mã QR

    ![](picture/PIC_DW_Addon_QRcode-QuetMaQR.jpg)

3. Sau đó, người dùng truy cập vào app trên thiết bị di động, vào tài khoản người dùng 

    ![](picture/PIC_DW_Addon_QRcode-QuetMaQR2.jpg)

    Chọn biểu tượng ![](picture/PIC_DW_Addon_QRcode-QuetMaQR3.png). Di chuyển Camera đến mã QR hiển thị trên màn hình máy tính để tiến hành quét mã QR.

    * **Ghi chú:** Thiết bị của người dùng phải được đăng ký trên hệ thống trước đó

    * Hệ thống sẽ thực hiện đối chiếu với mã đã được quy định sẵn cho từng người dùng. Nếu mã khớp đăng nhập thành công trên máy tính
    
    * Nếu mã QR không đúng, hệ thống ở lại trang đăng nhập với mã QR và người dùng sẽ thực hiện lại việc quét mã QR
    
4. Trường hợp người dùng có nhu cầu xem hướng dẫn trước khi thực hiện đăng nhập với mã QR, tại màn hình đăng nhập bằng QR Code, người dùng nhấn **Xem hướng dẫn** để di chuyển đến trang hướng dẫn quét mã QR



