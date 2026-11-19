---
paths: ["**/*.{tsx,jsx,vue,html}", "**/locales/**", "**/i18n/**", "**/*.md"]
---

# UX Writing — Mẫu theo loại UI

**Nút**
- Một động từ, cùng lắm thêm một danh từ: `Lưu`, `Thêm nhãn`, `Tạo đơn hàng`.
- Nút xác nhận phải lặp lại đúng động từ của hành động: hành động xóa thì nút là `Xóa`, không phải `OK`/`Đồng ý`.
- Nút phụ: `Hủy`. Nút đóng thông tin: `Đóng`.

**Lỗi**: [Chuyện gì xảy ra]. [Cách sửa].
- Đúng: `Không thể kết nối nhà vận chuyển. Kiểm tra lại Client ID và Secret Key.`
- Sai: `Lỗi! Đã có lỗi xảy ra, vui lòng thử lại sau.`
- Không đổ lỗi cho người dùng ("Bạn đã nhập sai"). Viết là "Số điện thoại chưa đúng định dạng".
- Lỗi validate trường nhập: `[Tên trường] + vấn đề`, ví dụ `Giá bán phải lớn hơn 0`.

**Toast thành công**: [Đối tượng] + đã + [hành động], không chấm câu.
- `Đã lưu sản phẩm`, `Đã xóa 3 đơn hàng`
- Không viết: `Thành công!`, `Cập nhật thành công dữ liệu`

**Dialog xác nhận** (hành động không hoàn tác được)
- Tiêu đề là câu hỏi: `Xóa 3 sản phẩm?`
- Nội dung nêu hậu quả: `Sản phẩm và tồn kho liên quan sẽ bị xóa vĩnh viễn. Bạn không thể hoàn tác.`
- Nút: `Xóa` (nguy hiểm) và `Hủy`.

**Empty state**: [Chưa có gì] + [Lợi ích/hướng dẫn] + [Nút hành động]
- `Chưa có mã khuyến mãi` / `Tạo mã để giảm giá cho đơn hàng của khách.` / `Tạo mã khuyến mãi`

**Lưu ý / cảnh báo trong trang**
- Bắt đầu bằng `Lưu ý:`, viết một ý, nói rõ ảnh hưởng.
- `Lưu ý: Mỗi giao dịch qua PayPal sẽ bị tính phí giao dịch.`

**Placeholder**: ví dụ định dạng, không lặp lại tên trường: `VD: 0901234567`.

**Tooltip / mô tả trường**: giải thích "để làm gì", một câu.
