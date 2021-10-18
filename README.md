# LatihananVCS
# Langkah-langkah installasi GIT
# 1. download GIT 
untuk mengunduh Git, anda bisa mengunduh file-nya terlebih dahulu di laman resminya. karena saya pakai git-scm, linknya adalah https://git-scm.com/
![Screenshot (8)](https://user-images.githubusercontent.com/90132092/137739117-c6720d3b-0c23-4c10-96d8-7001739931a5.png)
# Installasi GIT
setelah selesai mengunduh file Git, install GIT
![Screenshot (9)](https://user-images.githubusercontent.com/90132092/137740336-f5ef00d6-7231-4fd3-a7fe-4ae7b41136a8.png)
klik next terus seperti contoh di bawah
![Screenshot (10)](https://user-images.githubusercontent.com/90132092/137740725-cfed336c-c09a-4c87-a378-86d8ee527991.png)
![Screenshot (11)](https://user-images.githubusercontent.com/90132092/137740757-ea18efd3-8f9c-4e68-b00b-47a80e6cfaf3.png)
![Screenshot (22)](https://user-images.githubusercontent.com/90132092/137741020-be6a7de0-1064-4280-a86a-3be1ed35c33a.png)
![Screenshot (23)](https://user-images.githubusercontent.com/90132092/137741062-69b7d583-f52f-46dd-aebb-991e68c7bf81.png)
lalu klik button install seperti gambar di bawah
![Screenshot (24)](https://user-images.githubusercontent.com/90132092/137741950-56cf05d2-f088-4c3a-8e72-b92ce147c7d9.png)
tunggu hingga proses installasi selesai
![Screenshot (25)](https://user-images.githubusercontent.com/90132092/137742225-71e2c62a-1353-44d3-b84e-39c255387b78.png)
selamat! installasi berhasil
![Screenshot (26)](https://user-images.githubusercontent.com/90132092/137742835-dd5dddd6-b1ec-4e78-addc-de5f55933d8b.png)
# setelah proses installasi selesai, lalu buat akun GIT. Jika Anda belum memiliki akun, anda bisa melakukan sign up, jika sebelumnya telah memiliki akun github maka anda tinggal log in saja 
![Screenshot (29)](https://user-images.githubusercontent.com/90132092/137742879-541b8be5-8ada-4775-860b-9ad32d38c978.png)
![Screenshot (30)](https://user-images.githubusercontent.com/90132092/137743699-6d62f845-5353-45a5-b807-c1abb6c31812.png)
# setelah selesai login/sign up di GITHUB, anda bisa langsung membuat file repository baru, seperti gambar dibawah ini
![Screenshot (32)](https://user-images.githubusercontent.com/90132092/137742961-fd7e5278-d3b8-4b93-a308-fb000004f74b.png)
# isikan repository name sesuai kebutuhan anda, lalu pilih repository untuk jadi file public atau private, setelah itu centang pilihan add a readme file, lalu klik create repository
![Screenshot (33)](https://user-images.githubusercontent.com/90132092/137743000-400a0a83-3216-4f20-8219-2e4861c6b827.png)
# cara penggunaan git
Apa itu Git?
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
# Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut
git config --global user.name "username"
git config --global user.email "email"
![Screenshot (34)](https://user-images.githubusercontent.com/90132092/137753993-ebd6e6bf-8b25-4e8c-a239-8ea1313fe532.png)
# jalankan perintah git init. untuk membuat repository local
git init
![Screenshot (35)](https://user-images.githubusercontent.com/90132092/137754034-95456c46-f947-488d-b99a-57a75e7d3c44.png)
# Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
echo "#User" >> README.md
![Screenshot (36)](https://user-images.githubusercontent.com/90132092/137754105-7e659ec7-084c-443a-8479-8b7bb9cb70f3.png)
# Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
git add README.md
git add .
![Screenshot (37)](https://user-images.githubusercontent.com/90132092/137754129-b9bfc05f-0cf2-41d6-846c-599cc98d84f5.png)
# Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu adalah nama kommentar setiap kita mencommit project
git commit -m "menambahkan Project"
![Screenshot (38)](https://user-images.githubusercontent.com/90132092/137754163-632c4388-fe1d-4a28-82ea-4326965b939c.png)
# untuk membuat working directory yang diambil dari repositry sever gunakan perintah git clone [url]
![Screenshot (39)](https://user-images.githubusercontent.com/90132092/137754186-2071a0b7-d323-4cd8-bb00-7b1375e162c2.png)
