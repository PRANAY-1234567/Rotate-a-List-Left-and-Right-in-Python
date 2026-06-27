Rotate a List Left and Right in Python
 
📌 Description

This program demonstrates how to rotate a list to the left and to the right by one position using simple Python list operations.
It is written in an easy way, suitable for beginners.

🧩 Problem Statement

Given a list:

[1, 2, 3, 4]

Left Rotation (by 1)

Result:

[2, 3, 4, 1]

Right Rotation (by 1)

Result:

[4, 1, 2, 3]

1️⃣ Rotate Left (by 1)
✅ Code
numbers = [1, 2, 3, 4]

first = numbers.pop(0)
numbers.append(first)

print(numbers)

🧠 Explanation

pop(0) removes the first element

append() adds it to the end

The list shifts left by one position

2️⃣ Rotate Right (by 1)
✅ Code
numbers = [1, 2, 3, 4]

last = numbers.pop()
numbers.insert(0, last)

print(numbers)

🧠 Explanation

pop() removes the last element
insert(0, value) adds it at the beginning
The list shifts right by one position

🛠 Concepts Used

Lists
pop()
append()
insert()
Basic list manipulation

🎯 Use Cases

Data rotation problems
Coding interview practice
Learning list operations
Beginner Python exercises

🚀 Future Improvements

Rotate by N positions
Use functions
Optimize using slicing

👨‍💻 Author
Pranay Jadhao
