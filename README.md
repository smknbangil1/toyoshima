# Panduan Kelola Email Server Mandiri

**oleh Purwanto | Jasa Konfig Server**  
**Kontak WA: +62 822-3348-3221**

## 1. Buka Control Panel
Akses control panel melalui link berikut:

[**Control Panel**](https://202.154.190.102:28389/Lcp2025)

- **Username:** tanyain saya via WA 
- **Password:** tanyain saya via WA mas 

## 2. Membuat Akun Email
1. Masuk ke menu **Home**.
2. Klik **Mail Server 7.0.4**.
3. Pilih **User** untuk menambah akun email.
4. Jika diperlukan, hapus akun email pengujian yang telah tersedia.

## 3. Akses Email via Web Browser
Gunakan salah satu browser seperti Chrome, Firefox, atau Edge, lalu buka:

[**Webmail**](https://mail.toyoshima.id/)

## 4. Konfigurasi Desktop Mail Client
Untuk mengatur email di **Microsoft Outlook** atau **Mozilla Thunderbird** pada Windows 11, gunakan pengaturan berikut:

### **Pengaturan Server**
- **POP3:** mail.toyoshima.id, port **110 (non-SSL) / 995 (SSL)**
- **IMAP:** mail.toyoshima.id, port **143 (non-SSL) / 993 (SSL)**
- **SMTP:** mail.toyoshima.id, port **25 / 465 (SSL) / 587 (STARTTLS)**

### **Jenis Enkripsi & Metode Autentikasi**
- **POP3 & IMAP:** SSL/TLS atau STARTTLS sesuai kebutuhan.
- **SMTP:** STARTTLS di port 587 atau SSL/TLS di port 465.
- **Autentikasi:** Gunakan kredensial email untuk login.

### **POP3 vs IMAP**
- **POP3** cocok untuk penggunaan satu perangkat, karena email akan diunduh dan dihapus dari server.
- **IMAP** lebih fleksibel karena menyimpan email di server, memungkinkan sinkronisasi di banyak perangkat.

### **Kapan Menggunakan Port SMTP yang Berbeda?**
- **Port 25:** Port Standar SMTP.
- **Port 465:** Digunakan untuk koneksi terenkripsi dengan SSL.
- **Port 587:** Alternatif, disarankan untuk pengiriman email dengan STARTTLS.

---
**Untuk bantuan lebih lanjut, silakan hubungi WA: +62 822-3348-3221.**

