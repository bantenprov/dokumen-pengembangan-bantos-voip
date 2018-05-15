---
date: 2018-05-13
title: Bantos VOIP
categories:
  - bantos-voip
description: Implementasi Teknologi VOIP pada distro linux BantOS
type: Document
---

## Mengenal VoIP – Voice over Internet Protocol

VoIP adalah teknologi yang memanfaatkan Internet Protocol untuk menyediakan komunikasi suara secara elektronis dan real-time. VoIP mulai dikenal di Indonesia semenjak tahun 2000 dimana saat itu sedang marak-maraknya teknologi internet. Saat itu dikenal dengan fasilitas telepon gratis via internet dengan pengguna internet lainnya.

Voice over Internet Protocol (VoIP) melewatkan trafik suara, video dan data yang berbentuk paket melalui jaringan IP. jaringan IP adalah jaringan komunikasi data yang berbasis packet switch. Trafik VoIP dibagi menjadi dua bagian transmisi jaringan yaitu transmisi untuk signaling dan untuk RTP (Realtime Transfer Protocol). Protokol yang digunakan unuk signaling selalu berbasis TCP (Transfer Control Protocol) sedang untuk RTP yang digunakan adalah protocol berbasis UDP (User Datagram Protocol). Signaling dilakukan diantara port TCP yang sudah umum diketahui, misalkan untuk H323 menggunakan port 1720, SIP (session Initiation Protocol) menggunakan port 5060, IAX (Inter Asterisk Exchange) menggunakan port 4569.

Menelepon dengan menggunakan VoIP banyak keuntungannya, diantaranya adalah dari segi biaya jelas lebih murah dari tarif telepon tradisional, karena jaringan IP bersifat global. Sehingga untuk hubungan Internasional dapat ditekan hingga 70%. Selain itu, biaya maintenance dapat ditekan karena voice dan data network terpisah, sehingga IP Phone dapat ditambah, dipindah, dan diubah dengan mudah. Hal ini karena VoIP dapat dipasang di sembarang ethernet dan IP address, tidak seperti telepon tradisional yang harus mempunyai port tersendiri di Sentral atau PBX.

Untuk membuat sistem VoIP, ada beberapa variasi penyambungan. Ada koneksi dari komputer ke komputer dengan berbekal sound card dan head-set melalui jaringan LAN maupun internet merupakan solusi paling murah tetapi cukup merepotkan, karena kedua sisi harus memiliki komputer dan perangkat lunak (Softphone) yang sama. Ada juga melalui komunikasi suara dari komputer ke pesawat telepon IP (IP Phone) maupun pesawat telepon biasa yang menggunakan gateway atau perangkat yang disediakan oleh suatu perusahaan untuk dapat mengakses jaringan PSTN (Public Switched Telephone Network) setempat.  

Untuk dapat melakukan implementasi Teknologi VoIP dalam Linux Bantos dibutuhkan beberapa komponen pendukung. Beberapa komponen yang harus ada dalam  VoIP, yaitu :
- Briker (ISO)
- PC Server
- Mikrotik
- Pc Client (OS Bantos)
- Sofphone (Linphone, Zoiper)

1. Briker (ISO)
Briker adalah perangkat lunak untuk menjadikan komputer sebagai sentral telepon. aplikasi ini memudahkan komunikasi yang dibangun dengan basis open source. Briker dapat membuat server VoIP sendiri agar tercipta komunikasi dengan biaya hemat, selain itu Briker juga mendukung penuh terhadap voice dan video conference, sehingga kita bisa melakukan conference dengan membuat room sendiri untuk conference, salah satu yang menarik lagi dari Briker adalah dapat menciptakan LCR (Least Cost Routing). 
Briker merupakan distro linux, buatan local (Indonesia asli), semoga dengan adanya Briker masyarakat Indonesia dapat membuat server VoIP sendiri agar tercipta komunikasi dengan biaya hemat. Briker dengan pintar mencari jalur terhemat untuk telephone dengan interkoneksi ke PSTN, GSM dan CDMA atau provider VoIP lainnya. Briker dapat dikunjungi disitusnya http://www.briker.org

2. PC Server
PC Server adalah Sebuah system komputer yang menyediakan berbagai jenis layanan yang dapat diakses oleh komputer client yang sedang terhubung pada sebuah jaringan. Server harus didukung dengan baik oleh prosesor dan juga Memori/RAM yang lumayan besar. Server juga harus memiliki System Operasi Kusus atau biasa juga disebut sebagai System Operasi Jaringan. Server mengatur lalu lintas data di dalam jaringan dan menyediakan resource yang dapat digunakan oleh komputer lain yang sedang terhubung pada jaringannya. Server bagian paling penting dalam jaringan komputer yg menjadi tempat untuk nodes di dalam jaringan agar mampu melakukan yang namanya Resource Sharing.

3. Mikrotik
Mikrotik adalah sistem operasi dan perangkat lunak yang dapat digunakan untuk menjadikan komputer manjadi router network yang handal, mencakup berbagai fitur yang dibuat untuk IP network dan jaringan wireless. Mikrotik didesain untuk mudah digunakan dan sangat baik digunakan untuk keperluan administrasi jaringan komputer seperti merancang dan membangun sebuah sistem jaringan komputer skala kecil hingga yang kompleks sekalipun.

4. PC Client (OS Bantos)
PC client adalah komputer yang digunakan untuk instalasi client VoIP dan melakukan pengolahan data VoIP yang diambil dari server VoIP, dalam hal ini PC / Laptop yang sudah terinstall Operation System Bantos ( Distribusi Linux Open Source )

5. Sofphone (Linphone, Zoiper)
Softphone adalah perangkat lunak yang mensimulasikan aksi telepon dan memungkinkan Anda membuat, menerima dan mengelola panggilan suara melalui Internet. Softphone biasanya berjalan di komputer, tablet, PC, dan smartphone, dan diperlukan untuk melakukan panggilan VoIP (Voice over IP) dan panggilan video.

## Jenis-jenis Metode Layanan dan VoIP
Seluruh layanan PSTN ditambah dengan Instant Messaging, Video Call, Video Conference :
- Analog Telephone Adaptor (ATA)
- IP Phones
- PC to PC

1. Analog Telephone Adaptor (ATA)
ATA adalah metode paling umum untuk menggunakan layanan VOIP yaitu menggunakan alat yang bernama ATA yang memungkinkan kita menyambungkan telepon konvensional ke PC atau internet untuk melakukan VOIP.

2. IP Phones
IP PHONES yaitu telepon yang sudah memiliki port RJ-45 untuk langsung di sambungkan ke router guna melakukan panggilan VOIP.

3. PC to PC
PC to PC seperti namanya saja kita sudah dapat membayangkan, yaitu panggilan VOIP yang dilakukan menggunakan PC dengan perlengkapan microphone, speaker, dan software yang di sediakan para developer komunikasi VOIP ini contoh : Zoiper, Linphone, X-Lite, User tidak membayar satu sen pun dalam melakukan panggilan antar pengguna sesama layanan.

## Manfaat VoIP
  - Penghematan biaya telepon SLJJ / SLI dengan tidak melanggar hukum
  - Next Generation Network (NGN)
