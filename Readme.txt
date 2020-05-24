while True:
	try:
		p1 = float(input("ingrese la nota del primer parcial"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")
while True:
	try:
		p2 = float(input("ingrese la nota del segundo parcial"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

while True:
	try:
		t = float(input("ingrese la nota del taller"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

while True:
	try:
		proy = float(input("ingrese la nota del proyecto"))
		break
	except ValueError:
		print("Opps, ingrese nuevamente")

p1= p1*1.25
p2=p2*1.25
t=t*1.20
proy=proy*1.30

suma = (p1+p2+t+proy)/4

print("su nota final es:")

print(suma)

