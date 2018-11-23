## GIT

---

![gambar](https://github.com/Apriliana2424/git-sendiri-tim/blob/master/images/git.jpg)

---

**Git** adalah version control system yang digunakan para developer untuk mengembangkan software 
secara bersama-bersama.  Git itu sebuah software, bukanlah sebuah bahasa seperti halnya HTML,CSS 
atau Js bukan pula sebuah konsep atau aturan baku dalam pemrograman.

*Fungsi utama git* adalah untuk mengatur versi dari source code yang telah dikerjakan, menambahkan 
checkpoint ketika terjadi perubahan pada kode yang telah dikerjakan dan tentunya akan mempermudah 
dalam mengetahui apa saja yang berubah dari source code itu sendiri , selain itu jika ingin 
mengembalikan Project anda dari awal dapat diambil source codenya tersebut di Git.

[https://www.dicloud.id/tutorial/articles/pengertian-apa-itu-git-dan-fungsi-dari-git](https://www.dicloud.id/tutorial/articles/pengertian-apa-itu-git-dan-fungsi-dari-git)

---

Kebanyakan operasi pada Git hanya membutuhkan berkas-berkas dan resource lokal – tidak ada informasi 
yang dibutuhkan dari komputer lain pada jaringan itu sendiri. Segala sesuatu pada Git akan melalui 
proses checksum terlebih dahulu sebelum disimpan yang kemudian direferensikan oleh hasil checksum 
tersebut. Hal ini berarti tidak mungkin melakukan perubahan terhadap berkas manapun tanpa diketahui 
oleh Git. Fungsionalitas ini dimiliki oleh Git pada level terendahnya dan ini merupakan bagian tak 
terpisahkan dari filosofi Git. kita tidak akan kehilangan informasi atau mendapatkan file yang cacat 
tanpa diketahui oleh Git.
Mekanisme checksum yang digunakan oleh Git adalah SHA-1 hash. Ini merupakan sebuah susunan string yang 
terdiri dari 40 karakter heksadesimal (0 hingga 9 dan a hingga f) dan dihitung berdasarkan isi dari 
sebuah berkas atau struktur direktori pada Git.

[https://git-scm.com/book/id/v1/Memulai-Git-Dasar-Git](https://git-scm.com/book/id/v1/Memulai-Git-Dasar-Git)

---

Secara umum Git hanya menambahkan data. Sulit untuk kehilangan suatu data yang sudah dicommit. 
Setiap developer bisa membuat branch sebagai workspacenya sehingga code tidak akan dapat bentrok. 
Pada git juga bisa ditambah komentar yang dapat mempermudah developer lain dalam mengetahui kendala 
dari developer lain.

***Untuk menggunakan git, perintah-perintah dasar git:***
* Git init : untuk membuat repository pada file lokal yang nantinya ada difolder .git
* Git status : untuk mengetahui status dari repository lokal
* Git add : menambahkan file baru pada repository yang dipilih
* Git commit : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository.
* Git push : untuk mengirimkan perubahan file setelah di commit ke remote repository.
* Git branch : melihat seluruh branch yang ada pada repository
* Git checkout : menukar branch yang aktif dengan branchyang dipilih
* GIt merge : untuk menggabungkan branch yang aktif dan branch yang dipilih
* Git clone : membuat Salinan repository local

Contoh dari software version control system adalah github, bitbucket, snowy evening, dan masih banyak lagi.
[https://idcloudhost.com/pengertian-dan-manfaat-git-bagi-developer/](https://idcloudhost.com/pengertian-dan-manfaat-git-bagi-developer/)

* ### ***Cara kerja Git (Github) Mandiri***

Dalam model fork and pull, siapapun dapat membingkai repository yang ada dan mendorong perubahan ketempat 
pribadi tanpa perlu akses ke repository sumber. Perubahan dpaat ditarik kedalam repository sumber oleh 
pengelola proyek. Repository diizinkan untuk siapa saja dengan akses push ke repository untuk membuat perubahan 
pada penarikan proyek. Model ini popular dengan proyek sumber terbuka karena mengurangi jumlah friksi untuk 
contributor baru dan memungkinkan orang untuk bekerja secara mandiri tanpa koordinasi dari awal.

* ### ***Cara kerja Git (Github) Bersama***

Dalam model repository bersama, kolabolator diberikan akses push ke satu repository bersama dan cabang topic 
dibuat ketika perubahan perlu dibuat. Permintaan tarik berguna dalam model ini ketika mereka memulai peninjauan 
kode dan diskusi umum tentang sekumpulan perubahan sebelum perubahan digabungkan ke dalam cabang pengembangan utama. 
Model ini lebih umum dengan tim kecil dan organisasi yang berkolaborasi dalam proyek – proyek swasta.

[](https://help.github.com/articles/about-collaborative-development-models/)