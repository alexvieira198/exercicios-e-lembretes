# exercicios-e-lembretes
x = 2
y = [10, 11, x, 13, "Ola", "casa", "carro", "pé" ]
for z in range(len(y)):
    print (z)
    #vemos que cada elemento da lista "y" recebe uma ordenação, sendo '10' o primeiro e 'pé' o ultimo ( de o a 7)

print ("__________________________________________")

x = 'OLA'
myList = [10, 11, x, 13, "Ola", "casa", "carro", "p ́e"]
i = 1
while myList[i] != "carro":
    print(myList[i])
    i+=1
    
print ("__________________________________________")

x = 1
y = 1%0.5

if x is y:
    print("iguais")
else:
    print ('naao')
    
print ("__________________________________________")
f = ['a','b','c','d','e']
fa = 'a'
fb = 'b'
print(fa not in f)
