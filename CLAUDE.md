# CLAUDE.md: portfolio (shendyu7-a11y.github.io)

Situs portofolio statis Aa Shendi Yusuf, live di GitHub Pages dari `main` (tanpa build step). Balas dalam bahasa Indonesia.
Status dan indeks semua project ada di repo hub `shendyu7-a11y/ai-mcp-project` (`PROJECT_INDEX.md`, `projects/portfolio/`).

## Hemat token
- `index.html` (109 KB, 996 baris, 5 script inline) berisi semua teks dan CSS: jangan dibaca utuh. Grep `id="<section>"` lalu baca rentang barisnya.
- `certs/` berisi 111 gambar/PDF (23 MB): jangan dibuka, cukup daftar nama file bila perlu.

## Section di `index.html`
`experience`, `projects`, `skills`, `certifications`, `education`, `awards`, `leadership`, `contact` (cari dengan `grep -n 'id="experience"' index.html`).

## Aturan
- Setiap push ke `main` langsung tayang. Kerja di branch `claude/<tugas>` lalu PR; merge hanya oleh pemilik.
- Gambar/PDF diganti dengan nama file yang sama agar link di `index.html` tetap berlaku.
- `localStorage` key `theme` = mode terang/gelap. Font dari Google Fonts.
- Jangan menambahkan data pribadi baru (alamat, nomor) tanpa diminta.
