
# Python Program to Find Sequences of Lowercase Letters Joined with '@'

## 🎯 Aim
To write a Python program that checks whether a string contains a sequence of lowercase letters followed by the symbol `@`.

## 🧠 Algorithm
1. Read a string input from the user.  
2. Use the `re` (regular expressions) module to search for the pattern `[a-z]+@`.  
   - `[a-z]+` matches one or more lowercase letters.  
   - `@` ensures the sequence is followed by the `@` symbol.  
3. If a match is found, print `"Found a match!"`.  
4. Otherwise, print `"Not matched!"`.  

## 🧾 Program
```python
import re

st = str(input("Enter a string: "))
fi = re.search(r"[a-z]+@", st)
if fi:
    print("Found a match!")
else:
    print("Not matched!")
```

## 🖥️ Example Output
<img width="1364" height="891" alt="image" src="https://github.com/user-attachments/assets/b867f0de-3906-4ac1-bed3-aeae9840d8bf" />



## ✅ Result
Thus, the program has been successfully executed to check for sequences of lowercase letters joined with `@`.

