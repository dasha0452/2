import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner a = new Scanner(System.in);
        System.out.println("enter a day number");
        int day = a.nextInt();
        if (day<1 || day>31){
            System.out.println("error");
            return;
        }
        Scanner b = new Scanner(System.in);
        System.out.println("enter a month number");
        int month = b.nextInt();
        if (month<1 || month>12){
            System.out.println("error");
            return;
        }
        if (month==12 || month==1 || month==2){
            System.out.println("Зима");
            return;
        }
        if (month==3 || month==4 || month==5){
            System.out.println("Весна");
            return;
        }
        if (month==6 || month==7 || month==8){
            System.out.println("Лето");
            return;
        }
        if (month==9 || month==10 || month==11){
            System.out.println("Осень");
            return;
        }
    }

}
