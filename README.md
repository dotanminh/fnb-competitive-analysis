# F&B Competitive Analysis Skill

Skill phân tích đối thủ cạnh tranh (Competitive Analysis) toàn diện cho ngành Food & Beverage tại Việt Nam.

## Tổng quan

Skill này giúp chủ doanh nghiệp F&B thực hiện phân tích đối thủ cạnh tranh chuyên sâu bằng AI. Từ việc so sánh Brand Positioning, Pricing Strategy, Marketing đến việc tìm Market Gap và đề xuất chiến lược cạnh tranh cụ thể.

## Tính năng chính

- **Phân tích 8 chiều (8 Dimensions):** Brand, Product, Pricing, Location, Marketing, Customer Experience, Operations, Financial
- **3 Framework chuyên sâu:** Porter's Five Forces, SWOT Analysis, Perceptual Mapping
- **Chiến lược 3 tầng:** Quick Win (30 ngày), Differentiation (1-3 tháng), Long-term Moat (6-12 tháng)
- **Hệ thống theo dõi:** KPIs, công cụ monitoring, template báo cáo tháng

## Cài đặt

Đặt folder `fnb-competitive-analysis` vào một trong các vị trí:

```
.agents/skill/fnb-competitive-analysis/    # Local project
~/.claude/skills/fnb-competitive-analysis/ # Global (Claude)
```

## Sử dụng

Nói với AI bất kỳ trigger phrase nào:

- "Phân tích đối thủ F&B"
- "Nghiên cứu đối thủ cạnh tranh ngành cà phê"
- "So sánh thương hiệu trà sữa tại TP.HCM"
- "Tìm market gap ngành đồ ăn nhanh"

### Ví dụ nhanh

```
User: Phân tích đối thủ cho chuỗi trà sữa phân khúc trung cấp tại TP.HCM, 
      đối thủ chính: Phúc Long, Highlands, Koi Thé

AI: [Chạy skill fnb-competitive-analysis]
    → Thu thập thông tin
    → Phân tích 8 Dimensions cho mỗi đối thủ
    → Tạo Competitive Matrix + Perceptual Map
    → SWOT từng đối thủ  
    → Đề xuất Quick Win + Differentiation + Long-term Moat
    → Output: Báo cáo markdown hoàn chỉnh
```

## Cấu trúc thư mục

```
fnb-competitive-analysis/
├── SKILL.md                              # File chính - chỉ thị cho AI
├── README.md                             # Hướng dẫn sử dụng (file này)
└── references/
    ├── analysis-frameworks.md            # Chi tiết Porter's, SWOT, Perceptual Map
    ├── fnb-market-vietnam.md             # Bối cảnh thị trường F&B Việt Nam
    └── strategy-templates.md             # Template chiến lược theo loại hình F&B
```

## Yêu cầu

- AI Agent hỗ trợ đọc file markdown (Claude, ChatGPT, Gemini, Copilot)
- Không cần dependencies bên ngoài
- Output hoàn toàn bằng markdown, không cần tool đặc biệt

## Author

**Minh Đỗ** - [Zalo Community](https://zalo.me/g/igkywu632)

## Version

- v1.0.0 (2026-04-14) - Initial release
