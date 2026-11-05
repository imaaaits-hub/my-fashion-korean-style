# my fashionstore — Korean Fashion & Style

Website toko fashion Korean style dengan tampilan ivory, cream, beige, dan taupe mengikuti logo.

## Menjalankan
Buka folder ini di VS Code lalu jalankan Live Server, atau:
`python3 -m http.server 5500`
Buka `http://localhost:5500`.

## Sebelum dipublikasikan
1. Perbarui nama, deskripsi, kategori, dan gambar produk pada `js/data.js` sesuai katalog toko.
2. Perbarui nomor WhatsApp admin pada `js/config.js` dengan format internasional tanpa `+` bila nomor berubah.
3. Periksa dan sesuaikan harga estimasi setiap produk di `js/data.js` dengan harga jual resmi sebelum dipublikasikan.
4. Lengkapi dan konfirmasikan metode pembayaran yang benar-benar tersedia kepada admin. Situs tidak memproses pembayaran atau menyimpan detail rekening; admin mengirim detail pembayaran resmi melalui WhatsApp.
5. Uji checkout WhatsApp di ponsel dan desktop.

## Publikasi gratis dengan GitHub Pages
1. Pastikan seluruh file website berada di root repository dan branch utamanya bernama `main`.
2. Buka **Settings → Pages** pada repository.
3. Pada **Build and deployment**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
5. Setelah proses deploy selesai, website dapat dibuka di `https://NAMA-AKUN.github.io/NAMA-REPOSITORY/`.

## Catatan
Keranjang dapat memuat beberapa produk dan menghitung subtotal dari harga katalog. Harga yang dicantumkan adalah estimasi awal, bukan harga resmi terverifikasi; perbarui `price` pada produk di `js/data.js` sebelum dipublikasikan. Checkout mengirim detail produk, subtotal, preferensi pembayaran, nama, nomor pembeli, dan catatan ke WhatsApp admin. Transfer bank, QRIS, dan COD (jika tersedia) adalah preferensi untuk dikonfirmasi admin; situs tidak memproses pembayaran dan tidak mencantumkan rekening/QRIS yang belum diverifikasi. Jangan membayar sebelum menerima konfirmasi resmi. Ongkos kirim belum termasuk. Semua produk saat ini berukuran AllSize. Setiap checkout dicatat sebagai riwayat berstatus menunggu konfirmasi admin dan disimpan hanya pada penyimpanan browser di perangkat yang digunakan; riwayat tidak tersinkron ke perangkat lain atau server. Galeri dan katalog otomatis memakai foto yang tercantum di `js/data.js`.
