### latihan2SQL
## NIM: 312210200
## Nama: Inayatus Sholekhawati
## Kelas: TI.22.A.2

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

```CREATE TABLE nama_tabel (nama_field1 tipe _data(ukuran), nama_field2 tipe_data(ukuran), ..., nama_fieldn tipe_data(ukuran));```

```CREATE TABLE biodata (nama VACHAR (15), alamat TEXT);```


<img width="498" alt="inay 2" src="https://user-images.githubusercontent.com/115867315/230778642-f405f3ee-ae63-4c15-97a7-c3784e495474.png">


<img width="604" alt="inay3" src="https://user-images.githubusercontent.com/115867315/230778674-9d10becd-c70c-4a19-8fc7-cb9b09c6f401.png">


3.Tambahkan sebuah kolam keterangan(varchar15) setelah kolom terakhir!
untuk menambahkan kolam di akhir biasanya mengunakn kata AFTER, contoh:


```
ALTER TABLE biodata ADD COLUMN keterangan VARCHAR (15) AFTER phone;
```

<img width="960" alt="inay6" src="https://user-images.githubusercontent.com/115867315/230781152-99ba15ff-85a5-4e42-8723-cd34ebfc3afb.png">


4.Tambahkan kolom id (int11) di awal (sebagai kolom pertama)!
Perintah yang dibutuhkan untuk menmbahkan kolom pertama:

```
ALTER TABLE biodata ADD COLUMN id int(11) FIRST;
```
<img width="960" alt="inay4" src="https://user-images.githubusercontent.com/115867315/230781228-c4d7bda2-13c8-4cfb-b80c-db2f83043d72.png">


5.Sisipkan sebuah kolom dengan nama phone (varchar15) setelah kolam alamat!

<img width="957" alt="inay5" src="https://user-images.githubusercontent.com/115867315/230781310-8b6dddf1-fbfe-4f33-b59c-a343f748f504.png">


6.Ubah type data kolom id menjadi char(11)!

Perintah untuk mengubah type data dengan:

```
ALTER TABLE [nama_tabel] MODIFY nama_field tipe_data_baru(ukuran);
```

<img width="960" alt="inay7" src="https://user-images.githubusercontent.com/115867315/230780025-1be24236-736f-4363-8cd4-c418c6823d66.png">

7.Ubah nama kolom phone menjadi hp (varchar 20)

perintah yang digunakan untuk mengubah nama kolom:

```
ALTER TABLE [nama_tabel] CHANGE nama_field_lama nama_field_baru tipe_data(ukuran);
```

<img width="960" alt="inay8" src="https://user-images.githubusercontent.com/115867315/230780202-6f8e304f-e4ed-473f-adad-80caee5f7fff.png">

8.Tambahkan kolom email setelah kolom hp

<img width="960" alt="inay9" src="https://user-images.githubusercontent.com/115867315/230780263-f63d7f27-a3c9-4268-b83c-431bfba40258.png">

9.Hapus kolom keterangan dari tabel!

untuk mengahapus kolom dari tabel mengunkan perintah:

```
ALTER TABLE [nama_tabel] DROP nama_field;
```

<img width="960" alt="inay10" src="https://user-images.githubusercontent.com/115867315/230780418-da0e41e7-38b7-4fe9-b9a8-146e2832d521.png">

10.Ganti nama tabel menjadi data_mahasiswa!

untuk mengganti nama tabel menunakan mengunakan perintah:

```
ALTER TABLE [nama_tabel] RENAME [nama_tabel_baru]
```

<img width="341" alt="inay11" src="https://user-images.githubusercontent.com/115867315/230780619-490f6f9d-145b-4175-bd56-c5926677f896.png">
<img width="832" alt="inay12" src="https://user-images.githubusercontent.com/115867315/230780725-93fdfb0c-b175-496f-882f-c86c6d94570a.png">


11.Ganti nama field id menjadi nim!

<img width="960" alt="inay13" src="https://user-images.githubusercontent.com/115867315/230780690-22ed278a-4151-4430-8c11-2faccc091654.png">

12.Jadikan nim sebagi PRIMARY KEY!

tipe index:
PRIMARY KEY
UNIQUE KEY
FULLTEXT

untuk menambahkan index atau key gunakan perintah:
```
ALTER TABLE [nama_tabel] ADD [INDEX|PRIMARY KEY] (nama_field);
```
![inay](https://user-images.githubusercontent.com/115867315/230781772-b69a5df1-a6ce-48d3-8e86-e0b298cdaa28.jpeg)

13.Jadikan kolom email sebagai UNIQUE KEY

perintahnya masih sama dengan yang diatas, hanya saja di gantikan menjadi UNIQUE KEY

<img width="960" alt="inay14" src="https://user-images.githubusercontent.com/115867315/230781507-88396d68-4046-490c-9a16-3615049b5bc3.png">

### EVALUASI DAN PERTANYAAM
## Tulis semua perintah-perintah SQL percobaan diatas berserta optpitnya!

# Membuat Database
```
CREATE DATABASE latihan1;
```

<img width="960" alt="inay15" src="https://user-images.githubusercontent.com/115867315/230782620-34b7152b-f15f-47cc-b3ce-97f333c43b41.png">

# Membuat Tabel
```
CREATE TABLE siswa (nama VARCHAR (100), alamat TEXT);
```

<img width="960" alt="inay16" src="https://user-images.githubusercontent.com/115867315/230782663-da28f4c3-338a-4e38-932d-272569f76d8b.png">

# Membuat kolom
```
ALTER TABLE biodata ADD COLUMN ketengan TEXT AFTER alamat;
```

<img width="880" alt="inay17" src="https://user-images.githubusercontent.com/115867315/230782748-bd917559-1190-4db9-b63a-0b3475aada82.png">

# Menamabah kolom diawal
```
ALTER TABLE siswa ADD COLUMN id INT FIRST;
```

<img width="930" alt="inay18" src="https://user-images.githubusercontent.com/115867315/230782838-eb3029fa-7f71-4be2-a7ea-d2b5fee498a0.png">

# Mengubah nama kolom
```ALTER TABLE siswa CHANGE COLUMN keterangan TO kelas;```

Diperintah ini terdapat kesalahan, seharusnya yang benar yaitu ini ``ALTER TABLE siswa CHANGE keterangan kelas TEXT``

<img width="960" alt="inay19" src="https://user-images.githubusercontent.com/115867315/230782951-eae2cd17-6c45-49cb-a94a-cdddcf640260.png">

# Mengubah tipe data
```
ALTER TABLE siswa MODIFY COLUMN kelas VARCHAN(10);
```

<img width="960" alt="inay20" src="https://user-images.githubusercontent.com/115867315/230783006-f0456635-45f8-4e4d-90e3-c33e54843670.png">

# Menghapus kolom
```
ALTER TABLE siswa DROP COLUMN kelas;
```

<img width="960" alt="inay21" src="https://user-images.githubusercontent.com/115867315/230783054-c2cd4b59-da50-4b7d-a84e-13b362fff458.png">

# Menambah PRIMARY KEY
```
ALTER TABLE siswa ADD PRIMARY KEY(id);
```

<img width="960" alt="inay22" src="https://user-images.githubusercontent.com/115867315/230783135-ec4a6a44-753e-4248-91df-0b3129e0b9c8.png">

# Menambah CONSTRAINT
```
ALTER TABLE siswa ADD CONSTRAINT pk_sisiwa PRIMARY KEY(id);
```

<img width="960" alt="inay23" src="https://user-images.githubusercontent.com/115867315/230783185-ef868063-0bda-4653-9d54-8f12b86551ab.png">

# Menghapus PRIMARY KEY
```
ALTER TABLE siswa DROP PRIMARY KEY;
```

<img width="960" alt="inay24" src="https://user-images.githubusercontent.com/115867315/230783245-487fd6d4-05dc-48f1-b0c3-58e52a8aa290.png">

# Menghapus CONSTRAINT
```
ALTER TABLE siswa DROP CONSTRAINT pk_siswa;
```

<img width="960" alt="inay24" src="https://user-images.githubusercontent.com/115867315/230783300-1f1adbed-15f5-440b-8948-884dc99448eb.png">

## Apa Maksud dari int(11)?
adalah suatu data yang dipakai atau digunakan menggunakan tipe data int atau integer dengan length atau panjang 11 karakter

## Ketika kita melihat struktur tabel dengan perintah desc, ada kolom Null yang berisi Yes dan No. Apa maksdnya?
Maksud dari kata yes dan no pada kolom null itu adalah untuk menjelaskan bahwa pada record yang no harus di isi sedangkan yes bisa tidak di isi
