# Bookshelf API

Bookshelf API adalah sebuah aplikasi RESTful API yang memungkinkan pengguna untuk mengelola koleksi buku. Pengguna dapat menambahkan, mendapatkan, memperbarui, dan menghapus buku dari koleksi mereka.

## Fitur

- Menambahkan buku baru
- Mendapatkan semua buku
- Mendapatkan buku berdasarkan ID
- Memperbarui informasi buku
- Menghapus buku dari koleksi

## Teknologi yang Digunakan

- Node.js
- Hapi.js
- Nanoid
- Nodemon (untuk pengembangan)

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/repo.git
   cd bookshelf-api
2. Install depedencies:
   ```bash
   npm install
3. Jalankan aplikasi:
   ```bash
   npm run start-dev
Aplikasi akan berjalan pada `http://localhost:9000`

## Endpoints

### 1. Menambahkan Buku

- **URL**: `/books`
- **Method**: `POST`
- **Body**:
  ```json
  {
    "name": "Judul Buku",
    "year": 2021,
    "author": "Nama Penulis",
    "summary": "Ringkasan Buku",
    "publisher": "Penerbit",
    "pageCount": 300,
    "readPage": 100,
    "reading": true
  }

### 2. Mendapatkan Semua Buku

- **URL**: `/books`
- **Method**: `GET`

### 3. Mendapatkan Buku Berdasarkan ID

- **URL**: `/books/{id}`
- **Method**: `GET`

### 4. Memperbarui Buku

- **URL**: `/books`
- **Method**: `PUT`
- - **Body**:
  ```json
  {
    "name": "Judul Buku",
    "year": 2021,
    "author": "Nama Penulis",
    "summary": "Ringkasan Buku",
    "publisher": "Penerbit",
    "pageCount": 300,
    "readPage": 100,
    "reading": true
  }
  
### 5. Mendapatkan Semua Buku

- **URL**: `/books/{id}`
- **Method**: `DELETE`
