---
title: Modul 2.2 - Pengelolaan Kategori Proyek & Artikel
created: 2026-09-01
updated: 2026-09-01
tags:
  - sop
  - gitbook
  - modul-2
  - kategori
  - database
sources:
  - https://garudakaryateknik.com
related:
  - "[[Garuda Karya Teknik]]"
---

# Modul 2.2: Pengelolaan Kategori Proyek di Database GKT

Sistem klasifikasi kategori pada backend PT Garuda Karya Teknik membedakan antara kategori portofolio fisik (**Projects**) dan kategori wawasan tulisan (**Posts / Artikel**).

---

## 2.2.1 Daftar Kategori Aktif di Database Website

Berikut adalah daftar kategori resmi yang telah terdaftar di database WordPress GKT:

| Nama Kategori (*Category Name*) | Slug URL | ID Database | Penggunaan Utama |
|---|---|---|---|
| **Interior** | `interior` | ID: 16 | Portofolio interior komersial, kafe, dan perkantoran |
| **House Renovation** | `house-renovation` | ID: 12 | Portofolio renovasi rumah tinggal dan bangunan residensial |
| **Interior Apartment Studio** | `interior-apartment-studio` | ID: 13 | Portofolio khusus unit apartemen dan hunian kompak |
| **Room Renovation** | `room-renovation` | ID: 14 | Portofolio renovasi kamar tidur, dapur, atau ruang spesifik |
| **Artikel** | `artikel` | ID: 10 | Berita perusahaan, artikel edukasi teknik, dan pengumuman |

---

## 2.2.2 Menambah Kategori Proyek Baru

Jika PT Garuda Karya Teknik memperluas cakupan portofolio (misalnya proyek gedung industri atau pabrikasi):

1. Pada menu dashboard kiri, buka **Projects** -> klik **Categories** (atau buka **Posts** -> **Categories** jika untuk artikel).
2. Di formulir sebelah kiri:
   - **Name**: Masukkan nama kategori baru (contoh: `Commercial & Office Building`).
   - **Slug**: Masukkan format URL ramah mesin pencari (contoh: `commercial-office-building`).
   - **Parent Category**: Pilih None (atau pilih kategori induknya).
   - **Description**: Penjelasan singkat cakupan proyek (opsional).
3. Klik tombol biru **Add New Category**.

---

## 2.2.3 Panduan Penerapan Kategori yang Tepat

> [!tip] Aturan Taksonomi GKT
> 1. **Satu Kategori Utama per Proyek**: Pastikan setiap proyek minimal memiliki 1 kategori spesifik (contoh: proyek kafe menggunakan kategori `Interior`, proyek rumah tinggal menggunakan `House Renovation`).
> 2. **Hindari Kategori "Uncategorized"**: Jangan biarkan proyek tersimpan di bawah kategori bawaan *Uncategorized*.
