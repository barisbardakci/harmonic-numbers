# harmonic-numbers
Java101_21 a program finding harmonic series with given numbers

https://www.patika.dev/tr

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    int num ;
	    double result, i ;
	    
	    Scanner input=new Scanner(System.in);
	    System.out.print("Enter N number : ");
	    num=input.nextInt();
	    
	    result=0.0;
	    for(i=1 ; i<=num ; i++){
	        result+=(1/i);
	    }
	    System.out.print(result);
	        
	    
	}
}
