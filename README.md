# Pratikum-6


## profil
Nama: Ricky Alfian Saputra

NIM : 312210279

Kelas: TI.22.A4


## Tugas Struktur kondisi
### Latihan 1
Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

#Masukan input 
bil1 = int (input("Masukan bilangan : "))
bil2 = int (input("Masukan bilangan : "))

#Nilai terbesar

if (bil1 > bil2):
   print("Bilangan terbesar :",bil1)

#Nilai terkecil

if (bil1 < bil2):
   print("Bilangan terbesar :",bil2)

Dibawah ini Program yg dijalankan
![](/Tugas%207/Screenshot%20(18).png)

### Latihan 2
Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

#Masukan inputan
bil1 = int(input("Bilangan ke-1: "))
bil2 = int(input("Bilangan ke-2: "))
bil3 = int(input("Bilangan ke-3: "))

#Buat variable data
data = [bil1, bil2, bil3]

#Menampilkan data
print("Data sebelum di urutkan :", data)
list.sort(data)
print("Data setelah di urutkan :", data)

list.sort Syntax ini berfungsi untuk mengurutkan data


Hasil program
![](Tugas%207/Screenshot%20(20).png)

### Tugas Perulangan
### Latihan 1
Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()

Penjelasan

1.Pendeklarasian variable

baris = 10
kolom = baris

2.Untuk perulangan baris dan kolom menggunakan for

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col        

3.Untuk menampikan hasil dari perulangan
        Agar terlihat rapih menggunakan format string rata ke kanan sebanyak 5 karakter
        Agar tidak membuat baris baru menggunakan end='' (baris)

  print("{0:>5}".format(tab), end='')
print()  

Hasil Program
![](Tugas%207/Screenshot%20(22).png)

### Latihan 2

Tampilkan n bilangan acak yang lebih kecil dari 0.5. nilai n diisi pada saat runtime anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya.

import random
print("===========================================")
print("= Bilangan acak yang lebih kecil dari 0,5 =")
print("===========================================")

jum = int( input("Masukan nilai: "))
i = 0
while i in range(jum):
    i += 1
    angkarandom = random.uniform(0,0.5)
    print("Bilangan ke :", i, " : ", angkarandom)

Hasil Program
![](/Tugas%207/Screenshot%20(24).png)

    import random Untuk membuat bilangan acak
    jum = int(input("Masukan nilai: ")) Menentukan jumlah input & di konversikan dalam bilangan bulat-dimasukan ke variable jum/jumlah
    while i in range(jum) Pengulangan
    Menampilkan urutan sesuai inputan dengan hasil di bawah 0.5

angkarandom = random.uniform(0,0.5)
    print("Bilangan ke :", i, " : ", angkarandom)


### Tugas Perulangan
## Latihan 1

Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.
print("===============================")
print("===Mencari bilangan terbesar===")
print("===============================\n")

max = 0
while True:
    a = int(input("Masukan bilangan :"))
    if max < a:
        max = a
    if a == 0:
        break

print("Bilangan terbesar adalah :", max)

Penjelasan

    max = 0 Deklarasi variable
    while True: Perulangan tak terbatas
    a = int(input("Masukan bilangan :")) Masukan inputan
    Jika max kurang dari a maka max = a, maka variable max = atau nilai yg di inputkan

    if max < a:
        max = 0
    if a == 0:
        break
print("Bilangan terbesar adalah :", max)

    print & max Menampilkan bilangan

Hasil Program
![](/Tugas%207/Screenshot%20(26).png)

