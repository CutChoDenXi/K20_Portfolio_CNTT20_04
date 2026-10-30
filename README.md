# K20 Portfolio CNTT 20-04

## Thông tin sản phẩm

- **Tên sản phẩm:** Portfolio cá nhân – Lab 5 (HTML5 và CSS3).
- **Tác giả:** Bùi Đức Duy, mã sinh viên 2071020057, lớp CNTT 20-04 (theo mẫu thông tin trong `kiem-tra-lab5.txt`).
- **Mô tả:** Portfolio tĩnh giới thiệu kỹ năng, dự án mẫu, lộ trình học tập và form liên hệ. Dự án dùng HTML/CSS thuần, có bố cục responsive, trạng thái focus bàn phím và kiểm tra dữ liệu bằng ràng buộc HTML. Phần giới thiệu trên trang vẫn ghi tên mẫu “An”.

## Liên kết

- **Repository:** [CutChoDenXi/K20_Portfolio_CNTT20_04](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04)
- **Trang GitHub Pages:** [https://cutchodenxi.github.io/K20_Portfolio_CNTT20_04/](https://cutchodenxi.github.io/K20_Portfolio_CNTT20_04/)
- **Hồ sơ tác giả:** [github.com/CutChoDenXi](https://github.com/CutChoDenXi)
- **Bản mã nộp để đối chiếu:** [commit `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/commit/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26) — đây là SHA của bản mã đã nộp; các liên kết minh chứng bên dưới được ghim vào commit này.

## Cấu trúc thư mục

```text
K20_Portfolio_CNTT20_04/
├── index.html          # Portfolio: giới thiệu, kỹ năng, dự án, lộ trình, form
├── ket-qua.html        # Trang kết quả mô phỏng của form
├── kiem-tra-lab5.txt   # Mẫu ghi kết quả kiểm thử (chưa điền kết quả)
├── README.md           # Hướng dẫn dự án
├── RELEASE_NOTES.md    # Ghi chú phiên bản và bàn giao
├── AI_LOG.md           # Nhật ký sử dụng AI và tình trạng kiểm chứng
└── css/
    └── style.css       # Giao diện, responsive và trạng thái tương tác
```

## Chạy local

Dự án không cần cài thư viện hay build. Mở PowerShell tại thư mục dự án và chạy:

```powershell
py -m http.server 8000
```

Nếu máy không có lệnh `py`, chạy `python -m http.server 8000`. Mở [http://localhost:8000](http://localhost:8000) trên trình duyệt. Dừng máy chủ bằng `Ctrl+C`.

## Nguồn xuất bản

Trang được xuất bản bằng **GitHub Pages** từ repository ở trên. Mã nộp ban đầu có các tệp HTML ở thư mục gốc và stylesheet trong `css/`. Để xác định chính xác mã nguồn đã nộp, dùng SHA cố định `0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26`; URL Pages là bản đang được xuất bản và có thể thay đổi khi nhánh triển khai được cập nhật.

## Cách kiểm tra trang và chức năng chính

1. **Trang portfolio:** Mở `index.html` hoặc URL Pages. Chọn Giới thiệu, Kỹ năng, Dự án, Lộ trình và Liên hệ; mỗi mục điều hướng tới phần tương ứng trên cùng trang.
2. **Responsive:** Thử cửa sổ hẹp, vừa và rộng. Các thẻ dự án được xếp lần lượt thành 1, 2 và 3 cột theo các breakpoint trong `css/style.css`.
3. **Bàn phím và tương tác:** Dùng `Tab`/`Shift+Tab` để đi qua liên kết, nút và trường nhập; xác nhận focus có viền dễ thấy. Thử hover menu, nút và thẻ dự án.
4. **Form liên hệ:** Thử gửi form để trống, email sai định dạng, họ tên ngắn hơn 2 ký tự, nội dung ngắn hơn 10 hoặc dài hơn 500 ký tự; trình duyệt cần chặn gửi. Thử dữ liệu hợp lệ để tới trang kết quả.
5. **Trang kết quả:** `ket-qua.html` thông báo form không gửi email và không lưu dữ liệu. Form dùng GET nên dữ liệu thử xuất hiện trên URL; chỉ nhập dữ liệu giả, không nhập thông tin cá nhân thật.

## Hồ sơ và minh chứng

- [Hồ sơ GitHub tác giả](https://github.com/CutChoDenXi)
- [Trang portfolio đang xuất bản](https://cutchodenxi.github.io/K20_Portfolio_CNTT20_04/)
- [Toàn bộ mã nguồn tại commit bản nộp `0ad4ea2`](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/tree/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26)
- [Trang portfolio `index.html` tại commit bản nộp](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/index.html)
- [CSS responsive và tương tác tại commit bản nộp](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/css/style.css)
- [Trang kết quả mô phỏng tại commit bản nộp](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/ket-qua.html)
- [Mẫu kiểm tra Lab 5 tại commit bản nộp](https://github.com/CutChoDenXi/K20_Portfolio_CNTT20_04/blob/0ad4ea286eb9ffa984b6b62e56ed8fdab9542c26/kiem-tra-lab5.txt) — mẫu này chưa có kết quả thực tế hoặc ảnh minh chứng; cần điền sau khi chạy kiểm tra.
- [Nhật ký sử dụng AI (`AI_LOG.md`)](AI_LOG.md) — ghi phạm vi AI hỗ trợ và nêu rõ các kiểm thử chưa thực hiện.
