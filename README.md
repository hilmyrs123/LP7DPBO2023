# LP7DPBO2023

Saya Muhammad Hilmy Rasyad Sofyan NIM 2100187 mengerjakan LP12 dalam mata kuliah Desain Pemograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.


Alasan Menggunakan MVVM

ika implementasi model yang ada merangkum logika bisnis yang ada, mungkin sulit atau berisiko untuk mengubahnya. Dalam skenario ini, model tampilan bertindak sebagai adaptor untuk kelas model dan mencegah Anda membuat perubahan besar pada kode model.
Pengembang dapat membuat pengujian unit untuk model tampilan dan model, tanpa menggunakan tampilan. Pengujian unit untuk model tampilan dapat menjalankan fungsionalitas yang sama persis seperti yang digunakan oleh tampilan.
UI aplikasi dapat didesain ulang tanpa menyentuh model tampilan dan kode model, asalkan tampilan diimplementasikan sepenuhnya di XAML atau C#. Oleh karena itu, versi baru tampilan harus berfungsi dengan model tampilan yang ada.
Desainer dan pengembang dapat bekerja secara independen dan bersamaan pada komponen mereka selama pengembangan. Desainer dapat fokus pada tampilan, sementara pengembang dapat mengerjakan model tampilan dan komponen model.
