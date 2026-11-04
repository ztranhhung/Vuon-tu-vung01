# Vườn Từ Vựng – bản chạy độc lập

Bản này được khôi phục từ project ZIP do người dùng cung cấp. Bao gồm 414 từ vựng, 9 chủ đề, 414 ảnh WebP và giao diện luyện tập/thư viện/thống kê.

## Chạy thử trên máy tính
Mở Terminal/Command Prompt tại thư mục này và chạy:

```bash
python -m http.server 8000
```

Sau đó mở http://localhost:8000

Có thể dùng VS Code Live Server hoặc bất kỳ static web server nào.

## Đưa lên hosting
Tải toàn bộ nội dung thư mục này lên GitHub rồi kết nối repository với Cloudflare Pages (Build command để trống, Output directory là `/` hoặc thư mục gốc).

## Lưu tiến độ
Bản độc lập lưu thống kê bằng localStorage của trình duyệt trên thiết bị hiện tại. Tiến độ không đồng bộ giữa các thiết bị và có thể mất nếu người dùng xóa dữ liệu trình duyệt.

## Phát âm
Dùng Web Speech API của trình duyệt; cần trình duyệt hỗ trợ giọng đọc tiếng Anh.

## Ghi chú
Không cần Netlify Functions, Netlify Database hay Netlify Image CDN. Ảnh được tải trực tiếp từ thư mục `img/`.
