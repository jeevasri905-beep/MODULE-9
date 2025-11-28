# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

---

## 💻 PROGRAM:
```
def create_matrix(r,c):
        m=[[int(input()) for i in range(c)] for j in range(r)]
        return m
def subtract(c,l):
    a=len(c)
    b=len(c[0])
    r=[[c[i][j]-l[i][j] for j in range(b)] for i in range(a)]
    return r
A=create_matrix(3,3)
B=create_matrix(3,3)
print("A=",A)
print("B=",B)
print(subtract(A,B))
```

## OUTPUT:
<img width="933" height="371" alt="image" src="https://github.com/user-attachments/assets/63e3a81b-f270-4e3c-8eb2-fe6b4ac5a00e" />
## RESULT:
Thus, the program is successfully executed.
