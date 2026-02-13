import java.util.Scanner;

public class exercicio5{
    public static void main(String[] args)
{
    Scanner scanner = new
Scanner(System.in);

        System.out.print("digite o primeiro numero: ");
        int n1 = scanner.nextInt();

        System.out.print("digite o segundo numero: ");
        int n2 = scanner.nextInt();

        int resto = n1 % n2;

        System.out.println("O resto da divisão é: " + resto);

            scanner.close();
}
}

