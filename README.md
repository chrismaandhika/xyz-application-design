# xyz-application-design

Application Design dari contoh kasus aplikasi pinjaman online PT. XYZ.

Asumsi yang digunakan:
- Bahasa yang digunakan adalah Bahasa.
- Proses registrasi tidak membutuhkan approval.
- Pilihan tenor: 3 bulan, 6 bulan, 9 bulan, 12 bulan.
- Tanggal cetak tagihan standar, 5, 15, 25.
- Tanggal cetak tagihan ditentukan dari tanggal diterimanya pengajuan.
- Tidak bisa separuh bayar.
- Tidak ada tagihan perpanjangan jika ada telat bayar.
- Bunga pinjaman di luar scope.
- Denda telat bayar di luar scope.
- Payment di luar scope.
- UI untuk approval peminjaman di luar scope.

High level architecture dapat dilihat di file xyz_component_diagram.png.

ER diagram dapat dilihat di file xyz_erd.png.

API spec dapat dilihat di xyz-openapi-spec.yml (YAML), atau xyz_openapi_spec.pdf (PDF).

Screen draft dapat dilihat di xyz_screen_flow.png.

Raw file di app.diagrams.net dapat ditemukan di dalam folder /raw.