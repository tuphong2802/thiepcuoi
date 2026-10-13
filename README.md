# Thiệp cưới online — Mạnh Quyết & Phạm Hân

Thiệp cưới website responsive, ưu tiên hiển thị trên điện thoại, sử dụng 8 ảnh cưới đã được cung cấp.

## Xem thiệp

1. Giải nén gói ZIP.
2. Mở `index.html` bằng Chrome, Edge hoặc Safari.
3. Ảnh hiển thị từ thư mục `assets`. Phông chữ Google Fonts và phần nhạc YouTube cần Internet.
4. Trong phần “Giai điệu cho ngày chung đôi”, chọn một bài để phát. Thiệp không tự phát nhạc khi vừa mở trang.

## Thông tin hiện tại

- Chú rể: Mạnh Quyết; bố mẹ: Cao Văn Lam và Nguyễn Thị Khương.
- Gia đình chú rể: Thôn Hồng Lĩnh, xã Sơn Hồng, tỉnh Hà Tĩnh.
- Cô dâu: Phạm Hân; bố mẹ: Phạm Văn Tuân và Nguyễn Thị Lụa.
- Gia đình cô dâu: Thôn Dương Trạch, xã Triệu Việt Vương, tỉnh Hưng Yên.
- Tiệc cưới nhà gái: 10:00, Thứ Ba, 24/11/2026, tại tư gia nhà gái, Thôn Dương Trạch, xã Triệu Việt Vương, tỉnh Hưng Yên.
- Tiệc cưới nhà trai: 10:45, Chủ Nhật, 29/11/2026, tại tư gia nhà trai, Thôn Hồng Lĩnh, xã Sơn Hồng, tỉnh Hà Tĩnh.

## Cập nhật sau này

Mở `index.html`, tìm `const WEDDING = {` ở gần cuối file. Thông tin cá nhân, thời gian, địa chỉ, bản đồ và kênh RSVP đều được cấu hình tại đây.

`rsvpWhatsApp`: số WhatsApp có mã quốc gia, chỉ gồm chữ số; ví dụ `84901234567`. Hoặc đặt `rsvpEmail` để mở email xác nhận. Để trống cả hai thì form RSVP sẽ báo rõ là chưa có kênh nhận phản hồi; không giả vờ gửi thành công.

Bản đồ mở trang tìm kiếm địa chỉ trên Google Maps; ghim vị trí chính xác có thể cần được chủ nhà xác nhận lại.

## Đăng tải thành trang web

Tải toàn bộ thư mục `thiep-cuoi-online` lên dịch vụ hosting trang tĩnh như Netlify Drop hoặc GitHub Pages. Phải giữ nguyên thư mục `assets` bên cạnh `index.html`.

## Lưu ý

Nhạc được phát qua trình nhúng YouTube, không tải kèm tệp nhạc có bản quyền. RSVP hiện chưa có backend lưu dữ liệu; hãy cấu hình WhatsApp/email hoặc kết nối một dịch vụ form nếu muốn nhận phản hồi tự động.
