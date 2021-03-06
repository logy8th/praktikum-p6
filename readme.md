# Tugas Pertemuan ke-6 [Senin, 26-10-2020]

<pre>
Nama    : NAUFAL NIRWANSYAH
Kelas   : TI.20.A1
NIM     : 312010174
Dosen   : Agung Nugroho S.Kom, M.Kom
</pre>

<br>
<br>

<p align="center">
  
Daftar isi tugas sebelumnya<br>
| No. | Keterangan | Link |
| --- | --- | --- |
| 1 | Pertemuan 5 | [Link](#tugas-pertemuan-5) |
| 2 | Pertemuan 6-1 | [Link](#tugas-pertemuan-6-1) |
| 3 | Pertemuan 6-2 | [Link](#tugas-pertemuan-6-2) |
| 4 | Pertemuan 6-3 | [Link](#tugas-pertemuan-6-3) |

</p>

<br>

## Tugas Pertemuan 5
Berikut adalah tugas pada pertemuan ke - 5 = **Biodata**
<br>

```print("Please enter your full name : ")
fullname=input()
print("Please enter nickname : ")
nickname=input()
print("Please enter your NPM : ")
npm=int(input())
print("Please enter your place of birth : ")
pob=input()
print("Please enter your date of birth : ")
date=int(input())
print("Pleae enter your month of birth : ")
month=input()
print("Please enter year of birth : ")
year=int(input())
print("Please enter your phone number : ")
phone=int(input())
print("Please enter your address : ")
address=input()

dob=2020-year

print("Assalamu'alaikum. ")
print(f"Let me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM {npm}. I was born in {pob} and Iam {dob} years old. I am very glad if you want to invite my house in {address}. So don't forget to call me before with the number {phone}. \n\n Thank You ")

```
<br>

**Maka akan keluar ouput sebagai berikut :**

![P5](pertemuan5/p5.png)

<br>
Berikut Penjelasannya :


***print("please enter your full name : ")***

Source code diatas berfungsi untuk mencetak hasil / output berupa **Please enter your full name** : ".

Untuk menampilkan output string, saya menggunakan tanda petik dua didalam fungsi print(),
sedangkan jika saya ingin menampilkan output atau hasil berupa angka atau interger saya tidak perlu menggunakan tanda petik dua. Contohnya : <br>

***print("Nama saya adalah...")***
<br>***print(1234567)***

![P5](pertemuan5/sample.png)

Keterangan : <br> 
>Variable adalah sebuah wadah penyimpanan data pada program yang akan akan digunakan selama program itu berjalan. yang berfungsi sebagai variable dalam source code diatas adalah **fullname** . <br>
>Fungsi **input()** adalah untuk memasukan nilai dari layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter *(newline)*<br> 
 *(newline)*<br>

 * Untuk menghitung rumus saya menggunakan variable *DOB* yaitu 2020 (Tahun sekarang) dikurangin dengan Year of Birt, pada source code berikut :<br>
``` python
dob=2020-year
```
<br> Pada syntax/source diatas, saya menggunakan variable (dob) dimana untuk menghitung umur (variable **age** pada output), yaitu dengan rumus pada variable *dob=2020-year*
<br>

* langkah kali ini saya akan menampilkan output yang diminta oleh dosen.<br>
output pertama yang diminta Dosen adalah menampilkan salam, yaitu dengan mengetikkan syntax/source code berikut :
``` python
print("\n\n Assalamu'alaikum. ")

Keterangan :
1. Fungsi **\n** pada source code di atas adalah untuk memberi baris baru / enter / *(newline)*
2. Fungsi print() seperti dijelaskan pada point **Output** diatas.
Hasil dari source code diatas adalah seperti gambar dibawah ini :
```
![P5](pertemuan5/sample2.png) <br>

Keterangan : 
1. Fungsi huruf **f** pada perintah *print(f"....")* adalah fungsi print atau bisa memudahkan programer dalam mencetak statement dalam satu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan simbol koma( , ) atau plus ( + )<br>
2. Sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variable<br>


## Tugas Pertemuan 6-1

Berikut adalah tugas pada pertemuan ke - 6 = **Operator**
<br>

```#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
```
<br>

***Maka akan terlampir input seperti ini***
![P6-1](pertemuan6.1/p6-1.png) <br>

-   Penggunaan END
Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris.  
``` python
print('A', end='')
print('B', end='')
print('C', end='')
```
> Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :

``` python
print()
```
>Syntax dibawah ini digunakan untuk menampilkan output berupa string
``` python
print('X')
print('Y')
print('z')
```
Hasil dari source code tersebut seperti gambar dibawah ini:
<br>

![P6-1](pertemuan6.1/sample2.png)

* Penggunaan separator

>Pendeklarasian beberapa variable beserta nilainya
``` python
w,x,y,z=10,15,20,25
```

>Menampilkan hasil dari variable tiap-tiap variable
``` python
print(w,x,y,z)
```

>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (koma)
``` python
print(w,x,y,z,sep=",")
```
>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah
``` python
print(w,x,y,z,sep="")
```

>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)
``` python
print(w,x,y,z,sep=":")
```

>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah -----
``` python
print(w,x,y,z,sep="-----")
```

hasil dari syntax / source code diatas adalah seperti berikut ini : <br>
![P6.1](pertemuan6.1/sample3.png)
<br>
<br>


## Tugas Pertemuan 6-2



<br>

Berikut adalah tugas pada pertemuan ke - 6 = **String Format**

- **String Format** <br>
String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.<br>

Menggunakan souce code yang diberikan oleh dosen pengampu pada pertemmuan ini :
![P6](pertemuan6.2/sample1.png)

```
#string format 1
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```

Mari kita bahas syntax yang telah diberikan.
<br>

1. **String Format 1** <br>
Pada syntax string format 1 akan menampilkan hasil berupa 2 output. <br>
Yang pertama dari sebelah kiri akan menampilkan urutan angka dari 0 - 10, sedangkan dari sebelah kanan akan menampilkan *Operasi Aritmatika Pangkat*. <br>
Dengan ketentuan sebagai berikut, Operasi pangkat dengan angka kiri sebagai pokok. <br>
(Rumus : ** [bintang dua] ) <br>
Berikut sample output dari syntax diatas : <br>

![P6](pertemuan6.2/string1.png)

2. **String Format 2** <br>
 Pada String Format 2 akan menampilkan output berupa 2 output'an juga **(seperti String Format 1, yaitu kanan dan kiri)**<br>
 Dengan ketentuan sebagai berikut : <br>
 >Secara Default, **.format()** menggunakan rata kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan **.format()** sebagai berikut :<br> 

 ```
 print('{0:8} | {1:9}'.format('Buah','Jumlah'))
print('{0:8} | {1:9}'.format('Semongko',3.))
print('{0:8} | {1:9}'.format('Gedang',10))
```
Hasil dari syntax contoh diatas akan seperti berikut :<br>
 ![P6](pertemuan6.2/string2.png)
<br>

 >Secara Default,**.format()** menggunakan rata text ke kiri, angka ke kanan, kita dapat menggunakan opsi opsional<,^,atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan **.format()** sebagai berikut : <br>
 ```
 print('{:<30}{:10}{:>30}'.format('kiri','tengah','kanan'))
print('{:<30}{:1}{:>30}'.format(7,20,34))
```
Hasil dari syntax contoh diatas akan seperti berikut :<br>
![P6](pertemuan6.2/sttring3.png)
<br>

Untuk hasil dari **String Format 2** adalah :<br>
![P6](pertemuan6.2/string4.png)

## Tugas Pertemuan 6-3

Berikut adalah tugas pada pertemuan ke - 6 = **Konversi Nilai Variable**
<br>
Untuk pembahasan terakhir, kali ini akan menyelesaikan tugas Lab 2 dari Dosen, yaitu konversi Nilai Variable.
<br>
Berikut syntax yang diberikan oleh dosen:: <br>

![P6](pertemuan6.3/sample1.png)
```
a=input("masukkan nilai a : ")
b=input("masukkan nilai b : ")
print("variable a : ",a)
print("variable b : ",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
<br>
Maka muncul error pada output seperti berikut : <br>

![P6](pertemuan6.3/error1.png) <br>
Disitu muncul pop up error : <br>
> **TypeError: %d format: a  number is required, not str** <br>

Pada error tersebut terdapat terbaca bahwa variable tersebut a adalah string, yang seharusnya dibaca oleh system adalah Number / Interger.<br>
*bagaimana cara memperbaiki error tersebut?*<br>
Kita lihat pada baris ke 5 (di notifikasi terbaca bahwa error terletak pada baris ke 5), yaitu pemformatan **.format()** adalah interger, sedangkan jika berupa string maka akan ada tanda titik dua ("..") pada pemformatan **.format()**<br>
Kita akan terfokus pada variable a dan b. <br> 
Pada line 1 tertulis syntax : *a=input("masukan nilai a : ")* <br>
Sedangkan pada line 2 tertulis syntax : *b=input("masukan nilai b : ")* <br>
Untuk membuat inputan berupa interger/angka harus ditambahkan syntax int() pada format input(). yang seharusnya ditulis adalah : <br>
```
a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
```
<br>
Kita akan ulangi semua syntax seperti berikut : <br>

```
a=int(input("Masukkan Nilai A : "))
b=int(input("Masukkan Nilai B : "))
print("Variable A =",a)
print("Variable B =",b)
print("Hasil Penggabungan {1} & {0} = %d ".format(a,b) %(a + b))

#konversi nilai variable
a=int(a)
b=int(b)
print("Hasil Pejumlahan {1} + {0} = %d".format(a,b) %(a + b))
print("Hasil Pembagian {1} / {0} = %d".format(a,b) %(a / b))
```
<br>

Kemudian kita **RUN** kembali maka akan muncul output seperti berikut : <br>

![P6](pertemuan6.3/konversi1.png)
<br>
Setelah semua file berhasil disimpan dan dijalankan berhasil, maka selesai sudah Tugas pertemuan 6 - Bahasa pemrograman kali ini.