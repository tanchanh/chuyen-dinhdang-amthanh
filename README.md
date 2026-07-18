# 🎧 Bộ Chuyển Đổi Âm Thanh Đa Định Dạng

Đây là ứng dụng web hiện đại, gọn nhẹ và tiện lợi, giúp bạn dễ dàng chuyển đổi hàng loạt tệp tin âm thanh và video thuộc nhiều định dạng khác nhau sang các định dạng đầu ra phổ biến như **Opus** (.opus), **MP3** (.mp3), hoặc **WAV** (.wav) chất lượng cao ngay trên trình duyệt của bạn.

Ứng dụng hoạt động trực tiếp trên thiết bị của bạn, bảo mật tuyệt đối vì không cần gửi tệp tin lên bất kỳ máy chủ nào trên mạng.

---

## 💡 Các Tính Năng Tiện Dụng

* **Hỗ trợ đa định dạng đầu ra linh hoạt**:
  * **Opus (.opus)**: Công nghệ nén hiện đại nhất, tiết kiệm tối đa không gian lưu trữ mà âm thanh nghe vẫn sắc nét, rõ ràng.
  * **MP3 (.mp3)**: Định dạng âm thanh phổ biến nhất thế giới, tương thích cực tốt với mọi thiết bị di động, loa nghe nhạc và máy nghe nhạc cổ điển.
  * **WAV (.wav)**: Định dạng âm thanh thô không nén, lưu giữ trọn vẹn từng chi tiết âm thanh ở dạng gốc.
* **Cài đặt chất lượng mặc định tối ưu**:
  * **Mặc định định dạng**: Hệ thống ưu tiên chọn định dạng **Opus** chất lượng cao khi khởi động.
  * **Tốc độ truyền (Bitrate) tối ưu**: Đã cấu hình mặc định sẵn **320 kbps** cho định dạng MP3 và **192 kbps** cho định dạng Opus để mang lại trải nghiệm âm nhạc hoàn hảo nhất.
  * **Tần số lấy mẫu và số kênh**: Mặc định **giữ nguyên gốc** của tệp tin đầu vào để tránh suy giảm chất lượng do việc chuyển đổi không mong muốn.
* **Chuyển đổi hàng loạt nhanh chóng**:
  * Hỗ trợ kéo thả trực tiếp cùng lúc nhiều tệp âm thanh hoặc video vào ứng dụng hoặc click chọn từ thiết bị của bạn.
  * Hàng đợi trực quan hiển thị rõ tên tệp, kích thước tệp gốc, thanh tiến trình chạy phần trăm thời gian thực và dung lượng sau khi nén để bạn tiện theo dõi.
* **Lưu trữ thành phẩm tiện lợi**:
  * **Tải riêng lẻ**: Khi một tệp đã được chuyển đổi xong, nút chức năng sẽ tự động chuyển sang nút **Tải về** màu xanh lá giúp bạn nhanh chóng lưu riêng tệp đó.
  * **Tải tất cả cùng lúc (ZIP)**: Chỉ với một nút bấm duy nhất, toàn bộ các tệp âm thanh đã được xử lý xong sẽ được gom lại thành một tệp nén duy nhất giúp tải về máy siêu tốc.
* **Nghe thử trực tiếp & Biểu đồ sóng âm trực quan**:
  * Tích hợp sẵn trình phát nhạc nhỏ gọn để bạn bấm nghe thử ngay tập tin đã chuyển đổi để kiểm tra chất lượng âm thanh trước khi lưu.
  * Biểu đồ hiển thị dạng sóng âm thanh giúp bạn dễ theo dõi và click chuột trực tiếp lên dải sóng để tua nhanh.
* **Hoạt động hoàn toàn không cần Internet (Offline)**:
  * Ứng dụng được tích hợp sẵn cơ chế dự phòng thông minh (offline fallback) cho tất cả các thư viện xử lý âm thanh như **Opus**, **MP3 (lamejs)** và **ZIP (JSZip)**. Toàn bộ các tệp thư viện gốc đã được lưu sẵn trong thư mục `js/` giúp chương trình chạy mượt mà ngay cả khi không có mạng.

---

## 🛠️ Hướng Dẫn Sử Dụng Nhanh

1. **Mở ứng dụng**: Truy cập trực tiếp vào trang web của chương trình bằng bất kỳ trình duyệt nào (Chrome, Firefox, Edge, Safari...).
2. **Chọn định dạng & cấu hình**:
   * Chọn định dạng xuất ra bạn mong muốn (**Opus**, **MP3** hoặc **WAV**).
   * Thay đổi các thông số về tốc độ truyền (Bitrate), số kênh, tần số lấy mẫu (nếu bạn có yêu cầu đặc biệt; khuyến nghị giữ nguyên cấu hình mặc định tối ưu).
3. **Kéo thả tệp tin**: Kéo các tệp âm thanh hoặc video cần chuyển đổi thả vào vùng nét đứt **Kéo thả tệp âm thanh hoặc video vào đây**, hoặc nhấp chuột vào khung đó để duyệt tìm tệp từ thiết bị của bạn.
4. **Bắt đầu thực hiện**: Nhấn nút **Bắt đầu chuyển đổi** để ứng dụng bắt đầu tiến hành xử lý hàng loạt tệp tin của bạn.
5. **Nghe thử và Tải về**:
   * Bạn có thể bấm nút **Phát** để nghe thử trực tiếp trên thanh sóng âm nhạc ở bên dưới, hoặc bấm biểu tượng **Tải xuống** (màu xanh lá) để lưu tệp đó về máy.
   * Để tải về toàn bộ danh sách tệp tin đã xong: Nhấn nút **Tải tệp ZIP tổng hợp** để nhận về đầy đủ tất cả các bài nhạc chỉ trong một lần tải.

---

## 👥 Thông Tin Tác Giả

* **Tác giả:** Dương Tấn Chánh
