# Print()
### Print() is Built-in-function,  which prints whatever is passed inside the () paranthesis as arguments.

#### Syntax: 
  + ```
      >>> print("Things you need to Print ")
    ```
  + Ex - 
    ``` 
      >>> print("HELLO WORLD !")  
    ```

 
### Multiple Strings
  + ```
      >>> print("Things","you","need","to","Print")
    ```
  + O/P - 
    ``` 
      Things you need to Print
    ```

### Key Word Arguments

#### end = ""
  + Depending the value passed inside the ``" "`` the output changes.
  + In the below example an empty string is passed.
  + Eg -
      ```
        >>> print("Things you need to Print ", end='');\
        >>> print("can be given here ! ");\
      ```
  + O/P -
      ```
        Things you need to Print can be given here !
      ```
  + What ever is given inside the ```''``` will gets added once the statement is completed.
      
#### sep=" "
  + It allows you to seprate the arguments passed by the value passed inside ```''```
  + Eg -
      ```
        >>> print("Things","you","need","to","Print", sep="--");\
        >>> print("can","be","given","here ! ",sep='#');\
      ```
  + O/P -
      ```
        Things--you--need--to--Print
        can#be#given#here !
      ```
 ### Summary:
 + print() can be used without importing as it is a built-in-function
 + Allows us to print values to the console
 + We can pass the value to be printed inside the parantheses.
 + The blackslash ```\``` tells python the next charahter has special meaning eg - ```\n```, prints a new line.
