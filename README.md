import java.util.Scanner;

public class FiveAdd {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the 1st number");
        int a = sc.nextInt();
        System.out.println("Enter the 2nd number");
        int b = sc.nextInt();
        System.out.println("Enter the 3rd number");
        int c = sc.nextInt();
        System.out.println("Enter the 4th number");
        int d = sc.nextInt();
        System.out.println("Enter the 5th number");
        int e = sc.nextInt();
        int f = a + b + c + d + e;
        System.out.println("The total sum of the numbers are " + f);

    }
}
