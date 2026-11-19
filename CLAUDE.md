# Haravan — UX Writing

Repo này chứa bộ quy tắc UX writing cho sản phẩm Haravan (Trang quản trị, POS, app mobile, email, thông báo, bài help).

## Cấu trúc

```
.claude/rules/ux-writing/
  1-voice-tone.md      Giọng & xưng hô
  2-writing-rules.md   Quy tắc viết (viết hoa, dấu câu, số, tiền, ngày)
  3-glossary.md        Thuật ngữ dùng / không dùng, tên trạng thái
  4-ui-patterns.md     Mẫu cho nút, lỗi, toast, dialog, empty state
  5-help-docs.md       Cách viết bài help
  6-checklist.md       Checklist trước khi chốt
```

Rule tự nạp khi làm việc với file `.tsx/.jsx/.vue/.html`, `locales/`, `i18n/`, `.md` (xem `paths` trong frontmatter).

## Khi viết hoặc review copy

- Theo đúng rule trong `.claude/rules/ux-writing/`. Rule mâu thuẫn với chữ đang có trên help.haravan.com thì **rule thắng**: docs hiện tại chưa đồng nhất.
- Review copy: trả về theo dạng `Hiện tại → Đề xuất → Lý do (rule nào)`.
- Gặp thuật ngữ chưa có trong `3-glossary.md`: đề xuất cách dùng và hỏi trước, không tự đặt.
- Viết tiếng Việt có dấu đầy đủ, dấu thanh kiểu cũ (`Xóa`, `Hủy`).

## Khi sửa rule

- Mỗi file một chủ đề. Thêm nội dung vào đúng file, không tạo file mới nếu file cũ còn dưới ~300 dòng.
- Mỗi quy tắc nên có ví dụ đúng / sai.
- Giữ nguyên frontmatter `paths` ở mọi file.
- Nguồn tham khảo: https://help.haravan.com (sitemap: `/sitemap.xml`).

## Việc còn mở

- Danh sách trạng thái trong `3-glossary.md` lấy từ docs, chưa đối chiếu UI thật.
