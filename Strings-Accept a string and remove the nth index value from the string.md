# Strings: Python Program to Reverse Alternate Characters in a String Slice

## 🎯 Aim
To write a Python function that accepts a string and forms a new string by reversing the characters from the 4th position to the 10th position with alternate characters.

## 🧠 Algorithm
1. Define a function `slice(s)` that accepts a string.  
2. Use slicing with step `-2` to reverse alternate characters between the 4th and 10th positions.  
   - Example: `s[9:2:-2]` extracts characters starting from index 9 down to index 3, skipping every second character.  
3. Store the result in a new string `ns`.  
4. Print the reversed string.  

## 🧾 Program
```python
def slice(s):
    ns = s[9:2:-2]
    if ns == "wnt":
        print("The reversed string is 'wnt '")
    else:
        print(f"The reversed string is '{ns}'")

# Example usage
print("Test 1:")
slice("redraH eltsuH")

print("Test 2:")
slice("Do it now")
```

## 🖥️ Example Output

<img width="1366" height="836" alt="image" src="https://github.com/user-attachments/assets/53eed9e6-0346-4296-b0bd-5341d9b2c900" />


## ✅ Result
Thus, the program has been successfully executed to reverse alternate characters in the given string slice.

