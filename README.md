# Laporan Modul 1 dan 2 Prak Basis Data

#### Nama: Yudha Amartha Tungga
#### Kelas: XI RPL 2
#### Absen: 29

>## Modul 1

### 1.Install Xampp terlebih dahulu

![image](https://user-images.githubusercontent.com/92255670/190301531-fff847a3-2912-499c-90dc-98b112097e43.png)


### 2.aktifkan mysql di xampp

![image](https://user-images.githubusercontent.com/92255670/190300828-bc545470-06b3-49e6-86c7-2a8d147eab8f.png)

### 3.kemudian masuk ke command prompt 

![image](https://user-images.githubusercontent.com/92255670/190300950-b3c6cf63-dc30-454a-88ea-089139b4a69b.png)

- ### Cara membuat title

```
title nama_kaliam
```
![image](https://user-images.githubusercontent.com/92255670/190312984-86fb4ba3-62d4-429f-84b4-07dc6ee56ff6.png)

### 4.Masuk direktori Mysql 

```
cd xampp/mysql/bin
```

![image](https://user-images.githubusercontent.com/92255670/190303407-b4246b76-6ec3-4c79-af39-114aecb26db5.png)

### 5.ketik syntaks berikut untuk masuk ke MariaDB
```
mysql -u root
```

![image](https://user-images.githubusercontent.com/92255670/190308626-753b3710-6ba3-4ce7-8e66-224a08e8780a.png)

**Di atas sudah bisa menuliskan query**



>## Modul 2
- ### Cara melihat daftar database
```
show databases;
```

![image](https://user-images.githubusercontent.com/92255670/190309535-53e99a2d-071f-4b8a-a6b5-d7f9b6c4cd75.png)

- ### Cara membuat database
```
create database nama_database;
```
![image](https://user-images.githubusercontent.com/92255670/190311061-2402935f-72f3-4e58-91ef-deeaa6ff9c8c.png)

- ### Cara memilih dan masuk dafar database yang kita inginkan 

```
use nama_database;
```
![image](https://user-images.githubusercontent.com/92255670/190312060-2618fb47-49b7-4242-b6ad-1e2ffc73719f.png)

- ### Cara membuat table
```
create table name_table(nama varchar(50)not null,no int(3)not null);
```

![image](https://user-images.githubusercontent.com/92255670/190313876-73124c48-987b-467d-b775-a94d8cd51a73.png)

- ### Cara melihat daftar table
```
show tables;
```
![image](https://user-images.githubusercontent.com/92255670/190314476-a41bb5ec-8393-4404-aa93-6e3f2c6fbff8.png)

- ### Cara melihat isi (struktur) di sebuah tabel

```
desc name_table;
```

![image](https://user-images.githubusercontent.com/92255670/190314810-773e8af2-cd89-4cdf-827b-3016b01c41cf.png)

                                                           ## Selesai                                                     
