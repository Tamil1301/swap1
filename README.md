import java util.Scanner;
public class Swap1
{ 
  public static void main(String[]args)
  {
   System.out.println("Before Swapping");
   int x=15;
   int y=20;
   System.out.println("value of x:"+x);
   System.out.println("value of y:"+y);
   System.out.println("After Swapping");
   x=x+y;
   y=x-y;
   x=x-y;
   System.out.println("value of x:"+x);
   System.out.println("value of y:"+y);
  }
}
