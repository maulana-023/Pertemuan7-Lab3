## Tugas 
Repository ini dibuat untuk memenuhi tugas Pertemuan 7 - Bahasa Pemrograman.

Nama    : Maulana Muhamad

NIM     : 312010188

Kelas   : TI.20. A.1

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

![pratikum 1 Hasil Latihan 1](pict/gambar-2)
