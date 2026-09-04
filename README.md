# Blog Pribadi — Tugas Koding Komputer

Proyek blog pribadi sederhana yang dibuat untuk tugas koding komputer. Website ini di-hosting menggunakan **GitHub Pages**.

## ✅ Status

Website sudah aktif di: [https://nabilfp.github.io/tugas-kc-blog/](https://nabilfp.github.io/tugas-kc-blog/)

## Fitur

- **Halaman Home** — Menampilkan 3 postingan terbaru dengan visual modern
- **Halaman About** — Cerita tentang pembuat dan minat
- **Halaman Contact** — Formulir kontak
- **3 Artikel Detail** — Post1 (Bung Karno), Post2 (B.J. Habibie), Post3 (S.B. Yudhoyono)
- **Author Name Badge** — Nama tokoh ditampilkan dengan style box merah yang menonjol
- **Responsif** — Tampilan optimal di desktop dan mobile
- **Navigasi penuh** — Menu berpindah antar halaman di setiap halaman
- **Auto-deploy** — GitHub Actions workflow untuk deploy otomatis

## Teknologi

- HTML5 (semantic tags: header, nav, main, section, article, footer, blockquote)
- CSS3 (responsive design, flexbox, gradients, box-shadow)
- Google Fonts: **Inter** (body) & **Playfair Display** (heading)
- GitHub Pages (hosting)
- GitHub Actions (auto-deploy workflow)

## Struktur File

```
blog-pribadi/
├── index.html                  — Halaman utama (Home)
├── about.html                  — Halaman tentang (About)
├── contact.html                — Halaman kontak (Contact)
├── post1.html                  — Artikel: Selamat Datang di Blog Saya (Bung Karno)
├── post2.html                  — Artikel: Tentang Gaya Hidup Minimalis (B.J. Habibie)
├── post3.html                  — Artikel: Perjalanan Belajar Pemrograman (S.B. Yudhoyono)
├── style.css                   — Stylesheet utama
├── README.md                   — File ini
├── .github/
│   └── workflows/
│       └── deploy.yml          — GitHub Actions auto-deploy
└── images/                     — Folder gambar placeholder
    ├── hero-placeholder.png
    ├── post1-placeholder.png
    ├── post2-placeholder.png
    ├── post3-placeholder.png
    ├── about-placeholder.png
    └── contact-placeholder.png
```

## Pengembang

**Nabil Najwa Akmal** — 🎓 Tugas Koding Komputer

## Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/nabilfp/tugas-kc-blog.git
   cd tugas-kc-blog
   ```
2. Buka `index.html` di browser, atau lihat langsung di GitHub Pages.

## Hosting (GitHub Pages)

Website sudah aktif di GitHub Pages:

- URL: [https://nabilfp.github.io/tugas-kc-blog/](https://nabilfp.github.io/tugas-kc-blog/)
- Branch: `main`
- Otomatis deploy via GitHub Actions

### Cara deploy manual (jika diperlukan):
1. Buka **Settings** → **Pages** di repositori
2. Atur **Source** ke **Deploy from a branch**
3. Pilih **Branch: main**, folder **/ (root)**
4. Simpan — tunggu beberapa menit

## Lisensi

Proyek ini bersifat open source dan bebas digunakan.
