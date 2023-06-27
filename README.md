[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/MlDOtmfQ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11284182&assignment_repo_type=AssignmentRepo)
# Live Code 1

## Instruction

Live Code ini dikerjakan dalam format ***notebook*** isi *notebook* harus mengikuti *outline* di bawah ini:
1. Perkenalan\
   Bab pengenalan harus diisi dengan identitas
2. **Judul/Penanda Soal**\
    Sediakan *Cell* Markdown sebelum cell import pustaka yang berisi nomor soal dan judul problem yang dikerjakan di tiap soalnya. Tiap soal mengikuti format nomor 2-6.
3. *Import* pustaka yang dibutuhkan\
   *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
4. *Data Loading*\
   Bagian ini berisi proses *data loading* yang kemudian dilanjutkan dengan *explorasi data* secara sederhana.
5. *Answer*\
   Bagian ini berisi proses dalam menjawab soal.
6. Hasil\
   Pada bab terakhir ini berisi jawaban pertanyaan soal.

---

## Problems

1. Kamu adalah seorang data scientist yang bekerja di salah satu perusahaan manufaktur baterai Lithium ion. Tim produksi meminta kamu untuk mengecek apakah baterai yang mereka buat dalam kondisi bagus atau tidak. Sebelum melakukan pengecekan lebih lanjut, kamu diminta untuk menghitung hambatan/resistansi dan Daya setiap detik:


<p align="center"><img src="https://latex.codecogs.com/png.latex?R=\frac{V}{I}" title="R=\frac{V}{I}" /></p>


<p align="center"><img src="https://latex.codecogs.com/png.latex?P=VI" title="P=VI" class="center" /></p>

- R adalah Hambatan dalam satuan Ohm
- P adalah Daya dalam Watt
- I adalah kuat arus dalam satuan Ampere
- V adalah tegangan dalam satuan Volt

a. Buatlah dua fungsi eksplisit masing-masing memuat perhitungan hambatan (R) dan daya (P) yang nantinya akan digunakan untuk perhitungan

b. Buat kolom baru dengan nama kolom R/P berisikan hasil perhitungan daya/hambatan dengan kriteria untuk Kapasitas >=2.5 hitung daya, Kapasitas <2.5 hitung nilai hambatan. (**Hint:** Gunakan for loop dan if statement untuk mengerjakan perintah nomor b, kamu bisa menggunakan list untuk menyimpan perhitungan sementara, setelahnya dapat dimasukkan ke kolom R/P).

c. Hitunglah rata-rata nilai kapasitas untuk arus = 1 Ampere dan cycle ganjil.


## Dataset
Dataset dapat diakses pada link berikut: https://github.com/fahmimnalfrzki/Dataset/blob/main/NMC1-9.xlsx?raw=true

**Keterangan kolom:**
- time(s): Detik ke- pengukuran
- V_m: Voltage/tegangan yang terukur tiap waktu
- Current (A): Kuat arus terukur tiap waktu
- Cycle: Nomor siklus charge-discharge baterai
- Cap: Kapasitas baterai tiap waktu

---

## Assignment Rubrics

### Code Review

|      KEY COMPONENT      |                                               PREREQUISITES                                              |                                                               CRITERIA                                                              | POINTS | TOTAL |
|:-----------------------:|:--------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------:|:------:|:-----:|
|       Data Loading      | Siswa mampu memuat data menggunakan Pandas dengan sempurna                                               | Siswa mampu memuat data dengan pd.read_csv/pd.read_excel sesuai dengan format data                                                  |    1   |   2   |
|                         |                                                                                                          | Siswa dapat memuat data dengan benar sampai tidak ada pesan error dan data termuat dengan baik (dibuktikan dengan menampilkan data) |    1   |       |
|         Looping         | Siswa mampu menerapkan looping sesuai dengan instruksi pada soal                                         | Siswa mencoba menuliskan kode looping                                                                                               |    1   |   5   |
|                         |                                                                                                          | Siswa dapat membuat looping sesuai dengan instruksi (for/while)                                                                     |    2   |       |
|                         |                                                                                                          | Siswa dapat membuat looping dengan logika yang tepat sesuai dengan persoalan                                                        |    2   |       |
|      Conditional If     | Mampu menerapkan conditional if dalam suatu kasus                                                        | Siswa mencoba menuliskan kode if-else                                                                                               |    1   |   5   |
|                         |                                                                                                          | Siswa dapat membuat conditional if statement dengan kondisi dan logika yang benar                                                   |    2   |       |
|                         |                                                                                                          | Siswa dapat membuat conditional if statement sesuai dengan persoalan dan hasilnya benar                                             |    2   |       |
| Function Implementation | Siswa mampu menerapkan function dalam suatu kasus                                                        | Siswa mencoba membuat function eksplisit atau anonim sesuai dengan penulisan yang benar                                             |    1   |   5   |
|                         |                                                                                                          | Siswa dapat membuat function yang benar sesuai dengan instruksi soal                                                                |    2   |       |
|                         |                                                                                                          | Siswa dapat menggunakan/mengimplementasikan function yang sudah dibuat pada persoalan                                               |    2   |       |
|       Pandas Query      | Siswa mampu mengimplementasikan pandas query alam pengolahan data                                        | Siswa mencoba membuat pandas Query dengan df.query atau slicing biasa dengan [ ]                                                    |    2   |   5   |
|                         |                                                                                                          | Siswa mampu membuat pandas query dengan kondisi yang benar, sesuai dengan instruksi soal                                            |    3   |       |
|       Readability       | Semua cell di notebook terdokumentasikan dengan baik dengan markdown pada tiap cell ntuk penjelasan kode |                                                  Student menuliskan Nama dan Batch                                                  |    1   |   4   |
|                         |                                                                                                          |                                       Student menuliskan Objective tugas dengan bahasa sendiri                                      |    1   |       |
|                         |                                                                                                          |       Semua markdown dan heading digunakan secara tepat sehingga notebook rapih dan dapat dengan mudah dicerna dan ditelusuri       |    1   |       |
|                         |                                                                                                          |                              Student dapat memberikan penjelasan singkat pada cell code dengan komentar                             |    1   |       |

---

```{admonition} Total Points
**26**
```
