# palindrome_recursion-checkpoint

In this palindrome algorithm, a function is used to check if a word is palindromic.
In the function, a while loop is initialized if the first letter and the last letter of the word are the same character.
If both characters are same, the loop is executed and the word in reversed order is stored in a new variable "newWord".

The first IF CONDITION that follows checked for inequality in "newWord" and "word" variables and returns the string "not a palindrome"
ELSE IF the two variables are same words in length and character, it writes "word is a palindrome". 
In both cases, the newWord is returned.

A second IF CONDITION within the fuction, (a stop condition) if the word is an empty string or contains just one character in which case it writes "not a palindrome" and then returns the word.
