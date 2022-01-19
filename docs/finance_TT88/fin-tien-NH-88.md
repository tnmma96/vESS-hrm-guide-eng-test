# Quy trình nghiệp vụ

Kế toán được sử dụng để  :

- Quản lý tình hình thu, chi, tồn tiền mặt
- Hỗ trợ phiếu in theo mẫu TT88
- Lên các báo cáo sổ quỹ tiền ngân hàng, báo cáo kế toán

Quy trình nghiệp vụ

![NH_2217](images/NH_2217.PNG)

**Các luồng quy trình**

*[Liệt kê các luồng quy trình nghiệp vụ có trong Module, có link đến Phần Hướng dẫn chi tiết]*

·     Lập chứng từ Thu tiền gửi. Chi tiết nghiệp vụ **[Thu tiền gửi](#thu-tien-gui)**

·     Lập chứng từ Chi tiền gửi. Chi tiết nghiệp vụ **[Chi tiền gửi](#chi-tien-gui)**

## Thu tiền gửi

### Nhập số dư đầu kỳ

#### Mô tả nghiệp vụ

Cho phép nhập số dư ban đầu cho các tài khoản không có nhu cầu theo dõi chi tiết theo đối tượng (khách hàng, nhà cung cấp, nhân viên), vật tư hàng hoá

#### Hướng dẫn trên phần mềm

1. Vào phân hệ **Ngân quỹ**, Chọn **Tiền gửi**,Chọn **Thu tiền gửi**,  Nhấn **Tạo**

![NH_2201](images/NH_2201.png)

2. Khai báo các thông tin của **Thu tiền gửi**

- Tại mục **Lý do thu** (Tab chung) : Chọn **Số dư đầu kỳ**
- Tại mục **Sổ nhật ký** (Tab chung): Chọn **Tiền ngân hàng**
- Tại mục **Tổng tiền nguyên tệ** (Tab chung): Nhập số tiền dư đầu kỳ

![NH_2202](images/NH_2202.png)

3. Nhấn **Lưu**

   ![NH_2203](images/NH_2203.png)

   

4. Nhấn **Xác nhận**

   ![NH_2204](images/NH_2204.png)

   

Lưu ý:

-  Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Hủy xác nhận**

![NH_2205](images/NH_2205.png)

-  Trường hợp có nhu cầu theo dõi số dư đầu kỳ chi tiết theo Khoản mục chi phí, Công trình, Đơn hàng, Hợp đồng...

  - Nhấn thêm cột dữ liệu ở Tab **Bút toán**
    - Chọn thông tin **Khoản mục chi phí**, **Công trình**, **Đơn hàng**, **Hợp đồng**... muốn theo dõi chi tiết

### Thu tiền từ khách hàng

#### Mô tả nghiệp vụ

Khi khách hàng mang tiền mặt đến trả nợ hoặc nhân viên đi thu tiền tại khách hàng bằng tiền ngân hàng và mang tiền về nộp lại, sẽ phát sinh một số hoạt động sau:

- Sau khi nhận được tiền trả nợ của khách hàng, nhân viên sẽ yêu cầu Kế toán lập Phiếu thu.

- Kế toán chuyển phiếu thu cho Giám đốc ký sau đó chuyển lại cho Thủ quỹ.

- Thủ quỹ căn cứ vào Phiếu thu để thu tiền, sau đó ký vào phiếu thu và yêu cầu người nộp ký vào, đồng thời ghi sổ quỹ.

- Thủ quỹ lưu 1 liên, trả lại 1 liên cho Kế toán và chuyển 1 liên cho khách hàng.

- Kế toán căn cứ vào Phiếu thu đã đủ chữ ký để ghi sổ kế toán tiền gửi và lưu trữ phiếu thu.

#### Hướng dẫn trên phần mềm

1. Vào phân hệ **Ngân quỹ**, Chọn **Tiền gửi**, Chọn **Thu tiền từ khách hàng** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![TT88_PT01](images/TT88_PT01.PNG)

Note: Tại chức năng **Thu tiền từ khách hàng** hiển thị danh sách Hóa đơn bán hàng có trạng thái Đã vào sổ , Tình trạng thanh toán là chưa trả hoặc trả một phần

2. Tích chọn chứng từ khách hàng thanh toán tiền nợ
3. Nhấn **Ghi nhận thanh toán**

![TT88_PT02](images/TT88_PT02.PNG)

4. Tại mục Sổ nhật ký: Chọn **Tiền ngân hàng**

5. Trường hợp số tiền khách hàng thanh toán nhỏ hơn số nợ thực tế trên chứng từ, cần nhập lại số tiền khách hàng trả nợ vào cột **Số trả**. 

6. Nhấn **Tạo Thanh toán** để tạo Phiếu thu tiền ngân hàng

2. Kiểm tra và khai báo bổ sung các thông tin của **Thu tiền gửi**
3. Nhấn **Lưu**
4. Nhấn **Xác nhận**

## Chi tiền gửi

### Thanh toán tiền điện nước, tiền internet, tiền thuê mặt bằng..

#### Mô tả nghiệp vụ

Kế toán thực hiện tạo Phiếu chi tiền ngân hàng cho các dịch vụ phát sinh hàng tháng như : Điện, nước,internet. mặt bằng,......

#### Hướng dẫn trên phần mềm

1. Vào phân hệ **Ngân quỹ**, Chọn **Tiền gửi**, Chọn **Chi tiền gửi** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**

![NH_2206](images/NH_2206.png)

2. Khai báo các thông tin của **Chi tiền gửi**

- Tại mục **Lý do chi**: Thực hiện chọn Lý do chi như **Chi tiền điện bằng ngân hàng**, **Chi tiền mua văn phòng phẩm**,.... (nhấn **Tìm kiếm thêm** để tìm thêm Lý do chi tiền)

- Tại **Tổng tiền nguyên tệ**: Nhập số tiền cần thanh toán

![NH_2207](images/NH_2207.png)

3. Nhấn **Lưu**

![NH_2208](images/NH_2208.png)

4. Nhấn **Xác nhận**

![NH_2209](images/NH_2209.png)

Lưu ý:

-  Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Hủy xác nhận**

- Trường hợp có nhu cầu theo dõi chi phí chi tiết theo Khoản mục chi phí, Công trình, Đơn hàng, Hợp đồng...
  - Nhấn thêm cột dữ liệu ở Tab **Bút toán**
  - Chọn thông tin **Khoản mục chi phí**, **Công trình**, **Đơn hàng**, **Hợp đồng**... muốn theo dõi chi tiết

### Thanh toán tiền lương cho nhân viên

#### Mô tả nghiệp vụ

Căn cứ vào bảng lương của nhân viên, Kế toán thực hiện tạo phiếu chi trả lương cho nhân viên tiền mặt hàng tháng.

#### Hướng dẫn trên phần mềm

1. Vào phân hệ **Ngân quỹ**, Chọn **Tiền gửi**, Chọn **Chi tiền gửi** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**

![NH_2206](images/NH_2206.png)

2. Khai báo các thông tin của **Chi tiền gửi**

- Tại mục **Lý do chi**: Chọn **Chi thanh toán lương cho nhân viên bằng tiền gửi ngân hàng**.
- Tại **Tổng tiền nguyên tệ**: Nhập số tiền cần thanh toán

![NH_2210](images/NH_2210.png)

3. Nhấn **Lưu**

![NH_2211](images/NH_2211.png)

3. Nhấn **Xác nhận**

![TM_2214](images/NH_2214.png)

Lưu ý: Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Hủy xác nhận**

### Thanh toán các chi phí: BHXH, BHYT, BH thất nghiệp

#### Mô tả nghiệp vụ

Khi công ty phát sinh các nghiệp vụ nộp bảo hiểm cho nhân viên, thường phát sinh các hoạt động sau:

- Căn cứ vào Bảng lương của nhân viên, nhân viên chịu trách nhiệp nộp bảo hiểm sẽ lập yêu cầu chi tiền mặt để nộp bảo hiểm.

- Kế toán thanh toán lập Phiếu chi, sau đó chuyển cho Kế toán trưởng và Giám đốc ký duyệt.

- Thủ quỹ căn cứ vào Phiếu chi đã được duyệt thực hiện xuất quỹ tiền mặt

- Kế toán thanh toán căn cứ vào Phiếu chi có chữ ký của thủ quỹ và người nhận tiền để ghi sổ kế toán tiền mặt

- Sau khi nộp bảo hiểm xong, nhân viên đi nộp thuế sẽ giao lại cho kế toán thanh toán giấy xác nhận nộp bảo hiểm của cơ quan bảo hiểm.

#### Hướng dẫn trên phần mềm

1. Vào phân hệ **Ngân quỹ**, Chọn **Tiền gửi**, Chọn **Chi tiền gửi** (Hoặc thực hiện **Tìm kiếm** trực tiếp chức năng trên ô tìm kiếm chung của hệ thống), Nhấn **Tạo**![NH_2206](C:\Users\LUC PLUS\Desktop\ESS-System-Guide-main\ESS-System-Guide-main\docs\finance\images\NH_2206.png)

2. Khai báo các thông tin của **Chi tiền gửi**

- Tại mục **Lý do chi**: Chọn **Chi trả bảo hiểm xã hội** hoặc **Chi trả bảo hiểm y tế** hoặc **Chi trả bảo hiểm thất nghiệp**
- Tại **Tổng tiền nguyên tệ**: Nhập số tiền cần thanh toán

![NH_2213](images/NH_2213.png)

3. Nhấn **Lưu**

![NH_2214](images/NH_2214.png)

4. Nhấn **Xác nhận**

![NH_2215](images/NH_2215.png)

Lưu ý: Muốn chuyển trạng thái từ Hoàn thành về Nháp thì Nhấn **Hủy xác nhận**

## Thanh toán cho nhà cung cấp

### Mô tả nghiệp vụ

Khi nhà cung cấp đến nhận tiền mặt trực tiếp hoặc nhân viên mua hàng mang tiền mặt đến trả nợ cho nhà cung cấp sẽ phát sinh một số hoạt động sau:

- Sau khi nhận được yêu cầu trả nợ của nhà cung cấp hoặc yêu cầu của Giám đốc chi trả nợ cho nhà cung cấp, nhân viên làm đề nghị thanh toán và chuyển Kế toán sẽ lập Phiếu chi.
- Kế toán chuyển Phiếu chi cho Giám đốc ký duyệt sau đó chuyển lại cho Thủ quỹ.
- Thủ quỹ căn cứ vào Phiếu chi để chi tiền, sau đó ký vào phiếu chi và yêu cầu người nhận tiền ký vào, đồng thời ghi sổ quỹ.
- Thủ quỹ lưu 1 liên, trả lại 1 liên cho Kế toán và chuyển 1 liên cho nhà cung cấp.
- Kế toán căn cứ vào Phiếu chi đã đủ chữ ký để ghi sổ kế toán tiền mặt và lưu trữ Phiếu chi.

### Hướng dẫn trên phần mềm

1. Tại phân hệ **Ngân quỹ**, Chọn **Tiền gửi**, Chọn **Thanh toán cho nhà cung cấp** (Hoặc thực hiện tìm kiếm trức tiếp chức năng trên ô tìm kiếm chung của hệ thống)

![TT88_PC01](images/TT88_PC01.PNG)

Ghi chú: Tại chức năng **Thanh toán cho nhà cung cấp** hiển thị danh sách Hóa đơn mua hàng có trạng thái Đã vào sổ, Tình trạng thanh toán là chưa trả hoặc trả một phần

2. Tích chọn chứng từ khách hàng thanh toán tiền nợ
3. Nhấn **Ghi nhận thanh toán**

![TT88_PC02](images/TT88_PC02.PNG)

4. Tại mục Sổ nhật ký: Chọn **Tiền ngân hàng**
5. Trường hợp số tiền khách hàng thanh toán nhỏ hơn số nợ thực tế trên chứng từ, cần nhập lại số tiền khách hàng trả nợ vào cột **Số trả**. 
6. Nhấn **Tạo Thanh toán** để tạo Phiếu chi tiền ngân hàng

7. Kiểm tra và khai báo bổ sung các thông tin của **Chi tiền gửi**
8. Nhấn **Lưu**
9. Nhấn **Xác nhận**