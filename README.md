# Assignment 1

**Nama : Tis Fidiatul Hasanah**

**NPM : G1A023023**


# A. LATAR BELAKANG

Pemrograman komputer telah menjadi elemen inti dalam berbagai aspek kehidupan saat ini. Penggunaan bahasa pemrograman dalam pengembangan perangkat lunak sangat penting untuk mengotomatiskan tugas, mengelola data, dan mencapai efisiensi dalam proses bisnis dan komputasi. Bahasa pemrograman Java, yang dikenal dengan kemampuan berorientasi objek dan portabilitasnya, telah menjadi salah satu bahasa pemrograman paling populer dalam dunia teknologi informasi, menurut James Gosling (Pencipta Java): "Java adalah bahasa pemrograman yang dirancang dengan kesederhanaan, portabilitas, dan keamanan dalam pikiran. Hal ini memungkinkan pengembang untuk fokus pada logika aplikasi mereka tanpa khawatir tentang detail-detail platform.". Penelitian ini akan mengeksplorasi penggunaan bahasa pemrograman Java dalam konteks pengelolaan array, perulangan (loop), dan struktur pemilihan (if-else statement).

Array adalah struktur data yang penting dalam bahasa pemrograman yang memungkinkan pengguna untuk menyimpan dan mengelola sejumlah besar data dengan cara yang terstruktur. Java memiliki dukungan yang kuat untuk array, yang memungkinkan pengguna untuk membuat, mengakses, dan memanipulasi data dalam bentuk array. Penelitian ini akan mengeksplorasi berbagai teknik penggunaan array dalam bahasa Java, termasuk inisialisasi, pengindeksan, dan penggunaan array dalam konteks pengembangan aplikasi.

Perulangan (loop) adalah konsep penting dalam pemrograman yang memungkinkan eksekusi berulang dari serangkaian pernyataan. Java menyediakan beberapa jenis loop, seperti loop while, loop for, dan loop do-while, yang memungkinkan pengguna untuk mengotomatiskan tugas-tugas berulang. Penelitian ini akan mengkaji penggunaan loop dalam bahasa Java, termasuk cara membuat loop, mengendalikan loop, dan menghindari potensi masalah seperti perulangan tak terbatas.

Struktur pemilihan (if-else statement) adalah alat yang memungkinkan pengguna untuk mengontrol alur eksekusi program berdasarkan kondisi yang ditentukan. Java menyediakan berbagai bentuk if-else statement yang memungkinkan pengguna untuk mengambil keputusan dalam kode mereka. Penelitian ini akan memeriksa penggunaan if-else statement dalam bahasa Java, termasuk bagaimana menguji kondisi, menggabungkan statement if-else, dan menghindari masalah seperti perangkap logika.

Penelitian tentang penggunaan bahasa pemrograman Java dalam konteks array, loop, dan if-else statement memiliki relevansi yang signifikan dalam pengembangan perangkat lunak modern. Pemahaman yang kuat tentang konsep ini dan kemampuan untuk mengimplementasikannya dengan benar dapat meningkatkan efisiensi dalam pengembangan perangkat lunak, mengurangi kesalahan, dan memungkinkan pengembangan aplikasi yang lebih kuat dan dinamis.

Selain itu, Java adalah salah satu bahasa pemrograman yang paling banyak digunakan di dunia, dan pemahaman yang mendalam tentang penggunaan array, loop, dan if-else statement dalam konteks bahasa ini adalah keterampilan yang berharga bagi para pengembang perangkat lunak, baik yang baru belajar atau yang sudah berpengalaman. Oleh karena itu, penelitian ini akan menjelaskan pentingnya konsep-konsep tersebut dalam bahasa pemrograman Java dan memberikan wawasan yang mendalam tentang cara menggunakannya dengan efektif dalam pengembangan perangkat lunak.

# B. Soal dan Pembahasan
## 1. Buatlah perulangan hingga 100 menggunakan java dengan output sebagai berikut :
 1
 
 2
 
 3
 
 4
 
 5
 
 6
 
 7
 
 8
 
 9
 
 
 (your name)
 
 (your name)
 
 (your name)

 ## Jawaban :
 <img width="614" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/87787afc-7b3e-487d-9883-809934a62995">


**Gambar 1.1**


Berikut adalah penjelasan tentang fungsi dan cara kerja setiap baris dari Gambar 1.1 di atas:

1. public class task1 {
   - Ini adalah deklarasi kelas utama dengan nama "task1".

2. public static void main(String[] args) {
   - Ini adalah metode utama (main method) dari kelas "task1". Program Java akan dijalankan dari sini.

3. String name = "Tis Fidiatul Hasanah";
   - Ini mendefinisikan sebuah variabel dengan nama "name" dan menginisialisasinya dengan string "Tis Fidiatul Hasanah".

4. String NPM = "G1A023023";
   - Ini mendefinisikan variabel "NPM" dan menginisialisasinya dengan string "G1A023023".

5. System.out.println("Nama: " + name);
   - Ini mencetak teks "Nama: " diikuti oleh isi dari variabel "name" ke layar.

6. System.out.println("NPM : " + NPM);
   - Ini mencetak teks "NPM : " diikuti oleh isi dari variabel "NPM" ke layar.

7. System.out.println("x:==================");
   - Ini mencetak teks "x:==================" ke layar.

8. for (int i = 0 ; i<=100 ; i++){
   - Ini adalah awal dari loop for. Loop ini akan berjalan dari i mulai dari 0 hingga 100, dengan i bertambah satu pada setiap iterasi.

9. if (i>= 10 ){
   - Ini adalah kondisi if yang memeriksa apakah nilai i lebih besar atau sama dengan 10.

10. System.out.println(name);
    - Jika kondisi if terpenuhi (yaitu i lebih besar atau sama dengan 10), maka kode ini akan mencetak isi dari variabel "name" ke layar.

11. else {
    - Ini adalah bagian else yang akan dieksekusi jika kondisi if tidak terpenuhi.

12. System.out.println(i);
    - Jika kondisi if tidak terpenuhi (yaitu i kurang dari 10), maka kode ini akan mencetak nilai i ke layar.

13. } 
    - Ini adalah penutup dari blok else.

14. } 
    - Ini adalah penutup dari loop for.

Kode ini mencetak nama dan NPM ke layar, kemudian mencetak "x:==================", dan selanjutnya mencetak angka dari 0 hingga 100 atau nama "Tis Fidiatul Hasanah" tergantung pada nilai i. Jika i kurang dari 10, maka angka akan dicetak, dan jika i lebih besar atau sama dengan 10, maka nama akan dicetak.


## 2. Buatlah program bebas, dengan menerapkan if else dalam perulangan while!
<img width="616" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/c9d0909d-8fa4-44a7-bad1-90a9f09a2758">


**Gambar 1.2**


Kode yang ada pada gambar 1.2 adalah program Java sederhana yang meminta pengguna untuk memasukkan bilangan bulat, kemudian menentukan apakah bilangan tersebut genap atau ganjil, dan terakhir, melakukan perulangan while untuk menghitung dari 1 hingga bilangan yang dimasukkan :

1. `import java.util.Scanner;`: Ini adalah baris yang mengimpor kelas `Scanner` dari pustaka utilitas Java, yang digunakan untuk membaca input dari pengguna.

2. `public class task2 {`: Ini adalah deklarasi kelas Java dengan nama "task2". Setiap program Java harus memiliki kelas utama yang memiliki metode `main` sebagai titik awal eksekusi.

3. `public static void main(String[] args) {`: Ini adalah metode `main`, yang merupakan titik awal eksekusi program Java.

4. `Scanner input = new Scanner(System.in);`: Ini adalah pembuatan objek `Scanner` yang digunakan untuk membaca input dari pengguna melalui keyboard.

5. `System.out.print("Masukkan sebuah bilangan bulat: ");`: Pesan ini akan ditampilkan kepada pengguna untuk meminta mereka memasukkan bilangan bulat.

6. `int bilangan = input.nextInt();`: Ini akan membaca input bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `bilangan`.

7. `input.close();`: Ini adalah langkah yang baik untuk menutup objek `Scanner` setelah selesai menggunakannya.

8. `if (bilangan % 2 == 0) { ... } else { ... }`: Ini adalah struktur pengkondisian. Program akan memeriksa apakah bilangan yang dimasukkan oleh pengguna adalah genap atau ganjil. Jika bilangan tersebut habis dibagi 2 (sisa pembagian sama dengan 0), maka program akan mengatakan bahwa bilangan tersebut adalah genap; jika tidak, program akan mengatakan bahwa bilangan tersebut adalah ganjil.

9. `System.out.println("Menggunakan perulangan while untuk menghitung dari 1 hingga " + bilangan);`: Ini adalah pesan yang menginformasikan pengguna bahwa program akan menggunakan perulangan while untuk menghitung dari 1 hingga bilangan yang dimasukkan.

10. `int i = 1;`: Variabel `i` digunakan sebagai penghitung dalam perulangan while, dimulai dari 1.

11. `while (i <= bilangan) { ... }`: Ini adalah struktur perulangan while. Program akan memasuki perulangan ini jika `i` kurang dari atau sama dengan `bilangan`.

12. `System.out.println(i); i++;`: Ini akan mencetak nilai `i` ke layar dan kemudian meningkatkannya sebesar 1 setiap kali melalui perulangan, sehingga mencetak angka dari 1 hingga bilangan yang dimasukkan oleh pengguna.

Program ini memberikan tiga informasi kepada pengguna: apakah bilangan yang dimasukkan adalah genap atau ganjil, bahwa program akan melakukan perulangan, dan hasil perulangan yang menampilkan angka dari 1 hingga bilangan yang dimasukkan.


## 3. Buatlah program zodiac dengan menggunakan fitur input dengan hasil menampilkan zodiac sesuai dengan tanggal lahir yang diinputkan !!
<img width="615" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/88e18126-3b0f-4fa3-813a-3d09b2ab36da">

**Gambar 1.3**

<img width="616" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/43e22c2d-d32c-4824-b2f8-e322dce882b0">

**Gambar 1.4**

<img width="625" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/ee4edd64-64a5-4343-9153-be4c7a6a8385">

**Gambar 1.5**

<img width="626" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/541e6d5f-84dd-4e7a-b977-c943326533cd">

**Gambar 1.6**

Kode yang ada pada Gambar 1.3, 1.4, 1.5, 1.6 diatas adalah program Java yang meminta pengguna memasukkan tanggal lahir (hari dan bulan) dan kemudian menentukan zodiak berdasarkan tanggal tersebut. Berikut adalah penjelasan langkah demi langkah:

1. `import java.util.Scanner;`: Ini adalah baris yang mengimpor kelas `Scanner` dari pustaka utilitas Java untuk membaca input dari pengguna.

2. `public class zodiak {`: Ini adalah deklarasi kelas Java dengan nama "zodiak". Kode program ini berada di dalam kelas ini.

3. `public static void main(String[] args) {`: Ini adalah metode `main`, yang merupakan titik awal eksekusi program Java.

4. `Scanner SC = new Scanner(System.in);`: Ini adalah pembuatan objek `Scanner` yang digunakan untuk membaca input dari pengguna melalui keyboard. Anda menggunakan `SC` sebagai nama objek `Scanner`.

5. `System.out.println("Masukkan tanggal lahir kamu!");`: Program mencetak pesan ini untuk meminta pengguna memasukkan tanggal lahir mereka (hari).

6. `int tgl = SC.nextInt();`: Program akan membaca bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `tgl`.

7. `System.out.println("Kamu lahir bulan berapa?");`: Program mencetak pesan ini untuk meminta pengguna memasukkan bulan kelahiran mereka.

8. `int bln = SC.nextInt();`: Program akan membaca bilangan bulat yang dimasukkan oleh pengguna dan menyimpannya dalam variabel `bln`.

9. `SC.close();`: Ini adalah langkah yang baik untuk menutup objek `Scanner` setelah selesai menggunakannya.

10. `String zodiac = "";`: Program mendeklarasikan variabel `zodiac` sebagai string kosong yang akan digunakan untuk menyimpan nama zodiak.

11. `switch (bln) { ... }`: Ini adalah pernyataan `switch` yang digunakan untuk memeriksa bulan yang dimasukkan oleh pengguna. Program akan memasuki salah satu kasus berdasarkan bulan yang dimasukkan.

12. Dalam setiap kasus, program menggunakan pernyataan `if-else` untuk memeriksa tanggal dan menentukan zodiak yang sesuai dengan bulan dan tanggal yang dimasukkan. Misalnya, jika bulan adalah 1 (Januari) dan tanggal di antara 21 dan 31, maka zodiak adalah "aquarius". Jika tidak, maka zodiak adalah "capricorn". Hal yang sama dilakukan untuk semua bulan.

13. `System.out.println("Zodiak anda adalah: " + zodiac);`: Setelah menentukan zodiak berdasarkan bulan dan tanggal yang dimasukkan, program akan mencetak zodiak tersebut ke layar.

Program ini memberikan informasi zodiak berdasarkan tanggal lahir yang dimasukkan oleh pengguna. Ini adalah contoh sederhana dari penggunaan struktur kontrol dalam Java (kasus switch dan pernyataan if-else) dan pemrosesan input pengguna.

## 4. Buatlah sebuah vriabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for !!
<img width="626" alt="image" src="https://github.com/Tisfidiatulhasanah/Tis-Fidiatul-Hasanah_G1A023023/assets/149767458/fd086da1-c1be-4321-9c44-4341a8b91b63">


**Gambar 1.7**

Kode yang ada pada Gambar 1.7 diatas adalah program Java yang menggunakan array untuk menyimpan daftar judul novel dan kemudian mencetak judul-judul novel tersebut ke layar. Berikut adalah penjelasan langkah demi langkah:

1. `public class Array {`: Ini adalah deklarasi kelas Java dengan nama "Array". Kode program ini berada di dalam kelas ini.

2. `public static void main(String[] args) {`: Ini adalah metode `main`, yang merupakan titik awal eksekusi program Java.

3. `String[] novel = {"laskar pelangi", "pulang", "bumi manusia", "selena", "cantik itu luka"};`: Ini adalah deklarasi dan inisialisasi array `novel` yang berisi daftar judul novel. Array ini dapat menyimpan beberapa string, dan dalam kasus ini, menyimpan judul-judul novel.

4. `for (int i = 0; i < novel.length; i++) { ... }`: Ini adalah perulangan `for` yang digunakan untuk mengakses dan mencetak setiap elemen dalam array `novel`. Perulangan akan berjalan dari 0 hingga panjang array `novel - 1` (indeks array dimulai dari 0).

5. `System.out.println(novel[i]);`: Dalam setiap iterasi perulangan, program mencetak elemen array `novel` pada indeks `i` ke layar menggunakan `System.out.println()`. Ini akan mencetak judul-judul novel satu per satu.

Program ini efektif dalam menampilkan daftar judul novel yang disimpan dalam array. Dengan menggunakan perulangan `for`, program dapat mengakses semua elemen array dan mencetaknya ke layar secara berurutan.
