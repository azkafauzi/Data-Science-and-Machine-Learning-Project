# Klasifikasi Diagnosis Tumor Ganas dan Tumor Jinak (Kanker Payudara)

Proyek ini bertujuan untuk melakuakn klasifikasi dan mengukur akurasi pada data diagnosis kanker payudara winconsin. Jika sebelumnya data ini pernah dilakukan percobaaan dengan menggunakan algoritma KNN (K-Nearest-Neighbors) maka pada studi kasus ini kami menggunakan algoritma Support Vector Machine/Support Vector Classification untuk mengkalisifikasikannya dengan mencari tumor yang terdeteksi/terdiagnosis.

Dengan menerapakan train dan test data, berapakah nilai accuracy/ketepatan algoritma SVM ini untuk mengklasifikasi kelas berdasarkan diagnosis tumor yang terdeteksi/terdiagnosis?

## Datasets
Dataset merupakan kumpulan data cancer/ kanker payudara di Winconsin, yaitu sebuah negara bagian di Amerika Serikat. Kumpulan data ini berisi diagnosis kanker dengan membagi menjadi tumor jinak (Benign) dan tumor ganas (Malignant) berdasarkan nilai-nilai medis yang diteliti.  Benign tumor/ Tumor jinak disebut juga tumor non-kanker yang biasanya tidak mengancam jiwa.Sementara (malignant tumor) adalah tumor yang terbentuk dari sel kanker.
Dataset ini dapat di download dan berasal dari url berikut :
https://raw.githubusercontent.com/melwinlobo18/K-Nearest-Neighbors/master/Dataset/data.csv
atau data asli dapat diakses di kaggle, link berikut :
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

Terdapat 569 baris dan 33 kolom data. Beberapa kolom/atribut data terdiri dari :

1. id: Id sebuah data
2. diagnosis: hasil diagnosis dengan inisial M untuk Mallignant (Ganas) dan B untuk Benign (Jinak)

Kemudian ada kolom berisi nilai-nilai yang merupkan catatan medis atau yang sudah diteliti dengan pendekatan medis, seperti :

radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, concave points_mean, symmetry_mean fractal_dimension_mean, radius_se, texture_se, perimeter_se, area_se, smoothness_se, compactness_se, concavity_se, concave points_se. symmetry_se, fractal_dimension_se, radius_worst, texture_worst, perimeter_worst, area_worst, smoothness_worst, compactness_worst, concavity_worst, concave points_worst, symmetry_worst fractal_dimension_worst

Kemudian kolom Unnamed:32 yang tidak berisi nilai dan akan dihapus

## Kesimpulan
![image](https://github.com/azkafauzi/Data-Science-and-Machine-Learning-Project/assets/62132378/4fb02763-e9ef-410f-8a59-9cd56059652b)

Berdasarkan hasil klasifikasi data breast cancer menggunakan SVM, nilai accuracy yang didapatkan sebesar 96%
