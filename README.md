# 🛡️ Cybersecurity Analytics Dashboard (UI)

Siber güvenlik araçları ve log analizi için tasarlanmış, sade ve koyu temalı (Dark Mode) bir web kontrol paneli arayüzü. 

Bu proje, siber güvenlik alanındaki gelişimim doğrultusunda arka planda çalışan Python/C++ araçlarımın çıktılarını (ağ taramaları, log akışları, sistem durumları) görselleştirmek amacıyla hazırlanmış bir **ön yüz (UI) çalışmasıdır**.

---

## 🎨 Tasarım ve Geliştirme Süreci

Tasarım sürecinde dürüst bir yaklaşım benimsenmiştir:
* **HTML İskeleti:** Sayfa yapısı, semantik etiketler, tablo düzeni ve kart mimarisi tamamen **tarafımdan sıfırdan** kodlanmıştır.
* **CSS Düzeni:** Renk paleti seçimi (GitHub dark teması esinlenmesi), menü stilleri, durum etiketleri (badges) ve temel Flexbox yerleşimleri **manuel olarak yazılmıştır**.
* **Yapay Zeka Destekli İyileştirme:** Sayfa düzeninin farklı ekran boyutlarında esnek (responsive) kalması, kaymalara sebep olan kaydırma parametrelerinin (`position/top/left`) temizlenmesi ve CSS'in daha sürdürülebilir hale getirilmesi aşamasında **yapay zekadan (LLM) refactoring/düzenleme desteği** alınmıştır.

---

## 🚀 Öne Çıkan Özellikler

* **Minimalist & Siber Güvenlik Teması:** Kalabalık ve gereksiz menülerden arındırılmış, sadece kritik metriklere odaklanan sade arayüz.
* **Esnek Düzen (Flexbox Layout):** Sabit piksel bağımlılıkları temizlenmiş, ekran boyutuna göre ölçeklenebilir yapı.
* **Log Tablosu ve Etiketler:** Olay akışlarını ve durumları (Başarılı, Engellendi) net gösteren renk kodlamaları.

---

## 💻 Kullanılan Teknolojiler

* **HTML5** (Semantik yapı ve tablo mimarisi)
* **CSS3** (Flexbox, CSS Variables, Koyu Tema Tasarımı)

---

## 🎯 Gelecek Planları (Roadmap)

- [ ] Python (Flask / FastAPI) backend entegrasyonu ile canlı veri akışı sağlamak
- [ ] Log tablosu için anlık arama ve durum filtresi eklemek
- [ ] Anlık olay uyarıları (Live Alerts) için notification bileşeni dahil etmek
