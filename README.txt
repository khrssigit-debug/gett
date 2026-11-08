SHOCKRIDE GARAGE — VERSI PERBAIKAN GAMBAR UNTUK GITHUB PAGES

Perbaikan utama:
- Gambar produk sudah ditanam langsung di dalam index.html (embedded/base64).
- Jadi gambar tetap tampil walaupun hanya index.html yang diunggah ke GitHub.
- Folder assets tetap disertakan sebagai salinan gambar asli.
- Nama file dan jalur gambar tidak bergantung pada huruf besar/kecil atau path subfolder GitHub Pages.

CARA UPLOAD KE GITHUB:
1. Ekstrak ZIP ini.
2. Buka repository GitHub website kamu.
3. Upload/ganti file index.html yang lama dengan index.html dari folder ini.
4. Jika diminta, tetap boleh upload folder assets juga (opsional untuk versi embedded ini).
5. Klik Commit changes.
6. Tunggu 1–3 menit, lalu buka website dan tekan Ctrl + F5 untuk refresh tanpa cache.

PENTING: Jangan hanya upload file ZIP ke repository. Ekstrak dahulu, lalu upload index.html (dan folder assets bila diinginkan) ke lokasi yang sama dengan index.html lama.
