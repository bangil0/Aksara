### Kontribusi kalian dibutuhkan!
Silakan edit halaman ini di GitHub :)

Metode ini digunakan ketika akan menambahkan validasi input data. Pada kasus tertentu, Anda mungkin akan membutuhkannya apabila ingin menambahkan tindakan lain terkait pemeriksaan data inputan.

Contoh Penggunaan
->set_validation
(
	array
	(
		'nama'						=> 'required|string|max_length[60]',
		'deskripsi'					=> 'string',
		'email'						=> 'required|valid_email'
	)
)


Pemanggilan metode di atas akan memeriksa data yang di inputan pada form sebelum di simpan.
