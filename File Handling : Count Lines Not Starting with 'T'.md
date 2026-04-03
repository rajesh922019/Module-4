# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program

try:

    # Taking 3 elements input from the user
    
    L = []
    
    for i in range(3):
    
        item = ['laptop','mobile','pen']
        
        L.append(item)

    # Trying to access index 4
    
    print(L[4])

except IndexError:

    print("check index range")


## Output
<img width="957" height="246" alt="image" src="https://github.com/user-attachments/assets/7c4c4bf5-be46-4c14-87af-d885bbed2e5e" />

## Result

Thus the program executed successfully.
