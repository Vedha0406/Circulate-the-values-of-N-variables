# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
First step is to define the function
### Step 2: 
Get a,n inputs from the user
### Step 3: 
Define the formula 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Finally print the result
### Step 6: 
## Program:
Developed by:Vedhashree.G
Register No:212223240171
---
def circulate():

    l=eval(input())

    n=int(input())

    l=l[n:]+l[:n]
    
    print("After circulating the values are:",l)
---



## Output:
![alt text](image-1.png)

## Result:
By this program we able to circulate the values of n - variables
