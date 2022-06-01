<b>TUGAS PRATIKUM 9 & 10 PERTEMUAN 11</b>

PEMROGRAMAN WEB

TEKNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : Nurokhim

NIM : 312010064

KELAS : TI.20.D1

DOSEN : Agung Nugroho,S.Kom.,M.Kom Instruksi Praktikum

<b>Langkah_Langkah Pratikum</b>

Buat file baru dengan nama header.php

![image](https://user-images.githubusercontent.com/101801920/170997813-9faffed2-7d49-4fd7-9076-6a0f11ea82dd.png)

Buat file baru dengan nama footer.php

![image](https://user-images.githubusercontent.com/101801920/170998415-e6f47c76-dd77-4112-80db-52ac34bea933.png)

Buat file baru dengan nama home.php

![image](https://user-images.githubusercontent.com/101801920/170998816-d9d7f4ff-a35c-4ebd-9c6e-30183978989d.png)

Buat file baru dengan nama about.php

![image](https://user-images.githubusercontent.com/101801920/170999451-82282268-2f40-47ed-bf90-7f12ae8278cb.png)

Tampilan <b>tab About<b/> pada browser 
  
![image](https://user-images.githubusercontent.com/101801920/171354431-16e96921-d7d1-40a4-8f4b-ed94bd3ff28d.png)
  
  Tampilan <b>tab Home<b/> pada browser 
  
  
<b>Pertanyaan dan Tugas</b>

Implementasikan konsep modularisasi pada kode program praktikum 8 tentangdatabase, sehingga setiap halamannya memiliki template tampilan yang sama.

  1). Langkah pertama buat folder baru dengan nama <b>lab9_php_modular</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171356638-6ed2cc18-c12c-43ba-b252-a533856c20ee.png)

2). kemudian ambil file dari tugas pratikum sebelumnya (pratikum 8), di sini saya ambil file index.php, tambah.php, ubah.php untuk mengimplementasi modularisasinya.dan simpan ke folder tugas9 yang ada di dalam lab9_php_modular  
  
  ![image](https://user-images.githubusercontent.com/101801920/171386792-e0f39182-2308-404d-b469-4dfdf75442be.png)

3). Kemudian buat file baru dengan nama index_header dan index_footer yang di ambil dari file bagian atas dan bawah index.php
  
  <b>Index_header</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171391367-4faed33a-3f7f-4c40-a271-80dee146e5ae.png)

  <b>index_footer</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171392185-488ac108-ce20-4655-8ded-b53d559b6b00.png)

 4).Kemudian buat file baru dengan nama tambah_header dan tambah_footer yang di ambil dari file bagian atas dan bawah tambah.php
  
  <b>tambah_header</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171393210-7f4d469f-35c4-495f-9baf-eb0e175a0800.png)
  
  ![image](https://user-images.githubusercontent.com/101801920/171393543-506420df-b7d5-42ec-858f-8333e7f5fdb3.png)
  
  <b>tambah_footer</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171394084-1ef211af-3807-4c4f-b3c2-a5a1e14424e5.png)
  
  5).Kemudian buat file baru dengan nama ubah_header dan ubah_footer yang di ambil dari file bagian atas dan bawah ubah.php
  
  <b>ubah_header</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171413584-87c80fb8-8b18-4c8b-9516-35e242ab04cc.png)

  ![image](https://user-images.githubusercontent.com/101801920/171413744-a9924de6-1309-46e1-9631-6e57763bc861.png)
  
  <b>ubah_footer</b>

  ![image](https://user-images.githubusercontent.com/101801920/171394885-1ad9aacc-f601-46a4-ac49-07f9e7060122.png)

  6). Buat file index.php, kita ambil bagian body atau content dari index.php pada praktikum 8, dan kemudian tambahkan syntax <b> <?php require('index_header.php'); ?>
  
  </b> pada bagian atas body dan pada bagian bawah body di tambahkan syntax <b> <?php require('index_footer.php'); ?> <b/>
  
  ![image](https://user-images.githubusercontent.com/101801920/171407600-7db3a796-e283-414d-95a7-3a87cc577ade.png)

  ![image](https://user-images.githubusercontent.com/101801920/171407697-94f9babf-1228-494b-b282-ebbf48825a3e.png)
  
  <b>tampilan pada browser</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171415999-338a9dad-00e7-4f06-ae5f-19b8ea0cddf2.png)

  7). Buat file tambah.php, kita ambil bagian body atau content dari tambah.php pada praktikum 8, dan kemudian tambahkan syntax <b> <?php require('tambah_header.php'); 

  ?> </b> pada bagian atas body dan pada bagian bawah body di tambahkan syntax <b> <?php require('tambah_footer.php'); ?> <b/>
  
  ![image](https://user-images.githubusercontent.com/101801920/171408629-f3c672d3-a3b9-4037-91c6-a52104b8b6d7.png)

  ![image](https://user-images.githubusercontent.com/101801920/171408859-b0d0a4f9-c6b9-4e16-8063-4dea512d101c.png)

   <b>tampilan pada browser</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171416298-f43f8577-37ab-420c-bdcc-f4a1b7dafef1.png)

  8). Buat file ubah.php, kita ambil bagian body atau content dari ubah.php pada praktikum 8, dan kemudian tambahkan syntax <b> <?php require('ubah_header.php'); 

  ?> </b> pada bagian atas body dan pada bagian bawah body di tambahkan syntax <b> <?php require('ubah_footer.php'); ?> <b/>

   ![image](https://user-images.githubusercontent.com/101801920/171414034-644f9934-9271-45fe-a666-63f8008107ba.png)

  ![image](https://user-images.githubusercontent.com/101801920/171414632-8627a05f-f1e0-4d72-b867-2054c45767c3.png)
  
  <b>tampilan pada browser</b>
  
  ![image](https://user-images.githubusercontent.com/101801920/171416567-2c422331-442f-4393-a906-51b6bae3d576.png)
