# Kel-2-MI2022C.github.io
LAPORAN TUGAS PEMROGRAMAN WEB SRS GlamourousGems

Disusun oleh:
1. Adinda Nasywa Salsabila (22091397082)   2022C
2. M. Husein Abdillah      (22091397091)   2022C
3. Hkang Yochanan Tdamu    (22091397107)   2022C

Program Studi D4 Manajemen Informatika

Fakultas Vokasi

Universitas Negeri Surabaya

2023


Daftar Isi 

BAB I	

PENDAHULUAN	

1.1 Latar Belakang	

1.2 Tujuan	

1.3 Konvesi Dokumen	

1.4 Audiens yang Dituju dan Saran Bacaan	

1.5 Cakupan Produk	

1.6 Referensi	

BAB II	

DESKRIPSI KESELURUHAN	

BAB III	

PERSYARATAN ANTARMUKA EKSTERNAL	

BAB IV	

FITUR SISTEM DAN KERANGKA DESAIN FITUR	

BAB V	

PERSYARATAN NONFUNGSIONAL LAINNYA	

5.1 Persyaratan Kinerja	

5.2 Persyaratan Keselamatan	

5.3 Persyaratan Keamanan	

5.4 Atribut Kualitas Perangkat Lunak

5.5 Aturan Bisnis	

BAB VI	

PERSYARATAN LAINNYA	

6.1 Lampiran A: Glosarium	

6.2 Lampiran B: Model Analisis

6.3 Lampiran C :  Penjelasan Source Code	

1.  Penjelasan Source Code HTML	
2. Penjelasan Source Code Javascript	
3. Penjelasan Source Code CSS	

BAB 1

Pendahuluan

1.1 Latar Belakang

   Dalam era digital yang semakin maju ini, website telah menjadi bagian tidak terpisahkan dalam kehidupan sehari-hari. Website-website tersebut tidak hanya memberikan kenyamanan, tetapi juga membuka peluang baru dalam berbagai sektor, termasuk industri ritel. Salah satu bentuk website yang semakin populer adalah website GlamorousGems. Website GlamorousGems hadir sebagai solusi yang inovatif untuk mempermudah proses pengelolaan toko barang bekas. Dengan bantuan website ini, kami selaku pemilik website thrift shop dapat memperluas jangkauan pelanggan, mengelola inventaris barang dengan lebih baik, dan meningkatkan efisiensi operasional secara keseluruhan. Selain itu, website ini juga memberikan kemudahan bagi pelanggan dalam mencari produk, bertransaksi, Tidak hanya itu, website GlamorousGems juga menyediakan fitur manajemen inventaris yang komprehensif. Sehingga kami dapat dengan mudah melacak stok barang, memperbarui informasi produk, dan mengelola penambahan atau penghapusan barang dari inventaris.

   Kesimpulannya website GlamorousGems memberikan solusi modern untuk mengoptimalkan pengalaman belanja di website GlamorousGems. Dengan fitur-fitur yang inovatif dan efisien, website ini memudahkan pelanggan dalam mencari barang bekas berkualitas, serta membantu pemilik toko dalam mengelola inventaris, transaksi, dan operasional secara keseluruhan.

1.2 Tujuan

   Platform website e-commerce yang menawarkan barang bekas berkualitas kepada audiens yang lebih luas, dengan harga yang terjangkau. Tujuan dari website ini untuk menawarkan barang bekas yang berkualitas kepada audiens yang lebih luas. Target pasarnya yaitu individu yang mencari barang-barang vintage, unik, atau berharga dengan harga terjangkau.

1.3 Konvensi Dokumen

   Konvensi tipografi yang umum digunakan dalam SRS meliputi penggunaan huruf tebal atau italic untuk menyoroti kata-kata atau frasa yang penting, serta penggunaan nomor atau huruf untuk menyusun hierarki persyaratan. Selain itu, ada juga standar tertentu yang dapat diikuti, seperti IEEE 830 yang menetapkan format dan struktur umum untuk SRS.    

1.4 Audiens yang Dituju dan Saran Bacaan

Saran membaca dokumen ini ditujukan untuk beberapa jenis pembaca yang mungkin memiliki peran yang berbeda dalam proyek pengembangan perangkat lunak, termasuk :

1.	Pengembang : orang yang bertanggung jawab untuk merancang, mengembangkan, dan mengimplementasikan perangkat lunak. Mereka akan membutuhkan informasi detail tentang persyaratan fungsional dan nonfungsional, antarmuka, dan ketergantungan yang diperlukan oleh perangkat lunak.
   
2. Manajer Proyek : orang yang bertanggung jawab untuk merencanakan, mengarahkan, dan mengawasi pengembangan perangkat lunak. Mereka akan membutuhkan informasi tentang jadwal, sumber daya, tanggung jawab, risiko, dan kendala proyek.
   
3.	Pengguna : orang yang akan menggunakan perangkat lunak. Mereka akan membutuhkan informasi tentang fitur dan fungsi yang tersedia dalam perangkat lunak, serta persyaratan yang harus dipenuhi untuk menggunakannya.
   
4.	Penguji : orang yang bertanggung jawab untuk menguji perangkat lunak untuk memastikan bahwa perangkat lunak memenuhi persyaratan. Mereka akan membutuhkan informasi tentang persyaratan fungsional dan nonfungsional, dan bagaimana perangkat lunak harus beroperasi.
   
5.	Penulis Dokumentasi: orang yang bertanggung jawab untuk menulis dokumen-dokumen yang menjelaskan bagaimana cara menggunakan atau memelihara perangkat lunak. Mereka akan membutuhkan informasi tentang fitur dan fungsi perangkat lunak, serta bagaimana menggunakannya.

1.5 Cakupan Produk

   Dokumen ini menjelaskan tentang perangkat lunak website GlamorousGems. Tujuan dari perangkat lunak ini adalah untuk memfasilitasi operasi dari sebuah toko barang bekas atau yang sering disebut toko "GlamorousGems". Website ini dirancang untuk memungkinkan pengguna untuk melakukan manajemen inventaris, pelacakan penjualan, pengaturan harga, dan pelaporan secara efektif. Website GlamorousGems diharapkan dapat memberikan manfaat bagi pengguna, terutama bagi pemilik toko thrift shop. Dengan website ini, pemilik toko dapat mengelola inventaris dan melacak penjualan dengan lebih mudah dan akurat. Selain itu, webiste ini juga dapat membantu pemilik toko dalam mengambil keputusan bisnis yang lebih baik berdasarkan data dan informasi yang akurat dan terkini. Perangkat lunak ini dirancang untuk mendukung tujuan perusahaan atau strategi bisnis dalam meningkatkan efisiensi operasional dan pengambilan keputusan yang lebih baik berdasarkan data yang akurat dan terkini. Website ini juga dapat membantu toko GlamorousGems dalam meningkatkan pelayanan dan kepuasan pelanggan dengan menyediakan inventaris yang terorganisir dan harga yang terjangkau.

1.6 Referensi 

1)	https://docs.flutter.dev/
   
2)	https://dailysocial.id/post/rajaprelo-marketplace-jual-beli-barang-bekas/
   
3)	https://www.kompasiana.com/irfanfauzan/5f82d3a6d541df4a30452bc4/toko-kopi-aplikasi-jual-beli-barang-bekas-di-indonesia
   
4)	https://www.mamikos.com/blog/2019/12/09/mamikos-aplikasi-thrift-shop-khusus-untuk-barang-anak/
   
5)	https://karya.brin.go.id/id/eprint/12630/1/Jurnal_Fanny_IlmuBersama_2022.pdf
    
6)	 http://www.sisfotenika.stmikpontianak.ac.id/index.php/enter/article/view/856
     
7)	https://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/10246
    
8)	https://journal.untar.ac.id/index.php/JSA/article/view/24528


BAB 2

   Deskripsi Keseluruhan

   2.1 Perspektif Produk

   Produk yang dijelaskan dalam SRS ini adalah webiste GlamorousGems, yang merupakan produk mandiri baru. Website ini bertujuan untuk menyediakan platform bagi pengguna untuk menjual dan membeli barang-barang bekas secara online.

   2.2 Fungsi Produk

   - Dirancang khusus untuk membantu pengelolaan dan operasional GlamorousGems secara online.
  
   - membantu kami dalam melacak inventaris GlamorousGems yang tersedia. Ini mencakup melihat stok barang, memperbarui jumlah barang, dan mengatur kategori produk.
  
   - Website GlamorousGems memungkinkan pengguna untuk mendaftarkan produk bekas yang ingin dijual. Pengguna dapat memasukkan informasi seperti nama produk, deskripsi, kondisi barang, harga, dan gambar produk.

  2.3 Kelas Pengguna dan Karakteristik

  Berdasarkan tujuan dan fungsi utama dari produk website GlamorousGems dan aplikasi, beberapa kelas pengguna yang diantisipasi akan menggunakan produk ini meliputi :

   - Admin : Kelas pengguna ini akan memiliki hak akses penuh ke sistem dan bertanggung jawab untuk mengelola pengguna, produk, transaksi, dan laporan. Admin harus memiliki keahlian teknis yang tinggi dalam mengelola website, termasuk pengaturan dan konfigurasi server.
  
   - Penjual : Kelas pengguna ini dapat memposting barang dagangan mereka di website dan mengelola stok dan harga produk. Mereka dapat mengakses laporan penjualan untuk menganalisis kinerja toko mereka. Penjual harus memiliki keahlian teknis yang cukup untuk menggunakan website, tetapi tidak harus memiliki pengetahuan tentang pengaturan server.
  
   - Pembeli : Kelas pengguna ini dapat menjelajahi dan membeli produk yang ditawarkan oleh penjual. Mereka harus mendaftar ke website dan dapat melakukan transaksi melalui aplikasi. Pembeli tidak harus memiliki keahlian teknis tertentu untuk menggunakan webiste.

   - Tamu : Kelas pengguna ini adalah pengunjung aplikasi yang belum mendaftar sebagai pengguna. Mereka dapat menjelajahi dan melihat produk yang ditawarkan oleh penjual, tetapi tidak dapat melakukan transaksi atau mengakses fitur lainnya di aplikasi.

Kelas pengguna yang paling penting untuk dipenuhi adalah admin dan penjual, karena mereka bertanggung jawab untuk mengelola dan menjalankan website. Pembeli dan tamu juga penting, tetapi persyaratan mereka lebih sederhana dan lebih mudah dipenuhi.    

2.4 Lingkup Operasi 

   - Lingkup operasi webiste GlamorousGems :

     1.	Pendaftaran dan pengelolaan produk bekas yang ingin dijual.
        
     2.	Penjualan produk bekas kepada pelanggan.
        
     3.	Pembayaran dan transaksi melalui aplikasi.
        
     4.	Manajemen inventaris barang bekas.
        
     5.	Pelacakan pesanan dan pengiriman produk kepada pelanggan.
         
     6.	Pengelolaan data pelanggan dan riwayat pembelian.
         
     7.	Pelaporan dan analisis penjualan.

   - Lingkup operasi manajemen website GlamorousGems :

     1.	Manajemen proyek, termasuk pengaturan tugas, jadwal, dan pengalokasian sumber daya.
     	
     2.	Manajemen tugas dan jadwal individu atau tim.
        
     3.	Manajemen sumber daya, seperti manusia, keuangan, dan peralatan.
        
     4.	Manajemen kontak dan informasi pelanggan, partner bisnis, dan rekan kerja.
        
     5.	Pelaporan dan analisis kinerja organisasi.
         
     6.	Manajemen keuangan dan penggajian.
         
     7.	Pelacakan inventaris dan pengelolaan persediaan.

2.5 Kendala Desain dan Implementasi

Beberapa hal yang membatasi pilihan yang tersedia untuk para pengembang dalam pengembangan perangkat lunak termasuk :

   - Kebijakan perusahaan atau regulasi : Perusahaan dapat memiliki kebijakan atau aturan tertentu yang harus diikuti oleh pengembang dalam pengembangan perangkat lunak. Selain itu, adanya regulasi pemerintah dapat membatasi pilihan pengembang dalam pengembangan perangkat lunak.

   - Keterbatasan perangkat keras : Persyaratan waktu dan memori pada perangkat keras dapat membatasi pilihan pengembang dalam pengembangan perangkat lunak. Misalnya, jika perangkat keras yang tersedia hanya memiliki kapasitas memori terbatas, pengembang harus mempertimbangkan ukuran dan kompleksitas program agar sesuai dengan kapasitas perangkat keras.

   - Antarmuka ke aplikasi lain : Jika perangkat lunak harus berinteraksi dengan aplikasi lain, maka pengembang harus mempertimbangkan antarmuka aplikasi tersebut. Pengembang harus memastikan bahwa perangkat lunak dapat berfungsi dengan baik dengan aplikasi lain.

   - Teknologi khusus, alat, dan database : Jika organisasi pelanggan menggunakan teknologi khusus, alat, atau database tertentu, pengembang harus mempertimbangkan teknologi tersebut agar perangkat lunak dapat berfungsi dengan baik.

   - Operasi paralel : Jika perangkat lunak akan beroperasi secara paralel, pengembang harus mempertimbangkan teknik pemrograman paralel dan memastikan bahwa perangkat lunak dapat beroperasi dengan baik di lingkungan tersebut.

   - Persyaratan Bahasa : Jika pengguna dari berbagai negara akan menggunakan perangkat lunak, pengembang harus mempertimbangkan persyaratan bahasa dan memastikan bahwa perangkat lunak dapat berfungsi dengan baik di berbagai bahasa.

 - Pertimbangan keamanan : Pengembang harus mempertimbangkan masalah keamanan dalam pengembangan perangkat lunak. Perangkat lunak harus dapat menjaga kerahasiaan, integritas, dan ketersediaan data.

   - Konvensi desain atau standar pemrograman : Jika organisasi pelanggan memiliki konvensi desain atau standar pemrograman tertentu, pengembang harus mengikuti standar tersebut agar perangkat lunak sesuai dengan kebutuhan organisasi pelanggan.   

2.6 Dokumentasi Pengguna

Dalam SRS ini, akan disampaikan beberapa komponen dokumentasi pengguna yang akan disertakan bersama perangkat lunak, yaitu :

   - Panduan Pengguna	: dokumen ini akan memberikan petunjuk yang jelas tentang cara menggunakan perangkat lunak, mulai dari instalasi hingga penggunaan fitur-fitur utama.

   - Bantuan Online	: dokumen ini akan disediakan dalam bentuk online dan akan memberikan panduan lengkap tentang cara menggunakan website, fitur-fiturnya, serta solusi untuk masalah yang mungkin timbul saat penggunaan.

   - Tutorial		: dokumen ini akan memberikan panduan step-by-step tentang cara menggunakan fitur-fitur kunci dalam perangkat lunak.

2.7 Asumsi dan Ketergantungan

- Komponen pihak ketiga atau komersial	: Penggunaan komponen pihak ketiga atau komersial dalam pengembangan perangkat lunak dapat mempengaruhi persyaratan yang tercantum dalam SRS, terutama jika ada pembatasan lisensi atau fitur-fitur yang tersedia dalam komponen tersebut.
  
- Lingkungan pengembangan atau operasi	: Lingkungan pengembangan atau operasi yang berbeda dapat mempengaruhi persyaratan yang tercantum dalam SRS, seperti persyaratan kinerja dan keamanan. Misalnya, jika lingkungan operasi yang diinginkan adalah lingkungan yang sangat terdistribusi atau berada di lingkungan cloud, maka persyaratan kinerja dan keamanan harus diperhitungkan dengan cermat.
  
- Kendala : Kendala seperti anggaran dan waktu dapat mempengaruhi persyaratan yang tercantum dalam SRS. Jika anggaran atau waktu terbatas, maka beberapa persyaratan mungkin harus dikurangi atau dihilangkan.
  
- Faktor eksternal : Faktor eksternal seperti komponen perangkat lunak yang digunakan kembali dari proyek lain dapat mempengaruhi persyaratan dalam SRS. Jika komponen tersebut tidak tersedia atau tidak sesuai dengan kebutuhan proyek saat ini, maka persyaratan mungkin harus diubah.

BAB 3 

Persyaratan Antarmuka External

3.1 Antarmuka Pengguna

Antarmuka pengguna merupakan elemen penting dalam sebuah perangkat lunak karena merupakan tempat interaksi antara pengguna dan sistem. Beberapa karakteristik logis dari antarmuka pengguna yang perlu diperhatikan dalam SRS adalah sebagai berikut :

   - Tampilan	: antarmuka pengguna harus memiliki tampilan yang mudah dipahami dan menarik. Tampilan tersebut dapat berupa gambar layar sampel, yang menunjukkan bagaimana tampilan antarmuka pengguna akan terlihat.

   - GUI	: antarmuka pengguna harus mengikuti standar GUI (Graphical User Interface) atau panduan gaya keluarga produk yang telah ditentukan. Hal ini penting agar antarmuka pengguna mudah dipahami oleh pengguna.

   - Tata letak	: tata letak antarmuka pengguna harus dirancang sedemikian rupa sehingga mudah dipahami dan digunakan oleh pengguna. Batasan tata letak layar, tombol dan fungsi standar, serta pintasan keyboard yang akan muncul di setiap layar juga perlu ditentukan.

   - Pesan kesalahan : standar tampilan pesan kesalahan yang jelas dan mudah dimengerti oleh pengguna juga perlu ditentukan dalam SRS.

Beberapa komponen perangkat lunak yang memerlukan antarmuka pengguna adalah menu, tombol, dialog, dan tampilan data. Desain antarmuka pengguna yang lebih detail harus didokumentasikan dalam spesifikasi antarmuka pengguna yang terpisah. Spesifikasi tersebut harus mencakup deskripsi tentang semua elemen antarmuka pengguna, termasuk tata letak, tombol, menu, dan pintasan keyboard, serta bagaimana pengguna akan berinteraksi dengan mereka.

3.2 Antarmuka Perangkat Keras

   Karakteristik logis dan fisik dari antarmuka antara perangkat lunak dan perangkat keras sistem meliputi beberapa faktor. Secara logis, antarmuka harus didesain untuk dapat mendukung jenis perangkat keras tertentu yang digunakan dalam sistem. Selain itu, perangkat lunak harus mampu berinteraksi dengan perangkat keras, mengirim dan menerima data dari perangkat keras tersebut. Interaksi kontrol antara perangkat lunak dan perangkat keras harus didefinisikan secara jelas dan harus memperhitungkan protokol komunikasi yang digunakan oleh perangkat keras. Secara fisik, antarmuka perangkat lunak dan perangkat keras harus mempertimbangkan faktor-faktor seperti jenis konektor, pengaturan pin, dan kemampuan daya listrik. Komponen perangkat lunak yang memerlukan antarmuka perangkat keras mungkin termasuk driver perangkat keras atau layer middleware yang menghubungkan antara aplikasi dengan perangkat keras. Rincian desain antarmuka perangkat keras harus didokumentasikan dalam spesifikasi antarmuka perangkat keras yang terpisah.

   3.3 Antarmuka Perangkat Lunak

   Produk perangkat lunak yang akan dikembangkan mungkin akan tergantung pada beberapa komponen perangkat lunak khusus lainnya seperti database, sistem operasi, alat, perpustakaan, dan komponen terintegrasi komersial. Komponen perangkat lunak lainnya yang terkait dengan produk dapat mencakup :

   - Database : Produk dapat bergantung pada database tertentu untuk penyimpanan dan pengambilan data. Versi dan spesifikasi database harus ditentukan dalam SRS. Pesan atau data yang masuk ke dalam sistem mungkin termasuk permintaan untuk mengambil data dari database atau untuk menyimpan data ke dalam database.
   
   - Sistem operasi : Produk dapat bergantung pada sistem operasi tertentu untuk menjalankan aplikasi. Versi dan spesifikasi sistem operasi harus ditentukan dalam SRS. Pesan atau data yang masuk ke dalam sistem mungkin termasuk instruksi dari sistem operasi atau notifikasi yang diterima dari sistem operasi.

   - Komponen terintegrasi komersial : Produk dapat mengintegrasikan komponen perangkat lunak komersial lainnya. Versi dan spesifikasi komponen tersebut harus ditentukan dalam SRS. Pesan atau data yang masuk ke dalam sistem mungkin termasuk permintaan dari komponen terintegrasi atau notifikasi dari komponen terintegrasi yang digunakan.

   Data atau pesan yang masuk ke dalam sistem dapat mencakup permintaan untuk menjalankan fungsi atau proses tertentu, permintaan untuk mengambil atau menyimpan data, atau notifikasi tentang peristiwa tertentu yang terjadi dalam sistem. Tujuan dari data atau pesan tersebut adalah untuk memungkinkan interaksi antara komponen perangkat lunak yang berbeda dan memfasilitasi jalannya website.

   Layanan yang dibutuhkan mungkin mencakup layanan jaringan, layanan pengamanan, layanan pemantauan kinerja, dan layanan lainnya. Komunikasi antara komponen perangkat lunak dapat dilakukan melalui protokol antarmuka pemrograman website tertentu, seperti REST atau SOAP.

   Data yang akan dibagikan di seluruh komponen perangkat lunak harus ditentukan dalam SRS. Mekanisme berbagi data harus diimplementasikan dengan cara yang sesuai dan dapat diandalkan, seperti penggunaan panggilan fungsi atau variabel global. Batasan implementasi harus dijelaskan secara terperinci dalam spesifikasi antarmuka pengguna yang terpisah.

3.4 Antarmuka Komunikasi

1)	Chat Langsung antara Penjual dan Pembeli :
   
-	Pengguna dapat mengirim pesan langsung ke penjual untuk bertanya tentang produk, bernegosiasi harga, atau mengatur detail transaksi.
  
-	Antarmuka chat menyediakan fitur pengiriman teks, gambar, dan lampiran lainnya untuk memfasilitasi komunikasi yang lebih baik.

2)	Notifikasi Transaksi :
   
-	Pengguna akan menerima notifikasi langsung tentang status transaksi mereka, seperti konfirmasi pesanan, pembaruan pengiriman, atau penawaran khusus.
  
-	Notifikasi dapat dikirim melalui pesan teks, notifikasi push, atau email.

3)	Ulasan dan Penilaian Produk :
   
-	Pengguna dapat memberikan ulasan dan penilaian terhadap produk yang telah mereka beli.
  
-	Antarmuka ini memungkinkan pengguna untuk menulis ulasan, memberikan peringkat, dan melihat ulasan pengguna lainnya.

4)	Formulir Kontak Dukungan Pelanggan :
   
-	Pengguna dapat mengisi formulir kontak untuk mengajukan pertanyaan, melaporkan masalah, atau mendapatkan bantuan dari tim dukungan pelanggan.
  
-	Formulir ini biasanya berisi bidang untuk nama, alamat email, subjek, dan pesan.

BAB 4

FITUR SISTEM DAN KERANGKA DESAIN FITUR

   Menjelaskan mengenai proses yang akan dilakukan oleh sistem, Sistem dalam website 
GlamorousGems ini mempermudah penjual dan pembeli dalam bentransaksi jual-beli 
thrift shop.

4.1 Halaman Login

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/79bf13b1-7df3-41aa-a95d-ded62d7c15e1)

4.2 Halaman Utama

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/55f463a3-f8a6-417e-89e1-c751f95d4e1c)

4.3 Halaman Tentang Kami / About us

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/5adfe6ce-4610-47ac-a26e-0d59eac6381a)

4.4 Halaman Produk Kami

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/f8b515e8-4947-4157-b609-ed610c07d547)

BAB 5

PERSYARATAN NONFUNGSIONAL LAINNYA

5.1  Persyaratan Kinerja

Persyaratan keselamatan sangat penting untuk memastikan produk aman 
digunakan oleh pengguna. Berikut adalah beberapa contoh persyaratan 
keselamatan yang mungkin diperlukan:

   - Produk harus memenuhi standar keselamatan yang relevan, seperti standar 
keselamatan elektronik, keamanan produk, dan persyaratan lingkungan.

   - Produk harus dirancang sedemikian rupa sehingga tidak ada risiko kebakaran 
atau ledakan ketika digunakan dengan benar. Produk juga harus dilengkapi 
dengan tindakan pengamanan seperti sensor panas dan alat pemadam api 
otomatis.

   - Produk harus menghindari potensi kecelakaan saat digunakan, seperti cedera 
fisik atau trauma pada pengguna. Produk harus mempertimbangkan faktor 
ergonomic, seperti tinggi dan lebar kursi, untuk memastikan kenyamanan dan 
keselamatan pengguna.

   - Produk harus memiliki label peringatan dan petunjuk penggunaan yang jelas 
dan mudah dipahami oleh pengguna. Label harus mencakup informasi 
tentang bahaya dan peringatan penting yang berkaitan dengan penggunaan 
produk.

   - Produk harus memiliki fitur keamanan yang membatasi akses pengguna yang 
tidak sah. Ini dapat mencakup perlindungan password atau perangkat lunak 
enkripsi yang terenkripsi untuk melindungi informasi pribadi dan data 
penting.

   - Produk harus memiliki fitur cadangan atau pemulihan darurat yang 
memungkinkan pengguna untuk mengembalikan data dan informasi setelah 
kehilangan atau kegagalan sistem.

   - Produk harus dirancang untuk memenuhi persyaratan keselamatan yang 
diperlukan oleh badan pengatur atau sertifikasi. Ini mungkin mencakup 
persyaratan UL atau sertifikasi CE

Dalam mengembangkan produk, sangat penting untuk mempertimbangkan 
keamanan dan keselamatan pengguna sebagai prioritas utama. Tim pengembang 
harus berkolaborasi dengan ahli keselamatan dan badan pengatur untuk 
memastikan produk aman dan memenuhi standar keselamatan yang relevan.

5.2  Persyaratan Keselamatan

Berikut adalah beberapa persyaratan keamanan dan privasi yang dapat terkait 
dengan penggunaan produk:

   - Persyaratan autentikasi pengguna: Produk harus menyediakan mekanisme 
autentikasi pengguna yang aman dan dapat diandalkan untuk mengakses fitur 
atau layanan yang sensitif. Mekanisme autentikasi harus memenuhi standar 
keamanan dan privasi yang berlaku.

   - Persyaratan otorisasi pengguna: Produk harus memiliki mekanisme otorisasi 
yang tepat untuk mengontrol akses pengguna ke fitur atau layanan yang 
berbeda dalam sistem. Akses pengguna harus diatur berdasarkan peran, 
tanggung jawab, atau kebutuhan bisnis.

   - Persyaratan enkripsi data: Produk harus dapat mengenkripsi data yang 
sensitif pada saat penyimpanan atau pengiriman data melalui jaringan untuk 
melindungi kerahasiaan dan integritas data.

   - Persyaratan proteksi data: Produk harus dapat melindungi data sensitif dari 
kehilangan, penggunaan yang tidak sah, atau akses tidak sah. Data sensitif 
harus diidentifikasi dan dikelola secara khusus untuk meminimalkan risiko 
pelanggaran keamanan data.

   - Persyaratan pelaporan keamanan: Produk harus memiliki mekanisme 
pelaporan yang tepat untuk melaporkan pelanggaran keamanan atau aktivitas 
mencurigakan yang terkait dengan produk. Pelaporan harus dilakukan sesuai 
dengan standar industri atau peraturan yang berlaku.

   - Persyaratan pemantauan keamanan: Produk harus memiliki kemampuan 
untuk memantau aktivitas pengguna dan sistem secara real-time untuk 
mendeteksi dan merespons ancaman keamanan. Pemantauan harus meliputi 
audit log, alarm keamanan, dan tindakan pencegahan atau mitigasi risiko.

   - Persyaratan privasi data: Produk harus mematuhi standar privasi yang 
berlaku dan memproteksi data pribadi pengguna dengan tepat. Data pribadi 
harus diidentifikasi dan dikelola secara khusus untuk meminimalkan risiko 
pelanggaran privasi data.

   - Persyaratan sertifikasi keamanan atau privasi: Produk harus memenuhi 
sertifikasi keamanan atau privasi yang berlaku untuk industri atau wilayah 
tertentu, seperti PCI DSS, HIPAA, atau GDPR. Produk harus memenuhi 
persyaratan sertifikasi untuk memastikan keamanan dan privasi yang tepat 
bagi pengguna produk.

5.3 Persyaratan Keamanan

5.4 Atribut Kualitas Perangkat Lunak

5.5 Aturan Bisnis

BAB 6

Persyaratan Lainnya

6.1 Lampiran A : Glosarium


6.2 Lampiran B : Model Analisis


6.3 Lampiran C : Penjelasan Source Code

4. Penjelasan Source Code Html

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/c0bb84dd-ab3a-4ad4-8c74-5bdb358c0616)

   - <meta charset="UTF-8">: Mengatur karakter encoding menjadi UTF-8 untuk mendukung banyak karakter dan simbol.
   
   - <meta http-equiv="X-UA-Compatible" content="IE=edge">: Mengontrol kompatibilitas dengan Internet Explorer, memastikan penggunaan versi terbaru dari IE.
   
   - <meta name="viewport" content="width=device-width, initial-scale=1.0">: Mengatur tampilan dan skala halaman untuk perangkat bergerak, memastikan tampilan yang responsif.
   
   - <title>GlamourousGems</title>: Menentukan judul halaman web yang akan ditampilkan di bilah judul browser dan hasil pencarian mesin telusur.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/0fcf6802-2248-4ba4-8f14-cd254c876c3a)

   - Kode ini digunakan untuk menghubungkan jenis huruf (font) dari Google Fonts ke halaman web. Langkah-langkahnya meliputi prapenghubung (preconnect) ke server Google Fonts dan mengimpor jenis huruf Poppins dengan berkas CSS yang diperlukan untuk tampilan font tersebut.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/b84a4d71-71c4-4c7d-aff9-ad3bdb0a6274)

   - Kode ini mengimpor Feather Icons ke halaman web dengan menghubungkan ke skrip di alamat "https://unpkg.com/feather-icons."

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/d9cdfe30-61b4-4fbe-b594-9a40b5269520)

   - Kode ini mengimpor berkas CSS yang disebut "style.css" ke halaman web Anda, sehingga Anda dapat mengatur tampilan dan gaya halaman menggunakan CSS.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/0c15df1e-591c-475e-a42d-14240e934852)
   - <a href="#" class="navbar-logo">Glamourous<span>Gems</span></a>: Ini adalah logo situs yang terdiri dari teks "GlamourousGems" dengan dua kata yang diberi kelas "navbar-logo."
     
   - <div class="navbar-nav">: Ini adalah daftar tautan menu navigasi yang mencakup tautan ke bagian-bagian halaman seperti "Home," "Tentang Kami," "Produk," dan "Kontak." Ini diberi kelas "navbar-nav" untuk mengatur tampilan menu.
   
   - <div class="navbar-extra">: Ini adalah elemen tambahan di navbar yang berisi tautan untuk tindakan seperti pencarian ("search"), keranjang belanja ("shopping cart"), dan menu hamburger ("hamburger menu"). Masing-masing tautan ini memiliki ikon dari Feather Icons yang disediakan.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/380a4ce8-f775-495a-993c-b1bc50774374)

   - Kode ini adalah awal dan akhir dari formulir pencarian (search form) di halaman web. Formulir ini memiliki elemen input tipe "search" yang memungkinkan pengguna memasukkan teks pencarian, dan ada juga label yang berisi ikon pencarian.
     
   - Formulir ini diberi kelas "search-form" dan memungkinkan pengguna mencari informasi dengan memasukkan teks ke dalam kotak pencarian.

     ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/aafceaf6-5ffc-4582-bae5-c68f47ae9041)

   - Setiap elemen <div class="cart-item"> merepresentasikan satu item dalam keranjang belanja. Masing-masing item memiliki gambar produk, informasi produk yang terdiri dari nama ("Product 1," "Product 2," dan "Product 3") dan harga dalam mata uang Rupiah, serta ikon "hapus" (<i data-feather="trash-2" class="remove-item"></i>) untuk menghapus item dari keranjang.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/bc13bc35-d197-4ab2-b88b-7cbb586662d0)

   - Kode ini menutup elemen navigasi (navbar) dan menandai awal dan akhir dari bagian "Hero Section" di halaman web. Bagian "Hero Section" ini berisi elemen berjudul "Temukan Produk Terbaik" dengan deskripsi tambahan "Hanya untukmu!" yang menyoroti produk-produk unggulan dan menyambut pengguna ketika mereka masuk ke situs web. Bagian ini memiliki latar belakang atau "mask-container" yang mendukung elemen judul dan deskripsi tersebut.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/a57b4d23-8695-4db0-9e6d-c989e647c476)

   - Judul "Tentang Kami" yang memberi tahu pengguna bahwa ini adalah bagian yang berfokus pada informasi tentang situs.
     
   - Elemen gambar ("about-img") yang menampilkan gambar yang menggambarkan atau mendukung isi tentang halaman ini.
     
   - Elemen konten ("content") yang berisi informasi tentang alasan memilih situs "GLAMOUROUSGEMS." Informasi ini menjelaskan bahwa situs ini adalah tujuan utama untuk berburu barang-barang unik, fashion berkualitas, dan barang-barang vintage yang terjangkau. Selain itu, situs ini mengabdikan diri untuk menjadikan pengalaman berbelanja yang menyenangkan dan berkelanjutan.
  
   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/f416c4c5-4779-4e21-be60-15ac43d11aa7)

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/66fec68e-8dda-4b5f-a0f2-ff4f69e1f045)

   - Judul "Produk Unggulan Kami" yang menunjukkan bahwa ini adalah bagian yang menampilkan produk terbaik.
     
   - Deskripsi singkat yang menjelaskan bahwa produk-produk ini banyak dibeli dan berkualitas.
     
   - Elemen-elemen "product-card" yang mewakili produk-produk. Setiap "product-card" mencakup gambar produk, ikon "shopping cart" untuk menambahkan produk ke keranjang belanja, informasi produk seperti nama, peringkat bintang, dan harga dalam mata uang Rupiah.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/accdd8b8-0a54-457f-b224-41deda78b5e7)

   - Judul "Kontak Kami" yang menunjukkan bahwa pengguna dapat menghubungi situs web.
     
   - Deskripsi singkat yang mengundang pengguna untuk memberikan saran atau pertanyaan.
     
   - Sebuah peta (yang mungkin perlu dikonfigurasi dengan sumber peta yang valid) yang menunjukkan lokasi fisik atau wilayah operasi situs.
     
   - Formulir kontak yang memungkinkan pengguna memasukkan nama, email, nomor telepon, dan pesan.
     
   - Tombol "kirim pesan" untuk mengirim pesan kepada situs.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/1b2ca82c-ec00-4fba-89d5-062d7cea9834)

   - Tautan ke media sosial seperti Instagram, Twitter, dan Facebook yang memungkinkan pengguna mengunjungi profil atau halaman sosial situs.
     
   - Tautan menu yang mengarah ke bagian-bagian utama situs seperti "Home," "Tentang Kami," dan "Kontak."
     
   - Informasi kredit yang menyatakan bahwa situs dibuat oleh "GlamourousGems" dan mencantumkan hak cipta tahun 2023.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/81278227-b8e3-4e53-8e79-1515fcec6b1a)

   - Kode ini adalah bagian dari penggunaan Feather Icons di halaman web. Ini adalah skrip JavaScript yang menggantikan ikon-ikon dalam halaman dengan ikon-ikon dari Feather Icons, yang memungkinkan Anda menggunakan ikon-ikon yang tersedia dalam font icon di situs Anda. Ikon-ikon ini dapat digunakan untuk menyempurnakan tampilan dan fungsionalitas situs web.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/6ba373e3-ac58-4caf-9b1a-872859a6c8de)

   - Kode ini adalah cara untuk menghubungkan dan memuat berkas JavaScript eksternal dengan nama "script.js" ke halaman web. Berkas JavaScript ini kemungkinan berisi skrip-skrip yang mengendalikan perilaku interaktif atau fungsionalitas khusus pada situs web. Berkas ini dimuat sebelum penutupan elemen <body> untuk memastikan bahwa skrip-skrip tersebut tersedia dan siap digunakan oleh halaman web.

5. Penjelasan Source Code JavaScript
   
   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/2db87563-a219-4a9a-a4a4-9f9462b60e63)

   -Toggle class active untuk hamburger menu adalah kode untuk mencari elemen dengan kelas .navbar-nav dan menyimpannya dalam variabel navbarNav.
   -navbarNav. Ini digunakan untuk menampilkan atau menyembunyikan menu navigasi (hamburger menu) dengan mengubah tampilan CSS.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/aa064de6-d34a-4d12-8ba3-cdd482e1429e)

   -Toggle class active untuk search form adalah kode untuk mencari elemen dengan kelas .search-form dan elemen dengan id search-box, kemudian menyimpannya dalam variabel searchForm dan searchBox.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/d989fb81-458b-491e-b03e-910f7806037f)

   -Mengubah atau "toggle" kelas active pada elemen searchForm untuk menampilkan atau menyembunyikan kotak pencarian.
   -Memberikan fokus kepada elemen searchBox (sehingga pengguna dapat langsung memasukkan teks ke dalamnya).
   -Menghentikan aksi bawaan dari elemen HTML dengan e.preventDefault() untuk mencegah peristiwa klik standar (misalnya, mengirimkan formulir).

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/8ff47fa9-d591-4593-b5a4-65d2389877f5)

   -Toggle class active untuk shopping cart adalah kode untuk mencari elemen dengan kelas .shopping-cart dan menyimpannya dalam variabel shoppingCart.
   -Mengubah atau "toggle" kelas active pada elemen shoppingCart untuk menampilkan atau menyembunyikan keranjang belanja.
   -Menghentikan aksi bawaan dari elemen HTML dengan e.preventDefault() untuk mencegah peristiwa klik standar (misalnya, mengikuti tautan).

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/9b7f6027-e96f-4c78-97b1-7f80fb639a31)

   -Klik di luar elemen adalah kode untuk mengatasi kasus ketika pengguna mengklik di luar elemen-elemen seperti hamburger menu, form pencarian, dan shopping cart. Ini dilakukan dengan mengecek apakah klik terjadi di luar elemen-elemen tersebut.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/d5b3a7aa-3478-4ae8-8325-b72f3d4d981e)

   -Modal Box adalah kode untuk berurusan dengan tampilan modal (pop-up window) saat pengguna mengklik elemen-elemen dengan kelas .item-detail-button.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/2cfcbcc0-d5ea-402c-92d0-e437e861ba92)

   -Klik tombol close modal adalah kode untuk menangani pengklikan tombol close (ikon close) di dalam modal.
   -Ketika tombol close (dengan kelas .close-icon) dalam modal diklik, kode ini menyembunyikan modal dengan mengatur properti display CSS-nya menjadi "none".

7. Penjelasan Source Code CSS 

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/eeba4cf1-b2c7-4b24-9499-ad4aee4bfc1d)

-“ :root “ Ini adalah pseudo-class CSS yang digunakan untuk mendefinisikan variabel CSS kustom (variabel kustom). Dalam kode ini, mendefinisikan dua variabel kustom: --primary yang memiliki nilai #e96767 (warna merah muda) dan --bg yang memiliki nilai #010101 (warna hitam).

-“ * “ Adalah selector universal yang memilih semua elemen di halaman. Dalam blok ini, digunakan untuk mengatur beberapa properti yang akan berlaku pada semua elemen, termasuk menghapus margin, padding, dan garis luar (outline), serta menghilangkan border dan text-decoration.

-“ html “ merupakan selector untuk elemen <html> dalam halaman HTML. Di sini, untuk mengatur  gulir halus (scroll-behavior: smooth) ketika pengguna menggulir halaman. Dan akan memberikan efek gulir yang lebih mulus ketika pengguna mengklik tautan dalam dokumen.

-“ body “ Adalah  selector untuk elemen <body> dalam halaman HTML. Di sini, untuk mengatur beberapa properti seperti font-family (menggunakan jenis huruf Poppins atau jenis huruf sans-serif), warna latar belakang (background-color), dan warna teks (color).

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/e627eb90-5a72-4d0c-9770-63d656a12c7f)

-“ .navbar “ Ini adalah selector untuk elemen dengan kelas "navbar". Dalam blok ini, digunakan mengatur beberapa properti yang berkaitan dengan tampilan navbar.

  ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/66bd72c2-b196-4a29-881e-013983a30552)
-“ .navbar .navbar-logo “ Adalah selector untuk elemen dengan kelas "navbar-logo" yang berada di dalam elemen navbar.
  
-“ .navbar .navbar-logo span ” Selector untuk elemen <span> yang berada di dalam elemen "navbar-logo”.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/ef10b247-dacc-478f-8ce8-74ee4cf619a9)

-“ .navbar .navbar-nav a “ Selector untuk tautan yang berada di dalam elemen dengan kelas "navbar-nav" dalam navbar.
  
-“ .navbar .navbar-nav a:hover “ Selector untuk tautan ketika kursor mouse berada di atasnya (hover).

-“ .navbar .navbar-nav a::after “ pseudo-element seperti ::after digunakan untuk menambahkan konten tambahan atau efek visual ke elemen.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/666a0b91-8f48-4c37-b4f1-fa7594398ebb)

-“ .navbar .navbar-extra a “ Selector untuk tautan yang berada dalam elemen dengan kelas "navbar-extra".

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/7c5b8497-74e4-457a-9e52-45fd9fa98150)

-“ #hamburger-menu “ Adalah selector untuk elemen dengan ID "hamburger-menu".
  
-“ display: none; “ Ini mengatur elemen dengan ID "hamburger-menu" menjadi tidak terlihat (display: none).
  
-“ .navbar .search-form “ Selector untuk elemen dengan kelas "search-form" dalam elemen navbar.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/e8983d49-3163-487d-9671-fe7424a4e5b4)

-“ .navbar .search-form.active “ Selector untuk elemen "search-form" yang memiliki kelas "active". Ketika elemen ini aktif, transformasi skala vertikalnya akan diubah menjadi 1 (normal), sehingga elemen ini akan terlihat.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/9af6b665-44e0-4cc6-a79e-2a8d3f8a0699)

-" .navbar .search-form label “ selector untuk elemen label yang berada dalam elemen "search-form".

-“ .shopping-cart “ selector untuk elemen dengan kelas "shopping-cart".
  
-“ position: absolute; “ Ini mengatur posisi elemen "shopping-cart" menjadi absolut, yang berarti elemen ini akan ditempatkan secara absolut terhadap elemen yang paling dekat yang memiliki posisi relatif, atau elemen akar (root) jika tidak ada elemen yang memiliki posisi relatif.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/8fa88941-828c-4f27-97ab-5049a43e70df)

-	“ .shopping-cart.active “ Selector untuk elemen "shopping-cart" yang memiliki kelas "active".

  ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/af37ea34-50d8-4300-8b4c-1b0209716b4c)
  
-	“ /* Hero Section */ “ adalah bagian dari kode CSS yang digunakan untuk memberikan penjelasan atau catatan tentang bagian kode di bawahnya. Ini hanya digunakan untuk dokumentasi dan membantu pengembang atau orang lain yang membaca kode untuk memahami bahwa bagian kode yang berikut ini adalah bagian yang berkaitan dengan "Hero Section."

  ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/0e1aa050-e916-4be1-9edc-d0f0c902b43b)

-“ .hero::after “ Ini adalah selector CSS yang digunakan untuk memilih pseudo-element "::after" yang terkait dengan elemen yang memiliki kelas "hero". Pseudo-element "::after" adalah elemen virtual yang dapat digunakan untuk menambahkan konten tambahan atau mengubah tampilan elemen utama setelah kontennya.

-“ .hero .mask-container “ selector ini hanya berlaku jika elemen dengan kelas "mask-container" tersebut berada dalam elemen dengan kelas "hero." Dengan kata lain, elemen yang akan dipilih harus menjadi anak atau elemen turunan dari elemen dengan kelas "hero."

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/d78d6703-95be-45c0-b041-9c30b0fa54a6)

-“ .hero .content “ Kode tersebut menunjukkan bahwa Anda ingin mengatur properti CSS atau tampilan untuk elemen-elemen yang memenuhi kriteria di atas, yaitu elemen-elemen dengan kelas "content" yang berada di dalam elemen dengan kelas "hero."

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/0b089945-96bc-490a-b7e5-71acc2f0f4af)

-“ /* About Section */ “  adalah bagian dalam sebuah halaman web yang digunakan untuk menjelaskan atau menggambarkan informasi tentang bisnis, produk, atau topik tertentu yang relevan dengan situs web tersebut.

-“ padding: 8rem 7% 1.4rem; “  adalah sebuah aturan CSS yang mengatur jarak antara elemen terkait dengan menggunakan properti padding. Properti padding digunakan untuk mengatur jarak atau ruang internal pada elemen HTML, seperti elemen div atau kontainer.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/01229f11-0174-4ad1-855d-830aacfa37d8)

-“ /* Menu Section */ “  adalah bagian dalam sebuah halaman web yang digunakan untuk menampilkan daftar menu atau pilihan yang tersedia kepada pengunjung. Ini dapat mencakup daftar makanan, produk, atau kategori lain yang relevan dengan situs web tersebut.  

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/356fc5e3-ab61-49cc-a862-3657acebbd9d)

-“ /* Products Section */ “ adalah bagian dalam sebuah halaman web yang digunakan untuk menampilkan produk atau layanan yang ditawarkan oleh bisnis atau situs web tertentu. Ini biasanya mencakup gambar, deskripsi produk, harga, dan tautan ke halaman detail produk atau halaman lain yang relevan.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/13f52c17-20d5-4d7c-a213-7aa6f6ccad85)

-“ /* Contact Section * “ Adalah bagian dalam sebuah halaman web yang biasanya digunakan untuk menampilkan informasi kontak, seperti alamat, nomor telepon, alamat email, peta lokasi, atau formulir kontak yang memungkinkan pengunjung untuk menghubungi pemilik situs web atau bisnis.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/5674b5d5-deee-4af9-b592-57f921627aae)

-“ /* Footer */ “ adalah bagian umum dalam desain halaman web yang biasanya terletak di bagian bawah halaman. Ini berisi informasi tambahan seperti tautan ke halaman lain, hak cipta, tautan media sosial, dan informasi kontak. Biasanya, footer adalah bagian yang merinci informasi penting dan memberikan pengguna akses ke sejumlah tautan penting terkait dengan situs web atau perusahaan.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/9360d88b-5129-4e38-9d24-d425112aad61)

-/* Modal Box */ dan /* Item Detail */  Dalam desain web, "Modal Box" adalah komponen yang sering digunakan untuk menampilkan konten tambahan, seperti gambar atau informasi detail, dalam sebuah jendela kecil yang muncul di atas halaman web saat pengguna mengklik atau melakukan tindakan tertentu. “Item Detail" dapat merujuk pada konten atau informasi detail tentang sebuah item tertentu, seperti produk dalam toko online atau posting dalam galeri.

-“ /* Modal Animation */ "  merujuk pada animasi atau efek visual yang digunakan saat "Modal Box" ditampilkan atau disembunyikan, seperti pergeseran, transparansi, perubahan ukuran, atau efek lain yang membuat tampilan modal box lebih menarik atau informatif bagi pengguna.

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/7d58ce84-3a66-4d2b-930f-43304af47b88)

-“ /* Media Queries */ “ Adalah teknik yang digunakan untuk mengatur tampilan halaman web berdasarkan karakteristik perangkat yang digunakan oleh pengguna, seperti lebar layar, tinggi layar, orientasi layar (misalnya, potret atau lanskap), dan sebagainya.
