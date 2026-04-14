---
name: analyzing-fnb-competitors
description: "Use when analyzing competitors in the F&B industry, comparing brand positioning or pricing strategies, identifying market gaps in Vietnamese F&B, or needing competitive intelligence to make strategic decisions about expansion, repositioning, or product launches."
---

# F&B Competitive Analysis

Phân tích đối thủ cạnh tranh toàn diện cho ngành F&B (Food & Beverage) tại Việt Nam. Output action-oriented (hướng đến hành động), dựa trên dữ liệu khách quan.

## When to Use

- Phân tích đối thủ cạnh tranh, so sánh thương hiệu F&B
- Nghiên cứu thị trường: cà phê, trà sữa, nhà hàng, đồ ăn nhanh, cloud kitchen
- Tìm Market Gap (khoảng trống thị trường), whitespace opportunities
- Chuẩn bị mở chi nhánh mới, tái định vị, ra mắt sản phẩm
- Doanh thu giảm, mất khách, không rõ đối thủ đang làm gì

**KHÔNG dùng khi:** Chỉ cần so sánh giá nhanh, chưa rõ loại hình F&B, hoặc cần audit nội bộ (không so sánh đối thủ).

## Workflow

### Step 1: Thu thập Input

Hỏi user (nếu chưa cung cấp):

| Input | Ví dụ |
|-------|-------|
| Loại hình F&B | Cà phê, trà sữa, gà rán, cloud kitchen |
| Khu vực | TP.HCM quận 1-3-7, Hà Nội nội thành |
| Phân khúc giá | Bình dân (<30k), trung cấp (30-80k), cao cấp (>80k) |
| 3-5 đối thủ chính | Phúc Long, Highlands, The Coffee House |
| Mục tiêu nghiên cứu | Mở chi nhánh, tái định vị, ra sản phẩm mới |

Nếu user không cung cấp đối thủ, tự đề xuất 3-5 đối thủ phù hợp.

### Step 2: Phân tích 8 Dimensions

Phân tích mỗi đối thủ theo: Brand Positioning, Product & Menu, Pricing, Location & Distribution, Marketing & Digital, Customer Experience, Operations & Scale, Financial Indicators.

Chi tiết từng dimension + câu hỏi phân tích: xem `references/analysis-frameworks.md`

### Step 3: Cross-competitor Analysis

1. **Competitive Matrix** - Bảng so sánh tất cả đối thủ (dùng thang ⭐1-5)
2. **Perceptual Map** - 2 trục theo ngành (xem `references/analysis-frameworks.md` để chọn trục phù hợp)
3. **Porter's Five Forces** - 5 lực lượng cạnh tranh cho phân khúc cụ thể
4. **Market Gap** - Khoảng trống và cơ hội chưa khai thác

### Step 4: SWOT từng đối thủ

Tạo bảng SWOT. **Highlight điểm yếu đối thủ mà user có thể khai thác trực tiếp.**

### Step 5: Chiến lược 3 tầng

| Tầng | Timeline | Số lượng |
|------|----------|----------|
| Quick Win (Thắng nhanh) | 30 ngày | 2 chiến lược |
| Differentiation (Khác biệt hóa) | 1-3 tháng | 3 chiến lược |
| Long-term Moat (Hào cạnh tranh) | 6-12 tháng | 1 chiến lược + counter-strategies |

Mỗi chiến lược gồm: Mô tả, Lý do, Timeline, Resources, Expected Impact.

Template sẵn dùng theo loại hình: xem `references/strategy-templates.md`

### Step 6: Hệ thống theo dõi

KPIs tracking, công cụ monitoring, template báo cáo tháng. Chi tiết: xem `references/strategy-templates.md`

## Output Format

Báo cáo gồm: Executive Summary (3-5 bullets) → Competitive Matrix → Perceptual Map → Chi tiết từng đối thủ (8 Dimensions + SWOT) → Porter's Five Forces → Market Gap → Chiến lược 3 tầng → Hệ thống theo dõi → Phụ lục (nguồn, limitations).

## Common Mistakes

| Lỗi phổ biến | Cách tránh |
|-------------|-----------|
| Confirmation bias - chỉ tìm dữ liệu ủng hộ kết luận đã có | Thu thập data trước, rút kết luận sau |
| Chỉ focus đối thủ lớn, bỏ qua đối thủ đang lên | Luôn include 1-2 "rising competitors" |
| Phân tích quá nhiều chiều khiến insight bị loãng | Ưu tiên 3-4 dimensions quan trọng nhất cho mục tiêu cụ thể |
| Dùng dữ liệu cũ (outdated) | Ghi rõ thời điểm thu thập, ưu tiên data < 3 tháng |
| Copy chiến lược không phù hợp context | Mỗi đề xuất phải gắn với data cụ thể của đối thủ |

## Language Rules

- Tiếng Việt, thuật ngữ giữ tiếng Anh kèm giải thích: "USP (Điểm bán hàng độc nhất)"
- KHÔNG dùng dấu em-dash, thay bằng dấu gạch ngang (-) hoặc phẩy
- Tone: chuyên nghiệp, dễ hiểu, action-oriented

## References

| File | Purpose |
|------|---------|
| `references/analysis-frameworks.md` | Porter's Five Forces, SWOT, Perceptual Map, Competitive Matrix, Blue Ocean |
| `references/fnb-market-vietnam.md` | Thị trường F&B VN: quy mô, xu hướng, benchmark, delivery, pháp lý |
| `references/strategy-templates.md` | Template chiến lược: Cà phê, Trà sữa, QSR, Cloud Kitchen + KPI tracking |
