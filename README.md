# Kombucha Industrial Production Process

<p align="center">
  <img src="https://images.unsplash.com/photo-1623418663518-6b009d3e9488?w=400" width="120" alt="SCOBY">
</p>

<p align="center">
  <span style="font-size: larger;">Quy trình sản xuất trà Kombucha công nghiệp</span>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Mermaid-26A641?style=for-the-badge&logo=mermaid&logoColor=white" />
</div>

---

## 📋 Quy trình 14 bước

```mermaid
flowchart TD
    A[🍵 Chọn trà] --> B[Trích ly 5-10g/L]
    B --> C[Lọc bã + Lạnh 8-10°C]
    C --> D[🍬 Syrup 60-70% Brix]
    D --> E[Phối + pH 4.2 + 30°C]
    E --> F[🥼 Lên men SCOBY 3-7 ngày]
    F --> G[Vớt SCOBY + Lọc]
    G --> H[🍑 Thêm hương]
    H --> I[🥫 Chiết lon]
    I --> J[🔥 Tiệt trùng]
    J --> K[❄️ Bảo ôn]
    K --> L[✅ Sản phẩm]

    style F fill:#ff9999,stroke:#333
    style L fill:#90EE90,stroke:#333
| Công đoạn  | Tham số  | Giá trị |
| ---------- | -------- | ------- |
| Trích ly   | Tỷ lệ    | 5-10g/L |
| Syrup      | Brix     | 60-70%  |
| pH ban đầu | pH       | ≤4.2    |
| pH cuối    | pH       | 2.3-2.5 |
| Lên men    | Nhiệt độ | 28-32°C |def check_kombucha(ph, temp):
    if ph > 4.2: return "pH quá cao"
    if temp < 28 or temp > 32: return "Nhiệt độ sai"
    return "OK"

print(check_kombucha(4.0, 30))  # OK
git add README.md
git commit -m "Add Kombucha flowchart"
git push
