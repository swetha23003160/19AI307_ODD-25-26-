# Ex.No:2(B) METHODS

## QUESTION:
Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).

<img width="144" height="95" alt="image" src="https://github.com/user-attachments/assets/93ffaa13-4515-4872-826e-5d9f238fc9dd" />

## AIM:
To write a Java program to find the cube of a number using methods.

## ALGORITHM :
1. Start the program.
2. Read an integer `n` from the user.
3. Define a method `square()` to calculate the square of a number.
4. Define a method `cube()` that uses `square()` to calculate the cube of the number.
5. Display the cube of the given number and stop the program.




## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: Sanjay
RegisterNumber: 212224110047
*/
```

## SOURCE CODE:

```
import java.util.*;
public class main{
    static int square(int x){
        return x*x;
    }
    static int cube(int x){
        return x*square(x);
    }
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        System.out.println(cube(n));
    }
}

```





## OUTPUT:
<img width="316" height="105" alt="image" src="https://github.com/user-attachments/assets/2b168005-ac6c-4238-9ba2-07d1290fb508" />



## RESULT:
Hence, the Java program for finding the cube of a number using methods was executed successfully and the result was displayed.
