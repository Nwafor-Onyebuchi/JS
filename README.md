### Task 1: Basic Number Comparison
**Write a JavaScript program that checks if a given number is positive, negative, or zero.**

**Steps**:
1. Initialize a variable `number` and assign it a value.
2. Write an `if` statement to check if `number` is greater than 0.
   - Print "The number is positive" if the condition is true.
3. Add an `else if` block to check if `number` is less than 0.
   - Print "The number is negative" if the condition is true.
4. Add an `else` block to handle when `number` is 0.
   - Print "The number is zero."

### Task 2: Age Verification
**Write a JavaScript program that checks if a person is eligible to vote based on their age.**

**Steps**:
1. Initialize a variable `age` and assign it a value.
2. Write an `if` statement to check if `age` is greater than or equal to 18.
   - Print "Eligible to vote" if the condition is true.
3. Add an `else` block.
   - Print "Not eligible to vote" if the condition is false.

### Task 3: Number Range Check
**Write a JavaScript program that checks if a number falls within a specific range.**

**Steps**:
1. Initialize a variable `number` and assign it a value.
2. Write an `if` statement to check if `number` is greater than or equal to 10 and less than or equal to 50.
   - Print "The number is within the range" if the condition is true.
3. Add an `else` block.
   - Print "The number is out of range."

### Task 4: Grade Assignment
**Write a JavaScript program that assigns a grade based on a score.**

**Steps**:
1. Initialize a variable `score` and assign it a value.
2. Write an `if` statement to check if `score` is greater than or equal to 90.
   - Print "Grade: A" if the condition is true.
3. Add an `else if` block to check if `score` is between 80 and 89.
   - Print "Grade: B" if the condition is true.
4. Add additional `else if` blocks for scores between 70-79, 60-69, and below 60.
   - Print "Grade: C," "Grade: D," or "Grade: F" as appropriate.

### Task 5: Password Validation
**Write a JavaScript program that validates an entered password.**

**Steps**:
1. Initialize a variable `inputPassword` and assign it a value.
2. Create a variable `correctPassword` and set it to a predefined string.
3. Write an `if` statement to check if `inputPassword` is equal to `correctPassword`.
   - Print "Access granted" if the condition is true.
4. Add an `else` block.
   - Print "Access denied."

### Task 6: Even or Odd Checker
**Write a JavaScript program that checks if a number is even or odd.**

**Steps**:
1. Initialize a variable `number` and assign it a value.
2. Write an `if` statement to check if `number % 2 === 0`.
   - Print "The number is even" if the condition is true.
3. Add an `else` block.
   - Print "The number is odd."

### Task 7: Simple Calculator
**Write a JavaScript program that performs basic arithmetic operations based on an operator.**

**Steps**:
1. Initialize two variables, `num1` and `num2`, and assign them values.
2. Initialize a variable `operator` and assign it a value (e.g., `+`, `-`, `*`, `/`).
3. Write `if` statements to check the value of `operator`.
   - If `operator` is `+`, print the sum of `num1` and `num2`.
   - If `operator` is `-`, print the difference.
   - If `operator` is `*`, print the product.
   - If `operator` is `/`, print the quotient.
4. Add an `else` block for unsupported operators.
   - Print "Invalid operator."

### Task 8: Weather Suggestion
**Write a JavaScript program that suggests clothing based on the temperature.**

**Steps**:
1. Initialize a variable `temperature` and assign it a value.
2. Write an `if` statement to check if `temperature` is below 10.
   - Print "Wear a heavy coat" if the condition is true.
3. Add an `else if` block to check if `temperature` is between 10 and 20.
   - Print "Wear a light jacket."
4. Add an `else` block.
   - Print "No jacket needed."

### Task 9: Time of Day Greeting
**Write a JavaScript program that prints a greeting based on the time of day.**

**Steps**:
1. Initialize a variable `hour` and assign it a value (0-23).
2. Write an `if` statement to check if `hour` is between 0 and 11.
   - Print "Good morning!" if the condition is true.
3. Add an `else if` block to check if `hour` is between 12 and 17.
   - Print "Good afternoon!"
4. Add an `else` block.
   - Print "Good evening!"

### Task 10: Login Attempts
**Write a JavaScript program that limits login attempts.**

**Steps**:
1. Initialize a variable `attempts` and set it to 0.
2. Write a loop that increments `attempts` each time a password is entered incorrectly.
3. Write an `if` statement inside the loop to check if `attempts` equals 3.
   - Print "Too many failed attempts" and break out of the loop.
4. Add an `else` block to prompt the user to try again.
