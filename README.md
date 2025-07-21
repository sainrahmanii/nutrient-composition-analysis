# FoodAI: Analisis Komposisi Gizi Makanan

<p align="center">
  <img style="margin-right: 8px;" src="https://img.shields.io/badge/Language-Dart-blue" alt="Language: Dart">
  <img style="margin-right: 8px;" src="https://img.shields.io/badge/Framework-Flutter-brightgreen" alt="Framework: Flutter">
  <img style="margin-right: 8px;" src="https://img.shields.io/badge/Mobile-Android-green" alt="Mobile: Android">
  <img style="margin-right: 8px;" src="https://img.shields.io/badge/CNN-Model-orange" alt="CNN Model">
</p>

FoodAI adalah aplikasi mobile berbasis Flutter yang dirancang untuk membantu Anda memahami komposisi gizi makanan dengan lebih mudah. Aplikasi ini mampu mengidentifikasi jenis makanan dari gambar menggunakan model Convolutional Neural Network (CNN) yang telah dilatih. Setelah identifikasi, FoodAI akan menampilkan estimasi komposisi gizi makanan tersebut berdasarkan referensi data dari Kemenkes RI (NilaiGizi.com), memberikan wawasan berharga tentang apa yang Anda konsumsi.

## Fitur Utama ✨

*   **Identifikasi Makanan Berbasis Gambar 📸**: Menggunakan model CNN untuk mengidentifikasi jenis makanan dari gambar yang diambil atau diunggah.
*   **Estimasi Komposisi Gizi 📊**: Menampilkan estimasi komposisi gizi (karbohidrat, protein, lemak, dll.) dari makanan yang teridentifikasi.
*   **Referensi Data Kemenkes RI 🇮🇩**: Menggunakan data komposisi gizi yang terpercaya dari NilaiGizi.com, yang bersumber dari Kemenkes RI.
*   **Antarmuka Pengguna yang Intuitif 📱**: Dirancang dengan antarmuka pengguna yang sederhana dan mudah digunakan untuk pengalaman pengguna yang optimal.

## Tech Stack 🛠️

*   **Bahasa Pemrograman**: Dart dan Python (untuk integrasi dengan model CNN)
*   **Framework**: Flutter (untuk pengembangan aplikasi mobile)
*   **Machine Learning**: Convolutional Neural Network (CNN) untuk identifikasi gambar makanan

## Instalasi & Menjalankan 🚀

1.  Clone repositori:
    ```bash
    git clone https://github.com/sainrahmanii/nutrient-composition-analysis
    ```

2.  Masuk ke direktori:
    ```bash
    cd nutrient-composition-analysis
    ```

3.  Install dependensi Flutter:
    ```bash
    flutter pub get
    ```

4.  Jalankan proyek (pastikan Anda memiliki emulator Android atau perangkat terhubung):
    ```bash
    flutter run
    ```

## Cara Berkontribusi 🤝

Kami sangat menyambut kontribusi dari komunitas! Berikut adalah cara untuk berkontribusi:

1.  Fork repositori ini.
2.  Buat branch untuk fitur atau perbaikan bug Anda: `git checkout -b fitur/nama-fitur`
3.  Lakukan commit perubahan Anda: `git commit -m 'Tambahkan: Deskripsi perubahan'`
4.  Push ke branch Anda: `git push origin fitur/nama-fitur`
5.  Buat Pull Request.
