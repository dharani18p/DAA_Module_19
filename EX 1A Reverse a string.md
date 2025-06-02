# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Input the string s.
2. Define a recursive function reverse(s)
i) If len(s) == 1, return s.
ii) Otherwise, return s[-1] + reverse(s[:-1]).
3. Call reverse(s) to reverse the string.
4.  The function recursively reverses the string by appending characters from the end.
5. Print the reversed string.
## Program:
```
/*
Program to implement Reverse a String
Developed by: DHARANI P
Register Number: 212222220011
*/

def reverse(s):
    if len(s)==1:
        return s[0]
    else:
        
        return s[-1]+reverse(s[:-1])
s=input()
print(reverse(s))
```

## Output:
![447098542-54818f55-d4f5-4a09-b1cd-aa03caadd38f](https://github.com/user-attachments/assets/9e062840-71d3-4e31-83e4-a917e9096e5f)

## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
