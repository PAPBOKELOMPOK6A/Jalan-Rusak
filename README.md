# PROGRAM APLIKASI LAPOR JALAN RUSAK DI SAMARINDA
Kelompok 6A
1. Alyssa Dwiana Mulia 2309116009
2. Siti Annida Adzra 2309116013
3. Widia Saputri 2309116019
4. Fitriani 2309116021

## 📍Latar Belakang
Infrastruktur jalan merupakan salah satu elemen vital dalam pembangunan dan aktivitas masyarakat di Kota Samarinda. Kualitas jalan yang baik tidak hanya mendukung kelancaran mobilitas penduduk dan distribusi barang, tetapi juga menjadi faktor penting dalam menjaga keselamatan pengendara. Namun, permasalahan jalan rusak sering kali menjadi kendala yang mengganggu kelancaran aktivitas sehari-hari dan berpotensi meningkatkan risiko kecelakaan lalu lintas. Kendala yang sering dihadapi oleh masyarakat dalam menangani permasalahan jalan rusak adalah keterbatasan akses dalam melaporkan kondisi jalan yang memerlukan perbaikan. Sering kali laporan mengenai jalan rusak sulit untuk dipantau atau tidak ditindaklanjuti dengan cepat oleh instansi terkait. Hal ini dikarenakan kurangnya sarana komunikasi yang efektif antara masyarakat dan pihak berwenang, dalam hal ini Dinas Pekerjaan Umum Kota Samarinda.

## 📍Deskripsi Project
Aplikasi Pelaporan dan Monitoring Jalan Rusak di Kota Samarinda. Aplikasi ini berbasis aplikasi Java dengan antarmuka GUI, yang memungkinkan pengguna umum (User) untuk melaporkan kondisi jalan yang mengalami kerusakan, serta memberikan akses kepada petugas dinas (Admin) untuk memantau, mengelola, dan memperbarui status perbaikan jalan tersebut. Melalui aplikasi ini, diharapkan masyarakat dapat lebih mudah dan cepat melaporkan jalan berlubang atau rusak. Sementara itu, pihak Admin dari Dinas Pekerjaan Umum dapat melakukan manajemen laporan dengan lebih efisien, termasuk melakukan pencarian, menyortir laporan berdasarkan tingkat kerusakan, dan memberikan tindak lanjut yang diperlukan. Adanya fitur CRUD (Create, Read, Update, Delete) untuk laporan juga memudahkan Admin dalam memvalidasi dan menghapus laporan yang tidak relevan atau telah selesai diperbaiki.

## 📍Flowchart
![image](https://github.com/user-attachments/assets/b18fd165-55dc-4050-9f4d-f57a2278364c)

Flowchart ini menggambarkan alur sistem pelaporan jalan rusak. 

## 📍Aktivity Diagram
![image](https://github.com/user-attachments/assets/dc149cc8-4784-4156-910b-debce08355f0)

## 📍Use Case
![image](https://github.com/user-attachments/assets/115de66b-d125-45e1-a43f-ed1ccd9ac74d)

Use Case Diagram memberikan gambaran visual tentang interaksi antara pengguna dengan sistem. Ini mencakup aksi-aksi utama yang dapat dilakukan oleh pelapor dan bagaimana sistem akan meresponsnya. dalam gambar tersebut ada 2 role yaitu admin dan pelapor dimana mereka memiliki fungsi mereka masing-masing.

a. Pelapor, jika dalam gambar pelapor ini dapat melakukan login, jika pelapor belum memiliki akun maka akan diminta untuk melakukan registrasi dan ketika sudah selesai maka akan diminta untuk login kembali. pelapor juga dapat menambahkan laporan terkait jalan rusak, lihat laporan jalan rusak, mencari laporan berdasarkan nama jalan, dan memfilter laporan berdasarkan tingkat kerusakan jalan yang sudah dilaporkan.

b. Admin, jika dalam gambar admin ini bisa langsung login sebagai admin yang dimana tanpa registrasi. Admin dapat melihat laporan jalan rusak, mencari laporan, filter laporan sebenarnya hampir sama dengan pelapor hanya saja  admin bisa mengedit status laporan. 

## 📍Logical ERD
![image](https://github.com/user-attachments/assets/0eae3afe-0e9c-48f7-99c6-c51397d5701e)

Dalam ERD di atas memiliki 2 entitas yaitu User dan laporan dimana entitas User ini memiliki Subtype yaitu Pelapor dan Admin. Konsep supertype dan subtype digunakan untuk membedakan antara admin dan pelapor sebagai subtype dari entitas user. Admin dan pelapor memiliki atribut khusus, namun keduanya merupakan jenis akun dalam sistem lapor jalan.
Dalam hubungan antar entitas, terdapat keterkaitan atau relasi wajib (mandatory) user memiliki relasi yang wajib dengan laporan dimana artinya user harus mengelola laporan dimana di user ada admin dan pelapor si admin bertugas mengelola laporan yang sudah dibuat oleh si pelapor.

## 📍Relational ERD
![image](https://github.com/user-attachments/assets/5a9cad39-99cf-495a-a05b-b5ea7ae4ff5c)


## 📍Penerapan 4 Pilar

## 📍Screenshoot Output

1. Tampilan Login
   ![image](https://github.com/user-attachments/assets/9bf9ead7-59e7-416e-91b2-3c3dced71f9c)

   Tampilan di atas merupakan tampilan login dimana user dan admin dapat memasukkan username dan password yang mereka miliki.

3. Tampilan Registrasi
   ![image](https://github.com/user-attachments/assets/4f76b446-468e-42be-8a52-a822f9cfe99c)
   
   Tampilan diatas merupakan tampilan registrasi untuk pelapor yang tidak memiliki akun maka akan diminta untuk daftar atau registrasi, dimana pelapor memasukkan data dirinya. 
   
6. Tampilan Menu Admin
   ![image](https://github.com/user-attachments/assets/11ed16f3-0a57-4bd4-8bcc-d8ea69c233b1)

   Tampilan menu admin ini diberikan akses untuk mengelola laporan yang masuk melalui dua opsi utama, yaitu Lihat Laporan dan Edit Status Laporan. Setiap opsi dirancang untuk membantu admin dalam memantau dan memperbarui data laporan jalan rusak. Selain itu, admin juga memiliki opsi untuk kembali dari halaman jika tugas telah selesai.

7. Tampilan Menu Edit Status Laporan
    ![image](https://github.com/user-attachments/assets/eb39cfda-83fd-47e4-8ef2-64deb3dfac3e)

   Tampilan Edit Status Laporan, admin dapat memilih laporan tertentu dari daftar laporan yang sudah ada untuk diperbarui. Setelah laporan dipilih, sistem akan memberikan pilihan untuk mengubah status laporan sesuai kebutuhan, seperti dari "belum diproses" menjadi "sedang diproses" atau "selesai". Perubahan status ini akan disimpan ke dalam database dan menjadi rekam jejak laporan yang dapat dilihat kembali kapan saja oleh admin.
   
9. Tampilan Menu Lihat Laporan Admin
  
  
10. Tampilan Menu Pelapor
    ![image](https://github.com/user-attachments/assets/357fe79f-4074-4e46-8d40-0936d0cb0930)

   Tampilan menu pelapor ini adalah menu milik pelapor yang sudah berhasil masuk ke aplikasi, , pelapor akan diberikan dua pilihan utama, yaitu Buat Laporan dan Lihat Laporan. Kedua pilihan ini dirancang untuk mempermudah pelapor dalam membuat laporan jalan rusak dan memantau laporan yang sudah diajukan. Selain itu, pelapor juga dapat memilih untuk keluar dari aplikasi setelah selesai menggunakan sistem.

11. Tampilan Menu Buat Laporan
    ![image](https://github.com/user-attachments/assets/6f32a68e-3c9d-4822-9fda-1867df04565c)

    Jika pelapor memilih Buat Laporan, sistem akan meminta pengguna untuk mengisi detail laporan, seperti nama jalan, kecamatan, tingkat kerusakan jalan, dan deskripsi. Setelah data diinput, laporan akan disimpan ke dalam database. 
   
13. Tampilan Menu Lihat Laporan Pelapor
    ![image](https://github.com/user-attachments/assets/e06f5a14-6122-471b-8941-ca4f104f2f18)

14. Tampilan Filter Sesuai Tingkat Kerusakan
   ![image](https://github.com/user-attachments/assets/4f1c431e-5bd2-4f25-a989-2065905c04cf)

 Tampilan fitur filter ini berfungsi untuk menyaring laporan berdasarkan tingkat kerusakan, jadi si pelapor ini dapat memilih laporan yang sudah ada berdasarkan tingkat kerusakannya ada berat, sedang, dan ringan.


16. Tampilan Searching Nama Jalan
    ![image](https://github.com/user-attachments/assets/00441622-3794-45e4-9edf-742cfe441586)
    
    Pada tampilan fitur searching ini pelapor dapat mencari sesuai dengan nama jalan yang dilaporkan bukan hanya dari filter saja jadi pelapor dapat searching menggunakan nama jalan rusak.

    

