# java-test-0002-final-17958-chetan
Final Project Assignment - This repository contains the complete final project code and documentation.

## Assignment - 2 Solution 
```java
package Basic;

/**
 * Prints a palindrome number pyramid pattern.
 */
public class Assignment {

    public static void main(String[] args) {

        final int PATTERN_SIZE = 5; // size of the pyramid

        for (int i = 1; i <= PATTERN_SIZE; i++) {

            // print starting spaces
            for (int j = i; j < PATTERN_SIZE; j++) {
                System.out.print("  ");
            }

            // increasing numbers
            for (int j = 1; j <= i; j++) {
                System.out.print(j + " ");
            }

            // decreasing numbers
            for (int j = i - 1; j >= 1; j--) {
                System.out.print(j + " ");
            }

            System.out.println();
        }
    }
}

```
