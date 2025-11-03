# 🚚 Program Perhitungan Biaya Pengiriman Paket

## 📝 Penjelasan Singkat
Program ini dibuat untuk menghitung total biaya pengiriman sebuah paket berdasarkan **berat**, **jarak tempuh**, dan **volume barang**.  
Tujuannya supaya pengguna bisa tahu berapa biaya yang harus dibayar sebelum paket dikirim.

Pengguna akan diminta untuk mengisi:
- Berat paket (kg)
- Jarak pengiriman (km)
- Panjang, lebar, dan tinggi paket (cm)

Dari data itu, program akan menghitung **volume paket** dan menentukan tarifnya:
- Jika jarak **≤ 10 km**, biaya kirim Rp 4.250 per kg  
- Jika **> 10 km**, biaya kirim Rp 6.000 per kg  
- Jika **volume paket lebih dari 100 cm³**, akan ada **biaya tambahan Rp 50.000**  

Biaya tambahan ini hanya muncul **kalau volumenya besar**, sebagai kompensasi ruang ekstra dalam pengiriman.  
Hasil akhirnya akan menampilkan rincian lengkap seperti berat, jarak, volume, biaya per kg, biaya tambahan (jika ada), dan total biaya kirim.

---

## 📷 Screenshot Hasil Program
Berikut tampilan hasil program setelah dijalankan:

![Screenshot Output Program](images/output.png)
