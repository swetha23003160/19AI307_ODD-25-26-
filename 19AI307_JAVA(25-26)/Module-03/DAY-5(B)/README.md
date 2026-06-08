# Ex.No:3(F) WRAPPER CLASS

## QUESTION:
Write a Java program to check if a number is prime using wrapper classes. 

## AIM:
To write a Java program that checks whether a given number is prime by using the Integer wrapper class for parsing and handling the input.
a# Ex.No:3(E) INNER CLASS

## QUESTION:
Write a Java program to create an inner class and access it from the outer class.

## AIM:
To demonstrate accessing an inner class from an outer class in Java.

## ALGORITHM :
1.	Create an outer class with a private variable.
2.	Define an inner class inside it with a method to access the outer variable.
3.	In main(), create an object of the outer class.
4.	Use it to create an object of the inner class.
5.	Call the inner class method.

## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: Swetha M
RegisterNumber: 212223040223
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class OuterClass {
    String name;

    OuterClass(String name) {
        this.name = name;
    }

    void display() {
        InnerClass inner = new InnerClass();
        inner.showMessage();
    }

    class InnerClass {
        void showMessage() {
            System.out.println("Hello, " + name + "! This message is from the Inner Class.");
        }
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("");
        String input = scanner.next();
        scanner.close();

        OuterClass outer = new OuterClass(input);
        outer.display();
    }
}
```

## OUTPUT:
<img width="1223" height="347" alt="image" src="https://github.com/user-attachments/assets/3a4a3b07-7cc7-4e68-877e-4bb04d3aab6d" />

## RESULT:
The program successfully accesses and prints data from the inner class using the outer class.





2. Use the Integer.parseInt() method (wrapper class) to convert the input into an integer.

3. If parsing fails, catch NumberFormatException and display an error message.

4. If the number is less than or equal to 1, it is not prime.

5. If any divisor divides the number completely, mark it as not prime.

6. After checking, print whether the number is prime or not.

7. Close the scanner.




## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: Sanjay
RegisterNumber: 212224110047
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class PrimeChecker {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        String input = scanner.nextLine();

        try {
            Integer number = Integer.parseInt(input); // Using Integer wrapper class

            if (number <= 1) {
                System.out.println(number + " is not a prime number.");
            } else {
                boolean isPrime = true;
                for (int i = 2; i <= Math.sqrt(number); i++) {
                    if (number % i == 0) {
                        isPrime = false;
                        break;
                    }
                }

                if (isPrime) {
                    System.out.println(number + " is a prime number.");
                } else {
                    System.out.println(number + " is not a prime number.");
                }
            }

        } catch (NumberFormatException e) {
            System.out.println("Invalid input. Please enter a valid integer.");
        }

        scanner.close();
    }
}
```






## OUTPUT:
<img width="893" height="258" alt="image" src="https://github.com/user-attachments/assets/2cfce946-0ad1-43c0-a0b9-9f1d4d27a34b" />



## RESULT:
Therefore the program successfully checks if the input number is a prime using the Integer wrapper class.







