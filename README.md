<div align="center">

<img src="docs/01-kapak.png" alt="Rick & Morty Karakter Portalı — Enes Öztürk imzalı proje" width="100%">

# Rick & Morty Karakter Portalı

**826 karakter, 51 bölüm ve 126 lokasyon için arama, filtre, kart/tablo görünümü ve favori yönetimi sunan React portalı.**

[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/rick-morty-portali)
[![TypeScript](https://img.shields.io/badge/TypeScript-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/rick-morty-portali)
[![REST](https://img.shields.io/badge/REST-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/rick-morty-portali)
[![API](https://img.shields.io/badge/API-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/rick-morty-portali)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/rick-morty-portali)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

Bu portal, Rick and Morty evreninin resmî API'sini kullanarak karakterleri, bölümleri ve konumları tek arayüzde toplar. Canlı arama, durum/tür filtreleri, kart ve tablo görünümleri, favoriler ve rastgele karakter keşfi gibi özelliklerle veri gezinmesi hızlı ve keyiflidir.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **826 karakter** | Resmî API'den canlı veri çekme ve sayfalama. |
| **Arama & filtre** | İsim, durum ve tür bazlı anlık filtreleme. |
| **Kart / Tablo** | İki farklı görünüm modu arasında geçiş. |
| **Favoriler** | Beğenilen karakterleri yerel olarak saklama. |
| **Rastgele keşif** | Tek tıkla rastgele karakter açma. |
| **Bölüm & lokasyon** | 51 bölüm ve 126 lokasyon referansı. |

---

## Evren

| Ölçü | Değer |
| --- | --- |
| Karakter | 826 |
| Bölüm | 51 |
| Lokasyon | 126 |
| Görünüm | 2 mod |

---

## Galeri

<img src="docs/02-ekran.png" alt="Rick & Morty Karakter Portalı ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="Rick & Morty Karakter Portalı etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="Rick & Morty Karakter Portalı detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/rick-morty-portali.git
cd rick-morty-portali
npm install
npm run dev
```

> Veriler canlı olarak https://rickandmortyapi.com adresinden alınır.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/services/rickAndMortyApi.ts  API katmanı
src/components/HeroSection.tsx    Karşılama alanı
src/components/FilterBar.tsx      Arama ve filtreler
src/components/CharacterCard.tsx  Kart görünümü
src/components/CharacterTableView.tsx  Tablo görünümü
src/components/FavoritesModal.tsx Favori listesi
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
