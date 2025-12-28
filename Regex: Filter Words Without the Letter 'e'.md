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
<img width="1157" height="287" alt="Screenshot 2025-12-28 131113" src="https://github.com/user-attachments/assets/66b4cc20-b03f-42f8-8883-fc1b28f2d853" />

## Output
<img width="514" height="176" alt="Screenshot 2025-12-28 131132" src="https://github.com/user-attachments/assets/5aff154d-b48a-465a-8c34-f3f41dc697cf" />

## Result
Thus the program is successfully executed.
