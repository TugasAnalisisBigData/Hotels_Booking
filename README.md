# 🤖 **Tugas Akhir: Analisis Big Data** 🤖

## Analisis Big Data untuk Distribusi Status Reservasi Hotel

Selamat datang di proyek Tugas Akhir ini! Proyek ini berfokus pada analisis data besar (Big Data) yang terkait dengan distribusi status reservasi hotel. Yang terdapat kode dan penjelasan untuk mengeksplorasi, memvisualisasikan, dan memahami pola data dalam konteks bisnis perhotelan.
---

## Daftar Isi
- [Tentang](#tentang)
- [Diagram Alur Proses](#diagram-alur-proses)
- [Dependensi](#dependensi)
- [Tim](#tim)
- [Ucapan Terima Kasih](#ucapan-terima-kasih)

---

## Tentang
Proyek ini bertujuan untuk memberikan wawasan tentang pola status reservasi meliputi "Canceled," dan "Not Canceled" pada data hotel. Melalui analisis ini, dapat memahami pola musiman, tren pembatalan, dan ketidakhadiran tamu, yang semuanya bermanfaat untuk pengambilan keputusan strategis di industri perhotelan.

Sebagai bagian dari proyek ini, sebuah Storyboard telah disiapkan untuk memberikan gambaran visual mengenai alur analisis dan hasil utama. **Link Storyboard**: [Klik di sini untuk melihat Storyboard](https://prezi.com/p/edit/gc0hoobcnzab/). Dalam proyek ini, menggunakan Python dan pustaka visualisasi data untuk membuat grafik interaktif dan informatif. File utama proyek ini berupa sebuah Jupyter Notebook yang berisi analisis data langkah demi langkah, mulai dari persiapan data hingga visualisasi hasil.

---

## Diagram Alur Proses
Tahapan analisis dalam proyek ini dapat divisualisasikan dalam diagram berikut:

![Analisis drawio](https://github.com/user-attachments/assets/b464487b-c17b-4da6-953c-fdf6f017ed0e)

### Penjelasan Diagram  

1. **Dataset**  
   Analisis dimulai dengan dataset utama, yaitu `Hotels.csv`, yang berisi informasi tentang status reservasi hotel. Dataset ini mencakup beberapa fitur penting seperti tanggal reservasi, durasi menginap, jenis kamar, jumlah tamu, dan status reservasi (Canceled atau Not Canceled).  

2. **Pra-Pemrosesan Data**  
   Tahapan pra-pemrosesan melibatkan beberapa langkah:  
   - **Mengatasi Nilai NAN:** Dataset dibersihkan dengan cara menghapus baris atau kolom yang memiliki banyak nilai kosong (NAN), atau menggantinya dengan nilai tertentu, seperti rata-rata untuk kolom numerik.
   - **Penghapusan Kolom**: Penghapusan kolom `country` 
   - **Konversi Data:** Kolom tertentu, seperti tanggal, dikonversi ke format datetime untuk memudahkan analisis waktu. Kolom kategorikal diubah menjadi numerik menggunakan teknik seperti one-hot encoding atau label encoding.  
   - **Normalisasi Data:** Data numerik dinormalisasi agar berada dalam rentang tertentu untuk memastikan model bekerja lebih baik.  

3. **Visualisasi Data**  
   Data yang telah diproses divisualisasikan dengan diagram histogram 

4. **Pemodelan Random Forest**  
   Model Random Forest digunakan untuk mengklasifikasikan status reservasi. Proses ini mencakup:  
   - Pemisahan data menjadi set pelatihan dan pengujian.  
   - Pelatihan model pada set pelatihan dengan hyperparameter yang telah disesuaikan.  
   - Evaluasi model menggunakan metrik seperti akurasi, precision, recall, dan F1-score untuk mengukur kinerja model.  

5. **Rangkuman**  
   Proyek ini diakhiri dengan merangkum hasil analisis, seperti:  
   - Identifikasi fitur utama yang memengaruhi status pembatalan.  
   - Wawasan tentang pola musiman atau tren pembatalan.  
   - Rekomendasi untuk pengelola hotel, seperti penyesuaian strategi reservasi atau promosi berdasarkan hasil analisis.
      
---

## Dependensi
- `Tensorflow` >= 2.17.1
- `Panda` >= 2.2.2
- `Numpy` >= 1.26.4
- `Matplotlib.Pyplot` >= 3.8.0
- `Seaborn` >= 0.13.2
- `Sklearn Pandas` >= 2.2.0
- `Scikit-Learn` >= 1.6.0
- `python` >= 3.10 

Untuk informasi lebih lanjut, lihat file `requirements.txt` di repositori ini.

---

## Tim
- 👨‍💻 [Nadiya Dewi Al Khlifi](https://github.com/Nadiyaal)
- 👨‍💻 [Mufidatul Nabilla Khasanah](https://github.com/MufidatulNabilla)
- 👨‍💻 [Nadia Humaira](https://github.com/NadiaHumairaa)

## Ucapan Terima Kasih
Kami ingin mengucapkan terima kasih kepada dosen mata kuliah Analisis Big Data, dan teman-teman sekolompok atas kontribusi dalam penyelesain tugas akhir selama pengerjaan proyek ini.

---

Semoga proyek ini bermanfaat untuk dalam memahami analisis data besar di dunia nyata. Jika memiliki pertanyaan atau saran, jangan ragu untuk membuat *issue* di repositori ini. Selamat menganalisis!

