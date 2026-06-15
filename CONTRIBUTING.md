# Panduan Kontribusi (CONTRIBUTING.md)

Terima kasih atas ketertarikan Anda untuk berkontribusi di repositori "Buku Tamu Kelas"! 
Untuk menjaga agar repositori ini tetap bersih dan terorganisir, mohon ikuti aturan berikut:

## 🚦 Langkah-Langkah Berkontribusi

1. **Buat Issue Terlebih Dahulu**
   - Sebelum mengubah kode, silakan buat _Issue_ baru di repositori utama.
   - Gunakan format judul: `Add [Nama Lengkap Anda] to Guestbook`.
   - Tunggu hingga Instruktur/Maintainer merespon dan memberikan lampu hijau.

2. **Fork dan Clone**
   - Jangan melakukan *push* ke repositori ini secara langsung.
   - Lakukan **Fork** ke akun GitHub Anda, lalu jalankan perintah `git clone [url-fork-anda]` ke komputer lokal Anda.

3. **Gunakan Branch Baru**
   - Biasakan tidak bekerja di branch `main`.
   - Buat branch baru: `git checkout -b feat/add-[nama-anda]`.

4. **Tambahkan Nama Anda**
   - Buka file `index.html`.
   - Cari baris komentar `<!-- MAHASISWA: Tambahkan Card HTML Anda di BAWAH BARIS INI -->`.
   - Tambahkan blok HTML berikut, ganti bagian di dalam kurung kurawal sesuai dengan data diri Anda:
   
   ```html
   <div class="card">
       <h3>{NAMA LENGKAP ANDA}</h3>
       <p class="nim">{NIM ANDA}</p>
       <p class="quote">"{KUTIPAN / MOTIVASI / KATA-KATA MUTIARA ANDA}"</p>
   </div>
   ```

5. **Commit dan Push**
   - Jika *Issue* Anda bernomor `#5`, maka commit message Anda harus mengandung kalimat penutup _Issue_.
   - Contoh: `git commit -m "feat: tambahkan nama saya (Closes #5)"`.
   - Lakukan push: `git push origin feat/add-[nama-anda]`.

6. **Kirim Pull Request (PR)**
   - Masuk ke GitHub, dan buat _Pull Request_ dari repositori Fork Anda menuju ke repositori utama (ini).
   - Tunggu _Code Review_ dari Maintainer.

Terima kasih telah belajar dan berkontribusi! 🎉
