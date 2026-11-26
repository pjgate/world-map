# Bản đồ địa chính trị

Bản đồ thế giới tương tác (một file HTML duy nhất) với 3 lớp thông tin:

- **Khối thương mại**: WTO, APEC, ASEAN, RCEP, CPTPP, G7, G20, BRICS, EU, USMCA. Tick nhiều khối để chồng lên nhau; nước thuộc nhiều khối hiện sọc nhiều màu.
- **Xung đột đang diễn ra**: ~20 điểm nóng, xếp theo mức độ, kèm số người chết tạm tính năm 2026.
- **Logistics**: các điểm nghẽn hàng hải (Hormuz, Bab el-Mandeb, Suez, Malacca, Panama...) và các tuyến vận tải biển/đường sắt chính, tô màu theo tình trạng.

Phóng to/thu nhỏ bằng con lăn chuột, kéo để di chuyển, hoặc dùng nút `+` `−` `⤢`. Bấm vào một nước để xem nước đó thuộc khối nào và có xung đột nào liên quan.

## Chạy

Mở `index.html` bằng trình duyệt (cần internet để tải d3 và dữ liệu bản đồ từ CDN).
Hoặc bật **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root) để xem online.

## Cập nhật dữ liệu

Toàn bộ dữ liệu nằm ở đầu phần `<script>` trong `index.html`:

| Biến | Nội dung |
|---|---|
| `UPDATED` | Ngày cập nhật hiển thị trên trang |
| `BLOCS` | Các khối và danh sách thành viên (mã số ISO 3166-1, ví dụ Việt Nam = `704`) |
| `CONFLICTS` | Xung đột: tên, mức độ, toạ độ `[kinh độ, vĩ độ]`, nước liên quan, ghi chú |
| `CHOKEPOINTS` | Điểm nghẽn hàng hải và tình trạng |
| `ROUTES` | Tuyến vận tải (danh sách điểm `[kinh độ, vĩ độ]`) |
| `SOURCES` | Nguồn tham khảo |

Phiên bản hiện tại: **v1.4.7** — xem [CHANGELOG.md](CHANGELOG.md). Dữ liệu cập nhật ngày 26/11/2026. Các tuyến đường chỉ mang tính minh họa. Biên giới theo Natural Earth, không thể hiện quan điểm về chủ quyền.
