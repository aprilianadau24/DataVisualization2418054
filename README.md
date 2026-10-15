Data Visualization — Global AI Jobs 2026
Informasi Proyek
- Nama: Apriliana Trisnawati Dau
- NIM: 2418054
- Mata Kuliah: Data Mining
Deskripsi
Proyek ini mengeksplorasi dataset Global AI Jobs 2026 melalui pemeriksaan struktur data, pembersihan data ringan, analisis deskriptif, dan visualisasi menggunakan Python. Notebook menjelaskan tujuan setiap grafik, cara membacanya, serta batasan interpretasinya.
Hasil analisis hanya menggambarkan pola pada file dataset yang digunakan dan tidak otomatis mewakili seluruh pasar kerja AI global.
Dataset
Notebook membaca file hasil pembersihan bernama global_ai_jobs_2026_cleaned.csv dari Google Drive pada Google Colab.
Kolom yang digunakan dalam visualisasi antara lain:
- AI_Specialization
- Experience_Level
- Salary_USD
- Country
- Work_From_Home_Available
- Posted_Date
Sumber dataset: Global AI Jobs 2026 Dataset, yang dirujuk oleh notebook Kaggle “AI Jobs Salary 2026” karya Shair Khan.
- Platform sumber: Kaggle
- dataset di Kaggle: Global AI Jobs 2026
- Profil kreator yang disebut sebagai referensi: Shair Khan di Kaggle
Catatan: tautan langsung ke halaman dataset asli belum berhasil diverifikasi. Tautan pencarian Kaggle di atas mengarah ke hasil pencarian dataset, bukan ke file Google Drive yang digunakan untuk menjalankan notebook.

Tahapan Analisis
1. Mengimpor pustaka yang diperlukan.
2. Memuat dataset dari Google Drive.
3. Memeriksa struktur data, tipe kolom, nilai kosong, duplikasi, dan statistik deskriptif.
4. Melakukan pembersihan ringan: merapikan spasi pada kolom teks, mengonversi kolom tanggal, mengubah kolom gaji menjadi numerik, dan memberi label pada nilai kosong di Required_Certifications.
5. Membuat delapan visualisasi.
6. Memeriksa rentang tanggal posting serta ringkasan dan persentil ke-99 nilai gaji.
7. Menyusun kesimpulan berdasarkan hasil visualisasi.
Visualisasi
Notebook berisi delapan visualisasi berikut:
1. Jumlah catatan pekerjaan berdasarkan spesialisasi AI — grafik batang horizontal untuk membandingkan jumlah catatan tiap kategori AI_Specialization.
2. Median gaji berdasarkan tingkat pengalaman — grafik batang yang membandingkan median Salary_USD untuk setiap Experience_Level.
3. 10 negara dengan jumlah catatan pekerjaan AI terbanyak — grafik batang horizontal berdasarkan frekuensi nilai pada kolom Country.
4. Ketersediaan kerja dari rumah — grafik batang yang membandingkan kategori pada Work_From_Home_Available; nilai kosong ditampilkan sebagai “Tidak diketahui”.
5. Tren jumlah catatan pekerjaan AI per tahun — grafik garis berdasarkan tahun dari Posted_Date.
6. Rata-rata gaji berdasarkan spesialisasi AI — grafik batang untuk membandingkan rata-rata Salary_USD tiap AI_Specialization.
7. Distribusi catatan berdasarkan tingkat pengalaman — pie chart yang menunjukkan proporsi kategori Experience_Level.
8. Tren jumlah catatan untuk tiga spesialisasi AI teratas — grafik garis yang membandingkan catatan tahunan untuk tiga spesialisasi yang paling sering muncul.
Catatan interpretasi: jumlah baris yang tercatat untuk suatu negara atau spesialisasi tidak selalu sama dengan jumlah posisi yang benar-benar dibuka. Grafik gaji juga dipengaruhi cakupan data, nilai ekstrem, dan jumlah catatan tiap kategori. Grafik tren hanya mencakup tahun yang tersedia pada Posted_Date.

Teknologi dan Pustaka
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook
Cara Menjalankan
1. Buka notebook DataVisualization2418054(1).ipynb di Google Colab atau Jupyter Notebook.
2. Siapkan file global_ai_jobs_2026_cleaned.csv.
3. Jika menggunakan Google Colab, unggah dataset ke lokasi Google Drive yang sesuai dengan path di notebook, atau sesuaikan variabel file_path dengan lokasi file milik Anda.
4. Jalankan sel notebook secara berurutan dari atas ke bawah.
Path yang digunakan di notebook saat ini:
/content/drive/MyDrive/Colab Notebooks/dataset/global_ai_jobs_2026_cleaned.csv
Keterbatasan
- Notebook tidak mencantumkan URL sumber asli dataset.
- Kesimpulan bergantung pada kualitas, cakupan, dan kelengkapan dataset.
- Rentang tanggal dalam data perlu diperiksa; nama dataset yang memuat tahun 2026 tidak menjamin seluruh catatan berasal dari tahun 2026.
- Nilai gaji ekstrem perlu ditinjau sebelum dijadikan dasar kesimpulan.
- Hasil visualisasi tidak boleh langsung digeneralisasi sebagai gambaran seluruh pasar kerja AI dunia.
File
- DataVisualization2418054(1).ipynb — notebook analisis dan visualisasi.
- global_ai_jobs_2026_cleaned.csv — dataset yang dibaca oleh notebook (perlu disediakan secara terpisah).
