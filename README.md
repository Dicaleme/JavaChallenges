# JavaChallenges
Practice exercises to develop Java skills


/*import java.util.Scanner;
class Main {
  public static void main(String[] args) {
     float redes, cont, dis, total, p_redes, p_cont, p_dis;
        Scanner leer = new Scanner(System.in);
        System.out.println("Cantidad de alumnos de redes: ");
        redes = leer.nextFloat();
        System.out.println("Cantidad de alumnos de contabilidad: ");
        cont = leer.nextFloat();
        System.out.println("Cantidad de alumnos de diseño: ");
        dis = leer.nextFloat();
        total = redes + cont + dis;
        p_redes = (redes/total)*100;
        p_cont = (cont/total)*100;
        p_dis = (dis/total)*100;
        System.out.println("Los alumnos de redes equivalen al: "+Math.round(p_redes)+"%");
        System.out.println("Los alumnos de contabilidad equivalen al: "+Math.round(p_cont)+"%");
        System.out.println("Los alumnos de diseño equivalen al: "+Math.round(p_dis)+"%");
  }
}*/

import java.util.Scanner;
class Main{
    public static void main (String[] args){
        int a, b, suma, resta, multi, div;
        Scanner leer = new Scanner(System.in);
        System.out.println("Digite un número: ");
        a = leer.nextInt();
        System.out.println("Digite otro número: ");
        b = leer.nextInt();
        suma = a + b;
        resta = a - b;
        multi = a * b;
        div = a / b;
        System.out.println("********** RESULTADOS **********");
        System.out.println("Suma: "+suma);
        System.out.println("Resta: "+resta);
        System.out.println("Multiplicación: "+multi);
        System.out.println("División: "+div);
        System.out.println("********************************");
    }
}
