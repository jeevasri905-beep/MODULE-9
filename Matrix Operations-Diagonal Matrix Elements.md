# Matrix Operations-Diagonal Matrix Elements Printer 🧮

This Python program reads a matrix of any size from the user and prints **only the diagonal elements**, leaving other elements blank in the output.

## 📌 Aim

To write a Python program that prints only the diagonal elements of a given matrix.

## 🧠 Algorithm

1. Read the number of rows and columns from the user.
2. Initialize an empty matrix of size `rows × columns`.
3. Populate the matrix with user input.
4. Display the full matrix.
5. Iterate through the matrix and:
   - If `i == j`, print the element (main diagonal).
   - Else, print a blank space.
6. Print a newline after each row.

## 🖥️ Program
```
row = int(input())
cols = int(input())

matrix = [list(map(int, input().split())) for i in range(row)]

print(matrix)
for i in range(row):
    for j in range(cols):
        if i == j:
            print("  " * i+str(matrix[i][j]))
```
### Output:
<img width="773" height="395" alt="image" src="https://github.com/user-attachments/assets/055d608d-3e84-47a9-8a6b-2a6b8b392af1" />

## Result
Thus, the program is successfully executed.
