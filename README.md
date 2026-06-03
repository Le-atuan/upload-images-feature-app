# capture_upload_photo_app

A Flutter project for feature.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## **Tính năng: Chụp & Upload Ảnh**

Mô tả ngắn: luồng cho phép người dùng chụp/ chọn ảnh, xem trước, gộp thành PDF và upload lên server.

## **Thư viện chính đang dùng**

    - `image_picker` — chọn/ chụp ảnh (pickImage / pickMultiImage).
    - `flutter_doc_scanner` — scan tài liệu, trả về PDF (plugin native).
    - `pdf` — gộp ảnh thành file PDF (sử dụng `compute` để chạy ở isolate).
    - `path_provider` — lấy thư mục lưu file trên thiết bị.
    - `dio` — upload `multipart/form-data` (FormData / MultipartFile).
    - `permission_handler` — kiểm tra/ yêu cầu quyền camera / photos.


