# 🎓 Website Pemrograman Web - UNNES

Proyek praktikum sederhana untuk mata kuliah Pemrograman Web yang mendemonstrasikan konsep dasar HTML, CSS, dan JavaScript dengan sistem login dan halaman informasi mata kuliah.

## 📋 Deskripsi Proyek

Website ini adalah tugas praktikum yang menampilkan halaman login dan halaman informasi mata kuliah Pemrograman Web. Proyek ini dibuat sebagai bagian dari pembelajaran implementasi konsep dasar web development menggunakan HTML, CSS, dan JavaScript.

## ✨ Fitur Utama

- 🔐 **Halaman Login** - Form login dengan NIM dan Password
- 📚 **Informasi Mata Kuliah** - Deskripsi lengkap mata kuliah Pemrograman Web
- 👨‍🏫 **Profil Dosen** - Informasi dosen pengampu
- 📊 **Tabel Materi** - Daftar materi pokok dan sub topik pembelajaran
- 💻 **Praktikum JavaScript** - Demonstrasi output JavaScript (innerHTML, alert, console.log, print)
- 🎨 **Styling Kustom** - Desain dengan CSS eksternal
- 🖼️ **Logo UNNES** - Branding universitas pada setiap halaman

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur halaman web
- **CSS3** - Styling dan layout (file eksternal `style.css`)
- **JavaScript** - Interaktivitas dan fungsi dasar
- **Logo & Gambar** - Asset branding UNNES

## 📁 Struktur Proyek

```
uji-coba-unnes/
├── index.html          # Halaman login
├── belajar.html        # Halaman utama dengan materi
├── style.css           # File styling eksternal
├── logo.png            # Logo UNNES
├── garuda.png          # Gambar Garuda untuk halaman login
└── README.md           # Dokumentasi proyek
```

## 📄 Penjelasan File

### 1. index.html (Halaman Login)
Halaman pertama yang ditampilkan dengan fitur:
- Form login dengan input NIM dan Password
- Logo UNNES di bagian atas
- Gambar Garuda sebagai dekorasi
- Tombol login yang mengarah ke `belajar.html`
- Layout dua kolom (gambar Garuda + form)

### 2. belajar.html (Halaman Materi)
Halaman utama setelah login yang berisi:
- Deskripsi mata kuliah Pemrograman Web
- Informasi dosen pengampu (Riska Dami Ristanto, S.Pd., M.Pd.)
- Tabel materi pembelajaran (HTML, CSS, JavaScript, PHP)
- Praktikum JavaScript dengan berbagai metode output
- Tombol logout untuk kembali ke halaman login
- Tombol print untuk mencetak halaman

### 3. style.css (Stylesheet)
File CSS yang mengatur styling untuk:
- Background dan layout umum
- Styling judul dengan background kuning dan teks merah
- Container konten dengan border dan background putih
- Styling tabel materi (header hijau, cell hijau muda)
- Form login dengan layout flexbox
- Tombol login dan logout
- Responsif dan user-friendly

## 🚀 Cara Menggunakan

### Metode 1: Buka Langsung di Browser
1. Download atau clone repository ini
```bash
git clone https://github.com/username/uji-coba-unnes.git
cd uji-coba-unnes
```

2. Buka file `index.html` dengan browser
```bash
# Double-click index.html di file explorer
# Atau gunakan command line:
open index.html      # Mac
xdg-open index.html  # Linux
start index.html     # Windows
```

3. Klik tombol "Login" untuk masuk ke halaman belajar

### Metode 2: Menggunakan Live Server (VS Code)
1. Install extension "Live Server" di VS Code
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"
4. Browser akan otomatis terbuka di `http://localhost:5500`

### Metode 3: Menggunakan Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Akses di browser: `http://localhost:8000`

## 📚 Materi yang Tercakup

### 1. HTML (HyperText Markup Language)
- HTML Basic - Struktur dasar HTML
- HTML Heading - Penggunaan heading h1-h6
- HTML Image - Menampilkan gambar

### 2. CSS (Cascading Style Sheets)
- CSS Basic - Dasar-dasar CSS
- CSS Color - Pengaturan warna
- CSS Margins - Pengaturan margin

### 3. JavaScript
- JavaScript Basic - Konsep dasar JavaScript
- JavaScript Variable - Penggunaan variabel
- JavaScript Functions - Membuat fungsi

### 4. PHP
- PHP Basic - Dasar-dasar PHP
- PHP Tipe Data - Tipe data dalam PHP
- PHP MySQL Databases - Koneksi ke database

## 🎨 Demonstrasi JavaScript Output

Website ini mendemonstrasikan 5 cara menampilkan output di JavaScript:

1. **innerHTML** - Menulis ke elemen HTML
   ```javascript
   document.getElementById("demo").innerHTML = 6+5;
   ```

2. **document.write()** - Menulis langsung ke dokumen HTML
   ```javascript
   document.write(6+5);
   ```

3. **window.alert()** - Menampilkan alert box
   ```javascript
   window.alert("Login telah berhasil!");
   ```

4. **console.log()** - Menulis ke browser console
   ```javascript
   console.log("Pesan ini hanya muncul di konsol browser.");
   ```

5. **window.print()** - Mencetak halaman
   ```javascript
   window.print();
   ```

## 🎓 Informasi Mata Kuliah

**Nama Mata Kuliah:** Pemrograman Web

**Deskripsi:** Matakuliah ini berisi praktik implementasi konsep dasar Internet Web-Based dan Content Management System dengan bahasa pemrograman HTML, CSS, JavaScript, dan PHP.

**Dosen Pengampu:**
- Nama: Riska Dami Ristanto, S.Pd., M.Pd.
- NIP: 199207112019031012
- Email: rdristanto@mail.unnes.ac.id

## 🎨 Kustomisasi

### Mengubah Warna Tema
Edit file `style.css`:

```css
/* Warna background halaman */
body {
    background-color: #a5a5a5; /* Ubah sesuai keinginan */
}

/* Warna judul */
#Judul {
    background-color: #ffd965; /* Background kuning */
    color: red; /* Teks merah */
}

/* Warna tabel */
th {
    background-color: darkgreen; /* Header tabel */
}

td {
    background-color: #92d050; /* Cell tabel */
}
```

### Menambah Materi Baru di Tabel
Edit `belajar.html` dan tambahkan baris tabel baru:

```html
<tr>
    <td rowspan="3">5</td>
    <td rowspan="3">Bootstrap</td>
    <td>Bootstrap 1 Grid System</td>
</tr>
<tr>
    <td>Bootstrap 2 Components</td>
</tr>
<tr>
    <td>Bootstrap 3 Utilities</td>
</tr>
```

### Mengganti Logo
1. Siapkan logo baru (format PNG/JPG)
2. Rename file menjadi `logo.png` atau update nama di HTML:
```html
<img src="logo-baru.png" alt="Logo UNNES" width="150" height="150">
```

## 📱 Responsive Design

Website ini sudah responsif dengan:
- Container yang menyesuaikan lebar layar
- Flexbox layout untuk halaman login
- Margin dan padding yang proporsional
- Tabel yang dapat di-scroll pada layar kecil

## 🔒 Keamanan

⚠️ **Catatan Penting:**
- Ini adalah proyek pembelajaran, **TIDAK ADA** validasi login yang sebenarnya
- Form login hanya untuk demonstrasi UI/UX
- Tidak ada koneksi ke database atau autentikasi backend
- Tombol login hanya redirect ke halaman belajar

Untuk implementasi production, tambahkan:
- Backend authentication (PHP, Node.js, dll)
- Database untuk menyimpan user credentials
- Password hashing (bcrypt, argon2)
- Session management
- HTTPS connection

## 🐛 Troubleshooting

### Gambar tidak muncul
- Pastikan file `logo.png` dan `garuda.png` ada di folder yang sama dengan HTML
- Check nama file (case-sensitive di Linux)
- Pastikan path gambar benar

### CSS tidak ter-load
- Pastikan file `style.css` ada di folder yang sama
- Check link CSS di HTML: `<link rel="stylesheet" type="text/css" href="style.css">`
- Clear browser cache (Ctrl + F5)

### JavaScript tidak berjalan
- Buka browser console (F12) untuk lihat error
- Pastikan JavaScript enabled di browser
- Check syntax error di console

### Tombol Login tidak berfungsi
- Pastikan nama file `belajar.html` benar (typo di `onclick`)
- Check browser console untuk error
- Pastikan file belajar.html ada di folder yang sama

## 📝 To-Do List (Pengembangan Selanjutnya)

- [ ] Tambahkan validasi form login
- [ ] Implementasi backend dengan PHP
- [ ] Koneksi ke MySQL database
- [ ] Tambah halaman registrasi
- [ ] Implementasi session management
- [ ] Tambah quiz interaktif dengan JavaScript
- [ ] Responsive menu navigation
- [ ] Dark mode toggle
- [ ] Animasi transisi halaman

## 🤝 Kontribusi

Ini adalah proyek pembelajaran. Saran dan feedback sangat diterima:
1. Fork repository
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit changes (`git commit -m 'Menambahkan fitur'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## 📄 Lisensi

Proyek ini dibuat untuk keperluan edukasi dan pembelajaran. Bebas digunakan untuk tujuan akademis.

## 👨‍💻 Developer

Dikembangkan oleh mahasiswa Universitas Negeri Semarang (UNNES) untuk mata kuliah Pemrograman Web.

## 📞 Kontak

Untuk pertanyaan terkait proyek:
- Email: iqbalguntur354@students.unnes.ac.id
- GitHub: (https://github.com/MfBally354)

## 🙏 Credits

- **Universitas Negeri Semarang (UNNES)** - Logo dan branding
- **Dosen Pengampu** - Riska Dami Ristanto, S.Pd., M.Pd.
- **Mata Kuliah** - Pemrograman Web

---

Made with 💻 by UNNES Students | Praktikum Pemrograman Web

⭐ Star repository ini jika membantu pembelajaran kamu!
