total1=0
total2=0
totalsemua=0
jenis1=""
jenis2=""

print("=== Program Sederhana Pemesanan Makanan & Minuman ===")
nama = input("Masukkan nama Konsumen: ")
print ("Nama Konsumen :", nama)
print("")
print ("Menu Makanan")
    


def pilihan(i):
        switcher={
                1:'----Nasi Goreng 12000----',
                2:'----Sate Ayam 30000----',
                3:'----Sop Iga 25000----'
             }
        return switcher.get(i,"Masukan Pilihan yang Benar!")


print("1. Nasi Goreng")
print("2. Sate Ayam")
print("3. Sop Iga")
nomor=int(input("Masukan Pilihan: "))
menu=pilihan(nomor)
print (menu)
porsi1= int(input("Berapa Porsi: "))

if nomor==1:
    total1=total1+porsi1*12000
    print ("Hasilnya = ", total1)
    jenis1=("Nasi Goreng")
if nomor==2:
    total1=total1+porsi1*30000
    print ("Hasilnya = ", total1)
    jenis1=("Sate Ayam")
if nomor==3:
    total1=total1+porsi1*25000
    print ("Hasilnya = ", total1)
    jenis1=("Sop Iga")

def pilihan(i):
        switcher={
                1:'----Es Teh Manis 3000----',
                2:'----Es Jeruk 4000----',
                3:'----Jus Alpukat 9000----'
             }
        return switcher.get(i,"Masukan Pilihan yang Benar!")
print("\nMenu Minuman")
print("1. Es Teh Manis")
print("2. Es Jeruk")
print("3. Jus Alpukat")
nomor=int(input("Masukan Pilihan: "))
menu=pilihan(nomor)
print (menu)
porsi2= int(input("Berapa Gelas: "))
if nomor==1:
    total2=total2+(porsi2*3000)
    print ("Hasilnya = ", total2)
    jenis2=("Es Teh Manis")
if nomor==2:
    total2=total2+(porsi2*4000)
    print ("Hasilnya = ", total2)
    jenis2=("Es Jeruk")
if nomor==3:
    total2=total2+(porsi2*9000)
    print ("Hasilnya = ", total2)
    jenis2=("Jus Alpukat")
    
uang=int(input("\nUang Tunai: Rp."))
totalsemua=total1+total2    
print("\n=========================")
print("======= S T R U K =======")
print("=========================")
print ("=== Nama      :",nama)
print ("=== Beli      :",porsi1,jenis1)
print ("===            ",porsi2,jenis2)
print ("=== Tagihan   :Rp.",totalsemua)
print ("=== Uang      :Rp.",uang)
akhir=int(uang-totalsemua)
print ("=== Kembalian :Rp.",akhir)
print("=========================")
print("=========================")
print("  TERIMAKASIH SUDAH MEMBELI")
print(" DATANG LAGI YAAAAAA.......")
print("===========================")
print("===========================")
