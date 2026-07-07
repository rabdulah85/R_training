# Training R UNNES — Konstruksi & Agregasi Data SUSENAS–PODES

Materi pelatihan R: konstruksi dan agregasi data SUSENAS–PODES dengan studi kasus
Balita Sakit (SUSENAS) & Posyandu (PODES). **Seluruh data bersifat sintetis** dan
dibuat khusus untuk keperluan pelatihan.

## Isi

| File | Keterangan |
|------|------------|
| `slide_construct_aggregasi.qmd` | Sumber slide (reveal.js) |
| `handout_construct_aggregasi.qmd` | Sumber hand-out (HTML) |
| `*.html` | Hasil render Quarto |
| `index.html` | Halaman muka (landing page) |

## Situs

Materi dipublikasikan otomatis ke **GitHub Pages** melalui GitHub Actions
(`.github/workflows/deploy.yml`) setiap kali ada push ke `main`:

<https://rabdulah85.github.io/R_training/>

## Render ulang (opsional)

```bash
quarto render slide_construct_aggregasi.qmd
quarto render handout_construct_aggregasi.qmd
```
