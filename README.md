# Kelime Atölyesi sitesi

Uygulamanın gizlilik politikası, kullanım koşulları ve destek sayfaları. GitHub Pages yayınlıyor:
https://vizierson.github.io/kelime-atolyesi/

| Sayfa | Dosya | Adres |
|---|---|---|
| Gizlilik Politikası | `gizlilik.md` | /gizlilik/ |
| Kullanım Koşulları | `kosullar.md` | /kosullar/ |
| Destek | `destek.md` | /destek/ |

- İletişim e-postası, veri sorumlusu ve "son güncelleme" tarihi tek yerde: `_config.yml`.
- Sayfayı GitHub'da açıp kalem simgesiyle düzenleyebilirsin; kaydettikten 1-2 dakika sonra site güncellenir.
- Adresler uygulamada `uygulama/lib/ortak/baglantilar.dart` içinde; sayfa adı değişirse orası da değişmeli.
- `takvim.json`: uygulamanın çektiği ÖSYM sınav takvimi (https://vizierson.github.io/kelime-atolyesi/takvim.json).
  Kaynağı uygulama deposunda `icerik/takvim.json`; `python3 araclar/uygulama_icerigi.py` çalıştırınca oluşan
  `uygulama/assets/icerik/takvim.json` buraya aynen kopyalanır. Uygulama `guncelleme` tarihi kendi kopyasından
  eski olan takvimi kullanmaz; her değişiklikte `guncelleme` ilerletilmeli.
