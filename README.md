# LATIHAN2DPBO2023
## Identitas
- Nama  : Muhammad Azka Atqiya
- NIM   : 2100812
- Kelas : C2 2021

## Janji
Saya [Muhammad Azka Atqiya] dengan NIM 2100812 mengerjakan Latihan 2 Praktikum DPBO dalam mata kuliah [Desain Pemrograman Berorientasi Objek] untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Requirement Soal
Buatlah program berbasis OOP menggunakan bahasa pemrograman C++, Java, Python, dan PHP yang mengimplementasikan konsep Multi-level Inheritance  pada kelas - kelas tersebut:
- Mahasiswa: NIM, nama, jenis_kelamin, fakultas, prodi
- Human: NIK, nama, jenis_kelamin
- SivitasAkademik: asal_universitas, email_edu

## Desain Program 
![image](https://user-images.githubusercontent.com/90915678/220288425-5ab4eb07-9c60-48d4-9d71-f7cb1e1d6ae9.png)
### Alasan Desain
Setelah membaca mengenai sivitas akademik, saya menemukan bahwa sivitas akademik merupakan kumpulan orang-orang, maka dari itu saya menyimpulkan bahwa sivitas akademik merupakan anak dari Human.
Alasan saya memasangkan mahasiswa sebagai child dari sivitas akademik karena sivitas akademik terdiri dari mahasiswa, dosen, TU, dll sehingga sudah sangat jelas bahwa mahasiswa adalah bagian dari sivitas akademik.
### Penjelasan Kelas
- Class Human 
  - Atribut :
    - nik => nik orang
    - nama => nama orang
    - jenis kelamin => jenis kelamin orang
  - Method :
    - Human => Konstruktor
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut
   
- Class Sivitas Akademik 
  - Atribut :
    - asalUniv => asalUniv orang
    - emailEdu => email orang
  - Method :
    - SivitasAkademik => Konstruktor (disini saya juga memanggil variabel yang ada di parentnya)
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut
- Class Mahasiswa
  - Atribut :
    - nim => asalUniv orang
    - prodi => email orang
    - fakultas => fakultas orang
  - Method :
    - Mahasiswa => Konstruktor (disini saya juga memanggil variabel yang ada di parentnya, yang artinya memanggil parentnya si parent juga)
    - get... => Memanggil nilai atribut
    - set... => Assign nilai ke atribut

## Alur Program
1. Berikan masukkan 
2. Masukkan dimasukkan ke dalam variabel data
3. Kemudian print outputnya

## Dokumentasi
![image](https://user-images.githubusercontent.com/90915678/220280421-9ae89723-72a2-4cd7-b9a8-64ac6ecf549f.png)
