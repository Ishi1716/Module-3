# List Operations in Python: Sum of List Items

## 🎯 Aim

To write a Python program that calculates the sum of all elements in a list.

## 🧠 Algorithm

Define a list of numbers.

Use Python’s built-in sum() function to calculate the total.

Print the result.

## 🧾 Program

``` python

 L=[153,147,124,102] 
print(sum(L)))

```

## Output

![image](https://github.com/user-attachments/assets/5cfe4778-0e94-44b1-a239-6ae7a104ab6e)

## Result

Thus, the program has been executed successfully.

----

# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim

To write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex).

## 🧠 Algorithm

Import the re module.

Initialize an empty list l1 to store results.

Define a list of words:

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

Iterate through each word in the list:

Use re.search(r"e", i) to check if the word contains 'e'.

If not, append the word to l1.

Print the final filtered list.

## 🧾 Program

```
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = [item for item in items if not re.search(r'e', item)]
print(result)

```

## Output

![image](https://github.com/user-attachments/assets/4c537d60-a8d7-496a-ad97-3d4313ecde7c)


## Result

Thus,the program has been executed successfully.




