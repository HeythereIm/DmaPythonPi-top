# DmaPythonPi-top
import random
x=random.randint(1,3)
r = "Rock"
p = "Paper"
s = "Scissors"

if x==1:
    pc = r

if x==2:
    pc = p

if x==3:
    pc = s

my= input("r")

if pc == r and my == r:
    print("It's a tie")
    
if pc == p and my == r:
    print("You're bad")
    
if pc == s and my == r:
    print("You win")
    
if pc == r and my == p:
    print("You win")
    
if pc == p and my == p:
    print("It's a tie")
    
if pc == s and my == p:
    print("Your bad")
    
if pc == r and my == s:
    print("You're bad")
    
if pc == p and my == s:
    print("You win")

if pc == s and my == s:
    print ("It's a tie")
