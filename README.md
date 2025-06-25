# ✨ Igdl

[![HTML](https://img.shields.io/badge/language-HTML-blue.svg)](https://www.w3.org/html/)
[![NPM](https://img.shields.io/badge/npm-Node.js-brightgreen)](https://www.npmjs.com/)


> Igdl adalah pengunduh Instagram sederhana yang dibangun menggunakan HTML dan Node.js (melalui node-fetch).  Aplikasi ini memungkinkan pengguna untuk mengunduh media dari Instagram.

## ✨ Fitur Utama

* **Pengunduhan Media Instagram:** Igdl memungkinkan pengguna untuk mengunduh foto dan video dari Instagram dengan memasukkan URL postingan.
* **Antarmuka Pengguna Sederhana:** Meskipun detail antarmuka tidak sepenuhnya jelas dari informasi yang tersedia, dirancang untuk kemudahan penggunaan dan aksesibilitas yang tinggi.
* **Integrasi node-fetch:**  Menggunakan library node-fetch untuk melakukan permintaan HTTP ke API Instagram (tidak langsung, kemungkinan melalui API pihak ketiga atau scraping, yang perlu diverifikasi lebih lanjut).

## 🛠️ Tumpukan Teknologi

| Kategori        | Teknologi      | Catatan                                  |
|-----------------|-----------------|------------------------------------------|
| Bahasa Pemrograman | HTML            | Untuk antarmuka pengguna                 |
| Manajer Paket     | npm             | Untuk manajemen dependensi               |
| Library          | node-fetch      | Untuk melakukan permintaan HTTP           |


## 🏛️ Tinjauan Arsitektur

Arsitektur aplikasi saat ini tidak diketahui secara pasti.  Berdasarkan file yang tersedia, aplikasi ini kemungkinan besar bergantung pada pendekatan front-end sederhana dengan logika pengunduhan yang diimplementasikan melalui JavaScript (kemungkinan menggunakan node-fetch di sisi server atau dalam lingkungan browser).  Lebih banyak informasi dibutuhkan untuk deskripsi arsitektur yang lebih rinci.


## 🚀 Memulai

1. Kloning repositori:
   ```bash
   git clone https://github.com/Fiisya/igdl.git
   ```
2. Instal dependensi:
   ```bash
   npm install
   ```
3. Jalankan server pengembangan (asumsikan `npm run dev` adalah perintah yang tepat):
   ```bash
   npm run dev
   ```

## 📂 Struktur File

```
/
├── index.html
└── package.json
```

* **/:** Direktori root proyek.
* **index.html:** File HTML utama yang berisi antarmuka pengguna.
* **package.json:** Menentukan dependensi proyek dan skrip.

