# to-find-smallest-number-in-a-list-in-python
# Apporach-1

# In Ascending Order
# Python program to find smallest number in a list
# list of numbers
list1 = [10, 20, 4, 45, 99]

# sorting the list
list1.sort()

# printing the first element
print("Smallest element is:", list1[0])

# Apporach-2

# IN Descending Order
# list of numbers
list1 = [10, 20, 4, 45, 99]

# sorting the list
list1.sort(reverse=True)

# printing the first element
print("Smallest element is:", list1[-1])

# Apporach-3

# Using min() Method to find smallest number in a list
# Python program to find smallest number in a list

# list of numbers
list1 = [10, 20, 1, 45, 99]

# printing the minimum element
print("Smallest element is:", min(list1))

# Apporach-4

# Find minimum list element for a user defined list
# Python program to find smallest number in a list
# creating empty list
list1 = []

# asking number of elements to put in list
num = int(input("Enter number of elements in list: "))

# iterating till num to append elements in list
for i in range(1, num + 1):
	ele= int(input("Enter elements: "))
	list1.append(ele)
	
# print minimum element:
print("Smallest element is:", min(list1))
