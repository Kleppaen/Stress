/*
 *Skal prove aa lage en kalkulator med en meny
 */



import java.util.Scanner;
	class Enkelkalkulator{

		public static void main(String [] args){

			Scanner scanner =  new Scanner(System.in);

			System.out.println("Skriv inn to tall som du vil regne med");
			
			double tall1= double.parseDouble(scanner.nextLine());
			double tall2= double.parseDouble(scanner.nextLine());

			addisjon(tall1,tall2);
			substraksjon(tall1, tall2);
			multiplikasjon(tall1,tall2);
			divisjon(tall1,tall2);
		}
		public static void addisjon(double tall1, double tall2){

			double sum=tall1+tall2;
			System.out.println("Summen av tallene dine addert er " + sum);
		}

		public static void substraksjon(double tall1, double tall2){

			double sum=tall1 -tall2;
			System.out.println("Summen av tallene dine subtrahert er " + sum);
		}
		public static void multiplikasjon(double tall1, double tall2){

			double sum=tall1*tall2;
			System.out.println("Summen av tallene dine multiplisert er "+ sum);
		}
		public static void divisjon(double tall1, double tall2);{

		}

		
	}
