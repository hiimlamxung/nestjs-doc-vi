# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Tổng quan dự án

Đây là tài liệu NestJS được dịch sang tiếng Việt (nestjs-doc-vi). Dự án gồm các file HTML tĩnh, không có build tools, không có dependencies.

## Cấu trúc

- **Overview/** - 9 file: Controllers, Providers, Modules, Middleware, Exception filters, Pipes, Guards, Interceptors, Custom decorators
- **Fundamentals/** - 12 file: async-providers, circular-dependency, custom-providers, dynamic-modules, execution-context, injection-scopes, lazy-loading-modules, lifecycle-events, module-reference, platform-agnosticism, testing, discovery-service
- **Techniques/** - 21 file: Configuration, Database, Mongo, Validation, Caching, Serialization, Queues, Logger, Cookies, Events, Compression, FileUpload, StreamingFiles, HTTPModule, Session, MVC, Versioning, TaskScheduling, Logging

## Kiến trúc HTML

Mỗi file HTML là một trang tài liệu độc lập với:
- Ngôn ngữ: `lang="vi"`
- Dark theme với accent color `#ea2845`
- Font: Inter (body), Source Code Pro (code)
- Sidebar Table of Contents (sticky)
- Code blocks có filename header, tab switching, copy button
- Callout boxes: `.hint`, `.warn`, `.note`
- Layout max-width 1060px, responsive

## Quy ước

- Tên file Overview dùng PascalCase có khoảng trắng (VD: `Exception filters.html`)
- Tên file Fundamentals dùng kebab-case (VD: `lazy-loading-modules.html`)
- Tên file Techniques dùng PascalCase không khoảng trắng (VD: `FileUpload.html`)
- CSS và JS được nhúng trực tiếp trong mỗi file HTML (không có file CSS/JS riêng)
- Khi crawl document của trang đích thì nội dung viết bằng tiếng Việt, code examples giữ nguyên tiếng Anh. Nội dung viết bằng tiếng Việt, dịch sát nghĩa, không thêm bớt hay chế thêm lời. Các khái niệm kỹ thuật thì vẫn để chuẩn tiếng Anh cộng đồng. Yêu cầu đầy đủ các section của doc, đúng thứ tự.
