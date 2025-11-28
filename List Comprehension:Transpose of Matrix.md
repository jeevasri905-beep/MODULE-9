# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
def transpose_matrix(matrix):
    return [[matrix[j][i] for j in range(len(matrix))] for i in range(len(matrix[0]))]
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

transposed_matrix = transpose_matrix(matrix)

print("Original Matrix:")
for row in matrix:
    print(row)
print("\nTransposed Matrix:")
for row in transposed_matrix:
    print(row)
```
## OUTPUT:
<img width="463" height="424" alt="image" src="https://github.com/user-attachments/assets/b8ef734f-478f-462b-b6aa-76f25f7378d7" />

## RESULT:
Thus, the program is executed successfully.

