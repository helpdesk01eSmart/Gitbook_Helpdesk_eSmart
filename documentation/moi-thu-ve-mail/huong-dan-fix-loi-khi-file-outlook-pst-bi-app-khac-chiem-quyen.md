---
description: Created by SG, Dương Phạm - 2026
---

# 🐔 Hướng dẫn fix lỗi khi file Outlook pst bị app khác chiếm quyền

***

Nếu bạn đang gặp trường hợp như này:

<figure><img src="../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

Thì bạn gặp đúng nơi rồi ấy :))))

Hãy làm theo các bước nhé, có thể sau bước 1 máy bạn đã được fix nhưng tùy trường hợp phải thực hiện bước 2 3 mới xử lý được, chúc bạn có 1 ngày làm việc vui vẻ.

**Bước 1:** Restart máy

Ngay trên thông báo Outlook đã hiển thị rằng là hãy restart máy. Bước này giải quyết 70% vấn đề gặp phải rồi. Nếu không được thì thực hiện bước 2

**Bước 2:** Chuột phải dưới thanh task bar -> Task manager

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

Sau đó Task manager sẽ hiển thị:

<figure><img src="../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

Trên thanh tìm kiếm -> gõ Outlook để tìm kiếm

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

Chuột phải vào tác vụ Outlook đang hiển thị: Chọn end task.

Mở lại Outlook để kiểm tra, nếu chưa được thì kiểm tra tiếp bước 3.

**Bước 3:** Nhấn Window + R trên bàn phím

Tìm từ khóa Resmon trên trang Run

<figure><img src="../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

nhấn ok.

<figure><img src="../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

Đây là giao diện của trình quản lý nguồn tài nguyên của Window, trên thanh menu, chọn CPU

<figure><img src="../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

Trong phần Associated Handles, tìm từ khóa .pst ( đuôi file outlook bị chiếm) hoặc từ khóa Outlook, điền xong từ khóa thì nhấn enter để tìm kiếm.

<figure><img src="../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

Trên màn hình thấy 1 số kết quả, mình chỉ quan tân các type là Event.  Chuột phải vào tác vụ đó -> end process

<figure><img src="../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

Cứ thử đóng tác event đến khi nào Outlook không báo lỗi nữa, chúc bạn thành công :))))

Done.
