# Tugas-4
# Mebuat program untuk menghitung luas dan keliling lingkaran

# Pertama buat nama variable untuk meng-input data
x = input("Masukkan nilai diameternya (cm) = ")

# Variable tersebut akan berbentuk string maka buatlah variable baru untuk menggantikan ke nilai interger yaitu 'int(x)'
panjang = int(x)

# Setelah itu, Buatlah rumus untuk keliling dan luas lingkaran
# '*' mengalikan
# '**' kuadrat dari
keliling = panjang * (22/7)
luas = (panjang / 2) ** 2 *(22/7)

# Terakhir, buatlah print function untuk menghasilkan eksekusi dari data tersebut, seperti berikut
print(f'Jadi, keliling lingkarannya adalah {keliling}cm dan untuk luasnya adalah 154.0cm')

# Hasil output
# 'Masukkan nilai diameternya (cm) = 14'
# 'Jadi, keliling lingkarannya adalah 44.0cm dan untuk luasnya adalah 154.0cm'
