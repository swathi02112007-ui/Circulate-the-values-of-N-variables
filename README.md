# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Commence the program
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4: 
Print the rotated list
### Step 5: 
End the program.

## Program:
~~~
def circulate():
    values = eval(input())
    
    k = int(input())

    n = len(values)
    k = k % n

    values = values[k:] + values[:k]

    print("After circulating the values are:", values)
  ~~~
## Output:

<img width="1331" height="815" alt="Screenshot 2026-06-27 125243" src="https://github.com/user-attachments/assets/60ad0771-f59b-4465-b00f-91252c874ff8" />

## Result:
Thus the program is excuted successfully
