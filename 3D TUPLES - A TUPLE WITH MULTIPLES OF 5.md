# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.no 212222060279
#Name Thiyaga Sri Charumathy
l=[]
n=int(input())
for i in range(5,n,5):
    l.append(i)
t=tuple(l)
print(t)
```

### OUTPUT
<img width="736" height="214" alt="image" src="https://github.com/user-attachments/assets/1fd92bc7-0ac6-4154-b3f4-2091e67d17e3" />


### RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number N has been implemented and executed.
