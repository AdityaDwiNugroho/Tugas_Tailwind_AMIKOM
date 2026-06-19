# Penjelasan 10 Class Tailwind CSS - Tugas Navbar

Berikut adalah penjelasan mengenai minimal 10 class Tailwind CSS yang digunakan pada navbar proyek ini sesuai dengan ketentuan tugas praktikum:

1. **`bg-purple-900`**
   * **Fungsi:** Menentukan warna latar belakang (background) navbar menjadi ungu tua (shade 900 pada palet Tailwind CSS). Hal ini memenuhi kriteria tugas untuk mengubah warna navbar menjadi ungu.

2. **`flex`**
   * **Fungsi:** Mengubah tipe display elemen menjadi Flexbox. Class ini mempermudah penyusunan elemen anak (logo, menu, tombol) secara sejajar dalam satu baris maupun kolom.

3. **`justify-between`**
   * **Fungsi:** Mendistribusikan ruang kosong secara merata di antara elemen anak di dalam flex container. Elemen pertama (logo) akan merapat ke ujung kiri, sedangkan elemen terakhir (tombol hamburger/login) akan merapat ke ujung kanan.

4. **`items-center`**
   * **Fungsi:** Mengatur perataan vertikal elemen anak agar berada tepat di tengah-tengah flex container (sama seperti `align-items: center` pada CSS murni).

5. **`transition-transform`**
   * **Fungsi:** Mengaktifkan efek transisi animasi halus saat terjadi perubahan transformasi (transform), seperti skala (`scale`) saat elemen diberi efek hover.

6. **`duration-300`**
   * **Fungsi:** Mengatur durasi waktu animasi transisi selama 300 milidetik (0.3 detik) sehingga efek perpindahan warna atau skala terasa mulus dan tidak kaku.

7. **`hover:scale-110`**
   * **Fungsi:** Memberikan efek pembesaran skala elemen sebesar 110% (scale 1.1) saat kursor menyentuh elemen tersebut (efek zoom halus pada logo).

8. **`hidden`**
   * **Fungsi:** Menyembunyikan elemen dari tampilan layar (sama seperti `display: none` pada CSS murni). Digunakan untuk menyembunyikan menu mobile secara default sebelum di-klik.

9. **`md:flex`**
   * **Fungsi:** Mengubah display elemen menjadi Flexbox hanya saat ukuran layar mencapai ukuran medium ke atas (lebar layar ≥ 768px). Class ini memastikan menu navigasi utama hanya tampil di layar desktop/tablet.

10. **`rounded-lg`**
    * **Fungsi:** Memberikan sudut membulat (border-radius) berukuran medium-large (8px) pada elemen. Digunakan pada tombol Login agar terlihat modern dan premium.

11. **`bg-orange-500`** *(Bonus)*
    * **Fungsi:** Memberikan warna latar belakang oranye pada tombol Login sesuai instruksi tugas nomor 7.

12. **`hover:bg-orange-600`** *(Bonus)*
    * **Fungsi:** Mengubah warna latar belakang tombol menjadi oranye yang lebih gelap saat diarahkan kursor (hover effect).
