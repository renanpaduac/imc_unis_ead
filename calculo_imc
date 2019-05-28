/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package massacorp;

import javax.swing.JOptionPane;

/**
 *
 * @author rpcarvalho
 */
public class MassaCorp {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {

        double peso;
        peso = Double.parseDouble(JOptionPane.showInputDialog("Digite seu Peso em KG!"));

        double altura;
        altura = Double.parseDouble(JOptionPane.showInputDialog("Digite sua Altura em Metros!"));

        double imc;
        imc = peso / (altura * altura);

        JOptionPane.showMessageDialog(null, "O seu Peso digitado foi: " + peso + "Kg" + "\n" + "A sua altura digitada foi: " + altura + "m" + "\n" + "O Cáculo do seu IMC foi: " + imc);

        if (imc <= 17) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Você está Muito Abaixo do Peso!");
        } else if (imc > 17 && imc <= 18.499999999) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Você está Abaixo do Peso!");
        } else if (imc > 18.500000000 && imc <= 24.999999999) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Seu Peso está Normal!");
        } else if (imc > 25 && imc <= 29.999999999) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Você está Acima do Peso!");
        } else if (imc > 30 && imc <= 34.999999999) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Seu IMC está em Obesidade I!");
        } else if (imc > 35 && imc <= 39.999999999) {
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Seu IMC está em Obesidade II (severa)");
        } else { 
            JOptionPane.showMessageDialog(null, "Seu IMC é: " + imc + "\n" + "Seu IMC está em Obesidade III (mórbida)");
    }
    }
}
