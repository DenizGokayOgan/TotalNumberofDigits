# TotalNumberofDigits



    import java.util.Scanner;
    public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Bir sayı giriniz :");
        int number = input.nextInt();
        int total = 0 , othernum;
        while(number!= 0){
            othernum = number %10;
            total += othernum;
            number = number/10;

        }
    System.out.println("girilen sayının basamakları toplamı= " +total);
    }
    }
