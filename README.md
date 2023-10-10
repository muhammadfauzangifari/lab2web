# Lab2 PEMOGRAMAN WEB

# CSS Dasar

Nama    : Muhammad Fauzan Gifari

NIM     : 312210428

Kelas   : TI.22.A.1

# Intruksi Praktikum

1. Persiapkan text editor misalnya VSCode
   
2. Lalu buat file baru terlebih dahulu, dengan nama "lab2_css_dasar.html"

3. Buat struktur dasar dari dokumen HTML

4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya

5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/    

# Langkah-Langkah Praktikum

1. Pertama kita buat dokumen HTML seperti gambar berikut

![Screenshot (228)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/299b41e7-7e4d-4c4c-875c-3054a02cb9f6)

2. Setelah itu kita langsung run untuk melihat hasilnya, seperti gambar berikut

![Screenshot (229)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/6a506095-9e87-4f9b-92d0-590cb33b2b1e)

3. Lalu kita akan membuat deklarasi CSS Internal seperti gambar berikut

![Screenshot (230)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/70031019-93d4-448b-8a68-e631d85aabd2)

4. Selanjutnya kita akan run kembali untuk melihat hasilnya, seperti gambar berikut

![Screenshot (231)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/eb279728-8d1c-4fe4-b9de-ba89458405a6)

5. Setelah itu tambahkan deklarasi inline CSS pada tag < p > seperti berikut.

![Screenshot (233)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/50cc6f61-ce18-47c5-bd5b-d484b786b966)

6. Kemudian kita run kembali untuk melihat hasil yang terbarunya, seperti gambar berikut

![Screenshot (234)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/e545252f-a3a8-4e49-95d1-25937e926905)

7. Selanjutnya kita buat CSS Eksternal, buat file baru terlebih dahulu dengan nama file "style_eksternal.css" seperti gambar berikut

![Screenshot (232)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/e288376e-c616-4ddf-b054-dc16d2c8e672)

8. Selanjutnya membuat deklarasi CSS seperti gambar dibawah

![Screenshot (235)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/667555e0-29c1-46ac-9074-7dc5986063e5)

9. Kemudian tambahkan tag < link > untuk merujuk file css yang sudah dibuat pada bagian < head > seperti gambar berikut

![Screenshot (236)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/66417d92-fcf2-4557-9316-9fb8d5849759)

10. Setelah itu kita coba dirun kembali untuk melihat hasilnya, seperti gambar dibawah

![Screenshot (237)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/19035ebd-2627-44f6-b920-3421a685d652)

11. Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file "style_eksternal.css",
tambahkan kode berikut.

![Screenshot (240)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/4cfbbc78-3350-45b0-9061-ce926b5b8009)

12. Lalu dirun kembali untuk melihat hasil yang terbarunya seperti dibawah ini

![Screenshot (239)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/9ce429bf-6ed7-405e-b66f-87efb4de357d)

13. Kemudian lakukan validasi dokumen CSS dengan cara mengakses https://jigsaw.w3.org/css-validator/ seperti gambar berikut

![Screenshot (227)](https://github.com/amandaaaapn/Lab2Web/assets/115678845/08ffe9d2-2fa1-453f-94f1-53d751ca21c3)

Pertanyaan
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

   jawab :

    Pada contoh ini, terdapat elemen `<h2> dengan class "title"` dan elemen `<p> dengan class "text"`. Class tersebut akan digunakan sebagai selector dalam CSS untuk mengubah properti dan nilai. Dalam file CSS (style.css), terdapat aturan CSS yang dideklarasikan untuk class `"title" dan "text"`. Aturan tersebut mengubah properti `"color"` pada elemen dengan class tersebut. Anda dapat mengubah nilai properti `"color"` pada file CSS sesuai keinginan Anda untuk melihat perubahan yang terjadi pada judul `(h2) dan paragraf (p)` dalam hal warna teks.

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

   jawab :

   - h1 {...} : Deklarasi ini akan merubah semua elemen "h1".

   - intro h1 {...} : Deklarasi ini lebih spesifik, maksud nya adalah pendeklarasian yang mengacu kepada 
     pemberian atribut pada elemen "h1" dengan menambahkan id "intro".

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

   jawab :

   Ketika kita mendeklarasikan secara bersamaan antara INTERNAL EKSTERNAL dan INLINE yang akan ditampilkan 
   pada Browser adalah INLINE, karena INLINE memiliki prioritas dibanding EKSTERNAL atau pun INTERNAL 
   seperti contoh yang saya buat, saya membuat dokumen baru HTML kemudian saya buat Elemen {h1}yang 
   kemudian saya akan deklarasikan di CSS INTERNAL EKSTERNAL dan juga INLINE Dengan property {color} dengan 
   warna yang berbeda,jika INTERNAL {color: orange} sementara EKSTERNAL {color:aqua;} dan INLINE {color: 
   red;} yang terpanggil dibrowser adalah INLINE karena memiliki prioritas.

   Jadi yang terpanggil adalah CSS INLINE karena memiliki prioritas tinggi dibanding CSS deklarasi lainnya.
   
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya!      (    < p id="paragraf-1" class="text-paragraf" >    )


Yang terpanggil di browser adalah ID karena ID bersifat unik berbeda dengan Class. Class bisa digunakan banyak sementara ID hanya tertentu saja itu kenapa ID unik dan yang terpanggil di browser adalah ID.

# SEKIAN, TERIMA KASIH
