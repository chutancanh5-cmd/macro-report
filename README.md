# Báo cáo vĩ mô phân tầng

Trang tĩnh tự động cập nhật từ bot vĩ mô (`macro/` trong dự án TradingView cục bộ).

**Xem báo cáo:** https://chutancanh5-cmd.github.io/macro-report/

Bản tin đọc **từ toàn cầu xuống Việt Nam**:

| Tầng | Nội dung |
|---|---|
| 1 · Toàn cầu | Điều kiện tài chính, chênh lệch lợi suất trái phiếu rác/mới nổi, độ rộng chỉ số lớn, biến động trái phiếu, chu kỳ bán dẫn, đồng/vàng |
| 2 · Nền kinh tế lớn | Mỹ · Trung Quốc · Châu Âu · Nhật · Hàn Quốc — mỗi nước 4 trụ: chính sách tiền tệ, lạm phát, tăng trưởng, thị trường (+ tiền tệ) |
| 3 · ASEAN & mới nổi | Độ rộng 7 chỉ số khu vực, rổ 9 đồng tiền châu Á, hướng chính sách 5 ngân hàng trung ương |
| 4 · Việt Nam | Lãi suất liên ngân hàng, tỷ giá & biên độ, tín dụng, định giá P/E, chênh giá vàng, căng thẳng trái phiếu |

Nền kinh tế nước ngoài **không** cộng thẳng vào điểm Việt Nam — chỉ vào qua các kênh
lan truyền có điều kiện kích hoạt kiểm chứng được (tỷ giá, xuất khẩu, bán dẫn, carry trade yên).

## Cách đọc

- Điểm thang **−100…+100**, âm là bất lợi cho cổ phiếu.
- Mỗi tầng kèm **độ phủ dữ liệu**. Thành phần thiếu bị loại khỏi *cả tử số lẫn mẫu số*,
  không bao giờ bị gán 0 — và luôn được liệt kê ở mục *"Bot không đo được hôm nay"*.
- Mục **"Số liệu AI đọc từ web"** là các con số không có API miễn phí ổn định. Chúng
  **không** được tính vào bất kỳ điểm số nào; chỉ là bối cảnh, luôn kèm nguồn và kỳ.

## Nguồn

FRED · BIS (lãi suất chính sách 49 nước) · eastmoney (vĩ mô Trung Quốc) · OECD CLI qua
DBnomics · ECB · Yahoo Finance · STOXX · vnstock · NSDP/Tổng cục Thống kê · Vietcombank · RSS.

---

⚠️ Đây là **công cụ hỗ trợ ra quyết định**, không phải khuyến nghị đầu tư và không phải
dự đoán chắc chắn. Đọc kèm bối cảnh và quản trị rủi ro của riêng bạn.
