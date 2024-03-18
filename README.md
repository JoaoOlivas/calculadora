import java.util.Scanner;

public class calculadora {

    public static void main(String[] args){
    
         Scanner teclado = new Scanner(System.in);
         
         int numero; 
         
         double x, y;
         
         System.out.print("insira um numero de 1 a 4" );
         
         numero = teclado.nextInt();
         
         System.out.println("Insira os valores de X e Y");
         
         x = teclado.nextDouble();
         
         y = teclado.nextDouble();
         
         
         switch (numero){
            
             case 1:
                 System.out.println ("A soma dos valores da " + (x + y));
                 break;
                
           
            case 2:
                 System.out.println ("A subtração dos valores da " + (x - y));
                 break;
                
             
            case 3:
                 System.out.println ("A multiplicação dos valores da " + (x * y));
                 break;
                
             
             case 4:
                 System.out.println ("A divisão dos valores da " +(x/y));
                 break;
                
                 
            default:
                     System.out.println (" esse numero esta invalido");
                     break;
            
         }
    }
}
