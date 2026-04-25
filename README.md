# football-simulator

## Android install note (including Samsung S24 FE)

The APK in this repository has been zip-aligned and re-signed for better compatibility with modern Android package installers (APK Signature Scheme v2/v3).

If you get **"There was a problem parsing the package"** during installation:

1. Re-download the APK (a partial/corrupt download can cause parse errors).
2. If an older app version is installed, uninstall it first (signature changed, so in-place update may fail).
3. Install from local device storage after download.
4. Ensure install permission from unknown sources is enabled.

If the app still crashes on startup, share device model + Android version + error screen/logcat.

## Android kurulum notu (Samsung S24 FE dahil)

Bu repodaki APK, modern Android sürümleriyle uyumluluk için yeniden hizalanıp (zipalign) yeniden imzalandı (APK Signature Scheme v2/v3).

Eğer kurulumda **“paket ayrıştırmasında sorun oldu”** hatası alırsanız:

1. APK dosyasını yeniden indirin (bozuk indirme parse hatası üretebilir).
2. Telefonda eski sürüm yüklüyse kaldırın (imza değiştiği için üzerine kurulamaz).
3. Dosyayı cihazın yerel depolamasına indirip oradan kurun.
4. Bilinmeyen kaynaklardan yüklemeye izin verin.

Uygulama açılışında crash devam ederse cihaz modeli + Android sürümü + hata ekranı/logcat paylaşın.
