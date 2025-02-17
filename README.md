# Causal Inference with Randomized Controlled Trial (RCT)

## Deskripsi
Repositori ini berisi analisis Causal Inference menggunakan metode Randomized Controlled Trial (RCT) untuk mengevaluasi dampak suatu treatment terhadap outcome tertentu. Notebook ini mengeksplorasi perbedaan rata-rata pendapatan rumah tangga antara kelompok treated dan control serta menghitung Average Treatment Effect (ATE).

## Struktur File
lbb_causal_inference_RandomizedControlledTrial.ipynb → Notebook utama yang berisi eksplorasi data, perhitungan ATE, dan visualisasi hasil.
data/ → (Opsional) Folder tempat dataset yang digunakan dalam analisis.

## Analisis yang Dilakukan
1. Eksplorasi Data:
   - Mengelompokkan data berdasarkan variabel responded.
   - Menghitung statistik deskriptif (mean, median) dari variabel median household income.
2. Estimasi Average Treatment Effect (ATE):
   - Menggunakan perbedaan rata-rata pendapatan rumah tangga antara kelompok treated (responded = 1) dan control (responded = 0).
   - Menghitung persentase perubahan dari kelompok control.
3. Visualisasi Data:
   - Scatter plot dan pairplot untuk memahami hubungan antar variabel.
   - Distribusi pendapatan rumah tangga berdasarkan kelompok treatment.
## Sumber Data
Dataset yang digunakan dalam analisis ini berasal dari library pandas - Black Politician dataset, yang merupakan bagian dari eksperimen sosial. Dataset ini mencakup informasi mengenai karakteristik rumah tangga, pendapatan, serta variabel treatment dan outcome.

📌 Nama Dataset: Black Politician Dataset
🔗 Sumber: Library pandas
📋 Deskripsi:
Dataset ini berisi informasi tentang rumah tangga di berbagai wilayah dan dampak kehadiran politisi kulit hitam terhadap tingkat partisipasi dan ekonomi masyarakat di wilayah tersebut.
⚠️ Catatan: Dataset ini bisa diakses langsung menggunakan library pandas. Jika dataset tidak tersedia, Anda dapat menggunakan dataset serupa dengan struktur yang sesuai.

## Teknologi & Library yang Digunakan
Notebook ini dibuat menggunakan Python dan memanfaatkan beberapa library berikut:

Data Manipulation

pandas → Untuk membaca, mengolah, dan menganalisis data.
numpy → Untuk operasi matematika dan perhitungan statistik.
Data Visualization

matplotlib → Untuk membuat berbagai jenis grafik.
seaborn → Untuk visualisasi statistik yang lebih kompleks (misalnya, pairplot dan distribusi data).
Statistical Analysis & Causal Inference

statsmodels → Untuk uji signifikansi statistik dan regresi.
scipy → Untuk analisis statistik tambahan.
Jupyter Notebook

Notebook interaktif untuk eksplorasi dan dokumentasi analisis.
## Cara Menggunakan
Clone repositori ini:
bash
Salin
Edit
git clone https://github.com/username/repo-name.git
cd repo-name
Install dependencies:
bash
Salin
Edit
pip install -r requirements.txt
Jalankan notebook di Jupyter:
bash
Salin
Edit
jupyter notebook
## Catatan
Dataset dapat diakses menggunakan pandas. Jika dataset tidak tersedia, alternatif lain bisa digunakan.
Untuk eksperimen lanjutan, metode Propensity Score Matching (PSM) atau Instrumental Variables (IV) dapat diterapkan.
## Kontak
Jika ada pertanyaan atau ingin berdiskusi lebih lanjut, silakan buat issue atau hubungi saya melalui LinkedIn.
