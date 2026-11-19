# WISDOM_ACCUMULATION — Học Qua Video (Lồng Tiếng)

Web app học qua video YouTube có **lồng tiếng Việt tự động từ phụ đề SRT**.

## Tính năng
- Tạo **cấu trúc khóa học**: Thư mục → Bài học (mỗi bài = link YouTube + file phụ đề SRT).
- Bấm vào bài → tự **dịch EN→VI** + **đọc tiếng Việt đồng bộ** theo video.
- **Tua tới/lui vẫn khớp** (lấy thời gian video làm đồng hồ chủ).
- Bật/tắt lồng tiếng, chỉnh tốc độ đọc.
- Lưu cục bộ (localStorage) + xuất/nhập dữ liệu ra file JSON.

## Công nghệ
- **YouTube IFrame Player API** — điều khiển + đồng bộ video.
- **Dịch:** Google Translate (free) → MyMemory (dự phòng).
- **TTS:** SpeechSynthesis (giọng sẵn trình duyệt — free, không bị chặn).

## Dùng
Mở `index.html` (hoặc qua GitHub Pages). Thêm thư mục → thêm bài (dán link YouTube + file SRT tiếng Anh) → bấm học.

> v1 — dịch/giọng ở mức cơ bản, ưu tiên "chạy đủ chức năng + đồng bộ". Có thể nâng cấp DeepL (qua proxy) + Edge TTS sau.
