---
title: Modul 3.1 - Dasar Pengeditan Halaman Elementor
created: 2026-09-01
updated: 2026-09-01
tags:
  - sop
  - gitbook
  - modul-3
  - elementor
  - page-builder
sources:
  - https://garudakaryateknik.com
related:
  - "[[Garuda Karya Teknik]]"
---

# Modul 3.1: Panduan Dasar Pengeditan Visual Elementor di GKT

Website garudakaryateknik.com dibangun menggunakan arsitektur Elementor.

---

## 3.1.1 Cara Membuka Mode Visual Editor

### Opsi 1: Dari Bilah Atas Halaman Website
1. Login ke dashboard admin terlebih dahulu.
2. Kunjungi halaman depan `https://garudakaryateknik.com/`.
3. Pada bilah hitam admin bar di bagian atas layar, klik tulisan **Edit with Elementor** (pilih `Home` untuk mengedit isi halaman beranda, atau pilih `Header / Footer` untuk mengedit navigasi).

### Opsi 2: Dari Menu Dashboard
1. Buka menu **Pages** -> **All Pages**.
2. Arahkan mouse ke halaman `Home` -> klik **Edit with Elementor**.

---

## 3.1.2 Memahami Tata Letak Halaman Utama (Homepage Anatomy)

Halaman beranda GKT terdiri dari beberapa seksi kontainer utama:

```text
+-------------------------------------------------------------+
| 1. HERO SECTION                                             |
|    "Build Beyond Value."                                    |
|    Tombol CTA: [ View Selected Projects ] [ Discuss Project ]|
+-------------------------------------------------------------+
| 2. OUR DELIVERY PROCESS (4 Pilar Manajemen)                 |
|    - Project Management  - Quality Control                  |
|    - Cost Control        - Schedule Management              |
+-------------------------------------------------------------+
| 3. SELECTED WORKS (Widget Loop Grid -> Sumber: CPT Projects)|
|    - Otomatis menampilkan proyek terbaru dari menu Projects |
|    - Tombol: [ VIEW ALL PROJECTS ] -> /projects-archive     |
+-------------------------------------------------------------+
| 4. OUR CAPABILITIES (6 Kotak Layanan Terintegrasi)          |
|    - Design & Build | Build Construction | Fit-Out          |
|    - Procurement & PM | MEP Smart Building | Civil          |
+-------------------------------------------------------------+
| 5. CONTACT & CONSULTATION FOOTER                            |
|    Form Kontak + Tombol WA: 0821 2864 4561                  |
+-------------------------------------------------------------+
```

---

## 3.1.3 Aturan Keamanan Pengeditan Visual GKT

> [!danger] Perhatian Staf Pengelola
> 1. **Widget Selected Works Bekerja Otomatis**: Seksi *Selected Works* menggunakan widget *Loop Grid* yang otomatis menarik data dari menu **Projects**. Anda tidak perlu menambahkan kotak proyek secara manual di Elementor; cukup buat proyek baru di menu **Projects**, dan foto beserta judulnya akan otomatis muncul di sini.
> 2. **Jangan Mengubah Lebar Container (Padding 6%)**: Tata letak website diatur dengan padding presisi 6%. Cukup klik pada widget teks, gambar, atau ikon untuk mengubah isinya tanpa mengubah konfigurasi layout kontainer pembungkus.
> 3. **Wajib Menekan Tombol UPDATE**: Setelah melakukan perubahan, tombol Update  harus ditekan agar perubahan tersimpan ke publik.
