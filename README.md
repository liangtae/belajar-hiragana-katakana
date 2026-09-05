# belajar-hiragana-katakana
🌸 Aplikasi flashcard interaktif untuk belajar Hiragana &amp; Katakana, lengkap dengan animasi kelopak sakura, mode gelap/terang, dan fitur manajemen data penuh (CRUD). Dibuat sebagai satu file HTML mandiri — tidak perlu instalasi, tidak perlu server, tinggal dibuka di browser.

# 🌸 Sakura Kartu — さくらカード

**Aplikasi flashcard interaktif untuk belajar Hiragana & Katakana**, lengkap dengan animasi kelopak sakura, mode gelap/terang, dan fitur manajemen data penuh (CRUD). Dibuat sebagai satu file HTML mandiri — tidak perlu instalasi, tidak perlu server, tinggal dibuka di browser.

![status](https://img.shields.io/badge/status-active-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)
![type](https://img.shields.io/badge/type-single--file%20app-ff8fab)

---

## ✨ Fitur

- **208 kartu bawaan** — seluruh suku kata Hiragana & Katakana: gojūon (dasar), dakuten/handakuten, dan yōon (kombinasi seperti kya, sha, cha, dst).
- **CRUD lengkap** — tambah, lihat, ubah, dan hapus kartu, termasuk membuat kartu custom sendiri.
- **Mode Belajar** — flashcard dengan animasi flip 3D, navigasi maju/mundur, acak (shuffle), dan progress bar.
- **Mode Kelola** — tampilan grid semua kartu untuk edit/hapus/favorit secara cepat.
- **Pencarian & filter** — cari berdasarkan karakter, romaji, atau catatan; filter berdasarkan skrip (Hiragana/Katakana), kategori, dan status favorit.
- **Sortir** — A-Z, Z-A, berdasarkan karakter, atau terbaru ditambahkan.
- **Favorit** — tandai kartu yang ingin difokuskan untuk dihafal.
- **Ekspor & Impor JSON** — simpan progres/kartu custom dan muat kembali kapan saja.
- **Ekspor Excel (.xlsx)** — unduh daftar kartu untuk dicetak atau diolah lebih lanjut.
- **Cetak / PDF** — cetak daftar kartu dalam format tabel rapi lewat dialog print browser.
- **Mode terang & gelap** dengan palet warna bertema sakura (pink untuk Hiragana, biru kehijauan untuk Katakana agar mudah dibedakan).
- **Reset pengaturan** dan **reset semua data** — masing-masing dengan konfirmasi agar aman dari klik tidak sengaja.
- **Notifikasi toast** untuk setiap aksi (tambah, ubah, hapus, ekspor, impor, dll).
- Animasi kelopak sakura berjatuhan di latar belakang untuk nuansa yang lebih hidup.

## 🖥️ Cara Menggunakan

1. Unduh atau clone repo ini.
2. Buka file `sakura-kartu.html` langsung di browser (Chrome, Firefox, Edge, Safari).
3. Mulai belajar di tab **Belajar**, atau kelola kartu di tab **Kelola**.
4. Gunakan ikon **⋮** di pojok kanan atas untuk ekspor/impor data, cetak, atau reset.

Tidak ada proses build, tidak ada dependensi yang perlu diinstal — cukup satu file HTML.

> **Catatan:** Aplikasi ini tidak menyimpan data secara permanen di browser. Setiap perubahan (kartu baru, favorit, dll) hanya tersimpan selama sesi berjalan. Gunakan fitur **Ekspor JSON** secara berkala untuk menyimpan progresmu, lalu **Impor JSON** untuk memuatnya kembali di kunjungan berikutnya.

## 🗂️ Struktur Proyek

```
sakura-kartu/
├── sakura-kartu.html   # Aplikasi utama (HTML + CSS + JS, satu file)
├── README.md           # Dokumen ini
└── LICENSE             # Lisensi MIT
```

## 🎨 Teknologi

- HTML5, CSS3 (animasi & tema terang/gelap murni CSS), JavaScript (vanilla, tanpa framework)
- [SheetJS (xlsx)](https://sheetjs.com/) — untuk fitur ekspor Excel, dimuat via CDN
- Google Fonts: [Shippori Mincho](https://fonts.google.com/specimen/Shippori+Mincho) & [Zen Maru Gothic](https://fonts.google.com/specimen/Zen+Maru+Gothic)

## 📚 Sumber Data

Data suku kata Hiragana dan Katakana disusun berdasarkan tabel resmi *Suku Kata Jepang* dari [NHK WORLD-JAPAN](https://www.nhk.or.jp/lesson/id/).

## 🤝 Kontribusi

Kontribusi sangat terbuka! Beberapa ide pengembangan lebih lanjut:

- Audio pengucapan untuk setiap karakter
- Mode kuis pilihan ganda
- Statistik progres belajar per kategori
- Dukungan penyimpanan lokal (localStorage / IndexedDB) di luar konteks web app builder

Silakan buat _issue_ atau _pull request_ jika ingin menambahkan fitur atau memperbaiki bug.

## 📄 Lisensi

Proyek ini dirilis di bawah [Lisensi MIT](LICENSE) — bebas digunakan, dimodifikasi, dan dibagikan.

---

Dibuat dengan 🌸 untuk siapa pun yang sedang belajar huruf Jepang.
