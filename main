import math


print("Kāda iespēja izvilkt krāsainu bumbiņu starp baltām?!?")
print("Tūlīt arī uzzināsim.")
print('\n')

a = int(input("Ievadiet PIRMĀS loterijas skaitli(cik daudz dāžādu krāsu bumbiņas no baltām jūs gribētu izvikt): "))
b = int(input("Ievadiet cik vispār bumbiņas būs loterejā: "))
if a > b:
    print("Tas nav iespējams. Mēģiniet velreiz.")
    exit(0)

c = int(input("Ievadiet OTRĀS loterijas skaitli(cik daudz dāžādu krāsu bumbiņas no baltām jūs gribētu izvikt): "))
d = int(input("Ievadiet cik vispār bumbiņas būs loterejā: "))
if c > d:
    print("Tas nav iespējams. Mēģiniet velreiz.")
    exit(0)
print("\n")




def varbutiba():


    pirma = a / b
    otra = c / d
    pirmaa = a / b *100
    otraa = c / d *100

    if pirma > otra:
        print("Pirmā loterijā iespēja uzvarēt ir lielāka.")
        print("Tās iespēja ir: ", pirmaa, "%")
    elif pirma < otra:
        print("Otrā loterijā iespēja uzvarēt ir lielāka.")
        print("Tās iespēja ir: ", otraa, "%")
    elif pirma == otra:
        print("Vienāda iespēja uzvarēt abām loterijām.")
    else:
        print("Error, mēgiņiet velreiz.")




varbutiba()

def kombinatorika():

    pirma = a / b
    otra = c / d

    if pirma > otra:
        print("Šī ir tavs iespējamais krāsainu bumbiņu kombinācijas skaits: ", (math.factorial(a)))
    elif pirma < otra:
        print("Šī ir tavs iespējamais krāsainu bumbiņu kombinācijas skaits: ", (math.factorial(c)))
    elif pirma == otra:
        print("Šī ir tavs iespējamais krāsainu bumbiņu kombinācijas skaits(1.loterijai): ", (math.factorial(a)))
        print("Šī ir tavs iespējamais krāsainu bumbiņu kombinācijas skaits(2.loterijai): ", (math.factorial(c)))
