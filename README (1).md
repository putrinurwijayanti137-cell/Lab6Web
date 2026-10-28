# Lab6Web — JavaScript DOM dan Event Handling

## 1. Tujuan Praktikum

Praktikum ini bertujuan mempelajari penggunaan JavaScript DOM (*Document Object Model*) dan *Event Handling* untuk membuat halaman web interaktif. Materi yang dipelajari meliputi perubahan elemen HTML, pengaturan gaya CSS, penanganan event, penghitung karakter, validasi formulir, serta pembuatan daftar tugas.

## 2. Struktur File

```text
lab6_dom_event/
├── index.html
├── style.css
├── script.js
├── README.md
└── image/
    ├── eksperimen-sembunyi-tampil
    ├── latihan-1-2-dom-click
    ├── latihan-1-2-dom-click2
    ├── latihan-3-gaya-css
    ├── latihan-4-penghitung-karakter
    ├── latihan-5-email-tidak-valid
    ├── latihan-5-nama-kosong
    └── latihan-6-tambah-selesai-hapus
```

Keterangan:
- `index.html`: struktur halaman web.
- `style.css`: pengaturan tampilan halaman web.
- `script.js`: kode JavaScript untuk DOM dan event handling.
- `README.md`: dokumentasi proyek dan hasil praktikum.
- `image/`: tempat penyimpanan screenshot hasil praktikum.

## 3. Cara Menjalankan

1. Buka folder proyek `lab6_dom_event` di Visual Studio Code.
2. Pastikan file `index.html`, `style.css`, dan `script.js` berada dalam folder yang sama.
3. Pastikan file HTML sudah terhubung dengan CSS dan JavaScript.
4. Buka `index.html` melalui browser atau gunakan Live Server.
5. Jalankan setiap latihan dengan mencoba tombol, kolom input, dan formulir.
6. Periksa Console pada Developer Tools jika terjadi kesalahan.

## 4. Langkah Kerja

1. Membuat struktur HTML, CSS, dan JavaScript.
2. Mengubah judul dan paragraf menggunakan DOM.
3. Menambahkan event klik untuk memperbarui pesan.
4. Mengubah tampilan teks menggunakan `classList`.
5. Membuat penghitung karakter pada kolom input.
6. Menguji validasi formulir dengan nama kosong dan email tidak valid.
7. Membuat daftar tugas yang dapat ditambah, ditandai selesai, dan dihapus.
8. Membuat tombol untuk menyembunyikan dan menampilkan paragraf.
9. Menjalankan pengujian dan menyimpan screenshot hasil praktikum.

## 5. Screenshot dan Penjelasan Hasil

### 5.1 Eksperimen Sembunyi dan Tampil

![Eksperimen Sembunyi dan Tampil](image/eksperimen-sembunyi-tampil.png)

Screenshot ini menunjukkan penggunaan tombol untuk menyembunyikan dan menampilkan kembali paragraf. Program menggunakan `addEventListener()` untuk menangani klik dan `classList.toggle()` untuk mengubah class CSS pada elemen.

### 5.2 Latihan 1–2 — DOM dan Event Klik

![Latihan 1-2 DOM Click](image/latihan-1-2-dom-click.png)

Screenshot ini menunjukkan perubahan judul dan isi paragraf menggunakan DOM. Elemen dipilih dengan `getElementById()`, kemudian teksnya diubah menggunakan `textContent`. Latihan ini membuktikan bahwa JavaScript dapat mengubah isi halaman web.

### 5.3 Latihan 1–2 — Pengujian Tambahan

![Latihan 1-2 DOM Click 2](image/latihan-1-2-dom-click2.png)

Screenshot ini mendokumentasikan pengujian event klik pada tombol. Saat tombol ditekan, pesan pada halaman diperbarui dengan waktu saat tombol diklik. Fungsi tersebut menggunakan `addEventListener()` dengan event `click`.

### 5.4 Latihan 3 — Mengubah Gaya CSS

![Latihan 3 Gaya CSS](image/latihan-3-gaya-css.png)

Screenshot ini menunjukkan perubahan tampilan paragraf menggunakan `classList.toggle()`. Class `highlight` mengatur warna teks, latar belakang, garis tepi, dan padding, sedangkan class `teks-besar` mengubah ukuran teks.

### 5.5 Latihan 4 — Penghitung Karakter

![Latihan 4 Penghitung Karakter](image/latihan-4-penghitung-karakter.png)

Screenshot ini menunjukkan jumlah karakter yang berubah secara langsung ketika pengguna mengetik. Program menggunakan event `input` untuk mendeteksi perubahan teks dan `value.length` untuk menghitung jumlah karakter.

### 5.6 Latihan 5 — Email Tidak Valid

![Latihan 5 Email Tidak Valid](image/latihan-5-email-tidak-valid.png)

Screenshot ini menunjukkan pengujian validasi ketika alamat email tidak sesuai dengan format yang diharapkan. Program memeriksa email sebelum melanjutkan proses dan menampilkan pesan kesalahan apabila formatnya tidak valid.

### 5.7 Latihan 5 — Nama Kosong

![Latihan 5 Nama Kosong](image/latihan-5-nama-kosong.png)

Screenshot ini menunjukkan pengujian formulir ketika kolom nama belum diisi. Program menampilkan pesan bahwa nama wajib diisi sehingga pengguna mengetahui data yang masih perlu dilengkapi.

### 5.8 Latihan 6 — Tambah, Selesai, dan Hapus Tugas

![Latihan 6 Tambah Selesai Hapus](image/latihan-6-tambah-selesai-hapus.png)

Screenshot ini menunjukkan fitur daftar tugas (*to-do list*). Pengguna dapat menambahkan tugas, menandai tugas sebagai selesai, dan menghapus tugas. Program menggunakan `createElement()`, `appendChild()`, `classList.toggle()`, dan `remove()` untuk mengelola elemen daftar tugas.

## 6. Kesimpulan

Praktikum ini menunjukkan bahwa JavaScript dapat digunakan untuk mengakses dan mengubah elemen HTML melalui DOM. Penggunaan event handling memungkinkan halaman merespons tindakan pengguna, sedangkan `classList` membantu mengubah tampilan secara dinamis. Penghitung karakter, validasi formulir, dan daftar tugas juga memperlihatkan penerapan JavaScript dalam membangun fitur interaktif.

## 7. Catatan

Nama gambar pada bagian screenshot harus sesuai dengan nama file yang tersimpan di folder `image`. Jika nama file memiliki ekstensi seperti `.png` atau `.jpg`, sertakan ekstensi tersebut pada tautan gambar agar screenshot dapat ditampilkan di GitHub.
