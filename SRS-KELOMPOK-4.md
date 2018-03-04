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
Bab berikutnya, bagian Uraian Keseluruhan, dari dokumen ini memberikan sebuah
gambaran fungsionalitas produk. Ini menggambarkan persyaratan informal dan
digunakan untuk menetapkan konteks untuk spesifikasi persyaratan teknis di bab berikutnya.
Bab ketiga, Bagian Persyaratan Spesifikasi, dari dokumen ini ditulis
terutama untuk pengembang dan menjelaskan secara teknis rinciannya
fungsionalitas produk.
Kedua bagian dokumen tersebut menggambarkan produk perangkat lunak yang sama secara keseluruhan,
namun ditujukan untuk khalayak yang berbeda dan dengan demikian menggunakan bahasa yang berbeda.

### BAB II : Gambaran Umum

#### 2.1 Perspektif produk
Produk yang dirancang merupakan sebuah perangkat lunak berbasis android
dimana akan dapat digunakan secara online oleh pihak-pihak berkepentingan.

#### 2.1.1 Antarmuka sistem

#### 2.1.2 Antarmuka pengguna
Antarmuka pengguna menggunakan aplikasi berbasis android. Pengguna berinteraksi dengan perangkat lunak ayo mangan melalui antarmuka aplikasi pada smartphone android.

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
- Memori yang dibutuhkan untuk aplikasi minimal 512Mb

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

#### 3.1 Kebutuhan Fungsional
Kebutuhan fungsional sistem ini terdiri atas beberapa fungsi utama yang
saling berhubungan dan mendukung satu sama lain, yang meliputi fungsifungsi
sebagai berikut:
1. Input menu makanan dan harga dari user bisnis dan admin.
2. Pembelian makanan dari user individu / customer.
3. Perhitungan jumlah pembelian makanan dari user individu / customer.
4. Pendaftaran untuk user yang ingin menggunakan fasilitas sistem.
5. Akomodasi untuk user bisnis yang menjual barang dalam jumlah besar.

Untuk masing-masing fungsi diatas akan dijelaskan secara mendetil
sebagai berikut:
1. Input barang dari customer : sistem menerima input data makanan dan harga dari
user bisnis dan admin, lengkap dengan gambar dari tiap barang.
2. Pembelian barang dari user individu / customer : sistem mencatat
Menu makanan yang dipilih oleh user individu untuk dibeli, dan
mencatat segala detil pembelian, seperti jumlah menu makanan yang dibeli.
3. Perhitungan jumlah pembelian barang dari user individu / customer : 
melakukan perhitungan terhadap harga total dari semua menu makanan yang
dibeli.
4. Pendaftaran untuk user yang ingin menggunakan fasilitas sistem :
mencatat data lengkap dari user individu dan user bisnis untuk
keperluan administrasi serta pengiriman barang.
5. Akomodasi untuk user bisnis yang ingin menjual barang dalam jumlah
besar : menyediakan kurir untuk user bisnis yang mengirim makanan yang udah dipesan dengan jumlah banyak.

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



