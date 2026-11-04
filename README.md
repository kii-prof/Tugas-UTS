# 📚 BookSpace - Online Book Store

Aplikasi web toko buku online sederhana berbasis **HTML, CSS, dan JavaScript** (tanpa backend). Data disimpan di `localStorage` browser sehingga tetap ada setelah halaman di-refresh.

## 📌 Informasi Project

| Keterangan | Isi |
|---|---|
| Nama Project | BookSpace - Online Book Store |
| Nama | Rizky Fauzan Sobari |
| NIM | 312510342
| Mata Kuliah | *(isi mata kuliah)* |
| Dosen Pengampu | *(isi nama dosen)* |
| Teknologi | HTML5, CSS3, JavaScript (Vanilla), localStorage |

## 🎥 Link Video YouTube

▶️ **[Klik di sini untuk menonton video presentasi project](https://youtu.be/oCyt4SrCHVA)**

> Ganti tautan di atas dengan link video YouTube Anda.

---

## 📖 Penjelasan Project

BookSpace adalah simulasi sistem pemesanan buku online. Pengguna dapat masuk ke akun, melihat katalog dan stok buku, menambah/menghapus data buku, memasukkan buku ke keranjang, membuat pesanan (checkout), melacak pengiriman berdasarkan Nomor Delivery Order (DO), serta melihat riwayat transaksi.

### Fitur Utama

- **Login, Daftar Akun, dan Lupa Password** (modal pada halaman login)
- **Dashboard** dengan sapaan sesuai waktu (Pagi/Siang/Sore/Malam), ringkasan transaksi, dan history transaksi
- **Katalog / Informasi Stok** dalam bentuk kartu dan tabel, plus form tambah buku dan tombol hapus
- **Pemesanan** dengan keranjang, ubah jumlah, validasi stok, dan form data pemesan
- **Tracking Pengiriman** berdasarkan Nomor DO dengan progress bar status
- **Logout** dengan konfirmasi
- Proteksi halaman: pengguna yang belum login otomatis diarahkan ke halaman login

### Struktur Folder

```
BookSpace/
├── index.html          # Halaman login
├── dashboard.html      # Dashboard
├── stok.html           # Katalog & stok buku
├── checkout.html       # Pemesanan
├── tracking.html       # Tracking pengiriman
├── css/
│   └── style.css       # Styling seluruh halaman
├── js/
│   ├── data.js         # Data pengguna, katalog, tracking, localStorage
│   └── script.js       # Logika aplikasi
├── ASSETS/
│   └── logo.jpeg       # Logo BookSpace
├── IMG/                # Gambar sampul buku
├── screenshots/        # Tangkapan layar untuk README
└── README.md
```

### Akun Demo

| Nama | Email | Password |
|---|---|---|
| Rina Wulandari | rina@gmail.com | rina123 |
| Agus Pranoto | agus@gmail.com | agus123 |
| Siti Marlina | siti@gmail.com | siti123 |

### Nomor DO untuk Uji Tracking

- `20230012` (Rina Wulandari, JNE)
- `20230013` (Agus Pranoto, Pos Indonesia)

### Cara Menjalankan

1. Clone atau unduh repository ini.
2. Buka file `index.html` di browser (atau gunakan ekstensi *Live Server* di VS Code).
3. Login memakai salah satu akun demo di atas.


## 🛠️ Teknologi yang Digunakan

- **HTML5** untuk struktur halaman
- **CSS3** (Flexbox, Grid, responsive) untuk tampilan
- **JavaScript** untuk logika aplikasi dan manipulasi DOM
- **localStorage** untuk penyimpanan data di browser

## 📄 Lisensi

Project ini dibuat untuk keperluan tugas perkuliahan.

© 2026 BookSpace - Online Book Store
