# Operators

### Arithmetic operators
  + Exponential ``` ** ```
    + Eg - 
      ```.py
        print(2. ** 3)
      ```
    + O/P -
      ```.py
        8.0
      ```
    + Here base is ``` 2.0 ``` and its raised to ``` 3 ``` . If either or both of them are floating values the output will also be a floating value.
  + Multiplication ``` * ```
    + Eg - 
      ```.py
        print(2 * 3.0)
      ```
    + O/P -
      ```.py
        6.0
      ```
    + Here ``` 2 ``` is multiplied with ``` 3.0 ``` . If either or both of them are floating values the output will also be a floating value.
  + Division ``` / ```
    + Eg - 
      ```.py
        print(10 / 2)
      ```
    + O/P -
      ```.py
        5.0
      ``` 
    + Here ``` 10 ``` is divided by ``` 2 ``` . The output will always be a floating value.
    
  + Floor Division ``` // ```
     + Eg - 
      ```.py
        print(13 // 2)
      ```
    + O/P -
      ```.py
        6
      ``` 
    + Here ``` 13 ``` is floor divided by ``` 2 ``` . If either or both of them are floating values the output will also be a floating value.
    + Can be used for - ve values too
    + Eg - 
       ```.py
        print(6. // -4 , 6./4 )
      ```
    + O/P -
      ```.py
        -2.0 -1.5
      ``` 
  + Modulo ``` % ```
    + Used for calculating remainder after the division.
    + Eg - 
       ```.py
        print(13%2)
      ```
    + O/P -
      ```.py
        1
      ```  
  + Add ``` + ``` & Subtract ``` - ```
    + Eg - 
       ```.py
        print(13+2 , 13-2)
      ```
    + O/P -
      ```.py
        15 11
      ```   
  + Unary Operator ```-x``` Negative value
    + Eg - 
       ```.py
        print(-6 - 6, 10 - -6)
      ```
    + O/P -
      ```.py
        -12 16
      ```   
### Priority
+ High to Low
``` .py
  +   -   (Unary)
  **    
  *   /   //    %
  +   -   (Binary)
```
+ Sub Expression have Higher priority, Expression can be given inside paranthesis  ```(X**Y)```  which will be evaluvated first.



