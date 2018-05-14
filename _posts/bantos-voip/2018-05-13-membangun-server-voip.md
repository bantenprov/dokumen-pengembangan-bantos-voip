---
date: 2018-05-13
title: Bantos VOIP
categories:
  - bantos-voip
description: Implementasi Teknologi VOIP pada distro linux BantOS
type: Document
---

## Membangun Server VoIP

### Komponen Jaringan VoIP
Untuk dapat melakukan implementasi dan VoIP dapat melaksanakan tugasnya menyalurkan sinyal suara, VoIP harus didukung oleh beberapa komponen yaitu 
- Terminal
- VoIP Gateway
- Network IP

1. Terminal adalah peralatan yang berhubungan langsung dengan pemakai aplikasi. Peralatan terminal yang dapat untuk hubungan VoIP ada bermacam-macam diantaranya 
    - Headphone
    - Pesawat telepon digital (ISDN)
    - Pesawat telepon analog dan komputer
    - Sofphone berbasis Android.

2. Gateway VoIP adalah interface antara telepon tradisional dengan network IP, memungkinkan interoperabilitas teknologi antara jaringan yang berbeda untuk dapat  saling  berkomunikasi. Gateway ini berupa komputer atau router yang dikonfigurasikan  untuk  menghubungkan  panggilan telepon  ke  jaringan IP. Pada Gateway ini terjadi proses pengkodean dan pengkompresan panggilan serta paketisasi data suara digital. 

3. Network IP adalah network (bisa internet atau intranet atau Virtual Private Network) yang telah menggunakan protokol TCP/IP sebagai aturan mentransfer data dari sumber ke tujuan. Jaringan IP sebenarnya adalah gabungan router-router yang saling berkomunikasi dengan bahasa yang sama  yaitu TCP/IP Komponen jaringan IP ini adalah router dan media transmisi.

### Persiapan
  - Mendata apa yang dimiliki dan/atau yang akan dimiliki, Kondisi jaringan, LAN dan/atau Internet
  - Menentukan fitur layanan Voice dan Video yang akan dibangun.
  - Memilih komponen yang tepat untuk memenuhi fitur layanan dengan infrastruktur yang sudah dimiliki dan/atau akan dimiliki.

### Perancangan
VoIP server yang akan dibangun adalah menggunakan sistem operasi Linux server. Sistem Operasi Linux yang akan digunakan untuk pembuatan Server VoIP adalah Briker 2.0.4. Briker adalah distribusi Linux yang didalamnya terdapat aplikasi server yang memungkinkan pengguna mengimplementasikan layanan VoIP, membangun sentral telepon sendiri. 

Pada perancangan VoIP IP Address yang digunakan adalah IP Address IPV4. Server VoIP yang akan dibangun akan menggunakan protocol  Session  Initiation  Protocol  (SIP).  SIP yang digunakan adalah berupa aplikasi yang berfungsi sebagai Proxy Server, Redirect Server dan Registrar Server. Aplikasi ini dinamakan dengan Asterisk. 

### Pelaksanaan
  - Download ISO Briker
  - Install Briker
  - Configurasi
  - Input User VoIP
  
1. Download ISO Briker
Download iso [download](http://arsip.voiprakyat.or.id/pub/briker/iso/briker-2.0.4.iso)
2. Instalasi

Proses Instalasi

![Instalasi](/images/install-briker-1.png)

Otomatis memeriksa perangkat keras jaringan, lalu mengkonfigurasi alamat IP secara otomatis.

![Instalasi](/images/install-briker-2.png)
Otomatis menghapus (format) hardisk dan menggunakan semua isi hardisk

![Instalasi](/images/install-briker-3.png)
Otomatis install base system dan software lainnya.  

![Instalasi](/images/install-briker-4.png)
Install GRUB boot loader.

![Instalasi](/images/install-briker-5.png)
Menjalankan proses Finishing Installation, setelah itu mesin akan restart secara otomatis.

![Instalasi](/images/install-briker-6.png)
Instalasi sistem selesai, mesin akan restart kembali



