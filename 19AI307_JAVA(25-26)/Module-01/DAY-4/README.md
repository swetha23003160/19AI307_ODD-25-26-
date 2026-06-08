# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to Find the Average of Array Elements.

<img width="391" height="230" alt="image" src="https://github.com/user-attachments/assets/aba7f55e-9953-4376-abd9-9685ff18cdae" />

## AIM:
To write a Java program to calculate the factorial of a given number.

## ALGORITHM :
1. Read an integer n from the user.
2. Initialize a variable fact to 1.
3. Use a loop to multiply fact by each number from 1 to n.
4. Store the final product in fact.
5. Display the factorial of the given number.

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Swetha M
RegisterNumber: 212223040223
*/
```

## SOURCE CODE:
```
import java.util.*;
public class main{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        int n = input.nextInt();
        int[] array = new int[n];
        int sum =0;
        for(int i=0;i<n;i++){
            int num = input.nextInt();
            array[i]=num;
            sum +=array[i];
        }
        double aver = (double)sum/n;
        System.out.printf("The average of elements is %.2f", aver);
    }
}
```
## OUTPUT:
<img width="762" height="347" alt="image" src="https://github.com/user-attachments/assets/55ddf503-0a2b-4873-b6a1-01e979c892e2" />



## RESULT:
Hence, the Java program for finding the factorial of a given number was executed successfully and the factorial value was displayed.
