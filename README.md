# 🔐 Kali Linux Parola Güvenlik Analiz Aracı

**Kali Linux'ta Python ile geliştirilmiş, profesyonel parola güvenlik analiz ve yönetim aracı**

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Kali%20Linux-red)

## ✨ Özellikler

✅ **Parola Güç Analizi** - 7 kritere göre detaylı skorlama  
✅ **Kırılma Süresi Tahmini** - Brute-force saldırı simülasyonu  
✅ **Sızdırılmış Parola Kontrolü** - SHA1 hash ile güvenlik kontrolü  
✅ **Akıllı Parola Üretici** - Hatırlaması kolay, güçlü parolalar  
✅ **Detaylı Raporlama** - PDF/HTML/TXT formatında çıktılar  
✅ **Kali Linux Optimize** - Pentesting dağıtımına özel optimizasyon  

## 🚀 Hızlı Kurulum

```bash
# Repoyu klonla
git clone https://github.com/kullaniciadi/password-analyzer.git
cd password-analyzer

# Kurulum script'ini çalıştır
chmod +x setup.sh
./setup.sh

# Programı başlat
python3 password_checker.py
┌─────────────────────────────────────────────┐
│ 🔒 PAROLA ANALİZ RAPORU                     │
├─────────────────────────────────────────────┤
│ Parola: K***4!                              │
│ Uzunluk: 12 karakter                        │
│ 📊 Güç Puanı: 13/15                         │
│ 📈 Seviye: 🟢 ÇOK GÜÇLÜ                     │
│ ⏱️ Kırılma Süresi: 345 yıl                  │
└─────────────────────────────────────────────┘password-analyzer/
├── password_checker.py     # Ana program
├── extra_features.py       # Gelişmiş özellikler
├── setup.sh               # Otomatik kurulum
├── requirements.txt       # Bağımlılıklar
├── weak_passwords.txt     # Zayıf parola listesi
├── LICENSE               # MIT Lisansı
└── README.md             # Bu dosya

# Temel analiz
python3 password_checker.py

# Gelişmiş özellikler
python3 extra_features.py

# Belirli bir parolayı test et
python3 -c "from password_checker import PasswordChecker; pc = PasswordChecker(); pc.check_password('Test123!')"

"Kali Linux ile Python'u birleştirerek, her parolayı kırılmaz bir dijital kale, her kullanıcıyı ise kendi siber güvenliğinin bilinçli muhafızı yapmayı hedefliyorum." 🔐⚔️💻

MIT License

Copyright (c) 2024 [Adınız]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
env/
venv/
.env

# Logs ve veri dosyaları
*.log
*.sqlite
*.db

# IDE
.vscode/
.idea/
*.swp
*.swo

# Sistem
.DS_Store
Thumbs.db

# Projeye özel
password_results.txt
test_results/## 📈 Proje İstatistikleri

```bash
git shortlog -s -n  # Commit istatistikleri
git log --oneline | wc -l  # Toplam commit sayısı
find . -name "*.py" | xargs wc -l  # Toplam kod satırı







