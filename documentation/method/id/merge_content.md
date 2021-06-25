Metode ini digunakan untuk menggabungkan beberapa nama field menjadi satu tampilan field.

###### Referensi

`merge_content('{$params}{$params2}{$params3}', $newfield)`

###### Parameter

* **$params** (mixed) - nama-nama field yang ingin digabungkan menjadi 1 (satu) field
* **$newfield** (mixed) - nama field tampilan yang baru

###### Contoh penggunaan

`$this->merge_content('{nama_depan}, {nama_belakang}, nama_lengkap');`
