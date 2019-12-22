sayi = input("Sayıyı Giriniz :")
sayim = input("2. Sayı Giriniz :")
if (sayi>sayim):
    print("1. Sayı 2. Sayıdan Büyüktür >> =")
    print(sayi)
elif (sayi==sayim):
    print("Sayılar Eşittir >> =")
    print(sayi,sayim)
elif (sayi<sayim):
    print("2. Sayı 1. Sayıdan Büyüktür >> =")
    print(sayim)
