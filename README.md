# ETAM v6 — SMP Negeri 10 Samarinda

Platform web terpadu untuk manajemen kegiatan, presensi, dokumentasi, dan administrasi ekstrakurikuler SMP Negeri 10 Samarinda.

## Struktur

- `index.html` — aplikasi utama / layanan password & log
- `pages/arsip-kegiatan.html` — jurnal kegiatan & papan pengumuman
- `pages/geotag-peta.html` — geotag/peta dan dokumentasi lokasi
- `pages/kegiatan.html` — modul kegiatan
- `pages/presensi-dashboard.html` — dashboard presensi
- `pages/presensi.html` — presensi sesi
- `pages/presensi-verifikasi.html` — hasil verifikasi presensi
- `pages/layanan-password.html` — layanan password
- `pages/arsip-lengkap.html` — arsip terpadu
- `DESIGN.md` — design system ETAM v6

## Menjalankan

Tidak membutuhkan build step untuk versi statis ini.

1. Upload seluruh folder ke repository GitHub.
2. Buka **Settings → Pages**.
3. Pilih branch utama dan folder `/ (root)`.
4. Simpan, lalu buka URL GitHub Pages yang diberikan GitHub.

## Catatan

Versi ini mempertahankan modul-modul unik dari beberapa rancangan yang diberikan, sementara aset dan fondasi visual ETAM v6 tetap konsisten. Integrasi Google Sheets/Drive/Apps Script tetap memerlukan endpoint/backend yang sesuai jika ingin data benar-benar tersimpan ke layanan eksternal.
