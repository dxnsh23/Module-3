# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def is_palindrome_string(s):
    length = len(s)
    for i in range(length // 2):
        if s[i] != s[length - i -1]:
            return False
        return True
        
s = input()
if(is_palindrome_string(s)):
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
<img width="1038" height="247" alt="image" src="https://github.com/user-attachments/assets/d8b0cece-6b1b-4b39-8bd1-6562aa10b135" />


## Result
The Python program was successfully executed to check whether a given string is a palindrome without using built-in palindrome functions.

