> Java koşullu ifadeler ile hava sıcaklığına göre etkinlik öneren program yapımı.
>
> Koşullar :
>
> - Sıcaklık 5'dan küçük ise "Kayak" yapmayı öner.
> - Sıcaklık 5 ve 15 arasında ise "Sinema" etkinliğini öner.
> - Sıcaklık 15 ve 25 arasında ise "Piknik" etkinliğini öner.
> - Sıcaklık 25'ten büyük ise "Yüzme" etkinliğini öner.

```java
import java.util.Scanner;

public class heat {
    public static void main(String[] args) {
        int heat;
        Scanner input = new Scanner(System.in);
        System.out.print("Etkinlik önerisi için sıcaklık giriniz :");
        heat = input.nextInt();

        if (heat <5) {
            System.out.println("Kayak Yapabilirsiniz.");
        }
        if (heat >= 5 && heat <= 15) {
            System.out.println("Sinemaya Gidebilirsiniz.");
        }
        if (heat > 15 && heat <=25) {
            System.out.println("Pikniğe Gidebilirsiniz");
        }
        if (heat >25) {
            System.out.println("Yüzmeye Gidebilirsiniz");
        }
        if (heat >60) {
            System.out.println("Or , Welcome to the hell :)");
        }

        
        
    }
    
}

```

