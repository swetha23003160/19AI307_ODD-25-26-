# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:

In a magical building, an elevator behaves oddly:
If the floor number is divisible by 3 and 5, it says "Skipped".
If the floor number is divisible by 3 only, it says "Beware!".
If the floor number is divisible by 5 only, it says "Blessings!".
Otherwise, it announces the floor number - print - "Floor {number}" .
Write a Java program to simulate this elevator logic for a given floor number.

<img width="218" height="108" alt="image" src="https://github.com/user-attachments/assets/f048c5ef-8c7f-4192-864a-8fc75255f57a" />

## AIM:
To write a Java program that checks whether a number is divisible by 3, 5, or both, and displays the corresponding message.

## ALGORITHM :
1. Read an integer n from the user.
2. Check if n is divisible by both 3 and 5 and print "Skipped".
3. Otherwise, check if n is divisible by 3 and print "Beware!".
4. Otherwise, check if n is divisible by 5 and print "Blessings!".
5. If none of the above conditions are true, print "Floor" followed by n.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Sanjay
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
        if (n%3 ==0 && n%5==0){
            System.out.println("Skipped");
        }
        else if(n%3==0){
            System.out.println("Beware!");
        }
        else if(n%5==0){
            System.out.println("Blessings!");
        }
        else{
            System.out.println("Floor "+n);
        }
    }
}

```
## OUTPUT:

<img width="464" height="232" alt="image" src="https://github.com/user-attachments/assets/497fbbcf-224f-4502-8339-0d410907647a" />

## RESULT:
Hence, the Java program for checking divisibility by 3 and 5 and displaying the corresponding output was executed successfully.
