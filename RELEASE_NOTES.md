# Ghi chú phiên bản và bàn giao

## Bản nộp Lab 5 — v1.0

- **Mã phiên bản:** `v1.0` (nhãn bàn giao cho bản nộp, không phải Git tag).
- **Ngày cập nhật:** 30/10/2026.
- **Tác giả:** Bùi Đức Duy (`CutChoDenXi`).
- **Commit bản mã được nộp:** [`0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/commit/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26) — `Add files via upload`, 30/10/2026 13:16 UTC (20:16 giờ Việt Nam).
- **Mã nguồn xuất bản:** [GitHub Pages](https://cutchodenxi.github.io/K20_Portfolio_CNTT20_04/).

### Thay đổi chính

Commit bản nộp thêm portfolio Lab 5 viết bằng HTML5/CSS3 thuần:

- `index.html`: phần giới thiệu, kỹ năng, dự án mẫu, lộ trình học và form liên hệ.
- `css/style.css`: bố cục responsive, focus bàn phím, trạng thái hover/active và kiểu trình bày form.
- `ket-qua.html`: trang kết quả mô phỏng khi form được gửi.
- `kiem-tra-lab5.txt`: mẫu ghi kết quả kiểm thử.

### Lỗi đã sửa

Lịch sử repository không có commit nào mô tả một lỗi cụ thể đã được sửa; commit bản nộp chỉ có thông điệp `Add files via upload`. Vì vậy không ghi nhận lỗi đã sửa để tránh suy diễn. Mẫu kiểm tra T01–T08 hiện chưa có kết quả thực tế.

### Bản mã chính xác để đối chiếu

Các liên kết dưới đây được ghim vào SHA bản nộp, không trỏ tới phiên bản thay đổi sau này:

- [`index.html` tại `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/index.html)
- [`css/style.css` tại `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/css/style.css)
- [`ket-qua.html` tại `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/ket-qua.html)
- [`kiem-tra-lab5.txt` tại `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/kiem-tra-lab5.txt)
- [Toàn bộ cây mã tại `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/tree/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26)

### Hạn chế còn lại

- Nội dung portfolio còn mang tính mẫu; trang tự giới thiệu tên “An” dù hồ sơ người nộp trong mẫu kiểm tra là Bùi Đức Duy.
- Form chỉ kiểm tra bằng ràng buộc HTML của trình duyệt, gửi GET tới trang mô phỏng; không gửi email, không có xử lý phía máy chủ và dữ liệu nhập có thể hiện trên URL.
- `kiem-tra-lab5.txt` chưa ghi kết quả kiểm thử, lỗi tái hiện, cách sửa hoặc minh chứng.
- Không có báo cáo kiểm thử tự động hay kiểm thử trình duyệt được đính kèm trong commit bản nộp.

### Tiếp tục kiểm tra và bàn giao

1. Tải/đối chiếu đúng bản tại [commit `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/commit/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26), hoặc checkout bằng:

   ```sh
   git checkout 0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26
   ```

2. Chạy local từ thư mục dự án bằng `py -m http.server 8000` (hoặc `python -m http.server 8000`), rồi mở [http://localhost:8000](http://localhost:8000).
3. Kiểm tra liên kết điều hướng, bố cục ở màn hình hẹp/rộng, thao tác bằng `Tab`, trạng thái focus/hover, và các trường hợp form thiếu dữ liệu, email sai, độ dài họ tên/nội dung không đạt, cùng trường hợp hợp lệ.
4. Xác nhận trang kết quả chỉ mô phỏng; dùng dữ liệu giả vì form GET đưa dữ liệu lên URL.
5. Ghi **kết quả thực tế**, bước tái hiện, trình duyệt/kích thước màn hình, ảnh chụp hoặc URL minh chứng vào [`kiem-tra-lab5.txt`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/kiem-tra-lab5.txt). Nếu cập nhật sản phẩm sau khi bàn giao, tạo commit mới và ghi SHA mới ở đây; không thay thế SHA bản nộp để đối chiếu.