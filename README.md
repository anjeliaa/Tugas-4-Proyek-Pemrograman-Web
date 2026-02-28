Di project ini membuat program dua rangkaian listrik yaitu seri dan pararel dibuat menggunakan HTML, CSS dan javascript untuk mengatur logika.
Setiap lampu dalam bentuk gambar yaitu off.jpg untuk lampu mati dan on.pg untuk lampu hidup.
Perubahan kondisi lampu dilakukan dengan menggunakan manipulasi DOM dengan mengubah atribut gambar src menggunakan javascript.
Di rangkaian pertama ada 3 buah lampu dan 2 button. 
Button pertama untuk menyalakan lampu satu persatu atau bergantian dengan logika membuat variabel urutan yang menentukan lampu mana yang akan di proses
ketika button ditekan. Setiap button diklik akan diperiksa status lampu melalui variabel (lampu1Hidup, lampu2Hidup, lampu3Hidup) lalu gambar akan diganti sesuai kondisi.
Setelah lampu ketiga diproses, urutan akan kembali ke lampu pertama.
Button kedua berfungsi untuk mengubah kondisi semua lampu sekaligus, jika lampu dalam keadaan menyala maka akan dimatikan sekaligus begitupun sebaliknya.
Lalu di rangkaian kedua ada empat lampu dan 3 button.
Button pertama mengaktifkan lampu satu persatu atau bergantian dengan variabel urut2 sebagai pengatur urutan.
Button kedua berfungsi untuk menyalakan atau mematikan seluruh lampu secara bersamaan dengan cara yang sama seperti pada rangkaian pertama.
Button ketiga mengaktifkan lampu secara berpasangan dan bergantian, yaitu lampu a dan b akan menyala saat diklik pertama dan lampu c dan d pada klik berikutnya, lalu saat klik ketiga semua lampu akan mati, menggunakan variabel urutPasangan yang menentukan pasangan mana yang aktif.
Status masing masing lampu disimpan dimasing masing variabel untuk rangkaian satu (lampu1Hidup, lampu2Hidup, ampu3Hidup), untuk rangkian kedua (aHidup, bHidup, cHidup, dHidup).
Semua proses ini dilakukan dengan menggunakan percangan if-else (untuk mengecek kondisi) pada masing masing lampu.
Dan button memiliki event handling melalui atribut onclick.
Saya menambahkan sedikit styling juga pada proyek ini.