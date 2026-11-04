
## 1. Bảng so sánh SMS OTP vs TOTP (Authenticator App)
| Tiêu chí | SMS OTP | TOTP (Google Authenticator) |
| :--- | :--- | :--- |
| **Chi phí** | Tốn kém phí Brandname (300đ-800đ/SMS), rủi ro SMS Toll Fraud | Miễn phí 100%, chuẩn mở RFC 6238 |
| **Bảo mật** | Thấp, dễ bị SIM Swapping, IMSI Catcher nghe lén sóng vô tuyến | Rất cao, khóa bí mật lưu mã hóa trong chip thiết bị, miễn nhiễm tráo SIM |
| **Tính khả dụng** | Phụ thuộc sóng di động, nghẽn mạng, tốn phí roaming | Hoạt động Offline 100%, tạo mã không cần mạng hay sóng |

## 2. Kết luận lựa chọn
Hệ thống Fintech bắt buộc chọn **TOTP Authenticator App** để triệt tiêu hoàn toàn nguy cơ tấn công SIM Swapping, đảm bảo tính sẵn sàng cao và tiết kiệm chi phí vận hành.
