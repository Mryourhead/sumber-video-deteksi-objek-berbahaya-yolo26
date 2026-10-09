# Daftar Sumber Video: Deteksi Objek Berbahaya pada Animasi Kartun Anak (YOLO26)

Repositori pendukung artikel **"Deteksi Objek Berbahaya pada Video Animasi Kartun Anak Menggunakan YOLO26 Berbasis Computer Vision"**
(Ridwan Widiyono, Muslim Hidayat, Iman Ahmad Ihsannuddin; Universitas Sains Al-Qur'an; INSTEK).

## Isi

- `sumber_video.csv`: daftar 52 video YouTube sumber dataset, dengan kolom `no`, `judul_video`, `nama_kanal`, `durasi` (menit:detik), `video_id`, `url`, `tanggal_akses`.

## Ringkasan sumber data

| Item | Nilai |
|---|---|
| Jumlah video | 52 |
| Jumlah kanal | 34 |
| Total durasi | 2 jam 57 menit 20 detik |
| Jenis animasi | 2D (klasik dan modern); sekitar tiga perempat berasal dari seri Tom and Jerry dan Looney Tunes |
| Tanggal akses | 10 sampai 12 Januari 2026 |

## Prosedur singkat

Bagian video yang memuat objek berbahaya dipotong menjadi klip maksimal 30 detik. Frame diekstraksi dengan laju 10 frame per detik, lalu gambar yang memuat objek berbahaya tampil utuh dipilih secara manual. Dari 5.000 gambar yang dikumpulkan, 4.486 gambar teranotasi dan digunakan (514 dikeluarkan karena objek terpotong tepi frame), dengan 5.060 bounding box pada empat kelas: pisau, senjata_tajam, pistol, senapan. Rincian lengkap ada pada artikel.

## Catatan

- Video tidak disimpan atau didistribusikan ulang. Gambar dataset tidak dipublikasikan karena berasal dari video berhak cipta.
- Video YouTube dapat dihapus atau dijadikan privat, sehingga replikasi penuh tidak dapat dijamin.
- Hak cipta video sumber dimiliki pemegang hak ciptanya masing-masing.

## Kontak

Ridwan Widiyono, ridwanwidiyono36@gmail.com
