# 0x00. Fix my code
- 0-fizzbuzz.py: The implementation of FizzBuzz has a logical error in the code. In the if statements, it was checking for multiples of 3 before checking for multiples of 3 and 5. Therefore, the condition to print "FizzBuzz" will never be reached because the condition to print "Fizz" is evaluated first. To fix this error, I checked for multiples of 3 and 5 before checking for multiples of 3 or 5 separately.

- 1-print_square.js: The implementation looks mostly correct, but there is a small issue with the parseInt function call. When converting a string to an integer using parseInt, you need to provide a second argument which is the radix, or base, of the number you're trying to convert. In this case, you want to convert the string to a decimal (base 10) number, so you should pass 10 as the second argument to parseInt.

- 2-sort.rb: The issue with this code is that the insertion of the new integer element into the result array is not done correctly. Specifically, the insertion index is off by one, which causes the program to sort the integers in descending order, rather than ascending order. To fix this issue, I changed the insertion index from i - 1 to i

- 3-user.py: There is a typo in the password setter method of the User class. The variable should be __password instead of _password. I Replaced self._password with self.__password in the password setter method to fix the issue.

