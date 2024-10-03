# java
import java.util.Scanner;
public class switch1 {


		public static void main(String []args)
		{
			Scanner sc=new Scanner(System.in);
			System.out.println("Enter the day no");
			String a=sc.next();
			switch(a.toLowerCase()) {
			case "monday" :System.out.println("1");
	          break;
			case "tuesday":System.out.println("2");
	        break;
			case "wed":System.out.println("3");
	        break;
			case "thrusday":System.out.println("4");
	        break;
			case "friday":System.out.println("5");
	        break;
			case "saturday":System.out.println("6");
	        break;
			case "sunday":System.out.println("7");
	        default :System.out.println("invalid input");

			}
					
		}
}

