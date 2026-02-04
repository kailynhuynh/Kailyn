# Kombucha Production 1000L/ngày

<img src="https://images.unsplash.com/photo-1623418663518-6b009d3e9488?w=400" width="120">

## 📋 12 BƯỚC SẢN XUẤT


## ⚙️ THÔNG SỐ QUAN TRỌNG


## 🐍 CHECKER PYTHON

Tạo file `check.py`:
```python
def check_kombucha(ph, temp):
    if ph <= 4.2 and 28 <= temp <= 32:
        return "✅ SẴN SÀNG LÊN MEN"
    return "❌ Cần chỉnh pH/nhiệt độ"

print(check_kombucha(4.0, 30))  # ✅ SẴN SÀNG
git add README.md check.py
git commit -m "Kombucha production"
git push
