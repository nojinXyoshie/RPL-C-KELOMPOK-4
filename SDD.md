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

###3.3 Dekomposisi Data.<br>
Data User Customer, Seller, Kurir, Admin.

|    No     |   Data            |        Keterangan                                  |
|-----------|-------------------|----------------------------------------------------|
|     1     | Email, No.Telepon | Digunakan Untuk Login Customer                     |
|     2     | Email, No.Telepon | Digunakan Untuk Login seller                       |
|     3     | Email, No.Telepon | Digunakan Untuk Login Kurir                        |
|     4     | Email, No.Telepon | Digunakan Untuk Login Admin                        |
