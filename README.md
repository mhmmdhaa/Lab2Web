# Lab2Web - Praktikum 2 HTML Lanjutan

Repository ini berisi hasil pengerjaan Praktikum 2: HTML Lanjutan untuk mata kuliah Pemrograman Web.

## Daftar Isi
1. [Deskripsi Proyek](#deskripsi-proyek)
2. [Struktur Direktori](#struktur-direktori)
3. [Fitur yang Diimplementasikan](#fitur-yang-diimplementasikan)
4. [Tugas dan Jawaban Pertanyaan](#tugas-dan-jawaban-pertanyaan)

## Deskripsi Proyek
Proyek mini berupa halaman **Biodata Mahasiswa** (`index.html`) yang menggabungkan seluruh materi HTML lanjutan. Halaman ini dirancang menggunakan Semantic HTML dan memuat tabel data, elemen multimedia (audio & video), serta form registrasi/update data dengan validasi dasar.

## Struktur Direktori
```text
Lab2Web/
├── index.html        (Halaman utama / Biodata Mahasiswa)
├── media/            (Folder penyimpanan file multimedia)
│   ├── audio.mp3     
│   └── video.mp4     
└── README.md         (Dokumentasi praktikum ini)
```

## Fitur yang Diimplementasikan (Checklist Praktikum)
- [x] Tabel berhasil ditampilkan dan memiliki header yang sesuai (`<thead>`, `<tbody>`).
- [x] Form memiliki label terhubung dan berbagai jenis input (`text`, `email`, `number`).
- [x] Radio button dan checkbox sudah digunakan.
- [x] Select box (dropdown) dan textarea telah diterapkan.
- [x] Validasi form (`required`, `minlength`, `min`, `max`) sudah diujicoba.
- [x] Semantic HTML (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`) digunakan secara tepat.
- [x] Elemen `<audio>` dan `<video>` ditambahkan *(Screenshot dapat ditambahkan di sini setelah di-push ke repo)*.

## Tugas dan Jawaban Pertanyaan

1. **Fungsi tabel:** `<table>` (membungkus tabel), `<tr>` (baris), `<th>` (sel header/judul kolom), `<td>` (sel data biasa).
2. **Perbedaan `<th>` dan `<td>`:** `<th>` digunakan untuk header sehingga teks otomatis tebal dan di tengah, sedangkan `<td>` untuk data reguler.
3. **Fungsi colspan:** Menggabungkan dua atau lebih kolom menjadi satu sel.
4. **Fungsi `<form>`:** Wadah untuk mengumpulkan input atau data dari pengguna lalu mengirimkannya ke server.
5. **Perbedaan radio button & checkbox:** Radio button hanya mengizinkan 1 pilihan dari sebuah grup, sedangkan checkbox mengizinkan banyak pilihan sekaligus.
6. **Fungsi atribut `for` pada `<label>`:** Mengikat label dengan input yang memiliki `id` yang sama, sehingga jika label diklik, input tersebut otomatis menjadi fokus.
7. **Perbedaan `<textarea>` & `<input type="text">`:** Textarea digunakan untuk input teks panjang multi-baris (seperti alamat), sedangkan tipe teks hanya satu baris.
8. **Fungsi Semantic HTML:** Memberikan makna atau konteks terstruktur pada elemen web sehingga lebih mudah dipahami oleh mesin pencari (SEO) dan perangkat pembaca layar (accessibility).
9. **Validasi:** `required` (wajib isi), `min` (batas angka minimum), `max` (batas angka maksimum), `minlength` (minimal jumlah karakter).
10. **Perbedaan audio dan video:** `<audio>` khusus untuk memutar suara/musik tanpa visual, `<video>` memutar berkas visual bergerak berserta suaranya.

---
*Praktikum disusun oleh: Nur Muhammad Baha (Universitas Pelita Bangsa)*
