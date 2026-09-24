# Java-Day-07-Even-Odd
# Java Day 7 - Even or Odd

This program takes a number from the user and checks whether the number is even or odd.

## Example Input

```text
Enter a number: 24
```

## Output

```text
The number is even.
```

## Concepts Used

* Scanner
* User input
* `if-else`
* Modulus operator `%`
* Comparison operator `==`

## How It Works

1. The program takes a number from the user.
2. The `%` operator finds the remainder when the number is divided by 2.
3. If the remainder is 0, the number is even.
4. Otherwise, the number is odd.
5. The result is displayed on the screen.

## Java Code

```java
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        if (number % 2 == 0)
        {
            System.out.println("The number is even.");
        }
        else
        {
            System.out.println("The number is odd.");
        }

        sc.close();
    }
}
```

## Sample Output

```text
Enter a number: 24
The number is even.
```

## Goal

The goal of this project is to practice `if-else` conditions and understand how the modulus operator is used to check even and odd numbers in Java.
