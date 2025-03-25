# CalculoPi
import java.util.Scanner;

public class CalculoPi{

public static void main (String[] args){
  // Definir o valor de pi
final double  PI = 3.14;
 // Criar um objeto Scanner para obter a entrada do utilizador
Scanner scanner = new Scanner (System.in);
 // Solicitar o raio do círculo ao utilizador
System.out.println("Incira o raio do circulo:");
double raio = scanner.nextDouble();
 // Calcular a área do círculo
 double area = PI * Math.pow(raio,2);
 //Exibir o resultado
System.out.println("Incira a area do circulo com raio" + raio + "e:" + area);
scanner.close();
}    
}
