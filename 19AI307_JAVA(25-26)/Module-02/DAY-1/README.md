# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Course with attributes code, title, credits.

<img width="403" height="120" alt="image" src="https://github.com/user-attachments/assets/bd3f84f1-24aa-460e-9fc7-f05e184120fa" />

## AIM:
To write a Java program to create and display details of two courses using objects.

## ALGORITHM :
1. Start the program.
2. Create a class `Course` with attributes code, title, and credits.
3. Create two Course objects and read their details from the user.
4. Store the input values in the respective object attributes.
5. Display the details of both courses and stop the program.

## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Swetha M
RegisterNumber: 212223040223
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
class Course{
    String code;
    String title;
    int credits;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Course c1 = new Course();
        c1.code = sc.next();
        c1.title = sc.next();
        c1.credits = sc.nextInt();

        Course c2 = new Course();
        c2.code = sc.next();
        c2.title = sc.next();
        c2.credits = sc.nextInt();

        System.out.println(c1.code + " | " + c1.title + " | " + c1.credits + " credits");
        System.out.println(c2.code + " | " + c2.title + " | " + c2.credits + " credits");

        sc.close();
    }
}

```


## OUTPUT:

<img width="772" height="189" alt="image" src="https://github.com/user-attachments/assets/430ce2b0-8f49-4f3e-b52f-9a3c5b5589b9" />

## RESULT:
Hence, the Java program for creating and displaying the details of two course objects was executed successfully and the output was displayed.
