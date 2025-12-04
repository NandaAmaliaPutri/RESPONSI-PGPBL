# 🍴 Foodlok

**Foodlok** adalah aplikasi seluler yang dirancang untuk membantu pengguna menemukan tempat makan paling **murah** di sekitar lokasi mereka dengan cepat dan mudah. Temukan makanan lezat tanpa menguras kantong Anda!



---

## ✨ Fitur Utama

Foodlok hadir dengan serangkaian fitur yang memudahkan pengalaman mencari makan:

* **Cari Tempat Makan Murah:** Algoritma pencarian yang fokus pada rekomendasi makanan dengan harga terjangkau.
* **Lokasi Terbaru:** Data tempat makan yang selalu diperbarui, memastikan Anda mendapatkan informasi terkini.
* **Filter Kategori:** Saring hasil pencarian berdasarkan jenis masakan atau kategori makanan (misalnya, Jajanan, Warung, Kafe).
* **Pencarian Cepat:** Opsi pencarian instan untuk menemukan tempat spesifik.
* **Peta Interaktif:** Visualisasikan lokasi tempat makan di peta, lengkap dengan informasi harga dan jarak.
* **Profil Pengguna:** Kelola data, riwayat pencarian, dan simpan tempat favorit Anda.
* **CRUD Lokasi (Admin/Kontributor):** Fungsionalitas untuk **C**reate, **R**ead, **U**pdate, dan **D**elete data lokasi tempat makan.

---

## 🛠️ Teknologi

Aplikasi ini dibangun menggunakan teknologi modern untuk memastikan kinerja yang cepat dan pengalaman pengguna yang mulus.

### **Frontend & Framework**

| Teknologi | Deskripsi |
| :--- | :--- |
| **React Native** | Digunakan untuk membangun antarmuka pengguna yang *cross-platform* (Android & iOS) dari satu basis kode. |

### **Backend & Database**

| Teknologi | Deskripsi |
| :--- | :--- |
| **Firebase** | Menyediakan layanan *backend* tanpa server, termasuk otentikasi dan *hosting*. |
| **Firestore** | Database NoSQL *cloud-hosted* yang digunakan untuk menyimpan data tempat makan, profil pengguna, dan informasi lokasi. |

### **Geospasial**

| Teknologi | Deskripsi |
| :--- | :--- |
| **ESRI Basemap** | Digunakan sebagai penyedia peta dasar untuk tampilan dan navigasi peta interaktif. |

---

## 🚀 Instalasi dan Penggunaan

Ikuti langkah-langkah di bawah ini untuk menjalankan Foodlok di lingkungan pengembangan lokal Anda.

### **Prasyarat**

Pastikan Anda telah menginstal yang berikut:

* Node.js (versi terbaru direkomendasikan)
* React Native CLI atau Expo CLI
* JDK (Java Development Kit) untuk Android
* Xcode untuk iOS (jika mengembangkan di macOS)

### **Langkah-langkah Instalasi**

1.  **Kloning Repositori:**
    ```bash
    git clone [https://github.com/NandaAmaliaPutri/foodlok.git](https://github.com/NandaAmaliaPutri/foodlok.git)
    cd foodlok
    ```

2.  **Instal Dependensi:**
    ```bash
    npm install
    # atau
    yarn install
    ```

3.  **Konfigurasi Firebase:**
    * Buat proyek baru di [Firebase Console](https://console.firebase.google.com/).
    * Aktifkan **Firestore** dan siapkan aturan keamanan (security rules) yang sesuai.
    * Tambahkan konfigurasi aplikasi **Android** dan **iOS** ke proyek Firebase Anda.
    * Tambahkan file konfigurasi (misalnya `google-services.json` untuk Android dan `GoogleService-Info.plist` untuk iOS) ke direktori yang sesuai di proyek React Native Anda.
    * **Catatan:** Pastikan juga Anda telah mengatur kunci API untuk ESRI Basemap jika diperlukan.

4.  **Jalankan Aplikasi:**

    * **Android:**
        ```bash
        npx react-native run-android
        ```

    * **iOS:**
        ```bash
        # Jika menggunakan CocoaPods
        cd ios && pod install && cd ..
        npx react-native run-ios
        ```

---

## 🤝 Kontribusi

Kontribusi disambut baik! Jika Anda memiliki ide atau ingin melaporkan *bug*, silakan:

1.  *Fork* repositori ini.
2.  Buat *branch* baru (`git checkout -b feature/amazing-feature`).
3.  Lakukan *commit* perubahan Anda (`git commit -m 'feat: Add amazing feature'`).
4.  *Push* ke *branch* (`git push origin feature/amazing-feature`).
5.  Buka **Pull Request** baru.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi **MIT** - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

---
