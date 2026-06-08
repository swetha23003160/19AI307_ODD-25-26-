# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a Java program to reverse a given string.

<img width="329" height="122" alt="image" src="https://github.com/user-attachments/assets/2ce0efea-091e-4111-a795-b5c5ee39d649" />

## AIM:
To write a Java program to reverse a given string.

## ALGORITHM :
1. Start the program.
2. Read a string `word` from the user.
3. Reverse the string using `StringBuilder`.
4. Store the reversed string in the variable `reversed`.
5. Display the reversed string and stop the program.


## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Sanjay
RegisterNumber: 212224110047
*/
```

## SOURCE CODE:
```
import java.util.*;
import java.lang.String;
public class main{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        String word = input.next();
        String reversed = new StringBuilder(word).reverse().toString();
        System.out.println("Reversed string: "+reversed);
    }
}

```

## OUTPUT:
<img width="647" height="182" alt="image" src="https://github.com/user-attachments/assets/53fe4a9c-c30a-4017-8809-36296baba911" />

## RESULT:
Hence, the Java program for reversing a given string was executed successfully and the reversed string was displayed.
