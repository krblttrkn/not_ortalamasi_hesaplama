# Not Ortalaması Hesaplayan Program
* Java ile Matematik, Fizik, Kimya, Türkçe, Tarih ve Müzik derslerinin sınav puanlarını kullanıcıdan alıp puanların ortalamsını hesaplayıp çıkan sonuç 60 veya 60'ın üzerinde ise ekrana "Sınıfı Geçti" , 60'ın altında ise ekrana "Sınıfta Kaldı" yazdıran bir program yazıyoruz.
```
import java.util.Scanner;
public class Baslangic {
    public static void main(String[] args) {
        int mat, fizik, kimya, turkce, tarih, muzik;
        Scanner inp = new Scanner(System.in);

        System.out.print("Matematik Notunuzu Giriniz :");
        mat = inp.nextInt();

        System.out.print("Fizik Notunuzu Giriniz :");
        fizik = inp.nextInt();

        System.out.print("Kimya Notunuzu Giriniz :");
        kimya = inp.nextInt();

        System.out.print("Türkçe Notunuzu Giriniz :");
        turkce = inp.nextInt();

        System.out.print("Tarih Notunuzu Giriniz :");
        tarih = inp.nextInt();

        System.out.print("Müzik Notunuzu Giriniz :");
        muzik = inp.nextInt();

        int toplam = (mat + fizik + kimya + turkce + tarih + muzik);
        double sonuc = (toplam / 6.0);
        System.out.println(sonuc);

        int gecer=60;
        boolean sonuc1 = sonuc >= gecer ;
        String str = sonuc1 ? "Sınıfı Geçti" : "Sınıfta Kaldı" ;
        System.out.print(str);
    }
}
```
# Patika Profilim:
***
<a href="https://app.patika.dev/krblttrkn">Patika Linkim</a>