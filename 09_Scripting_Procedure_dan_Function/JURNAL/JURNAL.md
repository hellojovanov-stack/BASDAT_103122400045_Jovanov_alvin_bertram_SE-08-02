NOMOR 1 
No. 1 Penjelasan
Query digunakan untuk membuat tabel baru bernama EMPLOYEES_COPY berdasarkan data yang terdapat pada tabel EMPLOYEES. Perintah CREATE TABLE AS SELECT digunakan untuk menyalin struktur tabel beserta seluruh data yang ada di dalamnya.
<img width="658" height="479" alt="image" src="https://github.com/user-attachments/assets/c03c0a4e-29f3-438b-82b7-3dce07140af1" />

NOMOR 2
No. 2 Penjelasan
Query digunakan untuk menampilkan seluruh data yang terdapat pada tabel EMPLOYEES_COPY. Perintah SELECT * digunakan untuk mengambil seluruh kolom dan baris data dari tabel sehingga pengguna dapat melihat isi tabel yang telah dibuat.
<img width="633" height="483" alt="image" src="https://github.com/user-attachments/assets/4f20e20f-ad3c-4c73-a643-ff8a64599e74" />

NOMOR 3
Procedure increase_salary dibuat untuk melakukan perubahan gaji pegawai berdasarkan department tertentu. Procedure menerima dua parameter yaitu department_id_in sebagai kode department dan increase_pct_in sebagai nilai persentase perubahan gaji. Melalui perulangan FOR LOOP, setiap pegawai pada department yang dipilih akan diproses dan nilai salary diperbarui sesuai parameter yang diberikan.
<img width="633" height="646" alt="image" src="https://github.com/user-attachments/assets/b778cd69-6987-430e-be38-7857c1f7dcd7" />

NOMOR 4
Procedure increase_salary dijalankan pada department 80 dengan nilai parameter 0,50. Setelah proses update dilakukan, perintah ROLLBACK digunakan untuk membatalkan seluruh perubahan yang terjadi selama transaksi. Oleh karena itu, data salary pegawai tetap kembali ke kondisi semula dan tidak tersimpan secara permanen di database.
<img width="644" height="578" alt="image" src="https://github.com/user-attachments/assets/e8c06d08-cf8d-420d-9160-b5a90408e51f" />

No. 5 Penjelasan
Jika perintah ROLLBACK dihapus, maka seluruh perubahan salary yang dilakukan oleh procedure akan tetap tersimpan pada tabel EMPLOYEES. Akibatnya gaji pegawai pada department yang dipilih akan berubah secara permanen sesuai hasil eksekusi procedure.
