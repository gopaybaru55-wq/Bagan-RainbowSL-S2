# Rainbow 9 Ball Season 2 2026

Bagan turnamen double elimination, 32 peserta (slot L1 sampai L32), 62 pertandingan.

## File
- `index.html` : halaman publik (hanya melihat bagan)
- `admin.html` : panel admin (isi nama, acak posisi, input hasil)
- `config.js`  : isi URL dan key Supabase (cukup sekali)
- `supabase.sql` : dijalankan sekali di Supabase SQL Editor

## Pasang
1. Buat project Supabase, jalankan `supabase.sql` (ganti PIN `rainbow2026`).
2. Isi `config.js` dengan Project URL dan anon key.
3. Upload semua file ke GitHub, lalu deploy (Vercel/Cloudflare).
4. Buka `/admin.html` di HP, tekan Masuk admin, masukkan PIN.
