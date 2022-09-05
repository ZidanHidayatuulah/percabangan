/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package coding;

import java.util.Scanner;

/**
 *
 * @author HP
 */
public class Coding {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner input = new Scanner (System.in);
       int uang ;
        int batas=2500000;
        System.out.println("PINJAMAN UANG ");
        System.out.println("berapa uang yang ingin anda punjam ?");
        System.out.println("batas peminjaman adalah 2500000");
        uang=input.nextInt();
        
        
        
        
        if (uang < batas){
            System.out.println( "bunga="+uang*0.02);
        }else{
            System.out.println("maaf uang yang ingin anda pinjam terlalu banyak");
        }
    }
}
