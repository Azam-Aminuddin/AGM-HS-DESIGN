# Administrasi Tagihan (ke) BPJS
Versi: 2025-01-26

Ini adalah dokumen design pembuatan Aplikasi Administrasi Tagihan (ke) BPJS.

## Tujuan
- Memudahkan administrasi, monitor dan menyelesaikan tagihan ke BPJS.

## Daftar Persona
Kategori Persona/Pemakai aplikasi adalah:
1. Resepsionis
1. Dokter
1. Petugas Laboratorium
1. Petugas Apotik
1. Bagian Keuangan untuk Proses Penagihan
1. Admin Rumah Sakit
1. Direktur Rumah Sakit


### Persona Resepsionis
| Fitur | Via Menu |
|---|--|
| Registrasi Pasien Baru | Menu Personal |
| Ketik keluhan awal pasien | Menu Pasien |
| Ubah Data Pasien | Menu Pasien |
| Alokasi Pasien untuk konsultasi dokter | Menu Pasien |
| Ubah alokasi Pasien untuk konsultasi dokter | Menu Pasien |


### Persona Dokter
| Fitur | Via Menu |
|---|--|
| Lihat Alokasi Pasien | Menu Antrian Pasien |
| Lihat Narasi Keluhan | Menu Pasien |
| Lihat History Kunjungan Sekarang | Menu Pasien |
| Reassign Pasien ke dokter lain | Menu Pasien |
| Alokasi layanan pasien. Contoh: Lab, Rontgen, Buat resep | Menu Kunjungan |
| Registrasi tindakan | Menu Kunjungan |
| Isi Jurnal tindakan | Menu Kunjungan |
| Komen tambahn tentang pasien atau kunjungan | Menu Kunjungan |


### Persona Petugas Apotik
| Fitur | Via Menu |
|---|--|
| Cari Pasien | Menu Antrian Pasien |
| Cari Dokter | Menu Antrian Pasien |
| Untuk Pasien, Registrasi obat yang akan ditagihkan ke BPJS | Menu Resep |


### Persona Petugas Laboratorium
Misal: Petugas Rontgen.

| Fitur | Via Menu |
|---|--|
| Cari Pasien | Menu Antrian Pasien |
| Cari Dokter | Menu Antrian Pasien |
| Untuk Pasien, Registrasi tindakan yang akan ditagihkan ke BPJS | Menu Lab |


### Persona Bagian Keuangan
| Fitur | Via Menu |
|---|--|
| Cari Pasien | Menu Tagihan |
| Cari Dokter | Menu Tagihan |
| Lihat Daftar Tagihan | Menu Tagihan |
| Check Kelengkapan Tagihan | Menu Tagihan |


### Persona Administrasi Rumah Sakit
Untuk memasukkan data pokok rumah sakit sehingga pemakaian aplikasi bisa disederhanakan dengan fitur pencarian menggunakan singkatan.

| Fitur | Via Menu |
|---|--|
| Isi Daftar Kamar Perawatan | Menu Fasilitas |
| Isi Daftar Layanan atau Tindakan Dokter. Supaya bisa di-Search dengan singkatan | Menu Layanan |
| Isi Daftar Obat. Supaya obat bisa di-Search dengan singkatan | Menu Obat |
