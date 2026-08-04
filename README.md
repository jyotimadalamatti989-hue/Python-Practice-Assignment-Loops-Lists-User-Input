# Assignment 1
# Instructions Complete all questions using Python. 
Write clean and readable code. 
Add comments wherever necessary. 
Try solving the questions on your own before looking at the hints. 
Submit a single Python file containing all solutions.

# Question 1: Personal Introduction Repeater
. # Defining personal information variables
name = "Jyoti"
age = 18
college_ name = "  Government Women's collage Hubli "

. # Loop to repeat the details 10 times
for i in range(10):
    print(f" Name: {name}, Age: {age}, College: {college_ name}")

# Question 2: Welcome to Glow logics
. # Creating a list containing 5 student names
students = ["Sai", "Ananya", "Rahul", "Priyank", "Virama"]

. # Looping through the list to print a welcome message
for student in students:
    print(f"{student}: Welcome to the Glow logics Internship Program.")

# Question 3: Digital Greeting System
. # Creating a list of 10 student names
students_ list = ["Sai", "Ananya", "Rahul", "Priyank", "Virama", "Kiran", "Sneha", "Amit", "Pooja", "Arjun"]

. # Generating a personalized greeting for each student
for name in students_ list:
    print(f "Dear {name},")
    print("We are excited to have you as part of the internship.")
    print("Regards,\n Glow logics")
    print("-" * 30)  # Separator line between greetings

# Question 4: Even Number Challenge (with Bonus)
. # Printing all even numbers from 1 to 100
print("Even numbers from 1 to 100:")
for num in range(1, 101):
    if num % 2 == 0:
        print(num, end=" ")
print("\n" + "="*40)

. # Bonus: Printing odd numbers from 1 to 100
print("Odd numbers from 1 to 100:")
for num in range(1, 101):
    if num % 2 != 0:
        print(num, end=" ")
print()

# Question 5: Attendance Register
. # Creating a list of 6 students
attendance_ list = ["Abhishek", "Bhavana", "Chetan", "Divvy", "Eshwar", "Farhan"]

. # Displaying attendance
print("Attendance Sheet:")
for student in attendance_ list:
    print(f"{student} - Present")

# Question 6: Secure Login System
correct_ password = "Glow123"

. # Keep asking until the user enters the correct password
while True:
    user_ input = input("Enter the password: ")
    if user_ input == correct_ password:
        print("Access Granted")
        break  # Exit the loop when password matches
    else:
        print("Incorrect password. Try again.")

# Question 7: Multiplication Table Generator
. # Prompting user input and converting it to an integer
number = int(input("Enter a number to generate its multiplication table: "))

. # Using a loop from 1 to 10 to display the table
for i in range(1, 11):
    result = number * i
    print(f"{number} x {i} = {result}")

# Question 8: Amazon Order Confirmation
. # List of customer names
customers = ["Sai", "Kavya", "Manish", "Deepa"]

. # Automatically generating confirmation messages
for customer in customers:
    print(f "Hello {customer},")
    print("Your order has been successfully placed.")
    print("Thank you for shopping with us.")
    print("-" * 35)

# Question 9: Countdown Timer
. # Using range with a negative step value (-1) to count down
for count in range(10, 0, -1):
    print(count)

print("Launch Successful!")

# Question 10: Student Information Collector
. # Collecting user inputs
student_ name = input("Enter your name: ")
student_ age = input("Enter your age: ")
student_ college = input("Enter your college name: ")

. # Displaying details using f-strings for clean formatting
print("\n Student Details")
print(f "Name: {student_ name}")
print(f "Age: {student_ age}")
print(f "College: {student_ college}")



