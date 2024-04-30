# Palindrome check
## Description
A palindrome is a number that reads the same forward and backward.
Given an integer `x`, this function determines if `x` is a palindrome.It returns true if `x` is a palindrome and false otherwise.
## Examples
### Example 1:
Input: x = 121
Output: true
Explanation: 121 reads as 121 from left to right and from right to left.

### Example 2:
Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore, it is not a palindrome.
## Solution Overview
The function `isPalindrome` takes an integer as input and returns a boolean value indicating whether the integer is a palindrome.
## Approach
To determine if an integer is a palindrome:
* We first check if the input integer is negative. Negative numbers cannot be palindromes, so we return false immediately in that case.
* We then convert the integer `x` to a string using `toString()`.
* We create a `reversedStr` variable by splitting the string into an array of characters, reversing the array, and joining the characters back into a string.
* Finally, we compare the original string `str` with the reversed string `reversedStr` and return true if they are equal, indicating that the integer is a palindrome.

## Instructions
* Fork this repository from Github
* Clone this repository to your local machine
* Open files in Visual studio code to view the function implementation
## Contributions
Pull requests are welcomed.
## Contacts
For any feedbacks contact me through my email bilhaleposo@gmail.com