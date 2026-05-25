# Phân tích: Vì sao dùng Parameterized {} tối ưu hơn dấu +

- Dùng dấu + sẽ tạo chuỗi mới ngay cả khi log ở mức đó không được bật → lãng phí CPU và bộ nhớ.
- Parameterized {} chỉ thực sự thay thế biến khi log level được bật → hiệu năng tốt hơn.
- Viết gọn gàng, dễ đọc, tránh lỗi copy-paste và sai nguồn log.
