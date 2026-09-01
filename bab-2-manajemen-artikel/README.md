---
title: Modul 2.1 - SOP Input Portofolio Proyek (Custom Post Type)
created: 2026-09-01
updated: 2026-09-01
tags:
  - sop
  - gitbook
  - modul-2
  - project-cpt
  - portofolio
sources:
  - https://garudakaryateknik.com
related:
  - "[[Garuda Karya Teknik]]"
---

# Modul 2.1: SOP Input Portofolio Proyek (Menu Projects)

Portofolio hasil karya Garuda Karya Teknik dikelola secara terpisah melalui **Custom Post Type: Projects**. Proyek yang diterbitkan di sini akan otomatis tampil pada grid *Selected Works* di halaman Beranda dan halaman katalog *Projects Archive* (`https://garudakaryateknik.com/projects-archive`).

---

## 2.1 Format Standar Portofolio Proyek GKT

Setiap publikasi proyek baru memuat informasi teknis terstruktur:

```text
+-------------------------------------------------------------+
| CONTOH STRUKTUR PORTOFOLIO PROYEK GKT                       |
|                                                             |
| Judul Proyek : Coffee Shop Fit-Out                          |
| Slug URL     : fit-out-interior-project                     |
| Kategori     : Interior                                     |
| Featured Img : Foto Utama Tampak Depan (16:9)               |
|                                                             |
| [ Narasi Deskripsi Proyek & Tantangan Konstruksi ]          |
| [ Foto Dokumentasi Utama Resolusi Penuh ]                   |
| [ Blok Galeri Kolom Foto Detail Interior / Fit-Out ]        |
+-------------------------------------------------------------+
```

---

## 2.2 Prosedur Langkah Demi Langkah Menambah Proyek Baru

### Langkah 1: Membuka Menu Projects
1. Pada menu bilah kiri dashboard, klik menu **Projects** -> klik **Add New Project** (Tambah Proyek Baru).

---

### Langkah 2: Mengisi Judul dan Deskripsi Proyek
1. **Judul Proyek (Title)**: Masukkan nama proyek yang jelas dan profesional (contoh: `Coffee Shop Fit-Out`, `Classic House Renovation`, atau `Studio Apartment Fit-Out`).
2. **Paragraf Deskripsi Pembuka**:
   - Jelaskan konsep desain, fungsi bangunan, dan tujuan bisnis/hunian dari proyek tersebut.
3. **Penyisipan Galeri Foto Dokumentasi**:
   - Tekan `Enter`, klik tombol `+` (Tambah Blok) -> pilih blok **Gallery (Galeri)**.
   - Unggah foto-foto detail pengerjaan (custom furniture, pencahayaan, finishing lantai/dinding).
   - Atur pengaturan galeri pada bilah kanan menjadi **Columns: 2** atau **Columns: 3** agar tata letak foto tampil seimbang dan rapi.
4. **Paragraf Penutup (Quality Control)**:
   - Tuliskan ringkasan peran PT Garuda Karya Teknik sebagai kontraktor pelaksana, dan hasil akhir proyek.

---

### Langkah 3: Menentukan Gambar Sampul (Featured Image)
Gambar sampul ini adalah foto yang ditarik secara otomatis oleh widget *Loop Grid* di halaman depan website.

1. Di bilah pengaturan sebelah kanan (tab **Project**), gulir ke bawah ke seksi **Featured Image**.
2. Klik **Set featured image**.
3. Unggah foto terbaik proyek (rasio 16:9 atau 4:3, resolusi 1200 x 800 px, ukuran di bawah 250 KB dalam format `.webp` atau `.jpg`).
4. Klik tombol **Set featured image**.

---

### Langkah 4: Memilih Kategori Proyek
1. Pada bilah kanan (tab **Project**), buka seksi **Categories**.
2. Centang kategori proyek yang sesuai:
   - `[x] Interior` (untuk proyek kafe, apartemen, kantor)
   - `[x] House Renovation` (untuk renovasi rumah tinggal)
   - `[x] Room Renovation` (untuk renovasi ruang khusus)
   - `[x] Interior Apartment Studio` (untuk unit apartemen)

---

### Langkah 5: Pengaturan Yoast SEO
1. Gulir ke bawah ke kotak **Yoast SEO**:
   - **Focus Keyphrase**: Masukkan kata kunci pencarian (contoh: `jasa interior kafe bogor`).
   - **Meta Description**: Tulis 1-2 kalimat ringkas (maksimal 155 karakter) yang merangkum layanan proyek ini.

---

### Langkah 6: Publikasi dan Verifikasi
1. Klik tombol **Preview** -> **Preview in new tab** untuk memeriksa tampilan halaman proyek.
2. Jika format sudah rapi, klik tombol biru **Publish** dua kali.
3. Kunjungi `https://garudakaryateknik.com/[slug-project]` untuk memastikan proyek baru telah muncul.
