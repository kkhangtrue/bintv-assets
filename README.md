# BinTV Assets

Kho logo kênh tùy chỉnh để thử nghiệm tính năng **Logo Override** cho ứng dụng BinTV.

## TV360+2 đến TV360+12

- Gồm **11 PNG** 512 × 288 px với nền trong suốt (RGBA), đồng nhất kích thước và bố cục.
- Các ảnh là **bản dựng lại phục vụ thử nghiệm**, **không phải** file logo chính thức do TV360 cung cấp. Cần kiểm tra hình thức trước khi đưa vào ứng dụng.
- Ảnh đặt tại `logos/tv360plus2.png` đến `logos/tv360plus12.png`.
- `logo-overrides.json` ánh xạ `tvg-id` của các kênh trong playlist `vmttv` sang URL ảnh trên GitHub Raw. Đây là **cấu hình mẫu**; BinTV chỉ sử dụng khi tính năng Logo Override được tích hợp.
- **Không chỉnh sửa playlist M3U nguồn**; TV360 và nhà cung cấp vẫn chịu trách nhiệm về URL video, EPG và cập nhật danh sách.

## Link nhúng

- Logo TV360+2: https://raw.githubusercontent.com/kkhangtrue/bintv-assets/main/logos/tv360plus2.png
- Danh sách ánh xạ: https://raw.githubusercontent.com/kkhangtrue/bintv-assets/main/logo-overrides.json

## Lưu ý

Github Raw có cache; khi thay logo nhưng giữ nguyên tên file, thay đổi có thể xuất hiện trễ. BinTV cần cache và tải ảnh ngoài luồng giao diện để tránh lag.
