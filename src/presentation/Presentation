package presentation;

import dao.DaoImpl;
import ext.Dao.ext.DaoImpl2;
import metier.metierImpl;
public class Presentation {
    public static void main(String[] args){
        DaoImpl2 dao=new DaoImpl2();
        metierImpl metier=new metierImpl();
        metier.setDao(dao);
        System.out.println("Resultat="+metier.calcul());
    }

}
