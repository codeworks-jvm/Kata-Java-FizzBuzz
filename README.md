# Kata-Java-FizzBuzz
This kata is inspired by the common FizzBuzz exercise.

## Instructions
You have to implement a method with TDD.
Each step will add a new rule, for each step you have to create all tests for the new rule then modify the method to pass the tests.

The function takes in parameter one integer and return a string.

# Rules & examples
* Step 1 : Identity
  - The method may return the integer in parameter as a string. 
* Step 2 : Fizz
  - If the input number is divisible by 3 return "Fizz"
* Step 3 : Buzz
  - If the input number is divisible by 5 return "Buzz"
* Step 4 : FizzBuzz
  - If the input number is divisible by 3 and 5 return "FizzBuzz"
  
Examples :
  - fizzBuzz(1) must return "1"
  - fizzBuzz(6) must return "Fizz"
  
## Code
In the `src/main/java` folder, you will find the class `App` with the function ready to be implemented.

## Test it
You can use `mvn test` to test your code. If all tests pass, you can go to the next rule !

But first install the dependencies with `mvn clean install -DskipTests`. Thanks.

## Optimisation & clean code
When you add a rule try to keep you code clean and easy to read. You have to clean your code each time you had a new rule.