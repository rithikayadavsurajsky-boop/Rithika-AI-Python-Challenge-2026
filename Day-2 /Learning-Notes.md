# Day 2 - Python Collections + Loops

## What I Learned

### 1. For Loop

A `for` loop is used to repeat a block of code for each item in a sequence.

```python
for i in range(1, 6):
    print(i)
```
Output:
1
2
3
4
5

### 2. While Loop
A while loop repeats a block of code as long as a condition is True.

```python
i = 1
while i <= 5:
    print(i)
```
    i += 1

### 3. range()
range() generates a sequence of numbers.

for i in range(1, 6):
    print(i)

### 4. Lists
A list is an ordered and changeable collection of elements.

numbers = [10, 20, 30, 40, 50]
print(numbers)

### 5. List Indexing
List indexing starts from 0.

numbers = [10, 20, 30, 40, 50]

print(numbers[0])
print(numbers[2])
print(numbers[-1])

Output:
10
30
50

### 6. List Slicing

Slicing is used to get a part of a list.

numbers = [10, 20, 30, 40, 50]

print(numbers[1:4])
print(numbers[:3])
print(numbers[2:])

### 7. List Methods

append()

Adds an element to the end of a list.

numbers = [10, 20, 30]
numbers.append(40)

print(numbers)

remove()
Removes a specific element.

numbers = [10, 20, 30]
numbers.remove(20)

print(numbers)

sort()
Sorts the list in ascending order.

numbers = [30, 10, 20]
numbers.sort()

print(numbers)

pop()
Removes and returns an element from the list.

numbers = [10, 20, 30]
numbers.pop()

print(numbers)

### 8. Tuples
A tuple is an ordered collection that cannot be changed after creation.

numbers = (10, 20, 30, 40)

print(numbers)
print(numbers[0])

### 9. Sets
A set is an unordered collection that does not allow duplicate elements.

numbers = {10, 20, 30, 20, 10}

print(numbers)

Duplicate values are automatically removed.

### 10. Dictionaries

A dictionary stores data in key-value pairs.

student = {
    "name": "Rithika",
    "age": 20,
    "marks": 85
}

print(student["name"])
print(student["marks"])
