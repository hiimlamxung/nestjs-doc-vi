---
paths:
  - "**/*.html"
---

# Quy tắc chung cho tất cả file HTML

## Design System
- Dark theme với accent color đỏ `#ea2845`
- CSS variables được định nghĩa trong `:root` (--color-bg, --color-primary, --color-surface...)
- Font: Inter cho body, Source Code Pro cho code
- Layout 3 cột: Sidebar (280px) + Content + TOC (220px)

## Cấu trúc file HTML
- Mỗi file là standalone HTML (tự chứa CSS + JS)
- Lang="vi", title theo format: `Tên chủ đề | NestJS - Tài liệu tiếng Việt`
- Có sidebar navigation, table of contents, và copy button cho code blocks

## Quy tắc khi chỉnh sửa
- Giữ nguyên design system hiện tại, KHÔNG thay đổi CSS variables
- Nội dung viết bằng tiếng Việt.
- Code examples giữ nguyên tiếng Anh
- Đảm bảo responsive và scroll behavior smooth
