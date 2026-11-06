---
description: Created by SG, Dương Phạm - 2026
---

# 🗃️ Hướng dẫn sử dụng hệ thống lưu trữ mới - File Server eSmart

***

### 1. Cài đặt và Đăng nhập hệ thống

Truy cập đường link:[ https://tailscale.com/download](https://tailscale.com/download), tìm và tải phiên bản phù hợp với thiết bị của bạn.

<img src="../.gitbook/assets/unknown (68).png" alt="" height="321" width="602">

Mở file Tailscale đã tải xuống và cài đặt<br>

Lưu ý: Khi server đã hoạt động thì bước cài đặt đã được hoàn tất trước đó, trường hợp bị lỗi hệ thống hay xảy ra vấn đề phát sinh mới phải cài lại Tailscale

2.Khởi chạy và kiểm tra Tailscale:Ứng dụng chạy ngầm.

* Sau khi cài đặt, hãy khởi chạy ứng dụng Tailscale.
* Ứng dụng sẽ chạy ngầm và không hiển thị trực tiếp trên màn hình. Để kiểm tra, nhấn vào biểu tượng mũi tên mở rộng trên thanh Taskbar góc dưới bên phải.

<img src="../.gitbook/assets/unknown (16).jpeg" alt="" height="164" width="273">

* Nếu không thấy biểu tượng Tailscale hoạt động, hãy tìm ứng dụng và khởi động lại.

<br>

3.Đăng nhập File Server eSmart:

* Mở ứng dụng có tên Hệ thống lưu trữ chung eSmart.exe.

<img src="../.gitbook/assets/unknown (70).png" alt="" height="195" width="602">

* Nhập tài khoản và mật khẩu do bộ phận IT cấp.

<img src="../.gitbook/assets/unknown (71).png" alt="" height="308" width="602">

* Sau khi đăng nhập thành công, hãy mở trình quản lý tệp (File Explorer) trên Windows. Hệ thống lưu trữ sẽ xuất hiện dưới dạng một ổ đĩa mạng với tên Z: DATA KẾ TOÁN.

<img src="../.gitbook/assets/unknown (72).png" alt="" height="201" width="602">

### 2. Hướng dẫn dành cho User Kế toán viên

Giao diện và thao tác làm việc trên File Server hoàn toàn tương tự như khi bạn sử dụng các thư mục trên Windows bình thường.

<img src="../.gitbook/assets/unknown (73).png" alt="" height="92" width="602">

Ở đây có folder theo từng Tax, người dùng lựa chọn TAX của mình để làm việc

<img src="../.gitbook/assets/unknown (74).png" alt="" height="165" width="602">

Ví dụ ở đây vào folder TAX01 thì bao gồm 5 kế toán, đối với user kế toán thường thì sẽ chỉ hiển thị folder của kế toán đó, còn với user Leader thì sẽ hiện toàn bộ kế toán của mình quản lý

<img src="../.gitbook/assets/unknown (75).png" alt="" height="147" width="602">

Ví dụ ở đây là bên trong của folder KT01 thì gồm 3 công ty. Các folder công ty này sẽ được lead của TAX tạo, trong site này người dùng không được điều chỉnh gì

<img src="../.gitbook/assets/unknown (76).png" alt="" height="115" width="602">

Khi vào trong folder của từng công ty, kế toán được quyền thêm sửa xóa folder, file như bình thường, thao tác y hệt sử dụng trong window.

### 3. Hướng dẫn dành cho User Leader

User Leader có cách hoạt động tương tự như Kế toán viên, nhưng được phân quyền rộng hơn: Leader có thể truy cập vào tất cả các thư mục của các Kế toán viên thuộc TAX do mình quản lý. (Nếu quản lý nhiều TAX, Leader sẽ truy cập được tất cả các TAX đó).

#### 3.1. Tạo thư mục Công ty cho Kế toán viên

Thực hiện khi Kế toán viên tiếp nhận một công ty mới đăng ký dịch vụ:

1. Truy cập vào thư mục TAX tương ứng -> Chọn thư mục của Kế toán viên phụ trách.
2. Click chuột phải chọn New > Folder (hoặc dùng phím tắt tạo thư mục của Windows).

<img src="../.gitbook/assets/unknown (77).png" alt="" height="541" width="602">

3. Đặt tên thư mục theo đúng cú pháp: \[Mã khách hàng] - \[Mã số thuế].

<img src="../.gitbook/assets/unknown (78).png" alt="" height="51" width="602">

#### 3.2. Bàn giao công ty giữa các kế toán CÙNG TAX

LƯU Ý: Trong tất cả trường hợp chuyển folder công ty, leader cần tạo task trước khi chuyển folder công ty giữa các kế toán để lưu trữ thông tin. Yêu cầu tạo task bao gồm:&#x20;

* Cú pháp tiêu đề: Bàn giao công ty từ kế toán A sang kế toán B (Ví dụ: Bàn giao công ty từ Kế toán 23 sang Kế toán 22).
* Người tham gia : Bắt buộc phải gắn thẻ (tag) tài khoản của Kế toán giao và Kế toán nhận vào Task.
* Nội dung trong task: các folder công ty được chuyển giao giữa 2 kế toán
* Quy tắc phối hợp chéo: Nếu việc luân chuyển diễn ra giữa hai phòng ban khác nhau (VD: Từ TAX01 sang TAX02), Leader tạo Task bắt buộc phải tag thêm Leader của phòng ban nhận để cùng phối hợp xác nhận.

Sử dụng khi Leader cần chuyển giao công ty giữa các Kế toán viên thuộc cùng quyền quản lý của mình.

* Thao tác: Truy cập thư mục công ty cần chuyển -> Chọn Copy -> Đi tới thư mục của Kế toán viên nhận bàn giao -> Chọn Paste -> Quay lại thư mục cũ và Xóa thư mục gốc đi.
* Lưu ý quan trọng: Bắt buộc dùng thao tác Copy & Paste rồi Xóa, tuyệt đối KHÔNG dùng lệnh Cut. Việc này giúp hệ thống tự động thiết lập lại phân quyền chính xác cho user mới, tránh làm lỗi hay phức tạp hóa hệ thống phân quyền.

#### 3.3. Bàn giao công ty giữa các kế toán KHÁC TAX

Sử dụng khi cần chuyển công ty sang một Kế toán viên thuộc TAX khác (do Leader khác quản lý). Vì các Leader không có quyền truy cập chéo vào TAX của nhau, nên phải sử dụng đến folder Thùng Chung Chuyển.

1. Leader giao (TAX A): Copy thư mục công ty cần chuyển đi -> Paste vào folder Thùng Chung Chuyển -> Xóa thư mục gốc ở vị trí cũ.
2. Leader nhận (TAX B): Truy cập vào folder Thùng Chung Chuyển -> Copy thư mục công ty đó -> Paste vào thư mục của Kế toán viên tiếp nhận (thuộc TAX B) -> Xóa thư mục công ty vừa copy trong Thùng Chung Chuyển để hoàn tất.

#### 3.4. Quét và xử lý file trùng lặp

Sử dụng khi Leader cần dọn dẹp không gian lưu trữ và kiểm tra các dữ liệu bị nhân bản không cần thiết trong quá trình làm việc của team.

* Bước 1: Leader truy cập vào thư mục Kế toán của cá nhân mình trên hệ thống File Server.
* Bước 2: Tìm và khởi chạy scan trùng lập . bat  đã được IT đặt sẵn tại đây.

<img src="../.gitbook/assets/unknown (79).png" alt="" height="51" width="624">

Nháy đôi vào file để khởi chạy&#x20;

<img src="../.gitbook/assets/unknown (80).png" alt="" height="140" width="624">

<br>

* Bước 3: Sau khi hệ thống trả về kết quả quét trong file Bao\_Cao\_Folder\_Cong\_Ty\_Trung.txt, Leader tiến hành rà soát, giữ lại bản chính và xóa các file bản sao/trùng lặp dư thừa.

<img src="../.gitbook/assets/unknown (81).png" alt="" height="560" width="624">

Lưu ý: Leader chỉ có thể scan các folder của kế toán do mình quản lý. IT sẽ gửi báo cáo scan toàn bộ hệ thống vào mỗi cuối thứ 6 để toàn bộ kế toán kiểm tra

<br>
