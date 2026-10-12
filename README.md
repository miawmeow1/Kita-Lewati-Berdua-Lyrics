# 🌅 Life After Just Friends — Animated Lyrics

Tool pemutar lirik beranimasi (karaoke style) berbasis web, dibuat dengan **HTML, CSS, dan JavaScript** murni. Tanpa framework, tanpa instalasi, cukup buka di browser.

Dibuat untuk lagu **"Kita Lewati Berdua" – Overnight**, tapi bisa dipakai untuk lagu apa pun.

## ✨ Fitur

- **Efek karaoke**: baris yang sedang dinyanyikan terisi warna dari kiri ke kanan, layar bergulir otomatis mengikuti baris aktif.
- **Background foto fade in/out**: pilih beberapa foto, lalu foto berganti dengan efek crossfade yang halus.
- **Efek fajar**: cahaya di bagian bawah layar makin terang seiring lagu berjalan.
- **Pemutar lagu bawaan**: play/pause, slider posisi, dan klik baris untuk lompat ke bagian itu.
- **Dua mode timing**:
  - *Otomatis*: baris berganti tiap beberapa detik (bisa diatur).
  - *Manual*: pakai format waktu `[mm:ss.xx] lirik`.
- **Mode sinkron**: ketuk tiap baris saat dinyanyikan, waktu tersimpan otomatis dan bisa disalin.
- **Tema terang/gelap** dan tampilan responsif untuk HP.

## 🚀 Cara Pakai

1. Unduh atau clone repo ini.
2. Buka `index.html` di browser (atau jalankan lewat XAMPP / Live Server).
3. Di bagian **Lirik dan pengaturan**, tempel lirik (satu baris untuk satu kalimat).
4. Klik **Pilih file lagu** dan **Pilih foto latar** untuk memilih file dari perangkatmu.
5. Tekan tombol play.

### Sinkron dengan lagu

1. Pilih file lagu.
2. Nyalakan **Mode sinkron**, lalu tekan play.
3. Ketuk tombol (atau tekan `Spasi`) tepat saat tiap baris dinyanyikan.
4. Matikan Mode sinkron, lalu putar ulang dari awal.
5. Klik **Salin lirik + waktu** untuk menyimpan hasilnya.

Contoh format dengan waktu:

```
[00:12.50] contoh baris pertama
[00:17.20] contoh baris kedua
```

## 🗂️ Struktur

```
.
├── index.html   # semua kode: HTML, CSS, dan JavaScript
└── README.md
```

## 🛠️ Teknologi

| Bagian | Dipakai untuk |
| --- | --- |
| HTML | Struktur halaman dan input file |
| CSS | Animasi karaoke, crossfade foto, tema terang/gelap |
| JavaScript | Pemutar, penentuan baris aktif, mode sinkron |

## 🌐 Deploy ke GitHub Pages

1. Ubah nama `animated-lyrics.html` menjadi `index.html`.
2. Push ke GitHub.
3. Buka **Settings → Pages**, pilih branch `main` dan folder `/ (root)`.
4. Halaman akan tersedia di `https://username.github.io/nama-repo/`.

## 📌 Catatan

- **Lirik dan lagu tidak disertakan** dalam repo ini karena dilindungi hak cipta. Pengguna menempel lirik dan memilih file lagu sendiri.
- File lagu dan foto hanya dibaca di browser, tidak diunggah ke server mana pun.
- Pastikan kamu punya hak untuk memakai lagu dan foto yang dipilih.

## 👤 Pembuat

Dibuat oleh **An Nisaa Nurrahman**, mahasiswa Teknik Informatika.

## 📄 Lisensi

Kode dirilis di bawah lisensi [MIT](https://opensource.org/licenses/MIT). Lisensi ini hanya berlaku untuk kode, bukan untuk lirik atau lagu.
