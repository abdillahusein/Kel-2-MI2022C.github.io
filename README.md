# Kel-2-MI2022C.github.io
LAPORAN TUGAS PEMROGRAMAN WEB SRS GlamourousGem

Disusun oleh:
1. Adinda Nasywa Salsabila (22091397082)   2022C
2. M. Husein Abdillah      (22091397091)   2022C
3. Hkang Yochanan Tdamu    (22091397107)   2022C

Program Studi D4 Manajemen Informatika

Fakultas Vokasi

Universitas Negeri Surabaya

2023

1. Tujuan

Platform website e-commerce yang menawarkan barang bekas berkualitas kepada audiens yang lebih luas, dengan
harga yang terjangkau. Tujuan dari website ini untuk menawarkan barang bekas yang berkualitas kepada audiens 
yang lebih luas. Target pasarnya yaitu individu yang mencari barang-barang vintage, unik, atau berharga dengan 
harga terjangkau.

2. Lampiran

   A. Flowchart Website Glamourous Gems

   ![Flowchart Diagram](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/83c1631c-5dfd-4ea2-9057-f348ac19f19e)


   B. Use Case Glamourous Gems

   ![Use case (1)](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/50589000-ab40-464e-be29-12460ad434be)

3. Penjelasan Source Code Html

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/c0bb84dd-ab3a-4ad4-8c74-5bdb358c0616)

   - <meta charset="UTF-8">: Mengatur karakter encoding menjadi UTF-8 untuk mendukung banyak karakter dan simbol.
   
   - <meta http-equiv="X-UA-Compatible" content="IE=edge">: Mengontrol kompatibilitas dengan Internet Explorer, memastikan penggunaan versi terbaru dari IE.
   
   - <meta name="viewport" content="width=device-width, initial-scale=1.0">: Mengatur tampilan dan skala halaman untuk perangkat bergerak, memastikan tampilan yang responsif.
   
   - <title>GlamourousGems</title>: Menentukan judul halaman web yang akan ditampilkan di bilah judul browser dan hasil pencarian mesin telusur.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/0fcf6802-2248-4ba4-8f14-cd254c876c3a)

   - Kode ini digunakan untuk menghubungkan jenis huruf (font) dari Google Fonts ke halaman web. Langkah-langkahnya meliputi prapenghubung (preconnect) ke server Google Fonts dan mengimpor jenis huruf Poppins dengan berkas CSS yang diperlukan untuk tampilan font tersebut.

   ![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124490604/b84a4d71-71c4-4c7d-aff9-ad3bdb0a6274)

   - Kode ini mengimpor Feather Icons ke halaman web dengan menghubungkan ke skrip di alamat "https://unpkg.com/feather-icons."

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

6. Penjelasan Source Code CSS 

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








![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/d78d6703-95be-45c0-b041-9c30b0fa54a6)

-“ .hero .content “ Kode tersebut menunjukkan bahwa Anda ingin mengatur properti CSS atau tampilan untuk elemen-elemen yang memenuhi kriteria di atas, yaitu elemen-elemen dengan kelas "content" yang berada di dalam elemen dengan kelas "hero."

![image](https://github.com/abdillahusein/Kel-Pemweb2-MI2022C.github.io/assets/124483393/0b089945-96bc-490a-b7e5-71acc2f0f4af)

-“ /* About Section */ “  adalah bagian dalam sebuah halaman web yang digunakan untuk menjelaskan atau menggambarkan informasi tentang bisnis, produk, atau topik tertentu yang relevan dengan situs web tersebut.




   
