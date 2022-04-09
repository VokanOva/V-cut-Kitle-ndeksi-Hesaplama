import java.util.Scanner;
     
     public class index {
         
         public static void main(String[] args) {
           
           Scanner Scanner = new Scanner(System.in);

              System.out.print("kilonuz girin :");
              double kg = Scanner.nextDouble();

              System.out.print("bounuz girin (metre) :");
              double m = Scanner.nextDouble();

              double VucutKitleIndeksiniz = kg /(m*m) ;
              System.out.print("VucutKitleIndeksiniz :");
          }
