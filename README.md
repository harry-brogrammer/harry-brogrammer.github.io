# Taolao Lab

Trang chủ của Taolao Lab, phòng nghiên cứu sản phẩm AI cho những vấn đề chưa ai đặt ra.

**Môi trường production:** https://taolaolab.com

## Danh mục sản phẩm

| Sản phẩm | Đường dẫn | Mã nguồn | Ghi chú |
|---|---|---|---|
| Giọng Quê HR | https://taolaolab.com/giong-que-hr/ | [harry-brogrammer/giong-que-hr](https://github.com/harry-brogrammer/giong-que-hr) | Hỗ trợ 1/3 miền |
| Chợ Việt | https://taolaolab.com/cho-viet/ | [harry-brogrammer/cho-viet](https://github.com/harry-brogrammer/cho-viet) | Tối đa 3 người dùng đồng thời |

## Kiến trúc hệ thống

| Thành phần | Công nghệ | Ghi chú |
|---|---|---|
| Hosting | GitHub Pages | Repo này là site của org. Mọi repo Pages khác trong org tự chạy tại `taolaolab.com/<tên-repo>/` |
| Tên miền | `taolaolab.com` | Tệp `CNAME` |
| Backend | Không có | |
| Build | Không có | Một tệp HTML |

## Thêm sản phẩm mới

1. Tạo repo trong org `harry-brogrammer`, bật GitHub Pages từ nhánh `main`.
2. Dùng đường dẫn tương đối trong trang. Sản phẩm sẽ chạy tại `https://taolaolab.com/<tên-repo>/`.
3. Thêm một thẻ vào mục "Danh mục sản phẩm" trong `index.html`.

Không cần cấu hình tên miền cho từng repo.

## Giấy phép

MIT.
