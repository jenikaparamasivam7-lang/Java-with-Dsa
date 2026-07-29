
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

Take a number as input and print the multiplication table for it.

code
import java.util.Scanner;
public class AlphabetOrSpecial {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a character: ");
        char ch = sc.next().charAt(0);

        if ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z'))
            System.out.println("Alphabet");
        else
            System.out.println("Special Character");
    }
}

output
Enter a character: 
@
Special Character
=== Code Execution Successful ===

numbers as inputs and find their HCF and LCM.

code
import java.util.Scanner;
public class VowelConsonant {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter an alphabet: ");
        char ch = sc.next().charAt(0);

        if (ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U' ||
            ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
            System.out.println("Vowel");
        else
            System.out.println("Consonant");
    }
}

output

Enter an alphabet: A
Vowel
=== Code Execution Successful ===

Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.

code
import java.util.Scanner;
public class AlphabetOrSpecial {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a character: ");
        char ch = sc.next().charAt(0);

        if ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z'))
            System.out.println("Alphabet");
        else
            System.out.println("Special Character");
    }
}

output

Enter a character: A
Alphabet
=== Code Execution Successful ===
