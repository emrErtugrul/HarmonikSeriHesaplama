# HarmonikSeriHesaplama

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner inp=new Scanner(System.in);
        int x,i;
        double total=0.0;
        System.out.println("Lütfen Sayı giriniz:");
        x=inp.nextInt();
        for (i=1;i<=x;i++){
            total=total+(1.0/i);
        }
        System.out.println(total);
    }
}
