# InsMail - Instagram Email Checker
![InsMail](https://github.com/user-attachments/assets/f44de405-9800-47ce-a63b-b0a9da42b359)


**InsMail** adalah program berbasis Python yang dirancang untuk mengecek dan mengumpulkan daftar email yang terkait dengan Instagram. Program ini menawarkan beberapa fitur utama, termasuk mengumpulkan email dengan metode Faker, berdasarkan nama, nomor telepon, atau mengecek validitas email dalam file. Program ini juga dilengkapi dengan tampilan yang interaktif dan mudah digunakan.

> Terima Kasih Telah Menggunakan InsMail! Semoga Bermanfaat 🚀

## Fitur Utama
1. **Generator Email**
     - **Menggunakan Faker**: Menggunakan `locale` tertentu seperti `en_US`, `id_ID`, `en_GB`, dll.
     - **Berdasarkan Nama**: Menghasilkan email dari daftar nama depan atau belakang.
     - **Berdasarkan Nomor**: Menghasilkan email berbasis angka untuk variasi unik.

2. **Pengelola Email**
    - **Memeriksa Email**: Mengecek validitas daftar email dalam file tertentu.
    - **Kelola File**: Memastikan tidak ada duplikat dalam daftar email yang dihasilkan.

## Instalasi 🛠️
1. **Kloning Repository**
    ```bash
    git clone https://github.com/RozhakXD/InsMail.git
    cd InsMail
    ```
2. **Instal Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Jalankan Program**
    ```bash
    python Run.py
    ```

## Masalah yang Mungkin Muncul ❗️
1. **Locale Tidak Tersedia di Faker**
    - **Solusi**: Gunakan locale yang didukung seperti `en_US`, `id_ID`, `en_GB`, atau lainnya yang terdaftar dalam dokumentasi Faker.
2. **Domain Tidak Valid**
    - Jika Anda memasukkan domain yang tidak valid atau tidak ada, program mungkin gagal dalam menghasilkan email.
    - **Solusi**: Pastikan domain sudah benar, misalnya `gmail.com`, `yahoo.com`.
3. **Program Tidak Merespon Setelah Masukan Jumlah yang Besar**
    - Terlalu banyak email yang diminta dapat menyebabkan kelambatan atau crash.
    - **Solusi**: Batasi jumlah email yang ingin dibuat di bawah 1000 untuk menjaga kinerja program tetap optimal.
4. Email Tidak Terdeteksi dalam Pengecekan
    - Daftar email yang diberikan mungkin berisi format yang tidak benar atau data tambahan selain email.
    - **Solusi**: Periksa kembali file daftar email Anda, pastikan hanya berisi alamat email yang valid, satu per baris.
5. Error pada Penyimpanan File
    - Jika file output tidak tersedia atau Anda tidak memiliki izin yang benar di direktori, file mungkin gagal tersimpan.
    - **Solusi**: Pastikan direktori `Penyimpanan/` ada dan Anda memiliki izin yang diperlukan untuk menyimpan file di dalamnya.

## Tangkapan Layar 🖼️
![FunPic_20241026](https://github.com/user-attachments/assets/2d5ba622-1360-4e6d-8c12-a6691382352d)

## Warning ⚠️
- **Penggunaan yang Bertanggung Jawab**: InsMail dibuat untuk tujuan edukasi. Harap digunakan secara etis dan tidak untuk aktivitas yang melanggar kebijakan privasi atau peraturan platform apa pun, termasuk Instagram.
- **Batasan Jumlah Email**: Jika Anda memasukkan jumlah email yang terlalu besar (lebih dari 1000), program dapat melambat atau bahkan berhenti berfungsi dengan optimal. Disarankan untuk memasukkan angka yang lebih kecil.
- **Penggunaan Lokal Faker**: Pastikan bahwa locale yang Anda gunakan tersedia di Faker library. Locale yang tidak didukung dapat menyebabkan error.

## Dukungan ☕
Jika Anda merasa terbantu dengan program ini, Anda dapat mendukung pengembang melalui:
- [Trakteer](https://trakteer.id/rozhak_official/tip)
- [PayPal](https://paypal.me/rozhak9)
- [Saweria](https://saweria.co/rozhak9)

## Kontribusi 👥
Kontribusi selalu diterima! Silakan buka _Issue_ atau kirim _Pull Request_ untuk membantu pengembangan InsMail.

## Lisensi 📜
Proyek ini dilisensikan di bawah MIT License.
