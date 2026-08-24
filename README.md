# Pemulihan joinkuliner.com

Cadangan statis ini dibuat dari snapshot publik sebelum batas aman **20251011**.

- URL unik ditemukan: 2337
- File berhasil dipulihkan: 2310
- File gagal dipulihkan: 25
- File dikarantina karena terindikasi konten tidak terkait: 2

## Memasang di GitHub Pages

1. Buat satu repositori publik baru di GitHub.
2. Salin **isi folder ini** ke root repositori, bukan folder induknya.
3. Commit dan push seluruh file.
4. Buka **Settings → Pages**.
5. Pada **Build and deployment**, pilih **Deploy from a branch**.
6. Pilih branch `main`, folder `/ (root)`, lalu simpan.
7. Website akan tersedia di `https://USERNAME.github.io/NAMA-REPO/`.

Semua tautan internal dibuat relatif agar dapat digunakan pada domain bawaan GitHub Pages.
Formulir, login, pencarian WordPress, komentar, checkout, dan database tidak dapat berfungsi pada website statis.

Lihat `_recovery/manifest.csv` untuk daftar sumber setiap file.
