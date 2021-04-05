# Praktikum 2 - Pemrograman Web (CSS Dasar)

### Sigit Ardiansyah - 311910627
### TI.19.A.2

## Langkah 1
Membuat dokumen html sebagai berikut:
![2 1](https://user-images.githubusercontent.com/56240134/113570267-3702c800-963e-11eb-9132-ad4e5b138511.png)

## Langkah 2
Menambahkan deklarasi CSS Internal pada bagian `<head>` dokumen.
![2 2](https://user-images.githubusercontent.com/56240134/113570277-3a964f00-963e-11eb-967f-892463e79f5a.png)

## Langkah 3
Menambahkan deklarasi inline CSS pada tag `<p>`.
![2 3](https://user-images.githubusercontent.com/56240134/113570278-3b2ee580-963e-11eb-9584-6bf199f46bb5.png)

## Langkah 4
Membuat file CSS eksternal dan menambahkan tag `<link>` pada bagian `<head>` dalam dokumen html untuk memuat dokumen css eksternal tersebut.
![2 4](https://user-images.githubusercontent.com/56240134/113570281-3c601280-963e-11eb-847c-a8b4d9673441.png)

Berikut tampilan setelah browser direfresh.
![2 5](https://user-images.githubusercontent.com/56240134/113570283-3d913f80-963e-11eb-9908-8f5b8671120c.png)

## Langkah 5
Menambah CSS Selector dengan menggunakan ID dan Class Selector pada dokumen css eksternal.
![2 6](https://user-images.githubusercontent.com/56240134/113571351-703c3780-9640-11eb-9b22-96518a29321b.png)

# Pertanyaan dan Tugas
### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![2 7](https://user-images.githubusercontent.com/56240134/113570292-3ff39980-963e-11eb-9155-d20406022053.png)

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
* Pendeklarasian CSS elemen h1 akan mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.

### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Jika deklarasi ketiga jenis CSS berada pada elemen yang sama (contoh = ukuran font), maka deklarasi inline css lah yang akan ditampilkan oleh browser.

### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Kedua deklarasi tersebut akan tampil, tapi deklarasi selector id lah yang akan ditampilkan jika terdapat deklarasi pada elemen yang sama.
![2 8](https://user-images.githubusercontent.com/56240134/113573231-eaba8680-9643-11eb-8d31-3ddba9d5af56.png)
