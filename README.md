# TUGAS_APBO_SI_DAYCARE
---
## Nama  : AKHMAD RIZALDY
## NPM   : 4522210050
---
### Aktor yang terlibat
* Orang Tua/Wali
* Staf
* Admin
---

### USE CASE DAYCARE
![USE CASE](https://github.com/akhmadrizaldy74/TUGAS_APBO_SI_DAYCARE/assets/145973003/ebb52632-c10c-4400-aaf1-1e4a351f3629)

Penjelasan:
* Mendaftarkan Anak : Orang tua atau wali mendaftarkan anak mereka ke sistem daycare.
* Melihat Laporan Anak : Orang tua atau wali dapat melihat laporan perkembangan anak mereka yang disusun oleh staf daycare.
* Mencatat Kehadiran Anak : Staf mencatat kehadiran harian anak-anak yang terdaftar di daycare.
* Membuat Jadwal : Staf membuat jadwal kegiatan untuk anak-anak di daycare.
* Mencatat Perkembangan Anak : Staf mencatat perkembangan anak untuk membuat laporan yang bisa dilihat oleh orang tua/wali.
* Mengelola Data Anak :  Admin mengelola data anak, termasuk penambahan, pembaruan, dan penghapusan data anak.
* Mengelola Data Orang Tua/Wali : Admin mengelola data orang tua atau wali, termasuk penambahan, pembaruan, dan penghapusan data orang tua/wali.
* Mengelola Data Staf : Admin mengelola data staf daycare, termasuk penambahan, pembaruan, dan penghapusan data staf.
* Mengelola Jadwal : Admin mengelola jadwal kegiatan di daycare.
* Mengelola Laporan : Admin mengelola laporan perkembangan anak yang dibuat oleh staf.
---

### CLASS DIAGRAM
![CLASS DIAGRAM](https://github.com/akhmadrizaldy74/TUGAS_APBO_SI_DAYCARE/assets/145973003/da1bc95c-f5e4-4b25-99b8-9994ae051854)

---

### ERD (Entity Relationship Diagram)
![ERD](https://github.com/akhmadrizaldy74/TUGAS_APBO_SI_DAYCARE/assets/145973003/3026f7c1-4b5f-4381-9059-4fc641a2c003)

Relasi antar Entitas:
* Anak memiliki satu atau lebih OrangTuaWali (relasi 1 ke banyak).
* Staf membuat satu atau lebih Jadwal (relasi 1 ke banyak).
* Anak mengikuti satu atau lebih Jadwal (relasi 1 ke banyak).
* Anak memiliki satu atau lebih Kehadiran yang dicatat oleh Staf (relasi 1 ke banyak).
* Anak memiliki satu atau lebih Laporan yang dilihat oleh OrangTuaWali (relasi 1 ke banyak).
