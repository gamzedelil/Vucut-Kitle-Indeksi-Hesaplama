# Vucut-Kitle-Indeksi-Hesaplama

import java.util.Scanner;

class Main {
    public static void main(String[] args) {
      
        double m,kg; 
        
        Scanner input = new Scanner(System.in);
        System.out.println("Boyunuzu metre cinsinden girin:");
        m = input.nextDouble();
        System.out.println("Kilonuzu girin:");
        kg = input.nextDouble();
         
        double vki = (kg /( m * m));
       System.out.println("Vucut kitle indeksiniz:" +vki);
        vki = input.nextDouble();
       
        
    }
}
