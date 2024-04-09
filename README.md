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
Get the input from user using eval(input)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using concatination operation dispaly in the entire rorated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate n values
#Developed by: DURGADEVI P
#Register no.:212223100006
def circulate():
    l=eval(input())
    n=int(input())
    result=l[n:]+l[ :n]
    print("After circulating the values are:",result)
```

## Output:
![output](/Screenshot%202024-04-09%20115909.png)

## Result:
Thus Circulate the values of N variables are successfully executed
