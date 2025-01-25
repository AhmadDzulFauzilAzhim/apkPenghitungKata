# Aplikasi Penghitung Kata
 
**ApkPenghitungKata** adalah aplikasi desktop berbasis Java Swing untuk menghitung jumlah kata, karakter, kalimat, dan paragraf dari teks yang dimasukkan pengguna. Selain itu, aplikasi ini juga memungkinkan pengguna untuk mencari kata tertentu dalam teks, serta menyimpan hasil analisis ke file.

## Fitur Utama
1. **Penghitungan Teks**:
   - Jumlah kata
   - Jumlah karakter
   - Jumlah kalimat
   - Jumlah paragraf
2. **Pencarian Kata**:
   - Menghitung jumlah kemunculan kata tertentu dalam teks.
3. **Penyimpanan Hasil**:
   - Menyimpan teks dan hasil analisis ke dalam file menggunakan JFileChooser.
4. **Penghapusan Teks**:
   - Menghapus teks dan reset hasil analisis.
5. **Keluar Aplikasi**:
   - Menutup aplikasi.

## Cara Menggunakan
1. Jalankan aplikasi.
2. Masukkan teks pada area yang disediakan.
3. Masukkan kata yang ingin dicari di kolom "Cari Kata" (opsional).
4. Klik tombol **Hitung Kata** untuk melihat hasil analisis teks.
5. Untuk menyimpan hasil analisis, klik tombol **Simpan Kata** dan pilih lokasi penyimpanan.
6. Klik tombol **Hapus** untuk menghapus teks dan mereset hasil analisis.
7. Klik tombol **Keluar** untuk menutup aplikasi.

## Struktur Antarmuka
- **Label dan Input**:
  - **"Tuliskan katanya dibawah ini"**: Area untuk memasukkan teks.
  - **"Cari Kata"**: Kolom input untuk kata yang ingin dicari.
  - **Hasil analisis**: Label yang menampilkan jumlah kata, karakter, kalimat, paragraf, dan kata yang ditemukan.
- **Tombol**:
  - **Hitung Kata**: Menghitung analisis teks.
  - **Simpan Kata**: Menyimpan hasil analisis ke file.
  - **Hapus**: Menghapus semua input dan hasil analisis.
  - **Keluar**: Menutup aplikasi.

## Dependensi
- **Java SE Development Kit (JDK)**
- **Java Swing**: Untuk antarmuka grafis.

## Cara Menjalankan
1. Pastikan Anda memiliki JDK yang terinstal di komputer Anda.
2. Kompilasi file Java menggunakan perintah berikut:
   ```bash
   javac apkPenghitungKata.java
   ```
3. Jalankan aplikasi dengan perintah berikut:
   ```bash
   java apkPenghitungKata
   ```

## Fungsi Utama dalam Kode
1. **countText()**:
   - Menghitung jumlah kata, karakter, kalimat, paragraf, dan kemunculan kata tertentu.
2. **saveToFile()**:
   - Menyimpan teks dan hasil analisis ke file yang dipilih pengguna.
3. **resetLabels()**:
   - Mereset label hasil analisis menjadi nilai awal.

## Catatan
- Pastikan pengguna memasukkan teks sebelum menghitung hasil analisis.
- Jika tidak ada kata yang dimasukkan di kolom "Cari Kata", aplikasi hanya akan menghitung analisis dasar (jumlah kata, karakter, kalimat, dan paragraf).

---

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo

![App Screenshot](https://github.com/AhmadDzulFauzilAzhim/apkPenghitungKata/blob/main/img/demo%20aplikasi%20penghitung%20kata.gif)
