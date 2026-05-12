# Known Issues · Buổi 1

Ghi lại lỗi chưa xử lý được hoặc đã xử lý xong.

| STT | Lỗi gặp phải | Lệnh gây lỗi | Cách đã thử | Trạng thái |
|---:|---|---|---|---|
| 1 | Quên bật Docker Desktop nên không kết nối được Docker daemon| docker compose up| Kiểm tra Docker Desktop, khởi động lại Docker và chạy lại lệnh| Đã xử lý xong|
| 1 | Không tải được image ultralytics/ultralytics:latest-cpu do dung lượng quá lớn, tải lâu hoặc bị lỗi| ddocker pull ultralytics/ultralytics:latest-cpu| Kiểm tra mạng, thử tải lại nhiều lần, cân nhắc dùng image nhẹ hơn hoặc build môi trường riêng| Chưa xử lý hoàn toàn|
