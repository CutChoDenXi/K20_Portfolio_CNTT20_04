# AI_LOG — Nhật ký sử dụng AI

## Phạm vi ghi nhận

Nhật ký này ghi lại việc dùng AI để hỗ trợ soạn tài liệu cho portfolio. AI không sửa mã HTML/CSS của sản phẩm. Không có kiểm thử trình duyệt hay chức năng nào được thực hiện trong quá trình ghi nhật ký này.

## Lần hỗ trợ tài liệu — 30/10/2026

### Hiện tượng và dữ kiện ban đầu

- Repository có portfolio tĩnh Lab 5 gồm `index.html`, `ket-qua.html`, `css/style.css` và mẫu kiểm thử `kiem-tra-lab5.txt`.
- Trang giới thiệu đang hiển thị tên mẫu “An”; hồ sơ trong mẫu kiểm thử ghi Bùi Đức Duy, mã sinh viên 2071020057, lớp CNTT 20-04.
- Form trong `index.html` dùng GET tới `ket-qua.html`; trang kết quả nêu rõ không gửi email và không lưu dữ liệu.
- Mẫu kiểm thử chưa có kết quả thực tế hoặc minh chứng.
- README ban đầu chỉ có tiêu đề và mô tả ngắn.

### Nhận định trước khi dùng AI

Không có nhận định trước AI nào được ghi lại trong tài liệu dự án hoặc yêu cầu ban đầu. Vì vậy không suy đoán hay ghi nhận định này như lời của tác giả.

### Công cụ và yêu cầu mẫu

- **Công cụ:** trợ lý AI trong Copilot SDK tại VS Code.
- **Yêu cầu ban đầu (tóm tắt):** cập nhật README với tên sản phẩm/tác giả, mô tả, repository và Pages, cấu trúc, chạy local, nguồn xuất bản, cách kiểm tra, hồ sơ và minh chứng; hướng dẫn phải theo sản phẩm thực tế.
- **Yêu cầu tiếp theo (tóm tắt):** tạo ghi chú phiên bản, ngày cập nhật, thay đổi, lỗi đã sửa, commit, hạn chế và hướng dẫn bàn giao.
- **Yêu cầu hiện tại (tóm tắt):** ghi nhật ký theo chuỗi dữ kiện → nhận định → AI → gợi ý → quyết định → phần sửa → thử lại, không bịa kết quả kiểm chứng.

Không chép lại toàn bộ cuộc trò chuyện. Các yêu cầu trên được tóm tắt, không phải phản hồi nguyên văn của công cụ.

### Gợi ý của AI

- Bổ sung README dựa trên nội dung HTML/CSS thật; nêu rõ form chỉ mô phỏng, dùng GET và dữ liệu có thể xuất hiện trên URL.
- Ghim liên kết mã nguồn minh chứng vào commit bản nộp `0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26`.
- Ghi rõ mẫu kiểm thử chưa điền, không khẳng định đã chạy kiểm thử.
- Tạo ghi chú phiên bản với hạn chế và các bước bàn giao.

### Quyết định và lý do

Các đề xuất về mô tả hiện trạng và giới hạn được dùng vì phù hợp với mã nguồn đã đọc. Ghi rõ phần chưa kiểm thử để tránh trình bày dự định như kết quả. Dùng liên kết ghim SHA để người nhận có thể đối chiếu đúng bản nộp. Không áp dụng thay đổi cho mã sản phẩm.

### Phần được sửa

- `README.md`: bổ sung hướng dẫn dự án và liên kết minh chứng.
- `RELEASE_NOTES.md`: ghi thông tin phiên bản, commit, hạn chế và bàn giao.
- `AI_LOG.md`: tài liệu này.

### Cách thử lại và kết quả

- **Đã đối chiếu tài liệu:** đọc lại README, ghi chú phiên bản và các tệp sản phẩm để xác nhận nội dung mô tả các trang/form đúng với mã nguồn; commit và SHA được tra từ lịch sử GitHub.
- **Chưa thực hiện:** chưa chạy website local, chưa kiểm tra trên trình duyệt, chưa thử responsive/bàn phím/form, và chưa điền kết quả vào `kiem-tra-lab5.txt`.
- **Kết quả:** việc rà soát trên chỉ xác nhận tính nhất quán của tài liệu với mã nguồn đã đọc; không phải kết quả kiểm thử chức năng. Cần thực hiện các bước trong README và ghi lại bằng chứng thực tế trước khi tuyên bố các kiểm thử đạt.

## Nếu không dùng AI

Không áp dụng cho lần ghi nhận này: AI đã được dùng để hỗ trợ soạn README và ghi chú phiên bản. AI không được dùng để tạo kết quả kiểm thử.