# Data Mahasiswa menggunakan ORM pada Java

File ini adalah aplikasi **CRUD sederhana** untuk data mahasiswa menggunakan **Java**, **MySQL**, **Hibernate**, dan **Maven** dengan antarmuka **Java Swing**.

## Struktur
- `Model`
  - `ModelMahasiswa.java` : Representasi data mahasiswa (@Entity Hibernate)  
  - `ModelTableMahasiswa.java` : Mengatur tampilan data di JTable  
  - `HibernateUtil.java` : Mengelola koneksi Hibernate  
- `Controller`
  - `MahasiswaController.java` : Interface pengatur alur CRUD  
  - `MahasiswaControllerImpl.java` : Pelaksana fungsi CRUD ke database  
- `View`
  - `MahasiswaView.java` : Tampilan utama dengan form dan tabel Swing  
- `pom.xml` : Konfigurasi Maven dan library Hibernate/MySQL

## Fitur
- Tambah, lihat, ubah, hapus data mahasiswa  
- Menampilkan data mahasiswa di tabel (JTable)  
- Cek koneksi database  

## Cara Menjalankan
1. Start **Apache & MySQL** di XAMPP  
2. Buat database `pert4_50422341`  
3. Build project dengan **Maven**  
4. Jalankan `MahasiswaView.java` dan gunakan form/tombol untuk CRUD
