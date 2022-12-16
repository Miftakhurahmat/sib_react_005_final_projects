# Website Shopping

# Tentang ini

> Pada projek ini kami ditugaskan untuk melakukan tugas akhir yang berbentuk website. Website ini bertemakan Website Movie yang menggunakan API publik dari OMDB API.

---

# 👥 Kelompok kami terdiri dari

- **Effendi Prakoso | RCTN-KS05-016**
- **Salman Alfarizi | RCTN-KS05-018 (Lead)**
- **Moh. Aulia Miftakhurahmat | RCTN-KS05-021**

---

# Fungsionalitas

1. **Home Pages**

   Pages ini akan menampilkan list movie (dengan default “Superman”), movie akan dengan default menampilkan dalam bentuk kartu kartu movie yang dapat di klik sehingga akan menampilkan details movie tersebut.

2. **Search Pages**

   Pages ini mirip dengan home pages, pengguna dapat menginputkan pada search bar yang terdapat pada navigasi bar. lalu list movie akan muncul sesuai dengan inputan pada search bar. jika inputan tidak ada, maka akan menampilkan error. movie yang muncul juga dapat di klik sehignga akan memunculkan details pada movie tersebut.

3. **Menambahkan dan disimpan kedalam cart**

   Pages ini akan menampilkan halaman tentang anggota kelompok kami

---

# Library yang digunakan

### Library Utama

- [**React.JS**](https://reactjs.org/)
- [**React reduxjs/toolkit**](https://redux-toolkit.js.org/)
- [**React Router**](https://www.npmjs.com/package/react-router-dom)
- [**Axios**](https://chakra-ui.com/)

### Library styling

- [Tailwinds](https://tailwindcss.com/)
- [Daisy UI](https://daisyui.com/)

---

# Tampilan Mockup

[https://www.figma.com/file/Ce2nrtJDgS9lDXaUx6FHpR/fp-4?node-id=0%3A1&t=zAjf3KG0x1bUF20I-1](https://www.figma.com/file/Ce2nrtJDgS9lDXaUx6FHpR/fp-4?node-id=0%3A1&t=zAjf3KG0x1bUF20I-1)

---

## Panduan Menjalankan Secara Lokal

1. Pertama kita clone github nya terlebih dahulu

   <aside>
   💡 git clone [https://github.com/Miftakhurahmat/sib_react_005_final_projects.git](https://github.com/Miftakhurahmat/sib_react_005_final_projects.git)

   </aside>

2. Setelah berhasil. kita masuk ke folder nya terlebih dahulu dengan masuk ke terminal dan memasukan kode berikut

   <aside>
   💡 sib_react_005_final_projects

   </aside>

3. Instalasi library yang digunakan dengan kode berikut

   <aside>
   💡 npm install

   </aside>

4. Setelah selesai, kita bisa menjalakan nya dengan kode berikut

   <aside>
   💡 npm start

   </aside>

---

# Panduan Penggunaan Website

1. Halaman Home

   Pada saat pertama kali mengakses website maka halaman yang pertama ditampilkan adalah halaman home, disini akan menampilkan list movie (default movie yang muncul adalah “Superman”). List movie akan berubah jika pengguna menginputkan kata kunci movie yang diinginkan pada bagian search dan menekan tombol search nya, jika tidak ada movie yang ditemukan akan muncul movies not found.

2. Halaman Search

   Hampir sama seperti halaman home, halaman search akan menampilkan list movie sesuai pencarian yang diinputkan pengguna.

3. Halaman Details Movie

   Halaman ini akan menampilkan details movie jika pengguna menekan kartu movie yang diinginkan.

4. Halaman About Us

   Menampilkan daftar anggota tim projek dan nomer kelompoknya

---

# Penjelasan Struktur Folder **\***Code**\***

Pada folder src, ada beberapa folder yaitu

![image](https://forest-elephant-f34.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F41fc6594-cc15-4b99-b676-9931bbfca38f%2FUntitled.png?id=e7f02c0e-2786-46ff-88f6-0792780c3150&table=block&spaceId=de47c32f-47ab-447d-a34b-d091f7f0c6c1&width=830&userId=&cache=v2)

1. yang pertama terdapat folder app yang digunakan untuk membuat store.js untuk keperluan state global menggunakan bantuan tools redux toolkits.

2. Berikutnya terdapat folder components, folder ini berisi Card.js yang menampilkan component movie dalam bentuk Card yang nantinya akan dapat digunakan kembali, lali ada Footer.js berisi komponen footer, dan Navbar.js yang berisi untuk membuat navigasi bar.

3. Folder features berguna untuk membuat slice yang nantinya akan digunakan untuk membuat fungsi menyimpan kedalam state global dengan bantuan redux toolkits.

4. Folder images berisi gambar anggota kelompok yang akan digunakan pada halaman about us.

5. Folder pages akan berisi 3 file utama yaitu About menampilkan anggota kelompok, Details akan digunakan untuk menampilkan details film yang di klik pada saat di halaman home, dan halaman home akan memunculkan list movie secara default value ataupun sesuai dengan inputan user pada search bar di navbar. .
