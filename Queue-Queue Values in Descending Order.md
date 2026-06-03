# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.

## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
```
from queue import PriorityQueue

q = PriorityQueue()

n = int(input())

for i in range(n):
    l = input().split(',')
    q.put((l[0], l[1]))

while not q.empty():
    next_item = q.get()
    print(next_item)
```
### Output:
<img width="501" height="232" alt="image" src="https://github.com/user-attachments/assets/d20dd574-7855-4613-87e3-abfc3e7dcbf7" />

## Result:
Thus the program is verified.

