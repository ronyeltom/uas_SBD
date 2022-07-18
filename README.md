# uas_SBD
## UJIAN AKHIR SEMESTER

Nama : RONY ELTOM ATIBAMAN

NIM : 312010003

Kelas : TI.20.D.1

Matkul : Sistem Basis Data

Dosen : Muhammad Najamuddin Dwi Miharja, S.Kom, M.kom

# Membuat Sistem Informasi Klinik.

* tampilan login
![gambar1](scs/1.1.png)

* tampilan daa pasien
![gambar2](scs/1.2.png)

* tapilan data dokter
![gambar3](scs/1.3.png)

* tampilan data obat
![gambar4](scs/1.4.png)


* Implementasi Fungsi.
Mengimplementasikan Fungsi untuk menampilkan total data :

CREATE FUNCTION fn_totalUsers() RETURNS INT(11) UNSIGNED NOT DETERMINISTIC NO SQL SQL SECURITY DEFINER RETURN (SELECT COUNT(id_pasien) FROM pasien)
![gambar5](scs/1.5.png)