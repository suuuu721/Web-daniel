# albumfotodaniel — Portfolio Fotografer

Website portofolio satu halaman untuk Daniel, fotografer dengan tema hitam-putih editorial.

## Struktur

```
.
├── index.html      # seluruh halaman (HTML + CSS + JS dalam satu file)
├── images/         # foto-foto portofolio
└── README.md
```

## Menjalankan secara lokal

Tidak perlu build tool apa pun — cukup buka `index.html` langsung di browser,
atau jalankan server statis sederhana:

```bash
python3 -m http.server 8000
```

lalu buka `http://localhost:8000`.

## Push ke GitHub

```bash
git init
git add .
git commit -m "Initial commit: website portofolio albumfotodaniel"
git branch -M main
git remote add origin https://github.com/<username>/<nama-repo>.git
git push -u origin main
```

## Deploy gratis (opsional)

- **GitHub Pages**: Settings → Pages → pilih branch `main` → folder `/ (root)`.
- **Netlify / Vercel**: hubungkan repo, tidak perlu build command (situs statis).

## Mengganti atau menambah foto

1. Taruh file foto baru di folder `images/`.
2. Buka `index.html`, cari tag `<img class="ph" src="images/...">` di bagian
   galeri (`<div class="gallery">`), ganti `src` dan `alt` sesuai foto baru.
3. Ganti juga teks `<span class="cat">` (kategori) dan `<span class="title">`
   (judul foto) di baris `<figcaption>` yang sama.

## Kontak yang tertaut di situs

- Email: danielanlindra152@gmail.com
- WhatsApp: 0878-9788-4071
- Instagram: @albumfotodaniel
