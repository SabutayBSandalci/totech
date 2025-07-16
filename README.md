# Totech - Teknoloji Ürünleri E-Ticaret Sitesi

Modern ve kullanıcı dostu teknoloji ürünleri e-ticaret platformu. Responsive tasarım, çoklu tema desteği ve professional UI/UX özellikleri ile donatılmış.

## 🚀 Özellikler

### 🎨 Tema Sistemi
- **3 Farklı Tema**: Açık Tema, Koyu Tema, Soft Tema
- **Tema Kalıcılığı**: LocalStorage ile tema tercihi korunur
- **Smooth Geçişler**: Tema değişimlerinde animasyonlu geçişler

### 📱 Responsive Tasarım
- **Mobil Öncelikli**: Mobile-first yaklaşımı
- **Responsive Breakpoints**: 480px, 768px, 1024px, 1200px
- **Touch-Friendly**: 48px minimum dokunma alanları

### 🛍️ E-Ticaret Özellikleri
- **Ürün Katalogu**: Kategorize edilmiş ürün listesi
- **Ürün Filtreleme**: Kategori bazlı filtreleme sistemi
- **Ürün Kartları**: Fiyat, özellikler, puanlama sistemi
- **"Sepete Ekle" Butonları**: Her ürün için entegre butonlar

### 💻 Teknik Özellikler
- **Pure HTML/CSS/JavaScript**: Framework bağımsızlığı
- **CSS Grid & Flexbox**: Modern layout teknikleri
- **Font Awesome Icons**: Kapsamlı ikon kütüphanesi
- **Google Fonts**: Inter font ailesi
- **CSS Variables**: Dinamik renk sistemi

## 📂 Proje Yapısı

```
totech/
├── index.html          # Ana sayfa
├── urunler.html        # Ürünler sayfası
├── hakkimizda.html     # Hakkımızda sayfası
├── styles.css          # Ana stil dosyası
├── README.md           # Proje dokümantasyonu
└── .gitignore         # Git ignore dosyası
```

## 🎯 Sayfalar

### 🏠 Ana Sayfa (index.html)
- Hero section ile marka tanıtımı
- Marka hikayesi kartı (brand story card)
- Öne çıkan ürünler showcase
- İnteraktif tema seçici

### 🛒 Ürünler Sayfası (urunler.html)
- Kapsamlı ürün katalogu
- Kategori filtreleme sistemi
- Ürün özellikleri ve puanlamalar
- "Neden Totech?" avantajları bölümü

### ℹ️ Hakkımızda Sayfası (hakkimizda.html)
- Şirket misyon, vizyon, değerleri
- Şirket hikayesi ve kuruluş öyküsü
- Ekip tanıtımları
- İstatistikler ("Rakamlarla Totech")
- İletişim formu

## 🎨 Tema Detayları

### 🌞 Açık Tema
- **Ana Renkler**: Beyaz arkaplan, mavi aksan renkleri
- **Fiyatlar**: Yeşil (#059669)
- **Butonlar**: Yeşil tonları
- **Typography**: Koyu gri metin renkleri

### 🌙 Koyu Tema
- **Ana Renkler**: Koyu gri arkaplan, açık mavi aksan
- **Fiyatlar**: Parlak yeşil (#10b981)
- **Butonlar**: Parlak yeşil tonları
- **Typography**: Açık gri metin renkleri

### 💧 Soft Tema
- **Ana Renkler**: Mavi gradyan arkaplan
- **Fiyatlar**: Açık mavi (#0ea5e9)
- **Butonlar**: Açık mavi tonları
- **Typography**: Lacivert metin renkleri
- **Efektler**: Backdrop blur ve transparency

## 🛠️ Kurulum

1. **Klonlama**:
   ```bash
   git clone [repository-url]
   cd totech
   ```

2. **Yerel Sunucu Başlatma**:
   ```bash
   # Python 3 ile
   python3 -m http.server 8000
   
   # Node.js ile
   npx serve .
   
   # PHP ile
   php -S localhost:8000
   ```

3. **Tarayıcıda Açma**:
   ```
   http://localhost:8000
   ```

## 📱 Responsive Breakpoints

| Cihaz | Genişlik | Açıklama |
|-------|----------|----------|
| Mobile | < 480px | Tek sütun layout |
| Tablet | 481px - 768px | 2 sütun layout |
| Desktop | 769px - 1024px | 3 sütun layout |
| Large Desktop | > 1024px | 4 sütun layout |

## 🎯 Tarayıcı Desteği

- **Chrome**: 80+
- **Firefox**: 75+
- **Safari**: 13+
- **Edge**: 80+

## 📈 Performans

- **CSS**: 108KB (gzip ile ~15KB)
- **HTML**: Toplam ~60KB
- **Resimler**: Unsplash CDN optimizasyonu
- **Fontlar**: Google Fonts preload
- **İconlar**: Font Awesome CDN

## 🔧 Özelleştirme

### Renk Değişimi
CSS variables kullanılarak kolay renk özelleştirmesi:

```css
:root {
  --primary-color: #059669;
  --secondary-color: #2563eb;
  --background-color: #ffffff;
}
```

### Yeni Tema Ekleme
1. CSS'te yeni tema sınıfı tanımla
2. JavaScript'te tema listesine ekle
3. HTML'de dropdown seçeneği ekle

## 📧 İletişim

- **E-posta**: satis@totech.com
- **Destek**: destek@totech.com
- **Website**: [totech.com]

## 📄 Lisans

Bu proje MIT lisansı ile lisanslanmıştır.

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Commit yapın (`git commit -m 'Add amazing feature'`)
4. Branch'i push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📝 Changelog

### v1.0.0
- ✅ Ana sayfa, ürünler ve hakkımızda sayfaları
- ✅ 3 tema desteği (Açık, Koyu, Soft)
- ✅ Responsive tasarım
- ✅ Ürün filtreleme sistemi
- ✅ İletişim formu
- ✅ Brand story card tasarımı

---

**Totech** - Teknolojiye Giden Yol 🚀 