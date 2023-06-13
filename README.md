# Praktikum_4
INNER JOIN

## Profil
| Variable | Isi |
| -------- | --- |
| **Nama** | Gilar Sumilar |
| **NIM** | 312210407 |
| **Kelas** | TI.22.A4 |
| **Mata Kuliah** | Basis data |

## Soal praktikum_5
### Tugas Buat Table & Lengkapi data pada semua table
![image]

# Tugas Latihan
![image]


## Lakukan join table Mahasiswa dan Dosen
**Query : (Menggunakan INNER JOIN)**
```sql
SELECT tb_mahasiswa.nim, tb_mahasiswa.nama, tb_mahasiswa.jk, tb_dosen.nama AS "Dosen"
FROM tb_mahasiswa INNER JOIN tb_dosen ON tb_dosen.kd_ds = tb_mahasiswa.kd_ds;
```
**Hasil**

![image]

**Query : (Menggunakan LEFT JOIN)**
```sql
SELECT tb_mahasiswa.nim, tb_mahasiswa.nama, tb_mahasiswa.jenis_kelamin, tb_dosen.nama AS "Dosen"
FROM tb_mahasiswa LEFT JOIN tb_dosen ON tb_dosen.kd_ds = tb_mahasiswa.kd_ds;
```
**Hasil**

![image]

## Lakukan join tabel Matakuliah dan Dosen
**Query : 

## Lakukan join table JadwalMengajar, Dosen, dan Matakuliah

## Lakukan join tabel KrsMahasiswa, Mahasiswa, Matakuliah, dan Dosen
