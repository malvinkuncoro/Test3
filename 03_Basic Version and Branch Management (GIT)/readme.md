# 03_Basic Version and Branch Management (GIT)

## Data Diri
#### Nomer urut : 1_015FLB_36
####  Nama : Malvin Kuncoro Prawira

## Summery

## Resume :
### Penjelasan Versioning
Versioning adalah sebuah kumpulan perangkat lunak yang sudah terintegrasi dan digunakan untuk membantu software engineer mengelola perubahan dalam source code dari waktu ke waktu.
Jenis jenis Version Control :
- Version Control System
- Source Code Manager
- Revision Control System

### Penejelasan GIT
Dari beberapa Version control system yang paling banyak digunakan salah salah satu nya yaitu GIT. 
Pengembangan Git dimulai pada April 2005, setelah banyak pengembang kernel Linux berhenti menggunakan BitKeeper, sebuah sistem manajemen kendali kode sumber propiertary yang telah mereka gunakan untuk mememelihara proyek Linux sejak tahun 2002.
Untuk Penginstalan GIT dapat di instal di Windows, Mac, Dan Linux.

1. Setting Up
- Git init : digunakan untuk membuat repository di file lokal
   ##### $ git init
- Git clone : perintah yang digunakan untuk mengkloning repository lokal
   ##### $ git clone <Link repository>
   ##### $ cd my-project
- Git config : menetapkan nama pengguna dan alamat surel.
   ##### $ git config --global user.name "siapa"
   ##### $ git config --global user.email "siapa"

2. Saving changes
- Git status : digunakan untuk mengetahui sebuah status dari sebuah repository lokal
   ##### $ Git status
- Git add : perintah yang digunakan untuk menambahkan file baru di repository yang dipilih.
   ##### $ git add <directory>
   ##### $ git add .
- Git commit : digunakan untuk menyimpan perubahan yang sudah dilakukan, namun tidak ada perubahan yang terjadi pada remote repository
   ##### $ git commit -m "add config file"

3. Inspecting Repository
- Git log : untuk melihat catatan log perubahan pada respositori
   ##### $ git log --online #Viewing an old revision
- Git checkout : sebuah perintah yang digunakan untuk menukar branch yang aktif dengan bracht yang sudah dipilih
   ##### $ git chekout 1aeBfb5