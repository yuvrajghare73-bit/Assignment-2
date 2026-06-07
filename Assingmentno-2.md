# Practical Assignment - 2

---

## Q1. Create a function welcome() that prints "Welcome to Python Programming".

### Code

```
def welcome():
    print("Welcome to Python Programming")

welcome()
```

### Output

```
Welcome to Python Programming
```

---

## Q2. Create a function college_info() that displays your college name and department.

### Code

```
def college_info():
    print("ABC College")
    print("Computer Engineering")

college_info()
```

### Output

```
ABC College
Computer Engineering
```

---

## Q3. Create a function rules() that prints three classroom rules.

### Code

```
def rules():
    print("1. Be punctual")
    print("2. Maintain discipline")
    print("3. Respect everyone")

rules()
```

### Output

```
1. Be punctual
2. Maintain discipline
3. Respect everyone
```

---

## Q4. Create a function star_pattern() that prints five rows of stars.

### Code

```
def star_pattern():
    for i in range(5):
        print("*" * 5)

star_pattern()
```

### Output

```
*****
*****
*****
*****
*****
```

---

## Q5. Create a function that accepts a student's name and prints a welcome message.

### Code

```
def welcome_student(name):
    print("Welcome", name)

welcome_student("Rahul")
```

### Output

```
Welcome Rahul
```

---

## Q6. Create a function that accepts two numbers and prints their sum.

### Code

```
def add(a, b):
    print("Sum =", a + b)

add(10, 20)
```

### Output

```
Sum = 30
```

---

## Q7. Create a function that accepts a city name and prints "You are from <city>".

### Code

```
def city_name(city):
    print("You are from", city)

city_name("Pune")
```

### Output

```
You are from Pune
```

---

## Q8. Create a function that accepts marks and prints whether the student passed or failed.

### Code

```
def result(marks):
    if marks >= 40:
        print("Pass")
    else:
        print("Fail")

result(55)
```

### Output

```
Pass
```

---

## Q9. Create a function that accepts two numbers and returns their multiplication.

### Code

```
def multiply(a, b):
    return a * b

print(multiply(5, 4))
```

### Output

```
20
```

---

## Q10. Create a function that accepts a number and returns its square.

### Code

```
def square(num):
    return num * num

print(square(6))
```

### Output

```
36
```

---

## Q11. Create a function that accepts a number and returns whether it is Even or Odd.

### Code

```
def check_even_odd(num):
    if num % 2 == 0:
        return "Even"
    else:
        return "Odd"

print(check_even_odd(7))
```

### Output

```
Odd
```

---

## Q12. Create a function that accepts two numbers and returns the larger number.

### Code

```
def larger(a, b):
    if a > b:
        return a
    else:
        return b

print(larger(25, 18))
```

### Output

```
25
```

---

## Q13. Create a function that accepts three numbers and returns the largest among them.

### Code

```
def largest(a, b, c):
    return max(a, b, c)

print(largest(10, 25, 18))
```

### Output

```
25
```

---

## Q14. Create a function that accepts temperature in Celsius and returns temperature in Fahrenheit.

### Code

```
def celsius_to_fahrenheit(c):
    return (c * 9/5) + 32

print(celsius_to_fahrenheit(30))
```

### Output

```
86.0
```

---

## Q15. Create a function that returns your college name.

### Code

```
def college_name():
    return "ABC College"

print(college_name())
```

### Output

```
ABC College
```

---

## Q16. Create a function that returns the current year.

### Code

```
def current_year():
    return 2025

print(current_year())
```

### Output

```
2025
```

---

## Q17. Create a function that returns a predefined salary value and display it.

### Code

```
def salary():
    return 50000

print("Salary =", salary())
```

### Output

```
Salary = 50000
```

---

## Q18. Create a function that returns a welcome message and store it in a variable before printing.

### Code

```
def message():
    return "Welcome to Python"

msg = message()
print(msg)
```

### Output

```
Welcome to Python
```

---

## Q19. Create a function that accepts a student's name and age as arguments and displays them.

### Code

```
def student_info(name, age):
    print("Name:", name)
    print("Age:", age)

student_info("Rahul", 20)
```

### Output

```
Name: Rahul
Age: 20
```

---

## Q20. Create a function that accepts product name and price and displays the details.

### Code

```
def product_info(name, price):
    print("Product:", name)
    print("Price:", price)

product_info("Laptop", 50000)
```

### Output

```
Product: Laptop
Price: 50000
```

---

## Q21. Create a function that accepts length and width and returns the area of a rectangle.

### Code

```
def area(length, width):
    return length * width

print(area(10, 5))
```

### Output

```
50
```

---

## Q22. Create a function that accepts principal amount, rate, and time and returns simple interest.

### Code

```
def simple_interest(p, r, t):
    return (p * r * t) / 100

print(simple_interest(10000, 5, 2))
```

### Output

```
1000.0
```

---

## Q23. Create a function that accepts first name and last name using positional arguments and displays the full name.

### Code

```
def full_name(first, last):
    print(first, last)

full_name("Rahul", "Sharma")
```

### Output

```
Rahul Sharma
```

---

## Q24. Create a function that accepts two numbers using positional arguments and returns their difference.

### Code

```
def difference(a, b):
    return a - b

print(difference(20, 8))
```

### Output

```
12
```

---

## Q25. Create a function that accepts employee name and designation and displays both details.

### Code

```
def employee(name, designation):
    print("Name:", name)
    print("Designation:", designation)

employee("Amit", "Manager")
```

### Output

```
Name: Amit
Designation: Manager
```

---

## Q26. Create a function to display student details using keyword arguments.

### Code

```
def student(name, age):
    print("Name:", name)
    print("Age:", age)

student(name="Rahul", age=20)
```

### Output

```
Name: Rahul
Age: 20
```

---

## Q27. Create a function to display employee information using keyword arguments.

### Code

```
def employee(name, salary):
    print("Name:", name)
    print("Salary:", salary)

employee(name="Amit", salary=50000)
```

### Output

```
Name: Amit
Salary: 50000
```

---

## Q28. Create a function to display book information using keyword arguments.

### Code

```
def book(title, author, price):
    print("Title:", title)
    print("Author:", author)
    print("Price:", price)

book(title="Python", author="ABC", price=450)
```

### Output

```
Title: Python
Author: ABC
Price: 450
```

---

## Q29. Create a function greet() with default value "Student".

### Code

```
def greet(name="Student"):
    print("Hello", name)

greet()
```

### Output

```
Hello Student
```

---

## Q30. Create a function to calculate bonus percentage with default bonus value of 10%.

### Code

```
def bonus(salary, percent=10):
    return salary * percent / 100

print(bonus(50000))
```

### Output

```
5000.0
```

---

## Q31. Create a function to display a course name with default value "Python".

### Code

```
def course(name="Python"):
    print(name)

course()
```

### Output

```
Python
```

---

## Q32. Create a function to calculate simple interest where the rate defaults to 5%.

### Code

```
def simple_interest(p, t, r=5):
    return (p * r * t) / 100

print(simple_interest(10000, 2))
```

### Output

```
1000.0
```

---

## Q33. Create a function that accepts any number of integers and returns their sum.

### Code

```
def total(*numbers):
    return sum(numbers)

print(total(10, 20, 30, 40))
```

### Output

```
100
```

---

## Q34. Create a function that accepts any number of marks and returns the average marks.

### Code

```
def average(*marks):
    return sum(marks) / len(marks)

print(average(70, 80, 90))
```

### Output

```
80.0
```

---

## Q35. Create a function that accepts multiple product prices and returns the highest price.

### Code

```
def highest(*prices):
    return max(prices)

print(highest(100, 250, 500, 350))
```

### Output

```
500
```

---

## Q36. Create a function that accepts any number of integers and returns the count of numbers entered.

### Code

```
def count_numbers(*nums):
    return len(nums)

print(count_numbers(1, 2, 3, 4, 5))
```

### Output

```
5
```

---

## Q37. Create a function that accepts student details using **kwargs.

### Code

```
def student_details(**data):
    for key, value in data.items():
        print(key, ":", value)

student_details(name="Rahul", age=20, branch="Computer")
```

### Output

```
name : Rahul
age : 20
branch : Computer
```

---

## Q38. Create a function that accepts employee information using **kwargs.

### Code

```
def employee_details(**data):
    for key, value in data.items():
        print(key, ":", value)

employee_details(name="Amit", salary=50000)
```

### Output

```
name : Amit
salary : 50000
```

---

## Q39. Create a function that accepts customer information using **kwargs.

### Code

```
def customer_details(**data):
    for key, value in data.items():
        print(key, ":", value)

customer_details(name="Raj", city="Pune")
```

### Output

```
name : Raj
city : Pune
```

---

## Q40. Create a function that returns the square and cube of a given number.

### Code

```
def square_cube(n):
    return n**2, n**3

s, c = square_cube(4)

print("Square =", s)
print("Cube =", c)
```

### Output

```
Square = 16
Cube = 64
```

---

## Q41. Create a function that accepts marks and returns Grade A, B, C, or D.

### Code

```
def grade(marks):
    if marks >= 90:
        return "A"
    elif marks >= 80:
        return "B"
    elif marks >= 70:
        return "C"
    else:
        return "D"

print(grade(85))
```

### Output

```
B
```

---

## Q42. Create a function that accepts a salary and returns the calculated annual salary.

### Code

```
def annual_salary(monthly):
    return monthly * 12

print(annual_salary(50000))
```

### Output

```
600000
```

---

## Q43. Create a function that accepts two numbers and returns Sum, Difference, and Product.

### Code

```
def operations(a, b):
    return a + b, a - b, a * b

s, d, p = operations(10, 5)

print("Sum =", s)
print("Difference =", d)
print("Product =", p)
```

### Output

```
Sum = 15
Difference = 5
Product = 50
```

---

## Q44. Create a function that accepts a number and returns Square, Cube, and Square Root.

### Code

```
import math

def values(n):
    return n**2, n**3, math.sqrt(n)

s, c, r = values(9)

print("Square =", s)
print("Cube =", c)
print("Square Root =", r)
```

### Output

```
Square = 81
Cube = 729
Square Root = 3.0
```

---

## Q45. Create a function that accepts marks of three subjects and returns Total Marks and Average Marks.

### Code

```
def result(m1, m2, m3):
    total = m1 + m2 + m3
    average = total / 3
    return total, average

t, a = result(80, 75, 90)

print("Total =", t)
print("Average =", a)
```

### Output

```
Total = 245
Average = 81.67
```

---

## Q46. Create a lambda function to calculate the square of a number.

### Code

```
square = lambda x: x * x

print(square(6))
```

### Output

```
36
```

---

## Q47. Create a lambda function to add two numbers.

### Code

```
add = lambda a, b: a + b

print(add(10, 20))
```

### Output

```
30
```

---

## Q48. Create a lambda function to find the larger of two numbers.

### Code

```
larger = lambda a, b: a if a > b else b

print(larger(25, 18))
```

### Output

```
25
```

---

## Q49. Create a lambda function that checks whether a number is Even or Odd.

### Code

```
check = lambda n: "Even" if n % 2 == 0 else "Odd"

print(check(7))
```

### Output

```
Odd
```

---

## Q50. Create a lambda function that converts Celsius temperature to Fahrenheit.

### Code

```
fahrenheit = lambda c: (c * 9/5) + 32

print(fahrenheit(30))
```

### Output

```
86.0
```

---

# Q51. Accept a list of numbers and display Length, Sum, Maximum, and Minimum

## Code

```
numbers = list(map(int, input("Enter numbers separated by space: ").split()))

print("Length:", len(numbers))
print("Sum:", sum(numbers))
print("Maximum:", max(numbers))
print("Minimum:", min(numbers))
```

## Output

```
Enter numbers separated by space: 10 20 30 40 50
Length: 5
Sum: 150
Maximum: 50
Minimum: 10
```

---

# Q52. Accept a list of marks and display the highest mark using a built-in function

## Code

```
marks = list(map(int, input("Enter marks: ").split()))

print("Highest Mark:", max(marks))
```

## Output

```
Enter marks: 78 89 95 67 88
Highest Mark: 95
```

---

# Q53. Accept different types of values and display their data types using type()

## Code

```
a = 10
b = 10.5
c = "Python"
d = True

print(type(a))
print(type(b))
print(type(c))
print(type(d))
```

## Output

```
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
```

---

# Q54. Accept five numbers and display the maximum and minimum values

## Code

```
numbers = []

for i in range(5):
    numbers.append(int(input("Enter number: ")))

print("Maximum:", max(numbers))
print("Minimum:", min(numbers))
```

## Output

```
Enter number: 25
Enter number: 12
Enter number: 89
Enter number: 45
Enter number: 30
Maximum: 89
Minimum: 12
```

---

# Q55. Create a program demonstrating a local variable inside a function

## Code

```
def show():
    x = 100
    print("Local Variable:", x)

show()
```

## Output

```
Local Variable: 100
```

---

# Q56. Create a program demonstrating a global variable accessed inside a function

## Code

```
x = 100

def show():
    print("Global Variable:", x)

show()
```

## Output

```
Global Variable: 100
```

---

# Q57. Create a program that uses both local and global variables with the same name

## Code

```
x = 50

def show():
    x = 100
    print("Local Variable:", x)

show()
print("Global Variable:", x)
```

## Output

```
Local Variable: 100
Global Variable: 50
```

---

# Q58. Create a program where a function modifies and displays a global variable

## Code

```
count = 10

def update():
    global count
    count += 5
    print("Updated Value:", count)

update()
```

## Output

```
Updated Value: 15
```

---

# Q59. Create a nested function where the outer function displays a message and calls the inner function

## Code

```
def outer():
    print("This is Outer Function")

    def inner():
        print("This is Inner Function")

    inner()

outer()
```

## Output

```
This is Outer Function
This is Inner Function
```

---

# Q60. Create a nested function to calculate and display the square of a number

## Code

```
def outer(num):

    def square():
        return num * num

    print("Square:", square())

outer(5)
```

## Output

```
Square: 25
```

---

# Q61. Create a nested function for employee salary processing

## Code

```
def salary_process(basic):

    def bonus():
        return basic * 0.10

    total_salary = basic + bonus()

    print("Total Salary:", total_salary)

salary_process(20000)
```

## Output

```
Total Salary: 22000.0
```

---

# Q62. Create a nested function for student result processing

## Code

```
def result(marks):

    def grade():
        if marks >= 75:
            return "A"
        elif marks >= 50:
            return "B"
        else:
            return "C"

    print("Marks:", marks)
    print("Grade:", grade())

result(82)
```

## Output

```
Marks: 82
Grade: A
```

# Q63. Create a Student Result Management System using Functions

## Code

```
def input_marks():
    marks = []
    for i in range(5):
        marks.append(int(input(f"Enter marks for subject {i+1}: ")))
    return marks

def calculate_total(marks):
    return sum(marks)

def calculate_average(total):
    return total / 5

def assign_grade(avg):
    if avg >= 90:
        return "A"
    elif avg >= 75:
        return "B"
    elif avg >= 50:
        return "C"
    else:
        return "Fail"

marks = input_marks()
total = calculate_total(marks)
average = calculate_average(total)
grade = assign_grade(average)

print("Total:", total)
print("Average:", average)
print("Grade:", grade)
```

## Output

```
Enter marks for subject 1: 80
Enter marks for subject 2: 85
Enter marks for subject 3: 90
Enter marks for subject 4: 75
Enter marks for subject 5: 70
Total: 400
Average: 80.0
Grade: B
```

---

# Q64. Create a Bank Account Utility Program using Functions

## Code

```
balance = 1000

def deposit(amount):
    global balance
    balance += amount

def withdraw(amount):
    global balance
    if amount <= balance:
        balance -= amount
    else:
        print("Insufficient Balance")

def check_balance():
    return balance

deposit(500)
withdraw(300)

print("Current Balance:", check_balance())
```

## Output

```
Current Balance: 1200
```

---

# Q65. Create a Library Fine Calculator

## Code

```
def calculate_fine(days):
    return days * 5

delayed_days = int(input("Enter delayed days: "))
fine = calculate_fine(delayed_days)

print("Fine Amount:", fine)
```

## Output

```
Enter delayed days: 4
Fine Amount: 20
```

---

# Q66. Create a function that returns the nth Fibonacci number

## Code

```
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

n = int(input("Enter n: "))
print("Fibonacci Number:", fibonacci(n))
```

## Output

```
Enter n: 7
Fibonacci Number: 13
```

---

# Q67. Create a function that checks whether a number is a power of 2

## Code

```
def is_power_of_two(n):
    if n <= 0:
        return False
    return (n & (n - 1)) == 0

num = int(input("Enter a number: "))

if is_power_of_two(num):
    print("Power of 2")
else:
    print("Not a Power of 2")
```

## Output

```
Enter a number: 16
Power of 2
```

---

# Q68. Create a function that calculates the number of ways to reach the top of a staircase

## Code

```
def count_ways(n):
    if n <= 1:
        return 1
    return count_ways(n - 1) + count_ways(n - 2)

steps = int(input("Enter number of steps: "))
print("Ways:", count_ways(steps))
```

## Output

```
Enter number of steps: 5
Ways: 8
```

---

# Q69. Create a function that accepts two numbers and returns the count of odd numbers between them

## Code

```
def count_odds(start, end):
    count = 0

    for i in range(start, end + 1):
        if i % 2 != 0:
            count += 1

    return count

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Odd Numbers Count:", count_odds(a, b))
```

## Output

```
Enter first number: 1
Enter second number: 10
Odd Numbers Count: 5
```

---

# Q70. Create a function that accepts account balances of multiple customers and returns the maximum wealth

## Code

```
def maximum_wealth(accounts):
    wealth = []

    for customer in accounts:
        wealth.append(sum(customer))

    return max(wealth)

accounts = [
    [1000, 2000, 3000],
    [5000, 1000, 500],
    [2000, 2000, 2000]
]

print("Maximum Wealth:", maximum_wealth(accounts))
```

## Output

```
Maximum Wealth: 6500
```
