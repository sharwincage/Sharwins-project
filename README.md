# Sharwins-project
print("Hello world!")

a = "Ipek"
b = 11
c = 10.1
print(a)

x = 10
y = 12
z = x + y
z = y - x
print(z)

#replacing variables
a = 2
b = 3
c = a
a = b
b = c
print(a, b)

time = 45
payperhour = 10
income = time*payperhour
grosspay = income*105/100
print("John's gross pay is:", grosspay)

name = "Ipek"
message = "Hi " + name
print(message * 2)

drink = input("Coffee or tea? ")
print(drink, "is being prepared.")

num = int(input( "Enter a number: "))
print( num + 3)

name = input("Name: ")
surname = input("Surname: ")
number = input("School number: ")
print("Name: "+ name + "\nSurname: " + surname + "\nNumber: " + number)

inch = int(input("Write your length in inches:"))
feet = inch/12
print("This equals", feet, "feets")

min = int(input("Write total of minutes spent for excersises:"))
hour = int(min/60)
leftmin = min%60
print("You spent", hour, "hours and", leftmin, "minutes.")

num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
print( "Multiplication: ", num1 * num2)

#Input 3 numbers from the user and multiply each
num1 = int(input("First number: "))
num2 = int(input("Second number: "))
num3 = int(input("Third  number: "))
print(num1 * num2 * num3)

fuel = float(input("How much fuel does your vehicle use per kilometer when transferred to dollars? "))
distance = float(input("How many kilometers has your vehicle travelled? "))
print("Total price: " ,(fuel* distance))

d=997
h = int(input("Enter the height of your liquid: "))
P= d * h
print("Your liquid's pressure is ", P)

#Body Mass Index: : weight(kg) / height(m) * height
height = float(input("Please input your height in meters: "))
weight = float(input("Please input your weight in kilograms: "))
BMI = weight/(height* height)
print("Your body mass index:  ", BMI)

age = 13
if (age >= 14):
  print ("you can go to disco!")
else :
   print ("go home :(")

age = 13
if(age > 14) :
  print ("you can go to disco!")
elif(age == 14) :
  print ("you can go to disco!")
else :
  print ( "go home :(")

num = int(input("give me a number!!"))
if num%2 == 0 :
  print("that number is even!!")
else :
  print("that number is odd!!")

a = 5
b = 5
if(a!=5):
  print(a)
if(b==a):
  print("a is equal to b")
else:
  print("no")


num1 = int(input("Enter grade 1:"))
num2 = int(input("Enter grade 2:"))
num3 = int(input("Enter grade 3:"))
avg = (num1 + num2 + num3) / 3
if avg >= 70 :
  print(" you passed!!")
else :
  print("you didn't pass :(")

service = int(input("How many years have you worked for?"))
salary = float(input("What is your current salary?"))
if service > 5:
  print("Your net bonus is: ", salary * 5/100)
else:
  print("Your net bonus is:" , salary * 2/100)


age = int(input("What is your age?"))
if age < 0:
  print("Invalid input")
elif 0<=age<=9:
  print("Child")
elif 10<=age<=19:
  print("Adolescent")
elif 20<=age<=45:
  print("Adult")
elif 46<=age<=60:
  print("Middle Age")
else:
  print("Old")

operation = int(input("1. Add or 2. Subtract or 3. Multiply or 4. Divide. Please enter the number of your operation. "))
number1 = int(input("Please enter first number."))
number2 = int(input("Please enter second number."))
if operation == 1:
  print(number1, "+", number2,"=", number1 + number2)
elif operation == 2:
  print(number1, "-", number2, "=", number1 - number2)
elif operation == 3:
  print(number1, "*", number2, "=", number1 * number2)
elif operation == 4:
  print(number1, "/", number2, "=", number1 / number2)
else:
  print("Error")

cat = True
print("This person has a cat", cat)

has_enough_units = False
has_met_requirements = True
if has_enough_units and has_met_requirements== True:
  can_graduate= True
else:
  can_graduate= False
print("Can this person graduate? ", can_graduate)

is_weekday = True
is_holiday = False
if is_holiday == True or is_weekday == False:
  no_school = True
else :
  no_school = False
print("There is no school today ", no_school)

first_die = int(input("First die? "))
print(first_die)
second_die = int(input("Second die? "))
print(second_die)
if first_die == second_die:
  double_dice = True
else:
  double_dice = False
print("Rolled doubles? ", double_dice)

points = int(input("Points per game? "))
rebounds = int(input("Rebounds per game? "))
assists = int(input("Assists per game? "))
if points >= 25:
  all_star = True
elif points and rebounds and assists >= 10:
  all_star = True
else:
  all_star = False
print("Is all star?", all_star)

#BMI part 2
#BMI less than 18.5-------> Underweight
#BMI between 18.5 and 25  --> Healthy
#BMI between 25 and 30  ----> Overweight
#BMI over 30 ---------> Obese
height = float(input("Please input your height in meters: "))
weight = float(input("Please input your weight in kilograms: "))
BMI = weight/(height* height)
if BMI < 18.5:
  print("Underweight")
elif BMI < 25:
  print("Healthy")
elif BMI < 30:
  print("Overweight")
else:
  print("Obese")

a = int(input("First number: "))
b = int(input("Second number: "))
c = int(input("Third number: "))
if a > b and c:
  print("Greatest number is ", a)
elif b > a and c:
  print("Greatest number is ", b)
else:
  print("Greatest number is ", c)

#midterms1, midterms2 and final note
#Midterms are 30% of total grade each. Final is 40% of the total grade.
#Total grade >= 90 -----> AA Total grade  >= 85 -----> BA Total grade  >= 80 -----> BB Total grade  >= 75 -----> CB
#Total grade  >= 70 -----> CC Total grade  >= 65 -----> DC Total grade  >= 60 -----> DD Total grade  >= 55 -----> FD Total grade  < 55 -----> FF

midterm1 = float(input("First midterm grade: "))
midterm2 = float(input("Second midterm grade: "))
final = float(input("Final grade: "))
total_grade = midterm1 * 0.3 + midterm2 * 0.3 + final * 0.4
if total_grade>= 90:
  print("AA")
elif total_grade >= 85:
  print("BA")
elif total_grade >= 80:
  print("BB")
elif total_grade >= 75:
  print("CB")
elif total_grade >= 70:
  print("CC")
elif total_grade >= 65:
  print("DC")
elif total_grade >= 60:
  print("DD")
elif total_grade >= 55:
  print("FD")
else:
  print("FF")

for i in range(5):
  print(i, end= "")

for i in range(200,300,10):
  if(i>250 or i==230):
    print(i)

for i in range(2, 14, 2):
  if(i!=4 and i>8):
    print(i)

for i in range(2, 14, 3):
  print(i)

for i in range(14):
  print(i)

for a in range(100):
  print("Thank God it's Friday!")

name = input("Name: ")
for a in range (2,5):
  print(a)
  print(name)

number = int(input("Enter a number:"))
for i in range(0, number, 2):
    print(i)

number = int(input("Enter number: "))
total = 0
for a in range (number + 1):
  total = total + a
print(total)

for i in range(200, 1, -17):
  print(i)

for i in range(500, -36, -23):
  print(i)

for i in range(1, 11):
  for a in range(1, 11):
    print(i, "x", a , "=", i*a)

for i in range(-23, 137, 18):
  print(i)

a = -23

while a < 137:
  print(a)
  a += 18

#Input 2 numbers from the user, if the numbers are equal and first number is greater than 5 print yes
#If this condition is false but the numbers are greater than 3 print maybe
#If both conditions are false print all numbers between first and second number
print("The first number should be less than the second!")
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

if(num1==num2 and num1>5):
  print("Yes")
elif(num1>3 and num2>3):
  print("Maybe")
else:
  for i in range(num1, num2):
    print(i)







#If the total of a number's factors except itself is equal to itself, it's a "perfect number"
#For example, 6 is a perfect number (1 + 2 + 3 = 6)

num = int(input("Enter number"))
factors = 0
for i in range(1, num):
  if num % i == 0:
    factors = factors + i
if factors == num:
  print("This is a perfect number")
else:
  print("This is not a perfect number")

#If a number has 4 digits, ,if the total of each digits' 4th power (3rd power if it has 3 digits) is equal to the number itself, it's called an "Armstrong Number"
#1634 = 1^4 + 6^4 + 3^4 + 4^4

x = int(input("Enter number: "))
a = str(x)
digits = len(a)
total = 0

for i in a:
  total += int(i) ** int(digits)

if total == x:
  print("This is an Armstrong number")
else:
  print("This is not an Armstrong number")



not_zero = True
sum = 0
while not_zero:
  number = int(input("Enter a number: "))
  sum = sum + number
  if (number == 0):
    not_zero = False
print(sum)

for i in range(7, 103, 8):
  print(i)

x = 7
while x < 103:
  print(x)
  x += 8


a = 7
while a < 103:
  if a % 8 == 7:
    print(a)
  a += 1

#break the loop when q is pressed

total = 0
num = input()
while num != "q":
  num += int(num)
  num = input()
print(total)

#solution 2
total = 0
num = input()
while num:
  if num == "q":
    break
  else:
    total += int(num)
    num = input()
print(total)

for i in range(1, 101):
  if i % 3 != 0:
    continue
  else:
    print(i)""

a = float(input("First side length: "))
b = float(input("Second side length: "))
hypotenuse = (a * a + b * b) ** 0.5
print("Hypotenuse: " , hypotenuse)

#libraries
from math import sqrt
hypotenuse_2 = sqrt(a *a + b*b)
print("Hypotenuse: ", hypotenuse_2)

books = ["Momo", "Heartstopper"]
print(books)
print(books[0])
print(len(books))

for i in range(len(books)):
  print(books[i])

list1 = [27, True, 45.7, "İpek", 37, False, 49.2, "Deniz", 98239239, 9829.5]
for i in list1:
  print(i)

a = 0
while a <= 9:
  print(list1[a])
  a += 1

numbers = [42, 292, 34475, 12, 493]
total = 0
for i in numbers:
  total = total + i
average = total/ 5
print(average)

even_nums = []
for i in range(1, 101):
  if i % 2 == 0:
    even_nums.append(i)
print(even_nums)

grades = [97, 23, 86, 73]

total = 0
for a in grades:
  total += a
average = total/len(grades)
print(average)

liste = ["Python", "Java", "C", "C++", "JavaScript", "R", "HTML"]
# reverse order
print(liste[::-2])
print(liste[::-3])

student = { "name": "Ipek", "last_initial" : "Z", "school_no": 42, "grades": [100, 97, 98, 95]}
print(student["name"])
print(student["grades"])

dictionary = {"Apple": "a fruit", "Pencil": "a tool used for writing"}
print(dictionary["Pencil"])


for x in "apple":
  print(x)


tv = "Rise of Empires Ottoman "
print(tv[0], tv[5], tv[8], tv[15])
print(tv[:7], tv[16:])

text = "Are classes for sleeping?"

reverse = text[::-1]
print(reverse)
print(reverse[::2])
