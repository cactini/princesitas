# princesitas
public static void main(String[] args) {
			
			Scanner input = new Scanner(System.in);
			
			System.out.print("Dime el primer número:");
			int numerin1 = input.nextInt();
			
			System.out.print("Dime el segundo número:");
			int numerin2 = input.nextInt();
			
			System.out.print("Dime el tercer número:");
			int numerin3 = input.nextInt();
			
			input.close();
				
			System.out.println("Los números "+numerin1+ ","+numerin2+","+numerin3+"," + (numerin1>numerin2&&numerin2>numerin3||numerin1<numerin2&&numerin2<numerin3 ? " estan ordenados.": " no estan ordenados."));
	}
}
