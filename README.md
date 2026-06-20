# Task-3
import java.util.Scanner;

public class StudentMarksPrediction {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Study Hours: ");
        double hours = sc.nextDouble();

        double predictedMarks = (hours * 12) + 15;

        if (predictedMarks > 100) {
            predictedMarks = 100;
        }

        System.out.println("Predicted Marks = " + predictedMarks);

        sc.close();
    }
}