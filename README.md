/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
     import java.util.*;
/**
 *
 * @author Javier Octavio
 */
public class Principal {
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner input = new Scanner(System.in);
        System.out.println("Introduce la Velocidad Inicial");
        double rInicial;
        
        rInicial = input.nextDouble();
        System.out.println("Introduce la Velocidad final");
        double rFinal;
        
        rFinal = input.nextDouble();
        System.out.println("Introdice el tiempo");
        double rTiempo;
        
        rTiempo = input.nextDouble();
        double rDistancia;
        
        rDistancia = (rInicial + rFinal) / 2 * rTiempo;
        System.out.print("La distancia es: ");
        System.out.println(rDistancia);
    }
}
