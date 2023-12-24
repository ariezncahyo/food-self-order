# food-self-order
Food self order build with svelte and nest just to explore our tech


> Terinpirasi ketika makan di salah satu resto di surabaya ternyata sudah bisa order sendiri dan kira-kira step nya seperti berikut:
- Pelayan resto memberikan buku menu yang bisa di lihat di meja seperti pada umumnya dan juga.
- di meja ada QRCode yang bisa di scan, berisi link yang mengarah ke website katalog menu untuk order. dari sini juga bisa tau order dari meja berapa, tanpa harus login.
  tapi juga ada opsi untuk login with (google account)
  - kira-kira ada beberapa menu (login, tentang kami, katalog)
- ada pencarian untuk menu yang tersedia (filter by category, switch view list atau tumbnail)
- menu yang dipilih masuk ke kerajang, dan ada button view keranjang untuk masuk ke keranjang
- dikeranjang berisi list menu yang sudah di pilih, dan ada menu next ke pembayaran.
- pembayaran ada beberapa metode, misal CASH dikasir, VA atau digital.
- setelah pembayaran berhasil tinggal tunggu pesanan kerjakan dan dikirim.

## Stack 
(BE)
- Nest
- MikroORM
- MySQL
  
(FE)
- Svelte
