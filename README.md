# PP-3.8

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package pp.pkg3.pkg8;

import java.util.Random;
public class PP38 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        double number;
        Random rand = new Random();
        number = rand.nextInt(21)+20;
        System.out.println("Random Number Is " + number);
        System.out.println("Sin = " + Math.sin(number));
        System.out.println("Cos = " + Math.cos(number));
        System.out.println("Tan = " + Math.tan(number));
        
        
    }
    
}
