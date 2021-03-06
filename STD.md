<html>
<body>
<body><div align="center"><h1>Software Testing Document</h1></div>
<p align="center"><b>Version 1.0 </b><br>
<p align="center">15 Mei 2018<br><br>
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

### 1.1 Tujuan Pembuatan Dokumen
Dokumen ini digunakan sebagai panduan untuk melakukan pengujian terhadap perangkat lunak Sistem APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID , untuk melihat kemampuan dari program yang telah dirancang agar sesuai dengan keinginan dari pengguna. Pembuatan dokumen ini ditujukan untuk menguji perangkat lunak  yang merupakan bagian dari tugas mata kuliah Rekayasa Perangkat Lunak.
### 1.2 Deskripsi Umum Sistem
Perangkat lunak yang akan diuji adalah “APLIKASI PEMESANAN MAKANAN BERBASIS ANDROID”. Perangkat lunak ini adalah aplikasi pemesanan makanan berbasis android .
### 1.3 Deskripsi Dokumen (Ikhtisar)
### 1.4 Definisi dan Singkatan
-  SKPL adalah Spesifikasi Kebutuhan Perangkat Lunak, atau dalam bahasa Inggris-nya sering juga disebut sebagai Software Requirements Spesification (SRS), dan merupakan spesifikasi dari perangkat lunak yang akan dikembangkan

-  DFD adalah Data Flow Diagram, diagram dan notasi yang digunakan untuk menunjukkan aliran data pada perangkat lunak.

- ERD adalah Entity Relationship Diagram, diagram dan notasi yang digunakan untuk merepresentasikan struktur data statis pada perangkat lunak.

- DPPL-SPP.K-yyyy kode yang merepresentasikan kasus uji perangkat lunak pada Pencarian Pegawai dengan SPP adalah kode produk, DPPL adalah kode fase dan yyyy merupakan nomor kasus uji relative tehadap nomor SKPL.

### 1.5 Dokumen Referensi
IEEE. IEEE Std 830-1998 Praktik yang Direkomendasikan IEEE untuk Persyaratan Perangkat Lunak
Spesifikasi. IEEE Computer Society, 1998.

### BAB II : Lingkungan Pengujian Perangkat Lunak

### 2.1 Perangkat Lunak Pengujian
Perangkat lunak ini (SPP) diujikan dengan beberapa perangkat lunak lain, yaitu:<br>
-  Sistem operasi: Windows 7<br>
-  Bahasa pemrograman: PHP<br>
-  Database: XAMPP<br>

### 2.2 Perangkat Keras Pengujian
Perangkat keras yang diperlukan untuk menguji aplikasi SPP ini adalah satu set komputer dengan spesifikasi:<br>
-  Processor: intel i5 <br>
-  Memory: 8 GB DDR4<br>
-  Harddisk 500 GB<br>
### 2.3 Sumber Daya Manusia
Persyaratan sumber daya manusia yang akan terlibat dalam proses pengujian perangkat lunak ini adalah :<br>
- Memahami konsep pemrograman berorientasi objek dalam bahasa PHP.<br>
- Memahami proses pengujian perangkat lunak berorientasi objek.<br>
- Memahami konsep pemrograman database XAMPP.<br>
### 2.4 Prosedur Umum Pengujian
### 2.4.1 Pengenalan dan Latihan
Penguji aplikasi ini hanya diberikan latihan kembali tentang SQL, dan pengenalan lebih lanjut tentang Java dan android studio. Pada dasarnya penguji telah memiliki pengetahuan tentang hal yang disebutkan sebelumnya tetapi latihan yang diberikan hanya bersifat penyegaran kembali.
### 2.4.2 Persiapan Awal
### 2.4.2.1 Persiapan Prosedural
Pengujian ini dilakukan di luar lingkungan kampus. Dimana pengujian ini dilakukan oleh tim penguji yang telah di tentukan oleh Dosen mata kuliah Rekayasa Perangkat Lunak (RPL). Alat yang digunakan 1 buah laptop dengan software yang telah di instalasi.
### 2.4.2.2 Persiapan Perangkat Keras
Perangkat keras yang perlu dipesiapkan adalah :<br>
Sebuah perangkat komputer yang dilengkapi dengan :<br>
-  Processor: intel i5 <br>
-  Memory: 8 GB DDR4<br>
-  Harddisk 500 GB<br>
### 2.4.2.3 Persiapan Perangkat Lunak
Persiapan yang harus dilakukan untuk menyiapkan perangkat lunak untuk diuji di lingkungan sistem operasi Microsoft Windows 10 adalah sebagai berikut :<br>
1. Persiapkan sistem operasi Microsoft Windows.<br>
2. Perangkat lunak yang akan di uji di copy ke sebuah direktori, misalnya C:\XAMPP\htdocs.<br>
3. Browser Google Chrome.<br>
4. Database di import ke phpMyAdmin di database ayomangan.<br>
5. Adobe Dreamweaver untuk melihat source code.<br>
6. Android Studio untuk menjalankan PL
### 2.4.3 Pelaksanaan
Pelaksanaan pengujian dilakukan dengan mengeksekusi perangkat lunak SPP dengan mengikuti skenario tertentu yang dibuat berdasarkan skenario yang tedapat pada dokumen SKPL-SPP.
### 2.4.4 Pelaporan Hasil
Dokumen hasil uji dari aplikasi ini akan diberikan kepada asisten praktikum dan dievaluasi oleh asisten dan kelompok lain yang bertindak sebagai klien dari kelompok kami. Sehingga aplikasi mendapatkan umpan balik dalam pengembangan perangkat lunak ini selanjutnya.


### BAB III : Identifikasi dan Rencana Pengujian

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Login Customer</td>
	<td>Data user-id dan password benar</td>
	<td>SRS 2.2.1.1/SDD 3.2.1</td>
	<td>STD-01</td>
	<td>sistem</td>
	<td>black box</td>
	<td>irin</td>
<tr>
	<td>Data user-id dan password salah</td>
	<td>SRS 2.2.1.1/SDD 3.2.1</td>
	<td>STD-02</td>
	<td>sistem</td>
	<td>black box</td>
	<td>irin</td>
<tr>
	<td>Login customer tanpa terhubung ke internet</td>
	<td>SRS 2.2.1.1/SDD 3.2.1</td>
	<td>STD-03</td>
	<td>sistem</td>
	<td>black box</td>
	<td>yoshie</td>
</tr>

</thead>  
</table>
<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Tambah makanan pada Seller</td>
	<td>Data makanan yang diinputkan sesuai dengan yang diminta oleh sistem</td>
	<td>SRS 2.2.2.2/SDD 3.2.6</td>
	<td>STD-04</td>
	<td>sistem</td>
	<td>black box</td>
	<td>yoshie</td>
<tr>
	<td>Data makanan yang diinputkan tidak sesuai dengan yang diminta oleh sistem</td>
	<td>SRS 2.2.2.2/SDD 3.2.6</td>
	<td>STD-05</td>
	<td>sistem</td>
	<td>black box</td>
	<td>yoshie</td>
<tr>
	<td>Tidak mengisi form data makanan</td>
	<td>SRS 2.2.2.2/SDD 3.2.6</td>
	<td>STD-06</td>
	<td>sistem</td>
	<td>black box</td>
	<td>yoshie</td>
</tr>

</thead>  
</table>

<table>  
	<thead>  
<tr>
	<td rowspan="2" align="center"><strong>Kelas Uji</td>
	<td rowspan="2" align="center"><strong>Butir Uji </td>
	<td colspan="2" align="center"><strong>Identifikasi</td>
	<td rowspan="2" align="center"><strong>Jenis Pengujian</td>
	<td rowspan="2" align="center"><strong>Teknik Pengujian</td>
	<td rowspan="2" align="center"><strong>Penguji</td>
</tr>
		<tr>
			<td align="center"><strong>SRS/SDD</td>
			<td align="center"><strong>STD</td>
		</tr>
<tr>
	<td rowspan="3" align="center"><strong>Tambah Kurir pada seller</td>
	<td>Menginput data biodata kurir yang benar</td>
	<td>SRS 2.2.2.3/SDD 3.2.7</td>
	<td>STD-07</td>
	<td>sistem</td>
	<td>black box</td>
	<td>Yoshie Pangestu</td>
<tr>
	<td>Menginput data kurir dengan salah satu field tidak diisi</td>
	<td>SRS 2.2.2.3/SDD 3.2.7</td>
	<td>STD-08</td>
	<td>sistem</td>
	<td>black box</td>
	<td>Yoshie Pangestu</td>
</tr>
<tr>
	<td>Menginput data kurir tanpa koneksi internet</td>
	<td>SRS 2.2.2.3/SDD 3.2.7</td>
	<td>STD-09</td>
	<td>sistem</td>
	<td>black box</td>
	<td>Yoshie Pangestu</td>
</tr>

</thead>  
</table>


### BAB IV : Deskripsi dan Hasil Uji

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-01</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Customer dengan data user-id dan password benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengecek apakah user dapat login pada aplikasi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Data user sudah terdaftar di database<br>
							- Data user sudah ditentukan level nya</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">15 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Irin Windiyati</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Ketikkan email dan password</li>
					<li>2.Tekan button login</li>
				</ul>
</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>email : irin@gmail.com</li>
					<li>password : polindra</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>customer berhasil masuk ke aplikasi dengan akun yang benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>button login dapat di-klik jika field email dan password sudah terisi</li>
					<li>jika field belum di isi kemudian menekan button login maka sistem akan menampilkan peringatan "kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>


<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-02</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Customer dengan data user-id dan password yang tidak sesuai</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengecek apakah user dapat login pada aplikasi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Data user sudah terdaftar di database<br>
							- Data user sudah ditentukan level nya</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">15 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Ketikkan email dan password yang tidak sesuai dengan database</li>
					<li>2.Tekan button login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>email : irin@yahoo.com</li>
					<li>password : polindra123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>customer tidak dapat masuk ke aplikasi dengan akun yang salah</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>button login dapat di-klik jika field email dan password sudah terisi</li>
					<li>jika field belum di isi kemudian menekan button login maka sistem akan menampilkan peringatan "kolom tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-03</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Login Customer tanpa terhubung ke internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengecek apakah user dapat login pada aplikasi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Data user sudah terdaftar di database<br>
					- Internet mati </td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">15 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan email dan password</li>
					<li>2.Tekan button login</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>email : irin@yahoo.com</li>
					<li>password : polindra123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>customer tidak dapat masuk ke aplikasi tanpa internet</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>button login dapat di-klik jika field email dan password sudah terisi</li>
					<li>jika button login di-klik maka akan muncul peringatan "koneksi error"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-04</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Data makanan yang diinputkan sesuai dengan yang diminta oleh sistem</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengetahui apakah data makanan tersimpan ke database</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan data makanan yang diminta oleh sistem dengan benar</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama makanan : Bakso</li>
					<li>harga : 5000</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data makanan yang diinputkan dapat tersimpan di database</li>
					<li>jika button simpan di-klik akan muncul peringatan "berhasil tersimpan"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>dapat disimpan ke database jika data yang diinputkan benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-05</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Data makanan yang diinputkan tidak sesuai dengan yang diminta oleh sistem</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengetahui apakah data makanan tersimpan ke database jika tidak sesuai dengan yang diminta oleh sistem</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan salah satu data makanan yang tidak sesuai dengan yang diminta oleh sistem</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama makanan : Bakso</li>
					<li>harga : seribu</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data makanan yang diinputkan tidak dapat tersimpan di database</li>
					<li>jika button simpan di-klik akan muncul peringatan "data tidak sesuai"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>dapat disimpan ke database jika data yang diinputkan benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>data harga yang diinputkan tidak sesuai, karena data harga harus berupa bilangan</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-06</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Tidak mengisi form data makanan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengetahui apakah data makanan tersimpan ke database jika tidak mengisi form data makanan</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Kosongkan semua data form makanan</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama makanan : -</li>
					<li>harga : -</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data makanan yang diinputkan tidak dapat tersimpan di database</li>
					<li>jika button simpan di-klik akan muncul peringatan "data tidak boleh kosong"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>dapat disimpan ke database jika data yang diinputkan benar</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>
<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-07</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menginput data biodata kurir yang benar</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk menambahkan user kurir ke database</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan biodata kurir dengan benar</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama : dina micela</li>
					<li>no hp : 089777222111</li>
					<li>email : dina200@gmail.com</li>
					<li>password : polindra123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data kurir yang diinputkan tersimpan di database</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>tidak dapat disimpan jika ada form biodata kurir yang tidak terisi</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-08</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menginput data kurir dengan salah satu field tidak diisi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengetahui apakah data kurir akan tersimpan jika salah satu field tidak diisi</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan biodata kurir dengan mengosongkan salah satu form biodata yang diminta</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama : dina micela</li>
					<li>no hp : 089777222111</li>
					<li>email : dina200@gmail.com</li>
					<li>password : -</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data kurir yang diinputkan tidak dapat tersimpan di database</li>
					<li>jika button simpan di-klik akan muncul peringatan "form tidak lengkap"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>tidak dapat disimpan jika ada form biodata kurir yang tidak terisi</li>
					<li>jika button simpan di-klik akan muncul peringatan "form tidak lengkap"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>

<table>  
	<thead> 
		<tr>
			<td rowspan="1"><strong>Identifikasi</td>
			<td colspan="3">STD-09</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Nama Butir Uji</td>
			<td colspan="3">Menginput data kurir tanpa koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tujuan</td>
			<td colspan="3">untuk mengetahui apakah data kurir akan tersimpan jika tanpa koneksi internet</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Kondisi Awal</td>
			<td colspan="3">- Sudah login sebagai seller</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Tanggal Pengujian</td>
			<td colspan="3">20 mei 2018</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Penguji</td>
			<td colspan="3">Yoshie Pangestu</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Skenario</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>1.Inputkan biodata kurir yang diminta oleh sistem</li>
					<li>2.Tekan button simpan</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Hasil</td>
		</tr>
		<tr>
			<td rowspan="1"><strong>Data yang Diberikan</td>
			<td rowspan="1"><strong>Yang Diharapkan</td>
			<td rowspan="1"><strong>Pengamatan</td>
			<td rowspan="1"><strong>Kesimpulan</td>
		</tr>
		<tr>
			<td rowspan="1">
				<ul>
					<li>nama : dina micela</li>
					<li>no hp : 089777222111</li>
					<li>email : dina200@gmail.com</li>
					<li>password : polindra123</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>data kurir yang diinputkan tidak dapat tersimpan di database</li>
					<li>jika button simpan di-klik akan muncul peringatan "koneksi error"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>tidak dapat disimpan jika tanpa koneksi internet</li>
					<li>jika button simpan di-klik akan muncul peringatan "koneksi error"</li>
				</ul>
			</td>
			<td rowspan="1">
				<ul>
					<li>Ok</li>
				</ul>
			</td>
		</tr>
		<tr>
			<td colspan="4" align="center"><strong>Catatan</td>
		</tr>
		<tr>
			<td colspan="4">
				<ul>
					<li>Tidak ada</li>
				</ul>
			</td>
		</tr>
	</thead>
</table>


