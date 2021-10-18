# Part 1. A Quick Introduction...

1. What is printed by line 9? If the code returns an error, explain why.  
```
values added: 20
```

2. What is printed by line 13? If the code returns an error, explain why.   
```
final result: 20
```

3. What is printed by line 9? If the code returns an error, explain why.  
```
values added: 20
```

4. What is printed by line 13? If the code returns an error, explain why.   
  
      It returns error since the result is defined by "let". This keyword prevent line 13, which is outside of block, from accessing result's value.
      
5. What is printed by line 9? If the code returns an error, explain why. 

      It returns error since the result is defined by "const". This keyword prevent result from being changed, so there is a conflict between line 5 and line 7.
      
6. What is printed by line 13? If the code returns an error, explain why. 

      The reason is the same as question 4, since the scopes of "const" and "let" are the same.
