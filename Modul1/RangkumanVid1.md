# APA ITU GIT & GITHUB?

Git dan GitHub merupakan dua platform yang bisa digunakan dengan saling independen maupun digunakan secara bersaman. Platform ini biasanya digunakan oleh programmer dalam menyusun kode script secara tim. Seluruh pekerjaan juga dapat dipantau dan dievaluasi dengan mudah karena penggunaan Version Control System (VCS).

## VCS (Version Control System)

Version Control System (VCS) adalah sebuah sistem yang melakukan source code management (SCM) )untuk mengelola perubahan di setiap dokumen, program komputer, website, dan kumpulan pemrograman lainnya.

Pada umumnya saat melakukan sesuatu dan ada perubahan, biasanya kita akan melakukan copypaste dari file dan merename file tersebut. Konsep pekerjaan tersebut dianggap tidak efisien oleh banyak developer karena kapasitas penyimpanan akan membengkak. VCS disini berfungsi untuk membantu penyimpanan berupa history tanpa menyimpan file baru, yang tersimpan hanya perubahan data. Sehingga kapasitas penyimpanan file menjadi ringan.

## GIT

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

Prosedur yang diterapkan ini dapat membantu antar divisi project untuk memantau dan menghubungkan (merge) antar ekstensi yang berbeda dengan mudah. Sehingga aplikasi yang dibuat oleh sebuah tim project dapat berfungsi tanpa menghubungkan secara manual.

Terdapat istilah commit pada Git yang berfungsi untuk menyimpan riwayat perubahan data pada file. Melalui commit, developer dapat kembali ke source code sebelumnya dengan istilah checkout.

Untuk mengoperasikan Git, kamu perlu menginstall software terlebih dahulu sehingga pekerjaan ini dapat dilakukan secara offline (tidak terkoneksi internet). Software ini juga tersedia secara gratis melalui web unduhan resminya di Git Downloading.

## GITHUB

GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git). Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-install sebuah software ke dalam perangkat keras. Hal ini memberikan keringanan penyimpanan komputer yang kita gunakan karena file project tersimpan oleh cloud GitHub.

Konsep kerja GitHub pada dasarnya sama dengan Git yaitu dapat menulis source code secara individu atau tim. User interface yang tersedia pada GitHub lebih menarik dan mudah dipahami oleh pengguna awal. Pekerjaan secara tim, pengguna juga bisa melihat siapa penulis kode dan tanggal berapa kode tersebut dibuat.

## GIT dan GITHUB

Keduanya bisa digunakan bersamaan dengan cara membuat repository github remote dengan melakukan aksi `git clone`. Setelah itu, kita bisa menggunakan aksi `git push` dan `git pull`.

## Keyword

`repository` folder project  
`commit` rekaman/snapshot repo  
`hash` penanda unik pada commit  
`checkout` berpindah ke sebuah commit  
`brach` cabang bebas dari sebuah commit  
`merge` menggabungkan brach  
`remote` sumber yang memiliki repo  
`clone` mengambil repo dari remote  
`push` mengirim commit ke repo  
`pull` mengambil commit dari repo
