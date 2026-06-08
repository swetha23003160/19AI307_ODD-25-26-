# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program to calculate the factorial of a number using a for loop. The factorial of n is the product of all positive integers less than or equal to n.

<img width="267" height="97" alt="image" src="https://github.com/user-attachments/assets/7e44b009-a2c9-4539-890e-229940e5d267" />

## AIM:
To write a Java program to find the factorial of a given number.

## ALGORITHM :
1. Read an integer n from the user.
2. Initialize a variable fact to 1.
3. Use a loop to multiply fact by each number from 1 to n.
4. Store the final product in fact.
5. Display the factorial of the given number.


## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Sanjay S
RegisterNumber: 212224110047
*/
```

## SOURCE CODE:
```
import java.util.*;
public class main{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        int n = input.nextInt();
        int fact=1;
        for(int i=1;i<=n;i++){
                 fact *=i;
        }
        System.out.println("Factorial of "+n+" is: "+fact);
    }
}

```
## OUTPUT:
<img width="685" height="188" alt="image" src="https://github.com/user-attachments/assets/656d1fd9-e302-4974-933c-433de8b8db59" />

## RESULT:
Hence, the Java program for finding the factorial of a given number was executed successfully and the result was displayed.
