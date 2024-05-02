# Correlational Analysis of Movie Data (1980 - 2020) 

**Correlational Analysis of Movie Data** merupakan project yang memuat kumpulan data yang berfokus pada pendapatan film dan menganalisisnya selama beberapa dekade terakhir. Analisis ini bertujuan untuk mencari tau hubungan setiap atribut pada datasets seperti aktor, genre, peringkat pengguna, dan lainnya. Hasil dari analisa ini yaitu atribut mana yang memiliki korelasi terkuat diantara semua atribut. Hasil korelasi yang dihitung menggunakan Pearson correlation coefficient.


Beberapa atribut yang terdapat pada dataset, diantaranya:
1. Budget: anggaran film
2. Company: perusahaan produksi
3. Country: negara asal film
4. Director: sutradara
5. Genre: jenis atau genre utama film
6. Gross: pendapatan kotor film
7. Name: nama film
8. Rating: peringkat film (R, PG, etc.)
9. Released: tanggal rilis (YYYY-MM-DD)
10. Runtime: durasi film
11. Score: peringkat pengguna IMDB
12. Votes: voting atau suara dari penonton
13. Star: aktor/aktris utama
14. Writer: penulis film
15. Year: tahun rilis

## Kesimpulan
Berdasarkan hasil analisa tersebut, budget dan gross memiliki korelasi kuat sebesar 0.74 serta gross dan votes yang memiliki korelasi yang cukup kuat sebesar 0.61. Sedangkan data tidak menunjukkan korelasi apa pun antara company dan gross dikarenakan  company adalah string bukan nilai numerik sehingga korelasi tidak bisa dilakukan. Hal ini pun berlaku untuk atribut string lainnya, seperti country, director, name, dll.
