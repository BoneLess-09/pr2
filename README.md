import random

def sifreolusturucu():
    karakter = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

    sifre = ""
    for i in range(10):
        sifre = sifre + random.choice(karakter)
    return sifre

sifreolusturucu()

def yazi_tura():
    para = ()
    random.randint(0,2)
    if para == "0":
      return "YAZI"
    else:
      return "TURA"

yazi_tura()
