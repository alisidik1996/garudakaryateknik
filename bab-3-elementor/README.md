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

# 🎨 Modul 3.1: Panduan Dasar Pengeditan Visual Elementor di GKT

Website **garudakaryateknik.com** dibangun dengan arsitektur modern menggunakan **Elementor Pro** dan **Header Footer Elementor (HFE)** dengan font tipografi kustom **Montserrat & Gotham** serta palet warna korporat emas-navy.

---

## 3.1.1 Cara Membuka Mode Visual Editor

### Opsi 1: Dari Bilah Atas Halaman Website (Rekomendasi)
1. Login ke admin dashboard terlebih dahulu.
2. Buka halaman depan `https://garudakaryateknik.com/`.
3. Pada bilah admin hitam di bagian paling atas layar, klik tulisan **Edit with Elementor** (pilih `Home` untuk mengedit isi halaman beranda, atau pilih `Header / Footer` untuk mengedit menu navigasi).

### Opsi 2: Dari Menu Dashboard
1. Buka **Pages** $\rightarrow$ **All Pages**.
2. Arahkan mouse ke halaman `Home - Garuda Karya Teknik` $\rightarrow$ klik **Edit with Elementor**.

---

## 3.1.2 Memahami Tata Letak Halaman Utama (*Homepage Anatomy*)

Halaman beranda GKT terdiri dari beberapa seksi (*Container Sections*):

```text
┌─────────────────────────────────────────────────────────────┐
│ 1. HERO SECTION                                             │
│    "Build Beyond Value."                                    │
│    Tombol CTA: [ View Selected Projects ] [ Discuss Project ]│
├─────────────────────────────────────────────────────────────┤
│ 2. OUR DELIVERY PROCESS (4 Pilar Manajemen)                 │
│    • Project Management  • Quality Control                  │
│    • Cost Control        • Schedule Management              │
├─────────────────────────────────────────────────────────────┤
│ 3. SELECTED WORKS (Loop Grid Proyek Unggulan)               │
│    • Coffee Shop Fit-Out (Bogor)                            │
│    • Studio Apartment Fit-Out (Karawang)                    │
│    • Classic House Renovation (Bekasi)                      │
├─────────────────────────────────────────────────────────────┤
│ 4. OUR CAPABILITIES (6 Kotak Layanan Terintegrasi)          │
│    • Design & Build | Build Construction | Fit-Out          │
│    • Procurement & PM | MEP Smart Building | Civil          │
├─────────────────────────────────────────────────────────────┤
│ 5. CONTACT & CONSULTATION FOOTER                            │
│    Form Kontak + Tombol WA: 0821 2864 4561                  │
└─────────────────────────────────────────────────────────────┘
```

---

## 3.1.3 Aturan Keamanan Pengeditan Visual GKT

> [!danger] Larangan Keras Staf Pengelola
> 1. **Jangan Mengubah Lebar Container (Padding/Margin 6%)**: Tata letak website diatur dengan padding presisi `6%`. Cukup klik pada widget teks, gambar, atau ikon untuk mengubah isinya tanpa mengubah setting layout kontainer.
> 2. **Wajib Menekan Tombol UPDATE**: Setelah melakukan perubahan apa pun, tombol hijau **Update** di pojok kiri bawah panel harus ditekan agar tersimpan ke publik.
> 3. **Penyelamatan Kesalahan (*Undo / Revision History*)**:
>    - Tekan `Ctrl + Z` untuk membatalkan langkah terakhir.
>    - Klik ikon **History** (gambar jam putar) di bilah kiri bawah $\rightarrow$ pilih tab **Revisions** untuk mengembalikan halaman ke versi tanggal sebelumnya.
