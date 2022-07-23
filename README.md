# javada-d-g-ler-ile-kuvvet-hesablama
Java döngüler ile girilen sayıya kadar olan 4 ve 5'in kuvvetlerini ekrana yazdıran programı yazıyoruz.

    import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {

        int n,i;
        Scanner inp = new Scanner(System.in);
        System.out.print("dds :");
        n=inp.nextInt();


        for (i=1; i<=n; i*=4  ){
            System.out.println(i);


        }
        System.out.println("-------");
       for (i=1; i<=n; i*=5){
           System.out.println(i);
       }



     }
    } 


(https://www.patika.dev/tr)
![image](https://user-images.githubusercontent.com/107626332/180601571-150ce57a-42ab-405d-8a1d-ad77ffcdd53f.png)
