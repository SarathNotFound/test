import java.util.Scanner;

public class AddNumbers {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Ask the user to input two numbers
        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();

        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();

        // Add the numbers
        double sum = num1 + num2;

        // Display the result


        // Close the scanner
        scanner.close();
    }
}

