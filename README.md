# LatihananVCS
## Langkah-langkah installasi GIT
### 1. download GIT 
untuk mengunduh Git, anda bisa mengunduh file-nya terlebih dahulu di laman resminya. karena saya pakai git-scm, linknya adalah https://git-scm.com/
![gambar1](screenshot/ss1.png)
### 2. Installasi GIT
setelah selesai mengunduh file Git, install GIT
![gambar2](screenshot/ss2.png)
klik next terus seperti contoh di bawah
![gambar3](screenshot/ss3.png)
![gambar4](screenshot/ss4.png)
![gambar5](screenshot/ss5.png)
lalu klik button install seperti gambar di bawah
![gambar6](screenshot/ss6.png)
tunggu hingga proses installasi selesai
![gambar7](screenshot/ss7.png)
selamat! installasi berhasi
![gambar8](screenshot/ss8.png)
## setelah proses installasi selesai, lalu buat akun GITHUB. Jika Anda belum memiliki akun, anda bisa melakukan sign up, jika sebelumnya telah memiliki akun github maka anda tinggal log in saja 
![gambar9](screenshot/ss9.png)
![gambar10](screenshot/ss10.png)
## setelah selesai login/sign up di GITHUB, anda bisa langsung membuat file repository baru, seperti gambar dibawah ini
![gambar11](screenshot/ss11.png)
## isikan repository name sesuai kebutuhan anda, lalu pilih repository untuk jadi file public atau private, setelah itu centang pilihan add a readme file, lalu klik create repository
![gambar12](screenshot/ss12.png)
## cara penggunaan git
Apa itu Git?
Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.
## Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut
git config --global user.name "username"
git config --global user.email "email"
![gambar13](screenshot/ss13.png)
## Ketik pwd
pwd
![gambar14](screenshot/ss14.png)
## untuk membuat sebuah folder menjadi repository GIT kita harus masuk dulu ke dalam foldernya, nah kita buat dulu foldernya di file explorer seperti gambar di bawah
![gambar15](screenshot/ss15.png)
## jika kita ingin mengetahui di dalam sebuah directory ada apa saja bisa ketik ls
ls
![gambar16](screenshot/ss16.png)
## ketik cd (nama folder) untuk masuk
cd desktop
![gambar17](screenshot/ss17.png)
## lalu ketik cd (nama folder) lagi untuk masuk ke folder yang telah kita buat
cd lab
![gambar18](screenshot/ss18.png)
## jalankan perintah git init. untuk membuat repository local
git init
![gambar19](screenshot/ss19.png)
## Untuk membuat file dapat menggunakan Text Editor, di sini saya menggunakan visual code. setelah selesai membuat filenya lalu save file pada repository. 
![gambar20](screenshot/ss20.png)
## ketik git status untuk mengetahui keberadaan file baru yang telah dibuat
![gambar21](screenshot/ss21.png)
## simpan file yang telah kita buat di staging area dengan cara mengetik git add .(nama file)
git add . # LatihanVCS.md
![gambar22](screenshot/ss22.png)
## Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu adalah nama kommentar setiap kita mencommit project
git commit -m "menambahkan Project"
![gambar23](screenshot/ss23.png)
## ketik git status untuk mengecek apakah commit berhasil
![gambar24](screenshot/ss24.png)
## jika ingin mengetahui apa saja yang sudah kita lakukan ketik git log
git log
![gambar25](screenshot/ss25.png)

# sekian, terimakasih :)
