# Soyle web sayfası

Bu klasör sadece herkese açık web dosyalarını içerir. Uygulama kaynak kodunu bu depoya yüklemeyin.

## GitHub arayüzünden yükleme

1. ZIP’i açın. `soyle-web` klasörünün içine girin.
2. `appsoyle/soyle` deposunda Add file → Upload files seçin.
3. `index.html`, `privacy` klasörü ve `README.md` dosyasını sürükleyin. Dıştaki `soyle-web` klasörünü veya ZIP’i yüklemeyin.
4. `privacy/index.html` klasör yapısının korunduğunu kontrol edin. Commit changes ile kaydedin.
5. `.nojekyll` gizli dosyasını göstermek için Finder’da Command + Shift + . tuşlarına basın; onu da yükleyin. Alternatif olarak GitHub’da Add file → Create new file ile `.nojekyll` adlı dosya oluşturun; boş kaydedilemiyorsa tek satır boşluk yeterlidir. Bu sade HTML sayfaları `.nojekyll` olmadan da çalışabilir.
6. Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: / (root) → Save.
7. Yayın tamamlanınca https://appsoyle.github.io/soyle/privacy/ adresini açın. GitHub ilk yayının 10 dakikaya kadar sürebileceğini belirtir.

## Uygulama ve App Store Connect

Uygulamanın Ayarlar bölümüne Privacy Policy / Gizlilik Politikası bağlantısı ekleyin. App Store Connect → App Privacy → Privacy Policy URL alanına aynı adresi girin:
https://appsoyle.github.io/soyle/privacy/

Ana sayfa / destek: https://appsoyle.github.io/soyle/

## Metnin dayanağı

Politika, paylaşılan Soyle 0.9.5 (16) kaynak dökümüne göre hazırlanmıştır. Çalışan uygulama üzerinde ağ trafiği doğrulaması yapılmamıştır. Yayınlanacak sürüme analitik, reklam, sunucu veya veri eşzamanlama özellikleri eklendiyse metni güncelleyin. Destek e-postalarının saklama süresi koddan belirlenemez; otomatik silme süresi taahhüt edilmemiştir. Bu metin tüm ülkelerin mevzuatına uygunluk garantisi değildir.

Sayfalar harici font, JavaScript, analitik ve çerez kodu içermez. GitHub Pages’in kendi IP günlükleri politikada açıklanır.
