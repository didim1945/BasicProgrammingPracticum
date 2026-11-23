# JOBSHEET 9 - ARRAY 1 DIMENSI

**Identitas Mahasiswa:**
* **Nama:** Dimas Wahyu Ramadhani
* **NIM:** 264107020104
* **Kelas / No. Presensi:** 1D / 12

___

## 1. TUJUAN PRAKTIKUM

Berikut adalah tujuan pelaksanaan praktikum pada bab ini:

1. Mendeklarasikan, menginstansiasi, dan menginisialisasi array 2 dimensi dalam bahasa Java. 
2. Mengakses dan mengisi elemen array 2 dimensi menggunakan indeks baris dan kolom. 
3. Memproses array 2 dimensi dengan nested loop, baik for maupun foreach. 
4. Membuat array 2 dimensi dengan panjang baris yang berbeda (*jagged array*). 
5. Menghitung nilai rata-rata per baris dan per kolom pada studi kasus nyata. 
- - -

## 2. HASIL PERCOBAAN & ANALISIS
### 2.1 Percobaan 1: Deklarasi, Inisialisasi, Mengisi, dan Menampilkan Array 2 Dimensi
#### 2.1.1 Kode Program Java
```java

```
#### 2.1.2 Hasil Running / Screenshot Output
Berikut adalah contoh tampilan *output* setelah program dijalankan:

![Percobaan 1](ArrayBilangan.png)

#### 2.1.3 Jawaban Pertanyaan / Pertanyaan Refleksi
* **Pertanyaan 1:** Apakah pengisian elemen array harus dilakukan secara berurutan mulai dari indeks ke-0? Jelaskan!
    * **Jawab:**
* **Pertanyaan 2:** Mengapa terdapat *null* pada daftar nama penonton? Jelaskan dari sisi nilai default array.
    * **Jawab:**
* **Pertanyaan 3:** Lengkapi pengisian pada langkah 3 jika ada elemen yang belum terisi, lalu jalankan kembali program.
    * **Jawab:**
* **Pertanyaan 4:** Tambahkan kode berikut setelah langkah 4. Jelaskan fungsi dari `penonton.length` dan `penonton[0].length`!
    ```java
    System.out.println(penonton.length);
    System.out.println(penonton[0].length);
    System.out.println(penonton[1].length);
    System.out.println(penonton[2].length);
    System.out.println(penonton[3].length);
    ```
    * **Jawab:**
* **Pertanyaan 5:** Apakah `penonton[0].length, penonton[1].length, penonton[2].length, penonton[3].length` memiliki nilai yang sama? Mengapa?
    * **Jawab:**
* **Pertanyaan 6:** Modifikasi kode pada pertanyaan 4 untuk menampilkan panjang setiap baris menggunakan `for` loop. Compile, run, lalu amati hasilnya.
    ```java
    System.out.println(penonton.length);

    for (int i = 0; i < penonton.length; i++) {
        System.out.println("Panjang baris ke-" + (i + 1) + ": " + penonton[1].length);
    }
    ```
    * **Jawab:**
* **Pertanyaan 7:** Modifikasi kode pada pertanyaan 5 untuk menampilkan panjang setiap baris menggunakan foreach loop. Compile, run, lalu amati hasilnya.
    ```java
    System.out.println(penonton.length);

    for (String[] barisPenonton : penonton) {
        System.out.println("Panjang baris: " + barisPenonton.length); 
    }
    ```
    * **Jawab:**
* **Pertanyaan 8:** Tambahkan kode untuk menampilkan nama penonton pada baris ke-3 (indeks 2) menggunakan `for` loop. Compile, run, lalu amati hasilnya.
    ```java
    System.out.println("Penonton pada baris ke-3: "); 

    for (int i = 0; i < penonton[2].length; i++) { 
        System.out.println(penonton[2][i]); 
    } 
    ```
    * **Jawab:** 
* **Pertanyaan 9:** Modifikasi kode pada pertanyaan 8 menjadi perulangan dengan `foreach` loop. Compile, run, lalu amati hasilnya.
    ```java
    System.out.println("Penonton pada baris ke-3: ");

    for (String i : penonton[2]) { 
        System.out.println(i); 
    } 
    ```
    * **Jawab:**
* **Pertanyaan 10:** Modifikasi kode pada pertanyaan 9 untuk menampilkan nama penonton setiap baris. Gunakan `String.join()`, compile, run, lalu amati hasilnya.
    ```java
    for (int i = 0; i < penonton.length; i++) { 
    System.out.println("Penonton pada baris ke-" + (i + 1) + ": " + 
        String.join(", ", penonton[i])); 
    } 
    ```
    * **Jawab:** 
* **Pertanyaan 11:** Menurut Anda, apa kekurangan dan kelebihan `foreach` loop dibandingkan `for` loop?
    * **Jawab:**
* **Pertanyaan 12:** Berapa indeks baris maksimmal untuk array `penonton`? Dari mana nilai itu diperoleh?
    * **Jawab:** 
* **Pertanyaan 13:** Berapa indeks kolom maksimal untuk array `penonton`? Apakah nilainya sama untuk setiap baris?
    * **Jawab:**
* **Pertanyaan 14:** Apa fungsi String.join()? Jelaskan parameter yang diterimanya.
    * **Jawab:**
---

### 2.2 Percobaan 2: Scanner dan Perulangan untuk Input dan Output Array 2 Dimensi
#### 2.2.1 Kode Program Java
```java

```
#### 2.2.2 Hasil Running / Screenshot Output
Berikut adalah contoh tampilan *output* setelah program dijalankan:

![Percobaan 2](.png)

#### 2.2.3 Jawaban Pertanyaan / Pertanyaan Refleksi
* **Pertanyaan 1:** Apakah pengisian elemen array dari Scanner harus dilakukan secara berurutan mulai dari indeks ke-0? Jelaskan!
    * **Jawab:**
* **Pertanyaan 2:** Modifikasi program agar menampilkan menu berikut:
    * **Jawab:**
* **Pertanyaan 3:** Modifikasi program untuk menangani nomor baris atau kolom yang tidak tersedia (misalnya baris 7 atau kolom 0).
    * **Jawab:** 
* **Pertanyaan 4:** Pada menu 1, tampilkan peringatan jika kursi yang dipilih sudah terisi penonton lain, lalu minta baris dan kolom kembali.
    * **Jawab:**
* **Pertanyaan 5:** Pada menu 2, jika sebuah kursi kosong (`null`), tampilkan `***` sebagai pengganti `null`.
    * **Jawab:**
---

### 2.3 Percobaan 3: Array 2 Dimensi dengan Panjang Baris Berbeda
#### 2.3.1 Kode Program Java
```java

```
#### 2.3.2 Hasil Running / Screenshot Output
Berikut adalah contoh tampilan *output* setelah program dijalankan:

![Percobaan 3](.png)

#### 2.3.3 Jawaban Pertanyaan / Pertanyaan Refleksi
* **Pertanyaan 1:** Apa fungsi dari `Arrays.toString()`?
    * **Jawab:**
* **Pertanyaan 2:** Pada kode 16, `Arrays.toString()` dipanggil pada `myNumbers[i]`. Ganti pemanggilnya menjadi `Arrays.toString(myNumbers)`, lalu compile dan jalankan. Apa yang tampil? Jelaskan!
    * **Jawab:**
* **Pertanyaann 3:** Jelaskan juga `System.out.println(Arrays.deepToString(myNumbers));`. Bandingkan hasilnya dengan Kode 16. Mengapa `deepToString()` diperlukan untuk array 2 dimensi?
    * **Jawab:**
* **Pertanyaan 4:** Apa nilai default untuk elemen array dengan tipe data `int`?
    * **Jawab:**
* **Pertanyaan 5:** Tambahkan kode berikut untuk menampilkan panjang setiap baris. Compile dan run, lalu amati hasilnya. 
    ```java
    for (int i = 0; i < myNumbers.length; i++) { 
        System.out.println("Panjang baris ke-" + (i + 1) + ": " + 
    myNumbers[i].length); 
    } 
    * **Jawab:** 
* **Pertanyaan 6:** Array `myNumbers` memiliki panjang yang berbeda untuk setiap barisnya. Apakah panjang array dapat dimodifikasi setelah diinstansiasi? Jelaskan. 
    * **Jawab:**
* **Pertanyaan 7:** Jalankan `myNumbers[0] = new int[7];` setelah instansiasi, lalu cetak `myNumbers.length` dan `myNumbers[0].length`. Bagian mana yang berubah? Mengapa?
    * **Jawab:**
---

### 2.4 Percobaan 4:  Studi Kasus SIAKAD
#### 2.4.1 Kode Program Java
```java

```
#### 2.4.2 Hasil Running / Screenshot Output
Berikut adalah contoh tampilan *output* setelah program dijalankan:

![Percobaan 4](.png)

#### 2.4.3 Jawaban Pertanyaan / Pertanyaan Refleksi
* **Pertanyaan 1:** Bagaimana jika jumlah mahasiswa dan jumlah mata kuliah berubah? Modifikasi program SIAKAD agar jumlah mahasiswa dan mata kuliah dapat ditentukan saat program berjalan.
    * **Jawab:**
---

## 3. TUGAS
### 3.1 Tugas 1: Implementasi Flowchart
Implementasikan flowchart latihan survei pada slide Dasar Pemrograman (Teori) ke dalam program Java. Data survei terdiri dari 10 responden dan 6 pertanyaan dengan jawaban 1 sampai 5. Program harus: 
* menyimpan hasil survei ke dalam array 2 dimensi; 
* menampilkan nilai rata-rata untuk setiap responden; 
* menampilkan nilai rata-rata untuk setiap pertanyaan; 
* menampilkan nilai rata-rata secara keseluruhan. 
#### 3.1.1 Kode Program Java
```java

```
#### 3.1.2 Hasil Running / Screenshot Output
Berikut adalah contoh tampilan *output* 