**ANALISIS DAN PERANCANGAN**

1.
  1. 1. **Analisis**

Tahap analisis merupakan tahap pemahaman terhadap aplikasi yang akan dibuat. Pada tahap ini berisi hal-hal yang berhubungan dengan analisa requirement fungsional, requirement non-fungsional, kebutuhan pengguna sistem, kebutuhan perangkat keras dan lunak, dengan maksud untuk mengidentifikasikan segala permasalahan atau hambatan-hambatan yang terjadi. Analisis juga bertujuan untuk mengetahui mekanisme sistem, proses-proses yang terlibat dalam sistem serta hubungan antara proses-proses tersebut.

Analisa adalah tahap yang sangat penting karena suatu kesalahan dalam tahap ini akan mempengaruhi pada tahap berikutnya. Penelitian juga membuktikan bahwa kesalahan yang diperbaiki setelah tahap analisa akan memakan biaya yang lebih besar dari pada jika di perbaiki saat dilakukan analisa.

1. 1.1 **Analisis sistem yang sedang berjalan**

Analisis sistem ini digunakan untuk mengetahui bagaimana sistem pelayanan pasien yang digunakan sekarang di KLINIK TANIMULYA MEDIKA, adapun alur dari sistem pada ini adalah sebagai berikut :

1.
  1.
    1.
      1. 1.1.1 **Analisis Flow Map yang sedang berjalan**

1. a)Flowmap yang sedang berjalan pada proses Informasi dan login

**Gambar 3.1**** Proses **** Login **** di Klinik Tanimulya Medika yang **** sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses pencarian informasi terdapat beberapa tahap yaitu :

1. User menginputkan alamat url yang akan diakses, muncul tampilan utama web apakah anda admin, maka masuk ke menu login dan dapat mengakses informasi dan merubahnya.
2. Apabila admin maka aka nada proses login dimana admin harus memasukan username dan password, ketika masuk maka tampil menu pengelolaan data klinik tidak maka harus masuk kembali.

1. b)Flowmap yang sedang berjalan pada proses pendaftaran

**Gambar 3.**** 2 ****Proses pendaftaran oleh pasien di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses pendaftaran oleh pasien terdapat beberapa tahap :

1. **1.** Pasien mengakses informasi dari web.
2. **2.** Pasien memasuki laman web.
3. **3.** Jika pasien akan melakukan pendaftaran jika belum mendaftar dengan cara: pasien masuk laman pendaftaran, pasien mengisi identitas diri kemudian mencetak kartu pasien dengan mengklik print.
4. **4.** Apabila pasien ingin berobat maka pasien masuk ke laman daftar periksa untuk mendapatkan nomor antrian.

1. c)Flowmap proses pendaftaran oleh petugas yang sedang berjalan



**Gambar 3.**** 3 ****Proses**  **Pendaftaran oleh Petugas di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses pendaftaran oleh pasien terdapat beberapa tahap :

1. Petugas membuka laman web
2. Petugas melakukan login ke aplikasi web
3. Mendaftarkan pasien yang akan mendaftar tanpa web
4. Mencetak kartu pasien dan memberikan nomor antrian jika ada proses antri kepada pasien.

owmap yang sedang berjalan pada proses Daftar Periksa oleh Pasien

**Gambar 3.4 Proses Daftar Periksa oleh Pasien di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses daftar periksa terdapat beberapa tahap:

1. Pada proses ini pasien harus mengakses laman web utama untuk dapat memakai aplikasi.
2. Pasien dapat memilih menu &quot;Daftar Periksa&quot; pada web untuk memulai proses pendaftaraan pemeriksaan agar mendapat nomor antrian.
3. Pasien akan diberikan tampilan berupa form dari aplikasi untuk diisi sesuai aturan.
4. Pasien menginputkan kode pasien
5. Pasien memilih tombol untuk menyimpan data agar masuk kedalam database sistem.
6. Aplikasi menerima masukan berupa data baru dan disimpan kedalam database tabel daftar periksa.
7. Pasien melihat print preview daftar periksa
8. Pasien mencetak kartu nomor antrian dengan driver printer yang telah terhubung dengan PC yang digunakan.
9. Pasien datang ke klinik
10. Pasien menunggu giliran sesuai nomor antrian yang didapatkan.lowmap yang sedang berjalan pada proses Daftar Periksa oleh Petugas

**Gambar 3.5 Proses Daftar periksa oleh Petugas di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses daftar periksa terdapat beberapa tahap:

1. Pada proses ini petugas harus mengakses laman web utama untuk dapat memakai aplikasi.
2. Petugas dapat memilih menu &quot;Daftar Periksa&quot; pada web untuk memulai proses pendaftaraan pemeriksaan agar mendapat nomor antrian.
3. Petugas akan diberikan tampilan berupa form dari aplikasi untuk diisi sesuai aturan.
4. Petugas menginputkan kode pasien
5. Petugas memilih tombol untuk menyimpan data agar masuk kedalam database sistem.
6. Aplikasi menerima masukan berupa data baru dan disimpan kedalam database tabel daftar periksa.
7. Pasien melihat print preview daftar periksa.
8. Pasien mencetak kartu nomor antrian dengan driver printer yang telah terhubung dengan PC yang digunakan.
9. Petugas memberikan nomor antrian.
10. Pasien menunggu giliran sesuai nomor antria yang didapatkan.



1. d)Flowmap yang sedang berjalan pada proses Rekam Medis

**Gambar 3.6 Proses Rekam Medis di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses rekam medis adalah sebagai berikut :

1. Dalam proses pemeriksaan, dokter menanyakan kartu pasien/berobat kepada Pasien untuk keperluan pencarian data rekam medis.
2. Pasien menunjukan kartu pasien kepada dokter.
3. Dokter melakukan Login kedalam sistem.
4. Dokter melakukan pencarian data rekam medis pasien melalui identitas pasien di dalam sistem.
5. Dokter menanyakan keluhan dan melakukan tensi darah kepada pasien sebelum melakukan pemeriksaan lebih lanjut.
6. Dokter memeriksa pasien.
7. Dokter memasukan data riwayat penyakit pasien kedalam menu rekam medis didalam aplikasi.
8. Apabila pasien diperlukan untuk dirujuk maka dokter masuk menu rujukan tetapi apabila tidak perlu dokter memberikan resep kepada pasien.
9. Pasien menerima resep.

Flowmap yang akan sedang berjalan pada proses rujukan

**Gambar 3.7 Proses Rujukan di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses rujukan adalah sebagai berikut :

1. Pada proses ini Dokter sudah dalam keadaan  telah login atau masuk kedalam  halaman utama yang berisi menu-menu sesuai  hak akses dokter
2. Setelah pemeriksaan kesehatan oleh dokter apabila keadaan pasien kurang baik untuk diberikan obat atau cukup darurat  maka dokter memutuskan pasien untuk dirujuk .
3. Dokter membuat surat rujukan untuk diberikan kepada pelayan kesehatan lain dengan memberikan data pasien yang diperoleh dari sistem (data dokter dan data pasien)
4. Dokter menambahkan keluhan pasien didalam surat rujukan secara manual (tidak mengambil data dari database)
5. Melakukan print preview surat rujukan.
6. Dokter mencetak surat rujukan dan memberikan nya kepada pasien.
7. Pasien menerima surat rujukan dari dokter.

1. e)Flowmap yang sedang berjalan pada proses pembuatan laporan

**Gambar 3.8 Proses pembuatan laporan di Klinik Tanimulya Medika yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses laporan adalah sebagai berikut:

1. Petugas mengakses alamat web  kemudian melakukan login melalui halaman web utama yang terdapat pada menu yang telah disediakan dlaam sistem aplikasi yaitu menu &quot;Login&quot;
2. Petugas mengakases halaman laporan pada sistem aplikasi yang berisi menu-menu sesuai hak aksesnya. Untuk memgakses laman laporan dapat memilih menu &quot;Laporan&quot; pada menu aplikasi yang telah disediakan.
3. Aplikasi secara otomatis merekap data-daya yang diperlukan berdasarkan data yang diambil dari data dokter dan data rekam medis dalam databse masuk ke data laporan.
4. Sebelum mencetak laporan, petugas melakukan _print preview_ kemudiam memilih perintah untuk mencetak yang ada didalam _print preview_.

lowmap yang sedang berjalan pada proses pembayaran

**Gambar 3.9 Proses pembayaran di Klinik Tanimulya yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses pembayaran adalah sebagai berikut: