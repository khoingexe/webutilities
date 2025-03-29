# Markdown Viewer

![Demo](https://img.shields.io/badge/demo-available-green) 
![License](https://img.shields.io/badge/license-MIT-blue)

Trình xem Markdown trực tuyến đơn giản với chế độ sáng/tối, hỗ trợ xem file từ URL bất kỳ.

## Tính năng chính

✅ **Xem file Markdown từ URL**  
✅ **Chế độ sáng/tối** (lưu cài đặt bằng cookie)  
✅ **Tùy chỉnh tiêu đề trang**  
✅ **Giao diện tiếng Việt**  
✅ **Hiển thị code đẹp mắt**  
✅ **Tương thích mọi thiết bị**  

## Cách sử dụng

Truy cập trang web với các tham số URL:

```
https://khoingexe.github.io/webutilities/markdown/viewer.html?url=URL_FILE_MD&title=TIÊU_ĐỀ
```

### Ví dụ:

1. Xem README.md từ GitHub:
```
https://khoingexe.github.io/webutilities/markdown/viewer.html?url=https://raw.githubusercontent.com/khoingexe/webutilities/main/README.MD&title=README
```

2. Xem file markdown bất kỳ:
```
https://khoingexe.github.io/webutilities/markdown/viewer.html?url=https://example.com/document.md
```

## Tham số URL

| Tham số | Bắt buộc | Mô tả |
|---------|----------|-------|
| `url`   | Có       | Đường dẫn đến file markdown (phải là raw content) |
| `title` | Không    | Tiêu đề tùy chỉnh cho trang web |

## Công nghệ sử dụng

- [Marked.js](https://marked.js.org/) - Render Markdown
- [DOMPurify](https://github.com/cure53/DOMPurify) - Bảo mật XSS
- [Montserrat](https://fonts.google.com/specimen/Montserrat) - Font chữ
- Pure CSS - Không sử dụng framework

## Development

1. Clone repository:
```bash
git clone https://github.com/khoingexe/webutilities.git
```

2. Mở file `markdown/viewer.html` trong trình duyệt

## Tác giả

**Nguyễn Minh Khôi**  
- GitHub: [khoingexe](https://github.com/khoingexe)
- Email: khoing.exe@proton.me

## Giấy phép

Dự án được phân phối theo giấy phép [MIT](LICENSE).