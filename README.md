# python-largest-number-list

# Python program to find the largest number in a list without using built-in functions

numbers = [3, 8, 1, 7, 2, 9, 5, 4]

big = numbers[0]        # Initialize the largest number
position = 0            # Initialize position of the largest number

# Iterate through the list
for i in range(len(numbers)):
    if numbers[i] > big:
        big = numbers[i]
        position = i

print("The largest element is", big, "which is found at position", position)
OUTPUT:

The largest element is 9 which is found at position 5
