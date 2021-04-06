# Membuat Dokumen HTML
* Input CSS  Dasar sebagai Title, menambahkan tag (b= Boldt taxt) di Pemrograman Web, menambahkan tag (i= Italic text) di Universitas Pelita Bangsa

![CSS1_ST](https://user-images.githubusercontent.com/56245855/113674066-f2ca0300-96e3-11eb-8a94-bd33b80acf7e.PNG)

* Maka Outputnya : 

![CSS1](https://user-images.githubusercontent.com/56245855/113674186-1ee58400-96e4-11eb-9147-88cfd3addae5.PNG)


# Mendeklarasikan CSS Internal
* Input border-bottom: 1px solid #77CCEF;

![CSS3_ST](https://user-images.githubusercontent.com/56245855/113675445-8d771180-96e5-11eb-90ff-f3e288a49786.PNG)

* Maka Outputnya : 

![CSS2](https://user-images.githubusercontent.com/56245855/113674694-a9c67e80-96e4-11eb-8f01-351265c6e52b.PNG)


# Menambahkan Inline CSS
* Input tambahkan deklarasi inline CSS tag (p style="text-align: center; color: #ccd8e4;")

![CSS3_ST](https://user-images.githubusercontent.com/56245855/113674846-d9758680-96e4-11eb-9878-46c9bcad0b42.PNG)

* Maka Outputnya : 

![CSS3](https://user-images.githubusercontent.com/56245855/113674887-ec885680-96e4-11eb-8101-ca54106f0d47.PNG)


# Menambahkan CSS Eksternal
* Input pada file style_eksternal.css menambahkan background: #613686; (Merubah warna menjadi Ungu)

![CSS4Eksternal](https://user-images.githubusercontent.com/56245855/113676038-2e65cc80-96e6-11eb-9cd8-bcf714ca834f.PNG)

* Input tambahkan tag link untuk merujuk file css yang sudah dibuat pada bagian head Dokumen

![CSS4_ST](https://user-images.githubusercontent.com/56245855/113676184-581ef380-96e6-11eb-9c11-5aae435dbfcb.PNG)

* Maka Outputnya :

![CSS4](https://user-images.githubusercontent.com/56245855/113676363-8b618280-96e6-11eb-9541-863f67843999.PNG)


# Menambahkan CSS Selector
* Input pada file style_eksternal.css, Id Selector, Intro background: #414845; ( Untuk mengubah warna menjadi hitam)
![CSS5_sST](https://user-images.githubusercontent.com/56245855/113677344-ad0f3980-96e7-11eb-8bc6-c506e311e754.PNG)

* Maka Outputnya : 

![CSS5](https://user-images.githubusercontent.com/56245855/113677403-c0220980-96e7-11eb-942a-6db76698d734.PNG)



#  Soal

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!

# Jawaban
1. 
![CSStambahan](https://user-images.githubusercontent.com/56245855/113689446-91f6f680-96f4-11eb-8ca7-ebde02833ccc.PNG)

![tambahan2](https://user-images.githubusercontent.com/56245855/113689500-a0dda900-96f4-11eb-8138-475d2a24c084.PNG)


2. Elemen (h1) merupakan judul pada lever pertama, Ini harus menjelaskan secara ringkas tujuan konten secara keseluruhan, supaya tulisannya rata tengah, maka kita beri property text-align dengan value center. Sedangkan Intro di (h1) dia menggunakan selector id dalam file html untuk mendeklarasikan kedalam file css.
3. Css eksternal digunakan untuk menggabungkan CSS ke wibsite dengan menggabungkan file, dengan cara tersebut perubahan yang dibuat di file CSS akan tampil di website  secara keseluruhan.

![CSStambahan](https://user-images.githubusercontent.com/56245855/113691417-958b7d00-96f6-11eb-9f4e-52e094ddf850.PNG)

![Tambahan3](https://user-images.githubusercontent.com/56245855/113691439-9c19f480-96f6-11eb-8a36-8934c54978d1.PNG)

4. Semua akan menjadi satu, tetapi class mampu memanggil sekaligus atau berkali-kali pada halaman,sedangkan id  tidak bisa memanggil satu persatu.
