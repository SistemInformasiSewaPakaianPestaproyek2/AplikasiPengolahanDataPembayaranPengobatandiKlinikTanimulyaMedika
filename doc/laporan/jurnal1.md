

**PERANCANGAN SISTEM INFORMASI MANAJEMEN**

**PADA KLINIK SKALA KECIL**

**(Studi Kasus: Klinik Dr. Jonni)**



**Ayuliana; Stanislaus Steven Wijaya;**

**Lawrentius Siangjaya Lawunugraha; Irene Anindaputri Iswanto**

Computer Science Department, School of Computer Science, Binus University

Jl. K.H. Syahdan No. 9, Palmerah, Jakarta Barat 11480 ayuliana\_st@binus.ac.id **;** steven.wijayaaa@gmail.com **;** lslbinv10@yahoo.co.id **;** irene\_aninda@yahoo.com



**ABSTRACT**



_The purpose of this research was to develop a database application at dr. Jonni clinic which can be used for processing and recording of operational data with an attractive user interface. Through the integrated database application, data on dr. Jonni clinic would be more structured, therefore data retrieval will go faster and more accurate, data security administration will be increased, data redundancy will be eliminated and service performance clinic dr. Jonni will also be increased. The method of analysis includes the study of literature, examination of documentation, observation, and interviews. While in the design, the method includes application design using the waterfall method models, database design and data modeling application screens using State Transition Diagrams. The results achieved from this research is an application of data base management hospital. With database applications, all data and information can be integrated well, so that it would improve the quality of services as well as facilitate storing and accessing data. The conclusions obtained from this research is the application of data base management hospital helps in generating quick and accurate information that is used to support operations and decision-making in the clinic dr. Jonni._

**Keywords:** _application, database, management, hospitals, clinics_



**ABSTRAK**



_Tujuan penelitian yaitu untuk mengembangkan aplikasi basis data pada Klinik dr. Jonni yang dapat digunakan dalam penyimpanan dan pengolahan data operasional dengan user interface yang menarik. Dengan adanya aplikasi basis data yang terintegrasi, maka data-data pada klinik dr. Jonni menjadi lebih terstruktur sehingga pencarian data menjadi lebih cepat dan akurat, keamanan data administrasi meningkat, menghilangkan redundansi data, dan kinerja pelayanan klinik dr. Jonni pun menjadi meningkat. Metode penelitian yang digunakan yaitu dengan metode analisis yang meliputi studi kepustakaan, pemeriksaan dokumentasi, observasi, dan wawancara. Sedangkan dalam perancangan, metode yang digunakan adalah meliputi perancangan aplikasi menggunakan metode waterfall model, perancangan basis data, serta perancangan layar aplikasi menggunakan State Transition Diagram. Hasil yang dicapai dari penelitian ini adalah sebuah aplikasi basis data manajemen rumah sakit. Dengan aplikasi basis data, semua data dan informasi dapat diintegrasikan dengan baik sehingga dapat membantu meningkatkan kualitas pelayanan klinik serta mempermudah dalam penyimpanan dan pengaksesan data. Simpulan yang didapat dari penelitian ini yaitu dengan adanya aplikasi basis data manajemen rumah sakit membantu dalam menghasilkan informasi yang cepat dan akurat yang digunakan untuk mendukung kegiatan operasional dan dalam pengambilan keputusan pada Klinik dr. Jonni._

**Kata kunci:** _aplikasi, basis data, manajemen, rumah sakit, klinik_









_Perancangan Sistem … (Ayuliana; dkk)_        1059

**PENDAHULUAN**

Teknologi informasi mampu menyediakan informasi yang dapat membantu pihak manajemen perusahaan dalam pengambilan keputusan yang bersifat strategis. Aplikasi basis data merupakan bagian dari teknologi informasi dalam hal penyimpanan, pengelolaan data dan informasi. Aplikasi basis data ini didukung oleh perangkat lunak yang disebut _Database Management System_ (DBMS). Selain berfungsi untuk menyediakan informasi, DBMS dapat meningkatkan keamanan data, mengintegrasikan data-data yang ada dalam perusahaan sehingga mengurangi tingkat redundansi data.

Klinik dr. Jonni merupakan suatu unit kesehatan masyarakat yang terletak di Perumahan Ciledug Indah 2 No. 33 (Blok C). Klinik tersebut memberikan jasa konsultasi kesehatan, pemeriksaan kesehatan dengan para dokter yang bertugas serta tindakan medis bagi para pasien (sesuai dengan Peraturan Menteri Kesehatan - 2011, Tentang Klinik). Selain itu, klinik ini juga melayani pasien dalam hal pembeli obat berdasarkan resep yang diberikan. Pelayanan kesehatan yang tersedia mulai dari kesehatan umum, spesialis gigi serta pemeriksaan kesehatan yang membutuhkan laboratorium seperti pemeriksaan gula darah dan kolesterol.

Untuk menjalankan kegiatan operasional, klinik masih menggunakan sistem pencatatan manual, sehingga Klinik dr. Jonni masih melakukan penyimpanan data administrasi berupa _hardcopy_ pembukuan. Sedangkan untuk penyimpanan data pasien dan obat masih mempergunakan Microsoft Office Excel 2007, di mana dalam pengelolaannya sering mengalami kesulitan karena untuk melakukan operasi-operasi yang rumit, dibutuhkan _user_ yang paham dan terampil dalam menggunakan Microsoft Excel, contohnya dibutuhkan rumus matematika tertentu dalam melakukan suatu operasi, sedangkan sampai saat ini karyawan Klinik dr. Jonni hanya memahami operasi-operasi dasar dalam Microsoft Excel, dan data yang tersimpan dalam Microsoft Excel hanya data pasien dan obat.



Dwi Jaya, Irfan (2011), dalam jurnalnya membuktikan bahwa dengan adanya sistem manajemen rumah sakit yang terintegrasi dapat mendukung, mempermudah, serta mengurangi kesalahan dalam pelaksanaan kegiatan operasional administrasi sehari-hari. Selain itu, sistem ini lebih efektif dan efisien baik dari segi sumber daya manusia maupun dari segi pembagian tugasnya dibandingkan dengan sistem manual. Melihat permasalahan tersebut, maka diperlukan suatu Sistem Informasi Manajemen Klinik yang dapat mengintegrasikan semua data dan informasi dengan baik, sehingga dapat membantu meningkatkan kualitas pelayanan klinik serta mempermudah dalam penyimpanan dan pengaksesan data. Aplikasi juga memudahkan petugas klinik dalam mengerjakan tugas-tugas operasional klinik dr. Jonni karena aplikasi telah disesuaikan dengan tugas yang ada. Dengan adanya aplikasi basis data manajemen rumah sakit yang terintegrasi, di harapkan pengelolaan data dapat dilakukan dengan efisien, aman dan akurat.

Maka penelitian ini bertujuan untuk merancang dan menghasilkan aplikasi yang meliputi: (1) Pendaftaran pasien, mencakup data pasien dan data riwayat medis pasien. (2) Pencatatan data staff / karyawan, obat dan lab, rekanan klinik, supplier obat dan alat kesehatan, produsen obat dan alat kesehatan. (3) Pencatatan kode keuangan/general ledger. (4) Pengobatan pasien dan pemberian obat.

(5) Pencatatan keuangan klinik. (6) Pencatatan pembayaran pengobatan pasien. (7) Pembuatan laporan yang ditujukan kepada dr. Jonni

**METODE**

Penelitian ini berdasarkan pada kenyataan bahwa dibutuhkannya sebuah sistem informasi manajemen yang mampu mengumpulkan data dan memberikan informasi yang akurat secara tepat dan cepat. Data yang digunakan adalah data primer, yang diperoleh dengan pemeriksaan dokumentasi yang



1060        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

secara langsung mengumpulkan data dan informasi yang dibutuhkan dari dokumen internal Klinik dr. Jonni. Dari pemeriksaan dokumen internal ini akan diperoleh informasi yang mendukung dalam perancangan aplikasi basis data yang akan dibuat. Observasi dilakukan dengan melakukan survei dan mengamati kegiatan operasi pada Klinik dr. Jonni. Dari obervasi yang dilakukan akan diperoleh informasi yang dapat digunakan dalam merancang aplikasi basis data, dan wawancara dilakukan terhadap pihak Klinik dr. Jonni untuk menentukan dan menganalisis aplikasi basis data yang diinginkan. Wawancara juga dilakukan untuk memperoleh informasi tambahan mengenai berbagai proses yang tengah berjalan dalam Klinik dr. Jonni, permasalahan yang sedang dihadapi, dan kebutuhan akan aplikasi basis data yang sesuai.

Data kualitatif/data sekunder diperoleh dari studi kepustakaan dari berbagai sumber referensi baik fisik maupun elektronik yang berkaitan dengan perancangan aplikasi basis data sehingga dapat digunakan untuk merancang aplikasi basis data. Pengolahan dan analisis data, dilakukan sesuai dengan batasan penelitian dengan tujuan dapat menjawab permasalahan. Setelah data diolah, diharapkan didapat suatu aplikasi yang dapat membantu klinik dan petugas serta pemilik klinik khususnya dalam mencapai tujuannya.



**HASIL DAN PEMBAHASAN**



**Prosedur Pendaftaran Pasien**

Pasien datang dan melakukan pendaftaran di bagian administrasi. Selanjutnya pegawai administrasi akan menanyakan apakah pasien tersebut pernah berobat di klinik dr. Jonni. Jika pasien belum pernah berobat, data pasien akan dicatat di buku daftar pasien. Setelah semua data lengkap, akan dibuat kartu berobat, yang kemudian diserahkan kepada pasien atau kerabat yang mendaftarkan. Setelah mendapatkan kartu berobat, pasien menunggu giliran berobat dan pegawai administrasi akan membuat rekam medis. Jika pasien sudah terdaftar, pegawai administrasi akan menanyakan kepada pasien apakah pasien membawa kartu berobat. Jika pasien membawa kartu berobat, pegawai administrasi akan mencocokkan NRM (Nomor Rekam Medis) yang ada di kartu berobat dengan yang ada di rekam medis. Namun bila pasien tidak membawa kartu berobat, maka pegawai administrasi akan menanyakan nama dan alamat pasien lalu mencari rekam medis di rak buku penyimpanan rekam medis berdasarkan identitas pasien.

Pegawai administrasi akan mencatat data pasien dan data dokter yang dituju pada buku daftar hadir pasien. Kemudian pegawai administrasi akan membawa rekam medis pasien yang bersangkutan ke ruangan dokter yang dituju sementara pasien menunggu giliran untuk berobat. Gambar 1._Flowchart_

Prosedur Pendaftaran Pasien

**Prosedur Pengobatan Pasien**

Pasien yang sudah mendapatkan giliran berobat memasuki ruang pemeriksaan. Selanjutnya pasien akan berkonsultasi dan dokter melakukan pemeriksaan fisik terhadap pasien. Jika dokter merasa pasien membutuhkan pemeriksaan lebih lanjut di lab, dokter akan menanyakan kepada pasien apakah bersedia menjalani pemeriksaan lab? Jika pasien bersedia, dokter akan memberikan surat lanjutan ke bagian lab berisi jenis pemeriksaan lab yang harus diikuti oleh pasien. Surat diberikan kepada pasien untuk selanjutnya diberikan kepada pegawai laboratorium.

Selanjutnya pegawai laboratorium akan melakukan pemeriksaan laboratorium yang dibutuhkan pasien. Setelah analisa hasil pemeriksaan laboratorium telah dilakukan, maka hasil analisa laboratorium diberikan ke dokter. Setelah semua pemeriksaan selesai, dokter akan membuat resep obat



_Perancangan Sistem … (Ayuliana; dkk)_        1061

dan memberikannya kepada pasien. Selain itu, dokter juga akan mencatat keluhan pasien, hasil pemeriksaan fisik, diagnose, hasil analisa lab dan resep obat pada rekam medis pasien yang bersangkutan (Peraturan Menteri Kesehatan, 2011). Rekam medis ini diserahkan ke pegawai keperawatan untuk kemudian diserahkan ke bagian keuangan (kasir) agar pasien dapat mengetahui jumlah biaya yang harus dibayar.









































Gambar 1 _Flowchart_ Prosedur Pengobatan Pasien



**Prosedur Penjualan Obat**

Penjualan obat hanya dapat dilakukan bagi pasien yang telah terdaftar di klinik dr. Jonni. Penjualan obat dilakukan dengan dua cara, yaitu penjualan obat langsung dan penjualan obat yang didahului dengan pengobatan dokter. Untuk penjualan obat yang didahului dengan pengobatan dokter, pasien membawa resep yang diberikan oleh dokter ke bagian apotek. Selanjutnya pegawai apotek akan memeriksa ketersediaan obat yang dibutuhkan. Jika obat tidak tersedia, maka pegawai apotek akan mengembalikan resep kepada pasien dan meminta pasien untuk menebus obat ke apotek lain. Selanjutnya pegawai apotek akan mencatat ketidaktersediaan obat tersebut pada buku catatan ketersediaan obat untuk menentukan berapa anggaran yang dibutuhkan untuk membeli stok obat yang telah habis.



1062        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

Jika obat yang dibutuhkan tersedia, maka pegawai apotek akan memberikan obat sesuai dengan komposisi dan ketentuan yang pada resep obat. Selanjutnya pegawai apotek akan memberikan resep obat beserta obatnya ke bagian keuangan (kasir). Bagian keuangan (kasir) akan membuat kuitansi dan memberikannya kepada pasien yang bersangkutan untuk membayar obat yang ditebus. Kemudian bagian keuangan (kasir) akan mencatat transaksi dalam buku keuangan.









































Gambar 2 _Flowchart_ Prosedur Penjualan Obat



**Prosedur Pembayaran Pasien**

Mekanisme pembayaran pasien dapat dilakukan dengan: (1) Pembayaran pasien langsung – Bagian keuangan (kasir) menerima rekam medis pasien dari bagian keperawatan untuk menghitung total biaya yang harus dibayar oleh pasien yang bersangkutan beserta hutangnya jika ada. Setelah bagian keuangan selesai menghitung biaya pasien, rekam medis pasien akan dikembalikan ke bagian administrasi untuk disimpan. Selanjutnya bagian keuangan (kasir) akan memanggil pasien untuk melunasi pembayaran. Bagian keuangan akan menyebutkan total nominal yang harus dibayarkan oleh pasien. Setelah pasien melunasi pembayaran, maka pasien akan diberikan kuitansi pembayaran sebagai tanda bukti pembayaran. Selanjutnya, bagian keuangan akan mencatat transaksi ke dalam



_Perancangan Sistem … (Ayuliana; dkk)_        1063

buku keuangan. (2) Pembayaran pasien melalui rekanan – Bagian keuangan (kasir) menerima rekam medis pasien dari bagian keperawatan untuk menghitung total biaya yang harus dibayar oleh pasien yang bersangkutan. Setelah bagian keuangan selesai menghitung biaya pasien, rekam medis pasien akan dikembalikan ke bagian administrasi untuk disimpan. Selanjutnya, bagian keuangan akan mencatat transaksi ke dalam buku keuangan. Setiap akhir bulan, bagian keuangan akan merekap total piutang per rekanan. Kemudian bagian keuangan akan membuat surat tagihan yang berisikan data pengobatan pasien selama satu bulan berikut total biayanya dan mengirimkannya kepada rekanan. Apabila biaya telah lunas dibayar, maka bagian keuangan akan memberikan bukti pembayaran berupa kuitansi pada rekanan yang bersangkutan.



































]

Gambar 3 _Flowchart_ Prosedur Pembayaran Pasien

**Prosedur Pembelian Obat**

Setiap akhir bulan, bagian apotek (apoteker) akan melakukan _stock opname_ yaitu pengecekan stok obat di apotek dan pencatatan stok obat yang telah habis. Selanjutnya bagian apotek akan menyerahkan daftar stok obat yang telah habis ini ke bagian keuangan. Bagian keuangan akan menghitung jumlah anggaran biaya yang dibutuhkan untuk memenuhi stok obat yang telah habis. Selanjutnya bagian keuangan akan menghubungi pemasok obat dan membelikan semua kebutuhan obat yang dibutuhkan oleh klinik. Setelah pemasok mengirim obat, pemasok akan membuatkan sebuah faktur pembelian obat dalam bentuk dua slip, satu slip asli pembayaran diberikan ke bagian keuangan dan satu slip _copy_ untuk pemasok. Pembayaran obat dapat dilakukan dengan dua cara yaitu cara tunai dan hutang.



1064        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

Apabila pembayaran dilakukan secara tunai maka pemasok akan menerima pembayaran pada saat barang dikirimkan. Namun apabila pembayaran dilakukan secara hutang, maka pemasok akan menerima pembayaran paling lambat pada saat tanggal jatuh tempo yaitu satu bulan setelah obat dikirimkan. Setelah transaksi pembayaran pembelian obat telah selesai dilakukan maka pemasok akan memberikan tanda lunas ke bagian keuangan. Setelah itu obat yang telah dibeli akan diserahkan ke bagian apotek akan melakukan penyesuaian stok obat. Bagian keuangan akan mencatat transaksi pembelian obat dalam buku keuangan.











































Gambar 4 _Flowchart_ Prosedur Pembelian Obat



**Pembuatan Laporan**

Setiap bagian dan sub bagian diwajibkan untuk membuat laporan kepada pemilik klinik secara berkala, baik harian maupun bulanan. Laporan yang dibuat berupa laporan obat (laporan pemakaian obat, laporan pembelian obat dan laporan stok obat), laporan keuangan (neraca dan laporan laba rugi), dan laporan pasien.





_Perancangan Sistem … (Ayuliana; dkk)_        1065







































Gambar 5 _Flowchart_ Prosedur Pembuatan Laporan

**Analisa Sistem Basis Data**

Adapun permasalahan yang dihadapi oleh Klinik dr. Jonni saat ini, adalah sebagai berikut: (1) Pencatatan dan penyimpanan data pasien, karyawan, obat, laboratorium, rekanan, supplier, transaksi, rekam medis masih manual dan sering dijumpai banyak kesalahan sehingga data ada yang redundan dan tidak valid. (2) Kesulitan dalam pencarian data karena data sering tersimpan tidak pada tempatnya dan faktor jumlah data yang besar. (3) Pengolahan data antar bagian belum terintegrasi sehingga menyulitkan dalam pembuatan laporan. (4) Belum adanya sistem keamanan data yang disebabkan karena dokumen masih tersimpan di dalam buku besar dan rak pembukuan menyebabkan data rusak, hilang, dan tidak terjamin kerahasiannya.

**Rencana Pemecahan Masalah**

Berdasarkan permasalahan yang telah disebutkan di atas, pemecahan masalah yang dapat dilakukan saat ini adalah dengan cara membangun aplikasi basis data di Klinik dr. Jonni karena aplikasi memiliki _user interface_ yang sudah sangat sesuai dengan kegiatan operasional klinik sehari-hari sehingga tidak dibutuhkan keterampilan khusus dalam penggunaannya. Rancangan aplikasi basis data yang diajukan harus mampu memenuhi kebutuhan manajemen Klinik dr. Jonni sebagai berikut:



1066        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

(1) Pencatatan dan penyimpanan data pasien, karyawan, obat, laboratorium, rekanan, supplier, transaksi, rekam medis dilakukan dengan sebuah aplikasi basis data manajemen rumah sakit sehingga integritas data lebih terjamin. (2) Pencarian data menjadi lebih mudah karena aplikasi basis data akan didukung dengan fitur pencarian data. (3) Membuat sistem komputerisasi pengolahan data antar bagian yang terintegrasi satu sama lain untuk mempermudah pengelolaan data transaksi untuk membuat laporan keuangan (neraca dan laporan laba rugi), laporan obat (laporan pemakaian obat, laporan pembelian obat dan laporan stok obat), laporan pasien, dan resume medis pasien sehingga kegiatan operasional di Klinik dr. Jonni dapat berlangsung efektif, efisien, dan cepat. (3) Membuat sistem keamanan data untuk seluruh dokumen yang tersimpan dalam sistem basis data manajemen rumah sakit berbasis aplikasi sehingga hanya pihak yang berwenang dan berkepentingan yang dapat mengakses data. Hal tersebut dapat menjamin minimnya resiko kerusakan, kehilangan, serta meningkatkan integritas data.

**Perancangan Sistem Informasi Manajemen Klinik yang Diusulkan**

Rancangan sistem yang diusulkan digambarkan dengan perancangan basis data konseptual, logikal sesuai dengan tahapan siklus hidup aplikasi basis data (Connolly dan Begg, 2005).

**Perancangan Basis Data Konseptual / Mengidentifikasi Tipe Relasi**



Tabel 1 Tipe Relasi











_Perancangan Sistem … (Ayuliana; dkk)_        1067

























Gambar 6 ERD Konseptual dengan _multiplicity_ **Perancangan Basis Data Logikal**



Dengan melakukan langkah-langkah seperti: menghilangkan tipe relasi many to many, _multi__valued_ atribut, menentukan entitas kuat dan lemah, dan memvalidasi dengan normalisasi, diperolehERD sebagai berikut :































Gambar 7 ERD Normalisasi



1068        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

**Perancangan Struktur Menu**































Gambar 8 Perancangan Struktur Menu Klinik dr. Jonni



**Halaman Beranda**















Gambar 9 Tampilan Layar Halaman Beranda



Pada halaman ini dapat dilihat foto-foto klinik, visi dan misi klinik, serta dapat dilihat grafik jumlah pasien dengan meng-_click_ tombol &quot;Lihat Grafik Jumlah Pasien&quot;. Tersedia pilihan menu dan _submenu_ sesuai dengan hak akses yang dimiliki oleh _user_ tersebut. Secara umum menu pada aplikasiini terdiri dari lima yakni Master, Pasien, Kasir, Administrasi, Laporan. Sedangkan _submenu_ untuk menu Master terdiri dari 10 yakni Master Pasien, Master Obat, Master Lab, Master Rekanan, Master Supplier, Master Pegawai, General Ledger, Master Produsen Obat, Master Kategori Obat, Master Jabatan Pegawai. _Submenu_ untuk menu Pasien terdiri dari empat yakni Pendaftaran Pasien, Rekam



_Perancangan Sistem … (Ayuliana; dkk)_        1069

Medis, Tambah Lab, Daftar Obat dan Lab. _Submenu_ untuk menu Kasir terdiri dari dua yakni Pembelian Obat Saja, Kasir. _Submenu_ untuk menu Administrasi terdiri dari lima yakni Pembelian Obat, Pengeluaran Tidak Tetap, Pengeluaran Tetap Kas dan Bank, DP Rekanan, Pembayaran Hutang. _Submenu_ untuk menu Laporan ada 11 yakni Laporan Obat Terpakai Bulanan, Laporan Obat TerpakaiHarian, Laporan Pasien Harian, Laporan Pasien Bulanan, Laporan Stok Obat, Laporan Pembelian Obat, Laporan Laba Rugi, Neraca, Stok Opname, Laporan Keuangan Harian, Resume Medis Pasien.

**Halaman Master Pasien**

Pada halaman ini akan ditampilkan daftar semua pasien dengan informasi detail yang telah terdaftar di Klinik dr Jonni. Juga terdapat fitur pencarian cepat pasien berdasarkan nama pasien, alamat atau tanggal lahir. Pada halaman ini, user yang memiliki jenis hak sebagai _admin_ memiliki fitur tambahan yakni tombol &quot;Ubah&quot; untuk mengubah pasien.

















Gambar 10 Tampilan Layar Halaman Master Pasien



**Halaman Master Obat**























Gambar 11 Tampilan Layar Halaman Master Obat





1070        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

Pada halaman ini akan ditampilkan daftar semua obat dengan informasi _detail_ yang telah tersedia di Klinik dr Jonni. Juga terdapat fitur pencarian cepat obat berdasarkan nama obat, nomor rak obat. Pada halaman ini, _user_ yang memiliki jenis hak sebagai _admin_ memiliki beberapa fitur tambahan yakni dapat tombol &quot;Masukkan Data Obat&quot; untuk menambah obat, &quot;Ubah&quot; untuk mengubah obat dan &quot;Hapus&quot; untuk menghapus data obat, menentukan harga jual obat berdasarkan penambahan margin persentase harga satuan obat dengan mengisi pada &quot;Margin&quot; dan meng-_click_ &quot;Kirim&quot;.

**Halaman Master Pegawai**

_User_ yang memiliki hak akses &quot;Master Pegawai&quot; baik sebagai _admin_ maupun _staff_ dapatmengakses halaman ini. Pada halaman ini akan ditampilkan daftar semua pegawai dengan informasi detail yang telah tersedia di Klinik dr Jonni. Pada halaman ini dilengkapi juga dengan fitur pencarian cepat pegawai berdasarkan nama pegawai. Pada halaman ini, _user_ yang memiliki jenis hak sebagai _admin_ memiliki beberapa fitur tambahan yakni dapat tombol &quot;Masukkan Data Pegawai Baru&quot; untukmenambah pegawai, &quot;Ubah Profil&quot; untuk mengubah profil pegawai, &quot;Ganti Kata Sandi&quot; untuk mengubah kata sandi pegawai, &quot;Hapus&quot; untuk menghapus pegawai dan &quot;Hak Akses&quot; untuk menambah/mengubah hak akses dari pegawai.

















Gambar 12 Tampilan Layar Halaman Master Pegawai



**SIMPULAN**



Dengan adanya sistem yang diusulkan pada Klinik dr. Jonni, dapat diambil kesimpulan sebagai berikut: (1) Aplikasi basis data yang dibuat dapat menyelesaikan masalah integritas data yang meliputi encatatan dan penyimpanan data pasien (Gambar 10), karyawan (Gambar 12), obat (Gambar 11), laboratorium, rekanan, supplier, transaksi medis, rekam medis. (2) Aplikasi basis data yang dibuat telah menyelesaikan masalah pencarian data dengan memberikan fitur pencarian pada halaman aplikasi yang membutuhkan pencarian data secara cepat. (3) Aplikasi basis data yang dibuat dapat menyelesaikan masalah dalam pembuatan laporan karena data telah terintegrasi. Laporan yang ada yaitu laporan pasien Pasien Harian dan Laporan Pasien Bulanan, laporan obat, Laporan Pembelian Obat, dan laporan keuangan. (4) Aplikasi basis data yang dibuat dapat menyelesaikan masalah keamanan data dengan adanya menu untuk memberikan hak akses kepada bagian yang berwenang untuk melihat dan melakukan modifikasi pada data tertentu.







_Perancangan Sistem … (Ayuliana; dkk)_        1071

**DAFTAR PUSTAKA**



Connoly, T., Begg, C. (2010) . _Database Systems: A Pratical Approach To Design, Implementation, and__Management, Fifth Edition_. Harlow: Addison Wesley.

Dwi, J. I. (2011).  Sistem Informasi Rumah Sakit Dr. AK. Gani Palembang (Aplikasi Administrasi).

_Jurnal Teknologi dan Informatika_ (_Teknomatika_). _1_(3): 223-246.

Menteri Kesehatan. (2011). _Peraturan Menteri Kesehatan Republik Indonesia Nomor__028/MENKES/PER/I/201_1, diakses pada tanggal 11 November 2013 darihttp://www.dikti.go.id/files/atur/Permenkes28-2011.pdf


















1072        ComTech Vol. 5 No. 2 Desember 2014: 1059-1072

