# MODUL 6 - SUBQUERY

Nama : Jovanov Alvin Bertram
NIM : 103122400045
Kelas : SE-08-02

NOMOR 1
<img width="609" height="473" alt="image" src="https://github.com/user-attachments/assets/efb7f8e5-4bb6-4848-ac89-970ef4a7fe34" />
Query digunakan untuk menampilkan nama dan umur member yang menonton pada teater dengan harga tiket tertinggi. Subquery digunakan untuk mencari harga tiket tertinggi pada tabel THEATER menggunakan fungsi MAX(HARGA). Hasil subquery kemudian digunakan oleh query utama untuk menampilkan data member yang melakukan transaksi pada teater tersebut.

NOMOR 2
<img width="540" height="551" alt="image" src="https://github.com/user-attachments/assets/12a7accf-a548-49b8-8d9c-52b593825129" />
Query digunakan untuk menampilkan judul film yang ditayangkan pada teater dengan harga tiket paling murah maupun paling mahal. Subquery digunakan untuk mencari nilai harga maksimum dan minimum pada tabel THEATER menggunakan fungsi MAX(HARGA) dan MIN(HARGA). Hasil subquery kemudian digunakan oleh query utama untuk menampilkan judul film yang sesuai.

NOMOR 3
<img width="531" height="495" alt="image" src="https://github.com/user-attachments/assets/a376dec9-64e9-45c8-a360-fe162776a140" />
Query digunakan untuk menampilkan film yang memiliki jumlah penayangan lebih banyak dibandingkan film yang paling sedikit ditayangkan. Subquery digunakan untuk mencari jumlah penayangan minimum dari setiap film. Hasil subquery tersebut kemudian dibandingkan dengan jumlah penayangan masing-masing film pada query utama menggunakan klausa HAVING.

NOMOR 4
<img width="540" height="474" alt="image" src="https://github.com/user-attachments/assets/bd3966e2-b54d-42a9-8699-6b4bab23e2af" />
Query digunakan untuk menampilkan nomor teater dan judul film yang memiliki jumlah penayangan di atas rata-rata. Subquery digunakan untuk menghitung rata-rata jumlah penayangan seluruh film. Query utama kemudian menampilkan data film dan teater yang jumlah penayangannya melebihi nilai rata-rata tersebut.

NOMOR 5
<img width="497" height="541" alt="image" src="https://github.com/user-attachments/assets/258a61ee-feec-4da9-bf4c-53f788fded31" />
Query digunakan untuk menampilkan nama member dan nomor telepon member yang menonton film dengan ID yang diawali kode tertentu. Subquery dan operator pencarian digunakan untuk memilih film berdasarkan pola ID film. Query utama kemudian menampilkan data member yang memiliki transaksi pada film tersebut.
