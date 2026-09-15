# Đăng thông báo — chỉ sửa chữ

1. [Bấm vào đây để sửa thông báo trên GitHub](https://github.com/nguyenmanhvien/truyen-tu-dich-tu-nghe/edit/main/announcements.json). Đăng nhập nếu GitHub yêu cầu.
2. Thay chữ trong hai ô dưới đây. Giữ nguyên dấu ngoặc, dấu phẩy và tên ô.
3. Bấm **Commit changes…**, rồi **Commit changes** để lưu vào nhánh `main`.

```json
{
  "tieu_de": "Tiêu đề bạn muốn hiện",
  "noi_dung": "Viết thông báo của bạn ở đây."
}
```

Bạn có thể giữ nguyên tiêu đề và chỉ sửa nội dung. Không cần mã thông báo, ngày tháng, số phiên bản hay bật/tắt gì khác. Nội dung mới thay thông báo trước; app tự so sánh và chỉ tự hiện một lần cho mỗi nội dung khác nhau.

- Muốn gỡ thông báo: để `"noi_dung": ""`.
- Muốn xuống dòng trong nội dung: gõ `\n`, ví dụ `"Dòng một.\nDòng hai."`.
- Dùng dấu nháy cong “như thế này” khi trích dẫn trong nội dung; không thêm dấu nháy thẳng `"` vào giữa câu.
- Không đổi tên tệp `announcements.json` hoặc hai ô `tieu_de`, `noi_dung`.

## Khi nào điện thoại nhận được?

APK từ bản NoAds v16 tự đọc trực tiếp tệp đã lưu trên GitHub khi mở app, mở lại sau khi ra ngoài, bấm chuông và quét nền khoảng 5 giờ/lần khi có mạng. Android có thể trì hoãn quét nền khi tiết kiệm pin hoặc mất mạng. Sau khi bấm Buộc dừng, cần mở app lại.

Quét nền cập nhật danh sách và số ở chuông; không tự bật popup giữa lúc dùng app. Popup chỉ được xét khi mở app ở màn hình Trình duyệt, và không hiện khi đang nghe truyện hoặc đã chuyển sang Thư viện/Nghe truyện. Bấm chuông để đọc lại bất cứ lúc nào.

Nếu GitHub hoặc mạng đang lỗi, app giữ bản thông báo đã tải thành công trước đó. Nếu vừa lưu mà chưa thấy, đợi GitHub cập nhật bộ nhớ đệm rồi bấm chuông tải lại.

Cập nhật APK được kiểm tra riêng qua Google Play. Tệp này chỉ quản lý lời nhắn của bạn, không dùng để khai báo có bản cập nhật.
