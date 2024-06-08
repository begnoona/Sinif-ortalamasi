
        import java.util.Scanner;
public class Main4 {

    public static void main(String[] args) {

    
     //Dersler : Matematik, Fizik, Türkçe, Kimya, Müzik
        //Geçme Notu : 55
        
        int mat,fi,turk,kim,mu,ort;
        
        Scanner input= new Scanner(System.in);

    System.out.println("Matematik notunuzu giriniz: ");
        mat= input.nextInt();
        System.out.println("fizik notunuzu giriniz: ");
        fi= input.nextInt();
        System.out.println("Türkçe notunuzu giriniz: ");
        turk= input.nextInt();
        System.out.println("Kimya notunuzu giriniz: ");
        kim= input.nextInt();
        System.out.println("Müzik notunuzu giriniz: ");
        mu= input.nextInt();


        ort=(mat+fi+turk+kim+mu)/5;
        if(ort<50)
        {
            System.out.print("Sınıfta kaldınız");
        } else if (ort>=50 && ort<75) {
            System.out.print("Sınıfı ortalama ile geçtiniz");

        } else if (ort>=75 && ort<=100) {
            System.out.print("Başarıyla geçtiniz");

        }
        else {
            System.out.print("yanlış ortalama ");
        }


    }
