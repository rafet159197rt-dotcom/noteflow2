# NoteFlow — Android APK Kurulum Rehberi

## 📱 APK İndirmek İçin Adımlar

### 1. GitHub'a Yükle
1. **github.com** adresine git, giriş yap
2. Sağ üstteki **+** → **New repository** tıkla
3. Repository adı: `noteflow` yaz
4. **Public** seç
5. **Create repository** tıkla

### 2. Dosyaları Yükle
1. Oluşturulan sayfada **"uploading an existing file"** linkine tıkla
2. Bu ZIP içindeki **TÜM dosyaları** sürükle bırak
   - `www/` klasörü
   - `.github/` klasörü  
   - `package.json`
   - `capacitor.config.ts`
3. **Commit changes** butonuna tıkla

### 3. APK Build Et
1. Repository sayfasında üstteki **Actions** sekmesine tıkla
2. Sol tarafta **"Build NoteFlow APK"** görünecek
3. Sağ tarafta **"Run workflow"** butonuna tıkla → **"Run workflow"** onayla
4. ⏳ **5-8 dakika** bekle (yeşil tik çıkana kadar)

### 4. APK İndir
1. Actions sayfasında tamamlanan build'e tıkla
2. Altta **"Artifacts"** bölümünde **"NoteFlow-APK"** görünecek
3. Tıkla → ZIP indir → ZIP içindeki **app-debug.apk** dosyasını al

### 5. Tablette Yükle
1. APK'yı tablette aç
2. **"Bilinmeyen kaynaklardan yükleme"** izni iste — **İzin Ver**
3. Yükle → **NoteFlow** uygulaması ana ekranda!

---

## ⚡ Neden APK Daha İyi?

| | Chrome HTML | APK |
|---|---|---|
| Performans | Orta | Native GPU |
| Tam ekran | Hayır | ✅ Evet |
| Dosya erişimi | Sınırlı | ✅ Geniş |
| Arka planda | Hayır | ✅ Evet |
| Ana ekran ikonu | Manuel | ✅ Otomatik |

---

## 🔄 Güncelleme

HTML'yi değiştirip `www/index.html` dosyasını GitHub'a yeniden yükle → Actions otomatik yeni APK üretir.
