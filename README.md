# Lab2Web.
Practical Report - Lab2Web (HTML Lanjutan)

Mata Kuliah: Pemrograman Web

Dosen Pengampu: Agung Nugroho

Institusi: Universitas Pelita Bangsa, Bekasi

📌 Deskripsi Singkat

Repositori ini berisi seluruh hasil latihan dan proyek mini pada Praktikum 2: HTML Lanjutan. Fokus utama praktikum ini adalah pemahaman dan penerapan komponen HTML tanpa mengandalkan CSS/JavaScript secara mendalam.

Materi yang dicakup dalam praktikum ini meliputi:

Tabel HTML (<table>, <tr>, <th>, <td>, <thead>, <tbody>, <tfoot>, colspan, dll)

Form HTML & Jenis Input (<form>, <input>, <label>, <textarea>, <select>, <button>)

Pilihan Input Khusus (Radio Button & Checkbox)

Validasi Form Dasar (required, minlength, maxlength, min, max)

Semantic HTML (<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>)

Multimedia HTML (<audio> dan <video>)

Proyek Mini: Form & Halaman Biodata Mahasiswa

📂 Struktur Direktori

Lab2Web/
├── index.html        # Halaman utama latihan HTML Lanjutan
├── biodata.html      # Proyek mini: Halaman Biodata & Form Mahasiswa
├── media/            # Folder berkas multimedia
│   ├── audio.mp3     # Berkas audio pendukung
│   └── video.mp4     # Berkas video pendukung
└── README.md         # Dokumentasi laporan praktikum


🚀 Langkah-Langkah Praktikum

Persiapan Lingkungan Kerja

Membuka Text Editor (Visual Studio Code).

Membuat folder kerja utama Lab2Web.

Membuat folder media/ dan menambahkan file audio.mp3 serta video.mp4.

Membuat Tabel Data Mahasiswa & Struktur Tabel Lengkap

Menyusun tabel HTML sederhana untuk menyajikan NIM, Nama, dan Program Studi.

Mengembangkan struktur tabel menggunakan elemen semantic tabel: <thead>, <tbody>, dan <tfoot> serta menerapkan penggabungan kolom (colspan).

Membuat Form Registrasi & Jenis Input

Menerapkan tag <form> dan <label> dengan atribut for yang terhubung ke id elemen input.

Menggunakan berbagai jenis <input> seperti text, email, password, date, radio, dan checkbox.

Menambahkan elemen <select> untuk dropdown Program Studi dan <textarea> untuk alamat.

Penerapan Validasi Form Dasar

Menambahkan atribut validasi HTML5 bawaan seperti required, minlength, min, dan max pada elemen input form.

Penerapan Semantic HTML

Menyusun tata letak halaman yang terstruktur rapi menggunakan elemen <header>, <nav>, <main>, <section>, <article>, <aside>, dan <footer>.

Menambahkan Multimedia

Mengintegrasikan pemutar media audio dan video menggunakan tag <audio controls> dan <video controls>.

Proyek Mini (Halaman Biodata Mahasiswa)

Membuat file biodata.html yang menggabungkan seluruh konsep: struktur Semantic HTML, tampilan data dalam tabel, form pendaftaran/biodata lengkap dengan validasi dasar, serta elemen multimedia.

📸 Dokumentasi & Hasil Tampilan Browser

(Catatan: Silakan ganti path/tautan gambar berikut sesuai dengan screenshot file Anda di direktori)

1. Tampilan Tabel & Form Registrasi

2. Tampilan Validasi Form & Element Semantic

3. Tampilan Halaman Biodata (Proyek Mini)

❓ Jawaban Pertanyaan Praktikum

Apa fungsi <table>, <tr>, <th>, dan <td>?

<table>: Berfungsi sebagai kontainer utama untuk membuat struktur tabel.

<tr> (Table Row): Berfungsi untuk mendefinisikan baris di dalam tabel.

<th> (Table Header): Berfungsi untuk membuat sel judul/header pada kolom yang dicetak tebal dan rata tengah secara bawaan.

<td> (Table Data): Berfungsi untuk mengisi sel data biasa dalam baris tabel.

Apa perbedaan <th> dan <td>?

<th> digunakan khusus untuk header/judul kolom (teks tebal dan centered).

<td> digunakan untuk penulisan data standar pada tabel (teks normal dan rata kiri secara bawaan).

Apa fungsi colspan pada tabel?

colspan digunakan untuk menggabungkan dua atau lebih kolom secara horizontal menjadi satu sel.

Apa fungsi <form> dalam HTML?

Tag <form> berfungsi sebagai wadah penampung berbagai jenis penampung input pengguna (seperti input teks, tombol, checkbox) yang dapat dikirimkan ke server untuk diproses.

Apa perbedaan radio button dan checkbox?

Radio Button (type="radio"): Memungkinkan pengguna hanya memilih satu opsi dari sekelompok pilihan (dengan atribut name yang sama).

Checkbox (type="checkbox"): Memungkinkan pengguna untuk memilih beberapa/banyak opsi sekaligus atau tidak memilih sama sekali.

Mengapa <label> sebaiknya terhubung dengan id input melalui atribut for?

Menghubungkan <label for="id_input"> meningkatkan aksesibilitas (memudahkan screen reader) dan usabilitas pengguna (klik pada teks label akan otomatis memfokuskan atau mengaktifkan elemen input terkait).

Apa perbedaan <textarea> dengan <input type="text">?

<input type="text"> hanya menerima input teks satu baris.

<textarea> memungkinkan pengguna memasukkan teks banyak baris (multi-line) dengan dimensi baris dan kolom yang bisa diatur.

Apa fungsi semantic HTML seperti <header>, <nav>, <main>, <section>, <article>, <aside>, dan <footer>?

Tag semantic memberikan makna/arti yang jelas bagi browser dan mesin pencari (SEO) mengenai struktur dan peran isi halaman web tersebut:

<header>: Bagian kepala/header halaman atau artikel.

<nav>: Area menu navigasi/tautan utama.

<main>: Area konten utama yang unik dari halaman.

<section>: Kelompok/bagian konten yang bertema sama.

<article>: Konten mandiri yang berdiri sendiri (misal: postingan berita).

<aside>: Konten pendamping/sampingan (sidebar).

<footer>: Bagian kaki halaman berisi hak cipta atau informasi kontak.

Apa fungsi required, min, max, dan minlength?

required: Memaksa pengguna mengisi kolom input sebelum form disubmit.

min: Menentukan nilai angka/tanggal minimum yang diizinkan.

max: Menentukan nilai angka/tanggal maksimum yang diizinkan.

minlength: Menentukan panjang minimal karakter teks yang harus dimasukkan.

Apa perbedaan elemen <audio> dan <video>?

<audio> digunakan khusus untuk memutar berkas media suara/musik.

<video> digunakan untuk memutar berkas video/pergerakan visual yang juga dilengkapi area proyeksi layar visual di browser.
