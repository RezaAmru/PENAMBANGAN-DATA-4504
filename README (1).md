# PENAMBANGAN-DATA-4504
#### Tugas tentang mata kuliah penambangan data kelompok A11.4504.
#### Nama : Reza Amru Nismara
#### NIM : A11.2022.14516.
### JUDUL
- Footballers with 50+ International Goals men menggunakan KNN
# Ringkasan dan Permasalahan Project + Tujuan yang Akan Dicapai + Model / Alur Penyelesaian
-Ringkasan:
Project ini bertujuan untuk menganalisis dataset yang berisi informasi tentang pemain sepak bola pria yang telah mencetak lebih dari 50 gol internasional. Dataset ini mencakup berbagai fitur seperti nama pemain, usia, negara asal, tahun debut internasional, dan total gol yang telah dicetak oleh pemain.

-Permasalahan:
Permasalahan utama yang akan diselesaikan adalah bagaimana memprediksi kesuksesan seorang pemain sepak bola dalam mencetak lebih banyak gol internasional dengan menggunakan fitur-fitur yang ada di dataset ini. Model akan digunakan untuk mengklasifikasikan pemain berdasarkan tingkat pencapaian gol internasionalnya.

-Tujuan:
Menganalisis data pemain sepak bola dengan lebih dari 50 gol internasional.
Mengidentifikasi faktor-faktor yang mempengaruhi pencapaian gol internasional.
Menggunakan model klasifikasi untuk memprediksi apakah seorang pemain akan mencetak lebih banyak gol berdasarkan data yang ada.

Model / Alur Penyelesaian:
-Preprocessing Data: Persiapan data, pembersihan data, dan analisis eksplorasi.
-Feature Engineering: Penentuan fitur penting yang dapat mempengaruhi hasil.
-Pemodelan: Menerapkan algoritma KNN untuk klasifikasi dan mengevaluasi performa model.
-Evaluasi: Menggunakan metrik seperti akurasi, precision, recall, dan F1-score untuk menilai performa model.
-Bagan Alur Penyelesaian:
- 1. Data Collection --> 2. Data Preprocessing --> 3. Feature Engineering --> 
  4. Model Building --> 5. Model Evaluation --> 6. Result Analysis
# Penjelasan Dataset, EDA dan Proses Features Dataset
Penjelasan Dataset:
Dataset ini berisi informasi tentang pemain sepak bola pria yang telah mencetak lebih dari 50 gol internasional. Beberapa fitur penting dalam dataset ini termasuk:

- Name: Nama pemain.
- Country: Negara asal pemain.
- Goals: Total gol internasional yang dicetak.
- Age: Usia pemain pada saat pengumpulan data.
- Debut Year: Tahun debut pemain dalam tim nasional.
- Exploratory Data Analysis (EDA):

Memeriksa distribusi usia pemain dan rata-rata gol internasional yang dicetak.
Mengidentifikasi pemain dengan gol terbanyak dan tahun debut yang lebih awal.
Visualisasi jumlah pemain dari berbagai negara yang berada dalam dataset.
Proses Features Dataset:

Memilih fitur yang relevan, seperti Age, Goals, dan Debut Year.
Melakukan normalisasi pada kolom yang berhubungan dengan angka seperti Goals dan Age.
Memperbaiki nilai yang hilang (jika ada) dengan mengisi atau menghapus data yang tidak lengkap.
# Proses Learning / Modeling
Proses Learning:

-Pembagian Data: Memisahkan dataset menjadi dua bagian—data latih (train) dan data uji (test) dengan rasio 80:20.
-Penerapan Algoritma KNN: Menggunakan algoritma K-Nearest Neighbors (KNN) untuk mengklasifikasikan pemain berdasarkan jumlah gol yang mereka cetak dan faktor lainnya.
-Optimasi Parameter: Menyesuaikan nilai parameter k (jumlah tetangga terdekat) untuk memperoleh hasil yang optimal.
-Evaluasi Model: Menggunakan data uji untuk mengukur akurasi, precision, recall, dan F1-score dari model KNN.
# Peforma Model
Performa Model:
Setelah model KNN dibangun dan diuji, performa model dapat dinilai menggunakan metrik evaluasi:

Akurasi: Mengukur seberapa sering model memprediksi dengan benar.
Precision dan Recall: Mengukur ketepatan dan kemampuan model dalam mengidentifikasi pemain yang benar-benar memenuhi kriteria pencapaian gol tinggi.
F1-Score: Menggabungkan precision dan recall untuk memberikan gambaran yang lebih baik tentang kinerja model.
Hasil Akurasi: Skor F1: 0.6470588235294118 = 64,7% 
# Diskusi Hasil dan Kesimpulan
# Diskusi Hasil:
Berdasarkan hasil evaluasi, model KNN dapat memberikan prediksi yang cukup akurat tentang pencapaian gol internasional pemain sepak bola pria. Meskipun ada beberapa kesalahan dalam prediksi, model ini tetap dapat memberikan informasi yang berguna dalam memprediksi pemain yang mungkin mencetak lebih banyak gol internasional.

# Kesimpulan:
Proses pemodelan berhasil mengidentifikasi beberapa pola dalam data yang dapat digunakan untuk memprediksi pencapaian gol internasional.
Algoritma KNN terbukti efektif dalam memprediksi tingkat pencapaian gol internasional, meskipun ada ruang untuk peningkatan model menggunakan algoritma lain atau teknik lain seperti pengoptimalan parameter lebih lanjut.


