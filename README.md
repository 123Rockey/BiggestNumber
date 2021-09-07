import java.util.Scanner;
public class BiggestNumber
{
  public static void main(String[]args)
  {
    int x,y,z;
    Scanner S=new Scanner(System.in);
    System.out.print("Enter the first number:");
    x=S.nextInt();
    System.out.print("Enter the second number:");
    y=S.nextInt();
    System.out.print("Enter the third number:");
    z=S.nextInt();
  if(x>y&&x>z)
    {
      System.out.println("Largest number is:"+x);
    }
   else if(y>x&&y>z)                     
    {
      System.out.println("Largest number is:"+y);
    }
  else
    {
      System.out.println("Largest number is:"+z);
    }
  }
}
                                                                                                                                           
    

