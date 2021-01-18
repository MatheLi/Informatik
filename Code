# -*- coding: utf-8 -*-
"""
Spyder Editor

Dies ist eine temporäre Skriptdatei.
"""
def Erwartungswertfunktion(n,p):
    print("Erwartungswert:")
    return n*p
def Standardabweichungfunktion(n,p):
    print("Standardabweichung:")
    z= (n*p*(1-p))**0.5
    return z
def Binomialkoeffizientfunktion(n,k):
    print("Binomialkoeffizient:")
    a=n
    m= fakult(a)
    a=k
    l= fakult(a)
    a=n-k
    o= fakult(a)
    y= m/(l*o)
    return y
def fakult(a):
    if a < 0:
        raise ValueError
    if a == 0:
        return 1
    else:
        b = 1
        for i in range(2,a+1):
            b *= i
        return b
print("Dieses Programm ist zum Kapitel Wahrscheinlichkeiten. Im Folgenden können Sie verschiedene Zahlen eingeben um die Fakultät (0), den Erwartungswert (1), die Standardabweichung (2), den Binomialkoeffizient(3) zu berechnen.")

x=int(input())
if x==0:
    "Bitte geben Sie eine Zahl an von der die Fakultät berechnet werden soll."
    a=int(input())
    print(fakult(a))
if x==1 :
    "Bitte geben Sie n an um den Erwartungswert zu berechnen."
    n=int(input())
    "Bitte geben Sie p an."
    p=float(input())
    print(Erwartungswertfunktion(n,p))
elif x==2:
    "Bitte geben Sie n an um die Standardabweichung zu berechnen."
    n=int(input())
    "Bitte geben Sie p an."
    p=float(input())
    print(Standardabweichungfunktion(n,p))
elif x==3:
    "Bitte geben Sie n an um den Binomialkoeffizienten zu berechnen."
    n=int(input())
    "Bitte geben Sie p an."
    k=int(input())
    print(Binomialkoeffizientfunktion(n,k))

