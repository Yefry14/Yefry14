package javaapplication8;

import javax.swing.JOptionPane;


public class condicionalmultiple {
    public static void main(String[] args) {
        float n1,n2,suma,resta,mul,div;
        int opcion=Integer.parseInt(JOptionPane.showInputDialog(null, "CALCULADORA\n\n "
                + "1.SUMAR\n "
                + "2.RESTAR\n "
                + "3.MULTIPLICAR\n "
                + "4.DIVIDIR\n"
                + "5.SALIR\n"));
                    switch (opcion) {
            case 1:
                n1=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                n2=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                suma=n1+n2;
                JOptionPane.showMessageDialog(null, "La suma es:\n" + suma);
                break;
            case 2:
                n1=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                n2=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                resta=n1-n2;
                JOptionPane.showMessageDialog(null, "La resta es:\n" + resta);
                break;
            case 3: 
                n1=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                n2=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                mul=n1*n2;
                JOptionPane.showMessageDialog(null, "La multiplicacion es:\n" + mul);
                break;
            case 4:
                n1=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                n2=Float.parseFloat(JOptionPane.showInputDialog("Ingrese un numero"));
                div=n1/n2;
                JOptionPane.showMessageDialog(null, "La multiplicacion es:\n" + div);
                break;
            case 5:
                default:System.exit(0);
