print("Tarea 1 Arepas Dinámicas - León Enrique")

print("Por favor, ingrese los 3 ingredientes que desea en su arepa")

ingrediente1=input("Ingrediente 1: ")

ingrediente2=input("Ingrediente 2: ") 

ingrediente3=input("Ingrediente 3: ")
 
print("Usted desea los siguientes ingredientes: "+ingrediente1+", "+ingrediente2+" y "+ingrediente3)

print("Ahora indique cuántos gramos para cada uno, considere y tome en cuenta el orden anterior")

gingrediente1 = input("Gramos de su Ingrediente 1: ")

gingrediente2 = input("Gramos de Ingrediente 2: ")

gingrediente3 = input("Gramos de su Ingrediente 3: ")

totalGramos = float(gingrediente1) + float(gingrediente2) + float(gingrediente3)

print("La masa total de los ingredientes de su arepa es:", totalGramos,"g")