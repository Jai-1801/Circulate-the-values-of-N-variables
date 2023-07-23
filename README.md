# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function called 'circulate'
### Step 2: 
Get the first element from the list to be used later.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept to rotate the list

### Step 5: 
After shifting the elements, place the first element at the end of the list.
### Step 6:
Return the modified list with the circulated values. 

## Program:
```
#Program to circulate N values.
#Developed by:Jai Surya
#RegisterNumber:23002572
def circulate():
    lst=eval(input())
    n=int(input())
    print("After circulating the values are:",lst[n:]+lst[:n])
```

## Output:
![OUTPUT](/OUTPUT.png)

## Result:
The values have successfully circulated using the function concept in Python.