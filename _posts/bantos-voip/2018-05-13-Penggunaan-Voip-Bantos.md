---
date: 2018-05-13
title: Penggunaan Voip Bantos
categories:
  - bantos-voip
description: Implementasi Teknologi VOIP pada distro linux BantOS
type: Document
---

## Melakukan Panggilan VoIP

Pastikan nomor tujuan kita sudah didaftarkan di server VoIP oleh administrator.

- Buka terlebih dahulu aplikasi linphone dan pastikan pc anda sudah terkoneksi internet atau dalam satu jaringan (koneksi lokal)
![Panggilan VoIP](/images/bantos-voip/tampilan-awal.png)

- Menambahkan kontak telpon (SIP VoIP).
```
	1. Klik icon + 
	2. Isi akun identitas teman atau nomor yang akan di panggil
	3. Ok 
```
![Tambah Kontak](/images/bantos-voip/tambah-kontak.png)
	
- Setelah ditambahkan, coba kita lakukan dengan klik icon panggil
![Tes Panggil](/images/bantos-voip/test-panggil.png)

- Tunggu sampai nomor panggilan yang kita telfon menerima telfon kita.
![Panggilan](/images/bantos-voip/panggilan.png)

- Tampilan linphone di nomor yang kita panggil ( Answer atau Decline)
![Panggilan](/images/bantos-voip/panggilan-1.png)

- Tampilan setelah nomor yang kita panggil menerima panggilan kita
![Panggilan](/images/bantos-voip/panggilan-2.png)


## Melakukan Kirim Pesan (SMS) di VoIP

- Pengiriman pesan di VoIP dapat kita lakukan dengan klik icon Pesan di sebelah ikon panggil, dan ketik pesan di kolom bawah
Tulis pesan dan klik send.
![Kirim Pesan](/images/bantos-voip/sms-1.png)

## Hasil yang didapatkan
Teknologi VoIP Bantos dengan sofphone Linphone sebagai client Dapat melakukan pengiriman pesan singkat, telefon, dan call video.

```
Catatan penting:
Dalam tahap-tahap percobaan diatas, penggunaan user test dan 10001 adalah hanya contoh saja, pada percobaan anda sendiri anda harus menggunakan nama-nama yang lebih unik.
Dalam tahap-tahap percobaan diatas, perhatikan penggunaan tx dan rx, tx untuk transmit, rx untuk receive.
```


