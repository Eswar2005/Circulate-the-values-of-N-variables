# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define Function as Circulate
### Step 2: 
Get the list value from user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the program
## Program:
```
#Program to circulate N values.
#Developed by: Thirukaalathessvarar S
#RegisterNumber: 22004529
def circulate():
    list1=eval(input())
    n=int(input())
    list1=list1[n:]+list1[:n]
    print("After circulating the values are:",list1)
```

## Output:
![output](hehe.png)

## Result:
Thus the program is successfully executed.
