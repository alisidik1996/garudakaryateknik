---
title: Modul 1 - Login & Akses Dashboard
created: 2026-09-01
updated: 2026-09-01
tags:
  - sop
  - gitbook
  - modul-1
  - login
  - wordpress
sources:
  - https://garudakaryateknik.com
related:
  - "[[Garuda Karya Teknik]]"
---

# Modul 1: Login & Navigasi Dashboard WordPress GKT

Modul ini memandu staf administrator dan tim konten PT Garuda Karya Teknik dalam mengakses panel kontrol website secara aman serta memahami letak menu pengelolaan sistem.

---

## 1.1 Alamat URL Akses Admin

1. Buka peramban web (Google Chrome, Microsoft Edge, atau Safari).
2. Masukkan alamat URL login resmi:
   ```text
   https://garudakaryateknik.com/wp-admin
   ```
   (atau `https://garudakaryateknik.com/wp-login.php`).

---

## 1.2 Prosedur Masuk Akun

```text
+-------------------------------------------------------------+
|             Halaman Login garudakaryateknik.com             |
|                                                             |
|   Nama Pengguna / Email : [ admin@garudakaryateknik.com   ] |
|   Kata Sandi            : [ **********************        ] |
|                                                             |
|   [ ] Ingat Saya                                            |
|                                 [ Tombol: Masuk / Log In ]  |
+-------------------------------------------------------------+
```

1. Masukkan Username atau Email resmi akun admin.
2. Masukkan Password akun.
3. Klik tombol Log Masuk (Log In).
4. Setelah terverifikasi, sistem akan mengarahkan ke Dashboard WordPress Utama.

> [!warning] Standar Keamanan Akun GKT
> - Gunakan kata sandi yang kuat (kombinasi huruf besar, huruf kecil, angka, dan simbol).
> - Dilarang membagikan kredensial akun admin kepada pihak ketiga tanpa persetujuan pimpinan.
> - Hindari mencentang opsi "Ingat Saya" jika menggunakan perangkat bersama.

---

## 1.3 Navigasi Menu Backend Utama GKT

Berdasarkan struktur arsitektur WordPress PT Garuda Karya Teknik, berikut adalah pemetaan menu kerja yang digunakan:

1. **Projects (Custom Post Type)**:
   - Menu khusus untuk mengelola portofolio proyek konstruksi, fit-out, dan renovasi yang tampil pada halaman *Selected Works* di Beranda dan *Projects Archive* (`/projects-archive`).
2. **Posts (Pos / Artikel)**:
   - Menu untuk mengunggah artikel berita korporat, wawasan teknik, dan pengumuman umum.
3. **Media**:
   - Pustaka penyimpanan foto arsitektur, banner, gambar galeri proyek, dan logo perusahaan.
4. **Pages (Laman)**:
   - Mengelola halaman statis utama:
     - `Home` (Halaman Beranda Utama)
     - `Projects Archive` (Halaman Katalog Semua Proyek)
5. **Elementor & Header Footer Elementor (HFE)**:
   - Pengaturan tata letak visual halaman dan navigasi menu header/footer.
6. **Elementor Submissions**:
   - Memantau pesan dan formulir penawaran masuk dari calon klien (*Schedule Consultation*).

---

## 1.4 Prosedur Keluar Akun (Logout)

Setelah selesai melakukan pembaruan konten:
1. Arahkan kursor ke pojok kanan atas layar (Halo, [Nama Anda]).
2. Klik tombol Keluar (Log Out).
