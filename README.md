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

    pilihan=int(input("Masukkan pilihan anda :"))
    print('')
    print('')
    if pilihan==1:
        print("Luas Persegi")
        print('')
        s=int(input("Masukkan sisi :"))
        print("Luas Persegi:",luas_persegi(s))
        print('')
        print('')
    elif pilihan==2:
        print("Keliling Persegi")
        print('')
        s=int(input("Masukkan sisi :"))
        print("Keliling persegi :",kelilin_persegi(s))
        print('')
        print('')
    elif pilihan==3:
        print("Luas Persegi Panjang")
        print('')
        p=int(input("Masukkan panjang :"))
        l=int(input("Masukkan lebar :"))
        print("Luas persegi panjang :",luas_persegi_panjang(p,l))
        print('')
        print('')
    elif pilihan==4:
        print("Keliling Persegi Panjang")
        print('')
        p=int(input("Masukkan panjang :"))
        l=int(input("Masukkan lebar :"))
        print("Keliling persegi panjang :",keliling_persegi_panjang(p,l))
    elif pilihan==5:
        print("Luas Segitiga")
        print('')
        a=int(input("Masukkan alas :"))
        t=int(input("Masukkan tinggi :"))
        print("Luas segitiga :",luas_segitiga(a,t))
        print('')
        print('')
    elif pilihan==6:
        print("Keliling Segitiga")
        print('')
        a=int(input("Masukkan sisi a :"))
        b=int(input("Masukkan sisi b :"))
        c=int(input("Masukkan sisi c :"))
        print("Keliling Segitiga :",keliling_segitiga(a,b,c))
        print('')
        print('')
    elif pilihan==7:
        print("Luas Lingkaran")
        print('')
        r=int(input("Masukkan jari jari :"))
        print("Luas Lingkaran :",luas_lingkaran(r))
        print('')
        print('')
    elif pilihan==8:
        print("Keliling Lingkaran")
        print('')
        r=int(input("Masukkan jari jari :"))
        print("Keliling Lingkaran :",keliling_lingkaran(r))
        print('')
        print('')
    elif pilihan==9:
        print("Luas Jajar Genjang")
        print('')
        a=int(input("Masukkan alas :"))
        t=int(input("Masukkan tinggi :"))
        print("Luas Jajar Genjang :",luas_jajar_genjang(a,t))
        print('')
        print('')
    elif pilihan==10:
        print("Keliling Jajar Genjang")
        print('')
        a=int(input("Masukkan sisi a :"))
        b=int(input("Masukkan sisi b :"))
        print("Keliling Jajar Genjang :",keliling_jajar_genjang(a,b))
        print('')
        print('')
    else:
        print("Input yang anda masukkan salah")
        print('')
        print('')
    
