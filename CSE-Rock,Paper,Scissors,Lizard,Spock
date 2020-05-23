/* title: Rock, Paper, Scissors, Lizard, Spock 
 * author: Chelsea Chen 
 * date created: 2020-05-22
 */
import java.util.LinkedList;
import java.util.Scanner;
import java.util.Random;
public class Main {
	public static void main(String[] args) {
	do {
		int playChoice;
		Scanner myInput = new Scanner(System.in);
		System.out.println("Welcome to Rock, Paper, Scissors, Lizard, Spock. Choose Rock (1), Choose Paper (2), Choose Scissors (3), Choose Lizard (4), Choose Spock (5)");
		playChoice = Integer.parseInt(myInput.nextLine());
		int compChoice = getRandInt(1,5);
		if (compChoice == 1) {
			System.out.println("Computer Chose Rock");	
		}
		if (compChoice == 2) {
			System.out.println("Computer Chose Paper");
		}
		if (compChoice == 3) {
			System.out.println("Computer Chose Scissors");
		}
		if (compChoice == 4) {
			System.out.println("Computer Chose Lizard");
		}
		if (compChoice == 5) {
			System.out.println("Computer Chose Spock");
		}
		String[] playOptions = {"rock", "paper", "scissors", "lizard", "spock"};
		if (playChoice == 1) {
			System.out.println("Player chose" + " " + playOptions[0]);
			int [] playRockWins = {3,4};
			if (playChoice == compChoice) {
				System.out.println("There was a tie"); 
			}
			else {
				if (compChoice == playRockWins[0] || compChoice == playRockWins[1]) {
					System.out.println("You Win");
			}
				else {
					System.out.println("Computer Wins");
			}
		}
	}
		if (playChoice == 2) {
			System.out.println("Player chose" + " " + playOptions[1]);
			int [] playRockWins = {1,5};
			if (playChoice == compChoice) {
				System.out.println("There was a tie"); 
			}
			else {
				if (compChoice == playRockWins[0] || compChoice == playRockWins[1]) {
					System.out.println("You Win");
			}
				else {
					System.out.println("Computer Wins");
			}
		}
	}
		if (playChoice == 3) {
			System.out.println("Player chose" + " " + playOptions[2]);
			int [] playRockWins = {2,4};
			if (playChoice == compChoice) {
				System.out.println("There was a tie"); 
			}
			else {
				if (compChoice == playRockWins[0] || compChoice == playRockWins[1]) {
					System.out.println("You Win");
			}
				else {
					System.out.println("Computer Wins");
			}
		}
	}
		if (playChoice == 4) {
			System.out.println("Player chose" + " " + playOptions[3]);
			int [] playRockWins = {2,5};
			if (playChoice == compChoice) {
				System.out.println("There was a tie"); 
			}
			else {
				if (compChoice == playRockWins[0] || compChoice == playRockWins[1]) {
					System.out.println("You Win");
			}
				else {
					System.out.println("Computer Wins");
			}
		}
	}
		if (playChoice == 5) {
			System.out.println("Player chose" + " " + playOptions[4]);
			int [] playRockWins = {1,3};
			if (playChoice == compChoice) {
				System.out.println("There was a tie"); 
			}
			else {
				if (compChoice == playRockWins[0] || compChoice == playRockWins[1]) {
					System.out.println("You Win");
			}
				else {
					System.out.println("Computer Wins");
			}
		}
	}
		
}
	while(playAgain());
}
		public static int getRandInt(int min, int max) {
			Random rand = new Random();
	 
			int randDiff = rand.nextInt ((max - min) +1); //integer between 0 and 10.
	 
			return randDiff + min;
	 
	}
		private static boolean playAgain(){
			Scanner myInput = new Scanner(System.in);
			System.out.println("Play Again? y/N");
			String answer = myInput.nextLine();
			return !(answer.equals("n")) && !(answer.equals("N"));
	}
}

		
	


