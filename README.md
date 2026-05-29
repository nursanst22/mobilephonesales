# mobilephonesales


Judul Proyek
**TechSales Navigator: Prediksi Durasi Penjualan Perangkat Elektronik Berbasis Machine Learning dan Dashboard Interaktif**

**Latar Belakang Masalah (Why)**
Dalam industri ritel elektronik (khususnya mobile phone dan laptop), manajemen inventaris adalah kunci keuntungan. Masalah utama yang sering dihadapi perusahaan adalah penumpukan stok (Dead Stock).
Barang yang terlalu lama mengendap di gudang dari tanggal masuk (Inward Date) hingga tanggal terjual (Dispatch Date) akan membebani biaya operasional dan rentan mengalami penurunan nilai karena teknologi cepat usang.
Perusahaan saat ini kesulitan menentukan secara pasti: Kombinasi spesifikasi apa (RAM, ROM, Harga, Brand) yang membuat sebuah barang cepat laku atau justru susah terjual di wilayah tertentu?

**Pendekatan dan Solusi (How)**
Untuk menyelesaikan masalah tersebut, proyek ini menggunakan pendekatan Data Analytics & Predictive Machine Learning dengan alur sebagai berikut:
1.	Data Wrangling (Pembersihan Data): Mengubah data spesifikasi yang mentah (teks) menjadi data numerik yang terstruktur. Misalnya, mengekstrak "12GB" menjadi angka 12 agar bisa dihitung secara matematis.
2.	Exploratory Data Analysis (EDA): Menganalisis secara visual korelasi antara harga, kapasitas RAM/ROM, dan region untuk menemukan tren pasar yang tersembunyi.
3.	Pemodelan Prediktif (Machine Learning): Melatih algoritma Random Forest dan XGBoost menggunakan ekosistem tidymodels di R. Model ini diajarkan untuk memahami pola historis dan memprediksi target utama: Lama Waktu Terjual (Days to Sell).
4.	Analisis Kepentingan Variabel (VIP): Mengekstrak wawasan dari AI untuk melihat faktor mana (misal: apakah harga atau ukuran RAM) yang paling mendikte lambat-cepatnya barang terjual.

**Hasil Akhir dan Luaran (What & The UI)**
Hasil akhir dari proyek ini bukan sekadar baris kode, melainkan sebuah UI Dashboard Interaktif yang dirancang khusus untuk tim Manajemen Stok dan Strategi Harga (Pricing).
Dashboard ini akan memiliki antarmuka (UI) dengan fitur utama:
•	Panel Monitor Tren (Visualisasi): Menampilkan grafik interaktif dari hasil EDA (seperti tren penjualan per Region dan distribusi harga per Brand).
•	Kalkulator Prediksi AI (Input UI): Sebuah formulir di mana pengguna (misal: Manajer Gudang) bisa memasukkan rencana spesifikasi barang baru (Brand, RAM, ROM, Harga).
•	Output Rekomendasi: Setelah tombol ditekan, UI akan menampilkan hasil prediksi ML: "Barang ini diprediksi akan terjual dalam waktu 45 hari. Rekomendasi: Kurangi harga sebesar 5% agar lebih cepat terjual di bawah 30 hari."


