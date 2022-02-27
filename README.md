import java.util.Scanner;

public class SquatMaxCalculator {
	public static void main(String[] args)
	{
		
		System.out.println("Welcome to the Squat Max Calculator");
		
		Scanner scan= new Scanner(System.in); 	
		
		System.out.println("Enter gender: ");	
		 String gender = scan.nextLine();
		
		System.out.println("Enter Age: ");	
	    String age = scan.nextLine();
		
		System.out.println("Enter 8 rep max: ");	
		 int y = scan.nextInt();
		double X = 1.264;
		scan.close();
		double maxsquat = y * X;
		System.out.println(maxsquat);
		
}}
