# WebNusa

**WebNusa** adalah perusahaan pembuatan website & promo untuk UMKM Indonesia.
Membantu UMKM tampil lebih profesional di internet, jualan lebih, dan menjangkau
pelanggan baru yang mencari produk/jasa via Google.

> Tagline: *Tampil di internet, jualan lebih.*

---

## Isi Folder

| File | Deskripsi |
|------|-----------|
| `index.html`       | Website utama (one-page, responsive, siap produksi) |
| `logo.svg`         | Logo vektor (tema teal `#2C7A7B` + emas `#F2CC8F`) |
| `vercel.json`      | Konfigurasi deploy Vercel (static) |
| `package.json`     | Hint deploy / scripts utilitas |
| `.gitattributes`   | Normalisasi line endings |

---

## Cara Cepat (tanpa instal)

Buka `index.html` langsung di browser (double-click), atau jalankan server lokal:

```bash
cd webnusa
python -m http.server 8000
# lalu buka http://localhost:8000
```

---

## Deploy ke Vercel

### Metode A — Via GitHub (rekomendasi)
1. Buat repo GitHub **kosong** (tanpa README/license)
2. Di folder `webnusa`:
   ```bash
   git remote add origin https://github.com/<username>/webnusa.git
   git branch -M main
   git push -u origin main
   ```
3. Vercel → **Add New** → **Project** → pilih repo `webnusa`
4. **Framework Preset** → `Other`
5. **Deploy**

### Metode B — Dashboard Vercel (tanpa Git)
1. Buat folder `webnusa.zip`
2. Vercel → **Add New** → **Project** → **Import From TAR** → upload
3. Framework preset `Other` → **Deploy**

---

## Kontak Proyek

- **Email:** halo@webnusa.co.id
- **WhatsApp:** 62 812-3456-7890
- **Instagram:** @webnusa

> Catatan: nilai email/WA/IG di `index.html` masih placeholder.
> Ganti sesuai data perusahaan sebelum kirim ke klien/klien.

---

## Lisensi

Private / batalkan hak cipta.
