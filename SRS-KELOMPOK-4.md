# Software Requirements Spesification
#### Version 1.0
#### 4 Maret 2014

### APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID 

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
<div style="text-align:center"><img src="http://i66.tinypic.com/1z4g5zb.png"/></div>

#### 2.1.2 Antarmuka pengguna
#### * Kurir
<div style="text-align:center"><img src="http://i67.tinypic.com/2dh7038.png"/></div>
Sebelum Kurir memulai tracking kurir harus memilih list orderan terlebih dahulu.
<div style="text-align:center"><img src="http://i66.tinypic.com/2ngr6vd.png"/></div>
Proses tracking
<div style="text-align:center"><img src="http://i64.tinypic.com/jrvinp.png"/></div>
Setelah pesanan diterima oleh customer, kurir harus mengkonfirmasi kepada seller bahwa pesanan telah sampai/diterima.

#### * Seller
<div style="text-align:center"><img src="http://i64.tinypic.com/jrvinp.png"/></div>

-	Profil toko : untuk mengetahui informasi toko, seller dapat menedit informasi tokonya sendiri.
-	Alamat saya : alamat seller/toko
-	Produkku : menampilkan seluruh jenis makanan yg sudah di upload
-	Tambah produk baru : untuk mengupload menu baru
-	Kurirku : untuk mengecek posisi kurir.

#### * Costomer
<div style="text-align:center"><img src="http://i68.tinypic.com/4lodug.png"/></div>
Customer memilih menu makanan
<div style="text-align:center"><img src="http://i64.tinypic.com/n2hedg.png"/></div>
Setelah memilih salah satu menu, lalu customer oder jenis menu makanan
<div style="text-align:center"><img src="http://i65.tinypic.com/35c2wrl.png"/></div>
Customer memasukan jumlah orderan dan alamat orderan.

#### * Admin
<div style="text-align:center"><img src=http://i67.tinypic.com/nmhkcz.png"/></div>


#### 2.1.3 Antarmuka perangkat keras
Kebutuhan minimum perangkat keras yang dapat digunakan untuk mendukung aplikasi adalah :
- PC
- Mouse
- Keyboard
- Smartphone 

#### 2.1.4 Antarmuka perangkat lunak
Aplikasi dapat diakses jika terhubung dengan internet dan memiliki OS android

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
Untuk promosi aplikasi ini dilakukan melalui sosial media, agar pengguna dapat mengetahui informasi aplikasi tersebut.

#### 2.2 Fungsi-fungsi Produk
- Data Toko dan menu makanan
- Data Orderan
- Tracking

Fungsi produk aplikasi pemesanan aplikasi ini adalah menyediakan kemudahan dalam proses pemesanan dan pembuatan, dalam pembuatan aplikasi yang dinginkan oleh pengguna maupun pembuatan aplikasi tersebut. Serta dapat mensimulasi jangka waktu dalam pembuatan aplikasi tersebut.

#### 2.3 Karakteristik Pengguna
Untuk mengoperasikan aplikasi ini tidak diperlukan tingkat pendidikan tinggi, namun pengguna cukup memahami cara menggunakan smartphone dan penggunaan dalam sebuah aplikasi ini.

#### 2.4 Batasan-batasan.
Pengembangan Aplikasi pemesanan makanan berbasis mobile ini memiliki keterbatasan-keterbatasan yaitu sebagai berikut  :
-	Sistem Sistem Administrasi pemesanan makanan ini akan di buat menggunakan Android studio, MySql, PHP, dan html
-	Aplikasi bersifat android
- Pengembangan aplikasi Ayo Mangan ini akan meliputi pengelolaan data-data yang ada diadmin yang meliputi data toko, dan seller

#### 2.5 Asumsi dan ketergantungan/keterkaitan.
- Admin bisa melihat sistem secara keseluruhan dan dapat merubah data-data seller, Admin hanya mengatur data-data seller 
- Seller atau Owner bisa melihat sistem secara keseluruhan dan dapat merubah data-data tokonya sendiri
- Bagian costumer mempunyai wewenang untuk melakukan pemesanan makanan serta konfirmasi jika orderan telah sampai.

#### 2.6 kebutuhan-kebutuhan penyeimbang.

### BAB III : Kebutuhan Spesifik.

#### 3.1 External Interface Requirements

Kebutuhan akan pengelolaan/management pada suatu instansi sangatlah penting dengan menimbang beberapa aspek yang saling mendukung, pada hal ini tertuju pada pebisnis rumahan yang berdomisili di Indramayu dimana penerapan management/pengelolaan pemesanan nya sudah semestinya menggunakan komputerisasi untuk dapat memperkecil terjadinya human error pada pengerjaannya. Seller dan Customer yang bersangkutan sangatlah terbantu untuk meningkatkan efesiensi waktu dikarenakan fitur dari aplikasi ini menunjang kedua pihak antara seller dan customer untuk dapat berjual-beli jarak jauh tanpa harus face to face, dengan ini juga kedua pihak antara seller dan cutomer dapat memantau kurir yang memngantarkan orderan melalui fitur tracking di dalam aplikasi.

#### 3.2 Kebutuhan Non Fungsional
Dalam sistem informasi ini, kebutuhan yang mendukung kelancaran
fungsi-fungsi utama dapat didefinisikan pada Tabel 1.

|  Availability 			|  24 jam nonstop, kecuali ada maintenance / perbaikan sistem.   	|
|---------------------|-----------------------------------------------------------------|
|  Reliability 			  |  Kegagalan yang ditolerir sekitar 5%.			  	                  |
|  Ergonomy 			    |  Sistem informasi ini harus user friendly.			 	              |
|  Portability 			  |  Aplikasi ini berjalan pada platform atau sistem operasi apa    |
|  				            |  saja yang mendukung aplikasi berbasis android.		              |
|  Response 			    |  Time Tidak lebih dari 10 detik.				                        |
|  Safety				      |  Menggunakan secure socket layer dgn sertifikasi. 		          |
|  Security 				  |  Login (manajemen user) dan validasi data sangat penting  	    |
|                     |  karena menyangkut pembayaran secara online.		                |
|  Bahasa				      |  Menggunakan bahasa Indramayu, kecuali ada penambahan 	        |
|   Komunikasi			  |  Fasilitas untuk menggunakan bahasa lain selain bahasa Indonesia|


#### 3.3 Detail Persyaratan Tidak Berfungsi
<div style="text-align:center"><img src=http://i67.tinypic.com/11bj66a.jpg"/></div>
