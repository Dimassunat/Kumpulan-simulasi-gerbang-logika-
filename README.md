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

<img width="4096" height="3072" alt="IMG_20260530_170335" src="https://github.com/user-attachments/assets/dfe1ba0a-5503-4e4a-bfe3-6232bafbd730" />
<img width="4096" height="3072" alt="IMG_20260530_170352" src="https://github.com/user-attachments/assets/0cb5cb70-84fd-4daa-9046-76a805587d26" />
<img width="4096" height="3072" alt="IMG_20260530_170346" src="https://github.com/user-attachments/assets/5b50d0c5-1088-4b03-8445-b7d085fe913c" />
<img width="4096" height="3072" alt="IMG_20260530_170356" src="https://github.com/user-attachments/assets/98a4e807-777f-4a71-88e9-a271f273316d" />


### 2. Gerbang OR (Penjumlahan Logika)

Output akan bernilai 1 jika salah satu atau semua input bernilai 1.

* **Notasi:** $Y = A + B$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **0**
* 0 dan 1 -> **1**
* 1 dan 0 -> **1**
* 1 dan 1 -> **1**

<img width="4096" height="3072" alt="IMG_20260530_170405" src="https://github.com/user-attachments/assets/9dfb08d1-9ab2-4170-afe3-bbef443d0d16" />
<img width="4096" height="3072" alt="IMG_20260530_170409" src="https://github.com/user-attachments/assets/f4d4c1a3-1210-4f30-b414-cb2e572c18f5" />
<img width="4096" height="3072" alt="IMG_20260530_170414" src="https://github.com/user-attachments/assets/721af9ae-c650-401a-ad8d-aa586835a632" />
<img width="4096" height="3072" alt="IMG_20260530_170418" src="https://github.com/user-attachments/assets/a1db1b94-69a0-4230-983d-38c5b455bac7" />

### 3. Gerbang NOT (Inverter / Pembalik)

Mengubah nilai input menjadi kebalikannya. Hanya memiliki 1 input.

* **Notasi:** $Y = \bar{A}$
* **Kondisi Input -> Output:**
* 0 -> **1**
* 1 -> **0**

<img width="4096" height="3072" alt="IMG_20260530_170429" src="https://github.com/user-attachments/assets/a344d6ed-0d2e-4596-a987-4a40b47aad81" />
<img width="4096" height="3072" alt="IMG_20260530_170434" src="https://github.com/user-attachments/assets/044d9f97-0849-403b-8698-70b140e3a440" />

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

<img width="4096" height="3072" alt="IMG_20260530_170532" src="https://github.com/user-attachments/assets/4d49e74a-85ef-4301-bef6-da0a07ffd531" />
<img width="4096" height="3072" alt="IMG_20260530_170539" src="https://github.com/user-attachments/assets/5910b353-9683-4a99-81e8-8f87cb2d3298" />
<img width="4096" height="3072" alt="IMG_20260530_170546" src="https://github.com/user-attachments/assets/684fb249-9dcc-4bf5-b5ed-91d6d3923056" />
<img width="4096" height="3072" alt="IMG_20260530_170553" src="https://github.com/user-attachments/assets/cdaf4c2d-fd58-49cd-a1ee-28aa3a2f1b08" />

### 5. Gerbang NOR (Not OR)

Kebalikan dari gerbang OR. Output akan bernilai 1 hanya jika semua input bernilai 0.

* **Notasi:** $Y = \overline{A + B}$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **1**
* 0 dan 1 -> **0**
* 1 dan 0 -> **0**
* 1 dan 1 -> **0**

<img width="4096" height="3072" alt="IMG_20260530_171021" src="https://github.com/user-attachments/assets/2c4f2803-57d9-4efd-8372-c3eddd2ab67f" />
<img width="4096" height="3072" alt="IMG_20260530_171027" src="https://github.com/user-attachments/assets/ec9b8d49-0326-4a06-b13b-afc0069cb208" />
<img width="4096" height="3072" alt="IMG_20260530_171032" src="https://github.com/user-attachments/assets/330b51a2-6bbe-45ef-a00c-4538b47daabb" />
<img width="4096" height="3072" alt="IMG_20260530_171039" src="https://github.com/user-attachments/assets/39379c07-4c58-4cc9-9c95-ebc89138b955" />

### 6. Gerbang XOR (Exclusive OR)

Output akan bernilai 1 jika nilai kedua input berbeda.

* **Notasi:** $Y = A \oplus B$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **0**
* 0 dan 1 -> **1**
* 1 dan 0 -> **1**
* 1 dan 1 -> **0**

<img width="4096" height="3072" alt="IMG_20260530_171129" src="https://github.com/user-attachments/assets/ad9604ed-3691-480a-bb56-a6b6e429bd14" />
<img width="4096" height="3072" alt="IMG_20260530_171134" src="https://github.com/user-attachments/assets/d3ce489b-8192-46de-b85b-77fa959108c4" />
<img width="4096" height="3072" alt="IMG_20260530_171139" src="https://github.com/user-attachments/assets/2009ac18-8aeb-4f95-b1d9-cfead196826e" />
<img width="4096" height="3072" alt="IMG_20260530_171143" src="https://github.com/user-attachments/assets/797ae0ff-e0a3-4f12-a8b5-cc5f4bfe9f46" />

### 7. Gerbang XNOR (Exclusive NOR)

Kebalikan dari XOR. Output akan bernilai 1 jika nilai kedua input sama.

* **Notasi:** $Y = \overline{A \oplus B}$
* **Kondisi Input -> Output:**
* 0 dan 0 -> **1**
* 0 dan 1 -> **0**
* 1 dan 0 -> **0**
* 1 dan 1 -> **1**

<img width="4096" height="3072" alt="IMG_20260530_171058" src="https://github.com/user-attachments/assets/89ffe20a-e8b2-4318-b4b6-82ced86569f9" />
<img width="4096" height="3072" alt="IMG_20260530_171104" src="https://github.com/user-attachments/assets/e425b1e9-d870-4911-a02b-72928142e958" />
<img width="4096" height="3072" alt="IMG_20260530_171109" src="https://github.com/user-attachments/assets/e1997f77-9a1f-4a9f-8670-bd1c5fbfb3de" />
<img width="4096" height="3072" alt="IMG_20260530_171113" src="https://github.com/user-attachments/assets/5a946698-44f9-4925-9964-b2044f71f767" />

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
