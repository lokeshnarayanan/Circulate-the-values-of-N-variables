# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1:
Take input from the user.
### Step 2:
Use functions and pass parameters.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print circulated values.
### Step 6:
End the program.
## Program:
```
#Program to circulate N values.
#Developed by: Lokesh N
#RegisterNumber:212222100023
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![image](https://user-images.githubusercontent.com/119393019/225551173-99ecda67-ed8c-4669-8eb9-1fb58a1e5d69.png)

## Result:
Thus the circulate-the -values-of-N-variables are sucessfully excuted.
