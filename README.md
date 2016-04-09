/** Determine que dia la placa de un carro tiene restriccion
 * 0y1= LUNES, 2y3= MARTES, 4y5= MIERCOLES, 6y7= JUEVES, 8y9= VIERNES
 * @author Alee
 *
 */

import java.util.Scanner;
public class GAM {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner imput = new Scanner (System.in);
		System.out.println("Ingrese el ulyimo numero de la placa");
		
		int placa =imput.nextInt();
		imput.close();
		
		String dayString;
		
		switch (placa){
				
		case 1 : dayString = "LUNES" ;
		break ;
		case 2 : dayString = "MARTES" ;
		break ;
		case 3 : dayString = "MARTES" ;
		break ;
		case 4 : dayString = "MIERCOLES" ;
		break ;
		case 5 : dayString = "MIERCOLES" ;
		break ;
		case 6 : dayString = "JUEVES" ;
		break ;
		case 7 : dayString = "JUEVES" ;
		break ;
		case 8 : dayString = "VIERNES" ;
		break ;
		case 9 : dayString = "VIERNES" ;
		break ;
		case 0 : dayString = "LUNES" ;
		break ;
		
		default: dayString= "PASAN TODOS";
		break;
	}
		System.out.println("Tiene restriccion el dia " + dayString);
		
	}
}

