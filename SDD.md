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
##### BAB I : PENDAHULUAN <br>
Berisi overview perangkat lunak yang merupakan ringkasan terhadap kemampuan aplikasisecara umum. <br>
##### BAB II : DESKRIPSI PERANCANGAN GLOBAL<br>
Berisi perancangan global dari perangkat lunak yang meliputi perancangan lingkungan operasidimana perangkat lunak akan dioperasikan, deskripsi dari data yang digunakan oleh perangkatlunak, serta dekomposisi lojik dari modul-modul perangkat lunak.<br>
##### BAB III	: DESKRIPSI PERANCANGAN RINCI<br>
Berisi deskripsi lengkap dan rinci dari kebutuhan perangkat lunak yang meliputi deskripsi rincidari tabel yang digunakan, perincian dari setiap fungsi yang ada pada rancangan global,dekomposisi fisik dari modul –modul perangkat lunak, serta matriks kerunutan yangmenggambarkan keterkaitan antara perancangan dengan spesifikasi kebutuhan.<br>

### Bab 2 : Deskripsi Perancangan Global ###
#### 2.1 Rancangan Lingkungan Implementasi
Pada Proses Pembuatan Aplikasi, hal-hal yang mendukung dalam pemrosesan pembuatan aplikasi seperti :<br>
a. Bahasa Pemrograman<br>
Pada Admin (Web) menggunakan bahasa pemrograman PHP, HTML, Bootstrap dan CSS.
Pada costomer, seller, & kurir (Mobile) dalam pembuatannya menggunakan bahasa pemrograman android (java).<br>
b. DBMS<br>
DBMS yang digunakan adalah Mysql<br>
c. Development Tools<br>
Android Studio
Sublime text 3<br>

#### 2.2 Deskripsi Data<br>

* TABLE Admin<br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| Id_Admin        | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Admin           |
| Nama            | Varchar   |    50     |    Tidak    |     Tidak      |        -             |         Nama Admin            |
| Email           | Varchar   |    30     |    Tidak    |     Tidak      |        -             |        Email Admin            |
| Password        | Varcahar  |    20     |    Tidak    |     Tidak      |        -             |        Password Admin         |
| No_Hp           | Integer   |    15     |    Tidak    |     Tidak      |        -             |        No_Hp Admin            |

<br>

* TABLE Customer<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| Id_Customer     | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Customer        |
| Nama_Customer   | Varchar   |    50     |    Tidak    |     Tidak      |        -             |         Nama Customer         |
| Email           | Varchar   |    25     |    Tidak    |     Tidak      |        -             |        Email Customer         |
| Password        | Varcahar  |    25     |    Tidak    |     Tidak      |        -             |        Password Customer      |
| No_Hp           | Integer   |    15     |    Tidak    |     Tidak      |        -             |        No_Hp Customer         |
| Alamat          | Varcahar  |    50     |    Tidak    |     Tidak      |        -             |        Alamat Customer        |
| Status          | Tinyint   |     1     |    Tidak    |     Tidak      |        -             |    Status Review ke seller    |
<br>

* TABLE Data_makanan<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| Id_Makanan      | Varchar   |    15     | Primary key |      Iya       | Id_Makanan pada Makanan | Relasi untuk menampilkan Menu Makanan |
| Nama_makanan    | Varchar   |    50     |    Tidak    |     Tidak      |        -             |         Nama Makanan          |
| Harga_makanan   | VInteger  |    15     |    Tidak    |     Tidak      |        -             |        Harga Pada makanan     |
| Foto            | Blob      |     -     |    Tidak    |     Tidak      |        -             |       Foto Makanan            |

<br>

* TABLE Data_order<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| Id_order        | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Customer         |
| id_customer     | Varchar   |    15     | Foreign key |      Iya       | Id_customer dari Customer|                           |
| id_kurir        | Varchar   |    15     | Foreign key |      Iya       | Id_kurir dari kurir      |                           |
| id_seller       | Integer   |     5     | Foreign key |      Iya       | Id_seller dari seller    |                           |
|status_penjualan | Tinyint   |     1     |    Tidak    |     Tidak      |        -             |    Status penjualan aktif/off     |
|status_pengiriman| Tinyint   |     1     |    Tidak    |     Tidak      |        -             |    status pengiriman jarak        |
|konfirmasi_kurir | Tinyint   |     1     |    Tidak    |     Tidak      |        -             |Tracking kurir untuk mengirim orderan|
|konfirmasi_customer | Tinyint   |  1     |    Tidak    |     Tidak      |        -             |Konfirmasi Orderan dari customer|

<br>

* TABLE Data_toko<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| Id_toko         | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Toko            |
| Nama_toko       | Varchar   |    50     |    Tidak    |     Tidak      |        -             |       Nama unik toko          |
| Alamat_toko     | Varchar   |    50     |    Tidak    |     Tidak      |        -             |        Alamat toko            |
| Keterangan_toko | Varcahar  |    50     |    Tidak    |     Tidak      |        -             |  Ketarangan tambahan toko     |

<br>

* TABLE Data_detail_toko<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| id_detail       | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Detail order    |
| id_order        | Varchar   |    50     | Foreign key |     Tidak      |        -             |       Id order                |
| id_makanan      | Varchar   |    30     | Foreign key |     Tidak      |        -             |       Id menu makanan         |
| kuantitas       | Varcahar  |    20     |    Tidak    |     Tidak      |        -             |                               |
| keterangan      | Integer   |    15     |    Tidak    |     Tidak      |        -             |  keterangan tambahan order    |

<br>

* TABLE Kurir<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| id_kurir        | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Detail order    |
| id_seller       | Varchar   |    50     | Foreign key |     Tidak      |        -             |       Idseller                |
| nama_kurir      | Varchar   |    30     |    Tidak    |     Tidak      |        -             |     menampilkan nama kurir    |
| email           | Varcahar  |    20     |    Tidak    |     Tidak      |        -             |       email pengguna kurir    |
| password        | Varcahar  |    15     |    Tidak    |     Tidak      |        -             |    password pengguna kurir    |
| no_hp           | Integer   |    20     |    Tidak    |     Tidak      |        -             |       no_hp pengguna kurir    |
| status          | tinyint   |     1     |    Tidak    |     Tidak      |        -             |           status on/off       |

<br>

* TABLE Review<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| id_review       | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Detail order    |
| id_seller       | Varchar   |    15     | Foreign key |     Tidak      | id_seller pada seller| Relasi untuk mneampilkan seller|
| id_customer     | Varchar   |    15     | Foreign key |     Tidak      | id_customer pada customer|Relasi untuk menampilkan customer|
| id_status       | Varcahar  |    15     | Foreign key |     Tidak      | id_status pada status|Relasi untuk menampilkan status|
| pesan           | Varcahar  |    50     |    Tidak    |     Tidak      |        -             |Menampilkan pesan pada status

<br>

* TABLE Seller<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| id_seller       | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Detail order    |
| id_toko         | Varchar   |    15     | Foreign key |     Tidak      | Id_toko pada seller  |    Relasi menampilkan toko    |
| nama_seller     | Varchar   |    50     |    Tidak    |     Tidak      |        -             |     menampilkan nama seller   |
| email           | Varcahar  |    25     |    Tidak    |     Tidak      |        -             |       email pengguna seller   |
| password        | Varcahar  |    15     |    Tidak    |     Tidak      |        -             |    password pengguna seller   |
| no_hp           | Integer   |    15     |    Tidak    |     Tidak      |        -             |       no_hp pengguna seller   |
| status          | tinyint   |     1     |    Tidak    |     Tidak      |        -             |           status on/off       |

<br>

* TABLE Status_riview<br><br>

|   Nama Field    |   Jenis   |   Volume  |   Laju      |   Primary Key  | Constraint integrity |     Deskripsi                 |
|-----------------|-----------|-----------|-------------|----------------|----------------------|-------------------------------|
| id_status       | Varchar   |    15     | Primary key |      Iya       | Auto_increment       |       Id Auto Detail order    |
| Arah review     | tinyint   |     1     |    tidak    |     Tidak      |         -            |     Menampilkan arah review   |

<br>

#### 2.2.1 Definisi Domain/type<br>
* TABLE Admin<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_admin        | Primary key|
| Nama            |   Varchar  |
| Email           |   Varchar  |
| Password        |   Varcahar |
| No_Hp           |   Integer  |

<br>

* TABLE Customer<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_customer     | Primary key|
| Nama_Customer   | Varchar   |
| Email           | Varchar   |
| Password        | Varcahar  |
| No_Hp           | Integer   |
| Alamat          | Varcahar  |
| Status          | Tinyint   |

<br>

* TABLE Data_makanan<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| Id_Makanan      | Varchar   |
| Nama_makanan    | Varchar   |
| Harga_makanan   | VInteger  |
| Foto            | Blob      |

<br>

* TABLE Data_order<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| Id_order        | Varchar   |
| id_customer     | Varchar   |
| id_kurir        | Varchar   |
| id_seller       | Integer   |
|status_penjualan | Tinyint   |
|status_pengiriman| Tinyint   |
|konfirmasi_kurir | Tinyint   |
|konfirmasi_customer | Tinyint   |

<br>

* TABLE Data_toko<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| Id_toko         | Varchar   | 
| Nama_toko       | Varchar   |
| Alamat_toko     | Varchar   |
| Keterangan_toko | Varcahar  |

<br>

* TABLE Detail_toko<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_detail       | Varchar   |
| id_order        | Varchar   |
| id_makanan      | Varchar   |
| kuantitas       | Varcahar  |
| keterangan      | Integer   |

<br>

* TABLE Kurir<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_kurir        | Varchar   |
| id_seller       | Varchar   |
| nama_kurir      | Varchar   |
| email           | Varcahar  |
| password        | Varcahar  |
| no_hp           | Integer   |
| status          | tinyint   |

<br>

* TABLE Review<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_review       | Varchar   |
| id_seller       | Varchar   |
| id_customer     | Varchar   |
| id_status       | Varcahar  |
| pesan           | Varcahar  |

<br>

* TABLE Seller<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_seller       | Varchar   |
| id_toko         | Varchar   |
| nama_seller     | Varchar   |
| email           | Varcahar  |
| password        | Varcahar  |
| no_hp           | Integer   |
| status          | tinyint   |

<br>

* TABLE Status_riview<br><br>

|    Domain Type  |  Deskripsi |
|-----------------|------------|
| id_status       | Varchar   |
| Arah review     | tinyint   |

<br><br>

#### 2.2.2 Conceptual Data Model
<div style="text-align:center"><img src="http://i66.tinypic.com/jfetf4.png"/></div><br>

#### 2.2.3 Physical Data Model
#### 2.2.4 Daftar Tabel Aplikasi
#### 2.3 Deskripsi Modul

|    No     |          Nama Modul          |                 Keterangan                                                    |
|-----------|------------------------------|-------------------------------------------------------------------------------|
|     1     |         Seller               | Modul yang mencakup input, edit, delete dan update semua data seller/toko     |
|     2     |         Kurir                | Modul yang mencakup input, edit, delete dan update semua data kurir           |
|     3     |         Customer             | Modul yang mencakup input dan edit semua data customer                        |
|     4     |         Register             | Modul yang di gunakan untuk akses sebelum login/masuk ke aplikasi Ayo Mangan  |
|     5     |         Login                | Modul yang di gunakan untuk akses masuk ke Aplikasi Ayo Mangan di web/android |
|     6     |         Tracking             | Modul yang di gunakan untuk melihat lokasi customer/kurir                     |



### Bab 3 : Deskripsi Perancangan Rinci ###
#### 3.1 Diagram Konteks
Diagram konteks adalah diagram yang terdiri dari suatu proses dan menggambarkan ruang lingkup suatu sistem. Diagram konteks merupakan level tertinggi dari DFD yang menggambarkan seluruh input ke dalam sistem atau output dari sistem yang memberi gambaran tentang keseluruhan sistem. Sistem dibatasi oleh boundary (Digambarkan dengan garis putus - putus). Dalam diagram konteks hanya ada satu proses, tidak boleh ada store dalam diagram konteks. Berikut ini adalah gambar diagram konteks dari sistem Aplikasi Ayo Mangan.<br>
<div style="text-align:center"><img src="http://i64.tinypic.com/121coxh.jpg"/></div>

#### 3.1.1 DFD level 0
Flow Data Flow Diagram merupakan cara untuk memodelkan proses dalam analisis dan perancangan perangkat lunak, dan merupakan penjelasan dari context diagram. Dalam aplikasi ini terdapat 8 proses yaitu mengelola customer,mengelola order,mengelola review,mengelola seller,mengelola data_toko,mengelola data_makanan,mengelola kurir,mengelola admin.<br>
<div style="text-align:center"><img src="http://i65.tinypic.com/23vxrg2.jpg"/></div><br>

#### 3.2 Dekommposisi Proses Konkuren
#### 3.2.1 DFD Level 1 : Proses 1 (mengelola data customer)
DFD level 1 merupakan rincian dari dari level 0, dan pada dfd level 1 mengelola data customer terdapat 4 proses yaitu menambah data customer,menghapus data customer,mengubah data customer,melihat data customer.<br>
<div style="text-align:center"><img src="http://i65.tinypic.com/ruoabt.jpg"/></div><br>

#### 3.2.2 DFD Level 1 : Proses 2 (mengelola data order)
<div style="text-align:center"><img src="http://i64.tinypic.com/egpteh.jpg"/></div><br>
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...

#### 3.2.3 DFD Level 1 : Proses 3 (mengelola data riview)
<div style="text-align:center"><img src="http://i68.tinypic.com/vr9d0i.jpg"/></div><br>
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...

#### 3.2.4 DFD Level 1 : Proses 4 (mengelola data seller)
DFD level 1 merupakan rincian dari dari level 0, dan pada dfd level 1 mengelola data seller terdapat 4 proses yaitu menambah data seller,menghapus data seller,mengubah data seller,melihat data seller.<br>
<div style="text-align:center"><img src="http://i66.tinypic.com/2rnu1dg.jpg"/></div><br>

#### 3.2.5 DFD Level 1 : Proses 5 (mengelola data toko)
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...

#### 3.2.2 DFD Level 1 : Proses 6 (mengelola data makanan)
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...

#### 3.2.2 DFD Level 1 : Proses 7 (mengelola data kurir)
<div style="text-align:center"><img src="http://i65.tinypic.com/2m81w28.gif"/></div><br>
DFD Level 1 ini penjelasan dari DFD level 0 yang sebelumnya, Berikut DFD level 1 yg menjelaskan ...

#### 3.3 Dekommposisi Data
(tabel-tabel database yang digunakan pada DFD)
#### 3.3.1.1 Fungsi Modul

|    No     |         Fungsi              |           Jenis         |      Tabel Terkait       |
|-----------|-----------------------------|-------------------------|--------------------------|
|     1     |                             |                         |                          |
|     2     |                             |                         |                          |
|     3     |                             |                         |                          |
|     4     |                             |                         |                          |
|     5     |                             |                         |                          |
|     6     |                             |                         |                          |

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
