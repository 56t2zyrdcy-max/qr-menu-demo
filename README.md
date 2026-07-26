# QR Menu Demo — DJ oZMEn / Özkan Özmen

Çok dilli QR menü ve masa bazlı sipariş sistemi demosu.
Restoranlara sunum için hazırlanmıştır.

## Demolar

| Dosya | Restoran | Diller |
|---|---|---|
| `index.html` | Churrascaria Steakhouse (AIDA) | Almanca · İngilizce · İspanyolca · Felemenkçe · Türkçe |
| `fjordside.html` | Fjordside — Oslo cruise limanı | Norveççe · İngilizce · Almanca · Türkçe · Çince |

## Özellikler

- **Masa tanıma** — QR koddaki `?table=11` parametresi masayı otomatik tanır
- **Çok dilli menü** — tüm yemek adları, açıklamalar, alerjenler ve arayüz çevrilmiş
- **Pişirme derecesi** — biftekler sepete eklenmeden önce sorulur (Blutig → Durchgebraten)
- **Garson çağırma** — masaya bakan garsona sesli bildirim + titreşim, 45 sn'de bir tekrar
- **Servis paneli** — masa no, saat, misafir notu, bekleme süresi sayacı, durum akışı
- **QR üretici** — 30 masaya kadar yazdırılabilir QR kartları

## Kullanım

Ana sayfa: `https://KULLANICI-ADI.github.io/DEPO-ADI/`

Belirli bir masa: `https://KULLANICI-ADI.github.io/DEPO-ADI/?table=11`

Demo modunda alt bardan **Gast / Service / QR** görünümleri arasında geçiş yapılabilir.

## Teknik notlar

- Tek dosya, harici bağımlılık yok — görseller HTML içine gömülü
- Veri tarayıcı belleğinde tutulur (demo). Canlı kullanım için yerel sunucu veya Firebase gerekir
- Gemi içi kullanımda internetsiz çalışması için tüm varlıklar yerel sunucuya kopyalanmalıdır

## Telif

Churrascaria demosundaki logo, çizimler ve menü içeriği AIDA Cruises'a aittir ve yalnızca
sunum amacıyla kullanılmaktadır. Yayına alınması için yazılı izin gerekir.

---

İletişim: DJ oZMEn — Özkan Özmen
