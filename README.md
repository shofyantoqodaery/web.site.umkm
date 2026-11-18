# 🐟 Website UMKM Ikan Segar Bersih

Landing page satu halaman untuk usaha penjualan ikan segar siap masak (Patin, Lele, dan Gurame) yang menyasar pelaku UMKM seperti warung makan, catering, dan rumah makan. Pemesanan dilakukan langsung lewat WhatsApp, sehingga tidak memerlukan sistem keranjang atau backend.

## Tentang Proyek

Banyak UMKM kuliner masih membeli bahan baku ikan secara manual ke pasar. Website ini membantu penjual mempromosikan produknya secara online: menampilkan jenis ikan, harga grosir, paket langganan, dan cara order yang mudah, dengan tombol pesan langsung ke WhatsApp.

## Fitur

- **Hero section** berisi headline, badge keunggulan, tombol order WhatsApp, dan ringkasan statistik usaha
- **Keunggulan layanan**: ikan bersih siap masak, harga langsung tambak, stok harian, garansi segar, dan kemitraan jangka panjang
- **Katalog produk**: Ikan Patin, Lele, dan Gurame lengkap dengan harga per kg, minimum order, dan opsi potongan
- **Testimoni pelanggan** dari warung, catering, dan rumah makan
- **Paket harga**: Paket Makanan Kecil, Paket Catering & Rumah Makan, dan Paket Event & Arisan
- **FAQ interaktif** (accordion) seputar kesegaran, pembayaran, ongkir, dan garansi
- **Tombol WhatsApp melayang** yang selalu terlihat di layar
- **Tampilan responsif** untuk HP, tablet, dan desktop
- **Mode gelap otomatis** mengikuti pengaturan perangkat (`prefers-color-scheme`)
- **Animasi scroll reveal** dan smooth scroll antar bagian halaman
- **SEO dasar**: meta description dan atribut bahasa `id`

## Teknologi

- HTML5
- CSS3 (CSS variables, Grid, Flexbox, animasi)
- JavaScript (vanilla): IntersectionObserver, accordion FAQ, smooth scroll
- Font: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) via Google Fonts

Tidak ada framework, library tambahan, maupun proses build.

## Struktur Proyek

```
web.site.umkm/
├── ipo.html      # Halaman utama (HTML, CSS, dan JS dalam satu file)
└── README.md     # Dokumentasi proyek
```

## Cara Menjalankan

1. Clone repositori:
   ```bash
   git clone https://github.com/shofyantoqodaery/web.site.umkm.git
   ```
2. Masuk ke folder proyek:
   ```bash
   cd web.site.umkm
   ```
3. Buka file `ipo.html` langsung di browser, atau jalankan server lokal, misalnya:
   ```bash
   python -m http.server 8000
   ```
   lalu buka `http://localhost:8000/ipo.html`.

## Kustomisasi

Sebelum dipublikasikan, sesuaikan bagian berikut di `ipo.html`:

| Bagian | Yang perlu diubah |
| --- | --- |
| Nomor WhatsApp | Ganti semua tautan `wa.me/...` dengan nomor aktif (format `62xxxxxxxxxx`) |
| Nomor telepon | Ubah tautan `tel:` dan teks kontak di bagian CTA |
| Harga & minimum order | Edit pada bagian produk dan paket harga |
| Foto produk | Ganti atribut `src` gambar dengan foto asli ikan dan lokasi usaha |
| Testimoni & statistik | Isi dengan data pelanggan dan angka usaha yang sebenarnya |
| Sosial media & lokasi | Ganti tautan Instagram dan Google Maps di footer |
| Warna tema | Ubah variabel warna di blok `:root` pada CSS |

## Deploy

Karena berupa situs statis, website ini bisa dipublikasikan gratis melalui GitHub Pages, Netlify, atau Vercel. Untuk GitHub Pages, pastikan file utama bernama `index.html` agar terbuka otomatis di alamat dasar situs.

## Kontribusi

Saran dan perbaikan sangat diterima. Silakan buka *issue* atau kirim *pull request*.

## Lisensi

Tentukan lisensi sesuai kebutuhan, misalnya [MIT](https://choosealicense.com/licenses/mit/).

## Kontak

Dikembangkan oleh **Shofyanto Qodaery**.
