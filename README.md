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

----

# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim

To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm

Define a function named remove that takes the input string as an argument.

Read the index n from the user input.

Initialize an empty string a to store the new string.

Iterate over each index of the string using a for loop.

Check if the current index i is not equal to n.

If i != n, append the character at index i to string a.

After the loop, return the modified string a.

Print the final result.

## 💻 Program

``` python

def remove(a):
    n=int(input())
    s=a[:n]+a[n+1:]
    print(s)

```

## Output


![image](https://github.com/user-attachments/assets/236c2fa3-6304-46e0-8bac-a884a1cd5f46)



## Result

Thus ,the program has been executed successfully

----

# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim

To write a Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions.

## 🧠 Algorithm

Assign the string "google" to a variable.

Reverse the string manually using slicing ([::-1]).

Compare the original string with the reversed string.

If they are equal, print that the string is a palindrome.

Otherwise, print that it is not a palindrome.

Execute the program.

## Program

``` python

def palindrome(a):
    rev=str(a)[::-1]
    if a==rev:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string=input()
palindrome(string)

```

## Output


![image](https://github.com/user-attachments/assets/72e3d572-a1f7-43da-a02c-3584ad68bbb9)

## Result

Thus,the program has been executed successfully.

----

# Tuple in Python: Check Element Existence

## 🎯 Aim

To write a Python program that checks if the element 'n' and the element 8 exist within a given tuple.

## 🧠 Algorithm

Define a tuple x with some letters and numbers.

Use the in operator to check if the string 'n' exists within the tuple.

Use the in operator to check if the integer 8 exists within the tuple.

Print the results.

## 🧾 Program

``` python

k=eval(input())
if "n" in k:
    print("False")
else:
    print("True")
if "8" in k:
    print("True")
else:
    print("False")

```

## Output

![image](https://github.com/user-attachments/assets/8a2204f5-0791-4b55-8050-629926e7fd0a)


## Result

Thus,the program has been executed successfully.




