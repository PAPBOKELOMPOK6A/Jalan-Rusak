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

## 📍Relational ERD
![image](https://github.com/user-attachments/assets/5a9cad39-99cf-495a-a05b-b5ea7ae4ff5c)


## 📍Source Code dan Penjelasaan
