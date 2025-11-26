## Name : S Dinesh Raghavendara
## Reg No : 212224040078




# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
items=[153,147,124,102]
print(sum(items))
```
## Output
![Screenshot 2025-04-29 120233](https://github.com/user-attachments/assets/c459f7ba-80e3-4ba0-8dfc-fe6e998a5a2b)
## Result
Thus, the python program was executed successfully.

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```python
import re

l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Words without 'e':", l1)
```
## Output
![Screenshot 2025-04-29 120555](https://github.com/user-attachments/assets/441f2da3-ba81-472e-b7ce-d719b858935d)

## Result

The program successfully filters and returns all words from the
list that do not contain the letter 'e' using regular expressions in Python.


# 🧹  To accept the string and join the string using the "-" symbol.

## 🎯 Aim
To write a Python function that accepts a string from the user and joins its characters using the "-" symbol.

## 🧠 Algorithm
1.Start the program.

2.Define a function joinstring(str1).

3.Inside the function, use the join() function with the "-" symbol to join the characters of the string.

4.Return or print the joined string.

5.Accept a string input from the user.

6.Call the function and display the result.

7.Stop the program.

## 💻 Program
```
def joinstring(text):
    print( "-".join(text))
```

## Output
<img width="1004" height="268" alt="image" src="https://github.com/user-attachments/assets/9e27ce97-361e-4f06-a5f6-036e22403b94" />


## Result
The program successfully joins the characters of the given string with the “-” symbol.


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


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x = ('a', 'n', 'g', '8', 8, 10, 'z')

print("'n' exists in tuple:", 'n' in x)
print("8 exists in tuple:", 8 in x)
```
## Output
![Screenshot 2025-04-29 120641](https://github.com/user-attachments/assets/00607186-cdf8-48f2-b001-63a9f87de3be)

## Result

The program successfully checks whether the elements 'n' and 8 exist within the given tuple using the in operator.
