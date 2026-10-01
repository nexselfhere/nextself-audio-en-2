# nextself-audio-en-2

NextSelf uygulamasının İngilizce B1+ ders sesleri — anahtarı 8…f ile başlayan kayıtlar (dilin sesleri nextself-audio-en · nextself-audio-en-2 depolarına bölünmüştür). Uygulama bu dosyaları tek tek indirir
(`en/<ilk iki hex>/<anahtar>.mp3`, mono mp3); anahtar, seslendirilen metnin
sha1 özetinin ilk 16 hanesidir.

## Ses modeli ve lisans

- **Kokoro-82M** (hexgrad) — Apache 2.0 — https://huggingface.co/hexgrad/Kokoro-82M

Kayıtlar bu ses modeliyle üretilmiştir; metinler NextSelf müfredatına aittir.

## Doğrulama

`SHA256SUMS.txt` tüm dosyaların özetini taşır: `shasum -c SHA256SUMS.txt`
