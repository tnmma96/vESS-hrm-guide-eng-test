### **Mua hàng**

#### **Quy trình nghiệp vụ**

*[Mô tả thông tin chung]*

Quản lý toàn bộ quy trình Mua hàng: Từ yêu cầu gửi báo giá đến Đơn hàng, Hóa đơn mua hàng và Hóa đơn trả hàng.

**Quy trình nghiệp vụ**

*[Hình luồng quy trình nghiệp vụ của Module]*

![](..\finance\images\fin_MuaHang_QuyTrinh.png)

**Các luồng quy trình**

*[Liệt kê đầy đủ các luồng quy trình nghiệp vụ có trong phân hệ Mua hàng,, có link đến Phần Hướng dẫn chi tiết]*

·     Lập yêu cầu báo giá gửi Nhà cung cấp. Chi tiết nghiệp vụ **[tại đây](#Lập yêu cầu báo giá gửi Nhà cung cấp)**

·     Lập Đơn mua hàng gửi Nhà cung cấp. Chi tiết nghiệp vụ [**tại đây**](#_Xác_nhận_Đơn)

·     Mua hàng trong nước về nhập kho. Chi tiết nghiệp vụ [**tại đây**](#_Mua_hàng_trong)

·     Mua hàng hóa nhập khẩu về nhập kho. Chi tiết nghiệp vụ [**tại đây**](#_Mua_hàng_hóa)

#### **Yêu cầu báo giá**

*[Mô tả nghiệp vụ và video hướng dẫn sử dụng các luồng nghiệp vụ của chức năng]*

##### **Mô tả nghiệp vụ**

**Nghiệp vụ**

Khi đơn vị có nhu cầu mua hàng, lập yêu cầu mua hàng thì quy trình thực hiện như sau:

1. Trưởng bộ phận có nhu cầu mua hàng trình Giám đốc đề nghị mua hàng kèm với đề xuất về nhà cung cấp (nếu có.

2. Ban giám đốc duyệt đề nghị mua hàng và chuyển lại cho bộ phận mua hàng; kế toán mua hàng.

3. Bộ phận mua hàng đàm phán giá cả với nhà cung cấp và đề xuất lựa chọn nhà cung cấp tới ban giám đốc.

4. Kế toán mua hàng kiểm tra lại giá cả, thông tin nhà cung cấp để tư vấn thêm cho giám đốc về lựa chọn nhà cung cấp

5. Ban giám đốc phê duyệt về kế hoạch mua hàng

6. Bộ phận Mua hàng thực hiện Lập yêu cầu báo giá và gửi thông tin đến Nhà cung cấp

**Luồng chức năng chính**

·     Lập yêu cầu báo giá gửi Nhà cung cấp. Chi tiết nghiệp vụ **[tại đây](#Lập yêu cầu báo giá gửi Nhà cung cấp)**

·     Xác nhận Đơn hàng từ Nhà cung cấp. Chi tiết nghiệp vụ [**tại đây**](#Xác nhận Đơn hàng từ Nhà cung cấp)

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

##### **Lập yêu cầu báo giá gửi Nhà cung cấp**

**Lập yêu cầu báo giá**

·     Khi Ban GĐ/Quản lý phê duyệt kế hoạch mua hàng; bộ phận mua hàng thực hiện lập Yêu cầu báo giá gửi cho Nhà cung cấp

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng 

1. Vào phân hệ **Mua hàng**, Chọn **Yêu cầu báo giá** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![](images/fin_MuaHang_YCBG_1.png)

2. Khai báo các thông tin chi tiết của Yêu cầu báo giá:

·     Chọn thông tin Nhà cung cấp

·     Chọn tiền tệ giao dịch trong Đơn hàng

·     Khai báo thông tin về Hạn chốt, Ngày nhận

·     Khai báo thông tin về Sản phẩm đặt từ Nhà Cung cấp: 

​			Chọn các sản phẩm yêu cầu báo giá từ nhà cung cấp

​			Nhập thông tin Số lượng, Đơn giá, Chiết khấu và mức Thuế đối với từng Sản phẩm

​			Với nội dung cần Lưu ý đối với Yêu cầu báo giá, thực hiện Thêm ghi chú è Thông tin nội dung sẽ được in trên file gửi nhà 	Cung cấp

3. Nhấn **Lưu**

4. Thực hiện In yêu cầu báo giá: kiểm tra thông tin dữ liệu trên mẫu yêu cầu báo giá và tùy chỉnh thông tin Mẫu yêu cầu

5. Thực hiện Gửi Email đến nhà cung cấp sau khi hoàn thành Yêu cầu báo giá

##### **Xác nhận Đơn hàng từ Nhà cung cấp**

**Xác nhận Đơn hàng**

·     Các đơn hàng được Nhà cung cấp trả hàng theo Yêu cầu báo giá đã gửi, bộ phận mua hàng/kho thực hiện xác nhận về kho của công ty

**Đối tượng thực hiện :** Nhân viên bộ phận mua hàng

1. Vào phân hệ **Mua hàng**, trên **Danh sách Yêu cầu báo giá**, tìm thông tin Yêu cầu đã được Nhà cung cấp xác nhận và thực hiện trả 

![](images/fin_MuaHang_YCBG_2.png)

2. Thực hiện xác nhận thông tin Số lượng sản phẩm mà Nhà cung cấp bàn giao

   ·     Trường hợp Nhà cung cấp trả hàng theo đúng Yêu cầu báo giá: Thực hiện Xác nhận thông tin toàn bộ Đơn hàng mà không cần xác nhận từng Sản phẩm nhận được

   ·     Trường hợp Nhà cung cấp trả hàng còn thiếu/thừa so với Yêu cầu: Khi đó người dùng cần Vào từng sản phẩm để xác nhận theo đúng số lượng thực tế nhận về

![](images/fin_MuaHang_YCBG_3.png)

3.  Nhấn nút **Xác nhận**

**<u>Lưu ý:</u>**

​	Sau khi thực hiện Xác nhận đơn hàng, chương trình tự động tạo ra một Phiếu nhập kho bên Phân hệ Quản lý kho

