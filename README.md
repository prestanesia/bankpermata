Bank Permata
--------
Modul pembayaran Bank Permata untuk PrestaShop 1.6.x

Modul ini dibuat berdasarkan modul BankWire. Versi/perubahan akan selalu mengikuti modul tersebut.

Instalasi dan Konfigurasi
--------
* Download, kemudian rename bankpermata-master.zip menjadi bankpermata.zip
* Upload dari halaman Modules di BackOffice.
* Di halaman konfigurasi modul, masukan nama bank, no rekening, nama pemilik rekening dan lokasi/cabang bank.
* Modul akan membuat status order baru yaitu "Awaiting Bank Permata Payment"/"Menunggu pembayaran via Bank Permata".
* Untuk pengiriman email, modul menggunakan format email sendiri yang dapat Anda temukan di folder mails/bahasa-yang-digunakan/bankpermata.html dan mails/bahasa-yang-digunakan/bankpermata.txt.

Kustomisasi
--------
Tampilan saat konfirmasi dan pemilihan bank masih standar, jika akan disesuaikan dengan theme yang Anda gunakan silahkan override file .tpl terkait, sebagai referensi cara override file modul silahkan baca [Override default behaviour][1]


[1]: http://doc.prestashop.com/display/PS16/Overriding+default+behaviors
