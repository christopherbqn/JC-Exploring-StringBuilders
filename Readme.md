# Lab: Exploring Java `StringBuilders` 

Submitted by: Bayquen, Christopher Gilbert A. | August 7, 2025

This repository holds our lab activity exploring the mutable nature of the `StrinBuilder` class.

**Output Predictions**

- Exercise 1: printing `sb` would output a "concatenated" string `Hello, Cadets!`. Adding the additional statements/words would also result to `Hello, Cadets! Welcome to 2025.`
- Exercise 2: inserting the string `really` in index 8 would result to `"Java is really great!"`
- Exercise 3: the statement `sb.delete(8,16)` will delete the characters from index 8 to index 15 resulting to `sb = This is sentence.`. Similarly, `sb.deleteCharAt(4)` will delete the character at index 4 which will result to `sb = thisis sentence.`
- Exercise 4: the statement `sb.replace(24,30,'Java')` will start to replace the characters at index 24 to 29, this will result to `sb = I like programming in PyJava`.
- Exercise 5: the output would `sb = Ready, Set, rt...`.
- Exercise 6: the program will output `sub = 'fox'`, `indexOfFox = 16`, and `indexOfCat = -1`.
- Exercise 7: since the `finalStatus` is an immutable String, it will only contain `Status: Pending`, and `sb.append("- Approved")` will result to `sb = Status: Pending - Approved`


**Actual Output**

![Sample Input/Output Screenshot](/images/output.png)
