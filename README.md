# Prob-EXP-01
#CODE 
'''
n = int(input("Enter number of values: "))

x = []
p = []

for i in range(n):
    xi = float(input(f"Enter value x{i+1}: "))
    pi = float(input(f"Enter probability p{i+1}: "))
    x.append(xi)
    p.append(pi)

if sum(p)!=1:
    print("Invalid PMF: Probabilities do not sum to 1")
else:
    EX = 0
    EX2 = 0

  for i in range(n):
        EX += x[i] * p[i]
        EX2 += (x[i] ** 2) * p[i]

  variance = EX2 - (EX ** 2)

  print("Random variable values:", x)
    print("Probabilities:", p)
    print("Mean =", EX)
    print("Variance =", variance)
    '''
  #Output
  Enter number of values: 4
Enter value x1: 0
Enter probability p1: 0.25
Enter value x2: 1
Enter probability p2: 0.25
Enter value x3: 2
Enter probability p3: 0.25
Enter value x4: 3
Enter probability p4: 0.25
Random variable values: [0.0, 1.0, 2.0, 3.0]
Probabilities: [0.25, 0.25, 0.25, 0.25]
Mean = 1.5
Variance = 1.25

#RESULT:
Hence the program for finding the mean and variance for a given probability distribution function is written and verified through output .
