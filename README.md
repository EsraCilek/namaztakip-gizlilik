# Namaz Takip – Gizlilik Politikası

Bu depo, Namaz Takip uygulamasının App Store gizlilik politikası sayfası için kullanılır.

**Canlı URL (GitHub Pages açtıktan sonra):**  
`https://KULLANICI_ADINIZ.github.io/namaztakip-gizlilik/`

---

## GitHub Pages ile yayınlama adımları

### 1. GitHub’da yeni depo oluşturun

1. https://github.com/new adresine gidin.
2. **Repository name:** `namaztakip-gizlilik` (veya istediğiniz isim).
3. **Public** seçin, "Add a README" işaretlemeyin.
4. **Create repository** tıklayın.

### 2. Bu klasörü depoya yükleyin

**Seçenek A – GitHub web üzerinden:**

1. Yeni oluşan depoda **"uploading an existing file"** veya **"Add file" → "Upload files"** deyin.
2. `index.html` ve `.nojekyll` dosyalarını sürükleyip bırakın (bu klasörden).
3. **Commit changes** ile kaydedin.

**Seçenek B – Bilgisayarınızda Git ile:**

Terminal’de (bu klasörde değil, bir üst klasörde):

```bash
cd /Users/esracilek/Desktop/IOS/NamazTakip/gizlilik-yayinla
git init
git add index.html .nojekyll README.md
git commit -m "Gizlilik politikası sayfası"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/namaztakip-gizlilik.git
git push -u origin main
```

`KULLANICI_ADINIZ` yerine kendi GitHub kullanıcı adınızı yazın.

### 3. GitHub Pages’i açın

1. Depo sayfasında **Settings** (Ayarlar).
2. Sol menüden **Pages**.
3. **Source:** "Deploy from a branch" seçin.
4. **Branch:** `main`, **Folder:** `/ (root)` seçin.
5. **Save** deyin.

### 4. URL’yi alın

1–2 dakika sonra sayfa yayında olur. Adres:

```
https://KULLANICI_ADINIZ.github.io/namaztakip-gizlilik/
```

Bu adresi **App Store Connect → App Privacy → Privacy Policy URL** alanına yapıştırın.

---

**Not:** `index.html` içindeki `[E-posta adresinizi buraya yazın]` kısmını kendi e-postanızla değiştirmeyi unutmayın.
