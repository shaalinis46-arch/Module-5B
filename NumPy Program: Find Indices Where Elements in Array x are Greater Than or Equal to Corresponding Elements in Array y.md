# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

x = np.array([13, 16, 17, 18, 20, 22, 24, 26, 29, 30])
y = np.array([13, 15, 30, 15, 20, 22, 23, 24, 25, 26])

print(np.where(x >= y))
print(np.where(x < y))
```

## Output
<img width="480" height="50" alt="image" src="https://github.com/user-attachments/assets/3721b85e-3c2f-4b0f-9e5c-021f52cdb734" />

## Result
Thus the python program for element wise comparison between two numpy array has been implemented and executed successfully.

