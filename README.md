# havasicakligi

    import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int heat;

        Scanner input = new Scanner(System.in);
        System.out.println("Sıcaklık Değerini Giriniz : ");
        heat = input.nextInt();

        if (heat < 5) {
            System.out.println("Kayak gidebiliriz");
        } else if (heat >5 && heat <=15 ) {
            System.out.println(" Sinemaya gidebilirsiniz");
        } else if ( heat >= 10 && heat < 25) {
            System.out.println("Pikniğe giddebilirsiniz");
        }
        else {
            System.out.println(" Yüzmeye gidebilirsiniz ");
        }


    }
    }

