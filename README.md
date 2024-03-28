import java.util.Scanner;

class Temperature
{
    public static void main(){ 
        Scanner inp = new Scanner (System.in);
        double C, F;
        System.out.println("Enter Temperature in celsius :");
        C = inp.nextDouble();
        F = C*9/5 + 32;
        System.out.println("Your temperature in fahrenheit is : " + F);
        System.out.println("Enter temperature in Fahrenheit : ");
        F = inp.nextDouble();
        C = F - 32 * 5/9;
        System.out.println("Your temperature in Celsius is : " + C);
    }

