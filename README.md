# Serinian Site

Website untuk **Restoran Seri Nian** — katering & nasi beriyani, Shah Alam.

## Fail Utama

- `index.html` — Homepage
- `menu.html` — Menu penuh
- `order.html` — Sistem order meja melalui QR code
- `dashboard.html` — Skrin kaunter (paparan order masuk)

## Setup

`order.html` dan `dashboard.html` menggunakan [Supabase](https://supabase.com) untuk order masa nyata. Sebelum kedua-dua fail ini boleh berfungsi, gantikan placeholder berikut dengan URL projek dan anon key Supabase anda:

```js
const SUPABASE_URL = "GANTI_DENGAN_PROJECT_URL";
const SUPABASE_ANON_KEY = "GANTI_DENGAN_ANON_KEY";
```

Nilai ini boleh didapati dari **Project Settings → API** di dashboard Supabase.
