/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package prueba.estatico;

import java.util.Arrays;
import java.util.Collections;
import java.util.Scanner;

/**
 *
 * @author admin
 */
class Prueba {

    public void Show() {
        System.out.println("Dentro de Show");
    }

    public static void ShowMassage() {
        System.out.println("Dentro de show massage");

    }

    public static void Show1() {
        //int i;
        for (int i = 1; i < 7; i++) {
            System.out.println(i);
        }
        System.out.println("10");

    }

    public static void Show2() {
        int i = 1;
        while (i <= 10) {
            if (i != 7 && i != 8 && i != 9) {
                System.out.println(i);
            }
            i++;
        }

    }

    public static void Show3() {
        int i = 10;
        while (i >= 2) {
            if (i != 7 && i != 9) {
                System.out.println(i);
            }
            i--;
        }
    }

    public static void Show4() {
        for (int i = 1; i < 6; i++) {
            System.out.print(i);
        }
        System.out.println("");
        for (int i = 6; i < 11; i++) {
            System.out.print(i);
        }
        System.out.println("");
    }

    public static void ShowText() {
        System.out.println("Hola");
        Scanner s = new Scanner(System.in);
        String ingreso = "";
        do {
            ingreso = s.next();
            System.out.println("Uds ingreso:" + ingreso);
        } while (!"SALIR".equals(ingreso));
        s.close();
    }
    //public static void ShowText2(){
    //  String prueba;
    //System.out.println(prueba.equals("Salir"));
    /*public static void ShowVect() {
        String ingreso1 = "";
        do {
            ingreso1 = s.next();
            System.out.println("Uds ingreso:" + ingreso1);
        } while (!"0".equals(ingreso1));
        s.close();

        int vectInt[] = {ingreso1};
        for (int i = 0; i < vectInt.length; i++) {
            System.out.println(vectInt[i]);
        }

    }
*/
    public static void ShowMyVect() {
        int ingreso = 0;
        int tam = 10;
        int i = 0;
        Integer vectInt[] = new Integer[tam];
        Scanner s = new Scanner(System.in);
        for (i = 0; i < tam; i++) {
            ingreso = s.nextInt();
            vectInt[i] = ingreso;
        }
        s.close();

        System.out.println("Vector Original: ");
        for (i = 0; i < vectInt.length; i++) {
            System.out.println(vectInt[i]);
        }
        
        System.out.println("Vector Ordenado: ");
        Arrays.sort(vectInt);
        for (i = 0; i < vectInt.length; i++) {
            System.out.println(vectInt[i]);
        }
        
        System.out.println("Vector Ordenado Invertido: ");
        
        Arrays.sort(vectInt, Collections.reverseOrder());
        for (i = 0; i < vectInt.length; i++) {
            System.out.println(vectInt[i]);
        }
    }
}
