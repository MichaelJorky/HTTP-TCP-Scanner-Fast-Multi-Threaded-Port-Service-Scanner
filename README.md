# 🛰️ HTTP & TCP Scanner – Fast Multi-Threaded Port & Service Scanner

> ⚠️ **Peringatan:**
> Alat ini dibuat semata-mata untuk tujuan penelitian, pengujian, dan pembelajaran. Penulis tidak bertanggung jawab atas penyalahgunaan, kerusakan, atau konsekuensi apa pun yang timbul dari penggunaan aplikasi ini. Gunakan hanya pada jaringan atau sistem yang Anda miliki atau memiliki izin eksplisit untuk diuji. Harap gunakan dengan penuh tanggung jawab.

HTTP &amp; TCP Scanner adalah aplikasi pemindai port multi-thread yang dirancang untuk melakukan pengecekan layanan HTTP dan koneksi TCP secara cepat dan efisien. Aplikasi ini cocok digunakan untuk memeriksa status port pada router, server, maupun jaringan lokal.

Aplikasi menampilkan hasil scan secara real-time dalam bentuk tabel berwarna untuk memudahkan identifikasi:

### 🔍 Fitur Utama

* **Load IP otomatis** dari file list.
* Mode **TCP Only** untuk pengecekan cepat.
* Validasi **Username & Password** untuk HTTP/Web Auth.
* Input **multi-port** dengan format fleksibel (contoh: `22,80,443,8080,8443` atau `1-1000,2000-3000` atau `22,80,443,8080,8443,1-1000,2000-3000`).
* **Multi-thread scanning** dengan progress bar real-time.
* Tampilan **status per port**:

  * `TCP Open`
  * `HTTP Open`
  * `Error / Timeout`
* Menampilkan:

  * Layanan terdeteksi (Service)
  * Status koneksi
  * HTTP Response Code
  * Response Time (ms)
  * Server Header
  * Web Titles
  * Response Header
* Log detail lengkap di bagian bawah aplikasi.
* Statistik runtime:

  * Total check
  * Jumlah open & error
  * Average response time
  * Total elapsed time

### 🎯 Kegunaan

Aplikasi ini sangat cocok untuk:

* Administrator jaringan yang ingin memantau router atau server.
* Pengujian layanan API RouterOS, Winbox, HTTP, SSH, Telnet, DNS dan lain-lain.
* Audit keamanan port di jaringan lokal atau remote.
* Troubleshooting koneksi server.
