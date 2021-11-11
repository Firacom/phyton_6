# phyton_6
SOURCE KODE:
try:
    level = input("level kamu : ")
    level = int(level)
    print(level)
    
except ValueError:
    print("yang kamu masukkan itu benar") 
    print("\n") 

try:
    level = input("level kamu : ")
    level = int(level)
    level = level / 0
    print(level)
    
except:
    print("telah terjadi kesalahan pada dirimu") 
    print("\n") 

users = open("file tgs membaca file.py", "r")

#read untuk membaca semua
#readline untuk membaca baris awal saja

#print(users.readline())

Array = users.readlines()
print(Array [1])

users.close()

# "r" untuk menulis data di file
# "a" untuk menambahkan data ke file yang sudah ada
# "r+" untuk membaca dan bisa menulis
print("\n") 

users = open("file tgs membaca file.py", "a")

users.write(" belum_makan - dari_pagi")
users.close()

OUTPUT:
