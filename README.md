# Rujukan Guru BM: Integrasi Tawhidic

Aplikasi web ringkas untuk guru Bahasa Melayu merujuk **Matriks Integrasi DSKP BM dengan Epistemologi Tawhidic & Quranic** (Prasekolah, Sekolah Rendah Tahun 1–6, Sekolah Menengah Tingkatan 1–5).

## Ciri
- Tapis mengikut peringkat, tahap, **Sifat 20**, **Asmaul Husna** dan carian teks. Sifat 20 dan Asmaul Husna diasingkan sepenuhnya.
- Klik pada nama Sifat 20 atau Asmaul Husna dalam kad untuk menapis semua baris yang berkaitan.
- **Bina RPH**: menjana draf tiga fasa (Set Induksi, Perkembangan, Penutup) daripada baris matriks. Draf boleh disunting, disalin atau dicetak.
- Berfungsi **luar talian**. Tiada pelayan, tiada pemasangan, tiada penjejakan, tiada fon atau skrip luar.

## Cara guna
Muat turun folder ini dan buka `index.html` dalam pelayar. Itu sahaja.

## Hos di GitHub Pages (percuma)
1. Cipta repositori baharu di GitHub dan muat naik semua fail.
2. Settings > Pages > Source: pilih cabang `main` dan folder `/ (root)`.
3. Alamat laman akan dipaparkan dalam beberapa minit.

## Kemas kini kandungan
Semua kandungan matriks berada dalam `data.js`. Setiap baris mempunyai format:

`[peringkat, tahap, tema/bab, tajuk, fokus, sifat 20, asmaul husna, ayat & sunnatullah, hasil]`

Lajur sifat 20 atau asmaul husna boleh dibiarkan kosong (`""`) jika belum ditetapkan.

Sunting atau tambah baris, simpan, dan muat semula pelayar. Tiada langkah binaan diperlukan.

## Struktur fail
- `index.html`: antara muka dan logik
- `data.js`: kandungan matriks
- `LICENSE`: lesen MIT untuk kod

## Menyumbang
Sumbangan dialu-alukan melalui *issue* dan *pull request*, terutamanya semakan kandungan oleh guru dan pakar agama, serta penambahan tahap atau subjek lain.

## Lesen dan kandungan
- **Kod**: MIT (lihat `LICENSE`). Gantikan `[NAMA PEMEGANG HAK CIPTA]` dengan nama anda.
- **Kandungan matriks**: pemilik kandungan perlu memilih lesen sendiri (contohnya CC BY-SA 4.0) dan menyatakannya di sini.

## Nota semakan kandungan
Kandungan berasal daripada dokumen asal dengan pindaan berikut:
- Nama Asmaul Husna dalam lajur Sifat 20 dipindahkan ke lajur Asmaul Husna.
- Nama yang tiada dalam senarai 99 nama yang biasa (Jamil, Shafi, Muhdith, Mudabbir) dibuang; “Raziq” diseragamkan kepada “Razzaq”.
- Sifat 20 dilengkapkan sebagai **cadangan** untuk baris yang tiada, dan ejaan diseragamkan (Baqa’, Wahdaniyyah).
- Terjemahan ringkas beberapa nama diperkemas; ejaan “darjat” dan “maqasid syariah” dibetulkan.
- Setiap perkara yang perlu disahkan ditandakan sebagai **Nota semakan** pada kad berkenaan. Sila minta pakar agama menyemak sebelum digunakan secara rasmi.
