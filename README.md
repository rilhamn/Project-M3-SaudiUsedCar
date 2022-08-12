# Saudi Used Car
Platform penjualan mobil bekas sudah menjadi hal yang umum pada era ini. Karena dengan platform inilah (sebagai third party) interaksi yang terjadi antara penjual dan calon pembeli menjadi mudah.
Umumnya penjual diberi keleluasaan untuk menentukan harga mobil bekas. Namun akan sangat sulit bagi penjual untuk menentukan harga penjualan mobil bekas yang sekirnya kompetitif di Pasar.
Maka dari itu, setidaknya mereka diberi hint harga melalui platform penjualan mobil ini dengan membuat model regresi yang mampu memprediksi harga kompetitif secara tepat.

# Table of Content
## 1. Initial Preparation
- Daftar library yang digunakan 
- Overview singkat dataset (info dan describe)
- Penjelasan Singkat tiap Fitur
## 2. EDA dan Data Cleaning
- Penjelasan data tiap fitur (Berupa plot) serta kesimpulanya
- Penjelasan proses manipulasi data pada anomali (outlier, missing,etc)
## 3. Correlation
- Penjelasan mengenai keterkaitan antar fitur dan juga fitur dengan target
## 4. Modeling Preparation
- Persiapan data
- Mendefinisikan transformer (encoding, impute, etc)
## 5. Choose Best Benchmark Model
- Crossvalidation untuk 5 model regresi 
- Penjelasan mengenai penentuan model terbaik
## 6. Hyperparameter Tuning and Predict to Test Set (First Attempt)
- Penjelasan mengenai pencarian parameter terbaik untuk model XGBoost (Best Benchmark Model)
- Membandingkan hasil sebelum hyperparameter tuning dan setelah hyperparameter tuning
- Membandingkan hasil pada train set dan Test Set
## 7. Hyperparameter Tuning and Predict to Test Set (Second Attempt)
- Penjelasan sama dengan bab sebelumnya namun untuk bab ini merupakan perbaikan model dari bab sebelumnya
## 8. Feature Importance
- Penjelasan mengenai fitur-fitur apa saja yang sangat berpengaruh pada target
## 9. Conclusion dan Recommendation
- Penjelasan mengenai kesimpulan mengenai data dan hasil pemodelan
- Penjalasan langkah yang paling baik dilakukan untuk meningkatkan model
