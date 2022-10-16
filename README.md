# Sayinin-Ussunu-Hesaplama
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class sayiUssu {
    public static void main(String[] args) {

        int n,k;
        Scanner input = new Scanner(System.in);
        System.out.print("Üssü alınacak sayıyı giriniz:");
        n = input.nextInt();
        System.out.print("Üs olacak sayıyı giriniz:");
        k = input.nextInt();

        int i,total = 1;
        for (i=1 ;i<=k ;i++){
            total *= n;
        };
        System.out.println("Sonuç: "+total);
    }
}
```
