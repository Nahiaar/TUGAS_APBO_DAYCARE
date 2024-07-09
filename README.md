# TUGAS_APBO_SI_DAYCARE
---
## Nama  : RAIHAN ALFISA SAUGI 
## NPM   : 4522210037
---
### Aktor yang terlibat
* Orang Tua/Wali
* Staf
* Admin
---

### USE CASE DAYCARE
![usecase](https://github.com/Nahiaar/TUGAS_APBO_DAYCARE/assets/145973260/00773754-5ced-41b9-8296-27bf22823500)

## Penjelasan:
* Pendaftaran Anak: Orang tua/wali mengisi formulir pendaftaran online atau offline. Admin memverifikasi data pendaftaran. Orang tua/wali membayar biaya pendaftaran. Admin membuat akun untuk orang tua/wali dan anak.
* Check-in Anak: Orang tua/wali menitipkan anak kepada staf. Staf mencatat waktu check-in anak. Staf memastikan anak dalam keadaan sehat.
* Check-out Anak: Orang tua/wali memberitahu staf bahwa mereka ingin menjemput anak. Staf mencatat waktu check-out anak. Orang tua/wali menjemput anak dan menandatangani formulir penjemputan.
---

### CLASS DIAGRAM
![classdiagram](https://github.com/Nahiaar/TUGAS_APBO_DAYCARE/assets/145973260/701b7d6b-4324-4a57-b7a4-e1fae7b92a42)

---

### ERD (Entity Relationship Diagram)
![ERD](https://github.com/Nahiaar/TUGAS_APBO_DAYCARE/assets/145973260/7cce08ff-7ce0-43d3-a8b7-db366eeaa06f)

## Penjelasan:
* Orang Tua > Anak (One to Many): Seorang orang tua dapat memiliki banyak anak.
* Anak > Kehadiran (One to Many): Seorang anak dapat memiliki banyak catatan kehadiran.
* Staf > Kehadiran (One to Many): Seorang staf dapat mencatat kehadiran banyak anak.
* Jadwal > Anak (Many to Many): Anak dapat mengikuti banyak jadwal, dan satu jadwal dapat diikuti oleh banyak anak.
* Laporan > Anak (One to Many): Seorang anak dapat memiliki banyak laporan.
* Staf > Jadwal (One to Many): Seorang staf memiliki banyak jadwal.
