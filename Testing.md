<html>
<body>
<body><div align="center"><h1>Software Testing Document</h1></div>
<p align="center"><b>Version 1.0 </b><br>
<p align="center">09 Mei 2018<br><br>
<p align="center">
<img src="http://i68.tinypic.com/nlyf5v.jpg"/>
</p>
<br><p align="center"><b> APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID </b><br>

<p align="center"><b>Kelompok 4</b><br>
 Irin Windiyati 			(1603073)<br>
 Dina Micela				  (1603066)<br>
 Nunung Nurhayati			(1603081)<br>
 Yoshie Pangestu    	(1603089)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b><br>
<p align="center"><b>2018</b><br><br>
</p>
</body>
</html>

### BAB I : Pendahuluan
#### 1.1 Tujuan Pembuatan Dokumen hahaha
Dokumen ini dibuat sebagai pengujian terhadap perangkat lunak pada Sistem Aplikasi pada Android yaitu Pemesanan Makanan.
Dokumen ini dipakai untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan perancangan sistem
yang telah dibuat dan sesuai dengan keinginan pengguna. Sehingga, menghasilkan suatu aplikasi sistem yang dapat
mempermudah proses Pemesanan Makanan yang umumnya dilakukan secara manual. Pembuatan Dokumen ini ditunjukan untuk
menguji perangkat lunak Pemesanan makanan Berbasis Android yang merupakan bagian dari Tugas mata kuliah Rekayasa
perangkat Lunak.

#### 1.2 Deskripsi Umum Sistem
Pada umumnya sistem Pemesanan Makanan ini menggunakan aplikasi berbasis Android dimana para customer masih melakukan
pemesanan makanan secara manual dimana customer harus memesan makanan langsung ke toko sedangkan customer memiliki
kesibukan tersendiri sehingga memakan waktu dan tidak efesien. Selain itu pemesanan makanan manual menggunakan banyak
kertas dan tinta sehingga terjadi pemborosan.
<br>
<br>
Untuk itu, kelompok kami mempunyai gagasan yang dapat meminimilasirkan dari ketidak efesiennya Sistem Pemesanan Makanan
yang masih secara manual yaitu, dengan cara membuat Aplikasi Pemesanan Makanan Berbasis Android. Aplikasi ini setiap
Pemesanan makanan bisa diakses melalui Smartphone Android dan dapat diakses dimana saja dan kapan saja sesuai yang diinginkan.
Aplikasi ini memiliki 4 user yaitu Customer, Seller, Kurir dan Admin, tetapi Admin diakses melalui sistem Web.
<br><br>
Pada sisi Customer, Seller dan Kurir pada apliaksi Android terdapat beberapa Fungsi yaitu :
* Customer dapat mengakses Aplikasi dimana saja dan kapan saja
* Customer dapat memesan makanan di beberapa toko dan diantar di tempat
* Customer dapat melihat jumlah makanan yang di pesan
* Customer dapat membayar pesanan makanan ditempat
* Customer dapat memberikan review ke Seller
* Setelah Customer pesan makanan terdapat notifikasi pemesanan dari Customer
* Seller dapat memilih kurir yang aktif
* Seller dapat meneruskan pesanan makanan ke kurir
* Seller dapat memberikan review ke Customer
* Seller dapat menambahkan Kurir
* kurir dapat notifikasi pesanan makanan dari seller
* kurir dapat memberikan konfirmasi barang sampai ke seller
<br><br>

Pada sisi Admin pada sistem web terdapat beberapa fungsi:
* Admin dapat menambahkan Customer, Seller dan kurir
* Admin dapat menghapus akun Customer/seller dan kurir
* Admin juga dapat melihat kapan terakhir Customer aktif

#### 1.3 Deskripsi Dokumen (Ikhtisar)
Pada Dokumen Software Testing Document(STD) terdapat 3 bagian yaitu Pendahuluan, Lingkungan Pengujian Perangkat
Lunak, Identifikasi dan Rencana Pengujian.


#### 1.4 Definisi dan Singkatan

| Definisi, Akronim dan Singkatan |                                   Penjelasan                                        |
|---------------------------------|-------------------------------------------------------------------------------------|
|           STD/DUPL              | Software Test Description/Dokumen Uji Perangkat Lunak merupakan dokumen yang        |
|                                 | menyatakan haisil perencanaan pengujian, deskripsi kasus uji yang diberlakukan      |
|                                 | serta hasil pengujian yang telah dilakukan.                                         |
|           SRS/SKPL              | Software Requirements Spesification/Spesifikasi kebutuhan perangkat lunak meruakan  |
|                                 | spesifikasi dari perangkat lunak yang akan dikembangkan.                            |
|           SDD/DPPL              | Software Design Description/Deskripsi Perancangan Perangkat Lunak merupakan deskri- |
|                                 | psi dari perangkat lunak yang akan dikembangkan.                                    |

#### Dokumen Referensi
Dokumen Referensi yang digunakan dalam pembuatan DUPL adalah :
Ernita H. GL03. Dokumen Uji Perangkat Lunak (DUPL) SDS, Bogor.

#### BAB 2 Lingkungan Pengujian Perangkat Lunak

#### 2.1 Perangkat lunak Pengujian
Aplikasi ini diujikan dengan beberapa perangkat lunak lain seperti :
Sistem Oprasi : linux dan windows 10
Database : Mysql
<br><br>
#### 2.2 Perangkat Keras Pengujian
perangkat keras yang digunakan pada Aplikasi Pemesanan ini adalah satu set PC/Laptop dan Smartphone Android:
- PC/Laptop
* Processor 
* Memory    
* Hrddisk   
- Smartphone Android
* Versi Android
* Ram       
* Memory    
<br><br>

#### 2.3 Material Pengujian
Pada program Aplikasi Pemesanan Makanan Berbasis Android ini Customer dapat melakukan pemesanan makanan melaui
aplikasi yang yang menggunakan Device(HP) yang digunakan. Dengan melakukan pendaftaran menggunkanan Email dan
No Hp pengguna, satu email dan satu no hp yaitu satu pengguna, Dari User Customer, Seller dan Kurir menggunakan
Email dan no hp sebagai register untuk dapat bergabung di Aplikasi "AYO MANGAN".
<br><br>
Customer, Seller dan Kurir dapat bergabung apabila sudah terdaftar atau sudah memalukan registrasi di Aplikasi
AYO MANGAN, Jika Customer melakukan Pemesanan atau order dari berbagai toko yang dipilih
maka terdapat notifikasi dan akan masuk ke Seller, Seller dapat melakukan accept dengan hanya menekan tombol buttom,
ketika Seller accept orderan dari Customer maka seller akan memilih kurir yang aktif lalu meneruskan orderan ke kurir,
lalu kurir accept terusan order dari seller dan mengirim barang ke tempat. Customer melakukan transaksi di tempat
kemudian mengkonfirmasi barang sampai begitupun juga dengan kurir melakukan konfirmasi barang sampai. Selain itu Customer
dan Seller dapat memberikan review.
<br><br>
Dari s=user Admin dapat mengelola data berupa Data Customer,Data Seller,Data Kurir dan Data Review
<br><br>

#### 2.4 Sumber Daya Manusia<br><br>
Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian Aplikasi ini adalah :
* Memahami konsep pemrograman berorientasi Objek
* Memahami proses pengujian perangkat lunak berorientasi Objek
* Memahami konsep pemrograman Database<br><br>

#### 2.5 Pelaksanaan
Pelaksanaan dilakukan dengan mengeksekusi perangkat lunak Aplikasi Ayo Mangan dengan mengikuti skenario tertentu yang dibuat berdasarkan skenario yang terdapat pada dokumen SKPL-Aplikasi Ayo Mangan.

#### 2.6 Pelaporan Hasil
Dokumen hasil uji dari aplikasi ini akan diberikan kepada dosen Rekayasa Perangkat Lunak dan dievaluasi oleh dosen R
