# Ahmad Farrel Aly 
# 09011282328045
# SK3C

# Laporan Singkat Hasil Dari Eksplorasi Dataset Heart Disease UCI

Berdasarkan Dataset tentang kesehatan yakni Dataset Heart Disease UCI dari Kaggle, setiap variabel yang terdapat pada dataset tersebut (id, age, trestbps, dll) dilakukan perhitungan statistik deskriptif untuk menemukan mean, median, modus, standar deviasi, variansi. Setelah dilakukan perhitungan, terdapat beberapa penemuan seperti adanya distribusi tidak normal seperti pada nilai variansi yang setiap variabel memiliki perbedaan nilai-nilai yang cukup besar. Distribusi tidak nomral ini dapat terlihat dari grafik histogram dan pair plot yang memiliki bentuk persebaran data yang bervariasi, ada yang tidak merata, ada yang membentuk garis lurus dan sebagainya.

Selain itu terdapat nilai yang hilang atau disebut sebagai missing values, yakni sebuah data yang tidak tersedia dalam suatu dataset. Missing values ditemukan pada beberapa variabel seperti pada 'ca' yang memiliki missing values terbanyak yakni 611 missing values, diikuti dengan thal yakni 486 missing values, 'slope' dengan 309 missing values, juga 'trestbps, chol, fbs, thalch, dan oldpeak' yang juga memiliki missing values.

Kemudian Outlier, yang merupakan sebaran data yang melewati batas minimum dan maksimum dari sebaran data normal. Outlier ini berbentuk sebuah 'Dot' yang terdapat pada boxplot. pada dataset ini, variabel 'trestbps' dan 'chol' yang memiliki outlier yang banyak.

Lalu korelasi, terdapat beberapa korelasi positif sedang seperti 'ca' dan 'num (0,52), 'oldpeak' dan 'num' (0,44). Adapun korelasi positif lemah seperti 'age' dan 'oldpeak' (0,28), 'chol' dan 'ca' (0,24). Sedangkan korelasi negatif sedang seperti 'chol' dan 'id' (-0,38), 'thalch' dan 'num' (-0,37), untuk korelasi negatif rendah yakni 'chol' dan 'num' (-0,23), 'trestbps' dan 'thalch' (-0,1)
