age = int(input("Hi there! Please enter your age: "))

sum_of_numbers = 0

for i in range(1, age + 1):
    sum_of_numbers += i

print("The sum of all numbers from 1 to", age, "is:", sum_of_numbers)
