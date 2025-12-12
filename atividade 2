import java.util.Scanner;

public class ConversorTemperatura {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Informe a tempeatura em Celsius (ºC): ");

        if (!sc.hasNext()) {
            System.out.println("Digite um número real (ex: 25,0).");
            sc.close();
            return;
        }

        double celsius = sc.nextDouble();

        double fahrenheit = (celsius * 1.8) + 32.0;
        double kelvin = (celsius + 273.15);

        System.out.println();
        System.out.printf("Temperatura em Celsius: %.2f ºC\n", celsius);
        System.out.printf("Temperatura em Fahrenheit: %.2f ºF\n", fahrenheit);
        System.out.printf("Temperatura em Kelvin: %.2f ºK\n", kelvin);
    }
}
