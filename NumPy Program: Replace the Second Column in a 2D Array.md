# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np

a = np.array(list(map(int, input().split()))).reshape(3, 3)

print("Printing Original array")
print(a)

b = np.delete(a, 1, axis=1)

print("Array after deleting column 2 on axis 1")
print(b)

c = np.insert(b, 1, 10, axis=1)

print("Array after inserting column 2 on axis 1")
print(c)
```
## Output
<img width="443" height="290" alt="image" src="https://github.com/user-attachments/assets/d75b83b3-2acb-4846-b90c-a60363d6420c" />

## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.

