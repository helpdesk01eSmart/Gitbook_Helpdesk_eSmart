---
description: Created by SG. Dương Phạm - 2026
---

# 🪪 Hướng dẫn cập nhật thẻ ra vào của khách hàng

***

### 1. QUY ĐỊNH ĐẶT TÊN TRÊN THẺ&#x20;

#### Lưu ý chung (Bắt buộc):

* Sử dụng dấu gạch ngang có khoảng trắng ở hai bên (-) để ngăn cách các cụm từ.
* Tên chủ thẻ: Chỉ lấy tên chính (1 chữ) và phải VIẾT IN HOA toàn bộ.

#### 1.1. Khối Phòng Làm Việc (PLV)

**Cấu trúc:** PLV - \[SỐ PHÒNG.STT] - \[TÊN]&#x20;

**Giải thích:**

* PLV: Mặc định cho Phòng làm việc.
* SỐ PHÒNG.STT: Mã số phòng và số thứ tự định danh của nhân sự trong phòng đó (VD: A02.01).

**Ví dụ:** \* PLV - A07.11 - NHỰT (ĐÚNG)&#x20;

* PLV - B11.22 - Tuấn (SAI - do tên chưa viết in hoa)&#x20;

#### 1.2. Khối Bàn Làm Việc (BLV)

**Cấu trúc:** BLV - \[SỐ VP.STT] - \[TÊN]&#x20;

**Giải thích:**

* BLV: Mặc định cho Bàn làm việc.
* SỐ VP.STT: Mã địa chỉ văn phòng và số thứ tự bàn (VD: 50.01).

**Ví dụ:**

* BLV - 412.23 - NHỰT (ĐÚNG)&#x20;
* BLV - 197 - Nghĩa (SAI - do thiếu số thứ tự và tên chưa viết in hoa)&#x20;

#### Khối Phòng Giám Đốc (PGD)

**Cấu trúc:** PGD - \[SỐ PHÒNG.STT] - \[TÊN]&#x20;

**Giải thích:**

* PGD: Mặc định cho Phòng Giám đốc.
* SỐ PHÒNG.STT: Mã số phòng và số thứ tự định danh (VD: A02.01).

**Ví dụ:**

* PGD - A07.11 - NHỰT (ĐÚNG)&#x20;
* PGD - B11.22 - Tuấn (SAI - do tên chưa viết in hoa)&#x20;

<mark style="color:$warning;">Lưu ý chung, thứ tự định danh này là con số tăng tiến, dựa vào danh sách có sẵn, lễ tân đặt thứ tự định danh sao cho phù hợp</mark>

### 2. QUY TRÌNH NHẬP THÔNG TIN VÀO FILE QUẢN LÝ THẺ&#x20;

#### 2.1 Hướng dẫn nhập liệu danh sách thẻ khách hàng

Lễ tân truy cập đường link để vào file quản lý thẻ để điền thông tin thẻ :

https://docs.google.com/spreadsheets/d/1izRAYJh1Yli9cUkTrLk9XmHalSRv9k04Enz3QTHAKiw/edit?usp=sharing

<img src="../.gitbook/assets/unknown (107).png" alt="Giao diện quản lý thẻ" height="283" width="624">

Ở đây có các cột để lễ tân nhập thông tin lễ tân cần nhập liệu:&#x20;

* Mã Thẻ Ra Vào: Mã số được in trên thẻ, kí hiệu là NO.xxxx ( xxxx là số)
* Tên Trên Thẻ: đã được hướng dẫn ở trên
* Họ & Tên
* Tên công ty
* Tình trạng thẻ : có 4 tình trạng thẻ gồm:&#x20;
* Chưa cấp
* Đang hoạt động
* Mất thẻ (Lock)
* Đề nghị cấp
* Tùy theo trường hợp, lễ tân chọn tình trạng trẻ
* ID máy in(Mã KH) – Mã công ty
* Ghi Chú: dùng để ghi chú lại tình trạng chi tiết thẻ, khách hàng, vấn đề gặp phải, bộ phận IT sẽ nhìn vào chú thích để xử lý các vấn đề gặp phải

Với các trường hợp khách làm mất thẻ, lễ tân bôi đỏ hàng chứa thẻ của khách để lưu ý

#### 2.2 Hướng dẫn nhập liệu Nhật kí nhận - trả thẻ&#x20;

Nhật ký nhận - trả thẻ dùng để lễ tân ghi lại thời gian, thông tin trao thẻ . Tất cả các thẻ sẽ được IT mở sẵn và cập nhật thông tin 2 lần 1 tháng (vào ngày 5 và ngày 20) nên khi có việc nhận, trả thẻ hay đổi tên thẻ của khách hàng, lễ tân chủ động ghi lại thông tin giao dịch trong sheet NHẬT KÍ THẺ của từng văn phòng.

<img src="../.gitbook/assets/unknown (108).png" alt="" height="279" width="624">

**Có các thông tin lễ tân cần cập nhật:**

* STT
* Giờ
* Ngày
* Mã thẻ ( Dạng NO.0000)
* Thu lại từ ai: Ghi họ và tên&#x20;
* Tên công ty ( màu vàng) : tên công ty người trả thẻ
* Cấp mới cho ai: Ghi họ và tên
* Tên công ty ( màu xanh): tên công ty người nhận thẻ
* Ghi chú&#x20;

**Lưu ý trong trường hợp cấp thẻ mới:**

* Thu lại từ ai: Lễ tân
* Tên công ty ( màu vàng): eSmart
* Ghi chú: Cấp mới thẻ cho khách

**Lưu ý trong trường hợp thu hồi lại thẻ:**

* Cấp mới cho ai: Lễ tân
* Tên công ty ( màu xanh ): eSmart
* Ghi chú: khách hàng trả thẻ

**Trong trường hợp khách hàng mất thẻ:** Lễ tân thông báo ngay cho IT để được khóa thẻ kịp thời. Nội dung thông báo theo mẫu sau:

* Mã thẻ bị mất
* Tên khách hàng
* Tên công ty

Done.
