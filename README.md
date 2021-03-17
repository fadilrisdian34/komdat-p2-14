# Komdat-P2-14

# Aplikasi Web Agar IO


## Sekilas Tentang

Deskripsi singkat tentang aplikasi tsb.

Agar.io adalah permainan aksi MMO ynag diciptakan developer brazil yang bernama Matehus Valarades. Pemain mengontrol satu atau lebih sel melingkar di peta yang mewakili cawan Petri. Tujuannya adalah untuk mendapatkan massa sebanyak mungkin dengan memakan agar-agar dan sel yang lebih kecil dari sel pemain sambil menghindari yang lebih besar yang dapat memakan sel pemain. Setiap pemain memulai dengan satu sel, tetapi pemain dapat membagi sel menjadi dua setelah mencapai massa yang cukup, memungkinkan mereka untuk mengontrol banyak sel. Namanya berasal dari zat agar, yang digunakan untuk membiakkan bakteri. 

Game ini dirilis pertama di website pada 28 April 2015 dan  versi mobile Agar.io untuk iOS dan Android dirilis pada 24 Juli 2015 oleh Miniclip.
Versi Steam diumumkan pada 3 Mei 2015, tetapi tidak pernah dirilis

Gim ini hanya memiliki 2 aturan sederhana untuk diikuti: 
1) Anda hanya dapat mengonsumsi target yang lebih kecil dari Anda untuk mengembangkan diri, 
2) Anda harus memberi tempat yang lebih besar pada objek yang lebih besar atau Anda akan mati. 


## Instalasi

#### Prasyarat, apa saja yang harus diinstal sebelumnya.
-Window, Linux, dan Windows
-Ubuntu
-Node.js dan NPM
-Socket.io
-express

#### Langkah instalasi dalam CLI.
1. **Login kedalam server menggunakan SSH.** Pada ini kali penulis menggunakan aplikasi multipass. 
    ```
    $ ssh fadil@172.18.88.88 
    ```
2. **Install Node.js**
    ```
    $ sudo apt-get install -y nodejs
    ```
    #cek versi terbaru
    ```
    $ node -v
    ```
3. **Install npm**
    ```
    $ sudo apt install npm 
    ```
    #cek versi terbaru
    ```
    $ npm -v
    ```
5.  **Installasi Agar.io**
    ```
    $ git clone https://github.com/huytd/agar.io-clone.git
    ```
    Berpindah ke direktori agar.io-clone
    ```
    $ cd agar.io-clone
    ```
    Install npm
    ```
    $ sudo npm install
    ```


## Konfigurasi (opsional)

Setting server tambahan yang diperlukan untuk meningkatkan fungsi dan kinerja aplikasi, misalnya:
- batas upload file
- batas memori
- dll

Plugin untuk fungsi tambahan
- login dengan Google/Facebook
- editor Markdown
- dll


##  Maintenance (opsional)

Setting tambahan untuk maintenance secara periodik, misalnya:
- buat backup database tiap pekan
- hapus direktori sampah tiap hari
- dll


## Otomatisasi (opsional)

Skrip shell untuk otomatisasi instalasi, konfigurasi, dan maintenance.


## Cara Pemakaian

- Tampilan aplikasi web
- Fungsi-fungsi utama
- Isi dengan data real/dummy (jangan kosongan) dan sertakan beberapa screenshot


## Pembahasan

- Pendapat anda tentang aplikasi web ini
    - kelebihan
    - kekurangan
- Bandingkan dengan aplikasi web lain yang sejenis


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.
https://www.crazygames.com/game/agario
https://en.wikipedia.org/wiki/Agar.io
