# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the list from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated list
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Shehan Shajahan
#RegisterNumber: 23008724
def circulate():
     l=eval(input())
     n=int(input())
     l=l[n:]+l[ :n]
     print("After circulating the values are:",l)
```

## Output:
!["Output"](/output.png)

## Result:
The Python program for circualting n variables has been executed successfully.
