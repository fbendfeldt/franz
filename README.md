# franz
n=0 N=int(input("ingrese numero: "))  sumatorio=0 lista=[     ] for x in range(1,N):     if N%x==0:         sumatorio=sumatorio+x         lista.append(x)  if sumatorio==N:     print(N,'es un numero perfecto  ',lista) else:     print("No es perfecto")      input()
