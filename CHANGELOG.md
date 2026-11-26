# Lịch sử phiên bản

Quy ước số phiên bản `MAJOR.MINOR.PATCH`:
- **PATCH** (1.3.**1**): cập nhật dữ liệu định kỳ hằng tuần, sửa lỗi nhỏ.
- **MINOR** (1.**4**.0): thêm tính năng hoặc lớp thông tin mới.
- **MAJOR** (**2**.0.0): thay đổi lớn về giao diện hoặc cấu trúc dữ liệu.

## v1.4.8 — 25/11/2026

- Thêm 4 tin ngày 25/11: Iran thêm 26 tàu (chủ yếu tàu kéo) vào danh sách vi phạm Hormuz; Houthi tuyên bố tấn công nhà máy Ras Tanura; Mỹ gác ý tưởng hợp tác kinh doanh với Nga (Reuters, chưa xác minh); Anthropic ra mắt Claude Ship.
- Cập nhật xung đột Nga–Ukraine, Yemen và trạm Hormuz; 4 nguồn mới.

## v1.4.7 — 26/11/2026
- Cập nhật ngày: thêm 3 tin nổi bật — bồi thẩm đoàn Mỹ kết tội Huawei (24/11); Iran cáo buộc Mỹ dùng Claude của Anthropic trong chiến dịch chống Iran (cáo buộc, chưa kiểm chứng); Nvidia ngừng giao chip Hopper có giấy phép sang Trung Quốc (18/11). Bỏ 4 tin cũ (Panama, Brent 17/11, hai tin Gaza). Houthi tấn công cảng Jizan và đánh chặn drone trên cảng Jeddah (25/11); thêm tàu dầu bị đạn gần Dubai (25/11) vào ghi chú eo Hormuz.

## v1.4.6 — 25/11/2026
- Thêm tiêu chí theo dõi tin Jensen Huang, AI, Anthropic. Thêm 2 tin: Huang trở lại làm CEO Nvidia (23/11); IPO Anthropic 81,3 tỷ USD, cổ phiếu xuống dưới giá chào bán (24/11).

## v1.4.5 — 25/11/2026
- Cập nhật ngày: thêm 11 tin nổi bật 20–25/11 — lưu lượng tàu qua Hormuz giảm hơn 40%, thêm 4 tàu bị tấn công; Mỹ đưa Megaspeed và 6 công ty Đông Nam Á vào Entity List; Mỹ chuẩn bị tăng thuế với hàng Trung Quốc, EU; Trung Quốc tạm dừng lệnh cấm khoáng sản; Brent bật lại 91,4 USD; Houthi dọa cảng Jeddah sau khi liên quân Saudi đánh Hodeidah; Ukraine đánh chìm tàu Nga ngoài khơi Libya; Anh trừng phạt tướng Myanmar; Gaza. Cập nhật ghi chú eo Hormuz, Bab el-Mandeb và 5 xung đột.

## v1.4.4 — 22/11/2026
- Cập nhật ngày: thêm 3 tin nổi bật 19/11 — ICJ kết luận Myanmar diệt chủng người Rohingya; bộ ba Trump–Tập–Putin ra tuyên bố hòa bình; Mỹ phong tỏa Iran (147 tàu bị chuyển hướng).

## v1.4.3 — 20/11/2026
- Thêm 3 tin nổi bật ngày 19–20/11: tên lửa Houthi nhắm Riyadh, mức đe dọa Hormuz của JMIC, lưu lượng dầu qua Hormuz (Kpler).

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
