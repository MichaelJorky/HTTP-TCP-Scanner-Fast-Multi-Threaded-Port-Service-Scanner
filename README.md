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

---
## 🔌 Bonus: Default Port Lists

Aplikasi ini juga dilengkapi dengan *default port presets* untuk memudahkan proses scanning tanpa harus memasukkan port satu per satu. Daftar port ini mencakup port umum yang digunakan oleh server, game, aplikasi, hingga layanan P2P.

### 🖥️ **Server Ports**

```
21, 22, 23, 25, 53, 80, 110, 137, 138, 139, 143, 443, 445, 548, 587, 993, 995, 
1433, 1701, 1723, 3306, 5432, 8008, 8443, 8728, 8729, 8291
```

### 🎮 **Game Ports**

```
666, 2302, 3453, 3724, 4000, 5154, 6112, 6113, 6114, 6115, 6116, 6117, 6118, 
6119, 7777, 10093, 10094, 12203, 14567, 25565, 26000, 27015, 27910, 28000, 50000
```

### 📱 **Application Ports**

```
515, 631, 3282, 3389, 5190, 5050, 4443, 1863, 6891, 1503, 5631, 5632, 5900, 6667, 8080, 8081, 8888, 9090, 9091
```

### 🔁 **P2P Ports**

```
119, 375, 425, 1214, 412, 1412, 2412, 4661, 4662, 4665, 5500, 6346, 
6881, 6882, 6883, 6884, 6885, 6886, 6887, 6888, 6889
```

Port-port di atas dapat digunakan sesuai kebutuhan untuk mempercepat proses scanning dan analisis layanan jaringan.
