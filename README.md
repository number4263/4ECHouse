# 4ECHouse v1.0

Ứng dụng mẫu thiết kế nhà/nội thất bằng tiếng Việt, responsive cho iPhone, iPad và máy tính.

## Chạy
```bash
npm install
npm run dev
```
Sau đó mở địa chỉ Vite hiển thị trong terminal.

## Build
```bash
npm run build
npm run preview
```

## Có sẵn trong bản v1.0
- Trang chủ và quy trình khảo sát → vẽ → nội thất → xuất hồ sơ
- Đơn vị của tôi: vẽ mặt bằng, tải mặt bằng, LiDAR (giao diện), mẫu, nhận, khôi phục, chuyển giao
- Trình vẽ mặt bằng SVG cảm ứng: tường, phòng, cửa, cửa sổ, chọn đối tượng, thuộc tính, thống kê
- Xem 3D dạng mô phỏng dùng cùng dữ liệu mặt bằng
- Nội thất: danh mục đồ, vật liệu, thiết bị
- Toolbox: chụp nhanh, panorama 720°, quản lý vật liệu
- Thị trường nhà
- 31 bài hướng dẫn tiếng Việt
- Lưu dự án cục bộ bằng localStorage
- Giao diện responsive cho desktop/tablet/mobile

## Ghi chú kỹ thuật
Đây là bản nền tảng chạy được (functional prototype/MVP), không phải bản sao mã nguồn hay tài sản độc quyền của ZHouse/JoyPlan. Các tích hợp native như LiDAR thực, Bluetooth laser, CAD/DXF/OBJ, renderer 3D thật, tài khoản cloud và đồng bộ nhiều thiết bị cần backend/native modules ở các giai đoạn tiếp theo.
