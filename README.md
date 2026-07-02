# 🪵 Bara Nusantara — Landing Page Ekspor Briket Kelapa Premium

Sebuah landing page B2B (_single-file_) multibahasa (EN/ID) untuk bisnis ekspor briket arang batok kelapa. Dibuat sebagai portofolio front-end premium dengan estetika gelap/emas tanpa memerlukan proses _build step_.

**[Masukkan link demo / screenshot Vercel di sini nanti]**

## ✨ Fitur Utama

- **Multibahasa (EN/ID) Berbasis Client-Side i18n** — Menggunakan objek terpusat `languages`, atribut `data-i18n`, dan fungsi `switchLanguage()` untuk mengubah seluruh teks halaman secara instan tanpa perlu memuat ulang (_reload_) halaman.
- **Kalkulator Kontainer Interaktif** — Masukkan target berat pesanan dalam satuan metrik ton (MT) untuk mendapatkan estimasi instan jumlah kontainer 20ft (≤24 MT) dan 40ft HC (≤26 MT) yang dibutuhkan.
- **Integrasi WhatsApp Dinamis** — Tombol WhatsApp terapung dan tautan di footer secara otomatis menyusun template pesan penawaran pra-isi dalam bahasa yang sedang aktif.
- **Unduh Lembar Spesifikasi PDF** \*— Menghasilkan file PDF resmi untuk spesifikasi grade produk yang sedang dipilih secara langsung di sisi klien menggunakan library `jsPDF`.
- **Tab Spesifikasi Produk** — Memisahkan spesifikasi antara grade Shisha/Hookah vs. grade BBQ, lengkap dengan tabel data dinamis yang nilainya berubah otomatis sesuai tab yang dipilih.
- **Animasi Scroll-Reveal** — Menggunakan `IntersectionObserver` yang halus dan tetap menghormati preferensi aksesibilitas pengguna (`prefers-reduced-motion`).
- **Responsif Penuh** — Menggunakan HTML5 semantik, navigasi header _sticky_ dengan efek blur backdrop, serta menu mobile yang ramah pengguna.

## 🛠️ Teknologi yang Digunakan

- HTML5
- Tailwind CSS (Menggunakan CDN, konfigurasi di-extend langsung di dalam file untuk token warna dan font kustom)
- Vanilla JavaScript (Tanpa framework, tanpa perlu proses compile/build)
- [jsPDF](https://github.com/parallax/jsPDF) via CDN untuk generate PDF di sisi browser
- Google Fonts: Fraunces (untuk judul/display), Manrope (untuk teks utama), IBM Plex Mono (untuk data/tabel)

## 🚀 Cara Menjalankan Project Secara Lokal

Project ini tidak memerlukan proses instalasi atau _build step_—hanya satu file HTML utuh.

```bash
# Cukup buka langsung filenya
open index.html

# Atau jalankan menggunakan local server
npx serve .
```
