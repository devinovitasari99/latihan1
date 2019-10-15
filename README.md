#latihan1
#cara penggunaan git
1. pada saat pertamakali menggunakan git, perlu di lakukan konfigurasi user.name dan user.email
   $ git config --global uer.name "devi novitasari"
   $ git config --global user.email "devinovitasari18072000@gmail.com"
  .konfigurasi ini bisa dilakukan untuk global repository atau individual repository
  .apabila belum dilakukan konfigurasi,akan mengakibatkan terjadi kegagalan saat menjelaskan perintah git commit 
2. congfig global repository
3. buatlah directory project praktikum pertama dengan latihan1
4. sehingga terbentuk satu directory baru di bawahnya, selanjutnya masuk kedalam directory tersebut dengan perintah cd (change directory)
5. directory aktif menjadi d:\lab_pemrograman1\latihan1
6. jalankan perintah git init, untuk membuat repository local
7. pada directory tersebut, semua perubahan pada working directory akan disimpan.
8. disini kita akan coba membuat satu file bernama READMI.md
  . $ echo "#latihan 1" >> README.md
9. setelah itu, untuk menambahkan file yang baru saja di buat gunakan git add
10. untuk menyimpan perubahan yang ada kedalam database repository local gunakan perintah git commit -m 
11. server reopsitory yang akan kita gunakan adalah https://github.com anda harus membuat akun terlebih dahulu.
12. untuk menambahkan remote reopsitoryserver gunakan perintah git remote add origin [ur1]
13. untukmengirim perubahan pada local repository ke server gunakan git push
14. untuk masuk ke nano 
    - $ cd /d enter
    - $ cd lab_pemrograman enter
    - $ cd latihan Enter
    - $ nano README.md  
