<div align="center"><h1>Text Sentiment Analysis using Caikit and Hugging Face</h1></div>

## Deskripsi Proyek
Proyek ini merupakan eksperimen dalam membangun aplikasi sederhana untuk menganalisis sentimen menggunakan model pre-trained dari HuggingFace. Model ini dikombinasikan dengan Caikit dan gRPC untuk menciptakan sistem yang modular serta memiliki performa cepat.

## Lingkungan Pengembangan
Skills Network Cloud IDE (IBM)


## Panduan Instalasi
1. Buka terminal dan buat lingkungan virtual (virtual environment).
2. Pasang semua pustaka yang tercantum dalam file `requirements.txt`.

## Cara Penggunaan
1. Setelah semua pustaka terinstal, aktifkan lingkungan virtual.
2. Jalankan file `start_runtime.py`.
3. Buka terminal baru, edit file `client.py` untuk menyesuaikan teks yang akan diprediksi.
4. Jalankan file `client.py`.

## Analisis
Proyek ini menarik karena mengintegrasikan HuggingFace sebagai penyedia model pre-trained dengan Caikit sebagai framework untuk mendukung pengembangan kode yang modular. Hal ini mempermudah proses pemeliharaan. Selain itu, gRPC digunakan sebagai protokol komunikasi antara pengguna dan model, memastikan respons aplikasi yang cepat melalui penggunaan komponen protobuf. Praktik ini sangat relevan dan berpotensi untuk diimplementasikan dalam proyek berskala lebih besar.
