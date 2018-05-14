---
date: 2018-05-13
title: Instalasi Voip Client
categories:
  - bantos-voip
description: Implementasi Teknologi VOIP pada distro linux BantOS
type: Document
---

Linphone adalah Softphone VOIP yang merupakan internet ponsel open source atau Voice Over IP phone (VoIP). Dengan linphone kita dapat berkomunikasi secara bebas dengan orang-orang melalui internet dengan suara. Linphone menggumnakan protokol SIP, sebuah standar terbuka untuk telepon internet. Linphone harus dapat saling beroperasi dengan sebagian SIP-kompatibel ponsel.

## Install Linphone

Sebelum memasang linphone, tambahkan repositori linphone ke sistem :
Buka terminal gunakan perintah berikut :
```
sudo add-apt-repository ppa:linphone/release
```
![Install Linphone](/images/bantos-voip/install-linphone-1.png)

Kemudian jalankan perintah berikut untuk menerapkan perubahan di system :
```
sudo apt-get update
```
![Install Linphone](/images/bantos-voip/install-linphone-2.png)

Gunakan perintah berikut untuk menginstal perangkat lunak linphone :
```
sudo apt-get install linphone -y
```
![Install Linphone](/images/bantos-voip/install-linphone-3.png)

Cari dan klik ikon linphone di dashbor Bantos
![Install Linphone](/images/bantos-voip/install-linphone-4.png)

## Konfigurasi Linphone

Halaman beranda linphone akan muncul sebagai berikut.
![Konfigurasi Linphone](/images/bantos-voip/konfig-linphone-1.png)

Pilih "I have already a SIP acount and I just want to use it"
![Konfigurasi Linphone](/images/bantos-voip/konfig-linphone-2.png)

Masukkan detail Akun kita dan klik Apply.
![Konfigurasi Linphone](/images/bantos-voip/konfig-linphone-3.png)

Sekarang kita dapat mulai menggunakan Linphone di Linux Bantos.
![Konfigurasi Linphone](/images/bantos-voip/konfig-linphone-4.png)


Thank you! for using Linux Bantos.
