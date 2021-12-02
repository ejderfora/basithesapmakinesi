```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);

        System.out.print("İlk Sayıyı Girin: ");
        int n1 = input.nextInt();

        System.out.print("İkinci Sayıyı Girin: ");
        int n2 = input.nextInt();

        System.out.println("Yapacağınız İşlemi Seçin \n1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme\nİşlemin Numarasını Girin: ");
        int islem = input.nextInt();

        switch (islem){
            case 1:
                System.out.print(n1 + n2);
                break;
            case 2:
                System.out.print((n1 - n2));
                break;
            case 3:
                System.out.print(n1 * n2);
                break;
            case 4:
                System.out.print(n1 / n2);
                break;
            default:
                System.out.print("Hatalı Giriş Yaptınız.");
        }

    }
}
```