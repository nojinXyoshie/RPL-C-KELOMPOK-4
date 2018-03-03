# SPMP : PEMESANAN MAKANAN BERBASIS ANDROID 
### BAB I : Pendahuluan

### 1.1 Gambaran Proyek

Aplikasi Ayo Mangan! adalah sistem pemesanan delivery makanan yang berdomisili di Indramayu barbasis android, yang ditujukan untuk masyarakat Indramayu. Aplikasi Ayo Mangan! ini memiliki empat user antara lain sebagai admin, customer, penjual, dan kurir. 

### 1.2 Dokumen - dokumen dalam proyek

1. SPMP(Software Project Management Plant)
2. SRS(Software Requirment Spesification)

### 1.3 Evolusi SPMP

Segala dokumen yang di buat dalam tahapan pembuatan projek ini dirawat oleh salah satu anggota yang diberikan tanggung jawab untuk dokumentasi, tetapi dalam pembuatannya dokumen ini dikerjakan secara bersama oleh tim. Dokumen ini bersifat freeware, jadi siapa saja boleh untuk memanfaatkan dokumen ini untuk hal yang positif. Tentu ada hal-hal yang tidak boleh dilakukan dalam pemanfaatan dokumen ini, seperti menjualbelikan dokumen ini secara ilegal, atapun mengubah dokumen tanpa dasar yang jelas.

### 1.4 Material acuan

Materi yang menjadi acuan dalam pembuatan projek ini menggunakan standar IEEE, karena menyediakan kerangka kerja yang menggabungkan seluruh spektrum proses siklus hidup perangkat lunak. Dan juga standar IEEE untuk membentuk model yang diakui secara internasional dari kehidupan perangkat lunak umum, siklus proses yang dapat direferensikan oleh industri perangkat lunak diseluruh dunia, untuk mempromosikan pemahaman diantara pihak bisnis dengan aplikasi umum serta mengakui proses, kegiatan dan tugas.

### 1.5 Definisi dan akronim (singkatan)

Dalam penulisan dokumen pembuatan projek ini, ada beberapa kata yang mungkin akan sulit dipahami oleh orang awam berikut ini :
- Android
Android adalah suatu sistem operasi yang berjalan pada smatphone saat ini dan menyesuaikan spesifikasi di kelas low-end hingga high-end. Hampir semua vendor saat ini mengembangkan produknya dengan sistem operasi Android, karena peminatnya yang semakin meningkat tajam.

Seiring berkembangnya jaman tentu kita sebagai manusia butuh peralatan yang canggih dan efisien untuk keperluan sehari-hari. Oleh karena itu ada baiknya anda mulai menggunakan perangkat dengan sistem operasi ini, karena teknologi android pun sudah berkembang pesat dan ini sangat saya sarankan.

Tabel I.1 Akronim

| Singkatan | Arti kata |
| --------- | --------- |
| IEEE |	The International Institute ofElectronic and Electrical Engineers |
| SPMP |	Software Project Management Plan |
| SRS |	Software Requirement Specification |


IEEE adalah standar yang mendefinisikan lapisan fisik dan sublapisan media akses kontrol dari lapisan data-link dari standar Ethernet berkabel.

SPMP adalah salah satu dokumentasi untuk merencanakan pembuatan project

SRS adalah dokumen yang digunakan pada tahap pengumpulan/analisis kebutuhankebutuhan.
* SRS	Software Requirement Specification
* DFD	Data Flow Diagram
* ERD	Entity Relationship Diagram
* DBMS	Data Base Management System
    
### 2. Organisasi Proyek
    
### BAB II : 

### 2.1 Model proses
Dalam proyek yang kami buat kita menggunakan model proses V-model.

### 2.2 Struktur organisasi
Project Manajer
Programer
Desain
Analis

### 2.3 Batasan dan antarmuka organisasi.
|     Untuk             |     Dari       |    KAITAN                                                                                                                                                                                                                                                     |
|-------------------|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Manager           | Anggota    | Dimana manager menjadi pengawas dari anggota-anggotanya bilamana saat  anggota lalai dengan tugas-tugasnya manager berhak menegur dan bagi anggota tidak berhak melawan jika ditegur, dan untuk manager sendiri  tidak berhak semena-mena dengan jabatanya. |
| Programmer        | Tester     | Dikala programmer melakukan kesalahan dalam mengkoding, tester memiliki tanggung jawab untuk mengecek kesalahan koding-koding yg dilakukan programmer.                                                                                                      |
| Analisis          | Programmer | Betugas untuk memberi gambaran projek dan alur pengkodingan pada                                                                                                                                                                                            |
| Programmer        | Desainer   | "Bertugas mendesain tampilan aplikasi yang dapat menarik konsumen saat aplikasi dirilis                                                                                                                                                                     |

### 2.4 Lingkup tanggung jawab

| Ketua Tim (Manager) | Bertanggung jawab, mengarahkan, mengatur anggota tim atas  projek  yang sedang dibuat |
|---------------------|---------------------------------------------------------------------------------------|
| Tester              | Menguji dan mencari kesalahan hasil program program projek yang sedang dibuat.        |
| Programmer          | Membuat fungsi program projek yang sedang dibuat.                                     |
| Analisis            | Menganalisa atau  mengoreksi fungsi program                                           |
| Desainer            | Membuat kerangka desain projek yang sedang dibuat                                     |

### BAB III : PROSES MANAJERIAL
### 3.1 Tujuan dan prioritas manajemen 
#### 3.1.1 Prioritas jadwal

Prioritas jadwal yang dilakuakan pada saat ini adalah membuat sistem yang akan dibuat, dokumen  projek, jadwal  kegiatan, struktur pembuatan projek dan organisasi

### 3.1.2 Budget
| No          | Keterangan                                | Satuan | Jumlah Barang | Harga        | Jumlah Harga  |
|-------------|-------------------------------------------|--------|---------------|--------------|---------------|
| 1           | Gaji angota                               | bulan  | 3x4           | Rp.1.500.000 | Rp.18.000.000 |
| 2           | Sublime                                   | buah   | 1             | Rp.5000      | Rp.5000       |
| 3           | Xampp                                     | buah   | 1             | Rp.5000      | Rp.5000       |
| 4           | Web Browser                               | buah   | 1             | Rp.5000      | Rp.5000       |
| 5           | Android Studio , JDK dan plugin-pluginnya | set    | 1             | Rp.5000      | Rp.5000       |
| 6           | Sewa komputer                             | set    | 3x4           | Rp.500.000   | Rp.6.000.000  |
| 7           | Sewa mobile                               | buah   | 1             | Rp.380.000   | Rp.380.000    |
| 8           | Wifi                                      | set    | 1             | Rp.2.000.000 | Rp.2.000.000  |
| Total Biaya |                                           |        |               |              | Rp.26.400.000 |

### 3.1.3 Kemampuan 

Projek yang kami buat saat ini mempunyai kelebihan dalam memudahkan seseorang  untuk mengembangkan dan mengelola bisnisnya di bidang kuliner dan memudahkan orang untuk membeli makanan pesan antar lewat aplikasi android. Kelebihan produk antara lain :

* mampu melihat tracking saat kurir mengirim barang
* fitur chat dan telepon antara kurir dan pembeli


### 3.2 Asumsi, Keterkaitan, dan batasan
            
### 3.2.1 Asumsi
Adapun aplikasi yang kami buat adalah sejenis aplikasi pemesanan makanan berbasis android , guna memesan dan mengantar makanan pada tempat tujuan pembeli .    

### 3.2.2 Keterkaitan dan Batasan
Dalam projek yang kami buat maka aplikasi yang  kelola oleh admin diakses melalui device PC/Laptop yang menggunakan  aplikasi web. Sedangkan penjual , pembeli , dan kurir menggunakan aplikasi android yang diakses melalui device smartphone. 

### 3.3 Manajemen resiko
### 3.3.1 Resiko Proyek
| Resiko                                    | Teknik manajemen resiko                                           |
|-------------------------------------------|-------------------------------------------------------------------|
| Biaya dan waktu tidak sesuai              | membuat biaya estimasi                                            |
|                                           | menambah waktu dalam pengerjaan projek                            |
|                                           | menganalisa projek yang akan di buat                              |
|                                           |                                                                   |
| Pengembangan software yang belum maksimal | evaluasi untuk meningkatkan projek                                |
|                                           | membuat metode dan spesifikasi                                    |
|                                           | buat prototype                                                    |
|                                           |                                                                   |
| kegagalan pada komponen-komponen          | mencari referensi-referensi menganalisis projek yang akan di buat |
|                                           |                                                                   |
| kegagalan kinerja realtime                | prosedur jaminan kualitas                                         |
|                                           | membangun kekompakan tim                                          |
|                                           | kesungguhan dalam tim                                             |
|                                           |                                                                   |
| kegagalan memjalankan tugas eksternal     | analisis teknis                                                   |
|                                           | simulasi                                                          |


### 3.4 Mekanisme monitoring dan kontroling 
### 3.4.1 Monitoring
Proses monitoring dilakukan secara tim dan dilaksanakan setiap hari senin
### 3.4.2 Kontroling
Proses kontroling dilakukan oleh manager tim dan dilaksanakan setiap hari jumat agar bisa dievaluasi pada hari terakhir kegiatan
### 3.5 Perencanaan staf 
* Project Manager  	 : Irin Windiyati
* Programmer		 : Yoshie Pangestu
* Desainer 		: Nunung Nurhayati
* Analysis	       	 : Dina Micela

### BAB IV: PROSES TEKNIS
### 4.1 Metoda,tool,dan teknik
### 4.2 Dokumentasi perangkat lunak
### 4.3 Fungsi-fungsi pendukung proyek



### BAB V : PAKET PEKERJAAN, JADWAL DAN BUDGET

## 5.1 Paket pekerjaan
                    Tabel Paket Pekerjaan

  | Bulan                   |  Februari  |    Maret   |   April    |    Mei     |
  --------------------------|------------|------------|------------|-------------
  | Minggu                  | 1  2  3  4 | 1  2  3  4 | 1  2  3  4 | 1  2  3  4 |
  
  
                    Kategori Kegiatan      

  |  Nama                   |            |            |            |            |
  --------------------------|------------|------------|------------|------------|
  |  1. Irin Windiyati      | A  B  B  E | V  V  V  V | C  C  C  C | D  E  F    |
  |  2. Yoshie Pangestu     | A  B  B  E | V  V  V  V | C  C  C  C | D  E  F    |
  |  3. Dina Micela W       | A  B  B  E | V  V  V  V | C  C  C  C | D  E  F    |
  |  4. Nunung Nurhayati    | A  B  B  G | G  C  C  C | C  C  C  C | D  E  F    |
  
 <br> Kategori Kegiatan :

* (A) : Persiapan projek dan pengumpulan sumber daya yg diperlukan.
* (B) : Waktu pengerjaan dokumen-dokumen.
* (C) : Proses Pembuatan Aplikasi
* (D) : Pengujian Aplikasi 
* (E) : Pengecekan Hasil Projek
* (F) : Perbaikan Projek
* (G) : Pengerjaan Laporan
* (H) : Presentasi

### 5.2 Ketergantungan/keterkaitan
Dalam proses pengerjaan proyek yang kami buat ini, keterkaitan dari tugas masing-masing saling membantu agar terbentuknya ketelitian saat mengerjakan dan mendapatkan hasil yang bagus. Berikut adalah perinciannya.

            Tabel ketergantungan dan keterkaitan

|  Dari       |  Tugas Untuk  |   Keterkaitan                                                          |
--------------|---------------|-------------------------------------------------------------------------
| Manager     | Anggota       | Tugas manager adalah mengawasi anggota-anggotanya jika saat mengerjakan|
|             |               | projek anggotanya lalai dalam mengerjakan tugas tersebut berhak untuk  |
|             |               | menegur anggota dan yg menjadi anggota tidak berhak untuk melawan.     |
| Programmer  | Manager       | Salah satu tugas Tester yaitu untuk mengecek jika saat programmer salah|
|             |               | dalam melakukan pengkodingan tersebut agar bisa langsung di perbaiki.  |
| Analisis    | Programmer    | Yang bertugas sebagai analisis yaitu memberi suatu gambaran projek dan |
|             |               | pengkodian pada programer.                                             |
| Manager     | Programmer    | Bertugas sebagai memberi masukan-masukan kepada Programer untuk membuat|
|             |               | program yang sedang di buat.                                           |
| Design      | Programmer    | Bertugas mendesign tampilan aplikasi lalu dedign tersebut diberikan ke |
|             |               | programmer agar tampilan aplikasi sesuai dengan design yg dibuat.      |


### 5.3 Kebutuhan-kebutuhan sumber daya
Untuk pembuatan aplikasi ini akan dikerjakan oleh 4 (empat) orang, dapat dilihat pada tabel berikut ini.

            Tabel kebutuhan sumber daya

| No   Nama Personal     |    Job               |
|------------------------|----------------------|
| 1.   Irin Windiyati    |   Manager            |
| 2.   Yoshie Pangestu   |   Programmer         |
| 3.   Nunung Nurhayati  |   Design             |
| 4.   Dina Micela       |   Sistem Analis      |


### 5.4 Alokasi budget dan sumber daya
Berikut adalah rincian biaya yang diperlukan untuk pengerjaan proyek kami, dapat dilihat pada tabel dibawah ini.

Estimasi biaya software

            Tabel Estimasi biaya software
            
|No    Kebutuhan Software  | Biaya          |
|--------------------------|----------------|
| 1. Windows 7 or Higher   | Rp. 1.100.000,-|
| 2. Android Studio        | Rp. 500.000,-  |
| 3. Xampp                 | Rp. 500.000,-  |
| 4. Sublime               | Rp. 500.000,-  |

### 5.5 Jadwal


![image](http://i63.tinypic.com/1zy8x6t.png)

