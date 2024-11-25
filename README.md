# Reto-3
<pre>
n=int(input("ingrese el numero:"))
a=1
while a<=(n):
    b = 1
    v = 0
    while b<=a:
	    c = a%b
	    if c == 0:
		    v = v+1
		    b = b+1
	    elif c !=0:
		    b = b+1
    if v ==2:
        print(a)
        a=a+1
        b=1
        v=0
    elif v >=3:
        a=a+1
        b=1
        v=0
</pre>
DIAGRAMA DE FLUJO:
![Captura de pantalla 2024-11-25 174501](https://github.com/user-attachments/assets/9fec608a-acd1-495a-8698-e487fc1352cf)
