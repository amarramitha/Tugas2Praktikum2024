# Tugas Pertemuan 2

berikut penjelasan proses passing data dari form menuju tampilan.

1. Pengguna mengisi formulir yang memiliki 3 input, yaitu nama, nim, dan tahun lahir. Pada fromData, terdapat 3 TextEditingController yang digunakan untuk mengelola teks yang dimasukkan oleh pengguna.
2. Ketika pengguna menekan tombol "Simpan", maka fungsi _tombolSimpan() akan dijalankan. Nilai dari TextEditingController diambil, kemudian dikirim ke halaman baru menggunakan Navigator.of(context).push().
3. Navigator.of(context).push() akan membuat navigasi ke halaman baru (TampilData) sambil mengirim data yang dikumpulkan(nama, nim, dan tahun lahir). kemudian, data ini diterima oleh TampilData melalui parameter nama, nim, dan tahun yang dideklarasikan sebagai variabel final dalam class TampilData.
4. Setelah halaman TampilData dibuka, data yang diterima akan ditampilkan dengan teks yang sudah disusun. 
