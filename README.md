# RACUNIN V2

Website statis Shopee Affiliate yang siap di-host di GitHub Pages.

## Struktur
- `index.html` — homepage
- `produk/*/index.html` — halaman detail produk
- `artikel/*/index.html` — artikel SEO
- `assets/style.css` — styling
- `assets/script.js` — pencarian & filter
- `sitemap.xml` — sitemap
- `robots.txt` — aturan crawler
- `404.html` — halaman error

## Penting sebelum dipakai serius
Semua link Shopee contoh masih `https://shopee.co.id/`.
Ganti dengan link produk/affiliate yang sebenarnya.

Contoh:
```html
<a href="LINK_AFFILIATE_SHOPEE" target="_blank" rel="sponsored noopener">
  CEK HARGA DI SHOPEE →
</a>
```

## Cara upload ke GitHub
1. Ekstrak ZIP.
2. Di repository `racunin`, upload **isi folder ini**, bukan ZIP-nya.
3. Timpa `index.html` lama.
4. Upload folder `assets`, `produk`, `artikel`, serta `robots.txt`, `sitemap.xml`, `404.html`.
5. Commit changes.
6. GitHub Pages tetap gunakan `main` + `/ (root)`.

Website:
https://kalima112.github.io/racunin/

## SEO
V2 sudah memiliki:
- title + meta description per halaman
- canonical URL
- Open Graph dasar
- sitemap.xml
- robots.txt
- halaman produk terpisah
- artikel terpisah
- internal linking
- struktur heading yang lebih jelas

Tidak ada jaminan ranking Google. Untuk hasil SEO, tambahkan konten unik, foto produk yang sah digunakan, pengalaman/review yang nyata, internal linking, dan Search Console.
