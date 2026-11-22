# pos-struk

Halaman struk publik untuk aplikasi POS Kasir (Google Apps Script).

Halaman membaca `?nota=…&t=…` dari URL, lalu mengambil data struk dari web app Apps Script (`?api=struk`) tanpa cookie akun Google. Pelanggan bisa membuka struk dan menekan **Download PDF**.

Token salah atau kedaluwarsa menampilkan "Struk tidak ditemukan atau tautan sudah kedaluwarsa".

## Link pendek

- `/admin/` → halaman admin POS (`.../exec?page=admin`)
- `/kasir/` → halaman kasir POS (`.../exec`)

Keduanya hanya halaman pengalih. Jika deployment ID Apps Script berubah, perbarui URL di `admin/index.html`, `kasir/index.html`, dan `index.html`.
