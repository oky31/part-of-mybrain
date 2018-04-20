# Terjemahan untuk RFC 2119

S. Brander\
Harvard University\
March 1997

Kelompok Kerja Jaringan\
Permintaan untuk Komentar: 2119\
BCP: 14			

Kategori : Praktik Terbaik Saat Inia

    Kata-kata kunci yang di gunakan dalam RFC untuk Menunjukkan Tingkat Kebutuhan

Status Memo ini

    Dokument ini menetapkan prakter terbaik untuk komunitas internet saat ini, dan meminta
    diskusi dan saran untuk perbaikan. Distribusi memo ini tidak terbatas

Abstrak

    Didalam banyak dokument standar beberapa kata di gunakan untuk menandakan persyaratan di dalam
    spesifikasi. kata kata ini sering mengunakan huruf kapital. Dokument ini mendefinisikan kata-kata ini 
    karena harus ditafsirkan dalam dokumen IETF. Penulis yang mengikuti panduan ini harus memasukan frasa 
    ini di awal dokumen mereka :

		Kata Kuncinya "HARUS", "TIDAK HARUS", "WAJIB", "BOLEH", "TIDAK BOLEH", "SEBAIKNYA", "JANGAN", 
		"DIREKOMENDASIKAN", "MUNGKIN", dan "PILIHAN". Dalam dokumen ini harus ditafsirkan seperti yang 
 		dijelaskan dalam RFC 2119.

Perhatikan kekuatan dari kata-kata ini dimodifikasi oleh tingkat persyaratan dokumen yang di gunakan.

	1. HARUS(MUST) kata ini, atau istilah "WAJIB (REQUIRED)","BOLEH (SHALL)", 
	   bahwa definisi kalimat tersebut adalah persyaratan mutlak dari spesifikasi.

	2. TIDAK HARUS (MUST NOT) frasa ini, atau frasa "TIDAK BOLEH (SHALL NOT)", 
	   mendefinisikan bahwa kalimat tersebut adalah larangan absolut dari spesifikasi.

	3. SEBAIKNYA(SHOULD) kata ini, atau kata "DIREKOMENDASIKAN(RECOMMENDED)", berarti bahwa mungkin ada 
	   alasan yang sah dalam keadaan tertentu untuk mengabaikan item tertentu, tetapi implikasi penuh harus
	   dipahami dan ditimbang dengan hati-hati sebelum memilih arah yang berbeda.

	4. JANGAN(SHOULD NOT) prasa ini, atau prasa "TIDAK DIREKOMENDASIKAN(NOT RECOMMENED)" berarti bahwa 
	   mungkin ada alasan yang sah dalam keadaan tertentu ketika prilaku tertentu dapat di terima atau 
	   bahkan bermanfaat, tetapi implikasi penuh harus dipahami dan kasus ditimbang dengan cermat sebelum
	   menerapkan prilaku apa pu yang di uraikan dengan label ini.

	5. MUNGKIN(MAY) kata ini, atau kata sifat "PILIHAN(OPTIONAL)", berarti item itu benar-benar pilihan.
	   Satu vendor mungkin memili untuk memasukan sebuah item karena beberapa pasar membutuhkan itu atau
	   karena vendor merasa itu bisa meningkatkan produk ketika vendor lain mengkin menghilangkan item 
	   yang sama. Sebuah implementasi yang tidak termasuk beberapa pilihan HARUS di persiapkan untuk 
	   interoperate dengan implementasi lain yang termasuk di dalam pilihan, meskipun mungkin dikurangi
	   fungsionalitasnya. Didalam implementasi yang sama mencakup opsi tertentu HARUS siap untuk
	   berinteropersai dengan implementasi lain yang tidak termasuk opsi(kecuali untuk fiture yang 
	   disediakan opsi.)

	6. Panduan dalam mengunakan panduan Imperatif ini

	   Imperatif yang didefinisikan dalam memo ini harus digunakan dengan hati-hati dan hemat. 
	   Khurusnya, kata HARUS(MUST) hanya bisa digunakan ketika benar-benar di butuhkan untuk interoperasi
	   atau batasan tingkah laku yang memiliki potensi berbahaya (contoh., pembatasan retransmisi).
	   Sebagai contoh, kata ini tidak boleh digunakan untuk menerapkan metode tertentu pada sebuah
	   penerapan di mana metode ini tidak diperlukan untuk interoperabilitas.

	7. Pertimbangan Keamanan

	   Istilah ini sering digunakan untuk menentukan tingkahlaku dengan implikasi keamanan. 
	   Efek pada keamanan tidak menerapkan HARUS(MUST) atau WAJIB(SHOULD), atau melakukan spesifikasi 
	   dengan TIDAK HARUS(MUST NOT) atau TIDAK WAJIB(SHOULD NOT) dilakukan mungkin sangat halus.
	   Pemilik dokument harus mengunakan waktu untuk menguraikan implikasi keamanan yang tidak mengikuti
	   rekomendasi atau persyaratan karena kebanyakan pelaksana tidak akan mendapat manfaat dari pengalaman
	   dan diskusi yang menghasilkan spesifikasi.

	8. Ucampan Terimakasih
	   
	   Definisi instilah-istilah ini merupakan campuran definisi yang diambil dari sejumlah dokument RFC.
	   selain itu, saran telah di masukan dari sejumlah orang termasuk Robert Ullmann, Thomas Narten, 
	   Neal McBurnett, dan Robert Elz.

	9. Alamat Penulis

	   Scott Bradner
       Harvard University
       1350 Mass. Ave.
       Cambridge, MA 02138

       phone - +1 617 495 3864

       email - sob@harvard.edu
	

	

	
