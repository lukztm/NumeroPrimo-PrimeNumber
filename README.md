# NumeroPrimo-PrimeNumber
Recebe um numero e diz se o mesmo é primo.


	import javax.swing.JOptionPane;

	public class Exercicio5PrimoSwitch {

	public static void main(String[] args) {

		int contador = 0;

		String entrada = JOptionPane.showInputDialog("Digite o numero:");
		Integer num = Integer.parseInt(get);

		for (int divisores = 2; divisores < num; divisores++) {
			if (num % divisores == 0) {
				contador++;
				System.out.println("divisores: " + divisores);
				System.out.println("contador: " + contador);
			}
			System.out.println("divisores: " + divisores);
			System.out.println("contador: " + contador);
		}
		if (contador == 0) {
			System.out.println("Numero primo!");
		} else {
			System.out.println("Numero não primo!");
		}
	    }
	}

!!!ENGLISH!!!

#PrimeNumber

Gets a number and checks if it's a prime number.


	import javax.swing.JOptionPane;

	public class Exercise5PrimeSwitch {

	public static void main(String[] args) {

		int counter = 0;

		String get = JOptionPane.showInputDialog("Type a number:");
		Integer num = Integer.parseInt(get);

		for (int dividers = 2; dividers < num; dividers++) {
			if (num % dividers == 0) {
				counter++;
				System.out.println("divisores: " + dividers);
				System.out.println("contador: " + counter);
			}
			System.out.println("divisores: " + dividers);
			System.out.println("contador: " + counter);
		}
		if (counter == 0) {
			System.out.println("Prime number!");
		} else {
			System.out.println("Not a prime number!");
		}
	    }
	}
