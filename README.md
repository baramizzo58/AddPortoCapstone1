# CRUD Program: Student Grade List (Daftar Nilai Siswa)
Additional Portofolio Capstone Project Modul 1 Purwadhika Job Connector Data Science Online Batch 9 (JCDSOL-09) - Noor Kharismawan Akbar

# Data Description
Berikut deskripsi kolom:
| No | Nama Kolom | Type | Range | Deskripsi |
| -- | -- | -- | -- | -- |
| 1 | `nis` | `int` | - | Nomor Induk Siswa (NIS) |
| 2 | `nama` | `str` | Max 3 kata (Selebihnya akan disingkat) | Nama lengkap siswa |
| 3 | `sex` | `str` | M (Male) / F (Female) | Jenis Kelamin Siswa |
| 4 | `matematika` | `int` | 1-100 | Nilai matematika |
| 5 | `fisika` | `int` | 1-100 | Nilai fisika |
| 6 | `kimia` | `int` | 1-100 | Nilai kimia |

# Main Menu
Untuk flowchart program yang menggambarkan alur kerja setiap fungsi, bisa dilihat di link [berikut](https://github.com/baramizzo58/AddPortoCapstone1/blob/main/Flowchart%20Program%20CRUD.pdf). Main menu pada program ini terdiri dari 5 fungsi:

## Sub Menu 1: Read
Sub-menu ini akan menampilkan daftar nilai siswa. Terdapat 2 opsi yaitu menampilkan daftar nilai seluruh siswa & menampilkan daftar nilai seorang siswa. Dimana jika ingin menampilkan daftar nilai seorang siswa, akan diminta memasukkan `nis` yang harus terdapat dalam daftar nilai siswa.

## Sub Menu 2: Create
Sub-menu ini akan menambahkan daftar nilai siswa. Akan diminta untuk memasukkan value untuk semua kolom. Data yang dimasukkan tidak boleh kosong & harus sesuai range yang terdapat pada deskripsi kolom. Terkhusus untuk kolom `nis`, data tidak boleh duplikat dengan `nis` yang sudah ada.

## Sub Menu 3: Update
Sub-menu ini akan mengubah daftar nilai siswa. Akan diminta memasukkan `nis` yang akan diupdate. `nis` harus terdapat dalam daftar nilai siswa. Kemudian, akan diminta memasukkan nama kolom yang akan di update beserta value baru nya. Terkhusus untuk kolom `nis`, data tidak boleh duplikat dengan `nis` yang sudah ada.

## Sub Menu 4: Delete
Sub-menu ini akan menghapus daftar nilai siswa. Akan diminta memasukkan `nis` yang akan dihapus. `nis` harus terdapat dalam daftar nilai siswa.

## Sub Menu 5: Quit
Sub-menu ini akan membuat keluar dari program daftar nilai siswa.
