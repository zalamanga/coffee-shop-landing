# Coffee Shop Landing

Latihan landing page kedai kopi dengan HTML, CSS, dan JavaScript. Halamannya memuat bagian beranda, cerita kedai, kartu produk, dan contoh ulasan. Gambar produk tersedia di dalam repo.

## Buka di komputer

Dari folder repo, jalankan server statis dengan Python 3:

```powershell
python -m http.server 8080 --bind 127.0.0.1
```

Buka http://127.0.0.1:8080. Hentikan server dengan Ctrl+C. Tidak ada paket npm atau database yang perlu dipasang.

## Isi dan perilaku

- `index.html`: bagian halaman dan kartu produk.
- `style.css`: tampilan desktop dan aturan layar kecil.
- `main.js`: buka/tutup menu dan kotak pencarian, tutup keduanya saat scroll, serta bayangan header.
- `about.jpg`, `bg.png`, `logo.png`, `main.png`, `p1.png` sampai `p6.png`, serta gambar lainnya: aset lokal di root repo.

Kotak pencarian hanya dapat dibuka dan ditutup; belum ada penyaringan produk. Ikon keranjang dan tautan produk masih bagian tampilan latihan, belum memiliki checkout. Teks ulasan dan harga adalah konten contoh pada sumber, bukan bukti pelanggan atau penawaran kedai aktif.

Ikon Boxicons dimuat dari CDN unpkg. Halaman dan gambar lokal tetap dapat dilayani tanpa proses build, sedangkan ikon memerlukan koneksi internet.

## Pemeriksaan

Pemeriksaan source pada 27 Oktober 2026: seluruh rujukan aset HTML/CSS lokal ditemukan dan 1 pemeriksaan syntax JavaScript (berkas atau blok inline) berhasil dengan `node --check`. Tautan anchor ke bagian halaman yang bernama juga ditemukan.

Pemeriksaan kode tidak menggantikan uji interaksi, keyboard, dan tampilan pada browser. Screenshot aplikasi belum dibuat.

## Asal materi

Source dan gambar dipertahankan dari proyek lokal Coffee Shop. Belum ditemukan berkas lisensi proyek atau identitas upstream yang dapat dikonfirmasi. Repo ini mendokumentasikan latihan yang sudah ada; tidak menetapkan kepemilikan baru atas template, gambar, atau Boxicons.
