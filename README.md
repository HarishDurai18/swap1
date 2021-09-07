import java.util.Scanner;
public class swap 
{
  
  public static void main(String[]args)
  {
   
    int x=100,y=200;
   
    System.out.println("Swap");
    System.out.println("x="+x);
    System.out.println("y="+y);
  
    int temp=x;
    x=y;
    y=temp;
 
    System.out.print("After");
    System.out.println("x="+x);
    System.out.println("y="+y);
   }
 }
