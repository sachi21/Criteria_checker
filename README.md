# Criteria_checker
This code is about how to check total criteria is pass or not. Suppose i have total 5 criteria to check .
Solution Details:
1. Variable Creation
Create all the necessary variables and Flag Variables for the program

2. List Creation
Create lists for Capital Letter, Symbols and Numbers

3. Character Count
Setup a for loop to count the number of characters present in the password string.
Solution Details:


4. Loop and Condition Creation

Create a loop to check if the first letter is capital or not.
If the letter is capital then move on to the next conditions.
Check if the password contains numeric characters or not. If yes , then set the number flag to 1.
Check if the password contains any blank spaces or not. If yes, then set the blank flag to 1.
Check if the password contains any symbols or not. If yes then set the symbol flag to 1.
Increment the count variable as the characters are getting checked. 
Validate all the flags and also the length of the variable to give out the final result if the password is valid or not. 
Print the result:
Print the final result with the issues if the password is invalid. If not then you can print “Password is valid”.

Password Criteria:
Minimum Length: The password should have a minimum specified length. 
Combination of Character Types: The password should include a mix of uppercase letters, lowercase letters, digits, and symbols.
Blank Space : The password should not contain any blank space.
Implementation Steps
To implement the Password Validator Program, follow these steps:

Set up the programming environment and create a new Python file.
Define all the necessary variables for flags like symbol, isNum , isblank and others like total_character etc.
Create a list for Capital Character , Number and Symbol to check against the password.
Set up a loop to count the number of characters in the password string.
Set up a loop again to check the first character of the password should be capital letters.
Set up a condition for checking if the password contains a number or not.
Create a condition for checking if the password contains blank space or not.
Create a condition for checking whether the password contains special characters.
Setup nested condition to check all the flags
Print out whether the password is valid or not. If not then specify the reason why it is not valid.
