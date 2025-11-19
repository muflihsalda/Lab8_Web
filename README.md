# Lab8_Web
Nama  :Mulfih Salda Maulana

Nim  :312410527

Kelas:TI.24.A5




## **Membuat Database & Tabel**

### Query yang digunakan:

```sql
CREATE DATABASE latihan1;

USE latihan1;

CREATE TABLE data_barang (
  id_barang INT(10) AUTO_INCREMENT PRIMARY KEY,
  kategori VARCHAR(30),
  nama VARCHAR(30),
  gambar VARCHAR(100),
  harga_beli DECIMAL(10,0),
  harga_jual DECIMAL(10,0),
  stok INT(4)
);
```

## **Mengisi Data Awal**

```sql
INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok) VALUES
('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);
```

**Screenshot:**
<img width="869" height="338" alt="database" src="https://github.com/user-attachments/assets/9bc3c812-7a53-404b-89c9-0ce9b0259ad8" />

---
## **Halaman Index (Read Data)**

Halaman ini berfungsi untuk:

* Menampilkan semua data dari tabel `data_barang`
* Menampilkan gambar barang
* Menyediakan tombol **Ubah** dan **Hapus**

**Screenshot:**

<img width="567" height="355" alt="DATA_BARANG" src="https://github.com/user-attachments/assets/9f5ba343-6838-41f9-b9b4-6b119dc10480" />


---

## **Halaman Tambah Data (Create)**

Fitur:

* Menambah data baru
* Upload gambar
* Mengirim data ke database

**Screenshot:**
<img width="587" height="370" alt="TAMBAH_BARANG" src="https://github.com/user-attachments/assets/4ec5209e-60ce-4630-957a-99fd8fbbca27" />


---

## **Halaman Ubah Data (Update)**

Fitur:

* Menampilkan data lama berdasarkan ID
* Mengubah data di database
* Upload gambar baru (opsional)

**Screenshot:**
<img width="485" height="330" alt="UBAH_BARANG" src="https://github.com/user-attachments/assets/fcde7557-bd04-46f4-a5e1-b13a16060932" />


---

## **Menghapus Data (Delete)**
Menghapus data akan memunculkan pengingat seperti pada di gambar

**Screenshot:**

<img width="533" height="170" alt="hapus_data" src="https://github.com/user-attachments/assets/19457ec8-b269-4758-9855-6d1071c88775" />


---

## **Tampilan Setelah CSS Diterapkan**

File **style.css** digunakan untuk:

* Merapikan tampilan form
* Menata tabel
* Memberi jarak antar elemen

**Screenshot:**
<img width="787" height="545" alt="UBAH_BARANG_css" src="https://github.com/user-attachments/assets/3a01fcb3-e511-4b2c-af80-2294dff2a8ad" />

<img width="786" height="568" alt="Tambah_barang_css" src="https://github.com/user-attachments/assets/f66756bf-c820-4d63-9b93-c6437408a672" />

<img width="832" height="322" alt="data_barang_css" src="https://github.com/user-attachments/assets/2c91e793-21e9-419a-9788-d29d77dda8f8" />



---


