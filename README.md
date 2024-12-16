# Analisis Sentimen dengan Caikit dan Hugging Face

Repositori ini menampilkan analisis sentimen menggunakan framework runtime Caikit dan model dari Hugging Face. Proyek ini mengatur server gRPC untuk menangani permintaan analisis sentimen, memungkinkan pengguna mengklasifikasikan teks sebagai positif, negatif, atau netral.

## Overview

Proyek ini memanfaatkan framework modular Caikit untuk menjalankan model analisis sentimen dari Hugging Face dalam lingkungan gRPC. Kode klien yang disediakan menunjukkan cara mengirim input teks ke server dan menerima klasifikasi sentimen sebagai respon.

## Features

- **gRPC Server**: Server untuk menangani permintaan analisis sentimen berbasis gRPC.
- **Caikit Runtime**: Mengintegrasikan runtime Caikit untuk mempermudah operasi model.
- **Hugging Face Sentiment Models**: Menggunakan model pra-terlatih dari Hugging Face untuk klasifikasi sentimen.

## Installation

1. **Clone the Repository**
   Jalankan perintah berikut:
   ```bash
   git clone https://github.com/Alfajri711/Sentiment-Analysis-Using-Caikit-and-HuggingFFace.git

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   
5. **Set Up Environment**
   Pastikan konfigurasi environment yang diperlukan, seperti jalur atau identifier model, telah diatur dengan benar di sistem atau file konfigurasi Anda.
