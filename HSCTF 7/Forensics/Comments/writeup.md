# HSCTF 7

---

## Comments

- Kategori : Forensics
- Level : Pemula
- Poin : 100

---

## Soal

I found this file on my Keith's computer... what could be inside?

Author: AC

---

## Solusi

Extract file zip dimulai dari file comments hingga file flag. Lakukan pengecekan komentar pada file 1.zip - 8.zip menggunakan perintah `zipinfo`.

`zipinfo -12smlvChMtTz 1.zip`


### Flag

`flag{4n6}`