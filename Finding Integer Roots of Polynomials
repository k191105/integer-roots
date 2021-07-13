n = int(input("Enter the degree of your polynomial: "))
print("\n")

coefficients = []

for i in range(0,(n+1)): 
  b = input(f'Enter the coefficient of the degree {i} term ')
  coefficients.append(b)

coefficients.reverse()
c = int(coefficients[n])
print("\n\n")

for z in range((-1*c),(c+1)):
  polynomial = 0
  for m in range (0,(n+1)):
    polynomial = polynomial + (int(coefficients[m]))*(z**(n-m))
  if polynomial == 0:
    print(z, "is a root.")

