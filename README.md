# 🍴 Foodlok

## Nama Produk

**Foodlok** – Aplikasi Pencarian Tempat Makan Murah Berbasis Lokasi

---

## Deskripsi Produk

**Foodlok** adalah aplikasi seluler yang dirancang untuk membantu pengguna menemukan tempat makan paling **murah** di sekitar lokasi mereka dengan cepat dan mudah. Aplikasi ini ditujukan khusus untuk mahasiswa dan masyarakat umum yang ingin menikmati makanan lezat dengan harga terjangkau. Dengan memanfaatkan teknologi peta dan basis data *real-time*, Foodlok menyajikan informasi lokasi, kisaran harga, dan kategori tempat makan secara interaktif.

---

## ✨ Fitur Utama

Foodlok menyediakan beberapa fitur utama, antara lain:

* **Pencarian Tempat Makan Murah** – Menampilkan rekomendasi tempat makan dengan harga terjangkau di sekitar pengguna.
* **Peta Interaktif** – Menampilkan lokasi tempat makan pada peta lengkap dengan informasi jarak dan harga.
* **Filter Kategori** – Menyaring tempat makan berdasarkan kategori (warung, jajanan, kafe, dll).
* **Pencarian Cepat** – Memudahkan pengguna menemukan tempat makan tertentu.
* **Profil Pengguna** – Menyimpan data pengguna, riwayat pencarian, dan tempat favorit.
* **CRUD Data Lokasi** – Admin atau kontributor dapat menambah, mengubah, dan menghapus data tempat makan.

---

## 🛠️ Komponen Pembangun Produk

### Frontend

* **React Native** – Framework utama untuk membangun aplikasi mobile Android dan iOS.
* **Expo / React Native CLI** – Digunakan untuk proses pengembangan dan *testing* aplikasi.

### Backend & Database

* **Firebase Authentication** – Mengelola autentikasi pengguna.
* **Firebase Firestore** – Menyimpan data tempat makan, pengguna, dan informasi lokasi.

### Komponen Geospasial

* **ESRI Basemap** – Digunakan sebagai peta dasar untuk menampilkan lokasi tempat makan secara interaktif.

---

## 📊 Sumber Data

Sumber data yang digunakan dalam aplikasi Foodlok meliputi:

* **Data lokasi tempat makan** – Dikumpulkan secara manual oleh admin/kontributor.
* **Data harga dan kategori makanan** – Diperoleh dari hasil observasi lapangan dan input pengguna.
* **Data spasial (peta dasar)** – Bersumber dari layanan **ESRI Basemap**.

---

## 🖼️ Tangkapan Layar Aplikasi

Berikut adalah tangkapan layar untuk setiap fitur utama aplikasi **Foodlok**:

### 1. Halaman Beranda

Menampilkan ringkasan aplikasi dan akses cepat ke fitur utama.

![Halaman Beranda](screenshots/IMG-20251209-WA0004.jpg)

### 2. Peta Interaktif & Filter Makanan

Menampilkan lokasi tempat makan pada peta yang dapat difilter berdasarkan kategori makanan.

![Peta Interaktif](screenshots/IMG-20251209-WA0010.jpg)

### 3. Integrasi Google Maps

Menampilkan navigasi dan lokasi tempat makan menggunakan Google Maps.

![Integrasi Google Maps](screenshots/IMG-20251209-WA0009.jpg)

### 4. Tambah Data Tempat Makan (Add Data)

Fitur untuk menambahkan data lokasi tempat makan baru ke dalam sistem.

![Add Data](screenshots/IMG-20251209-WA0010.jpg)

### 5. Update & Delete Data Tempat Makan

Fitur untuk memperbarui dan menghapus data tempat makan yang telah tersimpan.

![Update dan Delete Data](screenshots/IMG-20251209-WA0005.jpg)

### 6. Profil Pengguna

Menampilkan informasi akun pengguna dan pengelolaan data profil.

![Profil Pengguna](screenshots/IMG-20251209-WA0006.jpg)

---

## 🤝 Kontribusi

Kontribusi sangat terbuka untuk pengembangan Foodlok. Silakan lakukan *fork*, buat *branch* baru, dan ajukan **Pull Request**.

---

## 📄 Lisensi

Proyek ini menggunakan lisensi **MIT**. Silakan lihat file `LICENSE` untuk informasi lebih lanjut.
