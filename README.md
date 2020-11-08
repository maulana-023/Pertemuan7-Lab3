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

# Modul Pratikum 2
## Latihan 1
### Membuat program menentukan nilai akhir

```python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
if akhir > 80:
 huruf = "A"
elif akhir > 70:
 huruf = "B"
elif akhir > 50:
 huruf = "C"
elif akhir > 40:
 huruf = "D"
else:
 huruf = "E"

print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
```

setelah di run, maka hasilnya seperti dibawah ini:

![pratikum 1 Hasil Latihan 1](pict/gambar-5.png)

### Penjelasan :

>Masukkan nilai yang sudah di tentukan oleh variabel "seperti nama, uts, uas,tugas"

```python
untuk, akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uts) * .4)
```

```python
if akhir > 80: Jika nilai akhir diatas 80, maka huruf = 'A'
```

```python
elif akhir > 70: dan jika nilai akhir diatas 70, maka huruf = 'B'
```

```python
elif akhir > 50: dan jika nilai akhir diatas 50, maka huruf = 'C'
```

```python
elif akhir > 40: dan jika nilai akhir diatas 40, maka huruf = 'D'
```

```python
else: selain itu maka huruf = 'E'
```

```python
cetak nilai akhir print
```
