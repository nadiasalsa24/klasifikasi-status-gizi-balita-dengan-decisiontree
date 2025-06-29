🎓 Eksperimen Data Mining: Klasifikasi Status Gizi Balita dengan Decision Tree
Proyek ini merupakan eksperimen machine learning sederhana yang bertujuan untuk mengklasifikasikan status gizi balita berdasarkan fitur-fitur seperti jenis kelamin, usia, berat badan, dan tinggi badan menggunakan algoritma Decision Tree Classifier dari Scikit-learn.

🧠 Tema Proyek
Tema utama: Klasifikasi status gizi balita berdasarkan atribut fisik dan demografis.

Model akan mempelajari pola dari data balita dan memprediksi kategori status gizinya.

📁 Dataset
Dataset yang digunakan bernama data_balita.csv dan memuat informasi sebagai berikut:

Kolom	Deskripsi
Nama	Nama anak (tidak digunakan)
Jenis Kelamin	Laki-laki / Perempuan
Umur	Umur dalam bulan
Berat Badan	Berat badan (kg)
Tinggi Badan	Tinggi badan (cm)
Status Gizi	Target klasifikasi (baik, kurang, buruk, dll)

🔍 Preprocessing
Encoding:

Jenis Kelamin: Diubah ke numerik (laki-laki = 0, perempuan = 1)

Status Gizi: Di-encode dengan LabelEncoder

Pembagian Data:

Data dibagi menjadi 80% untuk pelatihan dan 20% untuk pengujian

🧪 Algoritma yang Digunakan
Decision Tree Classifier

Kriteria pemisahan: entropy

Library: sklearn.tree.DecisionTreeClassifier
