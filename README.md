# ElaraDeck sürümleri

ElaraDeck masaüstü uygulamasının (Windows) kurulum dosyaları ve sürüm notları.

- **İndir:** [son sürüm](https://github.com/mburakerbay/elaradeck-release/releases/latest) → `ElaraDeck_<sürüm>_x64-setup.exe`
- **Güncelleme:** Kurulu uygulama yeni sürümleri buradan kendisi denetler. Ayarlar'da "Yeni uygulama sürümü mevcut" çıkınca "Hemen yükle" ile indirip kurar; "Yeniliklere bak" o sürümün notlarını açar. Ayarlar ve profiller korunur.
- **Cihaz yazılımı:** Her kurulum dosyası o sürümün cihaz yazılımını da taşır. Cihazdaki sürüm eskiyse uygulama "Yeni cihaz yazılımı sürümü mevcut" der ve uygulamadan yükler.

Kurulum dosyası imzasızdır; Windows SmartScreen ilk açılışta uyarabilir ("Ek bilgi" → "Yine de çalıştır"). Güncellemeler ayrıca uygulamanın kendi anahtarıyla imzalanır ve kurulmadan önce doğrulanır.

Kurulum dosyası, cihaz yazılımını yüklemek için Espressif'in [esptool](https://github.com/espressif/esptool) aracını içerir (GPLv2; lisansı kurulum klasöründe `cihaz-yazilimi/esptool-LICENSE.txt`).
