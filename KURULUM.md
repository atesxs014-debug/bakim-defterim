# Bakım Defterim: APK ve IPA kurulumu

Bu klasör, uygulamanın Android (APK) ve iPhone (IPA) projesidir. Derlemeyi GitHub senin yerine ücretsiz yapar.

## 1. GitHub'a yükle (bir kez)

1. github.com'da sağ üstten **New repository** de. Adı: `bakim-defterim`. **Public** seç (Actions dakikaları sınırsız olur). Oluştur.
2. Açılan sayfada **uploading an existing file** bağlantısına tıkla.
3. Bu zip'in içindeki **tüm dosya ve klasörleri** (`.github` klasörü dahil) sürükleyip bırak. **Commit changes** de.
   - `.github` klasörü görünmüyorsa: bilgisayarda gizli dosyaları göster ya da GitHub Desktop ile yükle. Bu klasör olmazsa derleme başlamaz.
4. Üstteki **Actions** sekmesine gir. "APK ve IPA derle" çalışmaya başlar. Yaklaşık 10–15 dakika sürer.

## 2. İndir

Derleme bitince depo sayfasının sağındaki **Releases** bölümünde iki dosya olur:

- `BakimDefterim.apk` (Android)
- `BakimDefterim.ipa` (iPhone)

Kalıcı indirme linki: `https://github.com/KULLANICI_ADIN/bakim-defterim/releases/latest`

## 3. Telefona kur

**Android:** APK'yı telefonda indir ve aç. "Bilinmeyen kaynaklardan yüklemeye izin ver" uyarısı çıkarsa izin ver.

**iPhone:** Apple imzasız uygulamayı doğrudan kurdurmaz.
1. Bilgisayara **Sideloadly** kur (Windows veya Mac).
2. iPhone'u kabloyla bağla, IPA'yı Sideloadly'ye sürükle, Apple ID'ni yaz, **Start** de.
3. iPhone'da Ayarlar > Genel > VPN ve Cihaz Yönetimi'nden kendi Apple ID'ne güven.
4. Ücretsiz Apple ID ile uygulama 7 günde bir yenilenmeli (Sideloadly ile tekrar yükle). Yıllık 99$ Apple Developer hesabıyla bu sınır kalkar.

## Güncelleme

`www/index.html` dosyasını değiştirip GitHub'a yüklediğinde yeni APK ve IPA otomatik derlenir.

## Veriler

- Araçlar, bakım kayıtları ve fotoğraflar sadece telefonda saklanır. Uygulamayı silersen veriler de silinir.
- Teknik bilgiler (motor, güç, tork, depo, tüketim vb.) internetten, CarQuery açık araç veritabanından çekilir. Bu veritabanında yağ, triger ve lastik bilgisi yok; bunları uygulamada Aracım > Düzenle'den bir kez girersin.
