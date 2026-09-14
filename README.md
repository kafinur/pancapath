# PancaPath v9 — Sumber Belajar + PancaQuest

Versi v9 mengintegrasikan sumber belajar dan permainan digital ke dalam PancaPath tanpa mengubah integrasi Form A dan Form B.

## Sumber belajar terintegrasi
Folder `resources/` berisi:
- `materi-pancasila-kelas-viii.pptx`
- `video-kepribadian-bangsa.mp4`
- `lkpd-pancapath.pdf`
- `buku-pkn-kelas-viii.pdf`

Video menggunakan `preload="none"` sehingga tidak dimuat saat landing page dibuka.

## PancaQuest
PancaQuest terdiri dari 4 misi:
1. **Detektif Nilai** — memilih sila yang sesuai.
2. **Radar Perilaku** — mengklasifikasikan perilaku.
3. **Ruang Musyawarah** — memilih solusi paling sesuai Pancasila.
4. **Builder Aksi** — merancang tindakan, pelaksana, waktu, dan indikator keberhasilan.

PancaQuest baru terbuka setelah siswa lulus checkpoint pada jalur hasil asesmen. Setelah PancaQuest selesai, Misi Bersama terbuka.

## Gamifikasi
- XP maksimum 100.
- Progress bar animatif.
- Streak.
- Petunjuk adaptif.
- Animasi kartu, radar scan, feedback benar/salah, trophy, dan confetti.
- Badge hasil:
  - Pancasila Explorer
  - Value Detective
  - Civic Problem Solver
  - Pancasila Pathfinder

## Alur v9
Beranda → Tujuan → Sumber Belajar → Identitas → Asesmen Awal → Jalur Adaptif → Checkpoint → PancaQuest → Misi Bersama → Asesmen Akhir → Refleksi → Form B → Selesai.

## Upload GitHub Pages
Upload **seluruh isi ZIP** ke root repository, termasuk folder:
- `assets/`
- `resources/`

File video berukuran sekitar 11 MB dan masih berada di bawah batas ukuran file GitHub biasa. Pastikan upload selesai sebelum commit.

## Pengujian
1. Cek empat kartu Sumber Belajar.
2. Pastikan video hanya dimuat setelah tombol Tonton Video ditekan.
3. Uji tiga jalur adaptif.
4. Lulus checkpoint.
5. Pastikan PancaQuest terbuka.
6. Selesaikan 4 misi.
7. Pastikan Misi Bersama terbuka.
8. Pastikan Form A dan B tetap berjalan.
9. Uji reset peserta baru.
