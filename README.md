## Aim: To study while loop in python.

## Theory:  
Types of loops: for, while, nested.      
A while loop in Python is a control flow statement that allows a block of code to be executed repeatedly as long as a given condition is True.      
Loop condition must eventually become False.      
If the condition never becomes False, it creates an infinite loop.      
digit = n%10     
rev = rev*10 + digit     
n //= 10 ..... This reverses a number.    
To reverse an element we use: rev = st[::-1] .     

## Algorithm:
    1. Print numbers 1 to n:
    Start
    Get an integer n from the user.
    Initialize: Set i to 1.
    Condition: While i is less than or equal to n. Output: Print the value of i. Update: Increment i by 1.
    End.

    2. Factorial of a Number
    Start
    Input: Get an integer n from the user.
    Initialize: Set fact to 1.
    Condition: While n is greater than 0 .
    Calculate: Multiply fact by n and store it in fact.
    Update: Decrement n by 1.
    Output: Print the final value of fact.
    End.

    3. Fibonacci Series (Up to n terms)
    Start
    Input: Get the number of terms n from the user.
    Initialize: Set a = 0, b = 1, and counter i = 1.
    Condition: While i is less than or equal to n:
    Output: Print the current value of a.
    Calculate: Store the sum of a and b in c.
    Shift: Update a to the value of b, and b to the value of c.
    Update: Increment i by 1.
    End.

    4. Reverse a Number
    Start
    Input: Get an integer n from the user.
    Initialize: Set rev to 0.
    Condition: While n is greater than 0:
    Extract: Get the last digit using n % 10.
    Append: Update rev as (rev * 10) + digit.
    Reduce: Remove the last digit from n using floor division (n // 10).
    Output: Print the reversed number rev.
    End.

    5. Check Palindrome (Number & String)
    Start
    Input: Get the input (number or string).
    Process: Reverse the input using a loop or slicing ([::-1]).
    Compare: Check if the original input is equal to the reversed version.
    Output: If equal, print "palindrome"; otherwise, print "not palindrome".
    End.

    6. Count Digits in a Number
    Start
    Input: Get an integer n.
    Initialize: Set count to 0.
    Condition: While n is not equal to 0:
    Update: Increment count by 1.
    Reduce: Remove the last digit from $n$ using floor division.
    Output: Print the count.
    End.

    7. Search Element in a List 
    Start
    Initialize: Define a list nums and get a key to search from the user.
    Iteration: Start a loop to check each index i of the list.
    Check: If the element at nums[i] matches the key:
    Result: Print the index and use break to exit the loop.
    Else Case: If the loop finishes without finding the key, print "number not found".
    End.

## Conclusion:
Hence while loop was successfully executed in python and operations were done using it.
