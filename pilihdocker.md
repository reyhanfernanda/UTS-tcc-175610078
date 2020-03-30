# image docker

1. Melakukan pengecekan versi docker apakah sudah berhasil diinstal atau belum
![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-01.png) 

2. kemudian kita melakukan clone/pull terhadap repository git yang didalamnya terdapat beberapa image docker dan berpindah ke direktori dengan mengetikkan perintah cd 

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-07.png) 

3. lalu image bulletinboard yang sudah di clone sebelumnya kita build

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-08.png)
![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-09.png)

4. Setelah melakukan build dan Success, selanjutnya dilakukan run images dengan docker run --publish 8000:808 --detcah --name bb bulletinboard:1.0

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-10.png)

5. buka browser kemudian ketikan localhost:8000 maka akan muncul sebuah tampilan dari image dockerbulletin board

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-12.png)

6. Setelah menjalankan image, kemudian  untuk menghentikan container sebelum melakukan stop container yang berjalan dilakukan pengecekan terlebih dahulu dengan mengetikkan perintah docker -ps a kemudian akan dimunculkan daftar container yang sedang berjalan

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-11.png)

7. dan untuk Memberhentikan container yang sedang jalan, dan menghapusnya dari list container dapat dilakukan dengan perintah docker rm --force bb

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-13.png)

8. untuk melakukan push image ke dokerhub kita harus memiliki akun dokerhub dan tempmembuatat repository untuk meletakan image tersebut

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-14.png)

9. lalu memberikan nama image sesuai dengan persyaratan share di dokerhub dan push image kedalam repository dengan perintah push

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-15.png)

10. setelah proses push ke respository dokerhub berhasil maka hasilnya dapat dilihat seperti gambar dibawah ini

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-16.png)