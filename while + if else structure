import java.util.Scanner;

public class exercicio {
    
    public static void main(String[] args) {
        Scanner leitorScanner = new Scanner(System.in);
        char desejaContinuar = 'S'; //Lembrar que char usa aspas simples
        
        while(desejaContinuar == 'S' || desejaContinuar == 's'){
            
            System.out.println("Digite um número: ");
            int numero = leitorScanner.nextInt();
        
            if (numero >= 0){
                if(numero == 0){
                    System.out.println("Voce digitou o numero zero");
                } else {
                    System.out.println("Voce digitou um numero positivo");    
                }
            } else {
                System.out.println("Voce digitou um numero negativo");
                   }
        System.out.println("Deseja continuar? S - Sim / N - Não");
        desejaContinuar = leitorScanner.next().charAt(0);
        }
    }
}
