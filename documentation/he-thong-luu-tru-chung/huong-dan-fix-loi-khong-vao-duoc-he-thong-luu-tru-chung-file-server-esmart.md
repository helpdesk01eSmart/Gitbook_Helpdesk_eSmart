---
description: Created by SG, Dương Phạm - 2026
---

# 📂 Hướng dẫn fix lỗi không vào được hệ thống lưu trữ chung – File Server eSmart

***

### 1. Một số lỗi cơ bản

Người dùng có thể làm qua các bước sau để fix một số lỗi như không đăng nhập được, hệ thống thông báo phản hồi chậm....

**Bước 1:** Kiểm tra máy đã có wifi chưa. Tailscale bắt buộc phải có Wifi để sử dụng, nên nhớ kiểm tra wifi có ổn định không nhé

**Bước 2:** Kiểm tra Tailscale đã lên chưa.

Góc bên phải phía dưới màn hình có mũi tên chỉ lên, nhấn mũi tên đó sẽ thấy các ứng dụng được chạy ngầm trên máy, ta sẽ thấy biểu tượng của Tailscale trên đây

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

Nếu không thấy Tailscale hoạt động, tìm app Tailscale bằng cách nhấn Window , gõ Tailscale trên thanh tìm kiếm, rồi khởi chạy app.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

Nhấn open để chạy Tailscale chạy ngầm ( không hiện thị gì). Thực hiện lại bước 2 để kiểm tra tailscale đã chạy chưa rồi sử dụng app Hệ thống lưu trữ eSmart\_V2.exe để đăng nhập sử dụng bình thường.

**Bước 3:** Góc bên phải phía dưới màn hình có mũi tên chỉ lên, nhấn mũi tên đó -> nhấn chuột phải vào Tailscale.

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

Trên màn hình đã hiển thị Tailscale connected + tài khoản esmartcorp.drive@gmail.com -> Mọi thứ vẫn đang bình thường.

### 2. Lỗi không hiển thị folder data kế toán trên desktop hoặc có hiển thị nhưng không vào được.

**Bước 1:** Chuột phải -> New -> Shortcut

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

Trang như này sẽ hiển thị:

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

**Bước 2:** Điển đường dẫn \100.77.62.83\data ke toan rồi ấn Next

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

Nhấn **Finish**

Vậy là sẽ hiển thị 1 Folder ở ngoài desktop cho mình truy cập. Một số trường hợp sẽ yêu cầu mình cần đăng nhập lại để vào được folder, hãy đăng nhập tài khoản truy cập do admin cung cấp.

