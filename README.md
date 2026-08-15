# Tạo Game Xe Tăng Cyberpunk

Một dự án ví dụ bằng HTML/JS mô phỏng trò chơi điều khiển xe tăng mang phong cách Cyberpunk. Mục tiêu: cung cấp nguồn mã mẫu để thử nghiệm AI, logic game đơn giản và giao diện UI retro-futuristic.

**Tính năng**
- Màn hình khởi động và giao diện điều khiển bằng bàn phím.
- Vật lý va chạm và di chuyển xe tăng đơn giản.
- Hiệu ứng âm thanh/ánh sáng theo phong cách Cyberpunk.
- Tập hợp tài nguyên và mã nguồn thuận tiện để mở rộng bởi Module-AI.

**Yêu cầu**
- Trình duyệt hiện đại (Chrome, Edge, Firefox) hỗ trợ ES6.
- Không cần server cho bản demo tĩnh — mở file `sources_game.html` trực tiếp hoặc phục vụ bằng static server nếu cần.

**Chạy thử nhanh**
1. Mở file `sources_game.html` trong trình duyệt.
2. Sử dụng phím mũi tên hoặc `W/A/S/D` để điều khiển xe tăng.
3. Xem console trình duyệt để biết log và debug.

Nếu muốn chạy qua một static server (ví dụ Python):
```bash
# Từ thư mục chứa file
python -m http.server 8000
# Mở http://localhost:8000/sources_game.html
```

**Thành phần chính**
- `sources_game.html` — trang demo chính.
- `assets/` — hình ảnh, âm thanh và tài nguyên (nếu có).
- `js/` — mã JavaScript điều khiển logic trò chơi.

**Góp ý & Phát triển**
- Bạn có thể thêm AI điều khiển kẻ địch, hệ thống điểm số, hoặc tích hợp với Module-AI để tạo kịch bản động.

**Giấy phép**
- Sử dụng cho mục đích học tập và thử nghiệm. Xin tôn trọng tác giả khi tái sử dụng mã.
