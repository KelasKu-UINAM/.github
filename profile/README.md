<div align="center">

# KelasKu UINAM

### Platform Manajemen Kelas untuk Mahasiswa UIN Alauddin Makassar

KelasKu UINAM adalah project aplikasi manajemen kelas yang dibuat untuk membantu mahasiswa, komting, bendahara, dan anggota kelas dalam mengelola informasi akademik serta administrasi kelas secara lebih rapi, terpusat, dan mudah diakses.

</div>

---

## Tentang Project

KelasKu UINAM dibuat sebagai solusi digital untuk kebutuhan kelas sehari-hari.
Aplikasi ini bertujuan agar informasi penting seperti jadwal kuliah, tugas, pengumuman, forum diskusi, dan iuran kelas tidak tercecer di banyak chat atau catatan manual.

Dengan KelasKu, setiap kelas dapat memiliki sistem manajemen sederhana yang bisa digunakan oleh beberapa role, seperti admin/komting, bendahara, dan mahasiswa.

---

## Fitur Utama

* Manajemen kelas dan anggota
* Jadwal mata kuliah
* Data mata kuliah
* Tugas dan deadline
* Pengumuman kelas
* Forum diskusi umum
* Forum diskusi per mata kuliah
* Manajemen iuran kelas
* Rekap pembayaran mahasiswa
* Konfigurasi WhatsApp
* Reminder pembayaran iuran
* Dashboard ringkasan aktivitas kelas

---

## Role Pengguna

### Admin / Komting

Admin atau komting bertugas mengelola data utama kelas, seperti anggota, mata kuliah, jadwal, tugas, pengumuman, dan forum.

### Bendahara

Bendahara bertugas mengelola data iuran kelas, melihat status pembayaran, dan membantu mengirim reminder pembayaran.

### Mahasiswa

Mahasiswa dapat melihat jadwal, tugas, pengumuman, forum, serta status pembayaran iuran masing-masing.

---

## Arsitektur Sistem

```text
Flutter Mobile App <----> Express REST API <----> PostgreSQL Railway
```

Project ini menggunakan konsep client-server.
Aplikasi mobile Flutter digunakan sebagai frontend, sedangkan backend Express.js menjadi penghubung antara aplikasi dan database PostgreSQL.

---

## Repository

| Repository                                                          | Deskripsi                                     | Tech Stack                      |
| ------------------------------------------------------------------- | --------------------------------------------- | ------------------------------- |
| [`kelasku-api`](https://github.com/KelasKu-UINAM/kelasku-api)       | Backend REST API untuk aplikasi KelasKu UINAM | Node.js, Express.js, PostgreSQL |
| [`kelasku_mobile`](https://github.com/KelasKu-UINAM/kelasku_mobile) | Aplikasi mobile KelasKu UINAM                 | Flutter, Dart                   |
| [`.github`](https://github.com/KelasKu-UINAM/.github)               | Konfigurasi dan profile organization          | Markdown                        |

---

## Tech Stack

### Mobile

* Flutter
* Dart

### Backend

* Node.js
* Express.js
* PostgreSQL Railway
* JWT Authentication
* bcrypt
* dotenv
* cors
* helmet
* morgan
* express-validator

### Database

* PostgreSQL
* Railway

---

## Tujuan Project

Project ini dibuat untuk:

1. Membantu pengelolaan kelas secara digital.
2. Mempermudah mahasiswa dalam melihat informasi kuliah.
3. Membantu komting mengatur jadwal, tugas, dan pengumuman.
4. Membantu bendahara dalam mengelola iuran kelas.
5. Mengurangi ketergantungan pada chat WhatsApp yang mudah tertimbun.
6. Membuat data kelas lebih terstruktur dan mudah dicari kembali.

---

## Status Project

Project ini masih dalam tahap pengembangan.

Beberapa bagian utama yang dikembangkan:

* Backend REST API
* Mobile App Flutter
* Dokumentasi sistem
* Integrasi fitur kelas, tugas, forum, dan pembayaran

---

## Struktur Umum

```text
KelasKu-UINAM
├── kelasku-api
│   └── Backend REST API
│
├── kelasku_mobile
│   └── Mobile App Flutter
│
└── .github
    └── Organization Profile
```

---

## Kontribusi

Project ini dikembangkan untuk kebutuhan pembelajaran dan pengembangan aplikasi manajemen kelas.
Kontribusi dapat dilakukan melalui pull request, issue, atau pengembangan fitur baru sesuai kebutuhan project.

---

## Catatan

KelasKu UINAM bukan aplikasi resmi dari kampus.
Project ini dibuat sebagai project pengembangan aplikasi untuk membantu aktivitas manajemen kelas mahasiswa.

---

<div align="center">

Made for better class management.

**KelasKu UINAM**

</div>
