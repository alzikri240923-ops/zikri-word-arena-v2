ZIKRI WORD ARENA V2.5 - CLASSIC CROSSWORD

Perubahan:
- Gameplay diganti menjadi TTS silang dengan kotak mendatar dan menurun yang saling berpotongan.
- Bank soal awal berisi 121 petunjuk Bahasa Indonesia.
- Papan TTS dibuat acak pada setiap pertandingan.
- Riwayat soal Solo disimpan per profil di browser.
- Riwayat soal Multiplayer disimpan per profil di server.
- Saat riwayat soal habis, sistem memulai siklus baru.
- Mode Solo tidak menambah skor leaderboard.
- Multiplayer tetap menggunakan Socket.IO, room, timer, chat, dan leaderboard.

Jalankan di Termux:
  npm install
  npm start

Buka http://localhost:3000

Catatan: Riwayat Solo mengikuti profil/browser yang digunakan. Riwayat Multiplayer tersimpan di data/players.json pada server. Data server dalam memori (room aktif) tetap hilang jika proses server dihentikan.


V2.7 UPDATE
- Kontrol volume efek suara 0-150% di toolbar game; default 130%.
- Pengaturan volume tersimpan di browser perangkat.
- Efek suara diperkuat dan durasinya sedikit diperpanjang.


V2.9 UPDATE — BERANDA & MENU TERPISAH
- Beranda diubah menjadi halaman sambutan, pengenalan game, detail gameplay, dan pesan untuk pemain.
- Tombol mulai Solo, buat room, dan gabung room dipusatkan di menu Mode.
- Form nama pemain dan identitas akun dipindahkan ke menu Profil.
- Leaderboard dipindahkan ke halaman Peringkat tersendiri.
- Menu Panduan ditambahkan langsung ke navigasi utama.
- Navigasi responsif untuk layar ponsel dan desktop.
- Login Google belum diaktifkan; profil lokal dan sistem multiplayer yang sudah ada tetap digunakan.
