## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  
To Write a Python program to check whether the given character is a vowel or not using if..else statement
## ALGORITHM  
1. Begin the program.  
2. Take a character input from the user
3. Convert the character to lowercase
4. Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
5. If it is a vowel, display "The given character is a vowel"
6. Otherwise, display "The given character is NOT a vowel"
4. Terminate the program.

## PROGRAM
```

char = input("Enter a character: ")
char_lower = char.lower()

if char_lower in ['a', 'e', 'i', 'o', 'u']:
    print("The given character is a vowel")
else:
    print("The given character is NOT a vowel")
```

## OUTPUT
![image](https://github.com/user-attachments/assets/34c29db9-8390-4546-bc26-b0e47715cf11)


## RESULT
Thus the given program implemented and executed successfully.

