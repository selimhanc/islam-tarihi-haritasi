# İslam Tarihi Haritası (400–1800)

400–1800 yılları arası İslam tarihinin **şehirlerini, âlimlerini, medreselerini,
eserlerini ve büyük savaşlarını** tek dosyada gösteren etkileşimli harita.

## Özellikler
- **Parola kilidi** — sayfa `Avr313` parolasıyla açılır (istemci tarafı, bkz. Güvenlik).
- **Google Maps** tabanlı klasik parşömen görünüm. Google'ın kendi ülke etiketleri kapalıdır;
  yalnızca veride noktası olan ülkeler etiketlenir.
- **Konu filtreleri** — Âlim, Fıkıh/Usûl, Hadîs, Felsefe, Kelâm, Tasavvuf, Dil, Tarih/Coğrafya,
  Siyaset/Hukuk, Kutsal/Hac, Eğitim, Savaş, Büyük Savaş, Biyografi.
- **Dönem filtreleri** ve **yıl aralığı** (400–1800).
- **Rotalar** — Hicret, İsrâ ve Mi'rac, Veda Haccı, Anadolu'nun Fethi, Timur'un ve Bâbûr'un seferleri.
- **Biyografi entegrasyonu** — 22 âlimin sayfasından 240 olay/şehir eşlemesi; detay kutusundan
  biyografi sayfasına bağlantı.
- **Arama yalnızca şehir adında** çalışır; tek sonuç kaldığında harita o şehre uçar.
- **Hover bilgi kutusu** (görsel alanı hazır) ve **tıkla detay kutusu** (yatay kaydırma yok).
- **Mobil uyumlu** — güvenli alan desteği, dinamik yükseklik (100dvh), 40–46px dokunma hedefleri.

## Veri
| | |
|---|---|
| Şehir | 133 |
| Olay | 712 |
| Âlim kaydı | 183 |
| Biyografi olayı | 240 (50 şehir) |

## Çalıştırma
Harita **Google Maps JavaScript API anahtarı** ister. Anahtar **depoya gömülmez**;
ilk açılışta istenir ve yalnızca tarayıcının `localStorage` alanında saklanır.

1. [Google Cloud Console](https://console.cloud.google.com/) → proje oluşturun.
2. **APIs & Services → Library** → *Maps JavaScript API* → etkinleştirin.
3. **Credentials → Create credentials → API key**.
4. Web sitesi kısıtı kullanacaksanız yayın alanını (örn. `*.github.io`) ekleyin.

Tek dosya olduğu için doğrudan açılabilir:

```bash
start index.html        # Windows
open  index.html        # macOS
```

## Güvenlik notu
Parola kilidi **istemci tarafıdır** (HTML/CSS/JS). İçeriği gizlemez, yalnızca meraklı
ziyaretçiyi durdurur. Gerçek gizlilik için sayfayı sunucu tarafı kimlik doğrulaması
arkasına alın. Depoda hiçbir API anahtarı tutulmaz.

## Lisans
Serbest kullanım.
