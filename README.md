# AxoNews

AxoNews adalah portal berita statis yang bersih, modern, responsif, dan ringan, terinspirasi dari situs berita besar seperti CNN, Kompas, dan BBC – namun dirancang lebih optimal, aman, dan mudah untuk dikembangkan.

## Fitur Utama

- **Responsive Design**: Tampil optimal di semua perangkat (mobile, tablet, desktop).
- **Clean & Modern UI**: Tampilan minimalis, nyaman dibaca, dan terstruktur rapi.
- **Optimized & Fast**: CSS dan gambar dioptimasi untuk kecepatan muat maksimal.
- **Dark/Light Mode**: Pilihan mode tampilan dapat diatur di menu Setting.
- **Sidebar Widgets**: Berita Populer, Newsletter, Widget Cuaca (dummy).
- **Berita Headline, Trending, Terbaru, Pilihan Editor**.
- **Tag Cloud** dan **Kategori Populer** untuk filter berita.
- **Share Button** (Twitter, WhatsApp, Copy Link).
- **Komentar (Dummy), Pagination, Breadcrumbs, Banner, Loader**.
- **Aksesibilitas**: Ukuran font dapat diubah, kontras warna baik, skip link, dsb.
- **Keamanan**: Tidak ada data sensitif, link eksternal aman, kode sudah dioptimasi.
- **SEO Friendly**: Meta tag dan struktur semantik sudah diterapkan.

## Cara Pakai

1. **Clone repo ini**  
   ```
   git clone https://github.com/AMillionDriver/axonews.git
   cd axonews
   ```

2. **Buka `index.html` di browser**  
   Tidak memerlukan server lokal, cukup klik dua kali file `index.html`.

3. **Edit Konten**  
   - Ubah berita, gambar, dan link sosial media di file `index.html`.
   - Untuk custom style atau script, edit pada `css/style.css` dan `js/main.js` (jika sudah dipisah).

4. **Deploy ke GitHub Pages**  
   - Push ke branch utama.
   - Aktifkan GitHub Pages dari Settings repo, pilih branch utama dan folder root.

5. **Optimasi Lebih Lanjut (Opsional)**
   - Lakukan minify pada CSS/JS jika ingin performa maksimal.
   - Gunakan [Netlify](https://www.netlify.com/) atau [Vercel](https://vercel.com/) untuk deploy gratis dan cepat.

## Struktur Direktori

```
/
|- index.html
|- css/
   |- style.css
|- js/
   |- main.js
|- img/
|- README.md
|- LICENSE
|- SECURITY.md
```

## Kontribusi

- Silakan fork dan pull request jika ingin berkontribusi.
- Tidak boleh memasukkan credential/API key/secret.
- Semua PR akan direview untuk keamanan dan kualitas kode.

## Keamanan

- Tidak terdapat backend, data sensitif, atau API key.
- Semua form dan komentar hanya dummy (tidak mengirim data).
- Selalu gunakan branch protection di repo public.
- Detail keamanan baca di [SECURITY.md](./SECURITY.md).

## Lisensi

[MIT License](./LICENSE)

---

Dibangun dengan ❤️ oleh [AxoNews Team](https://github.com/AMillionDriver).
