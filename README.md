# fakt-ryel
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        //n!=1*2*3*4*.....*n
        Scanner scan = new Scanner(System.in);
        System.out.print("faktöryel sayısı: ");
        int n= scan.nextInt();
        int total =1;

        for(int i=1; i<=n; i++) {
            total= total*i;
        }
        System.out.println(n+"faktöryel:"+total);

        }

    }
