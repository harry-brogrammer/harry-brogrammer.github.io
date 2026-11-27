# Taolao Lab

Trang chủ của Taolao Lab, AI lab tại Việt Nam chuyên những vấn đề chưa ai dám làm.

**Website:** https://taolaolab.com

## Hướng nghiên cứu

- Phương ngữ tiếng Việt
- AI chạy trên thiết bị
- Phần mềm do AI agent phát triển
- Công bố mở

## Sản phẩm

| Sản phẩm | Đường dẫn | Mã nguồn |
|---|---|---|
| Giọng Quê HR | https://taolaolab.com/giong-que-hr/ | [harry-brogrammer/giong-que-hr](https://github.com/harry-brogrammer/giong-que-hr) |
| Chợ Việt | https://taolaolab.com/cho-viet/ | [harry-brogrammer/cho-viet](https://github.com/harry-brogrammer/cho-viet) |

## Cấu trúc

| Thành phần | Ghi chú |
|---|---|
| Hosting | GitHub Pages. Repo này là site của org; mọi repo Pages khác trong org chạy tại `taolaolab.com/<tên-repo>/` |
| Tên miền | `taolaolab.com` (tệp `CNAME`), DNS trên Cloudflare |
| Trang | `index.html` một tệp, ảnh sản phẩm trong `assets/`, ảnh xem trước `og-3.png` |

## Thêm sản phẩm mới

1. Tạo repo trong org `harry-brogrammer`, bật GitHub Pages từ nhánh `main`.
2. Dùng đường dẫn tương đối trong trang. Sản phẩm sẽ chạy tại `https://taolaolab.com/<tên-repo>/`.
3. Thêm một khối sản phẩm vào mục "Sản phẩm" trong `index.html`.

## Giấy phép

MIT.
