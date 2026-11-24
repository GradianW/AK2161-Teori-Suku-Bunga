# Persiapan Kuis Obligasi - AK2161 Teori Suku Bunga

Direktori ini disusun khusus untuk persiapan **kuis terakhir sebelum UAS** mata kuliah **AK2161 Teori Suku Bunga (Theory of Interest)** yang berfokus pada materi **Obligasi (Bab 12--14)**.

---

## 📄 Berkas Utama

1. **Cheatsheet Ringkas 1 Lembar Bolak-Balik (`Cheatsheet_1Lembar_BolakBalik.pdf`)** *(Direkomendasikan untuk disalin tulis tangan)*:
   - **[`Cheatsheet_1Lembar_BolakBalik.pdf`](Cheatsheet_1Lembar_BolakBalik.pdf)**: Tata letak padat **tepat 2 halaman (1 lembar A4 bolak-balik)** berformat 2 kolom yang diurutkan berdasarkan tingkat kemunculan soal di kuis/UAS ITB:
     - **Sisi Depan (Halaman 1 — Tier 1)**: Kamus simbol & konversi frekuensi, 4 rumus harga obligasi, jadwal amortisasi & rumus langsung, matriks 3 metode valuasi antar tanggal kupon, serta *callable/putable bond*.
     - **Sisi Belakang (Halaman 2 — Tier 2 \& 3)**: Aproksimasi YTM, reinvestasi kupon, kupon/yield tidak konstan, *serial bonds* (Makeham), *straight line* & *sinking fund* ($j \neq i$), teori klasifikasi singkat, serta *checklist* & 7 jebakan maut.
   - **[`Cheatsheet_1Lembar_BolakBalik.tex`](Cheatsheet_1Lembar_BolakBalik.tex)**: Kode sumber LaTeX.

2. **Cheatsheet Rumus Lengkap (`Cheatsheet_Rumus_Obligasi.pdf`)**:
   - **[`Cheatsheet_Rumus_Obligasi.pdf`](Cheatsheet_Rumus_Obligasi.pdf)**: Rangkuman rumus lengkap Bab 12 s.d. Bab 14 (glosarium simbol, klasifikasi obligasi, 4 rumus harga, jadwal amortisasi & *sinking fund*, matriks 3 metode antar kupon, aproksimasi YTM, matriks *callable/putable*, *serial bonds* Makeham, variasi kupon/yield umum, pohon keputusan 5 langkah, dan 8 jebakan klasik).
   - **[`Cheatsheet_Rumus_Obligasi.tex`](Cheatsheet_Rumus_Obligasi.tex)**: Kode sumber LaTeX cheatsheet.

3. **Bank Soal Latihan & Ringkasan Rumus Kilat (`Bank_Soal_Latihan_Obligasi.pdf`)**:
   - **[`Bank_Soal_Latihan_Obligasi.pdf`](Bank_Soal_Latihan_Obligasi.pdf)**: Dokumen PDF siap baca/cetak berisi:
     - **Bagian 0**: Ringkasan rumus kilat Bab 12--14 + **6 Jebakan Klasik Kuis Obligasi**.
     - **Bagian I**: **12 Soal Latihan Terstruktur** yang diturunkan langsung dari slide perkuliahan (`12 Obligasi.pdf`, `13 Valuasi Bond di Antara Dua Pembayaran Kupon.pdf`, `14 Callable dan Putable Bond.pdf`) serta arsip ujian & *problem set* (`Past Problems/`).
     - **Bagian II**: Pembahasan lengkap langkah demi langkah, tabel amortisasi, dan verifikasi numerik.
   - **[`Bank_Soal_Latihan_Obligasi.tex`](Bank_Soal_Latihan_Obligasi.tex)**: Kode sumber LaTeX.

4. **Simulasi Kuis Mandiri 2 Paket (`Simulasi_Kuis_Obligasi.pdf`)**:
   - **[`Simulasi_Kuis_Obligasi.pdf`](Simulasi_Kuis_Obligasi.pdf)**: Paket simulasi berformat kuis asli AK2161 ITB (durasi **50 menit per paket**, 3 soal uraian beranak berbobot 100 poin, tutup buku):
     - **Paket Simulasi A**: Bab 12 (Harga, Jadwal Amortisasi, Rumus Langsung), Bab 13 (Valuasi Antar Kupon: Teoritis & Semi-teoritis), dan Bab 14 (*Callable Bond* dengan *call premium* bertingkat).
     - **Paket Simulasi B**: Pemilihan obligasi beda frekuensi & kupon bertahap, Aproksimasi YTM & *Putable Bond*, serta *Serial Bonds* (Makeham) & Obligasi *Sinking Fund* ($j \neq i$).
     - Disertai kunci jawaban dan pembahasan lengkap pada Bagian II.
   - **[`Simulasi_Kuis_Obligasi.tex`](Simulasi_Kuis_Obligasi.tex)**: Kode sumber LaTeX.

---

## 📚 Peta Cakupan Materi (Bab 12--14)

| Modul | Topik Utama yang Diuji | Nomor Soal Terkait |
|:---:|:---|:---|
| **Bab 12** | *Zero-coupon bond*, 4 rumus harga obligasi ($C \neq F$), kriteria premium/diskon ($g$ vs $i$), jadwal amortisasi (*writing down* & *writing up*), rumus langsung $P_t, I_t, B_t$, deret geometri pokok, *Straight Line Method*, & *Sinking Fund* ($j \neq i$) | Bank Soal 1--4, Simulasi A1, B1a, B3b |
| **Bab 13** | Valuasi antar dua tanggal kupon (*flat/dirty price*, *accrued coupon*, *market/clean price*) dengan metode **Teoritis**, **Praktis**, & **Semi-teoritis**; status premium/diskon via $B_{t+k}^m$; aproksimasi YTM & sensitivitas harga | Bank Soal 5--6, Simulasi A2, B2a |
| **Bab 14** | *Callable bond* ($\min P_n$, *call premium* bertingkat, soal invers & cek realisasi yield), *Putable bond* ($\max P_n$), *Serial bonds* (Makeham), frekuensi kupon $\neq$ yield, yield tidak konstan, kupon bertahap/geometrik, & reinvestasi kupon | Bank Soal 7--12, Simulasi A3, B1, B2b, B3a |

---

## 🎯 Strategi Belajar Cepat (Malam Ini & Besok Pagi)

1. **Tinjau Bagian 0** pada `Bank_Soal_Latihan_Obligasi.pdf` untuk menyegarkan semua formula dan 6 jebakan klasik.
2. **Kerjakan Soal 1--12** secara bertahap (fokus ekstra pada soal *Callable/Putable* bertingkat, *Valuasi Antar Kupon*, dan *Makeham/Serial Bonds* karena sering muncul di kuis/UAS ITB).
3. **Uji Waktu (50 Menit)**: Kerjakan **Paket Simulasi A** tutup buku dengan kalkulator saintifik, cocokkan jawaban, lalu kerjakan **Paket Simulasi B** sebelum kuis besok.

---

## ⚙️ Kompilasi Ulang LaTeX

```powershell
cd "Persiapan Kuis Obligasi"
pdflatex -interaction=nonstopmode -disable-installer Cheatsheet_1Lembar_BolakBalik.tex
pdflatex -interaction=nonstopmode -disable-installer Cheatsheet_Rumus_Obligasi.tex
pdflatex -interaction=nonstopmode -disable-installer Bank_Soal_Latihan_Obligasi.tex
pdflatex -interaction=nonstopmode -disable-installer Simulasi_Kuis_Obligasi.tex
```
