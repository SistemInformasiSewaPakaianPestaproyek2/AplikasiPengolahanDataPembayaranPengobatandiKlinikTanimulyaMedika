**Gambar 3.16**  **Sequ**** e ****nce Diagram**  **Laporan Pendapatan**

Keterangan :

1. Petugas memilih menu laporan pendapatan pada menu utama petugas;
2. Koneksi data dengan database;
3. Koneksi data pembayaran pada tabel pembayaran;
4. Database mengkonfirmasi data pembayaran;
5. Petugas mengubah data laporan pendapatan;
6. Mengkoneksikan perubahan data laporan pendapatan ke database tabel pendapatan;
7. Database mengkonfirmasi perubahan data laporan pendapatan;
8. Petugas melakukan _print preview_;
9. Petugas mencetak laporan pendapatan;
10. Petugas memperoleh data laporan pendapatan dalam bentuk dokumen.

1.
  1.
    1. 2.4 **Collaboration Diagram**
      1. 2.4.1 **Collaborarion Diagram Pembayaran**

**Gambar 3.17 Collaboration Diagram Pembayaran**

Keterangan :

1. Kasir masuk ke menu utama kasir atau admin. Terdapat aktivitas koneksi ke database;
2. Memvalidasi data rincian pemeriksaan;
3. Ada konfirmasi dari kelola data rincian;
4. Memvalidasi biaya dari rincian pemeriksaan;
5. Kelola biaya pemeriksaan mengkonfirmasi biaya rincian pemeriksaan;
6. Konfirmasi data biaya obat-obatan;
7. Bagian apotik mengkonfirmasi biaya obat-obatan;
8. Kasir menginputkan rincian pemeriksaan beserta biayanya;
9. Kasir menyimpan data pembayaran;
10. Kasir mencetak bukti pembayaran.

1.
  1.
    1.
      1. 2.4.2 **Collaboration Diagram Laporan Pendapatan**

**Gambar 3.18 Collaboration Diagram Laporan Pendapatan**

Keterangan :

1. Admin keuangan melakukan Login, masuk ke menu Utama Admin, memilih menu Laporan Pendapatan;
2. Melakukan pengkoneksian data ke database;
3. Databases melakukan koneksi ke data pembayaran pemeriksaan;
4. Data pembayaran mengkonfirmasi;
5. Database mengkonfirmasi data laporan;
6. Admin mengedit dan menambahkan data lainnya;
7. Admin diberi hak akses untuk melihat, dan mencetak laporan;
8. Menu laporan mengkonfirmasi data ke menu utama admin;
9. Admin mencetak dan mendapat hasil cetak laporan.

1.
  1.
    1. 2.5 **Activity Diagram**
      1. 2.5.1 **Activity Diagram Pembayaran**

**Gambar 3.19  Activity Diagram Pembayaran**

Keterangan :

1. Petugas mengakses menu pembayaran;
2. Sistem aplikasi menampilkan form menu pembayaran;
3. Petugas memasukan data pasien, data dokter dan rincian biaya medis;
4. Sistem aplikasi menampilkan inputan data pemabayaran;
5. Petugas menghitung total biaya;
6. Sistem aplikasi menampilkan total biaya;
7. Petugas menyimpan data pembayaran;
8. Aplikasi menyimpan data pembayaran;
9. Petugas memilih tombol print untuk mencetak bukti pembayaran;
10. Sistem aplikasi tersambung dengan printer untuk mencetak bukti pembayaran.

1.
  1.
    1.
      1. 2.5.2 **Activity Diagram Laporan Pendapatan**

**Gambar 3.20 Activity Diagram Laporan Pendapatan**

Keterangan :

1. Petugas mengakse menu utama laporan pendapatan;
2. Sistem aplikasi menampilkan data laporan pendapatan;
3. Petugas menambhakan data biaya admin;
4. Sistem aplikasi menampilkan data inputan;
5. Petugas menyimpan data laporan pendapatan;
6. Sistem aplikasi menyimpan perubahan data ke database;
7. Petugas melakukan print preview data laporan;
8. Sistem aplikasi menampilkan detail data laporan dalam bentuk print preview;
9. Petugas mengklik tombol cetak;
10. Sistem aplikasi tersambung dengan printer untuk mencetak laporan pendapatan.



1.
  1.
    1. 2.6 **Statechart Diagram**
      1. 2.6.1 **Statechart Diagram Pembayaran**

**Gambar 3.22 Statechart Diagram Pembayaran**

1.
  1.
    1.
      1. 2.6.2 **Statechart Diagram Laporan Pendapatan**

**Gambar 3.24 Statechart Diagram Laporan Pendapatan**



1.
  1.
    1. 2.7 **Component Diagram**

**Gambar 3****.25 **** Component Diagram**



1.
  1.
    1. 2.8 **Deployment Diagram**

**Gambar 3.**** 26 **** Deployment Diagram**



1.
  1.
    1. 2.9 **Sturktur Menu**



**Gambar 3.**** 27 **** Struktur Menu**

1.
  1.
    1. 2.10 **Perancangan Antarmuka**
      1. 2.10.1 **Form Transaksi Pembayaran**

**Gambar 3.**** 28 Rancangan Form Transaksi Pembayaran**

Algoritma :

Begin if

Pilih menu : Pembayaran

Then menginputkan data pembayaran

        If pilih item : Print

        Then tercetak bukti pembayaran

Else

Pilih item close : Keluar Halaman

End If

End

1.
  1.
    1.
      1. 2.10.2 **Form Edit Laporan Pendapatan**

**Gambar 3.**** 29 Rancangan Form Edit Laporan Pendapatan**

Algoritma :

Begin if

Pilih menu : laporan pendapatan

Then menampilkan data laporan pendapatan

        Else pilih item : edit

Then mengedit laporan pendapatan.

Else

Pilih close

End if

End

1.
  1.
    1.
      1. 2.10.3 **Data Laporan Pendapatan**

**Gambar 3.**** 30 Rancangan Tampilan Data Laporan Pendapatan**

Algoritma :

Begin if

Pilih menu : Laporan pendapatan

Then menampilkan data laporan pendapatan

        Else pilih item : Edit

        Then menampilkan form edit laporan pendapatan

Else if

Pilih close

End if

End

1.
  1.
    1.
      1. 2.10.4 **Data Pembayaran**

**Gambar 3.**** 31 Rancangan Tampilan Data Pembayaran**

Algoritma :

Begin if

Pilih menu : Data Pembayaran

Then menampilkan data pembayaran

        Else pilih item : Edit

        Then menampilkan form edit pembayaran

Else if

Pilih menu tambah

Then menampilkan form  pembayaran

Else if

Pilih close

End if

End