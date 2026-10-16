# Menara Hanoi — 5 Cakram

Game ini adalah situs statis berbasis HTML, CSS, dan JavaScript. Tidak memerlukan framework, backend, maupun database. File `index.html` adalah halaman utama.

## Deploy ke Vercel melalui GitHub

1. Buat repository baru di GitHub.
2. Upload `index.html` dan `README.md` ke root repository.
3. Di Vercel, pilih **Add New → Project**, lalu import repository tersebut.
4. Biarkan **Framework Preset** sebagai **Other**. Tidak perlu mengisi build command.
5. Pilih **Deploy**.

Setelah deploy, setiap commit/push baru ke branch yang terhubung akan memicu deployment baru secara otomatis.

Progress permainan disimpan di memori browser masing-masing pengunjung, jadi permainan antar pengguna tidak saling memengaruhi.
