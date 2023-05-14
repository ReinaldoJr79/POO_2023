Atv01
Apresente a soma de todos os argumentos inteiros ou reais recebidos

Códigos comentados aqui neste README

import java.util.Scanner; // importação da classe Scanner


public class Atv01{
    public static void main(String args[]) {
        

        Scanner s = new Scanner(System.in);
        int soma = 0, i, y; // Declaração das variáveis

            System.out.println("Dgite dois números inteiros: ");
            System.out.print("Digite o primeiro valor inteiro: ");
            i = s.nextInt();
            System.out.print("Digite o segundo valor inteiro: ");
            y = s.nextInt();
            soma = i + y; // Equação a ser solucionada
            System.out.println("O valor da soma é: " +soma); 
       
        s.close();
    }
}
