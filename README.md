# codewithmaheshshklaer-
print number pattern n*n all number same
import java.util.Scanner;

public class star1 {
	public static void main (String[] args) {
	
		//11111
		//22222
		//33333
		//44444
		Scanner s=new Scanner(System.in);
		
	int n;
	n=s.nextInt();
	int i=1;
	while(i<=n)
	{
		int j=1;
		while(j<=n)
		{
			System.out.print(n);
			j++;
			
		}
		System.out.println();
		i++;
		
	}
	
	
	}
}
