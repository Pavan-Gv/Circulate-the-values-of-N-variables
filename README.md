# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function.
### Step 2: 
Give the value of function.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
using l= L[n:]+L[:n] solve the circulation.
### Step 6:
End the program.
## Program:
def circulate():
    L= [10,20,30,40,50,60]
    n= int(input())
    l= L[n:]+L[:n] 
    print("After circulating the values are:",l)
    
## Output:
![Circulating](/circu/circulate.png)
## Result:
Therefore we successfully circulated the n variables using function concept.
