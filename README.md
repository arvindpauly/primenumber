# primenumber
import java.util.Scanner;
public class prime {
	
	private static Scanner pr;

	public static void main(String[] arg){
		pr = new Scanner(System.in);
		int i,a;
	    int n=1;
	    System.out.println("enter the number");
	    a= pr.nextInt();
		for(i=2;i<a/2;i++)
		{
		  if(a%i==0)
		  {
			n=0;
			break;
		  }
		  else
		  {  
		     n=1;
	      }
		}  
		
		if(n==1)
		{
		System.out.println(a+" is a Prime number");
		}
		else 
		{
			System.out.println( a+" is not a prime number");
	    }
}
}
