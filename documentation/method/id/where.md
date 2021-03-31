### Kontribusi kalian dibutuhkan!
Silakan edit halaman ini di GitHub :)

Metode ini digunakan ketika akan menampilkan suatu data berdasarkan kriteria tertentu dalam tabel CRUD. Pada kasus tertentu, Anda mungkin akan membutuhkannya apabila ingin menambahkan tindakan lain terkait dengan primary ID yang diminta, misal untuk menampilkan data berdasarkan id atau kategori tertentu dengan primary ID  atau krieteria yang lain diambil dari referensi tabel CRUD saat ini.

###### Referensi
'where($parameter)'

###### Parameter
* **$parameter** (array) - parameter tambahan untuk ditambahkan sebagai query string,

###### Contoh Penggunaan
'
	->where
	(
		array 
		(
			'status'				=> 0
		)
	)
'
Pemanggilan metode di atas akan menampilkan data yang bernilai 0
