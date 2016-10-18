Apa itu Github?
Apa itu SSH ?
Apa itu organization dalam github?
Bagaimana cara mengupload file ke github?

Baiklah kali ini saya akan menjelaskan tentang github,baik itu dalam membuat ssh key,upload file ke repository,membuat organization.
Github adalah software hosting untuk sebuah proyek open source yang mengguanakn tool system revisi kontrol git ,apa maksudnya? Maksudnya adalah tool untuk mengedit code yang telah kita upload.Jadi di Github kita bisa mengupload kodingan yang telah kita buat,dan kita juga bisa melakukan editing kodingan kita yang telah diupload di github.Github bisa juga kita anggap sebagai jejaring sosialnya software developer :

SSH adalah autentifikasi akun github kita ke PC yang sedang kita gunakan,jadi ketika kita melakukan upload file ke repository,kita tidak perlu lagi memasukkan username dan password

Organization dalam github itu adalah sebuah organisasi dalam github yang membuat kita bisa berkolaborasi dengan user lain dalam github,yang tentunya user yang dapat berkolaborasi itu harus ada pada organization yang sama dengan kita.

Langkah-langkah upload file ke github:
Buat sebuah repostitory
Pada folder yang ingin di upload klik kanan lalu pilih git bash here
Kemudia pada git bash ketikkan perintah berikut:
git init
git remote add origin link repository
git pull origin master
git status
git add folder/file
git status
git add folder/file (perintah ini digunakan apabila file kita berada pada suatu foder)
git status (jika muncul:On branch master Changes to be committed) langsung ke
git commit -m "komen"
git status (jika muncul:nothing to commit, working tree clean) langsung ke
git push origin master
