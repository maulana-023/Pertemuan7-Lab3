## Tugas 
Repository ini dibuat untuk memenuhi tugas Pertemuan 7 - Bahasa Pemrograman.
<hr>
Nama    : Maulana Muhamad

NIM     : 312010188

Kelas   : TI.20. A.1
<hr>

# Modul Pratikum 1 
## Latihan 1

![pratikum 1 - soal Latihan 1](pict/gambar-1.png)

```python
for row in range(0, 10):
    for col in range(0, 10):
        num = row + col
        if num < 10:
            empty = "  "
        else:
            if num < 100:
                empty  = " "
        print(empty, num, end = '')
    print()
```

setelah syntax diatas di run, maka hasilnya sperti gambar dibawah ini :

![pratikum 1 Hasil Latihan 1](pict/gambar-2.png)

## Latihan 2

![pratikum 1 Hasil Latihan 1](pict/gambar-3.png)

```python
    import random
    print(40*"=")
    print("Bilangan random yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)
```

setelah syntax diatas di run, maka hasilnya sperti gambar dibawah ini :

![pratikum 1 Hasil Latihan 1](pict/gambar-4.png)

### Penjelasan:

>syntax dibawah untuk mencari random <br>
```python 
import random
```

>dibawah ini untuk menuntukan jumblah input <br>
```python
jum = int(input("masukan nilai n : "))
```

>dibawah ini untuk menampilkan urutan sesuai data jumlah data inputan <br>
```python
angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
```