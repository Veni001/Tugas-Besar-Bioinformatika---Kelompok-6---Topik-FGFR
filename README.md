# **TUGAS BESAR BIOINFORMATIKA**

## **Klasifikasi Bioaktivitas Fibroblast Growth Factor Receptor (FGFR) Menggunakan Metode Lazy Classifier dan Random Forest**

## **Topik FGFR**
**Kelompok 6**

- Veni Zahara Kartika
- Khairunnisa Rifda Aulia
- Rahmi Agustin, Alayka Nazwa
- Rizka Yustiana Zahra
- Sylviani Prima Astuti Ananda

### Hasil
Evaluasi model menggunakan Lazy Classifier digunakan untuk mengevaluasi beberapa algoritma lain seperti RandomForestClassifier, LGBMClassifier, dan ExtraTreesClassifier, yang memberikan akurasi maksimum sebesar 90% dan 89%. Sebagai tambahan, model Random Forest Classifier menunjukkan performa yang sangat baik dengan akurasi training 0.9997 dan akurasi testing 0.9009, meskipun terdapat sedikit potensi overfitting. Analisis klasifikasi menunjukkan bahwa model lebih unggul dalam mengenali kelas mayoritas (kelas 0) dibandingkan kelas minoritas (kelas 1), dengan nilai F1-Score masing-masing 0.93 dan 0.84. Namun, Random Forest dengan parameter optimal yang diperoleh melalui Grid Search CV menunjukkan akurasi testing sebesar 89.7%, dengan kombinasi hyperparameter yaitu jumlah estimator 300, kedalaman maksimal None (kedalaman pohon tidak dibatasi), minimum samples split 2, dan minimum samples leaf 1. Dengan demikian, model Random Forest awal menjadi pilihan terbaik untuk klasifikasi dataset ini, karena menghasilkan performa paling stabil dan akurat dibandingkan algoritma lain.
