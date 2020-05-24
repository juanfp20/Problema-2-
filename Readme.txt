while True:
	try:
		p1 = int(input("ingrese la nota del primer parcial"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")
while True:
	try:
		p2 = int(input("ingrese la nota del segundo parcial"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

while True:
	try:
		t = int(input("ingrese la nota del taller"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

while True:
	try:
		proy = int(input("ingrese la nota del proyecto"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

p1= p1*0.25
p2=p2*0.25
t=t*0.20
proy=proy*0.30

suma = (p1+p2+t+proy)

print("su nota final es:")

print(suma)

