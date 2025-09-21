# Asymmetric Message Encryptor

Công cụ mã hóa tin nhắn sử dụng RSA-2048 để bảo mật thông tin liên lạc.

🔗 [Dùng trực tuyến tại EZSE.net](https://ezse.net/Asymmetric-Message-Encryptor/)

## Tính năng

- Mã hóa tin nhắn với RSA-OAEP 2048-bit
- Hoạt động hoàn toàn ở phía client (trình duyệt)
- Không lưu trữ hay gửi dữ liệu lên server
- Giao diện đơn giản, dễ sử dụng

## Hướng dẫn sử dụng

### 1. Người nhận tạo khóa
- Mở ["Trang Người Nhận"](https://ezse.net/Asymmetric-Message-Encryptor/receiver.html)
- Copy Public Key và gửi cho người gửi
- **Lưu ý:** Giữ bí mật Private Key, không chia sẻ cho bất kỳ ai

### 2. Người gửi mã hóa tin nhắn
- Mở ["Trang Người Gửi"](https://ezse.net/Asymmetric-Message-Encryptor/sender.html)
- Dán Public Key nhận được từ người nhận
- Nhập tin nhắn cần gửi
- Bấm "Mã hóa" và copy kết quả gửi cho người nhận

### 3. Người nhận đọc tin nhắn
- Dán bản mã nhận được
- Bấm "Giải mã"
- Đọc tin nhắn ở phần kết quả

## Đặc điểm bảo mật

### Mã hóa mạnh mẽ
- Sử dụng RSA-OAEP với khóa 2048-bit
- Hàm băm SHA-256 cho padding
- Mã hóa bất đối xứng an toàn

### Bảo vệ dữ liệu
- Mã hóa hoàn toàn ở trình duyệt
- Không gửi dữ liệu lên server
- Không lưu khóa riêng tư online
- Mã nguồn mở trên GitHub

## Yêu cầu hệ thống
- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Kết nối internet (chỉ để tải trang web)
