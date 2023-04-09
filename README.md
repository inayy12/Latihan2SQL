### latihan2SQL
## NIM; 312210200
## Nama; Inayatus Sholekhawati
## Kelas; TI.22.A.2

### TUGAS PRAKTIKUM
1.Buat sebuah database dengan nama lathan2!
untuk membuat database menggunakan perintah berikut:

```
CREATE DATABASE [nama_database]
```

```
CREATE DATABASE latihan 2;
```

setelah membuat database. kita bisa masuk mengunakan perintah berikut:

```
USE latiahan2
```

<img width="707" alt="inay1" src="https://user-images.githubusercontent.com/115867315/230777922-cab84edf-2c03-4870-ab7f-7edf12992e4d.png">


2.Buat sebuah tabel denngan nama biodata (nama,alamt) didalam database latihan1!
perintah yang digunakan untuk membuat tabel yaitu:

````
CREATE TABLE nama_tabel (nama_field1 tipe _data(ukuran), nama_field2 tipe_data(ukuran), ..., nama_fieldn tipe_data(ukuran));
```
```CREATE TABLE biodata (nama VACHAR (15), alamat TEXT);```

<img width="498" alt="inay 2" src="https://user-images.githubusercontent.com/115867315/230778642-f405f3ee-ae63-4c15-97a7-c3784e495474.png">

<img width="604" alt="inay3" src="https://user-images.githubusercontent.com/115867315/230778674-9d10becd-c70c-4a19-8fc7-cb9b09c6f401.png">


3.Tambahkan sebuah kolam keterangan(varchar15) setelah kolom terakhir!
untuk menambahkan kolam di akhir biasanya mengunakn kata AFTER, contoh:

```
ALTER TABLE biodata ADD COLUMN keterangan VARCHAR (15) AFTER phone;
```

<img width="960" alt="inay4" src="https://user-images.githubusercontent.com/115867315/230778897-a94bf9c2-2f71-427f-a18d-4cd668154790.png">
