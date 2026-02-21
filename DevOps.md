## Materi Review Dasar DevOps

## Penghantar The Three Way
- Apabila dalam bidang manufaktur dikenal istilah order lead times, di dunia DevOps terdapat istilah code deployment lead times, yakni waktu yang diperlukan untuk beralih dari “perubahan atau penambahan kode yang di-commit atau diunggah ke dalam version control system (seperti Git) oleh tim Developer” menjadi “kode berjalan dengan baik di lingkungan production”

Tiga prinsip utama atau **The Three Ways**
1. PrinsiTerkait ALur Kerja. Mampu mangakselerasikan penyelesaian dan penyerahan pekerjaan dari developer ke IT Operations hingga ke pengguna Aplikasi (End Users)
2. Prinsip Terkait Umpan Balik. Menciptakan sistem kerja yang lebih aman dan lebih baik
3. Prinsip Terkait Proses Belajar dan Eksperiment Berkelanjutan. Menciptkan kultur pertumbuhan antar pemahaman untuk mengulang atau latihan sebagai syarat penguasai dalam pemahaman materi. Selanjutnya, Kesadaran terus berexperimen sebagai peningkatan keterampilan dalam pengambilan resiko dan proses belajar baik dari kegagalan

# 1. Prinsip Alur Kerja
- Prinsip ini menjelaskan bahwa kita membutuhkan alur kerja yang cepat dan lancar dalam proses pengembangan aplikasi
- Alur kerja, mulai dari Penulisan Code (Developer) -> Penyiapan Infrastruktur -> Proses Deploy (IT Operation) -> End User -> Sampai terasa manfaat atau nilai aplikasi (fitur/perbaruan/update)
- metode untuk mengoptimalkan alur kerja :
 1. Membuat Pekerjaan Menjadi Tampak
    - Agar bisa mengidentifikasi mana pekerjaan/tugas yang punya proses pengerjaan yang baik dan mana yang sedang dalam antrean atau bahkan terhenti, kita perlu membuat alur kerja yang sejelas-jelasnya. Salah satu metode terbaik untuk melakukan ini adalah menggunakan papan kerja visual, seperti Kanban board atau Scrum board. Semacam card (kartu) baik fisik maupun digital. ada pelabelan status "Ready", “Done”, “ In Production", “Delivered” atau      
<img width="835" height="410" alt="image" src="https://github.com/user-attachments/assets/d22ec2ed-f3ab-44d0-8e19-d926f41f3435" />

 2. Membatasi Work In Process (WIP).
    Sebagai manusia, multitasking adalah sesuatu yang harus Anda hindari dalam melakukan aktivitas. Coba pikirkan, hanya sekadar menyelesaikan tugas sederhana seperti menyortir bentuk geometris saja, waktu kita akan tersita secara signifikan saat melakukan banyak tugas secara bersamaan. Berpatokan Card Board
 3. Mengurangi Skala Batch yang Dikerjakan
     ketahuilah bahwa memproduksi dalam skala batch yang besar dapat menghasilkan tingkat WIP (work in process) yang tinggi dalam alur kerja pabrik. Hasilnya adalah lead time (waktu yang diperlukan untuk membuat sebuah produk hingga akhirnya dikirim ke pelanggan) akan menjadi lama dan kualitas produk pun buruk. Jika ditemukan ada masalah atau kecacatan di salah satu panel bodi, seluruh panel bodi pada batch tersebut harus dibuang.
    <img width="1059" height="319" alt="image" src="https://github.com/user-attachments/assets/a058c68d-13ae-4ea1-a0c1-9fedea77ec4e" />

    Oleh karena itu, selaras seperti yang terjadi di manufaktur, di dunia IT pun perlu diterapkan single-piece flow. Di DevOps, hal itu dapat diwujudkan dengan praktik Continuous Deployment, di mana setiap perubahan kode yang dilakukan pada version control system (seperti Git) diintegrasikan, diuji, dan di-deploy ke lingkungan production secara bertahap dan dalam unit/cakupan kode yang tidak terlalu besar. Dengan demikian, alur kerja yang ada bisa tercipta makin baik dan kualitas perangkat lunak dapat kian meningkat

 5. Memangkas Jumlah Handoff
 6. Mengidentifikasi dan Memperbaiki Constraint

    

