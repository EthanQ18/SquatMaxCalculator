# SquatMaxCalculator
This will be a squat max calculator that predicts the max squat of a person based upon the number of reps that a person can complete at a lower weight. The function will be constructed to take the number of reps done at a higher rep count ie 10 reps and scale the level of difficulty to determine the max amount of weight the subject can complete. There will an added section that specifies squat max based upon wearing a weightlifting belt or no belt. 
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


			
	}
}
