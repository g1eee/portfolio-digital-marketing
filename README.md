# Portfolio — Gifar Rahmatilah

Personal portfolio website untuk **Gifar Rahmatilah** — Senior E‑Commerce & Performance Marketing Specialist.

Live site: https://portfolio-digital-marketing-isuliclu.devinapps.com

## Stack

- Static HTML (single page)
- [Tailwind CSS](https://tailwindcss.com/) via Play CDN
- [Lucide Icons](https://lucide.dev/)
- Google Fonts: Plus Jakarta Sans + Space Grotesk
- Pure vanilla JS (IntersectionObserver + mobile menu toggle)

No build step required — just open `index.html` in a browser.

## Sections

1. **Hero** — pitch + key stats
2. **Platform marquee** — platform yang dikuasai (Shopee Ads, Meta CPAS, TikTok Ads, dll)
3. **About** — pendekatan kerja + sertifikasi (Meta Blueprint, TikTok Creative Academy)
4. **Services** — 6 service utama (Shopee Ads, Meta CPAS & TikTok Ads, Live Commerce, Marketplace SEO, Creative & A/B Testing, Analytics)
5. **Selected Work** — 6 case study (nama brand disamarkan jadi industri)
6. **Experience** — timeline karier (Digivise Education → Varka Group → Tasik Store)
7. **Results** — snapshot performa Maret 2026
8. **Contact** — email, WhatsApp, LinkedIn, GitHub

## Local development

```bash
# Cara paling sederhana:
python3 -m http.server 8000
# Buka http://localhost:8000

# Atau:
npx serve .
```

## Deploy

### Vercel (recommended, gratis + custom domain)

1. Push repo ke GitHub
2. Import repo di [vercel.com/new](https://vercel.com/new)
3. Klik **Deploy** (tanpa build setting)
4. (Opsional) Tambahkan custom domain di Settings → Domains

### Netlify

1. Drag‑and‑drop folder ini ke [app.netlify.com/drop](https://app.netlify.com/drop)

### GitHub Pages

1. Settings → Pages → Source: `main` branch, root folder

## Cara mengedit konten

Semua konten ada di `index.html`. Section dipisah dengan komentar besar `<!-- ============== NAMA ============== -->` jadi gampang dicari pakai Ctrl+F.

Tips edit angka:
- **Hero stats** → cari `<dl class="reveal mt-16`
- **Case study cards** → cari `<!-- Brand Furniture -->`, `<!-- Brand Fashion -->`, dst
- **Results section** → cari `<!-- ============== RESULTS ============== -->`
- **Experience timeline** → cari `<!-- ============== EXPERIENCE ============== -->`
- **Kontak (email/WA)** → cari `mailto:` dan `wa.me`

## Lisensi

Konten (teks, data) © Gifar Rahmatilah. Kode template bebas dipakai/dimodifikasi.
