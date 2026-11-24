# VektorStudio Pro — Resize, HD Upscaler & Vektor EPS 4K

**VektorStudio Pro** adalah aplikasi web pengolahan gambar *all-in-one* yang berjalan 100% secara lokal di browser (*client-side*). Dirancang untuk memperkecil dan mengatur aspek rasio foto, mempertajam gambar buram ke resolusi HD/4K, hingga mengonversi gambar raster (`.JPG`, `.JPEG`, `.PNG`, `.WebP`) menjadi file vektor `.EPS` skala Ultra HD 4K tanpa memerlukan server maupun database.

---

## Fitur Utama & Kegunaan

### 1. Resize & Aspek Rasio
Memperkecil dimensi gambar dan menyesuaikan rasio untuk kebutuhan media sosial, dokumen, atau web.
- **Format Input:** Mendukung `.JPG`, `.JPEG`, `.PNG`, dan `.WebP`.
- **Dimensi Kustom:** Atur lebar dan tinggi secara bebas (px) dengan opsi **Kunci Rasio**, slider skala cepat (`10%–100%`), serta preset ukuran (`25%`, `50%`, `75%`, `1080px`, `720px`).
- **Pilihan Aspek Rasio:** Mendukung rasio **Asli**, **9:16**, **16:9**, **1:1**, **4:3**, dan **3:4**.
- **Mode Penyesuaian:**
  - **Potong (Crop):** Dilengkapi slider titik fokus sumbu X/Y.
  - **Penuh (Fit):** Dilengkapi pilihan latar *Transparan*, *Hitam*, *Putih*, atau *Blur*.
  - **Regangkan (Stretch):** Menyesuaikan penuh ke dimensi target.
- **Ekspor Fleksibel:** Unduh dalam format `JPG`, `PNG`, atau `WebP` dengan pengaturan kualitas kompresi (`10%–100%`) dan estimasi ukuran file secara *real-time*.

### 2. Upscaler HD & Penajam Gambar Buram
Meningkatkan resolusi dan kejernihan gambar buram atau beresolusi rendah.
- **Pilihan Skala Fleksibel:** Skala pengali (`2×`, `3×`, `4×`) atau target resolusi langsung (`HD 1280px`, `Full HD 1920px`, `2K QHD 2560px`, `4K UHD 3840px`).
- **Restorasi Citra:** Menggunakan *progressive multi-step upscaling*, *edge-preserving denoise*, *Unsharp Mask*, serta kontrol kontras & kejernihan.
- **Preset Cepat:** *Standar HD*, *Buram Ekstrem*, *Teks & Dokumen*, dan *Ilustrasi*.
- **Preview Interaktif:** Perbandingan *Split Slider* (Asli Buram vs Hasil HD).

### 3. Vektor EPS 4K
Mengonversi gambar raster menjadi format vektor siap cetak.
- **Skala Output Vektor:** Mendukung `Full HD (1920px)`, `2K QHD (2560px)`, dan `4K UHD (3840px)`.
- **Format Valid:** Menghasilkan file `.EPS` (`%!PS-Adobe-3.0 EPSF-3.0`) dengan konversi kurva Cubic Bézier dan `%%BoundingBox` 4K, serta opsi unduh `.SVG`.
- **Mode Inspeksi:** Dilengkapi tampilan *Split*, *Wireframe* (garis kurva vektor), kontrol zoom/pan, dan modal pratinjau kode EPS.

---

## Cara Menggunakan

1. Buka aplikasi melalui browser (Chrome, Edge, Firefox, atau Safari).
2. Pilih tab fitur yang diinginkan (**Resize & Aspek Rasio**, **Upscaler HD**, atau **Vektor EPS 4K**).
3. Unggah gambar melalui *drag & drop* atau klik tombol unggah (tersedia juga tombol **Coba Gambar Contoh** untuk pengujian instan).
4. Sesuaikan parameter dan lihat hasilnya secara langsung pada layar *preview*.
5. Klik tombol **Unduh** untuk menyimpan hasil, atau gunakan tombol integrasi untuk mengirim hasil langsung ke tab fitur lainnya tanpa mengunggah ulang.


Teknologi yang Digunakan
HTML5 & CSS3
- **Vanilla JavaScript** (Pemrosesan citra, *Unsharp Mask*, *Multi-step Upscaling*, & *EPS PostScript Generator*)
- **ImageTracerJS** (Mesin *vector tracing* dengan *fallback engine* bawaan)
