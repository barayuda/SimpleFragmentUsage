# SimpleFragmentUsage
Latihan IV, Mengenal Flexible UI

---
Mendemonstrasikan fleksibilitas UI dengan memanfaatkan fragment-fragment dalam satu Activity dengan memanfaatkan FragmentManager dan FragmentTransaction. Method Transaction yang akan digunakan diantaranya :

1. **Add()** : untuk menambahkan fragment ke dalam stack dan Activity sehingga dapat muncul dilayar
2. **AddToBackStack()** : untuk menambahkan object transaction ke dalam stack sehingga semua state akan tersimpan. Ketika user kembali ke fragment ini ketika tombol back diklik, tampilan yang dihasilkan akan persis sama.
3. **Replace()** : untuk mengganti existing fragment yang muncul dilayar
4. **Commit()** : untuk mengkonfirmasi bahwa semua proses pada traksaksi fragment dapat dijalankan
5. **setTransition** : untuk menambahkan animasi pada perpindahan fragment
