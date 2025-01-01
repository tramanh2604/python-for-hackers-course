#Task 1: Take a first name as a variable and last name, then print to the console "Your name is ..."

```
# Nhập chuỗi
fname = input("What is your first name? ")
lname = input("What is your last name? ")

# In chuỗi
print(f"Your name is {fname} {lname}")
# print("Your name is " + fname + " " + lname)
```

#Task 2: Create a greeting for your program

#Task 3: Ask for the user for the name of a pet

#Task 4: Ask for the name of the city you were born in

#Task 5: Compine the pet name with the word cyber as a new twitter handle and then add the city they are from

```
print("Thanks for using my program")

pname = input("What is the name of a pet? ")
cname = input("What is the name of the city your were born in? ")

print(f"Your new twitter handle and bio @cyber{pname} from {cname}")

```

#Task 6: Tìm số lớn hơn
```
fnum = input("What is the first number? ")
snum = input("What is the second number? ")

if fnum > snum :
    print("The first number is bigger")
elif fnum < snum:
    print("The second number is larger!")
else:
    print("The numbers are the same")
```

#Task 7: Write a program that promts the user to enter their score (out of 100) and displays their corresponding grade based on the following criteria

Grade A: 90 and above
Grade B: 80-89
Grade C: 70-79
Grade D: 60-69
Grade F: below 60

```
score = input("What is your score? ")
score = int(score)

if score >= 90:
    print("Your grade is an A")
elif score >= 88:
    print("Your grade is a B")
elif score >= 70:
    print("Your grade is a C")
else:
    print("You should study hard!")
``` 

#Task 8: find all the numbers divisible by 3 from 1-100
```
for num in range(1,100):
    if num % 3 == 0:
        print(num)
```

#Task 9: Fizzbuzz
If a number is divisible by 3, print fizz
If a number is divisible by 5, print buzz
If a number is divisible by both, print fizzbuzz

```
for num in range (1,100):
    if num % 3 == 0 and num % 5 == 0:
        print("fizzbuzz")
    elif num % 3 == 0:
        print("fizz")
    elif num % 5 == 0:
        print("buzz")
    else:
        print(num)
```

#Task 9: biến trò fizzbuzz thành hàm
```
import time
choice = int(input("What number would you like to choose? "))
def function(choice):
    for num in range (1,choice):
        if num % 3 == 0 and num % 5 == 0:
            print("fizzbuzz")
        elif num % 3 == 0:
            print("fizz")
        elif num % 5 == 0:
            print("buzz")
        else:
            print(num)

print("running the program")
time.sleep(5) #đợi 5s trước khi chạy hàm function
function(choice)
```

#Task 10: Create a program that can take in input of the users name
Save the name in a variable
pass the variable through a function and print "hello ..."
```
name = input("What's your name? ")

def greeting(name):
    print(f"Hello {name}")

greeting(name)
```

#Task 10: Create a greeting
- Create your word list
- Randomly choose a word from the list you have created
- Ask the user to guess a letter
- Bonus make the program take the input from the user and make it lowercase
- Check if the letter is in the word
```
import random
print("Welcome to Hangman!")
words = ["hacker", "bounty", "random"]

#lựa từ random trong mảng words and save into a variable
secret_word = random.choice(words)

#nhận input và đổi thành lowercase
guess = input("Guess a letter ").lower()

for letter in secret_word:
    if letter == guess:
        print("Right")
    else:
        print("Wrong")
```

#Task 11: cải tiến trò hangman
```

```