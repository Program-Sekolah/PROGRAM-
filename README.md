#PROGRAM PEMBELAJARAN MATEMATIKA MAHASISWA

#MEMASUKAN DATA DIRI
input("Nama :")
input("Kelas : ")
input("Prodi :")
print("Selamat Mengerjakan!")

#SOAL SOAL MATEMATIKA
def luas_persegi(s):
    luas=s*s
    return luas
def keliling_persegi(s):
    keliling=4*s
    return keliling
def luas_persegi_panjang(p,l):
    luas=p*l
    return luas
def keliling_persegi_panjang(p,l):
    keliling=2*(p+l)
    return keliling
def luas_segitiga(a,t):
    luas=0.5*a*t
    return luas
def keliling_segitiga(a,b,c):
    keliling=a+b+c
    return keliling
def luas_lingkaran(r):
    luas=3.14*r*r
    return luas
def keliling_lingkaran(r):
    keliling=2*3.14*r
    return keliling
def luas_jajar_genjang(a,t):
    luas=a*t
    return luas
def keliling_jajar_genjang(a,b):
    keliling=2*(a+b)
    return keliling

pilihan=1
while pilihan!=0:
    print("1.Menghitung luas persegi")
    print("2.Menghitung keliling persegi")
    print("3.Menghitung luas persegi panjang")
    print("4.Menghitung keliling persegi panjang")
    print("5.Menghitung luas segitiga")
    print("6.Menghitung keliling segitiga")
    print("7.Menghitung luas lingkaran")
    print("8.Menghitung keliling lingkaran")
    print("9.Menghitung luas jajar genjang")
    print("10.Menghitung keliling jajar genjang")

    elif pilihan==2:
        print("keliling bujur sangkar")
        print('')
        s=int(input("masukkan sisi:"))
        print("keliling bujur sangkar adalah:", keliling_bujur_sangkar(s))
        print('')
        
    
    elif pilihan==3:
        print("luas persegi panjang")
        print('')
        p=int(input("masukkan panjang:"))
        l=int(input("masukkan lebar:"))
        print("luas persegi panjang adalah:", luas_persegi_panjang(p,l))
        print('')
        print('')
        
    elif pilihan==4:
        print("keliling persegi panjang")
        print('')
        p=int(input("masukkan panjang:"))
        l=int(input("masukkan lebar:"))
        print("keliling persegi panjang adalah:", keliling_persegi_panjang(p,l))
        print('')
        print('')
        
    elif pilihan==5:
        print("luas segitiga")
        print('')
        a=int(input("masukkan alas:"))
        t=int(input("masukkan tinggi:"))
        print("luas segitiga adalah:", luas_segitiga(a,t))
        print('')
        print('')
        
    elif pilihan==6:
        print("keliling segitiga")
        print('')
        s=int(input("masukkan sisi:"))
        print("keliling segitiga adalah:", keliling_segitiga(s))
        print('')
        
    elif pilihan==7:
        print("luas lingkaran")
        print('')
        r=int(input("masukkan jari-jari:"))
        print("luas lingkaran adalah:", luas_lingkaran(r))
        print('')
        
    elif pilihan==8:
        print("keliling lingkaran")
        print('')
        r=int(input("masukkan jari-jari:"))
        print("keliling lingkaran adalah:", keliling_lingkaran(r))
        print('')
        
    elif pilihan==9:
        print("luas jajar genjang")
        print('')
        a=int(input("masukkan alas:"))
        t=int(input("masukkan tinggi:"))
        print("luas jajar genjang adalah:", luas_jajar_genjang(a,t))
        print('')
        print('')
        
    elif pilihan==10:
        print("keliling jajar genjang")
        print('')
        a=int(input("masukkan sisi a:"))
        b=int(input("masukkan sisi b:"))
        print("luas jajar genjang adalah:", keliling_jajar_genjang(a,b))
        print('')
        print('')
        
    else:
        print("input yang Anda masukkan salah")
        print('')
