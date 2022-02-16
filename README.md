# git-github
pengertian, cara menggunakan git dan github




Version Control System (VCS) adalah sistem yang menyimpan dan mengelola rekaman perubahan dari source code

-> memungkinkan untuk bekerja berkolaborasi dengan lebih baik

-> mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi

-> memungkinkan kita untuk kembali kekeadaan sebelum perubahan (checkout)

a. Git adalah software VCS untuk merekam riwayat perubahan isi file secara local

b. GitHub adalah website layanan cloud untuk menyimpan dan mengelola project/repo git

c. istilah-istilah dalam git dan github :

Repository/repo -> folder

Hash -> penanda unik pada sebuah commit

$git init -> inisialisasi repo git menjadi master branch

$git status -> untuk mengetahui status repo kita

$git config -> untuk configurasi repo ke dalam git -$git config --global user.email "dwi@gmail.com" -$git config --global user.name "dwiaja" -$git config --list (info detail username & useremail)

Commit -> rekaman/snapshot dari repo kita -$git commit -> untuk melakukan commit -$git commit -m "menambahkan file index.html" -$git commit -am "menambahkan file index.html" (status modified)

Branch -> cabang bebas dari sebuah commit () -$git branch namebranch (membuat branch baru) -$git checkout namebranch (pindah ke branch namebranch) -$git branch --merged (mengetahui branch yang sudah di merge) -$git branch -d namebranch (menghapus branch) -$git branch -D namebranch (memaksa menghapus branch)

Merge - menggabungkan 2 branch -$git merge namebranch

chekout -> berpindah ke sebuah branch/commit yang lain -$git checkout 32cv7 -- style.css (mengembalikan file terhapus) -$git checkout 32cv7aa (kembali ke commit sebelumnya) -$git checkout namebranch (pindah ke branch namebranch)

$git add -> menambahkan file baru ke staging area -$git add index.html (untrack) -$git add . -> menambahkan semua file baru ke staging area

$git log ( mengetahui riwayat seluruh commit ) -$git log -- style.css (mengetahui riwayat commit berdasrkan file)

pull request -> meminta pemilik repo untuk mengambil perubahan yang telah kita lakukan(github)

merge conflict -> baris yang sama dirubah oleh 2 branch yang berbeda

fork -> menduplikat dari repo orang lain beserta historinya(github)

remote -> sumber yang memiliki repo 
a. clone -> mengambil repo dari remote ke lokal (github to lokal) 
-$git clone https://github.com/.................. 
-$git remote (mengetahui nama remote) 
-$git remote -v (mengetahui detail nama remote) 

b. clone -> mengambil repo dari lokal ke remote (lokal to github) 
-create new repo github (nama repo harus sama dengan nama repo lokal) 
-un checklist readme 
-$git remote add origin https://github.com/.................. 
-$git push -u origin master

$git fetch (cek commit repo diremote sampai dimana)

Pull -> mengambil commit dari repo remote(git) -$git pull

Push -> mengirimkan commit ke repo -$git push (mengirimkan commit ke remote)

$alias graph="git log --all --decorate --oneline --graph" (visual graph)


working tree -> folder tempat kita bekerja setelah melakukan perintah git init

staging area -> pemberitahuan status perubahan setelah melakukan perintah git add

history -> posisi setelah melakukan commit

visual -> insights - network (info visual alur commit)





cek folder hidden
- view
- options
- view
- show hidden files


kembali ke cmd -> esc - :q!
