# Ari-autoref
Ari-autoref
# Bot giới thiệu tự động ví chuỗi Ari

Bot này tự động hóa quá trình tạo tài khoản và sử dụng mã giới thiệu cho Ví AriChain.

## Đặc trưng

- Tự động tạo địa chỉ email ngẫu nhiên.
- Sử dụng proxy để tránh lệnh cấm IP.
- Ghi nhật ký các tài khoản đã tạo.
- Xử lý xác minh email.

## Yêu cầu

- Node.js 18 v18.20.5 LTS hoặc mới nhất.
- npm (Trình quản lý gói nút)
- Sử dụng Dịch vụ 2Captcha [2Captcha](https://2captcha.com/?from=24541144), phiên bản miễn phí mà bạn có thể sử dụng gemini apikey.

## Cài đặt

1. Sao chép kho lưu trữ:

   ```sh
   clone git https://github.com/anht3k52/Ari-autoref.git
   cd Ari-autoref
   ```

2. Cài đặt các phần phụ thuộc:

   ```sh
   npm install
   ```

3. Tạo tệp `proxy.txt` trong thư mục gốc và thêm proxy của bạn (mỗi dòng một proxy).

4. thay đổi `client_secret.json.example` thành `client_secret.json`.

## Đầu ra

- Các tài khoản đã tạo sẽ được lưu trong `accounts.txt`.

## Ghi chú

- Nếu gặp lỗi `creds không hợp lệ` bạn có thể xóa token trong `src/json/token.json`
- Đảm bảo sử dụng proxy hợp lệ để tránh bị cấm IP.
- Bot sẽ cố gắng xác minh email tối đa 5 lần trước khi bỏ cuộc.

## Luôn kết nối

- Kênh Telegram : [Telegram](https://t.me/anht3k52)

