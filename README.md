# carrito

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package carrito;

/**
 *
 * @author Adolf
 */
public class Carrito {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Toyota civic=new Toyota();
        civic.encender();
        civic.gasolina();
        civic.apagar();
    }
    
}



#Toyota

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package carrito;

/**
 *
 * @author Adolf
 */
public class Toyota {
        public Toyota(){
        //Costructor 
        System.out.println("Se ha costruido el objeto");
    }
    //Metodos
        public void avanzar(){
            System.out.println("Estoy Avanzando ");
        }
        public void encender(){
            System.out.println("El Vehiculo esta Encendido");
        }
        public void frenar(){
            System.out.println("Frenado");
        }
        public void apagar(){
            System.out.println("Se apago el vehiculo");
        }
        public void gasolina(){
            System.out.println("El tanque tiene poca Gasolina");
        }
}
     
