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
