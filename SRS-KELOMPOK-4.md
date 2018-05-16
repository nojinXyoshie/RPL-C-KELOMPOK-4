<html>
<body>
<body><div align="center"><h1>Software Requirement Spesification</h1></div>
<p align="center"><b>Version 1.1 </b><br>
<p align="center">22 Maret 2018<br><br>
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
<img src="http://i63.tinypic.com/28akml0.jpg"/>
</p>


#### 2.1.2 Antarmuka pengguna
#### * Customer<br>
<table>
<tr>
	<td><p align="center">Mock up</td>
	<td><p align="center">Nama mock up</td>
	<td><p align="center">Keterangan</td>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/2eulyjb.png"></p></td>
	<td><p align="center">Splash</td>
	<td><p align="center">saat costomer membuka aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i67.tinypic.com/2rfsx3o.png"></td>
	<td><p align="center">Daftar</td>
	<td><p align="center">saat customer daftar (membuat akun baru)</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/rkoshz.png"></td>
	<td><p align="center">Masuk</td>
	<td><p align="center">saat customer masuk aplikasi (menggunakan email dan kata sandi)</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/24y7hgp.png"></td>
	<td><p align="center">Home</td>
	<td><p align="center">saat customer berhasil masuk aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/qs12z8.png"></td>
	<td><p align="center">Navigation drawer</td>
	<td><p align="center">navigation drawer dari aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i67.tinypic.com/r0poh3.png"></td>
	<td><p align="center">Masuk kategori</td>
	<td><p align="center">saat customer telah memilih kategori makanan </td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/350m4nc.png"></td>
	<td><p align="center">detail produk </td>
	<td><p align="center">saat customer memilih makanan yang diinginkan</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2hgspy8.png"></td>
	<td><p align="center">Detail pesan makanan</td>
	<td><p align="center">saat customer menekan button beli sekarang pada halaman detail produk</td>
<tr>
	<td><p align="center"><img src="http://i67.tinypic.com/2hgbfw7.png"></td>
	<td><p align="center">alert pemesanan</td>
	<td><p align="center">alert pemesanan ini digunakan untuk meyakinkan customer apakah benar ingin membeli makanan tersebut</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/14ufhag.png"></td>
	<td><p align="center">pesanan</td>
	<td><p align="center">saat customer telah pesan makanan , maka customer diarahkan ke halaman ini</td>
</tr>
</tr>
	<td><p align="center"><img src="http://i65.tinypic.com/2n705zb.jpg"></td>
	<td><p align="center">Mulai tracking</td>
	<td><p align="center">saat customer memilih makanan yang di beli pada halaman pesanan , pada halaman ini terdapat fitur tracking dan telepon</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2i26dq9.png"></p></td>
	<td><p align="center">Tracking</td>
	<td><p align="center">saat customer sebelumnya menekan button mulai tracking</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/2drawjt.png"></td>
	<td><p align="center">notifikasi</td>
	<td><p align="center">saat customer membuka pesanan sampai (sebelumnya customer telah menekan button konfirmasi pesanan sampai</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i63.tinypic.com/14lmqsx.png"></td>
	<td><p align="center">Review</td>
	<td><p align="center">saat customer diminta untuk memberikan ulasan kepada seller</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i68.tinypic.com/5xvel1.png"></td>
	<td><p align="center">Review seller</td>
	<td><p align="center">saat customer mendapat ulasan dari seller , berupa list dari beberapa seller</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2vx0ksl.png"></td>
	<td><p align="center">Detail review seller</td>
	<td><p align="center">Detail dari review seller</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i68.tinypic.com/15qr9xj.png"></td>
	<td><p align="center">Riwayat pesanan</td>
	<td><p align="center">Riwayat pesanan customer</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2q2gupu.jpg"></td>
	<td><p align="center">Profil</td>
	<td><p align="center">digunakan untuk pengaturan profil</td>
</tr>
	<td><p align="center"><img src="http://i68.tinypic.com/fm7ts2.png"></td>
	<td><p align="center">Ubah kata sandi</td>
	<td><p align="center">digunakan untuk mengubah kata sandi</td>
<tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/2vdlhti.png"></td>
	<td><p align="center">Bantuan</td>
	<td><p align="center">Berisi panduan dan aturan dari aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i63.tinypic.com/6ezsba.png"></td>
	<td><p align="center">Keluar aplikasi</td>
	<td><p align="center">Ketika keluar aplikasi</td>
</tr>
</table>

#### * Seller<br>
<table>
<tr>
	<td><p align="center">Mock up</td>
	<td><p align="center">Nama mock up</td>
	<td><p align="center">Keterangan</td>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/2eulyjb.png"></p></td>
	<td><p align="center">Splash</td>
	<td><p align="center">saat costomer membuka aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i67.tinypic.com/2rfsx3o.png"></td>
	<td><p align="center">Daftar</td>
	<td><p align="center">saat customer daftar (membuat akun baru)</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/rkoshz.png"></td>
	<td><p align="center">Masuk</td>
	<td><p align="center">saat customer masuk aplikasi (menggunakan email dan kata sandi)</td>
</tr>
</table>


#### * Kurir<br>
<table>
<tr>
	<td><p align="center">Mock up</td>
	<td><p align="center">Nama mock up</td>
	<td><p align="center">Keterangan</td>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/2eulyjb.png"></p></td>
	<td><p align="center">Splash</td>
	<td><p align="center">saat costomer membuka aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/rkoshz.png"></td>
	<td><p align="center">Masuk</td>
	<td><p align="center">saat customer masuk aplikasi (menggunakan email dan kata sandi)</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2jb2vie.png"></td>
	<td><p align="center">Notifikasi</td>
	<td><p align="center">Kurir akan mendapatkan notifikasi setelah seller meneruskan orderan ke kurir</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i63.tinypic.com/8wmnq0.png"></td>
	<td><p align="center">Detail Order</td>
	<td><p align="center">kurir melihat detail order dan klik mulai untuk mengantar pesanan/tracking</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/11aj3p0.png"></td>
	<td><p align="center">Tracking</td>
	<td><p align="center">kurir melakukan tracking</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/2w5u6ug.png"></td>
	<td><p align="center">Konfirmasi</td>
	<td><p align="center">kurir mengkonfirmasi orderan sampai setelah barang sudah diterima oleh customer</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/34rvo6c.png"></td>
	<td><p align="center">List Orderan Sampai</td>
	<td><p align="center">Setelah mengkonfirmasi kurir akan melihat list orderan sampai</td>
</tr>



</table>

#### * Seller<br>
<table>
<tr>
	<td><p align="center">Mock up</td>
	<td><p align="center">Nama mock up</td>
	<td><p align="center">Keterangan</td>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/2eulyjb.png"></p></td>
	<td><p align="center">Splash</td>
	<td><p align="center">saat costomer membuka aplikasi</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/rkoshz.png"></td>
	<td><p align="center">Masuk</td>
	<td><p align="center">saat customer masuk aplikasi (menggunakan email dan kata sandi)</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/jjbd6q.png"></td>
	<td><p align="center">Profil Toko</td>
	<td><p align="center">Profile toko seller</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i63.tinypic.com/2ijgn6u.png"></td>
	<td><p align="center">Toko</td>
	<td><p align="center">Menu</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i66.tinypic.com/28me3wl.png"></td>
	<td><p align="center">List Orderan Sampai</td>
	<td><p align="center">Setelah kurir mengkonfirmasi orderan sampai, maka seller dapat melihat list orderan yg sudah sampai</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/6ga2q9.png"></td>
	<td><p align="center">Tambah Produk Baru</td>
	<td><p align="center">Seller dapat menambahkan produk/makanan baru</td>
</tr>
</table>

#### * Admin<br>
<table>
<tr>
	<td><p align="center">Mock up</td>
	<td><p align="center">Nama mock up</td>
	<td><p align="center">Keterangan</td>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/21mfbqa.jpg"></p></td>
	<td><p align="center">Login Admin</td>
	<td><p align="center">Admin harus login terlebih dahulu sebelum masuk ke sistem</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i65.tinypic.com/n6qowi.jpg"></p></td>
	<td><p align="center">Dashboard Admin</td>
	<td><p align="center">Tampilan awal admin, dimana adshboard terdapat jumlah customer, jumlah seller dan kurir</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i68.tinypic.com/2lm8hkx.png"></p></td>
	<td><p align="center">Data Seller</td>
	<td><p align="center">Admin dapat melihat data seller, admin juga dapat melihat detal toko dan dapat menghapus toko</td>
</tr>
<tr>
	<td><p align="center"><img src="http://i64.tinypic.com/2mhsbd3.png"></p></td>
	<td><p align="center">Data Makanan</td>
	<td><p align="center">Admin dapat melihat data makanan, admin juga dapat melihat detal makanan dan dapat menghapus makanan</td>
</tr>
</table>
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
<p align="center"><img src="http://i64.tinypic.com/33as6kx.jpg"/></p>

Deskripsi :
Customer akan login terlebih dahulu kemudian memilih makanan yang akan diorder, setelah menginput data yang diperlukan maka customer dapat mengorder. setelah itu customer dapat tracking kurir untuk memastikan posisi orderan dan setelah barang sampai maka customer akan melakukan konfirmasi melalui aplikasi bahwa orderan telah sampai.

2.2.1.1 Login Customer
<p align="center"><img src="http://i67.tinypic.com/1zf3l1f.jpg"/></p>

Untuk dapat menggunakan aplikasi customer harus mengisi form login terlebih dahulu dengan cara: <br>
1. Member mengaktifkan fungsi login <br>
2. Sistem menampilkan halaman login yang terdiri dari email dan password <br>
3. Member mengisi email dan password <br>
4. Sistem melakukan validasi dari email dan password <br>
5. Jika login gagal maka member akan diminta mengulangi proses login <br>
6. Jika login berhasil maka customer akan diarahkan ke halaman utama yang menampilkan kategori makanan <br>

Untuk member yang belum mempunyai akun diharuskan melakukan sign up terlebih dahulu dengan cara: <br>
1. Member mangaktifkan fungsi sign up <br>
2. Sistem menampilkan halaman register <br>
3. Member mengisi form register sesuai dengan yang ditampilkan sistem <br>
4. Sistem menyimpan data yang dimasukkan customer <br>

2.2.1.2 Pesan makanan
<p align="center"><img src="http://i63.tinypic.com/351brzc.jpg"/></p>


2.2.2 Seller
<p align="center">
 <img src="http://i63.tinypic.com/jayidk.jpg/>
</p>

Deskripsi :
Seller akan login terlebih dahulu lalu memilih kelola toko jika seller ingin mengubah detile tokonya, setelah mengubah detile tokonya seller juga dapat mengelola kurir. Seller akan menerima pesanan/orderan dari customer setelah itu pesanan akan dteruskan ke kurir agar kurir dapat melihan pesanan yg akan diantar
Jika ada pesanan yg tidak sesuai dengan yg dipesan Seller dapat melihat review dari customer, seller dapat melihat tracking kurir untuk memastikan posisi orderan.<br>



2.2.3 Kurir
<p align="center"><img src="http://i64.tinypic.com/ifz76v.jpg"/></p>

Deskripsi :
Kurir akan login terlebih dahulu, lalu kurir menerima terusan pesanan/orderan dari seller setelah itu kurir bisa langsung tracking alamat customer dan kurir dapat menelfon customer jika ada trouble/masalah. Setelah barang sampai maka kurir akan melakukan konfirmasi melalui aplikasi bahwa orderan telah sampai.

2.2.4 Admin
<p align="center"><img src="http://i65.tinypic.com/2dkn1n4.jpg"/></p>

Deskripsi :
Admin akan login terlebih dahulu, lalu admin dapat mengelola data seller, kurir dan customer stelah selesai mengelola data admin akan logout.


#### 2.3. Spesifikasi kebutuhan non-fungsional
1. Usability <br>
Usability adalah kebutuhan non fungsional terkait dengan kemudahan penggunaan sistem atau perangkat lunak oleh user.

2. Portability <br>
Portability ialah kemudahan dalam pengaksesan sistem khususnya terkait dengan faktor waktu dan lokasi pengaksesan, serta perangkat atau teknologi yang digunakan untuk mengakses. Perangkat atau teknologi tersebut meliputi perangkat lunak, perangkat keras, dan perangkat jaringan.

3. Reliability <br>
Reliability merupakan kebutuhan terkait kehandalan sistem atau perangkat lunak termasuk juga faktor keamanan (security) sistem.

4. Supportability <br>
Supportability ialah kebutuhan terkait dengan dukungan dalam penggunaan sistem atau perangkat lunak.

5. Security <br>
Security ialah kebutuhan keamanan perangkat lunak pada sistem.

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

#### 3.1 Kebutuhan Antarmuka Eksternal

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

| Nama Fungsi    | Pesan Makanan                                                              |
|----------------|----------------------------------------------------------------------------|
| Referensi      | Bagian 2.1 Oder Makanan                                                    |
| Trigger        | Membuka Aplikasi Ayo Mangan!, dan sudah terdaftar                          |
| Precondition   | Menampilkan data menu makanan dan list orderan                             |
| Basic Path     |1. Customer Login ke dalam Aplikasi                                           |
|                |2.Customer Melihat Menu Makanan dan dan order makanan                        |
|                |3. Aplikasi dapat menampilkan Menu makanan dan List orderan                   |
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
<div style="text-align:center"><img src=http://i65.tinypic.com/x992u.jpg"/></div><br>
  
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
| Status       | Boolean  | Untuk menandakan bahwa customer aktif / non aktif                           |

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
| Status	      | Boolean| Untuk menandakan bahwa seller aktif / non aktif                                          |

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
| Id_kurir     | Varchar  | Sebagai identitas unik untuk membedakan antara kurir-kurir yg lainnya        |
| id_seller    | Varchar  | Nama toko yang bekerja sama                                                 |
| Nama kurir   | Varchar  | untuk  identitas kurir                                                      |
| No_hp        | integer  | Nomor hp kurir                                                              |
| Status       | Varchar  | Untuk menandakan bahwa kurir aktif / non aktif                                     |
|              |          |                                                                             |


