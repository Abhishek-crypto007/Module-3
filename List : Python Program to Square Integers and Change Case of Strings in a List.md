

# Python Program to Square Integers and Change Case of Strings in a List

## 🎯 Aim
To write a Python program that accepts a list containing integers and strings, squares the integers, and changes the case of the strings.

## 🧠 Algorithm
1. Define a function `change(L)` that accepts a list.  
2. Initialize an empty list `res`.  
3. Iterate through each element of the list using a loop.  
4. If the element is an integer, append its square to `res`.  
5. If the element is a string, append its case-swapped version using `.swapcase()`.  
6. Print the final list `res`.  

## 🧾 Program
```python
def change(L):
    res = []
    for i in range(len(L)):
        if type(L[i]) == int:
            res.append(L[i] ** 2)
        elif type(L[i]) == str:
            res.append(L[i].swapcase())
    print(res)  

L = eval(input("Enter a list: ")) 
change(L)
```

## 🖥️ Example Output
<img width="1360" height="785" alt="image" src="https://github.com/user-attachments/assets/ff8bfa56-480d-4f44-b2ea-3beabc0fbe43" />



## ✅ Result
Thus, the program has been successfully executed to square integers and change the case of strings in the given list.
