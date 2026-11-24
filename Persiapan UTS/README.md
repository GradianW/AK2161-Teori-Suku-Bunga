# Persiapan UTS (Ujian Tengah Semester) - Teori Suku Bunga

Direktori ini didedikasikan khusus untuk persiapan **Ujian Tengah Semester (UTS)** mata kuliah **AK2161 Teori Suku Bunga (Theory of Interest)**.

Di dalam folder ini terdapat **Cheatsheet Rangkuman Rumus Lengkap** dalam format sumber **LaTeX (`.tex`)** dan dokumen siap cetak **PDF (`.pdf`)** beresolusi tinggi, mencakup seluruh materi perkuliahan dari **Bab 01 sampai dengan Bab 10 (sampai Sinking Fund)**.

---

## 📄 Berkas Utama

1. **Cheatsheet Rangkuman Rumus**:
   - **[`Cheatsheet_Rumus_UTS.pdf`](Cheatsheet_Rumus_UTS.pdf)**: Dokumen PDF final (15 halaman) rangkuman rumus lengkap Bab 01 s.d. 10 (termasuk Jadwal Amortisasi & Sinking Fund), tabel matriks pola aktuaria, matriks komparasi terpadu Amortisasi vs Sinking Fund, pohon keputusan ujian, dan 8 jebakan klasik ujian.
   - **[`Cheatsheet_Rumus_UTS.tex`](Cheatsheet_Rumus_UTS.tex)**: Kode sumber LaTeX cheatsheet dengan styling `tcolorbox` full-width yang stabil.

2. **Kumpulan Soal Latihan Kontekstual Berbasis Kasus Nyata**:
   - **[`Latihan_Soal_Kasus_Nyata.pdf`](Latihan_Soal_Kasus_Nyata.pdf)**: Dokumen PDF latihan soal (16 halaman) per materi (Bab 01 s.d. Bab 08). Setiap bab memuat:
     - **Tinjauan Kasus Nyata Industri**: Penjelasan aplikasi konsep pada perbankan, pasar uang, pasar obligasi (SPN), restrukturisasi utang korporasi, evaluasi manajer investasi reksadana (TWRR vs DWRR), dana abadi (*endowment* beasiswa), skema cicilan kredit (*balloon & drop payment*), arus kas kontinu jalan tol, dan anuitas bertumbuh (*anti-inflation pensions* & pembiayaan industri).
     - **Soal Kasus Nyata**: Soal hitungan aplikatif dengan parameter angka realistis.
     - **Petunjuk Analisis & Rumus Kunci**: Formula utama dan jebakan yang perlu dihindari.
     - **Solusi Lengkap & Langkah demi Langkah**: Penurunan matematis detail hingga interpretasi finansial akhir.
   - **[`Latihan_Soal_Kasus_Nyata.tex`](Latihan_Soal_Kasus_Nyata.tex)**: Kode sumber LaTeX kumpulan soal dan pembahasan.

3. **Simulasi Ujian Tengah Semester (UTS) Mandiri & Pembahasan**:
   - **[`latihan_uts_v1.pdf`](latihan_uts_v1.pdf)**: Paket simulasi ujian 120 menit (11 halaman) yang dirancang khusus mengikuti tipologi soal asli UTS AK2161 ITB beberapa tahun terakhir. Terbagi atas:
     - **Bagian I: Lembar Soal Ujian (Halaman 1--3)**: Berisi 6 soal uraian standar UTS dengan alokasi bobot 100 poin untuk simulasi mandiri (tutup buku).
     - **Bagian II: Pembahasan Lengkap Langkah demi Langkah (Halaman 4--11)**: Penurunan simbolik aktuaria, diagram garis waktu, analisis konsep, dan hasil numerik presisi tinggi.
   - **[`latihan_uts_v1.tex`](latihan_uts_v1.tex)**: Kode sumber LaTeX simulasi ujian.

---

## 📚 Cakupan Materi (Bab 01 s.d. Bab 10)

Rangkuman ini mencakup 10 modul fundamental Teori Suku Bunga:

| No | Modul Perkuliahan | Topik & Rumus Kunci |
|:---:|:---|:---|
| **0** | **Peta Konsep & Rantai Konversi** | Prinsip ekuivalensi universal: $1+i = v^{-1} = (1-d)^{-1} = (1+i^{(m)}/m)^m = (1-d^{(p)}/p)^{-p} = e^\delta$, rantai ketaksamaan $i > i^{(m)} > \delta > d^{(m)} > d$, identitas aljabar, limit $m \to \infty$. |
| **1** | **Pendahuluan - Suku Bunga** | Fungsi akumulasi $a(t)$ vs jumlah $A(t)$, bunga $I_n$, suku bunga efektif $i_n$, bunga tunggal ($1+it$) vs majemuk ($(1+i)^t$), perbandingan jangka pendek/panjang, periode pecahan. |
| **2** | **Suku Bunga Nominal** | Faktor diskon $v$, diskonto efektif $d$, diskonto tunggal, suku bunga nominal $i^{(m)}$, tingkat diskonto nominal $d^{(m)}$, intensitas sesaat (\textit{force of interest}) $\delta_t$, konversi suku bunga bervariasi. |
| **3** | **Masalah Mengenai Interest** | Persamaan nilai (\textit{equations of value}), teorema independensi titik perbandingan (focal date), penentuan waktu ($t$), waktu terimbang (\textit{equated time}) $\bar{t}$, ketaksamaan Jensen ($\bar{t} > t$), aturan penggandaan modal (Rule of 72, 70, 69.3), konvensi hari (\textit{Actual/Actual, Banker's Rule, 30/360}), pencarian tingkat bunga tak diketahui (interpolasi & Newton-Raphson). |
| **4** | **Yield Rates** | *Net Present Value* (NPV) & *Internal Rate of Return* (IRR), syarat keunikan IRR (*Descartes' Rule of Signs*, *Pure Investment*), *Dollar-Weighted Rate of Return* (DWRR), *Time-Weighted Rate of Return* (TWRR), perbandingan kinerja investasi, alokasi *Portfolio Method* vs *Investment Year Method*. |
| **5** | **Annuitas dan Perpetuitas 1** | *Annuity-Immediate* ($a_{\overline{n}\|}, s_{\overline{n}\|}$), *Annuity-Due* ($\ddot{a}_{\overline{n}\|}, \ddot{s}_{\overline{n}\|}$), identitas resiprokal ($1/a - 1/s = i$ dan $1/\ddot{a} - 1/\ddot{s} = d$), anuitas ditunda ($_{m\|}a_{\overline{n}\|}$), perpetuitas ($1/i, 1/d, v^m/i$), dekomposisi keuangan. |
| **6** | **Annuitas dan Perpetuitas 2** | Unknown term ($t$) dengan *balloon payment* ($t=n$), *drop payment* ($t=n+1$), dan pembayaran fraksional ($t=n+k$); aproksimasi deret Maclaurin orde-2 untuk $i$; anuitas bunga tunggal; valuasi kurva imbal hasil (*Spot Rates*). |
| **7** | **Annuitas yang Lebih Umum 1** | Ketidaksamaan frekuensi pembayaran dan bunga: metode suku bunga ekuivalen $j$ vs aljabar aktuaria; bayar lebih jarang ($k > 1$): $a_{\overline{n}\|}/s_{\overline{k}\|}$ dan $a_{\overline{n}\|}/a_{\overline{k}\|}$; bayar lebih sering ($m > 1$): $a_{\overline{n}\|}^{(m)}, \ddot{a}_{\overline{n}\|}^{(m)}$; anuitas kontinu ($\bar{a}_{\overline{n}\|}, \bar{s}_{\overline{n}\|}$), identitas resiprokal kontinu ($1/\bar{a} - 1/\bar{s} = \delta$), dinamika kalkulus/PDB. |
| **8** | **Annuitas yang Lebih Umum 2** | Anuitas bervariasi aritmatika umum $(P, Q)$; anuitas meningkat standar $(Ia)_{\overline{n}\|}$; anuitas menurun standar $(Da)_{\overline{n}\|}$; identitas komplementer $(Ia) + (Da) = (n+1)a_{\overline{n}\|}$; perpetuitas aritmatika; anuitas bertumbuh geometrik (rasio $1+k$, suku bunga pengganti $\tilde{i}$, kasus $k=i \implies n v$); variasi frekuensi $m > 1$; anuitas kontinu bervariasi ($(\bar{I}\bar{a})_{\overline{n}\|}, (\bar{D}\bar{a})_{\overline{n}\|}$, laju kuadratik $f(t) = t^2$). |
| **9** | **Jadwal Amortisasi** | Prinsip *interest paid first*, dekomposisi $R_t = I_t + P_t$, penentuan saldo $B_t$ via prospektif ($R a_{\overline{n-t}\|}$) vs retrospektif ($L(1+i)^t - R s_{\overline{t}\|}$), teorema kesamaan, sifat deret geometri naik porsi pokok ($P_t = P_1(1+i)^{t-1}$), total pokok $\sum P_t = L$, total bunga $\sum I_t = nR - L$, valuasi piutang pasar sekunder ($S_b$ vs $S_c$ dan rekonsiliasi diskon/bunga), restrukturisasi bunga mengambang (kenaikan 1 periode vs permanen), amortisasi negatif ($R_t < I_t$), *balloon & drop payment*, amortisasi kontinu. |
| **10** | **Metode Sinking Fund** | Pelunasan pokok *lump-sum* di akhir tenor $n$, *service on loan* ($i L$), setoran tabungan $D = L/s_{\overline{n}\|j}$, total beban $R = i L + D$, saldo terakumulasi $SF_t = D s_{\overline{t}\|j}$, saldo bersih hutang $B_t^{\text{net}} = L - SF_t$. Kasus $j = i$: ekuivalensi sempurna dengan amortisasi ($R_{\text{SF}} = R_{\text{Amort}}$, $B_t^{\text{net}} = B_t^{\text{Amort}}$, bunga bersih $I_t^{\text{net}} = I_t^{\text{Amort}}$, kenaikan SF $\Delta SF_t = P_t^{\text{Amort}}$). Kasus $j < i$: anuitas 2 suku bunga $a_{\overline{n}\|i \& j}$, yield amortisasi ekuivalen $\hat{i}$ dengan sifat $\hat{i} > i > j$ dan aproksimasi Kellison $\hat{i} \approx i + \frac{n-1}{2n}(i - j)$, frekuensi bunga vs setoran beragam, sinking fund angsuran bervariasi. |

---

## 🎯 Fitur Khusus Cheatsheet

1. **Matriks Super Pola Pembilang & Penyebut**:
   Tabel ringkas yang membedah keteraturan rumus aktuaria di mana:
   - Akhir (*immediate*) $\to$ penyebut $i$ (atau $i^{(m)}$).
   - Awal (*due*) $\to$ penyebut $d$ (atau $d^{(m)}$).
   - Kontinu (*continuous*) $\to$ penyebut $\delta$.
   - Meningkat (*increasing*) $\to$ pembilang $\ddot{a}_{\overline{n}\|} - n v^n$.
   - Menurun (*decreasing*) $\to$ pembilang $n - a_{\overline{n}\|}$.
2. **Matriks Komparasi Terpadu: Amortisasi vs Sinking Fund**:
   Perbandingan struktural antara Metode Amortisasi, Sinking Fund Satu Bunga ($j = i$), dan Sinking Fund Dua Bunga ($j < i$).
3. **Pohon Keputusan Ujian (*UTS Decision Tree*)**:
   Panduan 5 langkah praktis saat membaca soal ujian untuk menentukan formula mana yang harus dipakai dalam hitungan detik.
4. **8 Jebakan Klasik Ujian UTS**:
   Peringatan kritis mengenai kesalahan perhitungan yang paling sering memicu pengurangan nilai pada ujian aktuaria dan matematika keuangan (termasuk rasio pangkat amortisasi, yield ekuivalen $\hat{i} > i$, dan valuasi piutang pasar sekunder).

---

## ⚙️ Cara Kompilasi LaTeX

Bagi yang ingin memodifikasi atau mengompilasi ulang dokumen:

```powershell
cd "Persiapan UTS"

# 1. Kompilasi Cheatsheet Rumus (11 halaman)
pdflatex -interaction=nonstopmode -disable-installer Cheatsheet_Rumus_UTS.tex

# 2. Kompilasi Kumpulan Soal Latihan & Pembahasan (16 halaman)
pdflatex -interaction=nonstopmode -disable-installer Latihan_Soal_Kasus_Nyata.tex

# 3. Kompilasi Simulasi Soal UTS & Pembahasan (11 halaman)
pdflatex -interaction=nonstopmode -disable-installer latihan_uts_v1.tex
```
Seluruh berkas akan menghasilkan output PDF berkualitas tinggi yang bebas dari *overfull hbox* dan tumpang tindih rumus.
