# Simple Project
Merupakan proyek berbasis Java dengan arsitektur MVC yang dirancang untuk mengelola data produk. Proyek ini mencakup fitur CRUD (Create, Read, Update, Delete) untuk produk, serta otentikasi pengguna. Dikembangkan menggunakan Java EE dan JSP

## Fitur Utama
1. **Manajemen Produk**:
   - Tambah, lihat, edit, dan hapus produk.
2. **Otentikasi Pengguna**:
   - Mengelola proses login dan otorisasi pengguna.
3. **Arsitektur MVC**:
   - Pemisahan antara Model, View, dan Controller untuk meningkatkan modularitas dan pemeliharaan kode.

## Struktur Proyek
- **`src/java/controllers/`**: Berisi logika kontrol aplikasi, seperti `AuthController` untuk otentikasi dan `ProductController` untuk produk.
- **`src/java/models/`**: Berisi model data aplikasi, seperti `Product`.
- **`web/`**: Berisi halaman JSP untuk tampilan, termasuk `index.jsp`, halaman produk (`add.jsp`, `edit.jsp`, `view.jsp`), dan konfigurasi kontekstual.

## Teknologi yang Digunakan
- **Java EE**: Platform utama untuk pengembangan aplikasi web.
- **JSP (JavaServer Pages)**: Untuk tampilan.
- **NetBeans**: Sebagai IDE utama untuk proyek ini.

## Cara Menjalankan
1. Unduh dan instal **NetBeans**.
2. Impor proyek ini sebagai proyek Java di NetBeans.
3. Atur server aplikasi (contohnya, Apache Tomcat) untuk menjalankan aplikasi.
4. Jalankan file `index.jsp` sebagai entry point.
