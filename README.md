This repository contains beginner-friendly Python programs I completed as part of my internship. All tasks are written using user-defined functions, with a focus on logic building, learning core concepts, and experimenting with basic encryption techniques.

This report explains my approach, the challenges I faced, the solutions I implemented, and what I learned from each task.

---
✅ Task 1: Sum of Two Numbers
🔹 Approach:
Start with a function that takes two numbers and adds them.
🔸 Challenge:
Understanding how user input is passed to a function and how to return results.
🔧 Solution:
I created a function calculate_sum(a, b) that adds two integers. The program takes input from the user and displays the result.
📘 What I learned:
How to define and call user-defined functions.
How to take user input and convert it to integers.


✅ Task 2: Check Odd or Even
🔹 Approach:
Use the modulo operator to check if a number is divisible by 2.
🔸 Challenge:
I had to make sure the function returned a string, not just a print statement.
🔧 Solution:
I wrote check_odd_even(number) which checks if number % 2 == 0 and returns "Even" or "Odd".
📘 What I learned:
How conditions work in Python.
The difference between returning and printing values.


✅ Task 3: Factorial of a Number
🔹 Approach:
Use a loop to multiply numbers from 1 to n.
🔸 Challenge:
I had to handle the case for 0 and 1 correctly, and also avoid negative inputs.
🔧 Solution:
I created a function factorial_loop(n) using a for loop and initialized fact = 1. Checked for invalid inputs outside the function.
📘 What I learned:
How loops work.
How to handle edge cases and validate inputs.


✅ Task 4: Fibonacci Sequence Generator
🔹 Approach:
Start with 0 and 1, and keep generating the next number by adding the previous two.
🔸 Challenge:
Making sure the output list works for small values like 1 or 2, and avoiding index errors.
🔧 Solution:
Created a function generate_fibonacci(n) using a loop. Returned a list with the sequence.
📘 What I learned:
How to use lists and loops together.
Fibonacci logic and edge case handling.


✅ Task 5: Reverse a String
🔹 Approach:
Use slicing in Python to reverse the string.
🔸 Challenge:
I needed to make sure the function worked even if the user typed spaces or special characters.
🔧 Solution:
Used slicing [::-1] inside reverse_string(s) to reverse the string and return it.
📘 What I learned:
String slicing in Python.
How to create reusable functions for string manipulation.


✅ Task 6: Palindrome Checker
🔹 Approach:
Compare the original string with its reversed version.
🔸 Challenge:
Making the comparison case-insensitive and ignoring spaces if needed.
🔧 Solution:
Used s.lower().replace(" ", "") to clean the string. Reversed it using slicing and compared.
📘 What I learned:
Palindrome logic.
Data cleaning before logic processing.


✅ Task 7: Leap Year Checker
🔹 Approach:
Follow the leap year rules:
Divisible by 4
Not divisible by 100 unless also divisible by 400
🔸 Challenge:
Writing nested conditions correctly so all cases work.
🔧 Solution:
Wrote a function is_leap_year(year) using if-else blocks to handle all 3 rules.
📘 What I learned:
Writing clean and readable conditionals.
The actual leap year rule logic.


✅ Task 8: Armstrong Number Checker
🔹 Approach:
Get each digit, raise it to the power of the number of digits, and sum them.
🔸 Challenge:
Splitting the number into digits and using the ** operator correctly.
🔧 Solution:
Wrote is_armstrong(n) that converts the number to a string, loops through digits, and applies the rule.
📘 What I learned:
Power operator, loops, and type conversion.
Armstrong number logic.


✅ Task 9: Caesar Cipher Encryption/Decryption
🔹 Approach:
Shift each letter by a fixed key value. For example, with key=3, A becomes D, B becomes E, etc.
🔸 Challenge:
Handling both uppercase and lowercase letters while keeping punctuation unchanged. Also needed to "wrap around" after Z.
🔧 Solution:
Wrote encrypt_caesar(message, key) and decrypt_caesar(message, key) using ASCII values and modular arithmetic to wrap around the alphabet.
📘 What I learned:
ASCII manipulation with ord() and chr()
Basics of encryption and substitution ciphers
Writing clean user-defined functions for both encryption and decryption


🏁 Final Reflection
Working on these tasks helped me:
Build confidence in solving problems using Python
Write clean, readable code using user-defined functions
Think through logic step-by-step
Understand how to document code like a developer
This README is a reflection of what I’ve learned and achieved during this internship as a first-year student. 💻✨
