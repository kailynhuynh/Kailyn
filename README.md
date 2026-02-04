# Kombucha Industrial Production Process
<p align="center">
  <img src="https://images.unsplash.com/photo-1623418663518-6b009d3e9488?w=400" width="120" alt="SCOBY culture">
</p>

<p align="center">
  <span style="font-size: larger;">Quy trình sản xuất trà Kombucha quy mô công nghiệp</span>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Mermaid-26A641?style=for-the-badge&logo=mermaid&logoColor=white" alt="Mermaid" />
</div>

## 📋 Quy trình sản xuất (14 bước)

```mermaid
flowchart TD
    A[🍵 Chọn trà đen/ô long/xanh] --> B[Trích ly 5-10g/L<br/>80-90°C, 5-10p]
    B --> C[Lọc bã bằng túi vải<br/>Làm lạnh 8-10°C] 
    C --> D[🍬 Nấu syrup 60-70% Brix<br/>Đun sôi 15-20p diệt khuẩn]
    D --> E[Phối syrup + trà<br/>Chỉnh pH ≤4.2, 28-32°C]
    E --> F[🥼 Lên men hiếu khí<br/>SCOBY 2-10%, 3-7 ngày<br/>pH 2.3-2.5, Bx 10-10.4]
    F --> G[Vớt SCOBY sạch<br/>Lọc dịch trong]
    G --> H[🍑 Phối hương chanh/đào/ổi]
    H --> I[🥫 Chiết lon nhôm<br/>Ghép mí kín khí]
    I --> J[🔥 Thanh trùng hấp<br/>Nâng nhiệt/Keep/Hạ nhiệt]
    J --> K[❄️ Bảo ôn 5-10°C & 28-32°C]
    K --> L[✅ Sản phẩm HSD 1 năm]
    
    style F fill:#ff9999,stroke:#333,stroke-width:3px
    style L fill:#90EE90,stroke:#333,stroke-width:3px
| Công đoạn     | Tham số   | Giá trị | Mục đích              |
| ------------- | --------- | ------- | --------------------- |
| Trích ly      | Tỷ lệ trà | 5-10g/L | Tối ưu hương vị       |
| Syrup         | Brix      | 60-70%  | Diệt khuẩn, dễ lọc    |
| Trước lên men | pH        | ≤4.2    | Chống nấm mốc         |
| Sau lên men   | pH cuối   | 2.3-2.5 | Vị chua ngọt lý tưởng |
| Lên men       | Nhiệt độ  | 28-32°C | Tối ưu SCOBY          |
def kiem_tra_quy_trinh(ph, nhiet_do, brix):
    if ph > 4.2: return "❌ pH quá cao"
    if not (28 <= nhiet_do <= 32): return "❌ Nhiệt độ sai"
    if not (10 <= brix <= 10.4): return "❌ Brix chưa đạt"
    return f"✅ Hoàn hảo! Lên men {int((ph-2.5)*24)}h nữa"

print(kiem_tra_quy_trinh(4.0, 30, 10.2))  # ✅ Hoàn hảo!
# 1. Thay thế toàn bộ README.md bằng code này
# 2. Commit 
git add README.md
git commit -m "Add Kombucha industrial process flowchart"
git push origin main
# 3. GitHub tự render Mermaid!
kombucha-process/
├── README.md ← File này
├── simulator.py
├── docs/
│   └── parameters.md
└── assets/
    └── scoby.jpg
