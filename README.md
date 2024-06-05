from math import *
from random import *

def simulipiece(n):
    p=0
    for i in range(n):
        p=p+randint(0,1)
    return round(p/n,2)

def rep(r):
    for i in range(r):
        a = simulipiece(1000)
    print("a est égale à " + str(a) )

rep(1000)
