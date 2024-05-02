# Sonar, Mines vs. Rocks

Proyek ini merupakan UAS bagian 2 yang menggunakan Dataset Sonar dataset yang digunakan dalam masalah klasifikasi untuk mendeteksi apakah objek di bawah laut adalah batu (rock) atau ranjau (mine), berdasarkan sinyal sonar. Dataset ini terdiri dari 60 input variable dan 1 output variable. Pada proyek ini 3 algoritma klasifikasi digunakan dan dibandingkan.

## Algoritma
Dalam studi kasus ini, Tiga Algoritma yang digunakan sebagai perbandingan dalam memprediksi, antara lain:
1. Support Vector Machine
2. Naive Bayes - Gaussian
3. Random Forest Classifier

## Library
*   Pandas untuk memanipulasi data
*   Sklearn  untuk membangun model Machine Learning
*   Confusion Matrix untuk informasi perbandingan hasil klasifikasi yang dilakukan oleh sistem (model) dengan hasil klasifikasi sebenarnya.
*   Gaussian NB untuk membangun algoritma dari naivebayes yang dapat memuat data numerik

## Kesimpulan 

* Support Vector Machine (SVM)
  
![image](https://github.com/azkafauzi/Data-Science-and-Machine-Learning-Project/assets/62132378/79ba97cd-4325-46e5-82ad-420e95ae69ad)

* Random Forest Classifier

![image](https://github.com/azkafauzi/Data-Science-and-Machine-Learning-Project/assets/62132378/a0b40cce-9a74-4ef8-97ec-e7efe4730e69)

* Naive Bayes - Gaussian

![image](https://github.com/azkafauzi/Data-Science-and-Machine-Learning-Project/assets/62132378/116ebdca-72f4-4f76-854b-9dad1ba401bf)

Berdasarkan pemodelan dengan tiga algoritma berbeda. Hasil terbaik yaitu dengan menggunakan model SVM dengan tingkat akurasi 100%. Namun, dalam prakteknya, sangat jarang untuk mendapatkan model yang sempurna dengan akurasi 100%, hal ini memungkinkan data memiliki kekacauan atau ketidakpastian tertentu, atau data terlalu sederhana. Sehingga model yang lebih tepat digunakan adalah model klasifikasi Random Forest dengan akurasi sebesar 97%.
