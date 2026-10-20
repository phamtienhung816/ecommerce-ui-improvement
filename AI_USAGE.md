# AI Usage Log

## 1. Công cụ AI

- **Công cụ:** ChatGPT (OpenAI).
- **Website tham khảo:** Hasaki – https://hasaki.vn/.
- **Phạm vi bài tập:** Khảo sát giao diện thương mại điện tử và cải tiến thẻ sản phẩm thuộc danh mục Sữa Rửa Mặt bằng HTML5/CSS3.

## 2. Mục đích sử dụng

Tôi sử dụng ChatGPT để hỗ trợ phân tích năm khu vực của website Hasaki từ ảnh chụp màn hình; nhận diện vấn đề UX ở thẻ sản phẩm; đề xuất bố cục cải tiến; hỗ trợ xây dựng trang HTML5/CSS3 mẫu; và giải thích cách tổ chức, chạy thử, kiểm tra mã nguồn. Kết quả AI chỉ mang tính hỗ trợ, cần được đối chiếu với website và kiểm tra thực tế.

## 3. Prompt đã sử dụng

### Prompt 1 – Phân tích giao diện website Hasaki

> Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng (UX) cho website thương mại điện tử.
>
> Tôi đang khảo sát website Hasaki (https://hasaki.vn/) và đã đính kèm 5 ảnh chụp màn hình thực tế.
>
> Hãy phân tích 5 khu vực: (1) Trang chủ, (2) Danh mục sản phẩm, (3) Chi tiết sản phẩm, (4) Tìm kiếm, (5) Giỏ hàng.
>
> Với mỗi khu vực, hãy trình bày: mục đích chức năng, thành phần giao diện, điểm thuận tiện với khách hàng, một vấn đề có thể phát sinh và một đề xuất cải tiến kèm lý do.
>
> Phân biệt rõ quan sát từ ảnh, suy luận và đề xuất của AI. Không khẳng định tính năng chưa được kiểm chứng. Nếu ảnh không đủ dữ liệu, hãy ghi rõ cần kiểm tra thêm.
>
> Trình bày thành bảng ngắn gọn, phù hợp đưa vào báo cáo Word của sinh viên ngành Thương mại điện tử.

### Prompt 2 – Đề xuất cải tiến thẻ sản phẩm

> Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3.
>
> Website tham khảo: Hasaki.vn. Khu vực lựa chọn cải tiến là thẻ sản phẩm thuộc danh mục Sữa Rửa Mặt.
>
> Vấn đề được nhận diện từ ảnh khảo sát: thẻ sản phẩm chứa nhiều thông tin về chương trình khuyến mãi, giá gốc, giá bán, quà tặng, thương hiệu và tên sản phẩm trong không gian tương đối hẹp, khiến việc đọc lướt và so sánh sản phẩm có thể khó khăn.
>
> Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam.
>
> Hãy đề xuất:
> 1. Bố cục giao diện cải tiến.
> 2. Các thành phần HTML5 cần sử dụng.
> 3. Cách tổ chức CSS3.
> 4. Cách hiển thị trên máy tính và điện thoại.
> 5. Những điểm cần kiểm tra về khả năng sử dụng.
>
> Chỉ giải thích phương án thiết kế, chưa tạo mã nguồn. Trình bày ngắn gọn, phù hợp với sinh viên học phần Phát triển ứng dụng WEB/TMĐT.

### Prompt 3 – Hỗ trợ xây dựng HTML5/CSS3

> Dựa trên phương án cải tiến thẻ sản phẩm Hasaki đã phân tích, hãy hỗ trợ xây dựng một trang HTML5 và CSS3 chạy độc lập.
>
> Yêu cầu:
> - Có tiêu đề trang và khu vực sản phẩm.
> - Hiển thị tối thiểu 4 sản phẩm sữa rửa mặt mẫu.
> - Mỗi sản phẩm có hình ảnh, tên, giá bán, giá gốc và nút thao tác.
> - Phân cấp rõ ràng giữa thông tin chính và nội dung ưu đãi phụ.
> - Bố cục phù hợp với máy tính và điện thoại bằng CSS Grid và media queries.
> - Tách HTML vào index.html và CSS vào css/style.css.
> - Không dùng backend, cơ sở dữ liệu, JavaScript hoặc thư viện không cần thiết.
> - Dùng dữ liệu và hình ảnh minh họa hợp pháp; không sao chép giao diện hoặc mã nguồn Hasaki nguyên bản.
>
> Hãy giải thích những thành phần mã quan trọng, cách chạy thử và các lỗi cần kiểm tra.

## 4. Kết quả AI đề xuất

- **Phân tích UX:** AI hỗ trợ đánh giá năm khu vực theo chức năng, thành phần giao diện, điểm thuận tiện, vấn đề tiềm năng và đề xuất cải tiến; phân biệt quan sát trên ảnh với suy luận và đề xuất.
- **Hướng cải tiến:** Chọn thẻ sản phẩm của danh mục Sữa Rửa Mặt; ưu tiên hình ảnh, thương hiệu, tên, dung tích và giá bán, đồng thời đưa ưu đãi thành thông tin phụ.
- **Cấu trúc HTML5:** Sử dụng `header`, `main`, `section`, `article`, `img`, `strong`, `del`, `details` và `summary` để thể hiện nội dung và mở/đóng thông tin sản phẩm không cần JavaScript.
- **Tổ chức CSS3:** Tách riêng `css/style.css`, dùng CSS Grid cho danh sách sản phẩm, Flexbox cho căn chỉnh và media queries cho bố cục thích ứng.
- **Sản phẩm mẫu:** Giao diện có bốn sản phẩm minh họa với hình ảnh SVG tự dựng, không sử dụng mã nguồn hay hình ảnh sao chép từ Hasaki. Giá và thương hiệu chỉ nhằm mục đích học tập, không phải dữ liệu bán hàng thật.

## 5. Kiểm tra và điều chỉnh

### 5.1. Những nội dung đã đối chiếu được từ mã nguồn mẫu

- `index.html` có **4** phần tử `article.product-card`, tương ứng bốn thẻ sản phẩm.
- Mỗi thẻ hiển thị ảnh, thương hiệu, tên, dung tích, giá bán, giá gốc và thông tin ưu đãi.
- Các ảnh được tham chiếu bằng đường dẫn tương đối `images/product-01.svg` đến `images/product-04.svg` và nằm trong gói mã nguồn.
- Trang liên kết đến tệp CSS riêng `css/style.css`.
- `.product-grid` có cấu hình **4 cột** mặc định; media query tại `max-width: 1040px` chuyển sang **2 cột** và tại `max-width: 560px` chuyển sang **1 cột**.
- Nút “Xem nhanh sản phẩm” được thiết kế bằng `details` và `summary`, không sử dụng JavaScript.

### 5.2. Kiểm tra trực tiếp trên trình duyệt

Phiên bản mẫu đã được AI hỗ trợ đánh giá ở các độ rộng màn hình 1440px (máy tính), 820px (máy tính bảng) và 390px (điện thoại). Tuy nhiên, **kết quả này không thay thế việc sinh viên tự mở `index.html` bằng Chrome, kiểm tra hình ảnh, bố cục, trạng thái mở/đóng và lưu ảnh chụp minh chứng**. Chỉ xác nhận “Đạt” trong báo cáo khi đã tự thực hiện các thao tác đó.

### 5.3. Phần tôi tự điều chỉnh

- File chỉnh sửa: `css/style.css`.
- Thành phần: `.product-grid`.
- Thuộc tính: `gap`.
- Trước khi sửa: `16px`.
- Sau khi sửa: `32px` trên Desktop.
- Lý do: Tăng khoảng cách giữa các thẻ sản phẩm,
  giúp bố cục thoáng và dễ phân biệt sản phẩm.
- Kết quả: Đã lưu CSS và tải lại trang trên Chrome
  để quan sát sự thay đổi.
- Kiến thức hiểu được: `gap` điều chỉnh khoảng cách
  giữa các phần tử trong CSS Grid.

### 5.4. Những đề xuất không triển khai

- Không xây dựng backend, cơ sở dữ liệu, tài khoản người dùng hoặc thanh toán do nằm ngoài phạm vi bài tập.
- Không sử dụng JavaScript hay thư viện giao diện vì HTML5/CSS3 đáp ứng mục tiêu thiết kế thẻ sản phẩm tĩnh.
- Không sao chép trực tiếp mã nguồn, banner hoặc ảnh sản phẩm từ website Hasaki.

## 6. Phần tôi hiểu và có thể giải thích

Sau khi tham khảo mã nguồn AI hỗ trợ, tôi đã tìm hiểu và nắm được một số thành phần cơ bản:

### 6.1. HTML – Tạo nội dung trang web
- `index.html`: File chính chứa nội dung trang web.
- `<main>`: Chứa nội dung chính của trang.
- `<section>`: Nhóm các nội dung liên quan.
- `<article>`: Đại diện cho một thẻ sản phẩm riêng biệt.
- `<img>`: Hiển thị hình ảnh sản phẩm.
- `<strong>`: Nhấn mạnh giá bán.
- `<del>`: Hiển thị giá gốc có gạch ngang.
- `<details>` và `<summary>`: Cho phép mở/đóng thông tin sản phẩm mà không cần JavaScript.

### 6.2. CSS – Trang trí giao diện
- `style.css`: Điều chỉnh màu sắc, kích thước và cách sắp xếp nội dung.
- `display: grid`: Chia danh sách sản phẩm thành các cột.
- `gap`: Điều chỉnh khoảng cách giữa các thẻ sản phẩm.
- `padding`: Tạo khoảng cách bên trong một thành phần.
- `border-radius`: Bo tròn các góc.

### 6.3. Hiển thị trên nhiều thiết bị
- `@media`: Giúp giao diện thay đổi theo kích thước màn hình.
- Máy tính hiển thị 4 sản phẩm một hàng, máy tính bảng 2 sản phẩm và điện thoại 1 sản phẩm theo các mốc kích thước đã thiết kế.

### 6.4. Những điều tôi có thể giải thích
- HTML tạo nội dung, còn CSS giúp giao diện đẹp và dễ nhìn hơn.
- Website có 4 thẻ sản phẩm mẫu với hình ảnh, tên, giá và nút xem nhanh.
- Khi mở `index.html`, trình duyệt đọc HTML và CSS để hiển thị trang web.
- Dự án chưa có backend hoặc chức năng thanh toán thực tế.

**Kết luận:** AI hỗ trợ tạo mã nguồn ban đầu và giải thích các thành phần. Tôi tập trung tìm hiểu cấu trúc HTML, cách sắp xếp sản phẩm bằng CSS và kiểm tra kết quả trên trình duyệt.
