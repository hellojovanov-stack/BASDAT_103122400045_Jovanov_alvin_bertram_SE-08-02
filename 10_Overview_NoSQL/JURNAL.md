No. 1a
Tentukan tipe database NoSQL yang paling cocok
Tipe database NoSQL yang paling cocok adalah Document Database (contohnya MongoDB).

No. 1b
Jelaskan alasan teknisnya
Document Database cocok digunakan karena data stok beras, jenis beras, tanggal kedaluwarsa, dan suhu gudang dapat disimpan dalam format dokumen JSON yang fleksibel. Database ini mampu menangani data sensor IoT yang terus bertambah, mudah diskalakan untuk banyak gudang di seluruh Indonesia, serta mendukung proses penyimpanan dan pengambilan data secara cepat untuk kebutuhan monitoring stok secara real-time.

No. 2a
Data JSON

{
  "name": "Jovanov Alvin Bertram",
  "category": "SE0802",
  "details": {
    "NIM": "103122400045",
    "roleTechManifest": "Backend Developer",
    "techStack": "Java, MySQL, Oracle"
  }
}

<img width="876" height="607" alt="image" src="https://github.com/user-attachments/assets/8e57269c-fec2-4388-b9b5-bd9866ce2bd3" />


No. 2b
Penjelasan
Data dikirim ke database Supabase menggunakan metode POST melalui Postman. Format data menggunakan JSON yang berisi nama, kategori, serta detail identitas mahasiswa.

No. 3
Penjelasan
Verifikasi data dilakukan menggunakan metode GET pada endpoint yang sama dengan menambahkan parameter query berdasarkan nama. Tujuannya untuk memastikan bahwa data yang telah dikirim berhasil tersimpan pada database dan dapat ditampilkan kembali melalui API.

Endpoint Supabase dapat diakses melalui browser, namun saat pengujian menggunakan Postman terjadi kendala koneksi sehingga response data tidak berhasil diperoleh.
