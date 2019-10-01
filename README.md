# calculator
import java.util.Scanner;
public static void class main (String [] args){
  Scanner scan = new Scanner (System.in);
  System.out.print("Enter number one: ");
  int num1 = scan.nextInt();
  System.out.println("Enter number two: ");
  int num2 = scan.nextInt();
  String s = new String();
  int sum = 0;
  double division = 0;
  int multiplication = 0;
  int minus = 0;
  s = JOptionPane.showInputDialog("Do you want a sum, diviision, multiplication? " );
  if ( s.equals("sum")){
    sum = num1 + num2;
    System.out.println(sum);
   }else if (s.equals(division)){
     division = num1/num2;
     System.out.println(division);
   }else if (s.equals("multiplication")){
    multiplication = num1 * num2;
    System.out.println(multiplication);
    }else {
      minus = num1 - num2;
      System.out.println(minus);
     }
   
    
