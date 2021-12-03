# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
 get the value from the user
### Step 2: 
give the input
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
 print the values
### Step 6: 
u get the result
## Program:
~~~
def circulate():
    l=[10,20,30,40,50,60]
    n=int(input())
    result=l[n: ]+l[ :n]
    print("After circulating the values are:",result)
~~~    

## Output:
![output](exam.png)
## Result:
successfully circulated the values
