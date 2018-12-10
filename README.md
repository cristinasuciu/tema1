# tema1
fisier = open('numbers.txt')
for linie in fisier:
    suma_pe_linie = 0
    numere = linie.split(",")
    for numar in numere:
        suma_pe_linie = suma_pe_linie + int(numar)
    print(suma_pe_linie)
