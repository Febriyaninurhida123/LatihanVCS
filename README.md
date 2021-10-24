# LatihananVCS
## Langkah-langkah installasi GIT
### 1. download GIT 
untuk mengunduh Git, anda bisa mengunduh file-nya terlebih dahulu di laman resminya. karena saya pakai git-scm, linknya adalah https://git-scm.com/
[img]screenshot/screenshot 8.png
### 2. Installasi GIT
setelah selesai mengunduh file Git, install GIT
![img](screenshot(9).png)
klik next terus seperti contoh di bawah
![img](screenshot(10).png)
![img](screenshot(22).png)
![img](screenshot(23).png)
lalu klik button install seperti gambar di bawah
![img](screenshot(24).png)
tunggu hingga proses installasi selesai
![img](screenshot(25).png)
selamat! installasi berhasi
![img](screenshot(26.png)
## setelah proses installasi selesai, lalu buat akun GITHUB. Jika Anda belum memiliki akun, anda bisa melakukan sign up, jika sebelumnya telah memiliki akun github maka anda tinggal log in saja 
![img](screenshot(29).png)
![img](screenshot(30).png)
## setelah selesai login/sign up di GITHUB, anda bisa langsung membuat file repository baru, seperti gambar dibawah ini
![img](screenshot(32).png)
## isikan repository name sesuai kebutuhan anda, lalu pilih repository untuk jadi file public atau private, setelah itu centang pilihan add a readme file, lalu klik create repository
![img](screenshot(33).png)
## cara penggunaan git
Apa itu Git?
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
## Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut
git config --global user.name "username"
git config --global user.email "email"
![img](screenshot(34).png)
## Ketik pwd
pwd
![img] (screenshot (61).png)
## untuk membuat sebuah folder menjadi repository GIT kita harus masuk dulu ke dalam foldernya, nah kita buat dulu foldernya di file explorer seperti gambar di bawah
![img](screenshot (65).png)
## jika kita ingin mengetahui di dalam sebuah directory ada apa saja bisa ketik ls
ls
![img](screenshot (66).png)
## ketik cd (nama folder) untuk masuk
cd desktop
![img](screenshot(67).png)
## lalu ketik cd (nama folder) lagi untuk masuk ke folder yang telah kita buat
cd lab
![img](screenshot(68).png)
## jalankan perintah git init. untuk membuat repository local
git init
![img](screenshot(69).png)
## Untuk membuat file dapat menggunakan Text Editor, di sini saya menggunakan visual code. setelah selesai membuat filenya lalu save file pada repository. 
![img](screenshot(48).png)
## ketik git status untuk mengetahui keberadaan file baru yang telah dibuat
![img](screenshot(70).png)
## simpan file yang telah kita buat di staging area dengan cara mengetik git add .(nama file)
git add . # LatihanVCS.md
![img](screenshot(72).png)
## Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu adalah nama kommentar setiap kita mencommit project
git commit -m "menambahkan Project"
![img](screenshot(74).png)
## ketik git status untuk mengecek apakah commit berhasil
![img](screenshot(75).png)
## jika ingin mengetahui apa saja yang sudah kita lakukan ketik git log
git log
![img](screenshot(76).png)
![Screenshot (38)](https://user-images.githubusercontent.com/90132092/137754163-632c4388-fe1d-4a28-82ea-4326965b939c.png)
# untuk membuat working directory yang diambil dari repositry sever gunakan perintah git clone [url]
![Screenshot (39)](https://user-images.githubusercontent.com/90132092/137754186-2071a0b7-d323-4cd8-bb00-7b1375e162c2.png)
# sekian, terimakasih :)
