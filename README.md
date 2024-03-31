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

# Menambahkan Data

```py
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual,
stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000,
2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
```

![image](Screenshoot/menambah%20data.JPG)

# Membuat Program CRUD

Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![image](Screenshoot/lab8.1.JPG)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:

http://localhost/lab8_php_database/

![image](Screenshoot/lab8.JPG)
