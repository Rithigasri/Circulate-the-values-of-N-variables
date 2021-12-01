# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Use the function Circulate

### Step 2: 
Assign variables into List.

### Step 3: 
Get the value from the user for the number of rotation.

### Step 4: 
Using the slicing concept rotate the List.

### Step 5:
Print the Result.

### Step 6:
End the Program.

## Program:
```
#Program to circulate N values.
#Developed by: Rithiga Sri.B
#RegisterNumber:21500732
def circulate():
    l=[10,20,30,40,50,60]
    n=int(input())
    result=l[n:]+l[:n]
    print("After circulating the values are:",result)
```

## Output:
![Output](./Output.png)

## Result:
Thus circulating the n variables is successfully executed.
