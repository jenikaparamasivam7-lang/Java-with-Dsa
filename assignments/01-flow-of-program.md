
Input a year and find whether it is a leap year or not.

code
import java.util.Scanner;

public class LeapYear {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the year: ");
        int year = sc.nextInt();

        if (year % 400 == 0 || (year % 4 == 0 && year % 100 != 0)) {
            System.out.println("Leap Year");
        } else {
            System.out.println("Not a Leap Year");
        }

        sc.close();
    }
} 
output
Enter the year: 2020
Leap Year2024

=== Code Execution Successful ===

Take two numbers and print the sum of both.

code 
import java.util.Scanner;

public class SumTwoNumbers {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        int sum = a + b;

        System.out.println("Sum = " + sum);

        sc.close();
    }
}

output
Enter first number: 10
Enter second number: 20
Sum = 30

=== Code Execution Successful ===


