package faktorial;

import java.util.Scanner;
public class Faktorial {


    public static void main(String[] args) {
        Scanner masuk = new Scanner(System.in);
        System.out.println("Input: ");
        int a = masuk.nextInt();
        int hasil=1;
        String faktor="";
        for (int i = a; i>0;i--){
            hasil=hasil*i;
            faktor=faktor+i;
            if(i!=1){
                faktor=faktor+"x";
            }
            System.out.println("Sample: "+faktor+"="+hasil);
        }
        System.out.println("");
        System.out.println("Output: "+hasil);
    }
    
}
