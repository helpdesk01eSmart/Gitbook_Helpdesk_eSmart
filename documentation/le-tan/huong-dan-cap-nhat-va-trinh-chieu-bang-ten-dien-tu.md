---
description: Created by SG, Dương Phạm - 2026
---

# 📱 Hướng dẫn cập nhật và trình chiếu bảng tên điện tử

***

### 1. Tổng quan hệ thống

Hệ thống hiển thị bảng tên hoạt động dựa trên 2 định dạng:

* Video bảng tên: Là 1 video tổng hợp hình ảnh bảng tên của tất cả khách hàng. Mỗi công ty sẽ xuất hiện lần lượt trong 5 giây, IT sẽ là người làm và đăng video này mỗi tháng 1 lần
* Ảnh bảng tên (Tĩnh): Là hình ảnh hiển thị cố định bảng tên của một khách hàng duy nhất.

### 2. Quy trình tạo Ảnh bảng tên

Ảnh bảng tên được hệ thống tạo ra thông qua 2 phương thức:

#### 2.1. Script tự động (Dành cho IT)

* Hoạt động dựa trên việc đọc dữ liệu từ file Excel và xuất đồng loạt toàn bộ bảng tên của các công ty có trong danh sách.
* Việc này giúp tiết kiệm thời gian khi có số lượng lớn dữ liệu cần cập nhật. IT sẽ thực hiện chạy script tự động vào đầu mỗi tháng.

#### 2.2. Web dụng tạo bảng tên (Dành cho Lễ tân)

Web được xây dựng để đơn giản hóa quy trình cập nhật nhỏ lẻ. Người dùng chỉ việc điền thông tin và bảng tên sẽ được tự động xuất ra.

* **Bước 1:** Truy cập trang web: [https://tao-bang-ten-esmart-ac5eb4fzsjelvnmqjys3j4.streamlit.app/](https://tao-bang-ten-esmart-ac5eb4fzsjelvnmqjys3j4.streamlit.app/)
* Bước 2: Nhập các thông tin cần thiết:

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

* Lễ tân nhập thông tin công ty vào các trường tương ứng (thông tin nào công ty không có có thể bỏ trống).
* Nhấn nút TẠO BẢNG TÊN, khi đó bảng tên sẽ download và lễ tân có thể trình chiếu bình thường

### 3. Hướng dẫn trình chiếu bảng tên lên màn hình

Đăng nhập hệ thống:

* Truy cập địa chỉ: http://www.techplaza.com.vn:8088/cdmsA/index.jsp
* Đăng nhập bằng tài khoản và mật khẩu do IT cung cấp để vào trang quản lý của văn phòng.

#### 3.1. Tải ảnh lên hệ thống (Upload)

Lưu ý: Mọi hình ảnh bảng tên tĩnh phải được tải lên hệ thống trước khi trình chiếu.

1. Trên thanh công cụ, chọn mục Media

<img src="../.gitbook/assets/unknown (83).png" alt="" height="318" width="624">

2. Nhấn chọn nút Upload  trên thanh Image

<img src="../.gitbook/assets/unknown (84).png" alt="" height="207" width="269">

➔ Tại thanh upload, chọn Add file.

3. Chọn một hoặc nhiều ảnh cần tải lên (tối đa 100 ảnh/lần).

<img src="../.gitbook/assets/unknown (85).png" alt="" height="209" width="267">

4. Nhấn nút Upload (đang sáng màu cam) để tải ảnh vào bộ nhớ hệ thống.

#### 3.2. Trình chiếu Video bảng tên (Chiếu tất cả các công ty)

1. Trên thanh công cụ, chọn Program ➔ Chọn Playlist.

<img src="../.gitbook/assets/unknown (86).png" alt="" height="315" width="624">

2. Trong các playlist, nhấn chọn vào mục VIDEO BANG TEN.

<img src="../.gitbook/assets/unknown (87).png" alt="" height="318" width="624">

3. Ở góc trên bên phải màn hình, chọn Publish.

<img src="../.gitbook/assets/unknown (88).png" alt="" height="315" width="624">

4. Nhấn chọn vào video bảng tên cần chiếu trong ô playlist.
5. Tại phần Publish Attribute, thiết lập thời gian hiển thị hợp lý tại mục Expiration ( ngày hết hạn ). Sau đó nhấn Next (ở góc trên bên trái).

<img src="../.gitbook/assets/unknown (89).png" alt="" height="315" width="624">

6. Ở góc dưới bên trái màn hình, chọn Player tương ứng ➔ Tại cột Target Player / Organization / Group, tích chọn bảng tên điện tử của văn phòng đó ( thường là có 1 cái).
7. Nhấn Publish để hoàn tất việc đăng tải.
8. Lưu ý quan trọng: Dựa vào thời gian cột Publish Time, tiến hành xóa toàn bộ các lịch publish cũ để hệ thống chạy chuẩn xác.

#### 3.3. Trình chiếu Ảnh bảng tên tĩnh (Chỉ chiếu duy nhất 1 công ty)

1. Trên thanh công cụ, chọn Program ➔ Chọn Playlist.

<img src="../.gitbook/assets/unknown (90).png" alt="" height="315" width="624">

2. Nhấn chọn vào mục DUNG BANG TEN.

<img src="../.gitbook/assets/unknown (91).png" alt="" height="317" width="624">

3. Giao diện thiết lập: Góc trái hiển thị kho ảnh hiện có, góc phải là Preview (xem trước), bên dưới là hàng đợi (các ảnh đang được xếp lịch chiếu).
4. Thao tác: Ở kho ảnh bên trái, Lễ tân tìm và kéo thả ảnh công ty cần chiếu xuống khu vực hàng đợi bên dưới. (Vì đây là chế độ chiếu duy nhất 1 bảng tên, hàng đợi chỉ nên chứa 1 hình ảnh duy nhất).
5. Sau khi đã đưa ảnh xuống hàng đợi, thực hiện thao tác Publish hoàn toàn tương tự như khi xuất video (Thực hiện lại từ Bước 3 đến Bước 8 của Mục 3.2).&#x20;
