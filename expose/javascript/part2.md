# Part 2. A Little More of a Challenge...  

1. What will happen at line 12 and why? If the code causes an error, explain why.  

      It prints 3 since the scope of `var` is the whole function, and the length of input list is 3. Therefore the pointer i will stop at the length after iterations.  
      
2. What will happen at line 13 and why? If the code causes an error, explain why.  

      It prints 150 for the same reason of scope of problem 1. Since the `descountedPrice` stoped at the price of last item after discounting, the result should be 300 * (1 - 0.5) = 150.  
      
3. What will happen at line 14 and why? If the code causes an error, explain why.  
 
      It prints 150 for the same reason of scope of problem 1. The `finalPirce` in the last iteration is equal to the value of `descountedPrice` rounding to nearest tenth, which is still 150.  
      
4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
 
      It returns the list `[50, 100, 150]` as the function return a list containing the discounted price of input list and given discount.
      
5. What will happen at line 12 and why?  If the code causes an error, explain why. (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
 
      It causes error since `i` is defiend by `let` in the for loop, which cannot be accessed outside the for loop.  
      
6. What will happen at line 13 and why? If the code causes an error, explain why.  
 
      It causes error for the same reason of scope of problem 5.
      
7. What will happen at line 14 and why? If the code causes an error, explain why. 
 
      It prints 150 since `finalPrice` defined by `let` in `discountPrices` can be accessed within the `discountPrices` function. The `finalPirce` in the last iteration is equal to the value of `descountedPrice` rounding to nearest tenth, which is still 150.   
 
8. What will this function return? Give a brief explanation. If the code causes an error, explain why.
 
      It returns the list `[50, 100, 150]` as the function return a list containing the discounted price of input list and given discount.
      
9. What will happen at line 11 and why? If the code causes an error, explain why.  
 
      It causes error since `i` is defiend by `const` in the for loop, which cannot be accessed outside the for loop.  
    
10. What will happen at line 12 and why? If the code causes an error, explain why.  

      It prints 3 since `length` defined by `const` in `discountPrices` can be accessed within the `discountPrices` function, and it is defined by `.length` method for input list. Therefore its value is 3.  
      
11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
 
      It returns the list `[50, 100, 150]` as the function return a list containing the discounted price of input list and given discount.  
      
# Data Types
 
12. Notations:  

```
    A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]  
 ```
13. Arithmetic Outputs:
 
```
    A. '3' + 2 = '32' (String concatenation)
    B. '3' - 2 = 1 (Arithmetic calculation)
    C. 3 + null = 3 (Arithmetic calculation, null equals 0)
    D. '3' + null = '3null' (String concatenation)
    E. true + 3 = 4 (Arithmetic calculation, true equals 1)
    F. false + null = 0 (Arithmetic calculation, false equals 0, null equals 0)
    G. '3' + undefined = '3undefined' (String concatenation)
    H. '3' - undefined = NaN (Arithmetic calculation, though the result is meaningless)
```
    
14. Comparison Outputs:
 
```
    A. True (Arithmetic comparison, simply 2 > 1)
    B. False (The comparison between two strings will become the comparison of each digits, and since '2' > '1' the result is false.)
    C. True (Arithmetic comparison, simply 2 = 2)
    D. False (Type comparison, their types are different.)
    E. False (Arithmetic comparison, true equals 1, and 2 != 1)
    F. True (Arithmetic comparison, true equals 1, and Boolean(2) equals 1 under the Boolean conversion rule.)
```

15. '==' does not require two values have same types and will automatically perform type conversion. On the other hand, '===' requires two values have the same type.  

16. In the part2-question16 file.

17. The `modifyArray` is a function that takes an input list and a function. For each element in the input list, the function will input it into the callback function, in this case, `doSomething`. The `doSomething` multiply each element in input list by 2 and therefore the `modifyArray` will return the list `[2, 4, 6]`.  

# setInterval(), setTimeout(), clearTimeout()

18. In the part2-question18 file.

19. Outputs: 

```
    1
    4
    3
    2
```
    
    
    
    
    
    
