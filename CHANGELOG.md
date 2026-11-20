# Lịch sử phiên bản

Quy ước số phiên bản `MAJOR.MINOR.PATCH`:
- **PATCH** (1.3.**1**): cập nhật dữ liệu định kỳ hằng tuần, sửa lỗi nhỏ.
- **MINOR** (1.**4**.0): thêm tính năng hoặc lớp thông tin mới.
- **MAJOR** (**2**.0.0): thay đổi lớn về giao diện hoặc cấu trúc dữ liệu.

## v1.4.2 — 20/11/2026
- Tin nổi bật chỉ giữ 30 ngày: tin hết hạn được xoá khi cập nhật. Bỏ tin Suez (14/10).

## v1.4.1 — 20/11/2026
- Cập nhật ngày: tàu dầu trúng đạn không rõ nguồn gốc cách Khasab (Oman) khoảng 6 hải lý, đêm 18/11; thêm vào tin nổi bật và ghi chú eo Hormuz.

## v1.4.0 — 19/11/2026
- GDP (IMF 2026) và xuất/nhập khẩu (World Bank) cho gần 200 nền kinh tế, trước chỉ có 50.
- Cột GDP mỏng lại cho đỡ rối; điểm đặt cột của các nước mới tự tính theo lãnh thổ.
- Chưa có: Syria (IMF chỉ có số liệu năm 2010), Kosovo; nhập khẩu của Venezuela, Sudan, Guyana, Papua New Guinea để trống vì số liệu nguồn bất thường.
- Tác vụ tự động chuyển sang Haiku 5.5: hằng ngày cập nhật logistics, xung đột, tin tức; hằng tháng cập nhật khối thương mại và GDP.

## v1.3.2 — 19/11/2026
- Sửa vị trí cột GDP của Việt Nam (trước bị đặt lệch sang Lào) và Israel.
- Di chuột lên một nước hiện luôn GDP, xuất, nhập khẩu.
- Cột nhỏ nhất cao tối thiểu 2,5px để nước nhỏ vẫn nhìn thấy.

## v1.3.1 — 19/11/2026
- Hiện số phiên bản trên app; thêm CHANGELOG và tag phiên bản trên GitHub.

## v1.3.0 — 19/11/2026
- Cột GDP (IMF 2026), xuất khẩu, nhập khẩu (World Bank) cho 50 nền kinh tế lớn nhất, hiện khi bật lớp Khối thương mại.
- Tuỳ chọn thang căn bậc hai để dễ nhìn nước nhỏ.

## v1.2.0 — 19/11/2026
- Tuyến logistics vẽ cong mềm, có viền và chấm chạy theo chiều di chuyển.
- Nền tối mặc định, nút đổi nền sáng/tối.

## v1.1.0 — 19/11/2026
- Lớp "Tin nổi bật" (xung đột, thương mại, công nghệ chiến lược, năng lượng, logistics) với bộ tiêu chí lọc tin 5 điểm.
- Nhãn MỚI cho tin và diễn biến trong 7 ngày gần nhất.

## v1.0.0 — 19/11/2026
- Phiên bản đầu: bản đồ phóng to/thu nhỏ, lớp Khối thương mại (10 khối), Xung đột (20 điểm nóng), Logistics (14 điểm nghẽn, 11 tuyến).
