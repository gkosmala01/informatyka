from random import random, shuffle
from math import prod
N = 1000
low=2.0
high=10.0
x = []

for i in range(N):
    r = random() * (high - low) + low
    x.append(r)
    x.append(1 / r)

shuffle(x)
product1 = prod(x)
print(product1)
