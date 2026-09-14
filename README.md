# PancaPath v7 — Visual Edition / GitHub Ready

Versi v7 mempertahankan seluruh alur dan integrasi PancaPath v6, lalu menambahkan identitas visual baru.

## Pembaruan visual
- Logo PancaPath resmi pada navbar dan landing page.
- Favicon PancaPath.
- Hero section baru dengan ilustrasi peta belajar adaptif.
- Background ringan berbasis SVG dan CSS.
- Tiga kartu alasan utama: asesmen awal, jalur adaptif, tujuan bersama.
- Ikon visual pada tiga jalur belajar.
- Tata letak landing page lebih modern dan responsif.
- Semua aset visual lokal agar tidak bergantung pada CDN gambar.

## Aset ringan
Folder `assets/` berisi:
- `pancapath-logo.webp`
- `pancapath-mark.webp`
- `favicon.png`
- beberapa SVG ringan untuk ilustrasi dan dekorasi

Logo utama sudah dikompresi ke WebP untuk memperkecil beban halaman.

## Fungsi yang tetap dipertahankan
- Google Form A + Google Sheets
- asesmen awal otomatis
- tiga jalur adaptif
- checkpoint
- Misi Bersama
- asesmen akhir C4–C5–C6
- refleksi
- Google Form B + Google Sheets
- progress tracker
- halaman selesai
- badge Pancasila Pathfinder
- reset peserta baru

## Upload ke GitHub Pages
Upload seluruh isi ZIP ke root repository, termasuk folder `assets/`.

Pastikan struktur:
- index.html
- styles.css
- script.js
- README.md
- assets/

Jangan memindahkan file dalam folder `assets`, karena HTML mengacu pada path tersebut.
