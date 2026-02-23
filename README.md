# tugas-struktur-data-2

# Python Basic Exercises (Latihan Python Dasar)

Koleksi skrip Python sederhana yang mengimplementasikan berbagai algoritma dasar dan struktur data, seperti manipulasi list, pengecekan string, dan manajemen kamus (*dictionary*).

## 🚀 Fitur Utama

Repositori ini mencakup 5 fungsi utama yang dapat diakses melalui menu interaktif:

1. **Deduplikasi**: Menghapus duplikat dari sebuah list angka tanpa mengubah urutan aslinya.
2. **Intersection**: Mencari irisan (elemen yang sama) di antara dua buah list.
3. **Anagram Checker**: Mengecek apakah dua string merupakan anagram (menggunakan karakter yang sama dengan jumlah yang sama).
4. **First Recurring Character**: Menemukan karakter pertama yang muncul kembali (berulang) dalam sebuah string.
5. **Buku Telepon Mini**: Aplikasi CRUD sederhana berbasis console untuk menyimpan, mencari, dan menampilkan kontak.

---

## 🛠️ Cara Penggunaan

### Prasyarat

Pastikan kamu sudah menginstal Python di komputermu (Versi 3.x direkomendasikan).

### Menjalankan Program

1. Clone repositori ini:
```bash
git clone https://github.com/username-kamu/nama-repo.git

```


2. Masuk ke direktori proyek:
```bash
cd nama-repo

```


3. Jalankan file utama:
```bash
python "Latihan Soal.py"

```



---

## 📖 Penjelasan Logika Kode

| Fungsi | Logika |
| --- | --- |
| `deduplikasi(lst)` | Menggunakan loop untuk membangun list baru berisi elemen unik. |
| `intersection(arr1, arr2)` | Membandingkan dua array dan mengambil elemen yang ada di keduanya. |
| `is_anagram(s1, s2)` | Mengurutkan kedua string dan membandingkan hasilnya. |
| `first_recurring_char(s)` | Menggunakan *nested loop* untuk mencari repetisi karakter pertama. |
| `buku_telepon()` | Memanfaatkan tipe data `dict` untuk penyimpanan pasangan Nama-Nomor. |

---

## 📝 Contoh Tampilan Menu

```text
=== MENU ===
1. Deduplikasi
2. Intersection
3. Anagram
4. First Recurring
5. Buku Telepon
6. Keluar
Pilih: _

daripada *nested loop*.

Apakah ada bagian spesifik atau gaya bahasa tertentu yang ingin kamu ubah?
