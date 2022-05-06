package VariaveisTiposOperadores;

import java.util.Scanner;

public class exercicioFor {

    public static void main(String[] args) {
        
        String nomeProduto;
        float precoCusto;
        float precoVenda;

        float totalCusto = 0.0f; //tudo que vai ser usado para c�lculo precisa ser inicializado antes de usar
        float totalVenda = 0.0f;
        
        Scanner leitor = new Scanner(System.in);
        
        int i = 0; //foi criada fora porque eu precisava do escopo da var i fora da estrutura for, pra usar ela no calculo de media
        for(; i < 40; i++){
            System.out.println("Digite o nome do produto: ");
            nomeProduto = leitor.next();
            
            System.out.println("Digite o preço de custo do produto: ");
            precoCusto = leitor.nextFloat();
            
            System.out.println("Digite o preço de venda do produto: ");
            precoVenda = leitor.nextFloat();
            
            totalCusto = totalCusto + precoCusto; //se nao colocar la em cima 0.0f, o totalCusto fica errado, "sem inicializa��o"
            totalVenda = totalVenda + precoVenda;
            
            
            if(precoCusto == precoVenda){
                System.out.println("Não houve lucro nem prejuízo, houve empate "
                        + "entre o preço de custo e o preço de venda.");
            } else {
                if(precoCusto > precoVenda){
                    System.out.println("Prejuízo.");
                    } else {
                        System.out.println("Lucro.");
                            }
                    }
                System.out.println(nomeProduto + ", preço de custo = " + 
                        precoCusto + ", preço de venda = " + precoVenda);
        }
        System.out.println("A media do preço de custo é de " + (totalCusto/i));
        System.out.println("A media do preço de venda é de " + (totalVenda/i));
    }
        
}
