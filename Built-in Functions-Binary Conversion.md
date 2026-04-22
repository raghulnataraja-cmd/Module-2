# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
    num = int(input("ENTER A NUMBER :"))
    temp = num
    rev = 0
    while temp > 0:
      rev = (10 * rev) + temp % 10
      temp = temp // 10
    if rev == num :
      print(f"The given number {num} is Palindrome")
    else:
      print(f"The given number {num} is not Palindrome")

## Output

## Result
