# Kumpulan-simulasi-gerbang-logika
Kumpulan simulasi gerbang logika dasar hingga rangkaian digital kompleks menggunakan Proteus.

🚪PENGERTIAN GERBANG LOGIKA
  Gerbang logika adalah blok bangunan dasar dari sistem digital. Setiap gerbang menerima satu atau lebih masukan (*input*) biner (0 atau 1) dan menghasilkan satu keluaran (*output*) biner berdasarkan aturan logika tertentu.


## 📌 Jenis-Jenis Gerbang Logika Dasar

### 1. Gerbang AND (Perkalian Logika)

Output akan bernilai 1 hanya jika semua input bernilai 1.

* **Notasi:** $Y = A \cdot B$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **0**
* 0 dan 1 -> **0**
* 1 dan 0 -> **0**
* 1 dan 1 -> **1**



### 2. Gerbang OR (Penjumlahan Logika)

Output akan bernilai 1 jika salah satu atau semua input bernilai 1.

* **Notasi:** $Y = A + B$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **0**
* 0 dan 1 -> **1**
* 1 dan 0 -> **1**
* 1 dan 1 -> **1**



### 3. Gerbang NOT (Inverter / Pembalik)

Mengubah nilai input menjadi kebalikannya. Hanya memiliki 1 input.

* **Notasi:** $Y = \bar{A}$
* **Kondisi Input -> Output:**
* 0 -> **1**
* 1 -> **0**



---

## 📌 Gerbang Logika Kombinasi (Turunan)

### 4. Gerbang NAND (Not AND)

Kebalikan dari gerbang AND. Output akan bernilai 0 hanya jika semua input bernilai 1.

* **Notasi:** $Y = \overline{A \cdot B}$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **1**
* 0 dan 1 -> **1**
* 1 dan 0 -> **1**
* 1 dan 1 -> **0**



### 5. Gerbang NOR (Not OR)

Kebalikan dari gerbang OR. Output akan bernilai 1 hanya jika semua input bernilai 0.

* **Notasi:** $Y = \overline{A + B}$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **1**
* 0 dan 1 -> **0**
* 1 dan 0 -> **0**
* 1 dan 1 -> **0**



### 6. Gerbang XOR (Exclusive OR)

Output akan bernilai 1 jika nilai kedua input berbeda.

* **Notasi:** $Y = A \oplus B$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **0**
* 0 dan 1 -> **1**
* 1 dan 0 -> **1**
* 1 dan 1 -> **0**



### 7. Gerbang XNOR (Exclusive NOR)

Kebalikan dari XOR. Output akan bernilai 1 jika nilai kedua input sama.

* **Notasi:** $Y = \overline{A \oplus B}$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **1**
* 0 dan 1 -> **0**
* 1 dan 0 -> **0**
* 1 dan 1 -> **1**



---

## 💡 Cheat Sheet Ringkas

> * **AND** -> Semua harus 1 agar output 1.
> * **OR** -> Salah satu saja 1, output sudah 1.
> * **NOT** -> Tukar nilai (0 jadi 1, 1 jadi 0).
> * **NAND** -> Kebalikan AND (hanya 1 dan 1 yang menghasilkan 0).
> * **NOR** -> Kebalikan OR (hanya 0 dan 0 yang menghasilkan 1).
> * **XOR** -> Input beda menghasilkan 1.
> * **XNOR** -> Input sama menghasilkan 1.
> 
>
