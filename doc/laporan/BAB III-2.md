1. rincian biaya kebagian admin .
2. Petugas atau bagian admin menerima resep dan rincian biaya.
3. Petugas bagian admin atau kasir menghitung rincian biaya dan menerima total biaya obat-obatan dari bagian farmasi (apotek).
4. Petugas memberikan informasi kepada pasien mengenai jumlah biaya yang harus dibayar oleh pasien.
5. Pasien melakukan pembayaran.
6. Petugas membuat kwitansi atau bukti pembayaran.
7. Pasien menerima bukti pembayaran.

1. a)Flowmap yang sedang berjalan pada proses pembuatan laporan pendapatan

**Gambar 3.10 Proses pembuatan laporan pendapatan di Klinik Tanimulya yang sedang berjalan**

Deskripsi sistem yang sedang berjalan dalam proses pembuatan laporan pendapatan adalah sebagai berikut:

1. Pasien memberikan rincian biaya medis kepada bagian admin.
2. Petugas admin menerima rincian biaya medis.
3. Petugas merekap data biaya medis kedalam software aplikasi pengolah data.
4. Petugas mencetak laporan pendapatan.

1.
  1.
    1.
      1. 1.1.2 **Analisis dokumen yang digunakan**

Tabel 3.1 Analisis dokumen yang sedang berjalan

1.
  1.
    1. 1.2 **Analisis sistem yang akan dibangun**

Dari analisis yang telah dilakukan, maka dapat dibuat sebuah analisis prosedur pelayanan pasien yang akan dibangun pada &quot;Klinik Tanimulya Medika&quot; yang menggambarkan proses pada pengelolaan data klinik di Klinik Tanimulya Medika. Adapun alur proses yang akan dibangun adalah sebagai berikut :

1. a)Flowmap pada proses pembayaran yang akan dibangun

**Gambar 3.**** 11 ****Proses**  **Pembayaran**  **di Klinik Tanimulya Medika yang**  **akan dibangun**

Deskripsi sistem yang akan dibangun dalam proses pembayaran terdapat beberapa tahap yaitu :

1. Kasir mengecek status pasien sudah mendaftar atau belum, apabila belum maka konfirmasi kebagian admin untuk memproses pendaftaran.
2. Kasir mengecek data rincian pemeriksaan dan total biaya obat-obatan. Apabila total biaya obat-obatan belum tercantum maka konfirmasi ke bagian apotek untuk memproses data total biaya obat-obatan.
3. Setelah semua data pembayaran terkumpul dan telah dicek maka diinputkan kedalam sistem untuk menyimpan data pembayaran dan melakukan transaksi pembayaran.
4. Menjumlahkan total biaya pengobatan. Kemudian disimpan datanya didalam tabel pembayaran.
5. Kasir mencetak bukti pembayaran.

Flowmap pada proses pembuatan laporan pendapatan yang akan dibangun

**Gambar 3.12 Proses pembuatan laporan pendapatan di Klinik Tanimulya yang akan dibangun**

Deskripsi sistem yang akan dibangun dalam proses pembayaran terdapat beberapa tahap yaitu :

1. Petugas mengakses menu laporan pendapatan pada menu utama.
2. Petugas merekap data jumlah pasien dan detail data pemabayarn setiap pasien yang diambil dari tabel pembayaran.
3. Petugas menginput data biaya admin, nama assisten atau petugas medis.
4. Petugas menyimpan data yang telah ditambahkan.
5. Data yang telah direkap disimpan ke tabel pendapatan.
6. Petugas melihat dokumen yang akan dicetak (_print preview_).
7. Petugas mencetak lalporan pendapatan.

1.
  1.
    1.
      1. 1.2.1 **Analisis kebutuhan aplikasi**

Analisis kebutuhan aplikasi secara garis besar dilakukan dengan cara membuat UML (Unifield Modeling Language), scenario, dan Class Diagram Aplikasi Pengolahan Data  Pembayaran Pengobatan menggunakan framework codeigniter di Klinik Tanimulya Medika.

Tabel 3.2 Analisis kebutuhan aplikasi

1.
  1.
    1.
      1. 1.2.2 **Analisis kebutuhan perangkat lunak dan perangkat keras**

Analisis kebutuhan perangkat lunak dan perangkat keras dilakukan untuk mengetahui spesifikasi kebutuhan untuk sistem. Spesifikasi kebutuhan melibatkan analisis perangkat keras/_hardware_, analisis perangkat lunak/_software_, analisis pengguna/_User_. Adapun kebutuhan perangkat lunak dan perangkat keras yang akan dibuat adalah sebagai berikut :



**Kebutuhan Perangkat Keras**

Tabel 3.3Deskripsi Perangkat Keras _Server_

Tabel 3.4 Deskripsi Perangkat Keras _Client_



1. **Kebutuhan Perangkat Lunak**

Tabel 3.5 Deskripsi Perangkat Lunak _Server_

Tabel 3.6 Deskripsi Perangkat Lunak _Client_

1.
  1. 1. **Perancangan**
2.
3.
  1. 1.
  2. 2.
    1. 2.1. **Use Case Diagram**

**Gambar 3.**** 13 **** Use Case Diagram**

1.
  1.
    1.
      1. 2.1.1 **Definisi Aktor**

Pada bagian ini akan dijelaskan aktor-aktor yang terlibat Diagram Aplikasi Sistem Informasi dan Pengolahan Data di Klinik Tanimulya Medika.

Tabel 3.7 Definisi Aktor

1.
  1.
    1.
      1. 2.1.2 **Skenario Use Case Diagram**

        Skenario untuk masing-masing Use Case dari Aplikasi Sistem Informasi dan Pengolahan Data di Klinik Tanimulya Medika adalah sebagai berikut :

1.
  1.
    1.
      1.
        1. 2.1.2.1 **Skenario Use Case Kelola**  **Data Transaksi Pembayaran**

Table 3.8 Skenario Use Case Kelola Data Transaksi Pembayaran

1.
  1.
    1.
      1.
        1. 2.1.2.2 **Skenario Use Case**  **Kelola Laporan Pendapatan**

Table 3.9 Skenario Use Case Kelola Laporan Pendapatan

1.
  1.
    1. 2.2. **Class  Diagram**

**Gambar 3.**** 14 **** Class Diagram**

**Sequence Diagram**

1.
  1.
    1.
      1. 2.2.1. **Sequ**** e ****nce Diagram**  **Pembayaran**

**Gambar 3.15**  **Sequ**** e ****nce Diagram**  **Pembayaran**

Keterangan :

1. Kasir  mengakses menu utama petugas dan masuk ke menu pembayaran;
2. Menu utama melakukan koneksi ke database untuk pembayaran;
3. Melakukan pengecekan kepada data pemeriksaan;
4. Konfirmasi dari kelola data pemeriksaan;
5. Input data pemeriksaan ke sistem;
6. Validasi biaya pemeriksaan;
7. Konfirmasi dari kelola biaya pemeriksaan;
8. Validasi data rincian pemeriksaan;
9. Konfirmasi data rincian pemeriksaan;
10. Validasi data total biaya obat-obatan;
11. Konfirmasi data total biaya obat-obatan;
12. Kasir menginputkan seluruh data rincian pemeriksaan beserta total biaya obat dan mentotalkan seluruh biaya. Menyimpan data ke database;
13. Kasir mencetak bukti pembayaran.