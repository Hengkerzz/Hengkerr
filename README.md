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

LANGKAH LANGKAH PENGERJAAN IntroToBurp

![burp 1](burpstep1.png)
Download burp dan standby di menu proxy

![burp 2](burpstep2.png)
salin link lalu kita masuk ke tools burp

![burp 3](burpstep3.png)
balik ke burp lalu open browser kemudian paste link

![burp 4](burpstep4.png)
jika sudah submit di web nya,lalu kembali ke tools dan lakukan foward

![burp 5](burpstep5.png)
isi kode otp

![burp 6](burpstep6.png)
hapus otp jangan sampai menghapus baris 16

![burp 7](burpstep7.png)
SELESAIIIIIIIIII 
>>>>> 89a8110 (Week0-CyberSec-TechArt)
