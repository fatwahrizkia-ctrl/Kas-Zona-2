# Kas Anggota - password sederhana
Website bisa dilihat tanpa login. Klik **Edit sebagai Admin** untuk memasukkan password.

## Pasang
1. Buat project Supabase.
2. Jalankan `supabase-schema.sql` di SQL Editor.
3. Isi `config.js` dengan Project URL, Publishable/anon key, dan ganti `ADMIN_PASSWORD`.
4. Upload semua file ke GitHub Pages.

## Catatan keamanan
Versi password sederhana ini cocok untuk penggunaan terbatas, tetapi password berada di JavaScript sehingga dapat dilihat jika orang memeriksa kode repository. Jangan gunakan untuk data yang sangat rahasia. Untuk keamanan penuh, gunakan login Supabase atau Edge Function. Jangan masukkan service_role key ke frontend.