- package Divisibleby3and5;
- import java.util.Scanner;
- public class Divisibleby3and5;

     public static void main(String[] args){
     
        Scanner in = new Scanner(Ststem.in);
        System.out.print("Enter number: ");
        int num = in.nextInt();
        
        if (num % 3 = 0 && num % 5 = 0)
            System.out.println("Divisible by 3 and 5");
       else if (num % 3 = 0 && num % 5 != 0)
            System.out.println("Divisible by 3 and not 5);
       else if (num % 3 != 0 && num % 5 = 0)
            Sysetm.out.println("Divisible by 5 and not 3);
       else
            System.out.println("Not divisible by 3 or 5");
