# HSCTF 7

---

## Pythagorean Tree Fractal 1

- Kategori : Algoritms
- Level : Pemula
- Poin : 100

---

## Soal

Pythagorean Tree 2

Because every good thing must have a sequel ;)

Please see the attached file for more details (and ignore the red dots on the images).

Note: Don't worry about overlapping squares!

Author: Plate_of_Sunshine


---

## Solusi

Menghitung jumlah box pohon pad fraktal. Saya menggunakan golang disini.

```
package main

func main() {
	var limit = 50
	hasil := 1
	println("1 .. ", hasil)
	for i := 2; i <= limit; i++ {
		var hitung = hasil + hasil + 1
		println(i, "..", hitung)
		hasil = hitung
	}
}
```

output

```
...
41 .. 2199023255551
42 .. 4398046511103
43 .. 8796093022207
44 .. 17592186044415
45 .. 35184372088831
46 .. 70368744177663
47 .. 140737488355327
48 .. 281474976710655
49 .. 562949953421311
50 .. 1125899906842623
```

### Flag

`flag{1125899906842623}`