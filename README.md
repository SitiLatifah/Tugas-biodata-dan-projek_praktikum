# Tugas-biodata-dan-projek_praktikum
**Nama	  	: Siti Latifah** <br>
**Nim	  	: 312010321** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	: Bahasa Pemrograman** <br>

## Tugas Pertemuan 5 (Biodata)
![Screenshot (7)](https://user-images.githubusercontent.com/73010098/98107335-fb1bd900-1ecc-11eb-87f4-585d4db60bff.png)

#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
 ``` python
#biodata Siti Latifah - 312010321

#mengambil input
namaLengkap = input ("nama lengkap:")
namaPendek = input ("nama panggilan:")
nim = input ("nim:")
tempatLahir = input ("tempat lahir:")
umur = input ("umur:")
alamat = input ("alamat:")
noHp = input ("no Hp:")

#menampilkan output
print("", end='\n')
print ("Assalamualaikum")
print ("Let me introduce my self.","My name is",namaLengkap,"but you can call me",namaPendek, ". My NIM is",nim, end='\n')
print ("I was born in",tempatLahir,"and i am",umur,"years old", end='\n')
print ("I am very glad if you want to invite my house in",alamat,".","So don't forget to call me before with the number",noHp)
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (8)](https://user-images.githubusercontent.com/73010098/98107746-8b5a1e00-1ecd-11eb-846f-16e4f03d1f63.png)


#### ANALISIS
•	Variabel adalah merupakan tempat untuk menyimpan data yang data-data tersebut dapat diambil/dipanggil kembali apabila dibutuhkan.
Pada syntak diatas namaLengkap, namaPendek, nim, tempatLahir, umur, alamat, dan noHp merupakan variabel. <br>
•	Pada program diatas kita akan menginputkan data yang akan disimpan di variabel pada #mengambil input menggunakan syntax seperti  <br>
``` pyhton
namaLengkap = input (“nama lengkap :”)
```
Pada syntax diatas namaLengkap merupakan variabel, yang isinya akan diinput dengan perintah = input (“nama lengkap: ”) . <br>

•	Pada #menampikan output untuk syntax dibawah ini
``` pyhton
print("", end='\n')
```
Fungsi print digunakan untuk mencetak output. <br>
Fungsi (“”, end =’\n’) digunakan untuk memberi jarak/garis baru/enter. <br>

•	Pada syntax
``` python
print ("Assalamualaikum")
print ("Let me introduce my self.","My name is",namaLengkap,"but you can call me",namaPendek, ". My NIM is",nim, end='\n')
print ("I was born in",tempatLahir,"and i am",umur,"years old", end='\n')
print ("I am very glad if you want to invite my house in",alamat,".","So don't forget to call me before with the number",noHp)
```
Bagian yang berada didalam tanda kutip seperti “My name is” akan ditampilkan/dicetak sama seperti statement tersebut, sedangkan pada ,namaLengkap, digunakan untuk memanggil data dari variabel namaLengkap yang telah diinputkan.

### Tugas Pertemuan 6 Lab 1
![Screenshot (14)](https://user-images.githubusercontent.com/73010098/98108318-539fa600-1ece-11eb-9496-6b42069c8dd3.png)

### PENGGUNAAN END
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan end
print ('A', end='')
print ('B', end='')
print ('C', end='')
print ( )
print ('X')
print ('Y')
print ('Z')
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (9)](https://user-images.githubusercontent.com/73010098/98109215-c8bfab00-1ecf-11eb-8684-9e71ac3e9c8f.png)

#### ANALISIS
•	Perintah end berguna untuk memberi garis baru/newline namun apabila value dari end maka statement yang dicetak tidak akan memberi garis baru seperti output diatas.

### PENGGUNAAN SEPARATOR
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print (w, x, y, z)
print (w, x, y, z, sep=',')
print (w, x, y, z, sep='')
print (w, x, y, z, sep=':')
print (w, x, y, z, sep='------')
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (10)](https://user-images.githubusercontent.com/73010098/98109359-0290b180-1ed0-11eb-86d3-3adfc30f73e3.png)


#### ANALISIS
•	Perintah separator berfungsi untuk memberi pemisah seperti koma( , ), titik dua( : )dan lain sebagainya seperti pada syntax diatas.

### PENGGUNAAN STRING
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan string 
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (11)](https://user-images.githubusercontent.com/73010098/98109567-6024fe00-1ed0-11eb-9ee7-dc97d87fbd09.png)


#### ANALISIS
•	Penggunaan string ** pada syntax diatas berfungsi untuk mencetak hasil pangkat, mulai dari 10 pangkat 0 sampai 10 pangkat 10

### PENGGUNAAN STRING FORMAT
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#string format
print ('{0:>3} {1:>16}'.format(0, 10**0))
print ('{0:>3} {1:>16}'.format(1, 10**1))
print ('{0:>3} {1:>16}'.format(2, 10**2))
print ('{0:>3} {1:>16}'.format(3, 10**3))
print ('{0:>3} {1:>16}'.format(4, 10**4))
print ('{0:>3} {1:>16}'.format(5, 10**5))
print ('{0:>3} {1:>16}'.format(6, 10**6))
print ('{0:>3} {1:>16}'.format(7, 10**7))
print ('{0:>3} {1:>16}'.format(8, 10**8))
print ('{0:>3} {1:>16}'.format(9, 10**9))
print ('{0:>3} {1:>16}'.format(10, 10**10))
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (12)](https://user-images.githubusercontent.com/73010098/98109749-aa0de400-1ed0-11eb-821d-2b158c7644b8.png)

#### ANALISIS
•	Untuk angka pada statement {0:<3} {1:<16} berfungsi untuk memberi jarak, lalu untuk tanda < dan > untuk memberikan rata kanan dan rata kiri. <br>
•	Untuk statement .format(0, 10** 0)) berfungsi untuk mencetak angka 0 dan hasil dari 10 pangkat 0 
### Tugas Pertemuan 6 Lab 2

![Screenshot (15)](https://user-images.githubusercontent.com/73010098/98110041-1852a680-1ed1-11eb-962d-8175e7828bfe.png)

#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
a = input("Masukkan Nilai a = ")
b = input("Masukkan Nilai b = ")
print("Variable a = ", a)
print("Variable b = ", b)
print("Hasil penggabungan {0} & {1} = %s".format(a,b) % (a+b))

# Konversi nilai variable ke dalam integer
a = int(a)
b = int(b)
print("Hasil penjumlahan {0} + {1} = %d".format(a,b) % (a+b))
print("Hasil pembagian {0} / {1} = %d".format(a,b) % (a/b))

```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![Screenshot (13)](https://user-images.githubusercontent.com/73010098/98110289-767f8980-1ed1-11eb-8935-45e87e6841fb.png)




#### ANALISIS
•	Statement %d berfungsi untuk wadah menyimpan variabel a, b, dan hasil setelah dipanggil kembali oleh statement % (a, b, hasil))





