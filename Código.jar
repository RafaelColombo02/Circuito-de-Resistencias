import javax.swing.JOptionPane;

public class CircuitoResistencias {
    public static void main(String[] args) {
        // Receber os valores das resistências usando JOptionPane
        String resistencia1Input = JOptionPane.showInputDialog(null, "Digite o valor da primeira resistência (em ohms):");
        double resistencia1 = Double.parseDouble(resistencia1Input);

        String resistencia2Input = JOptionPane.showInputDialog(null, "Digite o valor da segunda resistência (em ohms):");
        double resistencia2 = Double.parseDouble(resistencia2Input);

        String resistencia3Input = JOptionPane.showInputDialog(null, "Digite o valor da terceira resistência (em ohms):");
        double resistencia3 = Double.parseDouble(resistencia3Input);

        String resistencia4Input = JOptionPane.showInputDialog(null, "Digite o valor da quarta resistência (em ohms):");
        double resistencia4 = Double.parseDouble(resistencia4Input);

        // Calcular a resistência equivalente, a maior e a menor resistência
        double resistenciaEquivalente = resistencia1 + resistencia2 + resistencia3 + resistencia4;
        double maiorResistencia = Math.max(Math.max(resistencia1, resistencia2), Math.max(resistencia3, resistencia4));
        double menorResistencia = Math.min(Math.min(resistencia1, resistencia2), Math.min(resistencia3, resistencia4));

        // Exibir os resultados usando JOptionPane
        JOptionPane.showMessageDialog(null, "Resistência Equivalente: " + resistenciaEquivalente + " ohms\n"
                + "Maior Resistência: " + maiorResistencia + " ohms\n" + "Menor Resistência: " + menorResistencia + " ohms");
    }
}
