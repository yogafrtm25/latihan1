**Hallo nama saya Yoga Pratama. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
  
  ![Screenshot (6)](https://user-images.githubusercontent.com/115678171/196095595-564d6bc7-aa0e-421f-9927-a8e8eb811b0c.png) *Download aplikasinya sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.38.0.windows.1

  ![Screenshot (7)](https://user-images.githubusercontent.com/115678171/196095865-d51a47fc-5a93-43f4-b6e3-c6623d5a7a4d.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

![Screenshot (9)](https://user-images.githubusercontent.com/115678171/196096049-f92342ef-8a20-43f7-abca-53eeb670fc44.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### _Membuat repositori baru_

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git



- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![Screenshot (11)](https://user-images.githubusercontent.com/115678171/196099791-d2488348-e970-4a2e-aa65-fe479f299c00.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

 ![Screenshot (13)](https://user-images.githubusercontent.com/115678171/196099567-96395dc4-629c-478d-ad99-f20ad1cde4ef.png)

### _Membuat Repository Local_

- Lalu kita buka file explorer pilih dilocal disk C (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .
![Screenshot (12)](https://user-images.githubusercontent.com/115678171/196100034-dc4a102b-626f-4571-b8e8-a6a12ea1de6c.png)


- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.email “nama_user”**
      **$ git config --global user.name “nama_user”**
 ![Screenshot (14)](https://user-images.githubusercontent.com/115678171/196101224-2308182a-a7ce-413a-adc0-83148f8bf19b.png)


- Buatlah direktori baru dengan menggunakan perintah *" mkdir lab_pemrograman1 "*  LALU *" cd lab_pemrograman1![Screenshot (15)](https://user-images.githubusercontent.com/115678171/196101511-d554c813-b80c-4457-8b6b-6d6bd7f3a1cf.png)
 "*.

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
   ![Screenshot (16)](https://user-images.githubusercontent.com/115678171/196101754-f4f4a9b9-1d59-42d4-980a-452a7ab1c6e8.png)


-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

   ![Screenshot (17)](https://user-images.githubusercontent.com/115678171/196102685-cec2e8cf-0eb4-4bcc-a604-1968efff1608.png)


 ##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.
  ![Screenshot (18)](https://user-images.githubusercontent.com/115678171/196102839-492b2b51-f2c2-4b5c-8932-ec8ee41bb0bd.png)


- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/yogafrtm25/latihan1.git
   ![Screenshot (3)](https://user-images.githubusercontent.com/115678171/196103489-d9a8b659-aacf-4c7b-ab6a-7441d883576c.png)


 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![Screenshot (3)](https://user-images.githubusercontent.com/115678171/196103551-4b9cc31f-55ee-4449-a977-ac7db030c17f.png)


 ##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/yogafrtm25/latihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah _“ls -1"_
  ![Screenshot (3)](https://user-images.githubusercontent.com/115678171/196103594-212dc1dc-35fe-4620-b459-8e8b8cb987d8.png)


-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**.
