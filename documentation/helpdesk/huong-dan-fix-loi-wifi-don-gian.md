---
description: Created by SG, Dương Phạm - 2026
icon: wifi
---

# Hướng dẫn fix lỗi wifi đơn giản

***

Nếu thấy wifi bị lỗi kết nối, mất cài đặt wifi thì đây sẽ là các cách để lôi wifi về nhé.

### 1. Đưa wifi đi máy bay

**Bước 1:** tắt wifi và bậy chế độ máy bay\
Bước này nhằm tắt hết các sóng đang phát trên máy, reset các sóng lỗi trên máy, khi máy lỗi hãy thực hiện trong vòng 5p

**Bước 2:** tắt chế độ máy bay và bật lại wifi\
sau khi sóng đã được reset thì hãy bật lại wifi như bình thường để xem thiết bị đã có thể kết nối mạng hay chưa.

### 2. Fix lỗi địa chỉ IP

Nếu reset sóng cơ bản không làm hết lỗi, hãy thực hiện theo các bước:\
**Bước 1:** nhấn phím window trên bàn phím, tìm kiếm CMD

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>

Nhắn enter để truy cập cmd

**Bước 2:** tại giao diện gõ lệnh, thực hiện lệnh : **ipconfig /release**\
![](<../.gitbook/assets/image (94).png>)

sau khi lệnh chạy xong, gõ tiếp lệnh **ipconfig /renew**

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

**Bước 3:** kiểm tra xem mạng wifi đã có chưa. Có thể kiểm tra xem có mạng chua bằng lệnh Ping 8.8.8.8

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

Lệnh này dùng để ping tới internet ( DNS của google), nếu ping thành công như ảnh thì thiết bị đã kết nối được với google.<br>

### 3. Khởi động lại card wifi trên máy

Nếu các bước sau vẫn không thể kết nối, hãy tử reset card wifi trên máy xem có thực hiện được không.

**Bước 1:** nhấn Window + R, 1 trang sẽ hiện lên góc trái màn hình

<figure><img src="../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

Gõ ncpa.cpl và nhấn ok để truy cập vào cài đặt.

<figure><img src="../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

Trang sẽ hiển thị rất nhiều card mạng trên đây. vì vấn đề là wifi nên mình sẽ thao tác trên card wifi

**Bước 2:** chuột phải vào card wifi , chọn disable <br>

<figure><img src="../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

Sau khi disable xong, card wifi sẽ chuyển thành màu xám, lúc này chuột phải vào card wifi, chọn enable<br>

<figure><img src="../.gitbook/assets/image (101).png" alt=""><figcaption></figcaption></figure>

Sau khi enable, máy tính sẽ mất 1 2 p để bật lại card wifi, sau đó mở wifi và truy cập bình thường\
Done.
