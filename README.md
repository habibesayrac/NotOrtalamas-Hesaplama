# NotOrtalamas-Hesaplama

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {


     int mat,fizik,kimya,turkce,tarih,muzik;
     double average = 0;

        Scanner input = new Scanner(System.in);

        System.out.print("Matematik notunuz: ");
      mat = input.nextInt();

        System.out.print("Fizik notunuz: ");
       fizik = input.nextInt();

        System.out.print("Kimya notunuz: ");
        kimya = input.nextInt();

        System.out.print("Turkce notunuz: ");
       turkce = input.nextInt();

        System.out.print("Tarih notunuz: ");
        tarih = input.nextInt();

        System.out.print("Muzik notunuz: ");
        muzik = input.nextInt();

        average = (mat+fizik+kimya+tarih+turkce+muzik)/6;
        System.out.println("Ortalama Notunuz:   " +average);

        String avg=60< average?"Geçtiniz :)" : " Kaldınız:(";
        System.out.println(avg);
