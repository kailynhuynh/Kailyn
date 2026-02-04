# Kombucha Production Process

<p align="center">
  <img src="https://images.unsplash.com/photo-1623418663518-6b009d3e9488?w=400" width="120" alt="SCOBY">
</p>

<p align="center">
  <span style="font-size: larger;">14 bước sản xuất công nghiệp</span>
</p>

## Quy trình sản xuất

```mermaid
flowchart TD
    A[Chon tra] --> B[Trich ly] 
    B --> C[Loc va lam lanh]
    C --> D[Syrup 60-70%]
    D --> E[pH 4.2 + 30C]
    E --> F[Len men 3-7 ngay]
    F --> G[Vot SCOBY]
    G --> H[Huong trai cay]
    H --> I[Chiet lon]
    I --> J[Tiet trung]
    J --> K[Bao on]
    K --> L[San pham]
| Cong doan | Tham so | Gia tri |
| --------- | ------- | ------- |
| Trich ly  | Ty le   | 5-10g/L |
| pH dau    | pH      | ≤4.2    |
| pH cuoi   | pH      | 2.3-2.5 |
| Nhiet do  | Do C    | 28-32   |
def check(ph, temp):
    return "OK" if ph<=4.2 and 28<=temp<=32 else "Loi"
git add README.md
git commit -m "Kombucha process"
git push

