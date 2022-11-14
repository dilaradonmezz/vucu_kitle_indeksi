# vucut_kitle_indeksi
Vücut Kitle İndeksi Hesaplama

import java.util.Scanner;

public class vucut_kitle_indeksi {

    public static void main(String[] args){
    
        Scanner input =new Scanner(System.in);
        double boy, kilo;
        System.out.println("Lütfen boyunuzu (metre cinsinde) giriniz : ");
        boy= input.nextDouble();
        System.out.println("Lütfen kilonuzu giriniz : ");
        kilo=input.nextDouble();

        double index= kilo/(boy*boy);
        System.out.println("Vücut Kitle İndeksiniz : " +index);

    }
}
