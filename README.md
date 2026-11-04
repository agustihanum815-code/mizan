# Mizan — Asisten Nahwu

Aplikasi pembelajaran untuk mengidentifikasi isim, fi'il dan huruf menggunakan Groq. Hasil harus diverifikasi; AI bukan pengganti guru atau rujukan kitab.

## Penggunaan

Buka aplikasi melalui HTTPS, lalu masukkan kunci Groq pribadi melalui Pengaturan API. Kunci disimpan di sessionStorage tab dan dikirim ke fungsi server untuk diteruskan ke Groq; jangan gunakan perangkat bersama. Jangan membagikan kunci kepada orang lain. Teks dan gambar yang dianalisis dikirim ke Groq. Untuk penerapan publik, pertimbangkan autentikasi dan pembatasan akses.

Gambar ditranskripsikan oleh model vision Groq. Periksa hasilnya sebelum analisis. Mendukung JPG, PNG, WebP dan TXT hingga 3 MB, bukan PDF. Ketersediaan model bergantung pada akun Groq. Kamera memerlukan izin browser dan HTTPS atau localhost.

## Menjalankan dan deploy

Website statis dan fungsi `api/index.js` dapat dijalankan menggunakan Vercel CLI (`vercel dev`) dan di-deploy ke Vercel. Tidak ada API key yang disimpan di repositori atau di server.
