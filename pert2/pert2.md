# Tipe Data
> adalah kategori data yang akan diproses oleh sebuah program komputer. Dengan tipe data, program dapat mengetahui cara menangani data dengan benar, seperti melakukan operasi matematika pada angka atau memanipulasi string untuk tujuan tertentu.

* Macam-macam Tipe Data :
 1. Primitif
>> 1. Tipe Data Numerik (Angka)
 adalah tipe data pemrograman yang sering digunakan pada variabel konstanta yang menyimpan sebuah nilai berupa angka. Tipe data ini terdiri dari 3 jenis :
    >> - Integer (int): Digunakan untuk menyimpan angka bulat, baik positif maupun negatif. Contoh: int x = 10;
    >> - Float: Tipe Data Float adalah Tipe data pemrograman yang digunakan untuk menyimpan angka desimal. Contoh: float y = 10.5;
    >> - Double: Sama seperti float, tetapi lebih presisi. Contoh: double z = 10.123456;

> 2. Tipe Data String (Teks)
    adalah tipe data pemrograman yang dapat menampung karakter dengan jumlah yang banyak yaitu 255 karakter.
    >> - Char: Digunakan untuk menyimpan karakter dengan  ukuran yang tetap. Contoh: char c = 'A';
    >> - Varchar: Digunakan untuk menyimpan karakter dengan ukuran yang dinamis. Contoh (SQL): VARCHAR(50)
    >> - Teks: Digunakan untuk menyimpan data teks. Contoh (SQL): TEXT

> 3. Tipe Data Boolean
    adalah sebuah tipe data yang hanya dapat menyimpan nilai true atau false. Contoh: bool isTrue = true;

2. Non-Primitif
> 4. Tipe Data Kompleks
    >> - Array: Tipe Data array adalah Tipe Data pemrograman yang digunakan untuk menyimpan kumpulan nilai dengan tipe data yang sama dalam satu struktur data. Indeks array adalah angka atau nilai yang digunakan untuk mengakses elemen tertentu dalam sebuah array. Indeks array harus berupa tipe data yang menyatakan bilangan bulat (integer) atau tipe data lain yang dapat direpresentasikan sebagai bilangan bulat. Contoh: int arr[5] = {1, 2, 3, 4, 5};
    >> - Struct: Efisiensi Pengelolaan Memori: Sebuah kumpulan variabel dengan berbagai jenis tipe data yang terintegrasi dalam satu kesatuan. 

> 5. Tipe Data Date dan Timer
    Tipe Data Date and Time adalah tipe data yang berfungsi untuk menangani tanggal atau waktu dalam pemrograman. Contoh (Java): Date tanggalHariIni = new Date();

> 6. Tipe Data Pointer
    Menyimpan alamat memori dari variabel lain. Contoh: int* ptr = &x;