### BAB I : Pendahuluan
#### 1.1 Tujuan
Tujuan dari penulisan dokumen Softaware Requirement Specification (SRS) untuk mempermudah mengembangkan perangkat lunak yang kami buat dan memberikan gambaran yang spesifik dari kebutuhan softaware. Spesifikasi kebutuhan tersebut termasuk dari segi perangkat lunak dan perangkat keras,untuk memberikan gambaran dan penjelasan mengenai pembuatan produk termasuk kebutuhan fungsional hingga non-fungsional, dan kebutuhan antar muka mulai dari antar muka pengguna hingga antar muka komunikasi.
#### 1.2 Lingkup
Ruang lingkup dalam membangun aplikasi yaitu Delivery online menggunakan smartphone. Aplikasi ini perlu dibuatkannya karena untuk mempermudah penjual dan pembeli dalam bertransaksi jarak jauh.
#### 1.3 Definisi, Akronim, Singkatan
|      Istilah         |               Definisi                                                                                        |
|----------------------|---------------------------------------------------------------------------------------------------------------|
|   Artikel aktif      | Dokumen yang dilacak oleh sistem; itu adalah sebuah cerita yang rencananya akan diposkan ke situs publik      |
|   Author             | Orang yang mengirimkan artikel untuk ditinjau. Dalam kasus beberapa penulis, istilah ini mengacu pada penulis |  |                      | utama, dengan siapa semua komunikasi dibuat.                                                                  |
|   Database           | Pengumpulan semua informasi yang dipantau oleh sistem ini.                                                    |
|   Editor             | Orang yang menerima artikel, mengirimkan artikel untuk ditinjau, dan membuat keputusan akhir untuk publikasi. |
|   Bidang             | Sel dalam bentuk.                                                                                             |
|   Historical Society | Database keanggotaan yang ada (juga database HS).                                                             |
|   Database           |                                                                                                               |
|   Anggota            | Seorang anggota Historical Society terdaftar di HS database                                                   |
|   Pembaca            | Siapa pun yang mengunjungi situs tersebut untuk membaca artikel.                                              |
|   Ulasan             | Rekomendasi tertulis tentang kesesuaian sebuah artikel untuk publikasi; mungkin termasuk saran untuk          |  |                      |                                                                                                               |
|   Reviewer           | Seseorang yang memeriksa sebuah artikel dan memiliki kemampuan untuk melakukannya merekomendasikan persetujuan|  |                      | artikel untuk publikasi atau mohon agar perubahan dilakukan di artikel.                                       |
| Persyaratan Perangkat| Sebuah dokumen yang benar-benar menggambarkan semua fungsi dari sistem yang diusulkan dan kendala di mana itu |
| Lunak Spesifikasi    | harus beroperasi Misalnya, dokumen ini.                                                                       |

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
### 2.1.6 Batasan-batasan Memori
- RAM yang kami gunakan adalah 4Gb, tapi untuk kapassitas minimum 2 Gb
- Memori yang dibutuhkan untuk aplikasi minimal ------
### 2.1.7 Operasi-operasi
operasi-operasi yang ada pada aplikasi (simpan, buka, dll)
- Order
- Simpan
- Tampilan atau Buka
### 2.1.8 Kebutuhan-kebutuhan dalam tahapan Adaptasi
- Pemakaian data bisa sebagai sarana penyimpanan data.
- PL menggunakan bahasa Indonesia agar mudah dipahami oleh user.
### 2.2 Fungsi-fungsi Produk
Fungsi produk aplikasi pemesanan aplikasi ini adalah menyediakan kemudahan dalam proses pembelian dan penghitungan pembuatan dalam pembuatan aplikasi yang dinginkan oleh pengguna maupun pembuatan aplikasi tersebut. Serta dapat mensimulasi jangka waktu dalam pembuatan aplikasi tersebut.
### 2.3 Karakteristik Pengguna
Untuk mengoperasikan sistem ini tidak diperlukan tingkat pendidikan tinggi, namun pengguna cukup memahami cara pembuatan dan penggunaan dalam sebuah aplikasi ini.
#### 2.4 Batasan batasan.
Pengembangan Aplikasi pemesatan tiket berbasis web ini memiliki keterbatasan-keterbatasan yaitu sebagai berikut  :
-	Sistem Sistem Administrasi pemesanan makanan ini akan di buat databasenya menggunakan MySql dan bahasa pemrograman PHP, html dan java script. 
-	 Aplikasi bersifat android

#### 2.5 Asumsi dan ketergantungan/keterkaitan.
Asumsi-asumsi pada pemesanan makanan ini adalah:
a.   Setiap entitas mempunyai hak akses.
b.  Admin bisa melihat sistem secara keseluruhan dan tidak dapat merubah data-data. Admin hanya hanya mengatur data-data user.
c.   Pemilik atau Owner bisa melihat sistem secara keseluruhan dan dapat merubah data-data di dalamnya.
d.  Bagian costumer mempunyai wewenang untuk melakukan pemesanan makanan

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
-------------------------------------------|--------------------------------------------------------------------------------------|
|  Reliability 			  |  Kegagalan yang ditolerir sekitar 5%.			  	|
|  Ergonomy 			|  Sistem informasi ini harus user friendly.			 	 |
|  Portability 			|  Aplikasi ini berjalan pada platform atau sistem operasi apa     	 |
|  				|  saja yang mendukung aplikasi berbasis android.		  |
| Response 			|  Time Tidak lebih dari 10 detik.				  |
|  Safety				|  Menggunakan secure socket layer dgn sertifikasi. 		  |
Security 				Login (manajemen user) dan validasi data sangat penting  	  |
karena menyangkut pembayaran secara online.		  |
Bahasa				Menggunakan bahasa Indramayu, kecuali ada penambahan 	  |
Komunikasi			Fasilitas untuk menggunakan bahasa lain selain bahasa Indramayu.



