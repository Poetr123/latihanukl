# 🚚 Program Perhitungan Biaya Pengiriman Paket

## 📝 Penjelasan Singkat
Program ini dibuat untuk menghitung total biaya pengiriman sebuah paket berdasarkan **berat**, **jarak tempuh**, dan **volume barang**.  
Tujuannya supaya pengguna bisa tahu berapa biaya yang harus dibayar sebelum paket dikirim.

Di dalam program, pengguna akan diminta mengisi data seperti:
- Berat paket (kg)
- Jarak pengiriman (km)
- Panjang, lebar, dan tinggi paket (cm)

Dari data itu, program otomatis menghitung **volume** dan menyesuaikan tarifnya:
- Kalau jaraknya **≤ 10 km**, biaya kirim Rp 4.250 per kg  
- Kalau **> 10 km**, biayanya Rp 6.000 per kg  
- Kalau volume lebih dari **100 cm³**, dikenakan tambahan Rp 50.000  

Hasil akhirnya akan menampilkan rincian lengkap:
berat, jarak, volume, biaya per kg, biaya tambahan (kalau ada), dan total biaya kirim.

---

## 📷 Screenshot Hasil Program
Berikut tampilan hasil program setelah dijalankan:

![Screenshot Output Program](images/output.png)
