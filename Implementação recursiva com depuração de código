import java.util.Scanner;

public class TrabalhoRecursividade {
   public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);

       System.out.print("Quantos elementos o vetor terá: ");
       int n = sc.nextInt();

       int [] vetor = new int[n];

       preencher_vetor(vetor, 0, sc);

       exibir_vetor(vetor, 0);
   }

   public static void preencher_vetor(int vetor [], int indice, Scanner sc) {
       if (indice >= vetor.length) {
           return;
       }

       System.out.print("Valor do vetor da posição " + indice + ": ");
       vetor[indice] = sc.nextInt();

       preencher_vetor(vetor, indice + 1, sc);
   }

   public static void exibir_vetor(int vetor [], int indice) {
       if (indice >= vetor.length) {
           System.out.println("Fim");
           return;
       }
       System.out.println("Posição " + indice + " = " + vetor[indice]);

       exibir_vetor(vetor, indice + 1);
   }
}
