# sign-up
pythonda kayıt menüsü
kullanici_ismi = input("enter here your nickname: ")
sifre = input("enter here your password: ")
nick = (kullanici_ismi)
password = (sifre)
second = input("enter here your nickname: ")
if second in nick:
    print("kullanici ismi doğrudur")
else:
    print("kullanici ismi yanliştir")
lock = input("enter here your password: ")
if lock in password:
    print("şifre doğrudur")
else:
    print("şifre yanliştir")

#buradaki sistem oldukça basit ve öz bir yapıdadır.
