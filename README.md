# E-commerce UI Improvement – Product Cards

## 1. Giới thiệu
Giao diện minh họa cải tiến **thẻ sản phẩm** sau khi khảo sát website thương mại điện tử Hasaki. Bản demo dùng nội dung và hình ảnh minh họa tự tạo, không sao chép mã nguồn của Hasaki.

## 2. Website tham khảo
- Tên: Hasaki
- URL: https://hasaki.vn/
- Khu vực khảo sát: Trang chủ, danh mục, chi tiết sản phẩm, tìm kiếm và giỏ hàng
- Khu vực cải tiến: Thẻ sản phẩm trong danh mục Sữa Rửa Mặt

## 3. Chức năng
- Hiển thị 4 sản phẩm minh họa gồm hình ảnh, tên, dung tích, giá và nút “Xem nhanh sản phẩm”
- Phân cấp giá ưu đãi, giá gốc và thông tin khuyến mãi
- Bố cục responsive trên màn hình máy tính và điện thoại
- Nút **“Xem nhanh sản phẩm”** sử dụng HTML `<details>/<summary>` để mở/đóng mô tả ngay trên trang, **không dùng JavaScript**. Không có giỏ hàng, thanh toán hoặc đặt hàng

## 4. Công nghệ
- HTML5
- CSS3 (file `css/style.css`)
- 4 ảnh minh họa SVG được tạo mới trong thư mục `images/`

## 5. Cách chạy
Mở file `index.html` trong Chrome, hoặc sử dụng VS Code với tiện ích Live Server.

## 6. Cải tiến đã thực hiện
- Tách khối hình ảnh, tên sản phẩm, thông tin dung tích và giá
- Nhấn mạnh giá đang bán bằng cỡ chữ và màu sắc
- Đưa ưu đãi vào khu vực phụ riêng
- Dùng CSS Grid và media queries để thích ứng kích thước màn hình
- **Sinh viên bổ sung ở đây thay đổi CSS thực tế tự làm sau khi kiểm tra.**

## 7. Hỗ trợ từ AI
AI hỗ trợ đề xuất bố cục, viết mã mẫu và giải thích HTML/CSS. Sinh viên cần chạy thử, kiểm tra, sửa lỗi và ghi lại các thay đổi tự thực hiện trong `AI_USAGE.md` trước khi nộp.

## 8. Lưu ý khi nộp báo cáo Word
- Chụp ảnh website gốc, mã nguồn VS Code, màn hình Desktop và Mobile (F12 / Ctrl+Shift+M).
- Tự phát hiện và sửa ít nhất một chi tiết CSS; ghi rõ vị trí mã, trước/sau và lý do.
- Không gọi những kiểm thử chưa thực hiện là “đã kiểm thử”.
- Bốn nhãn hàng/sản phẩm/giá và hình SVG là **dữ liệu giả định dành cho bài học**, không đại diện sản phẩm trên Hasaki.
