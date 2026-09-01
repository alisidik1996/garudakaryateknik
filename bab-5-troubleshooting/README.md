---
title: Modul 5 - Form Masuk, Feed IG, & Troubleshooting Cepat
created: 2026-09-01
updated: 2026-09-01
tags:
  - sop
  - gitbook
  - modul-5
  - troubleshooting
  - form
  - instagram
sources:
  - https://garudakaryateknik.com
related:
  - "[[Garuda Karya Teknik]]"
---

# Modul 5: Pengecekan Form Masuk, Instagram Feed, & Troubleshooting GKT

Modul ini memandu staf operasional dalam memonitor pesan penawaran proyek yang masuk melalui website, memelihara widget Instagram feed @gkt.builds, dan menyelesaikan kendala teknis harian.

---

## 5.1 Memeriksa Pesan Masuk dari Formulir Website (Lead Submissions)

Calon klien yang mengisi form konsultasi ("Schedule Consultation / Contact Us") akan otomatis tercatat ke dalam dua saluran:
1. **Notifikasi Email**: Dikirim langsung ke `office@garudakaryateknik.com`.
2. **Database Dashboard WordPress**:

### Cara Mengecek Rekap Pesan Masuk di Dashboard:
1. Masuk ke dashboard WordPress admin (`garudakaryateknik.com/wp-admin`).
2. Di menu sebelah kiri, buka **Elementor** -> klik **Submissions** (atau buka menu **WPForms** -> **Entries**).
3. Tabel daftar pengirim memuat:
   - Nama Lengkap / Instansi Klien
   - Alamat Email & Nomor WhatsApp
   - Jenis Kebutuhan Proyek (Konstruksi, Fit-Out, MEP, atau Renovasi)
   - Pesan / Rencana Anggaran
4. Klik **View** pada pesan untuk melihat detail lengkap, lalu teruskan ke tim estimasi atau sales.

---

## 5.2 Pemeliharaan Widget Instagram Feed (@gkt.builds)

Seksi "Latest Updates & Projects" di halaman beranda menampilkan feed otomatis dari akun Instagram resmi @gkt.builds menggunakan plugin Smash Balloon:

> [!tip] Jika Foto Instagram Tidak Muncul / Token Kadaluarsa
> 1. Di menu dashboard kiri, buka **Instagram Feed** -> **All Feeds**.
> 2. Jika muncul peringatan "Access Token Expired", klik tombol biru **Reconnect / Update Account**.
> 3. Login ke akun Instagram @gkt.builds dan izinkan otorisasi akses. Foto terbaru akan otomatis tersinkronisasi kembali ke website.

---

## 5.3 Panduan Solusi Kendala Cepat (Quick Troubleshooting)

### Kendala 1: Perubahan di Elementor sudah di-Update, tapi saat dibuka di HP masih tampilan lama
- **Penyebab**: Memori cache browser HP atau cache hosting Hostinger Reach masih aktif.
- **Solusi**:
  1. Pada bilah atas (Top Admin Bar), klik menu **Purge All Caches** / **Clear Cache**.
  2. Buka website di browser HP menggunakan mode Incognito / Private.
  3. Di komputer, tekan kombinasi tombol `Ctrl + F5` untuk membersihkan cache peramban.

### Kendala 2: Editor Elementor tidak bisa dibuka (Loading berputar terus)
- **Penyebab**: Tab editor terbuka ganda atau limit memori PHP terganggu.
- **Solusi**:
  1. Tutup seluruh tab browser lain.
  2. Klik tombol **Enable Safe Mode** pada pesan yang muncul untuk mematikan plugin pihak ketiga saat mengedit.
  3. Bersihkan cookie browser, lalu login kembali ke `/wp-admin`.

---

## 5.4 Kontak Eskalasi Bantuan Teknis

Untuk kendala darurat (website down, error database, atau perpanjangan hosting/domain):

- **Tech Engineer & Konsultan**: [[Ali Sidik Abdus Salam]]
- **WhatsApp Teknis**: 0821 2864 4561 (atau kontak WhatsApp Tuan Ali)
- **Email Teknis**: office@garudakaryateknik.com
