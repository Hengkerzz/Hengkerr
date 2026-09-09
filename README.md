<<<<<<< HEAD
# Hengkerr
=======
Nama : Putu Dodik Putra Wijaya

NIM : 260530911025

Divisi : Cyber Security

Tools yang berhasil di install : Linux Ubuntu, Burp, Python

Langkah-langkah penyelesaian challenge
![langkah 1](step1.png)
Melakukan decoding pada string "CHARACTER" menggunakan perintah "base64 -d" untuk mengembalikan string ke bentuk aslinya.

![langkah 2](step1.png)
Menggunakan perintah "rev" untuk melakukan reverse atau membalikkan urutan karakter pada teks sehingga diperoleh teks dalam
urutan yang benar

![langkah 3](step2.png)
Menggunakan perintah "tr '-' '_ " untuk mengganti seluruh karakter "-" menjadi karakter "_" pada teks.

![langkah 4](step3.png)
Menggunakan perintah "tr '()' '{}'" untuk mengganti karakter "(" menjadi "{" dan karakter ")" menjadi "}" pada teks.

![langkah 5](step3.png)
Menggunakan perintah "tr 'a-zA-Z' 'n-za-mN-ZA-M'" untuk mengenkripsi atau mendekripsi teks menggunakan metode ROT13 (Rotate 13).
Perintah ini menggeser setiap huruf alfabet sebanyak 13 posisi. Karena alfabet terdiri dari 26 huruf,proses ROT13 yang dilakukan
dua kali akan mengembalikan teks ke bentuk aslinya.
>>>>>>> 89a8110 (Week0-CyberSec-TechArt)
