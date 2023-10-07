# lab2css
# M.Dzikri Hidayat
# TI 22 A1
# 312210136
# Langkah pertama pratikum CSS dasar
pertama buka VS Code maka tampilannya awal akan seperti ini. ![image](https://github.com/dzikri226/lab2css/assets/122372727/59ce9b37-8cbb-43f8-8913-dff497bdd6bc)


Selanjutnya membuat dokumen HTML, pada bagaian title uabah menjadi CSS Dasar agar tampilan judul halaman akan berubah menjadi CSS Dasar. ![image](https://github.com/dzikri226/lab2css/assets/122372727/047e14ae-0b64-4df1-a949-aba256ffec00) ![image](https://github.com/dzikri226/lab2css/assets/122372727/7005d38d-72be-42f1-a735-88bd23162ec7)



Lalu buat Kode didalam tag body seperti berikut. ![image](https://github.com/dzikri226/lab2css/assets/122372727/1910219e-fd2a-409c-bad9-2999c9eccfad)


Selanjutnya buka pada browser untuk melihat hasilnya. ![image](https://github.com/dzikri226/lab2css/assets/122372727/4d40b500-c9b7-4343-a821-f5943655afe7)


Kemudian mendeklarasikan CSS Internal, tambahkan deklarasi CSS internal pada bagian head lalu tambahkan style untuk membuat CSS internal. gambar-5

Lalu save perubahan tadi terus kembali ke browser dan refresh untuk melihat hasilnya. gambar-6

Selanjutnya menambahkan Inline CSS, untuk melakukannya tambahkan deklarasi inline CSS pada tag <p> seperti ini. gambar-7

lalu save perubahan lagi terus kembali ke browser refresh dan lihat hasilnya. gambar-8

Selanjutnya membuat CSS Eksternal, buat file baru terlebih dahulu dengan nama style_eksternal.css lalu buat deklarasi CSS seperti berikut. gambar-9

Tambahkan tag <link> pada bagian head untuk menghubungkan style_eksternal.css yang sudah dibuat tadi. gambar-10

Lalu save kembali ke browser refresh maka hasilnya seperti ini. gambar-11

Selanjutnya menambahkan CSS Selector menggunakan ID dan class selector pada file style_eksternal.css gambar-12

Lalu save lagi dan kembali ke browser dan refresh. gambar-13

Pertanyaan dan Tugas
Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Yang saya lakukan disini menambahkan hayperlink pada dokumen HTML saya lalu menambahkan juga kode pada style CSS maka hasilnya seprti ini
gambar-14

Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
Pada pendeklarasian CSS elemen h1 maka yang akan berubah adalah seluruh tag h1 pada halam web berdeda dengan #intro h1 atau tag yang ada id maka itu saja yang akan berubah pada tampilan web.
Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
Jika ada ketiga deklarasi css secara internal, css eksternal, dan inline css maka yang akan di tampilkan pada browser adalah deklarasi css inline karena memiliki prioritas tertinggi dalam aturan css cascade
contohnya : gambar-15

Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! <p id="paragraf-1" class="text-paragraf">
Ketika dalam satu tag html terdapat id dan class didalamnya maka yang akan di tampilkan oleh browser adalah deklarasi css dengan id karena id menjadi prioritas tertinggi dalam aturan css cascade sedangkan class menjadi peioritas kedua setelah id
contoh penulisan pada tag p di halaman HTML : gambar-16

contoh penulisan CSS iinternal atau eksternal gambar-17

