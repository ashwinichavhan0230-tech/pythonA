# pythonA
fruits = ["Apple", "Banana", "Mango", "Orange"]
print(fruits)
#Output: ['Apple', 'Banana', 'Mango', 'Orange']

numbers = [10, 20, 30, 40, 50]

print(numbers[0])
print(numbers[2])
print(numbers[-1])
#Output: 10
#Output: 30
#Output: 50

numbers = [10, 20, 30]
numbers.append(40)
print(numbers)
#Output: [10, 20, 30, 40]

numbers = [10, 20, 40, 50]
numbers.insert(2, 30)
print(numbers)
#Output: [10, 20, 30, 40, 50]


numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print("Sum:", total)
#Output: Sum: 150

numbers = [10, 50, 20, 80, 30]
print("Largest number:", max(numbers))
#Output: 80

numbers = [10, 50, 20, 80, 30]
print("Smallest number:", min(numbers))
#Output: 10
