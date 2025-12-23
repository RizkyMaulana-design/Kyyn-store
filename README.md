
---

# Kyyn Store: Luxury E-Commerce Digital Transformation 🛍️

**Kyyn Store** adalah platform *e-commerce* premium yang dirancang untuk mendigitalisasi operasional bisnis retail UMKM gaya hidup "Luxury Store" di Bekasi. Sistem ini mentransformasi proses transaksi konvensional menjadi ekosistem digital yang efisien, terstruktur, dan transparan.

## 📖 Ringkasan Proyek

Pengembangan sistem ini menerapkan metodologi pengembangan perangkat lunak **Multimedia Luther**, yang mencakup fase *Concept, Design, Material Collecting, Assembly,* dan *Testing*. Fokus utama proyek ini adalah integrasi manajemen inventaris dengan pengalaman belanja pengguna yang eksklusif.

## 🚀 Fitur Unggulan

* 
**Sistem Autentikasi**: Manajemen akses terpisah untuk Pengguna (Customer) dan Admin dengan validasi kredensial yang aman.


* 
**Katalog Produk Premium**: Tampilan etalase digital menggunakan sistem *grid* yang menyajikan informasi harga, gambar berkualitas, dan detail produk.


* 
**Manajemen Stok Real-time**: Monitoring ketersediaan barang secara otomatis di halaman detail produk.


* 
**Workflow Checkout Terintegrasi**: Proses pemesanan yang mencakup manajemen keranjang belanja, kalkulasi subtotal, dan penggunaan kupon voucher diskon.


* 
**Invoice Digital Otomatis**: Generasi bukti pembelian sah dalam format PDF dengan status "LUNAS".


* 
**Panel Administratif**: Kontrol penuh bagi Admin untuk mengelola data produk, stok barang, pemantauan transaksi, dan pengelolaan data pengguna.



## 🏗️ Arsitektur Perancangan (UML)

Sistem divalidasi menggunakan standar **Unified Modeling Language (UML)** untuk menjamin konsistensi antara desain dan logika bisnis:

* 
**Use Case Diagram**: Memetakan interaksi aktor Pengguna, Admin, dan Sistem Pembayaran eksternal terhadap fungsionalitas sistem.


* 
**Activity Diagram**: Memvisualisasikan *workflow* operasional melalui format *swimlane* dari tahap pencarian hingga finalisasi transaksi.


* 
**Sequence Diagram**: Merinci pertukaran pesan antar objek sistem dalam urutan waktu tertentu untuk proses *checkout* dan pembayaran.


* 
**Class Diagram**: Mendefinisikan struktur statis sistem yang mencakup atribut data dan metode fungsional pada setiap kelas objek.



## 🗄️ Manajemen Basis Data

Sistem mengimplementasikan basis data relasional **`ecommerce_kyyn`** yang dikelola melalui MariaDB/MySQL. Struktur database terdiri dari 10 tabel utama yang saling terintegrasi untuk menjaga integritas data transaksi:

* 
**`pengguna`**: Data identitas dan logistik pelanggan.


* 
**`produk`**: Katalog informasi detail barang, harga, dan stok.


* 
**`pesanan` & `pembayaran**`: Pencatatan rincian transaksi finansial dan status pesanan.


* 
**`admin`**: Kredensial khusus untuk akses manajemen sistem.



## 🎨 Filosofi Desain UI/UX

Antarmuka dikembangkan dengan pendekatan *user-centric* menggunakan tema **Dark Mode** untuk menciptakan kesan mewah (*luxury*) dan mengurangi kelelahan visual. Penerapan estetika **Glassmorphism** pada komponen dialog memberikan tampilan yang modern dan bersih.

## 🛠️ Spesifikasi Teknologi

* 
**Metodologi**: Multimedia Luther.


* 
**Database**: MariaDB / MySQL.


* 
**Modeling Tools**: UML (Unified Modeling Language).


* 
**Testing**: Black Box Testing.



---

**Pengembang:**

* 
**Nama**: Rizky Maulana 


* 
**Institusi**: Universitas Pelita Bangsa 


* 
**Tujuan**: Laporan UAS Matakuliah Bisnis Elektronik 2025 



---

