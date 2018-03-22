<html>
<body>
<body><div align="center"><h1>Software Requirement Spesification</h1></div>
<p align="center"><b>Version 1.0 </b><br>
<p align="center">4 Maret 2018<br><br>
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


### BAB I : Pendahuluan
#### 1.1 Tujuan
Tujuan dari penulisan dokumen Softaware Requirement Specification (SRS) untuk mempermudah mengembangkan perangkat lunak yang kami buat dan memberikan gambaran yang spesifik dari kebutuhan softaware. Spesifikasi kebutuhan tersebut termasuk dari segi perangkat lunak dan perangkat keras,untuk memberikan gambaran dan penjelasan mengenai pembuatan produk termasuk kebutuhan fungsional hingga non-fungsional, dan kebutuhan antar muka mulai dari antar muka pengguna hingga antar muka komunikasi.

#### 1.2 Lingkup
Ruang lingkup dalam membangun aplikasi yaitu Delivery online menggunakan smartphone. Aplikasi ini perlu dibuatkannya karena untuk mempermudah penjual dan pembeli dalam bertransaksi jarak jauh.

#### 1.3 Definisi, Akronim, Singkatan

Singkatan | Definisi 
| ------ | ------ |
| SRS | Merupakan singkatan dari Software Requirement Specfication |
| Webserver | Webserver sebuah software yang memberikan layanan berbasis data dan berfungsi menerima permintaan dari HTTP atau HTTPS pada klien yang dikenal dan biasanya kita kenal dengan nama web browser (Mozilla Firefox, Google Chrome) dan untuk mengirimkan kembali yang hasilnya dalam bentuk beberapa halaman web dan pada umumnya akan berbentuk dokumen HTML. |
| SPMP | Merupakan singkatan dari Software Project Management Plan. |

#### 1.4 Referensi
IEEE. IEEE Std 830-1998 Praktik yang Direkomendasikan IEEE untuk Persyaratan Perangkat Lunak
Spesifikasi. IEEE Computer Society, 1998.

#### 1.5 Overview

Pada dokumen ini memberikan penjelasan tentang gambaran umum, termasuk karakterisitik pengguna proyek ini, hardware produk, dan persyaratan fungsional seperti data siswa/guru pada instansi yag terkait yang digunakan untuk persyaratan penginputan data. Gambaran umum ini dibahasan pada bagian 2 yang terdiri dari prespektif produk,antarmuka sistem, antarmuka pengguna,antarmuka perangkat keras,antarmuka perangkat lunak sampe anatrmuka komunikasi. Hal ini juga dapat memberikan suatu kebutuhan yang terdapat pada aplikasi Ayo Mangan!.

### BAB II : Gambaran Umum

#### 2.1 Perspektif produk
Produk yang dirancang merupakan sebuah perangkat lunak berbasis android
dimana akan dapat digunakan secara online oleh pihak-pihak berkepentingan.

#### 2.1.1 Antarmuka sistem
<p align="center">
<img src="http://i64.tinypic.com/14jvlzd.jpg"/>
</p>

#### 2.1.2 Antarmuka pengguna
#### * Kurir
<p align="center">
<img src="http://i67.tinypic.com/wu4cx2.png"/>
</p>
Detail order
<p align="center">
<img src="http://i66.tinypic.com/avpv2x.png"/>
</p>
Proses tracking
<p align="center">
<img src="http://i64.tinypic.com/vipudc.png"/>
</p>
Setelah kurir mengantarkan pesanan, lalu diterima customer, maka kurir harus mengkonfirmasi kepada seller bahwa pesanan telah sampai/diterima.

#### * Seller
<p align="center">
<img src="http://i66.tinypic.com/2ap5cj.jpg"/>
</p>

-	Profil toko : untuk mengetahui informasi toko, seller dapat mengedit informasi tokonya sendiri.
-	Alamat saya : alamat seller/toko
-	Produkku : menampilkan seluruh jenis makanan yg sudah di upload
-	Tambah produk baru : untuk mengupload menu baru
-	Kurirku : untuk mengecek posisi kurir.

<p align="center">
<img src="http://i68.tinypic.com/2qtlurk.png"/>
</p>
Sunting profil seller

#### * Customer
<p align="center">
<img src="http://i65.tinypic.com/16ixkk4.jpg"/>
</p>
Customer harus login/masuk terlebih dahulu sebelum masuk ke menu home
<p align="center">
<img src="http://i65.tinypic.com/2ziygzt.png"/>
</p>
Setelah login/masuk muncul tampilan home
<p align="center">
<img src="http://i64.tinypic.com/2dipwlv.png"/>
</p>
Tampilan timeline akan menampilkan menu-menu makanan
<p align="center">
<img src="http://i65.tinypic.com/23uafjt.png"/>
</p>
Setelah memilih menu makanan, customer melakukan order makanan
<p align="center">
<img src="http://i66.tinypic.com/dbtzc1.png"/>
</p>
Tampilan Keranjang
<p align="center">
<img src="http://i65.tinypic.com/20j2wb9.png"/>
</p>
Profil Customer

#### * Admin
<p align="center">
<img src="http://i64.tinypic.com/21mfbqa.png"/>
</p>
Login admin
<p align="center">
<img src="http://i64.tinypic.com/bdqtqu.png"/>
</p>
Dashboard admin
<p align="center">
<img src="http://i67.tinypic.com/15qdxcl.png"/>
</p>
Data makanan
<p align="center">
<img src="http://i67.tinypic.com/1zohtht.png"/>
</p>
Data seller


#### 2.1.3 Antarmuka perangkat keras
Kebutuhan minimum perangkat keras yang dapat digunakan untuk mendukung aplikasi adalah :
- PC
- Mouse
- Keyboard
- Smartphone 

#### 2.1.4 Antarmuka perangkat lunak
- Aplikasi dapat diakses jika terhubung dengan internet dan memiliki OS android
- Webserver
Untuk Web admin dapat di akses menggunakan semua jenis browser, dan harus menggunakan akses internet .
- Bahasa pemrograman menggunakan JAVA
- Database Engine Xampp


#### 2.1.5 Antarmuka komunikasi
Yang dibutuhkan hanya sebuah komputer server dan satu atau
beberapa komputer client yang terhubung secara client-server dalam
lingkup jaringan Internet atau intranet berbasis protokol Transmission
Control Protocol/Internet Protocol (TCP/IP).

#### 2.1.6 Batasan-batasan Memori
- RAM yang kami gunakan adalah 8Gb, tapi untuk kapassitas minimum 4Gb
- Kapasitas minimum memori yang dibutuhkan untuk aplikasi minimal 512Mb

#### 2.1.7 Operasi-operasi
- Login melalui aplikasi, masuk sebagai customer, kurir dan seller
- Seller dapat mengupload foto makanan dan menginput data menu makanan melalui aplikasi
- Login melalui web, masuk sebagai admin untuk mengelola data seller
- Kurir dapat tracking alamat customer melalui aplikasi
- Customer dapat mengorder makanan melalui aplikasi, tracking kurir dan konfirmasi orderan telah sampai.

#### 2.1.8 Kebutuhan-kebutuhan dalam tahapan Adaptasi
- Pemakaian database sebagai sarana penyimpanan data.
- PL menggunakan bahasa Indonesia agar mudah dipahami oleh user tetapi ada juga beberapa yang menggunakan bahasa inggris.
Untuk promosi aplikasi ini dilakukan melalui sosial media, agar pengguna dapat mengetahui informasi aplikasi tersebut.

#### 2.2 Spesifikasi kebutuhan fungsional

2.2.1 Customer
<p align="center"><img src="http://i64.tinypic.com/n62kj8.png"/></p>

Deskripsi :
Customer akan login terlebih dahulu kemudian memilih makanan yang akan diorder, setelah menginput data yang diperlukan maka customer dapat mengorder. setelah itu customer dapat tracking kurir untuk memastikan posisi orderan dan setelah barang sampai maka customer akan melakukan konfirmasi melalui aplikasi bahwa orderan telah sampai.

2.2.2 Seller

<p align="center">
 <img src="http://i68.tinypic.com/11qts9g.png"/>
</p>


2.2.3 Kurir
<p align="center"><img src="http://i66.tinypic.com/xkpzpe.png"/></p>

2.2.4 Admin
<p align="center"><img src="http://i68.tinypic.com/1pjolc.png"/></p>


#### 2.3. Spesifikasi kebutuhan non-fungsional
-	Ganti password.
-	Tampilan layout service.
-	Lupa password.
- Edit profile.

#### 2.4 Karakteristik Pengguna
Untuk mengoperasikan aplikasi ini tidak diperlukan tingkat pendidikan tinggi, namun pengguna cukup memahami cara menggunakan smartphone dan penggunaan dalam sebuah aplikasi ini.
karakteristik pengguna dari aplikasi Ayo Mangan  adalah semua yang ingin menggunakan aplikasi ini diantaranya pedagang perumahan, maupun yang sudah memiliki tempat berjualan dan masyarakat  yang membedakan adalah pengguna yang berinteraksi dengan aplikasi yang dihubungkan dengan hak akses dan  autentifikasi sesuai aturan yang terdapat pada aplikasi ini, dimana aplikasi ini cara kerja nya ialah memesan makanan lewat online.

#### 2.5 Batasan-batasan.
Pengembangan Aplikasi pemesanan makanan berbasis mobile ini memiliki keterbatasan-keterbatasan yaitu sebagai berikut  :
-	Sistem Sistem Administrasi pemesanan makanan ini akan di buat menggunakan Android studio, MySql, PHP, dan html
-	Aplikasi bersifat android
- Pengembangan aplikasi Ayo Mangan ini akan meliputi pengelolaan data-data yang ada diadmin yang meliputi data toko, dan seller

#### 2.6 Asumsi dan ketergantungan/keterkaitan.
- Admin bisa melihat sistem secara keseluruhan dan dapat merubah data-data seller, Admin hanya mengatur data-data seller 
- Seller atau Owner bisa melihat sistem secara keseluruhan dan dapat merubah data-data tokonya sendiri
- Bagian costumer mempunyai wewenang untuk melakukan pemesanan makanan serta konfirmasi jika orderan telah sampai.

#### 2.7 kebutuhan-kebutuhan penyeimbang.

### BAB III : Kebutuhan Spesifik.

#### 3.1 kebutuhan antarmuka

Kebutuhan akan pengelolaan/management pada suatu instansi sangatlah penting dengan menimbang beberapa aspek yang saling mendukung, pada hal ini tertuju pada pebisnis rumahan yang berdomisili di Indramayu dimana penerapan management/pengelolaan pemesanan nya sudah semestinya menggunakan komputerisasi untuk dapat memperkecil terjadinya human error pada pengerjaannya. Seller dan Customer yang bersangkutan sangatlah terbantu untuk meningkatkan efesiensi waktu dikarenakan fitur dari aplikasi ini menunjang kedua pihak antara seller dan customer untuk dapat berjual-beli jarak jauh tanpa harus face to face, dengan ini juga kedua pihak antara seller dan cutomer dapat memantau kurir yang memngantarkan orderan melalui fitur tracking di dalam aplikasi.

Kebutuhan akan pengelolaan/management pemasaran  pada suatu pembisnis di bidang kuliner sangatlah penting dengan menimbang beberapa aspek yang saling mendukung, pada hal ini tertuju pada pedagang rumahan maupun yang sudah memiliki tempat jualan/lapak dimana penerapan management/pengelolaan pemasaran sudah semestinya menggunakan komputerisasi untuk dapat menghindari  terjadinya kesalahan dalam pelayanan secara manual, pedagang rumahan sangatlah terbantu untuk meningkatkan perekonomian di era global. Selain hal demikian, management/pengelolaan pemesanan makanan yang terkomputerisasi dapat membantu masyarakat yang malas keluar rumah untuk mencari makan yang  dimana harus mendatangi rumah makan dan mengantri , sekarang bisa menggunakan cara praktis dengan cara pemesanan makanan melalui aplikasi “AYO MANGAN”

#### 3.2 Kebutuhan Fungsional
### Customer
##### Login

| Nama Fungsi    | Login                                                                      |
|----------------|----------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Login                                                           |
| Trigger        | Membuka Aplikasi Ayo Mangan!, dan sudah terdaftar                          |
| Precondition   | Login untuk Customer                                |
| Basic Path     | User sudah terdaftar, jika sudah terdaftar maka bisa langsung menggunakan  |
|                | aplikasi yang menampilkan Home/Dashboard sebagai halaman utamanya          |
| Alternative    | Tidak Ada                                                                  |
| Post Condition | User dapat melihat Halaman utama Aplikasi dan dapat mengakses yang lainnya |
| Exception Push | Tidak ada koneksi                                                          |
|                | User belum mendaftar ke aplikasi                                           |

##### Order Makanan

| Nama Fungsi    | Order Makanan                                                              |
|----------------|----------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Oder Makanan                                                    |
| Trigger        | Membuka Aplikasi Ayo Mangan!, dan sudah terdaftar                          |
| Precondition   | Menampilkan data menu makanan dan list orderan                             |
| Basic Path     | Customer Login ke dalam Aplikasi                                           |
|                | Customer Melihat Menu Makanan dan dan order makanan                        |
|                | Aplikasi dapat menampilkan Menu makanan dan List orderan                   |
| Alternative    | Tidak Ada                                                                  |
| Post Condition | User dapat melihat Halaman utama Aplikasi dan dapat mengakses yang lainnya |
| Exception Push | Tidak ada koneksi                                                          |
|                | User belum mendaftar ke aplikasi                                           |

##### Tracking Kurir

| Nama Fungsi    | Tracking Kurir                                                                 |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Oder Tracking Kurir                                                 |
| Trigger        | Untuk melihat lokasi kurir                                                     |
| Precondition   | Menampilkan tracking kurir                                                     |
| Basic Path     | Customer dan Seller login ke dalam Aplikasi                                    |
|                | Customer dan Seller dapat melihat lokasi kurir dengan tracking kurir           |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Customer dan Seller dapat melihat tracking kurir                               |
| Exception Push | Tidak ada koneksi                                                              |
|                | User belum mendaftar ke aplikasi                                               |

##### Telepon

| Nama Fungsi    | Telepon                                                                        |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Telepon                                                             |
| Trigger        | Untuk menghubungi seller dan kurir melalui telpon                              |
| Precondition   | Menghubungi seller dan kurir melalui telpon                                    |
| Basic Path     | Untuk telpon Customer tidak harus login ke dalam Aplikasi                      |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Customer dapat menghubungi seller dan kurir                                    |
| Exception Push | Tidak ada jaringan                                                             |

##### Konfirmasi Orderan Sampai

| Nama Fungsi    | Konfirmasi Orderan Sampai                                                      |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Konfirmasi Orderan Sampai                                           |
| Trigger        | Customer mengkonfirmasi bahwa pesanan sudah diterima                           |
| Precondition   | Menampilkan notifikasi barang sudah diterima/dikonfirmasi                      |
| Basic Path     | User Login ke dalam Aplikasi                                                   |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat melihat list orderan yg sudah sampai                              |
| Exception Push | Tidak ada koneksi                                                              |
|                | User belum mendaftar ke aplikasi                                               |

### Seller
##### Kelola Toko

| Nama Fungsi    | Kelola Toko                                                                    |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Kelola Toko                                                         |
| Trigger        | Untuk menambah menu makanan,update profile toko,menambahkan kurir,menampilkan  |
|                | menu makanan dan menampilkan alamat toko                                       |
| Precondition   | Menampilkan Profile toko                                                       |
| Basic Path     | Seller Login ke dalam Aplikasi                                                 |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat mengelola toko sendiri                                            |
| Exception Push | Tidak ada koneksi                                                              |
|                | User belum mendaftar ke admin/aplikasi                                         |

##### Tambah Kurir

| Nama Fungsi    | Tambah Kurir                                                                   |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Tambah Kurir                                                        |
| Trigger        | Untuk menambahkan kurir                                                        |
| Precondition   | Membuka profil seller klik kurir                                               |
|                | Menginputkan data dan melihat data kurir                                       |
| Basic Path     | Seller Login ke dalam Aplikasi                                                 |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat mengelola kurir                                                   |
| Exception Push | Tidak ada koneksi                                                              |
|                | Seller belum mendaftar ke admin/aplikasi                                       |

##### Terima Order

| Nama Fungsi    | Terima Order                                                                   |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Terima Order                                                        |
| Trigger        | Seller menerima Orderan dari customer                                          |
| Precondition   | Membuka profil seller klik Orderan                                             |
|                | Teruskan ke kurir                                                              |
| Basic Path     | Seller Login ke dalam Aplikasi                                                 |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat melihat orderan masuk                                             |
| Exception Push | Tidak ada koneksi                                                              |
|                | Seller belum mendaftar ke admin/aplikasi                                       |

##### Teruskan Orderan Ke Kurir

| Nama Fungsi    | Teruskan Orderan Ke Kurir                                                      |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Teruskan Orderan Ke Kurir                                           |
| Trigger        | Seller meneruskan Orderan ke kurir                                             |
| Precondition   | Membuka profil seller klik Orderan                                             |
|                | Teruskan ke kurir                                                              |
|                | Kurir memulai tracking                                                         |
| Basic Path     | User Login ke dalam Aplikasi                                                   |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat melihat tracking kurir                                            |
| Exception Push | Tidak ada koneksi                                                              |
|                | Seller belum mendaftar ke admin/aplikasi                                       |

### Kurir
##### Terima teruskan order dari seller

| Nama Fungsi    | Terima teruskan order dari seller                                              |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Terima teruskan order dari seller                                   |
| Trigger        | Kurir menerima orderan yg diteruskan dari seller                               |
| Precondition   | Membuka detail Orderan                                                         |
| Basic Path     | User Login ke dalam Aplikasi                                                   |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | User dapat melihat detail orderan                                              |
| Exception Push | Tidak ada koneksi                                                              |
|                | User belum mendaftar ke admin/aplikasi                                         |

##### Tracking Alamat Customer

| Nama Fungsi    | Tracking Alamat Customer                                                       |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Tracking Alamat Customer                                            |
| Trigger        | Kurir melakukan tracking                                                       |
| Precondition   | Dapat melihat rute jalan dengan maps                                           |
| Basic Path     | User Login ke dalam Aplikasi                                                   |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Seller dapat melihat tracking kurir                                            |
| Exception Push | Tidak ada koneksi                                                              |
|                |User belum mendaftar ke admin/aplikasi                                          |

##### Telepon

| Nama Fungsi    | Telepon                                                                        |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Telepon                                                             |
| Trigger        | Untuk menghubungi seller dan customer melalui telpon                           |
| Precondition   | Menghubungi seller dan customer melalui telpon                                 |
| Basic Path     | Untuk telpon kurir tidak harus login ke dalam Aplikasi                         |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Kurir dapat menghubungi seller dan customer                                    |
| Exception Push | Tidak ada jaringan                                                             |

##### Konfirmasi Orderan Sampai

| Nama Fungsi    | Konfirmasi orderan sampai                                                      |
|----------------|--------------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Konfirmasi orderan sampai                                           |
| Trigger        | Untuk mengkonfirmasi kepada seller bahwa pesanan sudah sampai                  |
| Precondition   | Kurir dan Customer harus konfirmasi ke seller bahwa pesanan sudah sampai       |
| Basic Path     | Kurir harus login ke dalam Aplikasi                                            |
| Alternative    | Tidak Ada                                                                      |
| Post Condition | Kurir dapat mengklik tombol konfirmasi                                         |
| Exception Push | Tidak ada koneksi                                                              |
|                | User belum mendaftar ke admin/aplikasi






#### 3.3 Detail Persyaratan Non-Fungsional
#### 3.3.1 Struktur data logis
<div style="text-align:center"><img src=http://i67.tinypic.com/orrqdz.jpg"/></div><br>
  
Deskripsi data masing-masing entitas data ini adalah sebagai berikut:<br>

### Entitas Customer
|  Data Item   |   Type   |        Deskripsi                                                            |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_customer  | varchar  | Sebagai identitas unik untuk membedakan antara customer-customer yg lainnya |
| Nama         | Varchar  | Nama customer                                                               |
| Email        | Varchar  | Email untuk registrasi akun                                                 |
| Password     | Varchar  | Password sebagai registrasi akun                                            |
| No hp        | Varchar  | Nomor Hp customer                                                           |
| Alamat       | integer  | Alamat customer                                                             |
| Status       | Varchar  | Untuk menandakan bahwa data sudah valid menjadi customer                    |

### Entitas Data_Order
|  Data Item   |   Type   |        Deskripsi                                                            |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_Order     | Varchar |  identitas order                                                            |
| Id_Costomer  | Varchar  |Identitas customer                                                           |
| Id_Kurir     | Varchar | Identitas kurir                                                             |
| Id_Seller    | Varchar  | Identitas seller yang mempunyai toko                                        |
|Status_Penjualan | Boolean | penjualan ini sistemnya online                                            |
| Status_pengirimanan    | Boolean | data alamat dan jarak                                             |
| Konfirmasi_kurir  | Boolean  | kurir yang sudah ditentukan oleh seller/pemilik toko                   |
| Konfirmasi_customer  | Boolean | validasi orderan                                                     |

### Entitas Detail_Order
|  Data Item   |   Type   |        Deskripsi                                                            |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_detail    | Varchar  | Jumlah keterangan barangan                                                  |
| Id_makanan   | Varchar  | menu makanan yang dipilih                                                   |
| Id_order     | Varchar  | identitas order                                                             |
| Kuantitas    | Varchar  | memberikan feedback/ratting                                                 |
| Keterangan   | Varchar  | keterangan lainnya sebagai pelengkap order                                  |

#### Entitas Seller
|  Data Item   |   Type   |          Deskripsi                                                          |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_seller    | Varchar| Sebagai identitas unik untuk membedakan antara seller-seller yg lainnya       |
| No_hp        | integer| Nomor hp Seller                                                               |
| Nama         | Varchar| Nama Seller                                                                   |
| Email        | Varchar| Email untuk registrasi akun                                                   |
| Password     | Varchar| Password untuk registrasi akun			                                          	  |
| Status	      | Varchar| Untuk menandakan Seller sedang aktif                                          |

### Entitas Data_toko
|  Data Item   |   Type   |          Deskripsi                                                          |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_toko      | Varchar  | sebagai identitas untuk membedakan denan toko-toko lain nya                 |
| Id_seller    | Varchar  | Sebagai identitas unik untuk membedakan antara seller-seller yg lainnya     |
| Nama_toko    | Varchar  | nama toko itu sendiri                                                       |
| Alamat       | Varchar  | Alamat Toko                                                                 |
| Keterangan   | Varchar  | data lainnya yang penting                                                   |


### Entitas Data_makanan
|  Data Item   |   Type   |          Deskripsi                                                          |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_makanan   | Varchar  |  daftar makanan yang akan dijual                                            |
| Nama_makanan | Varchar  | sebagai identitas unik nama makanan                                         |
| Harga_makanan| Number   | Harga makanan                                                               |
| Foto         | Blob     |  foto makanan agar menarik customer                                         |
| keterangan   |Varchar   | ketrangan lainnya sebagai pelengkap                                         |

#### Entitas Admin
|   Data Item  |   Type   |         Deskripsi                                                           |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_admin     | Varchar  | Sebagai identitas unik untuk membedakan antara admin-admin yg lainnya       |
| Nama         | Varchar  | Nama admin                                                                  |
| Email        | Varchar  | untuk registrasi akun                                                       |
| Password     | Varchar  | untuk registrasi akun                                                       |
| No_hp        | integer  | Nomor hp admin                                                              |

#### Entitas Kurir
|   Data Item  |   Type   |         Deskripsi                                                           |
|--------------|----------|-----------------------------------------------------------------------------|
| Id_kurir     | Varchar | Sebagai identitas unik untuk membedakan antara kurir-kurir yg lainnya       |
| id_seller    | Varchar  | Nama toko yang bekerja sama                                                 |
| Nama kurir   | Varchar  | untuk  identitas kurir                                                      |
| No_hp        | integer  | Nomor hp kurir                                                              |
| Status Nama  | Varchar  | Untuk menandakan kurir aktif, sedang mengirim pesanan, dan konfirmasi       |
|              |          | orderan telah sampai                                                        |


