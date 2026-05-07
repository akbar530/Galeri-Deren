# Galeri Deren

Website portofolio galeri GFX design milik **@derenxtrnlz** — menampilkan hasil karya desain dengan tampilan yang bersih dan estetik.

---

## ✨ Fitur

- **Halaman Tentang Saya** — profil singkat, bio, dan link sosial media
- **Galeri Karya** — grid 2 kolom yang menampilkan hasil GFX design
- **Lightbox** — klik gambar untuk melihat ukuran penuh
- **Music Player** — pemutar musik background dengan kontrol play, pause, skip, dan prev
- **Animasi** — efek awan mengambang, scroll reveal pada galeri, dan transisi halus antar halaman
- **Responsive** — tampilan menyesuaikan layar mobile dan desktop

---

## 🗂️ Struktur

```
index.html   ← satu file, semua HTML + CSS + JS di dalamnya
```

---

## 🚀 Cara Pakai

1. Download atau clone file `index.html`
2. Buka langsung di browser — tidak perlu server atau instalasi apapun

---

## 🎨 Kustomisasi

### Ganti Foto Profil
Cari baris berikut dan ganti URL-nya:
```html
<img class="about-photo" src="URL_FOTO_KAMU" alt="Foto Profil">
```

### Tambah / Ganti Karya di Galeri
Tambahkan blok berikut di dalam `<div class="gallery-grid">`:
```html
<div class="gallery-item">
  <img src="URL_GAMBAR_KAMU" alt="Karya">
  <div class="overlay-icon">🔍</div>
</div>
```

### Ganti Musik
Edit array `playlist` di bagian script:
```js
const playlist = [
  { name: 'Nama Lagu', src: 'URL_MUSIK.mp3' },
];
```

### Ganti Link Sosial Media
Cari bagian `.social-links` dan `.gallery-footer`, lalu ubah atribut `href` sesuai akun kamu.

---

## 🛠️ Teknologi

- HTML5, CSS3, Vanilla JavaScript
- Google Fonts — [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) & [DM Sans](https://fonts.google.com/specimen/DM+Sans)
- CSS Grid & Flexbox
- Backdrop Filter / Glassmorphism

---

## 👤 Author

**Deren** — [@derenxtrnlz](https://www.instagram.com/drnalvrprtm)

> *"Masih belajar, kalau kurang bagus wajar 😄"*
