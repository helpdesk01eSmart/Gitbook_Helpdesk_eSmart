---
description: Created by SG, Dương Phạm - 2026
---

# 📁 Hướng dẫn check trùng lập hệ thống lưu trữ chung – File Server eSmart

***

<mark style="color:$warning;">Lưu ý: Tính năng check trùng lập chỉ hoạt động khi người dùng là leader.</mark>

**Bước 1:** Vào folder KT của leader, tìm 2 file là : &#x20;

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

* Bao\_Cao\_Folder\_Cong\_Ty\_Trung.txt: kết quả scan cả folder sẽ được ghi ở đây
* scan trung lap.bat: file tool quét trùng lập của leader

**Bước 2:** Nháy đôi vào scan trung lap.bat

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

Đợi từ 5 đến 10p cho hệ thống chạy xong.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Như vậy tool đã chạy xong, có thể tắt tool.

**Bước 3:** vào Bao\_Cao\_Folder\_Cong\_Ty\_Trung.txt để kiểm tra kết quả.

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

Đây sẽ là dữ liệu tool phân tích ra, sẽ hiển thị folder nào bị trùng lập, thời gian tạo của các folder đó, đường dẫn của nó. Leader từ những dữ liệu trên để phân tích xem cái nào thưa để xử lý.

**Lưu ý 2:** Leader chỉ có thể quét trùng lập phần mà leader quản lý. Vào mỗi cuối thứ 6 IT sẽ quét toàn bộ hệ thống lưu trữ và các leader sẽ dựa vào data trong đó để loại các folder bị trùng.

Done.
