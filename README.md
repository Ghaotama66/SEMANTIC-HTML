# SEMANTIC-HTML
Latihan Praktikum Semantik HTML

### 1. Tag `<html>` dan `<body>`

#### Codingan 1 (HTML)
- **Tidak Ada Tag `<html>` dan `<body>`**:  
  Struktur halaman langsung dimulai dengan tag `<header>`, yang berarti tidak mengikuti standar HTML5 yang benar.

#### Codingan 2 (HTML)
- **Menggunakan Tag `<html>` dan `<body>`**:  
  Menggunakan tag `<html>` dengan atribut `lang="en"` yang menandakan bahasa halaman adalah bahasa Inggris. Selain itu, tag `<body>` juga digunakan untuk membungkus seluruh konten halaman (header, nav, section, footer).

---

### 2. Tag `<head>`

#### Codingan 1 (HTML)
- **Tidak Ada Tag `<head>`**:  
  Ini berarti informasi meta dan referensi file eksternal seperti CSS tidak disertakan, yang bisa mengurangi aksesibilitas dan optimasi halaman.

#### Codingan 2 (HTML)
- **Ada Tag `<head>` yang Lengkap**:  
  Mencakup beberapa elemen penting untuk optimasi dan kompatibilitas:
  - `<meta charset="UTF-8">` untuk menentukan encoding karakter yang digunakan.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk memastikan tampilan responsif di perangkat mobile.
  - `<title>HTML5 Semantic</title>` untuk menentukan judul halaman.
  - `<link rel="stylesheet" href="./assets/styles/styles.css">` untuk menautkan file CSS eksternal.

---

### 3. Penutupan Tag

#### Codingan 1 (HTML)
- **Tidak Ada Penutupan Tag**:  
  Tidak ada tag penutupan `</html>` atau `</body>`, yang membuat struktur HTML tidak lengkap dan tidak sepenuhnya sesuai dengan standar HTML5.

#### Codingan 2 (HTML)
- **Memiliki Penutupan Tag yang Lengkap**:  
  Memiliki tag penutupan yang lengkap untuk `</html>` dan `</body>`, yang menjadikannya sesuai dengan struktur HTML5 yang benar.

---

### 4. Penggunaan `lang="en"` pada Tag `<html>`

#### Codingan 1 (HTML)
- **Tidak Ada Atribut `lang` pada Tag `<html>`**:  
  Tidak ada atribut `lang`, yang menyebabkan halaman tidak dapat dipahami dengan baik oleh mesin pencari atau pembaca layar.

#### Codingan 2 (HTML)
- **Ada Atribut `lang="en"` pada Tag `<html>`**:  
  Menunjukkan bahwa bahasa halaman ini adalah bahasa Inggris. Ini membantu mesin pencari dan pembaca layar untuk memahami bahasa konten halaman dan meningkatkan aksesibilitas.

---

### 5. Penyusunan Struktur Halaman

#### Codingan 1 (HTML)
- **Struktur HTML Sederhana**:  
  Struktur HTML cukup sederhana, hanya ada beberapa elemen dasar (`<header>`, `<nav>`, `<section>`, dan `<footer>`), tanpa elemen-elemen penting lainnya seperti `<head>` dan `<body>`.

#### Codingan 2 (HTML)
- **Struktur HTML Lengkap**:  
  Struktur HTML lebih lengkap dengan adanya elemen `<head>` dan `<body>`, yang mengikuti standar HTML5 dan praktik pengkodean yang benar.

---

### 6. `grid-template-columns`

#### Codingan 1 (CSS)
- **Kesalahan Penulisan pada `grid-template-columns`**:  
  `grid-template-columns: 20% 1fr 18;`  
  Di sini, lebar kolom grid ditentukan dengan `20%`, `1fr` (fraksi yang fleksibel), dan nilai `18` yang tidak diikuti satuan ukuran. Ini bisa dianggap tidak valid atau menimbulkan hasil yang tidak diinginkan.

#### Codingan 2 (CSS)
- **Penulisan yang Benar pada `grid-template-columns`**:  
  `grid-template-columns: 20% 1fr 18%;`  
  Pada Codingan 2, lebar kolom ketiga ditentukan dengan unit yang benar, yaitu `18%`, yang memastikan semua kolom memiliki ukuran yang valid dan diatur dengan benar.

---

### 7. Margin pada `<body>`

#### Codingan 1 (CSS)
- **Tidak Ada Margin pada `<body>`**:  
  Tidak ada properti margin yang diterapkan pada elemen `<body>`, yang berarti konten halaman akan menempel pada tepi jendela browser.

#### Codingan 2 (CSS)
- **Margin pada `<body>`**:  
  `margin: 10px;`  
  Pada Codingan 2, margin sebesar `10px` ditambahkan pada elemen `<body>`, yang memberikan jarak antara konten halaman dan batas tepi jendela browser.

---

### 8. Kesalahan Penulisan pada Footer di Codingan 1

#### Codingan 1 (CSS)
- **Kesalahan Penulisan Selector Footer**:  
  `I footer { ... }`  
  Pada Codingan 1, ada kesalahan penulisan selector CSS untuk elemen `footer`, yaitu menggunakan `I footer` (seharusnya tanpa huruf "I" sebelum tag `footer`). Ini menyebabkan aturan CSS tidak diterapkan pada elemen `footer`.

#### Codingan 2 (CSS)
- **Penulisan Selector Footer yang Benar**:  
  `footer { ... }`  
  Pada Codingan 2, selector CSS ditulis dengan benar (tanpa huruf `I`), sehingga aturan CSS akan diterapkan dengan benar pada elemen `footer`.

