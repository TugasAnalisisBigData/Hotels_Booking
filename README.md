# 📉 **Tugas Akhir: Analisis Big Data** 🤖

## Analisis Big Data untuk Distribusi Status Reservasi Hotel

Selamat datang di proyek Tugas Akhir ini! Proyek ini berfokus pada analisis data besar (Big Data) yang terkait dengan distribusi status reservasi hotel. Di dalamnya terdapat kode dan penjelasan untuk mengeksplorasi, memvisualisasikan, dan memahami pola data dalam konteks bisnis perhotelan.
---

## Daftar Isi
- [Tentang](#tentang)
- [Diagram Alur Proses](#diagram-alur-proses)
- [Fitur Utama](#fitur-utama)
- [Dependensi](#dependensi)
- [Cara Memulai](#cara-memulai)
- [Tim](#tim)
- [Ucapan Terima Kasih](#ucapan-terima-kasih)

---

## Tentang
Proyek ini bertujuan untuk memberikan wawasan tentang pola status reservasi seperti "Check-Out," "Canceled," dan "No-Show" pada data hotel. Melalui analisis ini, kita dapat memahami pola musiman, tren pembatalan, dan ketidakhadiran tamu, yang semuanya bermanfaat untuk pengambilan keputusan strategis di industri perhotelan.

Dalam proyek ini, kami menggunakan Python dan pustaka visualisasi data untuk membuat grafik interaktif dan informatif. File utama proyek ini berupa sebuah Jupyter Notebook yang berisi analisis data langkah demi langkah, mulai dari persiapan data hingga visualisasi hasil.

---

## Diagram Alur Proses
Tahapan analisis dalam proyek ini dapat divisualisasikan dalam diagram berikut:

![Analisis drawio](https://github.com/user-attachments/assets/b464487b-c17b-4da6-953c-fdf6f017ed0e)

### Penjelasan Diagram
1. **Dataset**  
   Proses dimulai dengan dataset utama berupa file `Hotels.csv`, yang berisi data reservasi hotel.

2. **Pra-Pemrosesan Data**  
   Tahap ini mencakup tiga langkah utama:  
   - **Mengatasi Nilai NAN:** Membersihkan data dengan menghapus atau mengisi nilai kosong (NAN).  
   - **Konversi Data:** Mengubah tipe data menjadi format yang sesuai untuk analisis.  
   - **Normalisasi Data:** Menstandarkan data agar lebih konsisten dan mudah dianalisis.

3. **Visualisasi Data**  
   Data yang telah diproses divisualisasikan untuk mengidentifikasi pola dan tren yang relevan.

4. **Pemodelan Random Forest**  
   Dilakukan pemodelan menggunakan algoritma Random Forest untuk menganalisis dan memprediksi pola status reservasi.

5. **Rangkuman**  
   Proyek diakhiri dengan rangkuman dari hasil analisis dan wawasan yang diperoleh, yang digunakan untuk mendukung pengambilan keputusan strategis.

---

## Fitur Utama
Proyek ini menawarkan fitur berikut:  
- **Eksplorasi Data:** Membersihkan dan mempersiapkan dataset untuk analisis.  
- **Visualisasi Data:** Menampilkan distribusi data secara grafik untuk mendapatkan wawasan lebih dalam.  
- **Pola Musiman:** Menganalisis tren musiman pada status reservasi.  
- **Reproduksibilitas:** Semua kode disertakan untuk reproduksi penuh hasil.

---

## Dependensi
Proyek ini telah diuji menggunakan Python 3.9 dan pustaka berikut:  
- `pandas`, versi 1.3.3  
- `numpy`, versi 1.21.2  
- `matplotlib`, versi 3.4.3  
- `seaborn`, versi 0.11.2  
- `jupyterlab`, versi 3.1.18  

Untuk informasi lebih lanjut, lihat file `requirements.txt` di repositori ini.

---

## Cara Memulai
1. Clone repositori ini ke komputer Anda menggunakan perintah berikut:  
   ```bash  
   git clone https://github.com/username/Tugas-Akhir-Analisis-Big-Data.git  


2. Masuk ke direktori proyek:
   ```bash
   cd Tugas-Akhir-Analisis-Big-Data
   ```

3. Instal semua dependensi yang dibutuhkan:
   ```bash
   pip install -r requirements.txt
   ```

4. Jalankan Jupyter Notebook:
   ```bash
   jupyter lab
   ```

## Tim
- 👨‍💻 [Nadiya Dewi Al Khlifi](https://github.com/Nadiyaal)
- 👨‍💻 [Mufidatul Nabilla Khasanah](https://github.com/Nadiyaal)
- 👨‍💻 [Nadia Humaira](https://github.com/Nadiyaal)

## Ucapan Terima Kasih
Saya ingin mengucapkan terima kasih kepada pembimbing, keluarga, dan teman-teman atas dukungan dan bimbingannya selama pengerjaan proyek ini. Terima kasih juga kepada komunitas Python yang telah menyediakan dokumentasi dan pustaka yang luar biasa.

---

Semoga proyek ini bermanfaat untuk Anda dalam memahami analisis data besar di dunia nyata. Jika Anda memiliki pertanyaan atau saran, jangan ragu untuk membuat *issue* di repositori ini. Selamat menganalisis!

