# Day-1--Super-Mario-_Ikrar-Bismi-Rabbik
MISI PROYEK WORKSHOP REPOSITORY GITHUB PUBLIC: DOKUMENTASI KEGIATAN WORKSHOP
# Building with AI, Managing Change with GitHub

Dokumentasi kegiatan **Day 1 Proyek Workshop** mengenai penggunaan Artificial Intelligence (AI), Git, dan GitHub untuk membantu proses pengembangan proyek serta mengelola perubahan kode.

##  Identitas Peserta

- **Nama:** Ikrar Bismi Rabbik
- **Kelompok:** 6 Super Mario
- **Kegiatan:** Day 1 Proyek Workshop
- **Materi:** Building with AI, Managing Change with GitHub

---

##  Deskripsi Repository

Repository ini dibuat sebagai dokumentasi dan media pembelajaran dari kegiatan Day 1 Proyek Workshop yang membahas dasar-dasar penggunaan AI, Git, dan GitHub.

Di dalam repository ini terdapat rangkuman materi workshop, pengetahuan baru yang diperoleh, serta dokumentasi pembelajaran mengenai cara memanfaatkan AI dalam proses pengembangan aplikasi dan menggunakan GitHub untuk mengelola perubahan proyek.

##  Tujuan Repository

Repository ini bertujuan untuk:

- Mendokumentasikan materi yang disampaikan selama kegiatan workshop.
- Memahami konsep dasar Git dan GitHub beserta fungsinya.
- Mempelajari cara menggunakan AI untuk membantu membuat dan mengembangkan aplikasi.
- Memahami proses version control untuk mengelola perubahan file dan proyek.
- Menjadi referensi pembelajaran dalam menggunakan GitHub untuk menyimpan dan mengembangkan proyek.

---

##  Rangkuman Materi Workshop

### 1. Prompt Engineering

Prompt Engineering merupakan cara merancang instruksi agar AI dapat memberikan jawaban yang tepat, relevan, dan sesuai dengan kebutuhan pengguna.

Prompt adalah instruksi atau masukan yang diberikan kepada model AI untuk memperoleh hasil tertentu. Prompt dapat berupa pertanyaan sederhana, kata kunci, instruksi kompleks, maupun potongan kode.

**Struktur prompt yang baik terdiri dari empat bagian:**

- **Role:** Menentukan peran yang harus dijalankan oleh AI.
- **Task:** Menjelaskan tugas yang harus dikerjakan.
- **Context:** Memberikan informasi atau latar belakang yang dibutuhkan.
- **Format:** Menentukan bentuk hasil atau jawaban yang diinginkan.

Pemberian konteks yang jelas dan instruksi yang spesifik dapat membantu AI menghasilkan jawaban yang lebih sesuai dibandingkan hanya memberikan perintah singkat tanpa penjelasan.

**Keuntungan Prompt Engineering:**
- Meningkatkan performa model AI.
- Mengurangi bias dan respons yang tidak sesuai.
- Meningkatkan kontrol dan konsistensi hasil.
- Memberikan pengalaman penggunaan yang lebih baik.

### 2. Pengenalan Git

Git merupakan *Version Control System* (VCS) yang digunakan untuk melacak perubahan pada file, termasuk informasi mengenai siapa yang melakukan perubahan dan kapan perubahan tersebut dilakukan.

Git diciptakan oleh Linus Torvalds pada tahun 2005 dan digunakan untuk membantu pengelolaan perubahan dalam suatu proyek.

**Tiga komponen utama dalam Git Workflow:**

1. **Working Directory**

   Merupakan tempat file proyek disimpan dan dikerjakan. Pengguna dapat membuat, mengedit, maupun menghapus file di dalamnya.

2. **Staging Area**

   Merupakan tempat untuk menampung perubahan file yang akan dimasukkan ke dalam commit berikutnya.

3. **Git Directory (Repository)**

   Merupakan tempat Git menyimpan metadata dan informasi perubahan proyek yang diperlukan untuk mengelola version control.

### 3. Perbedaan Git dan GitHub

Git dan GitHub memiliki fungsi yang berbeda, tetapi saling berkaitan dalam proses pengembangan proyek.

| Git | GitHub |
|---|---|
| Sistem version control terdistribusi. | Platform berbasis web. |
| Digunakan untuk melacak perubahan proyek secara lokal. | Digunakan untuk menyimpan repository Git secara online. |
| Dijalankan melalui terminal atau aplikasi yang mendukung Git. | Digunakan untuk mengelola repository dan mendukung kolaborasi. |

Dengan menggunakan keduanya, pengembang dapat mengelola perubahan proyek secara terstruktur serta menyimpan salinan repository secara online.

### 4. Perintah Dasar Git

Berikut beberapa perintah Git yang diperkenalkan selama workshop:

| Perintah | Fungsi |
|---|---|
| `git init` | Membuat repository Git baru pada direktori proyek. |
| `git add .` | Memasukkan perubahan file ke staging area. |
| `git add --all` | Menambahkan seluruh perubahan ke staging area. |
| `git commit -m "message"` | Menyimpan perubahan ke dalam repository dengan pesan commit. |
| `git clone <url>` | Menyalin repository dari GitHub ke komputer lokal. |
| `git remote add origin <url>` | Menghubungkan repository lokal dengan repository remote. |
| `git push origin main` | Mengirim perubahan dari branch lokal ke GitHub. |
| `git pull origin main` | Mengambil dan menggabungkan perubahan dari repository remote. |

Perintah-perintah tersebut merupakan dasar yang digunakan dalam proses pengelolaan dan pengembangan proyek menggunakan Git dan GitHub.

### 5. Instalasi dan Konfigurasi Git

Sebelum menggunakan Git, diperlukan proses instalasi dan konfigurasi identitas pengguna.

**Memeriksa instalasi Git:**

```bash
git --version
```

**Mengatur identitas pengguna:**

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

**Memeriksa konfigurasi:**

```bash
git config --global --list
```

Konfigurasi identitas ini digunakan untuk mengenali pengguna yang melakukan commit pada repository.

### 6. Konfigurasi Visual Studio Code

Workshop juga membahas persiapan Visual Studio Code agar dapat digunakan melalui terminal.

Langkah-langkahnya:

1. Menginstal Visual Studio Code.
2. Membuka aplikasi Visual Studio Code.
3. Menekan `Ctrl + Shift + P` pada Windows atau `Command + Shift + P` pada macOS.
4. Mencari perintah `Shell Command: Install 'code' command in PATH`.
5. Membuka terminal dan menjalankan perintah berikut:

```bash
code --version
```

Perintah tersebut digunakan untuk memastikan bahwa command line Visual Studio Code sudah dapat digunakan.

### 7. Menghubungkan Repository dengan GitHub

Repository lokal dapat dihubungkan dengan GitHub melalui beberapa langkah.

**Membuat repository Git lokal:**

```bash
git init
```

**Menghubungkan repository lokal dengan GitHub:**

```bash
git remote add origin <repository-url>
```

**Mengirim perubahan ke GitHub:**

```bash
git push origin main
```

Selain itu, repository yang sudah tersedia di GitHub dapat disalin ke komputer lokal menggunakan:

```bash
git clone <repository-url>
```

### 8. SSH Key dan Koneksi GitHub

SSH (Secure Shell) digunakan untuk menghubungkan komputer dengan GitHub melalui autentikasi menggunakan SSH Key.

Workshop memperkenalkan penggunaan algoritma Ed25519 untuk membuat SSH Key.

**Membuat SSH Key:**

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Setelah SSH Key dibuat, public key perlu ditambahkan ke pengaturan SSH and GPG Keys pada akun GitHub.

Koneksi dapat diperiksa menggunakan perintah:

```bash
ssh -T git@github.com
```

Jika berhasil, terminal akan menampilkan pesan autentikasi berhasil dari GitHub.

### 9. Proyek Praktik: Student Task Planner

Pada bagian akhir workshop, peserta diarahkan untuk membuat proyek sederhana berupa **Student Task Planner** dengan bantuan AI.

Tahapan pengerjaan proyek yang diperkenalkan:

1. Menginstal platform AI-assisted seperti ChatGPT, Claude, atau Antigravity.
2. Menulis prompt untuk membuat aplikasi atau website.
3. Menambahkan proyek ke Git menggunakan `git init`.
4. Melakukan commit dan push proyek ke GitHub.
5. Melakukan perubahan atau pengembangan pada proyek.
6. Melakukan commit dan push kembali untuk menyimpan perubahan terbaru.

Proyek ini bertujuan untuk menggabungkan penggunaan AI dalam proses pembuatan aplikasi dengan GitHub sebagai media pengelolaan dan penyimpanan perubahan proyek.

---

##  Poin Penting dan Pengetahuan Baru

Beberapa hal penting yang saya pelajari dari kegiatan workshop ini adalah:

1. **Pentingnya prompt yang spesifik.** Saya mempelajari bahwa hasil yang diberikan AI sangat dipengaruhi oleh instruksi dan konteks yang diberikan kepada AI.

2. **Memahami fungsi Git dan GitHub.** Sebelumnya, keduanya mungkin terlihat memiliki fungsi yang sama, tetapi ternyata Git digunakan untuk mengelola perubahan secara lokal, sedangkan GitHub menjadi platform untuk menyimpan repository secara online dan mendukung kolaborasi.

3. **Memahami konsep version control.** Dengan Git, setiap perubahan proyek dapat dicatat sehingga proses pengembangan menjadi lebih terorganisir.

4. **Mengenal Git Workflow.** Saya mempelajari alur kerja dari Working Directory, Staging Area, hingga Git Repository sebelum perubahan disimpan melalui commit.

5. **Mengenal perintah dasar Git.** Saya mendapatkan pengetahuan mengenai penggunaan `git init`, `git add`, `git commit`, `git push`, dan `git pull`.

6. **Memahami autentikasi SSH.** Saya mempelajari bahwa SSH Key dapat digunakan untuk menghubungkan komputer dengan GitHub melalui proses autentikasi.

7. **Menggabungkan AI dengan GitHub.** AI dapat membantu proses pembuatan aplikasi, sedangkan Git dan GitHub membantu mengelola serta menyimpan perkembangan proyek.

---

##  Pendapat Pribadi tentang Day 1 Proyek Workshop

Menurut saya, kegiatan workshop Day 1 ini memberikan pengetahuan dan pengalaman baru, terutama dalam memahami penggunaan AI serta Git dan GitHub dalam proses pengembangan proyek.

Materi yang paling menarik bagi saya adalah Prompt Engineering karena saya jadi memahami bahwa memberikan instruksi kepada AI tidak cukup hanya dengan perintah singkat. Diperlukan konteks, tujuan, dan format yang jelas agar hasil yang diberikan sesuai dengan kebutuhan.

Selain itu, saya juga mendapatkan pemahaman yang lebih baik mengenai Git dan GitHub, khususnya bagaimana perubahan pada suatu proyek dapat dikelola menggunakan version control. Saya merasa materi ini cukup penting karena GitHub merupakan salah satu platform yang banyak digunakan dalam dunia pengembangan perangkat lunak.

Menurut saya, praktik membuat Student Task Planner juga menjadi bagian yang menarik karena peserta tidak hanya mempelajari teori, tetapi juga diarahkan untuk menggabungkan AI dengan GitHub dalam sebuah proyek sederhana.

Secara keseluruhan, workshop hari pertama ini sangat bermanfaat untuk menambah wawasan dan menjadi bekal bagi saya dalam mempelajari pengembangan aplikasi serta penggunaan GitHub secara lebih lanjut. Saya berharap dapat menerapkan materi yang sudah dipelajari dan lebih terbiasa menggunakan Git dalam mengelola proyek ke depannya.

---

##  Referensi

- Materi presentasi workshop: *Building with AI, Managing Change with GitHub* — Nugi Farhan (Senior Product Designer).
- Google Cloud — [What is Prompt Engineering?](https://cloud.google.com/discover/what-is-prompt-engineering)
- Codepolitan — Referensi pengenalan Git yang dicantumkan dalam materi workshop.

---

**Dokumentasi ini dibuat sebagai bagian dari tugas Day 1 Proyek Workshop dan media pembelajaran pribadi dalam mengenal AI, Git, serta GitHub.**
