# LAB-11
Tuples
print("RATA RATA PENJUALAN MOTOR HONDA JOHAN JAYA")

def penjualan (motor) :
    a =  len(motor)
    nilAkhir = 0
    for i in motor :
        laku = int(input("jumlah yang laku merk motor %s : "%(i)))
        nilAkhir += laku
        merk2 = nilAkhir / a
        print("jumlah rata-rata penjualan motor Honda di Johan motor saat ini adalah : ", merk2)

motor = ("scoopy","supra","pcx","beat","genio","vario","megapro","cbr","revo","blade")
penjualan(motor)
        


        
