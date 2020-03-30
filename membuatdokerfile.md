# Membuat DockerFile

1. Pertama buat dulu file dockerfile dengan text editor
2. Kemudian kita tambahkan konfigurasi docker yang didalamnya, Saya akan menggunakan sebuah base image ubuntu.

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-17.png)

3. setelah itu kita build image nya dengan menggunakan dockerfile diatas

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-18.png)

4. setelah proses build selesai untuk Cek hasilnya bisa menggunakan perintah doker images

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-19.png)

5. kemudian kita run image tersebut dan hasilnya sesui dengan dokerfile yang sudah dibuat sebelumnya

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-20.png)

6. Setelah menjalankan image, kemudian  ketikan perintah docker -ps a maka akan dimunculkan daftar container yang sedang berjalan

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-21.png)

7. kemudian dilakukan commit docker untuk persiapan push dimana kita harus mendownload image yang kita buat menjadi local dan membuat nama, tag baru untuk image localnya

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-22.png)

8. lalu ketikan images untuk melihat daftar image yang ada

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-23.png)

9. setelah berhasil mendownload image tersebut ke lokal. sekarang kita tinggal push image tersebut ke repository dokerhub

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-24.png)

10. setelah proses push ke respository dokerhub berhasil maka hasilnya dapat dilihat di repository dokerhub

![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-25.png)
![image](https://github.com/reyhanfernanda/UTS-tcc-175610078/blob/master/gambar-26.png)