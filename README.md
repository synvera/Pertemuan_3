# 3.2 Test Awal
1. Operasikan perintah SQL untuk : <br>
a. Membuat database <br>
b. Melihat seluruh database pada mysql server <br>
c. Mengakses database/ menggunakan database <br>
d. Menghapus database <br>
--- <br>
mysql> create database db_sekolah; <br>
Query OK, 1 row affected (0.04 sec) <br>

mysql> show databases;<br>
+--------------------------+ <br>
| Database                 |<br>
+--------------------------+<br>
| admin_pembayaran_sekolah |<br>
| apotik                   |<br>
| bank                     |<br>
| db_sekolah               |<br>
| information_schema       |<br>
| klserpeel                |<br>
| mysql                    |<br>
| performance_schema       |<br>
| sys                      |<br>
| tokokelontong            |<br>
| tokoklontong             |<br>
| website                  |<br>
+--------------------------+<br>
12 rows in set (0.00 sec)<br>

mysql> use db_sekolah;<br>
Database changed<br>
mysql> drop database db_sekolah;<br>
Query OK, 0 rows affected (0.04 sec)<br>

mysql> show databases;<br>
+--------------------------+<br>
| Database                 |<br>
+--------------------------+<br>
| admin_pembayaran_sekolah |<br>
| apotik                   |<br>
| bank                     |<br>
| information_schema       |<br>
| klserpeel                |<br>
| mysql                    |<br>
| performance_schema       |<br>
| sys                      |<br>
| tokokelontong            |<br>
| tokoklontong             |<br>
| website                  |<br>
+--------------------------+<br>
11 rows in set (0.00 sec)<br>