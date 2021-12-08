# *Quy trình nghiệp vụ*

**Quy trình nghiệp vụ**

Kế toán kho thực hiện quản lý tình hình nhập, xuất, tồn kho theo chủng loại, nhóm, chi tiết vật tư, hàng hóa, thành phẩm. Ngoài ra có  quản lý chi tiết đến từng kho, hỗ trợ tự động xuất kho theo cách thức xuất kho Nhập trước xuất trước (FIFO),  Nhập sau xuất trước (LIFO) , thực hiện hỗ trợ tự động tính giá xuất kho theo 4 phương pháp: Bình quân tức thời, Bình quân cuối kỳ, Đích danh, Nhập trước xuât trước  và lên các báo cáo kho: Tồn kho, Nhập xuất tồn kho

![](images/fin_Kho_Quytrinh.png)

**Các luồng quy trình**

·     Lập Lệnh sản xuất. Chi tiết nghiệp vụ **tại đây**

·     Lập phiếu nhập kho hàng hóa, thành phẩm. Chi tiết nghiệp vụ **tại đây**

·     Lập phiếu xuất kho hàng hóa, thành phẩm. Chi tiết nghiệp vụ **tại đây**

·     Lập phiếu điều chuyển kho hàng hóa, thành phẩm. Chi tiết nghiệp vụ **tại đây**

·     Lắp ráp/Tháo dỡ. Chi tiết nghiệp vụ **tại đây**

·     Kiểm kê kho . Chi tiết nghiệp vụ **tại đây**

·     Tính giá xuất kho. Chi tiết nghiệp vụ **tại đây**

## *Lập lệnh sản xuất*

### Mô tả nghiệp vụ

Căn cứ vào đơn đặt hàng bán đã duyệt, bộ phận kế hoạch hoặc kế toán thực hiện Lập lệnh sản xuất theo số lượng thành phẩm đã được duyệt tại đơn đặt hàng bán

Đồng thời xác định vật tư chính, phụ cần để sản xuất ra số lượng thành phẩm theo lệnh sản xuất

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Lập lệnh sản xuất

Đối tượng thực hiện: Kế toán kho, nhân viên bộ phận kế hoạch

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Lệnh sản xuất** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_LenhSanXuat_TabChung.png)

![](images/fin_Kho_LenhSanXuat_TabNguyenLieu.png)

 

## *Lập phiếu nhập kho*

### Mô tả nghiệp vụ

Đối với các đơn vị sản xuất sản phẩm hàng loạt hoặc theo đơn đặt hàng... sau khi sản phẩm hoàn thành thì sẽ chuyển về nhập kho. Khi đó, Kế toán sẽ thực hiện các bước sau:

- Căn cứ và phiếu báo số lượng thành phẩm hoàn thành nhập kho của bộ phận sản xuất, Kế toán kho lập Phiếu nhập kho thành phẩm.
- Kế toán trưởng và Giám đốc ký duyệt.
- Căn cứ vào phiếu nhập kho, Thủ kho kiểm tra, nhận hàng và tiến hành nhập kho, người bàn giao và Thủ kho ký vào phiếu nhập kho.
- Thủ kho ghi sổ kho, chuyển 1 liên phiếu nhập kho cho Kếế toán ghi sổ kế toán kho.

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Lập phiếu nhập kho

Căn cứ vào đơn mua hàng, hóa đơn mua hàng, phiếu xuất kho bên bán, và thực tế hàng về, kế toán kho thực hiện Lập phiếu nhập kho (vật tư) tương ứng

Đối tượng thực hiện: Kế toán kho

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Phiếu nhập kho** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_PhieuNhapKho_TabChung1.png)

![](images/fin_Kho_PhieuNhapKho_TabChung2.png)

![](images/fin_Kho_PhieuNhapKho_TabChiTiet.png)



## *Lập phiếu xuất kho*

### Mô tả nghiệp vụ

Khi phát sinh nghiệp vụ xuất nguyên vật liệu dùng cho sản xuất, thông thường sẽ phát sinh các hoạt động sau:

- Căn cứ vào kế hoạch sản xuất hoặc đơn hàng của khách hàng trong kỳ, trưởng bộ phận sản xuất sẽ lập lệnh sản xuất cho các phân xưởng
- Căn cứ vào lệnh sản xuất kế toán kho hoặc người chịu trách nhiệm sẽ đề nghị xuất nguyên vật liệu dùng cho sản xuất
- Kế toán kho lập Phiếu xuất kho, sau đó chuyển Kế toán trưởng và Giám đốc ký duyệt
- Căn cứ vào Phiếu xuất kho, Thủ kho xuất kho hàng hoá
- Thủ kho ghi sổ kho, còn kế toán ghi sổ kế toán kho.

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Lập phiếu xuất kho

Đối tượng thực hiện: Kế toán kho

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Phiếu xuất kho** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_PhieuXuatKho_TabChung1.png)

![](images/fin_Kho_PhieuXuatKho_TabChung2.png)

![](images/fin_Kho_PhieuXuatKho_TabChiTiet.png)



## *Lập phiếu chuyển kho*

### Mô tả nghiệp vụ

Khi phát sinh nhu cầu vận chuyển hàng hóa giữa các kho nội bộ trong doanh nghiệp, thông thường sẽ phát sinh các hoạt động sau:

- Căn cứ vào tình hình tồn kho của các mặt hàng trong kho, Giám đốc sẽ có lệnh điều chuyển hàng giữa các kho trong doanh nghiệp
- Kế toán kho lập Phiếu xuất kho, sau đó chuyển Kế toán trưởng và Giám đốc ký duyệt
- Căn cứ vào Phiếu xuất kho, Thủ kho xuất kho hàng hoá
- Thủ kho ghi sổ kho, còn kế toán ghi sổ kế toán kho.
- Bộ phận chịu trách nhiệm vận chuyển nhận hàng, sau đó chuyển tới kho cần nhập hàng

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Lập phiếu chuyển kho

Đối tượng thực hiện: Kế toán kho

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Phiếu chuyển kho** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_PhieuChuyenKho_TabChung1.png)

![](images/fin_Kho_PhieuChuyenKho_TabChung2.png)

![](images/fin_Kho_PhieuChuyenKho_TabChiTiet.png)

## *Lắp ráp, tháo dỡ*

### Mô tả nghiệp vụ

Khi có yêu cầu xuất kho vật tư hàng hóa để tháo dỡ thành thành phẩm, thông thường sẽ phát sinh các hoạt động sau:

- Tùy thuộc vào nhu cầu hàng hóa để bán hàng, trưởng bộ phận bán hàng hoặc bộ phận kho lập lệnh tháo dỡ hàng hóa
- Căn cứ vào lệnh tháo dỡ kế toán kho hoặc người chịu trách nhiệm sẽ viết phiếu xuất kho hàng hóa mang đi tháo dỡ
- Căn cứ vào Phiếu xuất kho, Thủ kho xuất kho hàng hoá
- Thủ kho ghi sổ kho, còn kế toán ghi sổ kế toán kho.
- Bộ phận đề xuất nhận hàng để mang đi tháo dỡ
- Sau khi tháo dỡ hàng hóa, bộ phận tháo dỡ yêu cầu nhập kho thành phẩm tháo dỡ
- Kế toán kho lập Phiếu nhập kho, sau đó chuyển Kế toán trưởng và Giám đốc ký duyệt
- Căn cứ vào phiếu nhập kho, thủ kho kiểm, nhận thành phẩm và ký vào phiếu nhập kho.
- Thủ kho ghi sổ kho, còn kế toán ghi sổ kế toán kho.

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Lắp ráp, tháo dỡ

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Lệnh lắp ráp, tháo dỡ** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_lenhLapRapThaoDo.png)

## *Phân bổ phụ phí*

### Mô tả nghiệp vụ

Cho phép nhân viên kế toán, thủ kho thực hiện phân bổ phụ phí vào giá vốn hàng nhập kho

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Phân bổ phụ phí

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Phân bổ phụ phí** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]



## *Kiểm kê hàng tồn kho*

### Mô tả nghiệp vụ

Khi có yêu cầu kiểm kê kho từ kế toán trưởng hoặc Ban lãnh đạo công ty, bộ phận kế toán sẽ phát sinh một số hoạt động sau:

- Thành lập ban kiểm kê gồm: Kế toán kho, Thủ kho, Kế toán trưởng hoặc Giám đốc.
- Kiểm kê hàng hóa thực tế trong từng kho, đối chiếu số dư thực tế kiểm kê với sổ kế toán kho
- Nếu có chênh lệch thì tiến hành tìm nguyên nhân xử lý
- Trưởng ban kiểm kê sẽ đưa ra quyết định xử lý
- Căn cứ và quyết định xử lý, Kế toán kho thực hiện lập phiếu nhập kho, hoặc phiếu xuất kho. Đồng thời, hạch toán bút toán chênh lệch thừa, thiếu hàng hóa so với sổ kế toán.
- Trường hợp tìm được nguyên nhân và yêu cầu bồi thường thì hạch toán phải thu hoặc phải trả cho đối tượng phải bồi thường. Trường hợp chưa tìm được nguyên nhân thì hạch toán vào tài sản thừa chờ xử lý hoặc tài sản thiếu chờ xử lý 

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Kiểm kê kho

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Kiểm kê kho** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_KiemKeKho_TabChung.png)

![](images/fin_Kho_KiemKeKho_TabChiTiet.png)

## *Tính giá xuất kho*

### Mô tả nghiệp vụ

Thực hiện tính và cập nhật giá xuất kho vào các phiếu xuất kho trong kỳ, căn cứ vào phương pháp tính giá xuất kho đã được xác định trên **Kho vận\Cấu hình\Nhóm sản phẩm**

**Xem video hướng dẫn**

*[Xây dựng video hướng dẫn trên phần mềm, gồm đủ các luồng chức năng được mô tả bên dưới]*

### Tính giá xuất kho

Đối tượng thực hiện: Kế toán kho

Bước 1: Vào phân hệ **Kho vận**, Chọn nhóm **Hoạt động** , chọn chức năng **Tính giá xuất kho** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

[...Mô tả chi tiết các bước thao tác, trường hợp nhập/xuất, cần lưu ý chỗ cấu hình hạch toán...]

![](images/fin_Kho_TinhGiaXuatKho.png)

Nhập thông tin để tính giá xuất kho: Vật tư hàng hóa cần tính giá, thời gian, kho nhập, kho xuất, kỳ tính giá

Với phương pháp bình quân cuối kỳ: 

·     Tích chọn **Tính theo kho**, giá xuất của vật tư hàng hoá sẽ được tự động tính bình quân trên từng kho.

·     Tích chọn **Tính giá không theo kho**, giá xuất của vật tư hàng hoá sẽ được tự động tính bình quân trên tất cả các kho.

Nhấn **Lưu**

Với phương pháp bình quân tức thời:...

...



Lưu ý: Trường hợp muốn tính giá xuất kho cho một hoặc một số vật tư hàng hoá, thực hiện như sau:

- Tích **Chọn vật tư, hàng hóa** khi thực hiện tính giá xuất kho.
- Nhấn vào biểu tượng ![img](images/Bieu_tuong_ba_cham.png).
- Tích chọn các vật tư hàng hoá cần tính lại giá xuất kho, nhấn **Đồng ý**
