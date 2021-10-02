# Muhammad-Afdhal.-F
belajar membuat kalkulator sederhana
print(20*'=')
print("kalkulator sederhana")
print(20*"=" + "\n")

angka_1 = float(input("masukkan angka 1 = "))
operator = input("operator (+,-,x,/) : ")
angka_2 = float(input("masukkan angka 2= "))

if operator == "+":
    hasil = angka_1 + angka_2
    print(f"hasilnya adalah {hasil}")
elif operator == "-":
    hasil = angka_1 - angka_2
    print(f"hasilnya adalah {hasil}")
elif operator == "*" or operator == "x":
    hasil = angka_1 * angka_2
    print(f"hasilnya adalah {hasil}")
elif operator == "/":
    hasil = angka_1 / angka_2
    print(f"hasilnya adalah {hasil}")
else:
    print("masukkan yg baik mbak")

Print("akhirnya selesai")
