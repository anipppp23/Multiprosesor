# Multiproseso
![image](https://github.com/user-attachments/assets/3ebc6482-f13e-4215-92d0-e8f76647ea3d)
Berikut adalah penjelasan singkat tentang arsitektur multiprosesor simetris (SMP) dan asimetris (AMP):

### Arsitektur Multiprosesor Simetris (SMP)
Arsitektur multiprosesor simetris (SMP) adalah sistem di mana dua atau lebih prosesor memiliki akses yang sama terhadap memori dan perangkat input/output (I/O). Dalam arsitektur ini, semua prosesor memiliki peran yang setara dan dapat menjalankan tugas secara bersamaan. Keuntungan dari SMP adalah kemampuannya untuk meningkatkan kinerja dengan membagi beban kerja di antara prosesor. SMP sering digunakan dalam server dan sistem yang memerlukan pemrosesan paralel, seperti database dan aplikasi yang memerlukan kecepatan tinggi.

**Ciri-ciri SMP:**
- Semua prosesor memiliki akses yang sama ke memori dan I/O.
- Prosesor dapat berbagi data dan sumber daya dengan mudah.
- Memungkinkan pemrosesan paralel yang efisien.

### Arsitektur Multiprosesor Asimetris (AMP)
Arsitektur multiprosesor asimetris (AMP) adalah sistem di mana prosesor memiliki peran yang berbeda dan tidak semua prosesor memiliki akses yang sama terhadap memori dan I/O. Dalam arsitektur ini, satu atau beberapa prosesor dapat bertindak sebagai prosesor utama yang mengelola tugas, sementara prosesor lainnya berfungsi sebagai prosesor pendukung. AMP sering digunakan dalam sistem yang memerlukan pengolahan data yang berbeda-beda, seperti sistem embedded dan aplikasi real-time.

**Ciri-ciri AMP:**
- Prosesor memiliki peran yang berbeda (utama dan pendukung).
- Akses memori dan I/O tidak merata di antara prosesor.
- Cocok untuk aplikasi yang memerlukan pengolahan data yang spesifik.

### Kesimpulan
Kedua arsitektur ini memiliki kelebihan dan kekurangan masing-masing. SMP lebih cocok untuk aplikasi yang memerlukan pemrosesan paralel yang efisien, sedangkan AMP lebih sesuai untuk aplikasi yang memerlukan pengolahan data yang berbeda-beda dengan peran prosesor yang spesifik. Pemilihan arsitektur tergantung pada kebutuhan aplikasi dan tujuan sistem yang ingin dibangun.
