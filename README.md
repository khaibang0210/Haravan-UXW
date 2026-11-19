# Haravan-UXW

Bộ quy tắc UX writing cho sản phẩm Haravan: Trang quản trị, POS, app mobile, email, thông báo và bài help.

Rule viết dưới dạng [Claude Code rules](https://code.claude.com/docs/en/memory), nên Claude tự áp dụng khi viết hoặc review copy. Người cũng đọc trực tiếp được.

## Nội dung

| File | Nội dung |
|---|---|
| [1-voice-tone.md](.claude/rules/ux-writing/1-voice-tone.md) | Giọng văn, xưng hô (bạn / khách hàng / người mua) |
| [2-writing-rules.md](.claude/rules/ux-writing/2-writing-rules.md) | Viết hoa, dấu câu, số, tiền, ngày giờ, tiếng Anh |
| [3-glossary.md](.claude/rules/ux-writing/3-glossary.md) | Thuật ngữ dùng / không dùng, tên trạng thái |
| [4-ui-patterns.md](.claude/rules/ux-writing/4-ui-patterns.md) | Mẫu cho nút, lỗi, toast, dialog, empty state, placeholder |
| [5-help-docs.md](.claude/rules/ux-writing/5-help-docs.md) | Cách viết bài help |
| [6-checklist.md](.claude/rules/ux-writing/6-checklist.md) | Checklist trước khi chốt copy |

## Nguyên tắc chính

- Gọi người dùng là **bạn**.
- Nút bắt đầu bằng động từ, viết hoa chữ cái đầu câu: `Tạo đơn hàng`.
- Lỗi nói rõ chuyện gì xảy ra và cách sửa, không đổ lỗi người dùng.
- Dùng thuật ngữ tiếng Việt theo bảng: `Trang quản trị`, không viết `Admin`.
- Dấu thanh kiểu cũ: `Xóa`, `Hủy`. Tiền viết `1.250.000đ`.

## Cách dùng

**Với Claude Code**: clone repo, hoặc chép thư mục `.claude/rules/ux-writing/` vào project của bạn. Claude tự nạp rule khi làm việc với file `.tsx`, `.jsx`, `.vue`, `.html`, `.md` và thư mục `locales/`, `i18n/`.

Ví dụ yêu cầu:
- `Review copy trong src/pages/Orders.tsx`
- `Viết thông báo lỗi khi kết nối nhà vận chuyển thất bại`
- `Viết empty state cho trang Mã khuyến mãi`

**Không dùng Claude**: đọc các file ở bảng trên, dùng [checklist](.claude/rules/ux-writing/6-checklist.md) trước khi chốt copy.

## Đóng góp

- Thêm quy tắc vào đúng file theo chủ đề, mỗi quy tắc có ví dụ đúng / sai.
- Giữ nguyên frontmatter `paths` ở đầu mỗi file.
- Thuật ngữ mới cần thống nhất trong team trước khi thêm vào `3-glossary.md`.

## Nguồn

Rút từ [help.haravan.com](https://help.haravan.com). Những chỗ docs viết chưa đồng nhất đã được chuẩn hóa lại.

**Còn mở**: danh sách trạng thái trong `3-glossary.md` chưa đối chiếu với UI thật.
