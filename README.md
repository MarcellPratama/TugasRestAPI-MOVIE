# WPU Movies

## Deskripsi
WPU Movies adalah aplikasi web yang memungkinkan pengguna untuk mencari film berdasarkan judul. Aplikasi ini menggunakan API dari OMDb untuk mendapatkan informasi film dan menampilkan hasilnya dalam format yang menarik. Pengguna dapat melihat detail film yang dipilih dalam modal.

## Fitur
- Mencari film berdasarkan judul.
- Menampilkan daftar film yang ditemukan dengan poster, judul, dan tahun rilis.
- Melihat detail film dalam modal yang berisi informasi lengkap seperti genre, sutradara, dan aktor.

## Teknologi yang Digunakan
- HTML
- CSS (Bootstrap)
- JavaScript (jQuery)
- OMDb API

## Endpoint OMDb API
Aplikasi ini menggunakan dua endpoint dari OMDb API:
1. **Pencarian Film**
   - **URL**: `http://omdbapi.com`
   - **Method**: `GET`
   - **Parameters**:
     - `apikey`: Kunci API (digunakan untuk otentikasi)
     - `s`: Judul film yang dicari

   **Contoh Request**:
   ```http
   GET http://omdbapi.com?apikey=6d36cdbd&s=The%20Godfather
