# 🗡️ Gölge Yemini — League of Legends Tanıtım Sitesi

> **⚠️ Bu proje yalnızca eğitim amaçlıdır. Ticari bir amaç içermemektedir.**



---

## 🚨 Önemli Uyarı

```
BU PROJE BİR ÖĞRENCİ ÖDEVİDİR.
Burada yer alan hiçbir içerik — fiyatlandırma, ürün açıklamaları,
pazarlama metinleri — gerçek bir ürün veya hizmetin satışını
temsil etmez, amaçlamaz ya da ima etmez.

Tüm fiyatlar ve içerikler tamamen kurgusaldır.
```

**League of Legends** ve ilgili tüm varlıklar **Riot Games, Inc.** tescilli markasıdır.
Bu site Riot Games tarafından onaylı, sponsorlu veya bağlantılı değildir.
"Gölge Yemini" tamamen orijinal ve kurgusal bir konsepttir.


---

## 📋 Proje Hakkında

| Bilgi | Detay |
|---|---|
| **Ders** | Web Tasarımı / Front-End Geliştirme |
| **Ödev No** | Ödev 7 |
| **Konu** | Tek Sayfalık Responsive Tanıtım Sitesi |
| **Kullanılan Teknolojiler** | HTML5, CSS3 (Vanilla) |
| **Amaç** | CSS position, variables, transition ve animation kavramlarını pekiştirmek |

---

## 📁 Dosya Yapısı

```
golge-yemini/
├── index.html       # Ana HTML dosyası
├── style.css        # Tüm stillerin tanımlandığı CSS dosyası
└── README.md        # Bu dosya
```

---

## ✅ Ödev Gereksinimleri

### `position` Kullanımı
- [x] `fixed` — Sayfanın üstüne sabit yapıştırılmış navbar
- [x] `sticky` — Sol kenar çubuğu (sidebar), scroll'la birlikte hareket eder ama viewport'a yapışık kalır
- [x] `absolute` — Item ikonunun üzerindeki "MİTİK" / "YENİ" badge'leri; fiyat kartındaki "EN POPÜLER" etiketi
- [x] `relative` — Bu badge'leri saran `.item-icon-container` ve `.pricing-badge-wrap` container'ları

### CSS Variables (8+)
- [x] `--color-gold`, `--color-purple`, `--color-bg-primary` — Renk paleti
- [x] `--font-display`, `--font-body`, `--font-ui` — Tipografi
- [x] `--spacing-md`, `--spacing-lg`, `--spacing-xl` — Boşluk sistemi
- [x] `--navbar-height`, `--sidebar-width` — Layout boyutları
- [x] `--transition-speed`, `--shadow-gold` — Efektler
- [x] Toplamda **30+** değişken tanımlı

### Transition (3+ element)
- [x] Navbar linkleri — renk geçişi + alt çizgi animasyonu
- [x] Stat kartları — `translateY` + glow efekti
- [x] Butonlar — gradient kayması + box-shadow
- [x] Sinerji kartları — `translateX` kayma
- [x] Fiyat kartları — `translateY` yükselme

### Animation (Keyframes)
- [x] `floatItem` — İkon yüzer yukarı aşağı
- [x] `goldenGlow` — Nabız gibi parıldama efekti
- [x] `runeRotate` — Çevreleyen rün halkası döner
- [x] `badgePulse` — Badge'ler atar gibi büyür küçülür
- [x] `shimmer` — Başlık metni üzerinde parlak geçiş
- [x] `particleFall` — Altın parçacıklar düşer
- [x] `scanline` — İkon üzerinde tarama çizgisi
- [x] `fadeInUp` — Sayfa açılışında içerik yukarı kayar

---

## 🎨 Tasarım Kararları

- **Tema:** Karanlık fantezi / oyun estetiği — LoL'ün orijinal tasarım diliyle uyumlu
- **Tipografi:** `Cinzel Decorative` (başlıklar) + `EB Garamond` (metin) + `Rajdhani` (UI)
- **Renk Paleti:** Derin siyah arka plan, altın vurgular, mor efektler
- **Layout:** Fixed navbar + Sticky sidebar + scrollable main content

---

## 📜 Lisans & Telif Hakkı

Bu proje **MIT Lisansı** ile lisanslanmıştır — yalnızca eğitim amaçlı kullanım için.

- **League of Legends** © Riot Games, Inc. — Tüm hakları saklıdır.
- Bu site Riot Games ile hiçbir ticari, hukuki veya kurumsal ilişki içinde değildir.
- Ticari amaçla kullanılamaz, kopyalanamaz veya dağıtılamaz.

---

<div align="center">
  <sub>🎓 Öğrenci Projesi · CSS/HTML Ödev 7 · Ticari Amaç İçermez</sub>
</div>
