




//Ortalama Hesaplama

import java.util.Scanner;
public class test {
    public static void main(String[] args) {
        System.out.println();
    //degıskenler
        int mat,fizik,kimya,turkce,tarih,muzik;

        //scanner sınıfımızı tanımladık
        Scanner inp=new Scanner(System.in);

        //kullanınıcan degerlerı al

        System.out.print("Mat Notunuz : ");
        mat=inp.nextInt();

        System.out.print("Fizik Notunuz : ");
        fizik=inp.nextInt();

        System.out.print("kimya Notunuz : ");
        kimya=inp.nextInt();

        System.out.print("turkce Notunuz : ");
        turkce=inp.nextInt();

        System.out.print("tarih Notunuz : ");
        tarih=inp.nextInt();

        System.out.print("muzik Notunuz : ");
        muzik=inp.nextInt();

        int toplam=(mat+fizik+kimya+turkce+tarih+muzik);
        double sonuc=toplam/6.0;
        System.out.println("ortalama : " + sonuc);

        //İF SİZ KOSULLU
        double a;
        System.out.println(a=(sonuc>=50)?1:0);
    }
}
