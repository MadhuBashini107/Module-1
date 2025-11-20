# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
a=int(input())
b=int(input())
c=int(input())
minimum=(a if (a<b and a<c) else 
        b if(b<a and b<c) else c)
print(f"The minimum of {a}, {b}, {c} is {minimum}")
```

## OUTPUT

<img width="934" height="377" alt="image" src="https://github.com/user-attachments/assets/9425e6a7-dba1-4261-b3c0-81591fad7681" />

## RESULT
Thus,the given python program is implemented and the output is verified.


