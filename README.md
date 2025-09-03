# BASIC-CALCULATOR
Basic calculator using java language.

import java.util.Scanner;

public class calc {
    public static void main(String[] args) {
        System.out.println("CALCULATOR\n1. ADD\n2. SUBTRACT\n3. MULTIPLY\n3. DIVIDE");
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter 1st no: ");
        int a = sc.nextInt();
        System.out.println("Enter 2nd no: ");
        int b = sc.nextInt();
        System.out.println("Enter your choice: ");
        int n = sc.nextInt();
        switch (n) {
            case 1: System.out.println(a+b);
                break;
            case 2: System.out.println(a-b);
                break;
            case 3: System.out.println(a*b);
                break;
            case 4: System.out.println(a/b);
        }
    }
}
