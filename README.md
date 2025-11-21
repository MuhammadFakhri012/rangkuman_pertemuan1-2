📘 Rangkuman BAB 1 & BAB 2

Modul Praktikum Basis Data


---

BAB 1 – Review Konversi ER Diagram ke Skema Relasi

Bab ini membahas proses mengubah ER Diagram (ERD) menjadi skema relasi yang siap diimplementasikan sebagai tabel di database.

🔹 1. Konsep Dasar ERD

Entitas → objek yang direpresentasikan sebagai tabel.

Atribut → kolom pada tabel.

Primary Key (PK) → identitas unik setiap baris data.

Relasi → hubungan antar entitas.

Kardinalitas → tipe hubungan (1–1, 1–N, N–N).



---

🔹 2. Aturan Konversi ERD ke Relasi

Proses konversi mengikuti aturan berikut:

1. Entitas kuat → tabel


2. Atribut komposit → dipecah menjadi atribut sederhana


3. Atribut multivalue → tabel baru


4. Entitas lemah → tabel + PK dari entitas kuat sebagai FK


5. Relasi 1–1 → FK pada salah satu tabel


6. Relasi 1–N → FK pada entitas sisi 'N'


7. Relasi N–N → dibuat tabel penghubung


8. Relasi khusus:

Unary (rekursif)

Ternary

Generalisasi–spesialisasi

Agregasi





---

🔹 3. Studi Kasus – Sistem Apotek

ERD apotek dikonversi menjadi 13 tabel, di antaranya:

PASIEN

RESEP

OBAT

DETAIL_OBAT

PEGAWAI

PEMBAYARAN

RETUR
dll.



---

📌 Kesimpulan BAB 1

Bab ini berfokus pada transformasi ERD ke skema relasi, termasuk penerapan aturan relasional untuk mendapatkan struktur tabel yang benar dan konsisten.


---


---

BAB 2 – Pengantar Basis Data & DDL

Bab ini menjelaskan konsep dasar database, pengenalan MySQL, dan penggunaan perintah DDL untuk membuat dan mengelola database.


---

🔹 1. Pengertian Umum

Database → kumpulan tabel yang berisi data terstruktur.

DBMS → perangkat lunak pengelola database (contoh: MySQL, PostgreSQL, Oracle).



---

🔹 2. Pengenalan MySQL

Menggunakan bahasa SQL.

Bersifat open-source.

Ringan, cepat, aman, dan banyak digunakan dalam pengembangan aplikasi.

Sering digunakan bersama XAMPP untuk kemudahan instalasi.



---

🔹 3. Akses MySQL via Command Line

Perintah dasar:

mysql -u root -p

Keluar dari MySQL:

\q


---

🔹 4. Tipe Data Dasar di MySQL

INT, FLOAT,

CHAR, VARCHAR,

DATE, DATETIME,

BLOB.



---

🔹 5. Perintah DDL (Data Definition Language)

Digunakan untuk membuat dan mengatur struktur database.

Contoh:

CREATE DATABASE praktikum;
SHOW DATABASES;
USE praktikum;
DROP DATABASE praktikum;


---

📌 Kesimpulan BAB 2

Bab ini memberikan fondasi pemahaman mengenai database, MySQL, serta perintah dasar DDL yang digunakan dalam pembuatan dan pengelolaan database.
