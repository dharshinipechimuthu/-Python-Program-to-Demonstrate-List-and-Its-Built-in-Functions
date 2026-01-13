# -Python-Program-to-Demonstrate-List-and-Its-Built-in-Functions
# Creating a list
numbers = [10, 20, 30, 40, 50]

print("Original List:", numbers)

# append() – Adds an element at the end
numbers.append(60)
print("After append(60):", numbers)

# insert() – Inserts element at a specific position
numbers.insert(2, 25)
print("After insert(2, 25):", numbers)

# remove() – Removes a specific element
numbers.remove(40)
print("After remove(40):", numbers)

# pop() – Removes and returns element at given index
removed_element = numbers.pop(3)
print("After pop(3):", numbers)
print("Popped Element:", removed_element)

# index() – Returns index of an element
index_value = numbers.index(30)
print("Index of 30:", index_value)

# count() – Counts occurrences of an element
count_value = numbers.count(20)
print("Count of 20:", count_value)

# sort() – Sorts the list
numbers.sort()
print("After sort():", numbers)

# reverse() – Reverses the list
numbers.reverse()
print("After reverse():", numbers)

# len() – Returns length of the list
print("Length of list:", len(numbers))

# clear() – Removes all elements
numbers.clear()
print("After clear():", numbers)

Output:
Original List: [10, 20, 30, 40, 50]
After append(60): [10, 20, 30, 40, 50, 60]
After insert(2, 25): [10, 20, 25, 30, 40, 50, 60]
After remove(40): [10, 20, 25, 30, 50, 60]
After pop(3): [10, 20, 25, 50, 60]
Popped Element: 30
Index of 30: 3
Count of 20: 1
After sort(): [10, 20, 25, 50, 60]
After reverse(): [60, 50, 25, 20, 10]
Length of list: 5
After clear(): []

