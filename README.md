```py
Nama  : Muhamad Ali M
Nim   : 312210540
Kelas : TI.22.B2
```

# TUGAS

![image](Screenshoot/tugas.JPG)

# Membuat Database: Studi Kasus Data Barang

![image](Screenshoot/database.JPG)

# Membuat Database

CREATE DATABASE latihan1;

Membuat Tabel

```py
CREATE TABLE data_barang (
id_barang int(10) auto_increment Primary Key,
kategori varchar(30),
nama varchar(30),
gambar varchar(100),
harga_beli decimal(10,0),
harga_jual decimal(10,0),
stok int(4)
);
```

![image](Screenshoot/tabel.JPG)
