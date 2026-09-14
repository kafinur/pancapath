# PancaPath v9.1 — PancaQuest + Form B Terintegrasi

Versi ini melanjutkan PancaPath v9 dan menambahkan sinkronisasi hasil PancaQuest ke Google Form B.

## Integrasi baru Form B
- **Skor PancaQuest** → `entry.717118100`
- **Badge PancaQuest** → `entry.1724061796`

Data dikirim otomatis dari hasil game yang tersimpan di perangkat:
- `quest.xp` → Skor PancaQuest
- `quest.badge` → Badge PancaQuest

Siswa tidak perlu mengetik ulang skor atau badge.

## Badge yang digunakan
- 🌱 Pancasila Explorer
- 🔎 Value Detective
- 💡 Civic Problem Solver
- 🏅 Pancasila Pathfinder

## Alur data
Asesmen Awal → Jalur Adaptif → Checkpoint → PancaQuest → Misi Bersama → Asesmen Akhir → Refleksi → Form B → Google Sheets.

## Catatan
Form B hanya dapat dibuka dari PancaPath setelah:
1. PancaQuest selesai,
2. Misi Bersama tersimpan,
3. Asesmen akhir C4–C6 tersimpan,
4. Refleksi tersimpan.

## Pengujian yang direkomendasikan
Gunakan satu peserta uji. Setelah PancaQuest selesai, lanjutkan sampai Form B lalu pastikan:
- nama benar,
- kode benar,
- skor asesmen awal benar,
- jalur benar,
- Skor PancaQuest terisi otomatis,
- Badge PancaQuest terisi otomatis,
- jawaban C4–C6 dan refleksi tetap terisi.
