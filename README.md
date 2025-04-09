# 🔊 Hands-On Audio Processing — IF4021

Repositori ini berisi implementasi tugas Hands-On Audio Processing untuk mata kuliah **Pengolahan Multimedia (IF4021)** di Institut Teknologi Sumatera.

## 🎯 Tujuan Proyek

- Merekam dan memvisualisasikan audio (waveform & spektrogram)
- Menerapkan efek fade-in dan fade-out
- Menerapkan filter equalisasi (high-pass, low-pass, band-pass)
- Mengubah pitch suara (efek chipmunk)
- Melakukan normalisasi loudness berbasis persepsi (LUFS)

---

## 🧩 Modul Utama

| Modul | Fungsi |
|-------|--------|
| Visualisasi | Menampilkan bentuk gelombang & spektrogram |
| Fading | Efek transisi suara masuk & keluar |
| Filtering | Mengurangi noise menggunakan equalizer |
| Pitch Shifting | Pitch naik seperti chipmunk |
| Normalisasi Loudness | Suara konsisten di -18 LUFS |

---

## ⚙️ Instalasi

```bash
pip install numpy matplotlib librosa soundfile pydub scipy
