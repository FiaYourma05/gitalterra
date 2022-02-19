# __Summary Session 2 Version Control And Branch Management__

ada beberapa point yang didapatkan pada session ini yaitu :

<hr>

1. Versioning adalah mengatur versi dari source code program, ini dilakukan agar seseorang tidak perlu melakukan perubahan dengan mengunakan banyak file. Salah satu bentuk version control system yang popular digunakan para developer untuk mengenmbangkan software secara bersama-sama adalah git.
2. Untuk melakukan setting up pertama kali pada git, perlu dilakukan init  dengan memasukkan username dan email dari akun github. Ada beberapa syntax dasar untuk melakukan operasi di github, seperti :
- Untuk membuat file bisa menggunakan 
```
$ git add <nama directory>
```
- Untuk melakukan publish file ke github bisa menggunakan syntax 
```
$  git commit –m “add cofig file”.
```
- Untuk mengecek repository pada github bisa dilakukan dengan syntax 
```
$ git log –oneline
```
- Untuk berpindah repository atau bisa menggunaka syntax 
```
$ git checkout nama_repository
```

3. Branch adalah turunan dalam suatu repository untuk memudahkan proses pengeditan source code. Untuk membuat branch dapat dilakukan dengan syntax “$ git branch <nama branch>. Selain itu github juga memiliki suatu fitur  yang bisa memberikan akses untuk kita mengubah source code program orang lain yang salah, atas persetujuan pemilik source code tersebut. Fitur ini adalah fitur pull and request.