# Penawaran Rancangan Digital Ekosistem Hamasah International (by Dar Dev)
### Disusun oleh: Dar Developer untuk Mendukung Visi Hamasah International

Rancangan 1 Website Terpadu dengan 2 Layanan Utama (**Publik & App Portal**) dari Dar Developer untuk menyederhanakan pendaftaran, akademik, operasional staff, otomatisasi invoice & kuitansi, serta transparansi wali santri di Mesir.

---

## Struktur Arsitektur Resmi : 1 Website Terpadu (2 Layanan Utama)

### LAYANAN 1 : PUBLIK & PENDAFTARAN (Hamasah International)
**Layanan publik terdepan untuk masyarakat luas, calon santri, dan calon wali:**
- **Profil Lembaga:** Visi misi pimpinan lembaga dan galeri Kairo.
- **Informasi Program:** Brosur digital lengkap program bimbingan studi Al-Azhar.
- **Alur Pendaftaran & Persiapan Keberangkatan:** Panduan tahapan pendaftaran dari awal hingga keberangkatan.
- **Akun Registrasi Keberangkatan Calon Santri:** Akses calon santri untuk cek progres dokumen, visa, jadwal terbang, dan panduan Kairo (Pasti Berangkat).
- **Pusat Informasi & AI Konsultan:** Tanya jawab cerdas 24 jam serta kontak WhatsApp resmi.
- **Artikel Berita Kegiatan Mesir:** Dokumentasi kegiatan santri di Kairo yang dapat ditulis langsung oleh pengurus (CMS Mandiri).

### LAYANAN 2 : APP PORTAL TERINTEGRASI (App Portal Hamasah International)
**Layanan aplikasi internal terproteksi login enkripsi berbasis peran (Role-Based Access):**

1. **Portal Keluarga Hamasah (Wali Santri / Portal Keluarga):**
   - Monitoring absensi harian (Sholat Subuh berjamaah 98%).
   - Capaian tahfidz & perkembangan belajar (Rata-rata Mumtaz 94, Hafalan 7 Juz Mutqin).
   - Catatan evaluasi adab oleh ustaz pembina asrama Madinat Nasr.
   - Unduh dokumen rapor resmi semester Al-Azhar format PDF.
   - Foto dan update kegiatan harian santri di Kairo.
   - Unduh invoice & kuitansi sah pembayaran berstempel format PDF.

2. **Portal Akademik Hamasah (Santri, Pembina & Pengawas / Portal Akademik):**
   - **LMS Video Talaqqi Santri:** Video pembelajaran talaqqi yang dirancang khusus Hamasah International dengan kontrol interaktif, modul materi kitab PDF, silabus kurikulum terstruktur, dan AI Study Partner 24 jam untuk rangkum materi dan konsultasi istilah keilmuan Islam.
   - **Dashboard Rekam Jejak Belajar:** Pemantauan kurikulum talaqqi dan roadmap akademik santri dari awal bergabung (Dauroh Ta'hili) hingga target wisuda sarjana Al-Azhar Kairo (2030).
   - **Laporan Kegiatan Santri di Mesir:** Log aktivitas harian (Subuh berjamaah, Markaz Lughoh, talaqqi Rawaq Al-Azhar, katering asrama, dan mudzakarah malam).
   - **Pencapaian & Achievement:** Portofolio piagam digital, syahadah tahfidz bersanad, dan penghargaan keteladanan asrama.
   - **Disiplin, Presensi & Evaluasi Pengawas:** Rekap kehadiran sholat berjamaah (98.4%), catatan pelanggaran (0 kasus / bersih), dan lembar evaluasi jangka panjang musyrif asrama.
   - **Fitur Pembina:** Kelola materi video talaqqi, bagikan modul kitab klasik, evaluasi tugas berkala, serta susun catatan bimbingan adab santri.

3. **Portal Operasional Hamasah (Staff & Admin / Portal Operasional):**
   - **Auto Financial Generator:** Pembuatan otomatis invoice SPP (INV/HI/2026/XXXX) dan kuitansi sah digital PDF (KWT/HI/2026/XXXX).
   - **Auto-Sync Portal & WA:** Bukti pembayaran langsung tampil di dashboard wali (Portal Keluarga) dan terkirim ke WhatsApp resmi wali.
   - **Berkas Visa Santri:** Tracking paspor, legalisasi 4 kementerian di Jakarta, dan masa berlaku visa pelajar Mesir.
   - **Generate Akun Keberangkatan:** Pembuatan instan akun calon santri untuk akses registrasi keberangkatan di Layanan Publik.
   - **Logistik Asrama Kairo:** Inventaris fasilitas kamar santri ber-AC dan katering harian di Madinat Nasr.

---

## Matriks Akses Berbasis Peran (Role-Based Access)
- **Calon Wali & Calon Santri:** Layanan 1 (Publik & Pendaftaran)
- **Wali Santri:** Layanan 2 (Portal Keluarga)
- **Santri:** Layanan 2 (Portal Akademik)
- **Pembina & Musyrif:** Layanan 2 (Portal Akademik)
- **Staff & Admin Operasional:** Layanan 2 (Portal Operasional)

---

## Roadmap Pengembangan 5 Fase Bertahap
- **FASE 01:** Layanan 1 (Publik, Profil, Berita Kegiatan Mesir & Akun Keberangkatan)
- **FASE 02:** Layanan 2 (Portal Operasional: Staff & Auto Invoice/Kuitansi)
- **FASE 03:** Layanan 2 (Portal Keluarga: Monitoring Wali Santri & Kuitansi PDF)
- **FASE 04:** Layanan 2 (Portal Akademik: Santri, Pembina & LMS AI Study Partner)
- **FASE 05:** Integrasi Database Terpadu & Keamanan Akses Enkripsi

---

## Cara Mencoba Prototype
1. Buka browser: **http://localhost:3000**
2. Jelajahi struktur arsitektur 1 Website Terpadu dengan 2 Layanan Utama.
3. Coba fitur **Akun Registrasi Keberangkatan** calon santri pada Layanan Publik.
4. Coba simulasi **Portal Keluarga Hamasah** untuk monitoring santri & unduh kuitansi PDF.
5. Coba simulasi **Portal Akademik Hamasah** untuk progress maddah & AI study partner.
6. Coba simulasi **Portal Operasional Hamasah** untuk auto-generate invoice & kuitansi sah.
