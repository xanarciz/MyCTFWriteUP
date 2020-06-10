# HSCTF 7

---

## Meta Mountains

- Kategori : Forensics
- Level : Pemula
- Poin : 100

---

## Soal

It seems that mountains are a great place for hiding secrets. Maybe you could find this one!

Author: wooshi

---
## Solusi

Perikasi meta menggunakan tools binwalk.

`binwalk mountains_hsctf.jpg`

```
...
Camera Model Name               : part 1/3: flag{h1dd3n_w1th1n_
Orientation                     : Horizontal (normal)
X Resolution                    : 180
Y Resolution                    : 180
Resolution Unit                 : inches
Software                        : part 2/3: th3_m0unta1ns_
Modify Date                     : 2012:02:03 11:18:05
Artist                          : part 3/3: l13s_th3_m3tadata}

...
```

### Flag

`flag{h1dd3n_w1th1n_th3_m0unta1ns_l13s_th3_m3tadata}`