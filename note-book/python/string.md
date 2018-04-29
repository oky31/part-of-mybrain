# String 
Setiap string didalam python di nyatakan dalam  tanda yaitu
	
	'...' -> tanda kutip tunggal
	"..." -> tanda kutip ganda 
	'''...''' -> tanda kutip tunggal triple
	"""...""" -> tanda kutip double triple


untuk membuat string mudah di baca gunakan fungsi **print()**, fungsi ini \n
di gunakan untuk mencetak expresi ke layar.

## Contoh
	print('selamat siang') 		#selamat siang
	print("selamat siang')		#selamat siang
	print('jum\'at')			#jum'at
	print("jum'at')				#jum'at
	print("selamat \"datang\" di indonesia")  #selamat "datang" di indonesia
	print('selamat "datang" di indonesia') #selamat "datang" di indonesia

ketika di dalam string mengunakan tanda kutip tunggal atau tanda kutip \n
ganda , gunakan tanda \ lalu diikuti kutip tunggal atau kutip ganda maka\n
akan menampilkan tanda kutip tunggal atau kutip ganda.
 
## menghilangkan tanda \ sebagai karakter special
jika kita ingin menampilkan tanda \ di dalam string gunakan fungsi \n
**print(r'...')**, fungsi ini akan menampilkan raw string contoh :\n
	
	print('c:\xampp\nama') # c:\xampp
						   # ama
	print(r'c:\xampp\nama') # c:\xampp\nama

## String dengan banyak baris 
untuk menampilkan string dengan banyak baris ada baiknya gunakan tanda 
"""...""" atau '''...'''. seperti dibahan ini : 
	
	print("""\
	Pilih menu :
	----------------------------
	1. pilihan pertama
	2. pilihan kedua
	3. pilihan ketiga
	4. keluar
	-----------------------------
	pilihan : 
	""")


## Mengabungkan (concate) dan Mengulangi String
Pengabungan 2 buah string mengunakan operator **+**, Pengulangan string 
mengunakan operator __*__.
