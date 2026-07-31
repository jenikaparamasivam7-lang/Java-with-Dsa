Write a program to print whether a number is even or odd, also take input from the user

code
import java.util.Scanner;

public class EvenOdd {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int n = sc.nextInt();

        if (n % 2 == 0)
            System.out.println("Even Number");
        else
            System.out.println("Odd Number");
    }
}

Output
Enter a number: 2
Even Number
=== Code Execution Successful ===

Write a program to input principal, time, and rate (P, T, R) from the user and find Simple Interest.

Code
import java.util.Scanner;

public class SimpleInterest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Principal: ");
        float p = sc.nextFloat();

        System.out.print("Enter Time: ");
        float t = sc.nextFloat();

        System.out.print("Enter Rate: ");
        float r = sc.nextFloat();

        float si = (p * t * r) / 100;

        System.out.println("Simple Interest = " + si);
    }
}

Output
Enter a number: 2
Even Number
=== Code Execution Successful ===

Take in two numbers and an operator (+, -, *, /) and calculate the value. (Use if conditions)

Code
import java.util.Scanner;

public class SimpleInterest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Principal: ");
        float p = sc.nextFloat();

        System.out.print("Enter Time: ");
        float t = sc.nextFloat();

        System.out.print("Enter Rate: ");
        float r = sc.nextFloat();

        float si = (p * t * r) / 100;

        System.out.println("Simple Interest = " + si);
    }
}

Output

Enter Principal: 1000
Enter Time: 2
Enter Rate: 5
Simple Interest = 100.0
=== Code Execution Successful ===

Take in two numbers and an operator (+, -, *, /) and calculate the value. (Use if conditions)

Code
 import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        System.out.print("Enter operator (+,-,*,/): ");
        char op = sc.next().charAt(0);

        if (op == '+')
            System.out.println("Answer = " + (a + b));
        else if (op == '-')
            System.out.println("Answer = " + (a - b));
        else if (op == '*')
            System.out.println("Answer = " + (a * b));
        else if (op == '/')
            System.out.println("Answer = " + (a / b));
        else
            System.out.println("Invalid Operator");
    }
}

Output

first number: 2
Enter second number: 3
Enter operator (+,-,*,/): *
Answer = 6
=== Code Execution Successful ===

Take 2 numbers as input and print the largest number.

Code
import java.util.Scanner;

public class Largest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        if (a > b)
            System.out.println("Largest = " + a);
        else
            System.out.println("Largest = " + b);
    }
}

Output
Enter first number: 2
Enter second number: 3
Largest = 3

=== Code Execution Successful ===

Input currency in rupees and output in USD.

Code

import java.util.Scanner;

public class RupeesToUSD {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter amount in Rupees: ");
        double rupees = sc.nextDouble();

        double usd = rupees / 86.0;

        System.out.println("USD = " + usd);
    }
}

Output

Enter amount in Rupees: 86
USD = 1.0

=== Code Execution Successful ===

To calculate Fibonacci Series up to n numbers.

Code

import java.util.Scanner;

public class Fibonacci {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter n: ");
        int n = sc.nextInt();

        int a = 0, b = 1;

        for (int i = 1; i <= n; i++) {
            System.out.print(a + " ");
            int c = a + b;
            a = b;
            b = c;
        }
    }
}

Output

Enter n: 10
0 1 1 2 3 5 8 13 21 34 
=== Code Execution Successful ===

To find out whether the given String is Palindrome or not.

Code

import java.util.Scanner;

public class Palindrome {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a string: ");
        String str = sc.nextLine();

        String rev = "";

        for (int i = str.length() - 1; i >= 0; i--) {
            rev += str.charAt(i);
        }

        if (str.equals(rev))
            System.out.println("Palindrome");
        else
            System.out.println("Not Palindrome");
    }
}

Output
Enter a string: 1
Palindrome

=== Code Execution Successful ===

To find Armstrong Number between two given number.

Code

import java.util.Scanner;

public class Armstrong {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int n = sc.nextInt();

        int temp = n, sum = 0;

        while (temp > 0) {
            int rem = temp % 10;
            sum = sum + (rem * rem * rem);
            temp = temp / 10;
        }

        if (sum == n)
            System.out.println("Armstrong Number");
        else
            System.out.println("Not an Armstrong Number");
    }
}

Output

Enter a number: 4
Not an Armstrong Number

=== Code Execution Successful ===
