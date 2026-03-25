# Atividade-2-entrevista-de-emprego


import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner trabalho = new Scanner(System.in);

        // NOME DO TRABALHADOR
        System.out.print("Digite o nome dele");
        String nome = trabalho.nextLine();
        System.out.println("o nome dele é: " + nome);

        // A IDADE DO TRABALHADOR
        System.out.print("Digite a idade");
        int idade = trabalho.nextInt();
        System.out.println("a idade dele é: " + idade);

        // O GENERO DO TRABALHADOR
        System.out.print("Digite o genero dele");
        String genero = trabalho.nextLine();
        System.out.println("o genero dele é: " + genero);

        // ENDEREÇO DO TRABALHADOR
        System.out.print("Digite o endereço dele");
        String endereco = trabalho.nextLine();
        System.out.println("o endereco dele é: " + endereco);

        // ANOS DE EXPERIENCIA DO TRABALHADOR
        System.out.print("Digite a experiencia dele");
        int qualidade = trabalho.nextInt();
        System.out.println("a experiencia dele é: " + qualidade);
    }
}
