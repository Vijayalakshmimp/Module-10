# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).

## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
~~~
from collections import deque
q = deque()
n=int(input())
for i in range(n):
    q.append(input())
for i in range(2):
    q.popleft()
print(q)
~~~

### Output:
<img width="1241" height="448" alt="image" src="https://github.com/user-attachments/assets/60800de6-363e-4c7d-806f-5397497aa2c5" />

## Result:
Thus, the program has been executed and verified successfully.
