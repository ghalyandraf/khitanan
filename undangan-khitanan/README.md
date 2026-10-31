# Undangan Digital Tasyakuran Khitanan

Website demo statis untuk di-hosting gratis di Vercel.

## Menjalankan lokal
Buka `index.html` di browser, atau gunakan ekstensi Live Server di VS Code.

## Mengubah data demo
Buka `index.html`, cari bagian `const UNDANGAN = {` mendekati bagian paling bawah. Ubah:
- `namaAnak`
- `namaAyah`
- `namaIbu`
- `tanggalTeks`
- `waktu`
- `namaTempat`
- `alamat`
- `whatsapp` (format 62..., tanpa + atau spasi)
- `mapsUrl`
- `fotoAnak` (URL gambar)

## Deploy ke Vercel
1. Buat repository GitHub baru dan upload `index.html` (boleh juga upload folder ini).
2. Masuk ke https://vercel.com dan pilih Add New → Project.
3. Import repository GitHub.
4. Untuk website statis ini, pilih framework preset `Other`, biarkan build command dan output directory kosong, lalu klik Deploy.
5. Vercel akan memberi URL publik.

Catatan:
- Foto demo memakai URL gambar eksternal; koneksi internet diperlukan untuk memuatnya.
- Link Maps, nomor WhatsApp, dan foto harus diganti dengan data asli sebelum undangan dibagikan.
- Tombol musik saat ini berupa demo UI; belum memutar audio.
