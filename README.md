# Aplikasi Web Agar.io

![Screenshot VS](https://user-images.githubusercontent.com/61318031/120933062-a5d5cd80-c722-11eb-91e7-61f282158577.png)

![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/judul.png)

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Cara Pemakaian](#cara-pemakaian) | [Pembahasan](#pembahasan) | [Referensi](#referensi)
:---:|:---:|:---:|:---:|:---:

## Nama Anggota Kelompok 3
| Nama               | NIM         | 
| :---               |    :----:   |    
| Fadil Risdian A    | G64180111   | 
| Ferdi B M Erari    | G64180112   | 
| Rakheda Andria P   | G64180105   | 
| M Farhan Dirhami   | G64170099   | 

## Sekilas Tentang
[`^ kembali ke atas ^`](#)

Agar.io adalah permainan aksi MMO yang diciptakan developer brazil yang bernama Matehus Valarades. Pemain mengontrol satu atau lebih sel melingkar di peta yang mewakili cawan Petri. Tujuannya adalah untuk mendapatkan massa sebanyak mungkin dengan memakan agar-agar dan sel yang lebih kecil dari sel pemain sambil menghindari yang lebih besar yang dapat memakan sel pemain. Setiap pemain memulai dengan satu sel, tetapi pemain dapat membagi sel menjadi dua setelah mencapai massa yang cukup, memungkinkan mereka untuk mengontrol banyak sel. Namanya berasal dari zat agar, yang digunakan untuk membiakkan bakteri. 

Game ini dirilis pertama di website pada 28 April 2015 dan  versi mobile Agar.io untuk iOS dan Android dirilis pada 24 Juli 2015 oleh Miniclip.
Versi Steam diumumkan pada 3 Mei 2015, tetapi tidak pernah dirilis

Gim ini hanya memiliki 2 aturan sederhana untuk diikuti: 
1) Anda hanya dapat mengonsumsi target yang lebih kecil dari Anda untuk mengembangkan diri, 
2) Anda harus memberi tempat yang lebih besar pada objek yang lebih besar atau Anda akan mati. 


## Instalasi
[`^ kembali ke atas ^`](#)

#### Prasyarat, apa saja yang harus diinstal sebelumnya.
* Window, Linux, dan Windows
* Ubuntu
* Git
* Node.js dan NPM
* Socket.io
* express

#### Software yang digunakan penulis
* Multipass 
  Digunakan sebagai SSH 
   
* Virtual box 6.1.18
  Digunakan sebagai virtual machine 
  
* Ubuntu Desktop 20.04 LTS Desktop
  
* Node.js versi 10.19.0
* NPM versi 6.14.4
* express 4.17.1
* socket.io 4.00


#### Langkah instalasi dalam CLI.
1. **Login kedalam server menggunakan SSH.** Pada ini kali penulis menggunakan aplikasi multipass. 
    ```
    $ ssh fadil@172.18.88.88 
    ```
2. **Install Node.js**
    ```
    $ sudo apt-get install -y nodejs
    ```
    #cek versi 
    ```
    $ node -v
    ```
3. **Install npm**
    ```
    $ sudo apt install npm 
    ```
    #cek versi 
    ```
    $ npm -v
    ```
4.  **Install Git**
    ```
    $ sudo apt install git
    ```
    ```
    $ git --version
    ```
5.  **Installasi Agar.io**
    Mendownload aplikasi agar io
    ```
    $ sudo git clone https://github.com/huytd/agar.io-clone.git
    ```
    Berpindah ke direktori agar.io-clone
    ```
    $ cd agar.io-clone
    ```
    Install socket.io
    ```
    $ npm install socket.io --save
    ```
    Install express 
    ```
    npm install express.io --save
    ```
    Install gulp globally (menggunakan root privileges)
    ```
    $ sudo npm install -g gulp
    ```
    Install application dependencies
    ```
    npm install
    ```
    Menjalankan server
    ```
    gulp run 
    ```
    Membuka aplikasi di browser
    ```
    https://localhost:3000
    ```
    

## Cara Pemakaian

Tampilan aplikasi web <br>
![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/1.png)

## Fungsi-fungsi utama

### Play
  
![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/play.gif)
    
Setelah menekan tombol play, maka kita akan langsung menuju ke pertandingan arena. 
  
#### Cara Bermain
- Gerakkan mouse Anda di sekitar layar untuk memindahkan sel Anda
- Makan makanan dan pemain lain untuk mengembangkan karakter Anda
- Massa pemain adalah jumlah partikel makanan yang dimakan.
- Tujuan: Mencoba menjadi sebesar mungkin dan memakan pemain lain
  
#### Peraturan Game
- Setiap pemain bergabung dalam permainan, 3 partikel makanan akan muncul.
- Setiap partikel makanan dimakan oleh pemain, 1 partikel makanan baru akan muncul kembali
- Semakin banyak makanan yang Anda makan, semakin lambat Anda bergerak untuk membuat game lebih adil untuk semua.
    
### Spectate
    
  ![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/spectate.png)
  
Tombol spectate berguna untuk masuk ke dalam arena hanya sebagai pengamat pertandingan saja 
  
### Settings
  
  ![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/2.png)
  
 Terdapat 5 pengaturan berupa centang ketika menekan tombol setting.
 * Show border : Menunjukkan garis-garis di arena pertandingan
 * Show mass   : Menunjukan mass dari player
 * Continue moving when moving is off-screen : Player akan bergerak ketika mouse di luar game agar.io
 * Rounded food Mode : Mode makan berbentuk bulat
 * Toggle Dark : Arena menjadi berwarna hitam


## Pembahasan

kelebihan
* Mudah dimainkan bagi pemula
* Pengaturan permainan mudah

kekurangan
* Performa game sedikit lambat
* Fitur sangat sedikit

## Perbandingan 
![alt text](https://github.com/fadilrisdian34/komdat-p2-14/blob/main/vs.jpg)

### Agar.io vs Slither.io

Secara tampilan, slither.io lebih baik dibandingkan dengan agar.io. Mulai dari pergerakan ular, partikel yang berchaya, dan beberapa objek lainnya yang seakan akan terlihat 3 dimensi. Namun hal ini juga menjadi kelebihan bagi agar.io karena waktu akses yang dibutuhkan lebih cepat karena desain yang lebih simpel.


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.
https://www.crazygames.com/game/agario
https://en.wikipedia.org/wiki/Agar.io

https://www.pocketgamer.com/articles/070011/agar-io-vs-slither-io-which-is-the-best-game/
https://www.gameskinny.com/9d4c1/5-reasons-slitherio-is-going-to-be-better-than-and-outlast-agario
https://www.youtube.com/watch?v=HOCuAz1sNn4
