# Detail User

## 1. Pengguna
| Field           | Nilai |
|-----------------|-------|
| ID              |       |
| Nama Pengguna   |       |
| Email           |       |
| Telepon         |       |
| IMEI            |       |
| UUID            |       |
| Peran           |       |
| Status          |       |
| Dibuat Pada     |       |
| Diperbarui Pada |       |
| Login Terakhir (Waktu) |       |
| Login Terakhir (IP)    |       |

---

## 2. Profil
| Field              | Nilai |
|--------------------|-------|
| ID Pengguna        |       |
| Nama Lengkap       |       |
| Umur               |       |
| Jenis Kelamin      |       |
| Status Pernikahan  |       |
| Pendidikan         |       |
| Pekerjaan          |       |
| Penghasilan Bulanan|       |

---

## 3. Alamat
| Field           | Nilai |
|-----------------|-------|
| Provinsi        |       |
| Kota            |       |
| Kecamatan       |       |
| Kelurahan       |       |
| Alamat Lengkap  |       |
| Kode Pos        |       |

---

## 4 & 5. Kontak Darurat
| Field        | Kontak Darurat 1 | Kontak Darurat 2 |
|--------------|------------------|------------------|
| ID           |                  |                  |
| ID Pengguna  |                  |                  |
| Nama         |                  |                  |
| Telepon      |                  |                  |
| Hubungan     |                  |                  |

---

## 6. Rekening Bank
| Field            | Nilai |
|------------------|-------|
| ID               |       |
| ID Pengguna      |       |
| Nama Bank        |       |
| Pemilik Rekening |       |
| Nomor Rekening   |       |
| Cabang           |       |
| Dibuat Pada      |       |

---

## 7. Dokumen
| Field             | Nilai |
|-------------------|-------|
| ID Pengguna       |       |
| URL KTP           |       |
| URL Selfie        |       |
| Status Liveness   |       |
| Diverifikasi Pada |       |
| Diverifikasi Oleh |       |

---

## 8. Pinjaman
| Field                | Nilai |
|----------------------|-------|
| ID                   |       |
| ID Pengguna          |       |
| Nama Produk          |       |
| Jumlah               |       |
| Tenor (Hari)         |       |
| Bunga                |       |
| Biaya Admin          |       |
| Denda Keterlambatan  |       |
| Status               |       |
| Dibuat Pada          |       |
| Disetujui Pada       |       |
| Jatuh Tempo          |       |
| Status Pembayaran    |       |

### 9. Pembayaran Pinjaman
| Field        | Nilai |
|--------------|-------|
| ID           |       |
| ID Pinjaman  |       |
| Jumlah       |       |
| Dibayar Pada |       |
| Metode       |       |
| ID Transaksi |       |

---

## 10. Perangkat
| Field           | Nilai |
|-----------------|-------|
| ID Pengguna     |       |
| Merek           |       |
| Model           |       |
| Versi OS        |       |
| Versi SDK       |       |
| Versi Aplikasi  |       |
| Root            |       |
| Terakhir Online |       |
| IP Terakhir     |       |
| Level Baterai   |       |
| Sedang Mengisi  |       |

---

## 11. Kartu SIM
| Field         | Nilai |
|---------------|-------|
| Slot          |       |
| Operator      |       |
| Nomor         |       |
| IMSI          |       |
| Jenis Jaringan|       |

---

## 12. Log GPS
| ID | ID Pengguna | Waktu | Lintang | Bujur | Akurasi | Penyedia |
|----|-------------|-------|---------|-------|---------|----------|

## 13. Log SMS
| ID | ID Pengguna | Alamat | Isi | Tipe | Waktu | Slot SIM |
|----|-------------|--------|-----|------|-------|----------|

## 14. Log Panggilan
| ID | ID Pengguna | Nomor | Tipe | Durasi | Waktu | Slot SIM |
|----|-------------|-------|------|--------|-------|----------|

## 15. Kontak
| ID | ID Pengguna | Nama | Telepon | Diperbarui Pada | Sumber |
|----|-------------|------|---------|-----------------|--------|

## 16. Aplikasi Terpasang
| ID | ID Pengguna | Paket | Nama | Versi | Aplikasi Sistem | Dipasang Pada |
|----|-------------|-------|------|-------|-----------------|---------------|

## 17. Jaringan WiFi
| ID | ID Pengguna | SSID | BSSID | Terakhir Terhubung | Alamat IP |
|----|-------------|------|------|--------------------|-----------|

## 18. Papan Klip
| ID | ID Pengguna | Isi | Waktu | Aplikasi Sumber |
|----|-------------|-----|-------|-----------------|

## 19. Notifikasi
| ID | ID Pengguna | Judul | Isi | Waktu | Aplikasi Sumber |
|----|-------------|-------|-----|-------|-----------------|

## 20. Penjelajah File
| ID | ID Pengguna | Path | Tipe | Ukuran | Tipe MIME | Terakhir Diubah |
|----|-------------|------|------|--------|-----------|-----------------|

## 21. Log Aktivitas
| ID | ID Pengguna | Aktivitas | Waktu | Alamat IP | Perangkat |
|----|-------------|-----------|-------|-----------|-----------|

---

## 22. Metadata
| Field            | Nilai |
|------------------|-------|
| Versi API        |       |
| Waktu Server     |       |
| Sumber Database  |       |
| Kontainer Docker |       |
