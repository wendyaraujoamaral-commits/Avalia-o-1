import java.util.Scanner;

public class CalcularMedias {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        double[] notas = new double[8];

        System.out.println("Informe as 8 notas anuais do aluno:");
        for (int i = 0; i < notas.length; i++) {
            System.out.print("Nota " + (i + 1) + ": ");
            notas[i] = sc.nextDouble();
        }

        double b1 = (notas[0] + notas[1]) / 2;
        double b2 = (notas[2] + notas[3]) / 2;
        double b3 = (notas[4] + notas[5]) / 2;
        double b4 = (notas[6] + notas[7]) / 2;

        double s1 = (notas[0] + notas[1] + notas[2] + notas[3]) / 4;
        double s2 = (notas[4] + notas[5] + notas[6] + notas[7]) / 4;

        double mediaFinal = (s1 + s2) / 2;

        System.out.println("---------- RESULTADO ----------");
        System.out.printf("1° Bimestre: %.1f\n", b1);
        System.out.printf("2° Bimestre: %.1f\n", b2);
        System.out.printf("1° Semestre: %.1f\n", s1);
        System.out.println("-------------------------------");
        System.out.printf("3° Bimestre: %.1f\n", b3);
        System.out.printf("4° Bimestre: %.1f\n", b4);
        System.out.printf("2° Semestre: %.1f\n", s2);
        System.out.println("-------------------------------");
        System.out.printf("Média Final: %.1f\n", mediaFinal);

    }
}
