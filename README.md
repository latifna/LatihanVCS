# LatihanVCS
## Tugas bahasa pemrograman

### Dasar - dasar penggunaan git

1. Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email agar tidak terjadi kegagalan saat menjalankan perintah git commit
![konfigurasi](step/ss1.png)
2. Perintah 'cd' digunakan untuk masuk ke directory penyimpanan
![cd](step/ss2.png)
3. Perintah 'mkdir/git init' digunakan untuk membuat repository local
![mkdir](step/ss3.png)
4. Perintah 'echo"#isi file" >> README.md' digunakan untuk membuat file README.md
![echo](step/ss4.png)

### Cara membuat atau menambahkan file ke repository server

1. Buat akun terlebih dahulu di https://github.com ![akun](step/ss10.png)
2. Klik new repository
3. Isi nama repository dan klik create repository ![repository](step/ss11.png)
4. Perintah 'git clone[url]' digunakan untuk membuat working directory yang diambil dari repository server
![clone](step/ss5.png) ![output](step/ss6.png)
5. Langkah - langkah untuk menambahkan file ke dalam repository server ![repository_server](step/ss7.png)
- 'cd' perintah untuk masuk ke repository utama
- 'git add namafile.html' perintah untuk menambahkan file baru
- 'git status' perintah untuk melihat status file terbaru
- 'git commit -m "komentar"' perintah untuk menyimpan perubahan kedalam database git
- 'git push u- origin main' perintah untuk mengirim perubahan pada repository local menuju repository server ![output](step/ss8.png)
6. Lakukan hal yang sama ( step no 5 ) untuk update saat terjadi perubahan file pada repository server ![tampilan](step/ss9.png)