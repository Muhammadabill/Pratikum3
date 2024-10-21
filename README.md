# TUGAS-BAHASA-PEMOGRAMAN-PERTEMUAN-5

# BIODATA
NAMA : MUHAMAD NABIL SATRIYA SUNTARA

KELAS : TI 24.A4

NIM : 312410365

MATKUL : BAHASA PEMOGRAMAN

#![WhatsApp Image 2024-10-21 at 20 18 42_7bab611b](https://github.com/user-attachments/assets/929e5cc2-1fc1-4080-abbf-f689b7bd4c2f)

# PEMBAHASAN MENGENAI 
# PENGGUNAAN END
# PENGGUNAAN SEREPATOR
# STRING FORMAT

## PRAKTIKUM 3
# TUGAS 1
#![WhatsApp Image 2024-10-21 at 20 18 56_f04cff40](https://github.com/user-attachments/assets/5360c763-7668-4062-aae1-c3f8c0703a52)

#![WhatsApp Image 2024-10-21 at 20 19 06_a3047272](https://github.com/user-attachments/assets/3fa58d59-6cec-498f-a3ed-10c1fb6ff4d2)
```pyhton
```print('a',end=")
```print('b',end=")
```print('c',end=")
```print()
```print('x')
```print('y')
```print('z')
```'

Parameter end dalam fungsi print () di pyhton di gunakan untuk menambahkan string("") apapun diakhir dan mengeluarkan pertanyaan print

```pyhton
```print()

secara default,fungsi print() akan mengakhiri dengan baris baru,dan akan secara otomatis karakter baris baru di akhir output

inilah akhir program tersebut

#![Screenshot 2024-10-21 193251](https://github.com/user-attachments/assets/9b0fb46b-ea92-4bff-8906-d9ba7802afb2)

## PENGGUNAAN SEREPATOR
#![WhatsApp Image 2024-10-21 at 20 19 16_68a42294](https://github.com/user-attachments/assets/039a877a-9871-4d77-8092-30fe8945e37a)
```pyhton
```w,x,y,z,10,15,20,25
```print(w,x,y,z,)
```print(w,x,y,z, sep=',')
```print(w,x,y,z, sep='')
```print(w,x,y,z, sep=':')
```print(w,x,y,z, sep='-----')

pada pyhton pengguna serepator dapat menggunakan split() atau sep yang seperti dalam kode program di atas 

serepator ini menentukan pembatasan yang di gunakan untuk memisahkan string,serepator dapat berupa karakter tunggal atau beberapa karakter.jika tidak ditentukan,maka pyhton akan menggunakan spasi sebagai pemisah.

Berikut hasil kode Program di atas
#![WhatsApp Image 2024-10-21 at 21 08 18_b37df85c](https://github.com/user-attachments/assets/a29bd597-8068-4dda-89fb-147eca32d89f)

```pyhton
```w,x,y,z, =10,15,20,25

Variable yang seperti ini menentukan parameter,jadi variable ini tidak bisa memasukan variable angka yang sudah ditentukan w = 10,x=15,y=20,z=25

```Print(w,x,y,z sep=',')

karena pemisahnya dihilangkan,kita menggunakan fungsi sepatausplit()dan kita memasukkan pemisahnya didalam string akan memunculkan cetakan yang sesuai keinginan anda dalam memisahkan sesuatu parameter

#![WhatsApp Image 2024-10-21 at 20 19 25_ed004fd9](https://github.com/user-attachments/assets/ddd95fb3-e323-449e-adda-b6572c95f051)

```print(0, 10**0)
```print(1, 10**1)
```print(2, 10**2)
```print(3, 10**3)
```print(4, 10**4)
```print(5, 10**5)
```print(6, 10**6)
```print(7, 10**7)
```print(8, 10**8)
```print(9, 10**9)
```print(10, 10**10)

```print('{0:>3} {1:>16}'.format(0, 10**0))
```print('{0:>3} {1:>16}'.format(1, 10**1))
```print('{0:>3} {1:>16}'.format(2, 10**2))
```print('{0:>3} {1:>16}'.format(3, 10**3))
```print('{0:>3} {1:>16}'.format(4, 10**4))
```print('{0:>3} {1:>16}'.format(5, 10**5))
```print('{0:>3} {1:>16}'.format(6, 10**6))
```print('{0:>3} {1:>16}'.format(7, 10**7))
```print('{0:>3} {1:>16}'.format(8, 10**8))
```print('{0:>3} {1:>16}'.format(9, 10**9))
```print('{0:>3} {1:>16}'.format(10, 10**10))

String Format adalah proses memasukan variable atau string kustom ke dalam teks yang sudah ditentukan,dan dapat digunakan untuk berbagai keperluan,seperti memasukan judul dalam grafik,menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi

```print(0, 10**0)
```print(1, 10**1)
```print(2, 10**2)
```print(3, 10**3)
```print(4, 10**4)
```print(5, 10**5)
```print(6, 10**5)
```print(8, 10**8)
```print(9, 10**9)
```print(10, 10**10)

Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsinya (**) untuk menaikkan 10 ke pangkat yang sesuai dengan angka pertama, yang bisa di bahasa manusiakan variable 0 = 10 pangkat 0, variable 1 10 pangkat 1 dan seterusnya hingga variable 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi print()

```print('{0:>3} {1:>16}'.format(0, 10**0))
```print('{0:>3} {1:>16}'.format(1, 10**1))
```print('{0:>3} {1:>16}'.format(2, 10**2))
```print('{0:>3} {1:>16}'.format(3, 10**3))
```print('{0:>3} {1:>16}'.format(4, 10**4))
```print('{0:>3} {1:>16}'.format(5, 10**5))
```print('{0:>3} {1:>16}'.format(6, 10**6))
```print('{0:>3} {1:>16}'.format(7, 10**7))
```print('{0:>3} {1:>16}'.format(8, 10**8))
```print('{0:>3} {1:>16}'.format(9, 10**9))
```print('{0:>3} {1:>16}'.format(10, 10**10))

Kode ini mencetak 11 baris dengan format {0:3} {1:16} yang di gunakan untuk mengatur format string

Pada string pertama, angka 0 di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan perataan kanan.

angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan perataan kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi print()

## KODE PEMOGRAMAN
## 3 INPUT BILANGAN

```a = int(input("masukan angka pertama: "))
```b = int(input("masukan angka kedua: "))
```c = int(input("masukan angka ketiga: "))

```if a > b and a > c:
   ```print(f"angka lebih besar adalah {a}")
```elif b > a and b > c:
    ```print(f"angka lebih besar adalah {b}")
```else:
    ```print(f"angka lebih besar adalah {c}")

Program ini akan menginputkan 3 bilangan dari a yang sampai dengan c.

```if a > b and a > c:
   ```print(f"angka lebih besar adalah {a}")

Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, output yang keluar adalah {a}

```elif b > a and b > c:
   ```print(f"angka lebih besar adalah {b}")

Dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}

```else:
    ```print(f"angka lebih besar adalah {c}")

Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar

Hasil Pemograman Tersebut
#![WhatsApp Image 2024-10-21 at 21 20 14_d47cf637](https://github.com/user-attachments/assets/bcaca521-7fb7-4619-9d27-3024c9d07caf)

Hasil VisualCode
#![WhatsApp Image 2024-10-21 at 19 22 27_47869658](https://github.com/user-attachments/assets/a92d27a7-517d-4f70-88b0-28b911807dce)

Dan Flowchart
#![WhatsApp Image 2024-10-21 at 21 29 25_1bd6824e](https://github.com/user-attachments/assets/ce1143c8-2266-4b28-9e13-f9ccc367bfc6)

## MENENTUKAN BILANGAN TERBESAR DARI N DAN BERIKAN ANGKA 0

```while True:   
    ```N = int(input("masukan angka: "))

    ```if N == 0:
        ```print(f"angaka terbesar adalah: {max}")
        ```break
    ```if N > max:
        ```max = N

Untuk menentukan bilangan terbesar dari n dalam Python, Anda bisa menggunakan fungsi max()

```max = 0

Masukkan daftar angka ke fungsi max(), Fungsi max() akan mengembalikan angka terbesar dalam daftar

Fungsi max() adalah fungsi bawaan Python yang berguna untuk menemukan nilai terbesar dalam suatu iterable atau dalam serangkaian argumen reguler.

```if N == 0:
        ```print(f"angka yang terbesar adalah: {max}")
        ```break

Fungsi ini jika Kita memasukan inputan integer yaitu 0 akan berlanjut ke fungsi break program dihentikan yang artinya selesai.

```if N > max:
        ```max = N

Jika Inputan yang kita masukan lebih besar dari fungsi max() di atas, program akan melanjutkan ke proses max = N yang artinya Angka terbesar akan Mencetak Inputan Bilangan yang kita masukan yang terbesar di cetak

```while True:

While true: adalah konstruksi perulangan dalam bahasa pemrograman Python yang memungkinkan blok kode diulang tanpa batas. dan karna di kode program diatas ada fungsi While True: Program terus berlanjut terus menerus, dan ketika kita ingin berhenti saya berikan decision N==0 dengan fungsi di bawahnya break seperti di atas yang berarti Inputan Integer yang di masukan angka 0 program akan di hentikan dan memunculkan cetakan yang terbesar

Dan Hasil Pemograman Tersebut
#![Screenshot 2024-10-21 193354](https://github.com/user-attachments/assets/a660ffc5-0435-4107-b16f-3557ae8c07ff)

Hasil VisualCode
#![Screenshot 2024-10-21 193354](https://github.com/user-attachments/assets/515b04d1-829a-40d8-9da6-cc1284faa871)

Dan Hasil Flowchart
#![WhatsApp Image 2024-10-21 at 21 27 22_c524c0d6](https://github.com/user-attachments/assets/80999607-724c-4e68-b0cc-2a728efa462c)
