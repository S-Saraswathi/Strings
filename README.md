# Strings
## Aim
To understand the concept of strings in cpp
## Theory
A string is a sequence of characters used as an object of the class. The string class stores the characters as a sequence of bytes with the functionality of allowing access to the single-byte character. A string is different from an array of characters. Some key differences are:
| Strings | Array of characters |
|---------|---------------------|
| A string is a class that defines objects that be represented as a stream of characters | A character array is simply an array of characters that can be terminated by a null character |
| String class defines a number of functionalities that allow manifold operations on strings | Character arrays do not offer many inbuilt functions to manipulate strings |
## Algorithm
1. Start
2. Take the input of Name and Surname
3. Run a loop to find out the length of the string.
4. Print length.
5. Run Another loop using pointer to find out the length of the string.
6. Print Length.
7. Run another loop for get the initials of the name and surname.
8. Print the Initials.
## Explainantion
The ```cin.get(int value)``` takes in integer value number of characters including space and special characters.
The length can be found by running loop for every character of string until NULL (/0) shows up.
Initial of the name can be found by taking the first character of the array and Surname by finding the space between the namr and surname and the next character is the initial of the surname.
## Output Screenshot
![Screenshot of the output](image.png)
