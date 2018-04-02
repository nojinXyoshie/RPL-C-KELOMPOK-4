<html>
<body><div align="center"><h1>Software Design Document</h1></div>
<p align="center"><b>Version 1.0 </b><br>
<p align="center">11 Maret 2018<br><br>
<p align="center">
<img src="http://i68.tinypic.com/nlyf5v.jpg"/>
</p>

<br><p align="center"><b> APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID </b><br>

<p align="center"><b>Kelompok 4</b><br>
 Irin Windiyati 			(1603173)<br>
 Dina Micela				  (1603066)<br>
 Nunung Nurhayati			(1603081)<br>
 Yoshie Pangestu    	(1603089)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b><br>
<p align="center"><b>2018</b><br><br>
</p>
</body>
</html>
 

### Bab 1 : Pendahuluan ###
#### 1.1 Tujuan Penulisan Dokumen

Dokumen SDD ini disusun dengan tujuanuntuk menjelaskan langkah-langkah desain dan proses-proses dalam pembuatan sistem aplikasi yang akan di terapkan pada aplikasi simulasi management proyek RPL dan juga memberi definisi kebutuhan untuk sistem spesifikasi kebutuhan fungsional. dan juga dokumen ini digunakan sebagai landasan yang diperlukan dalam
proses pengembangan maupun perubahan fitur di masa yang akan datang. Dengan dokumen
ini diharapkan pengembang perangkat lunak akan dimudahkan dalam perubahan fitur dari
perangkat lunak tersebut.<br>

#### 1.2 Lingkup
Ruang lingkup SDD ini adalah penjelasan mengenai aplikasi simulasi management proyek RPL berbasis dekstop, ruang lingkup system ini mencangkup informasi mengenai antarmuka dari system tersebut.
#### 1.3 Definisi, akronim, dan singkatan
- SRS (Software Requirement Specification)
- DFD (Data Flow Diagram)
- ERD (Entity Relationship Diagram)
- DBMS (Data Base Management System)
- IEEE (The International Institute ofElectronic and Electrical Engineers)
- SPMP (Software Project Management Plan)
#### 1.4 Referensi
* IEEE, IEEE Draft Standard for Software Design Descriptions. IEEE P1 01 6/D5.0; 1 2 December 2005<br>
* Eka Ismantohadi & Moh. Yani, Software Design Document (SDD). 2018<br>
* Tri Suwarno, Dokumen Persyratan Perangkat Lunak. 2013<br>
#### 1.5 Ikhtisar dokumen

### Bab 2 : Deskripsi Perancangan Global ###
#### 2.1 Rancangan Lingkungan Implementasi
- Hypertext Prepocessor atau PHP adalah bahasa pemrograman yang digunakan untuk penanganan pembuatan dan pengembangan sebuah situs web dan bisa digunakan dengan HTML.
- Sublime adalah sebuah aplikasi text untuk bahasa pemrograman termasuk pemrograman PHP, sublime mendukung banyak bahasa pemrograman dan bahasa markup serta fungsinya dapat ditambah dengan plugin.
- MySQL adalah sebuah sistem manajemen basis data SQL atau DBMS yang multithread, multi-user, MySQL dimiliki dan disponsori oleh sebuah perusahaan komersial Swedia MySQL AB, di mana memegang hak cipta hampir atas semua kode sumbernya. Kedua orang Swedia dan satu orang Finlandia yang mendirikan MySQL AB adalah: David Axmark, Allan Larsson, dan Michael "Monty" Widenius.
- Android-SDK alat bagi para programmer yang ingin mengembangkan aplikasi berbasis android. Android SDK mencakup seperangkat alat pengembangan yang komprehensif. Android SDK terdiri dari debugger, libraries,handset emulator,dokumentasi,contoh kode, dan tutorial. Saat ini Android sudah mendukung arsitektur x86 pada Linux,Mac OS X 10.4.8 atau lebih, Windows XP atau Vista. Persyaratan mencakup JDK, Apache Ant dan Python 2.2 atau yang lebih baru.
- Java JDK adalah sebuah perangkat lunak yang digunakan untuk menggunakan proses kompilasi dari kode java ke bytecode yang dapat dimengerti dan dapat dijalankan oleh JRE(Java Runtime Envirotment)
JDK wajib terinstall pada komputer yang akan melakukan proses pembuatan aplikasi berbasis java.
- Java Script adalah bahasa pemrograman yang bisa di sisipkan ke HTML seperti halnya PHP akan tetapi Java script berjalan disisi Client, Desain java script dipengaruhi oleh banyak bahasa pemrograman, termasuk C, tetapi dimaksudkan untuk lebih digunakan oleh nonprogrammer.
- Android Studio adalah aplikasi lingkungan Pengembangan Terpadu-Integrated Development Environment(IDE) untuk pengembangan aplikasi Android, berdasarkan IntelliJ IDEA.
- Boostrap adalah sebuah library framework CSS yang dibuat khusus untuk mengembangkan front-end boostrap, Boostrap merupakan salah satu framework HTML, CSS, dan Javascript yang banyak digunakan pada website. Boostrap telah menyidiakan kumpulan komponen dasar yang telah dirancang sedimikian rupa untuk menciptakaan tampilan yang menarik. Boostrap juga berfungsi untuk mengatur layout pada halaman website yang bisa digunakan dengan mudah.
#### 2.2 Deskripsi Data
#### 2.2.1 Definisi Domain/type
#### 2.2.2 Conceptual Data Model
#### 2.2.3 Physical Data Model
#### 2.2.4 Daftar Tabel Aplikasi
#### 2.3 Deskripsi Modul

### Bab 3 : Deskripsi Perancangan Rinci ###
#### 3.1 Diagram Konteks
<div style="text-align:center"><img src="http://i68.tinypic.com/mhqbro.jpg"/></div>

#### 3.1.1 DFD level 0
<div style="text-align:center"><img src="http://i63.tinypic.com/2lxcx85.jpg"/></div><br>

#### 3.2 Dekommposisi Proses Konkuren
#### 3.2.1 DFD Level 1 : Proses 1
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...
#### 3.2.2 DFD Level 1 : Proses 2
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...
#### 3.3 Dekommposisi Data
(tabel-tabel database yang digunakan pada DFD)
#### 3.3.1.1 Fungsi Modul
#### 3.3.1.2 Spesifikasi Layar Utama
prototype belum jadi
#### 3.3.1.3 Spesifikasi Query
ID-QUERY , DESKRIPSI , EKSPRESI QUERY

### 3.3 Dekomposisi Data.<br><br>

- Data User Customer, Seller, Kurir, Admin.

|    No     |         Data                |                Keterangan                          |
|-----------|-----------------------------|----------------------------------------------------|
|     1     | Email, No.hp, Password      | Digunakan Untuk Login Customer                     |
|     2     | Email, No.hp, Password      | Digunakan Untuk Login seller                       |
|     3     | Email, No.hp, Password      | Digunakan Untuk Login Kurir                        |
|     4     | Email, No.hp, Password      | Digunakan Untuk Login Admin                        |


- Data Admin.<br>


|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_admin            | Primary Key                                        |
|     2     |         Nama                | Nama Admin                                         |
|     3     |         Email               | Email Pengguna                                     |
|     4     |         Password            | Password Pengguna                                  |
|     5     |         No.hp               | No.hp Pengguna                                     |


- Data Customer.<br>

|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_admin            | Primary Key                                        |
|     2     |         Nama                | Nama Customer                                      |
|     3     |         Email               | Email Customer                                     |
|     4     |         Password            | Password Customer                                  |
|     5     |         No.hp               | No.hp Customer                                     |
|     6     |         Alamat              | Alamat Customer                                    |
|     7     |         Status              | Status Customer Aktif/Off                          |


- Data Makan.

|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_makanan          | Primary Key                                        |
|     2     |         Nama_makanan        | Nama Makanan                                       |
|     3     |         Harga_makanan       | Harga makanan                                      |
|     4     |         foto_makanan        | Foto makanan                                       |

- Data Order.

|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_Order            | Primary Key                                        |
|     2     |         Id_customer         | Foreign Key                                        |
|     3     |         Id_seller           | Foreign Key                                        |
|     4     |         Id_kurir            | Foreign Key                                        |
|     5     |         status_penjualan    | Notif penjualan on/off                             |
|     6     |         status_pengiriman   | Notif Pengiriman sampai mana                       |
|     7     |         konfirmasi_kurir    | seller akan mengkonfirmasi kurir                   |
|     8     |         konfirmasi_customer | seller akan mengkonfirmasi orderan customer        |

- Data Toko.

|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_toko             | Primary Key                                        |
|     2     |         nama_toko           | nama unik toko agar tidak sama dengan toko lain    |
|     3     |         alamat_toko         | alamat lengkap toko                                |
|     4     |         keterangan          | keterangan lainnya                                 |

- Detail_Orderan

|    No     |          Data               |                 Keterangan                         |
|-----------|-----------------------------|----------------------------------------------------|
|     1     |         Id_detail           | Primary Key                                        |
|     2     |         Id_order            | Foreign Key                                        |
|     3     |         Id_makanan          | Foreign Key                                        |
|     4     |         kuantitas           | jumlah orderan                                     |
|     5     |         keterangan          | keterangan lainnya yang diperlukan                 |
