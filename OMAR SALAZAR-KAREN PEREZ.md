# PRUEBA
public class carro {
    public String color;
    public char placa;
   public String chasis;

    carro() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    public String getColor() {
        return color;
    }

    public void setColor(String color) {
        this.color = color;
    }

    public char getPlaca() {
        return placa;
    }

    public void setPlaca(char placa) {
        this.placa = placa;
    }

    public String getChasis() {
        return chasis;
    }

    public void setChasis(String chasis) {
        this.chasis = chasis;
    }

    public char getSeguro() {
        return seguro;
    }

    public void setSeguro(char seguro) {
        this.seguro = seguro;
    }

    public String getRin() {
        return rin;
    }

    public void setRin(String rin) {
        this.rin = rin;
    }
   public char seguro;
   public String rin;

    public carro(String color) {
        this.color = color;
    }

    void setMarca() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

}




package javaapplication1;

/**
 *
 * @author sistemas
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    carro mazda = new carro();
    
    mazda.setMarca();
    
        System.out.println(mazda.getMarca());
        carroVolador carro = new carroVolador();
        carro.setEsta_volando (setEsta_volando false);
        if(carro.esta_volando()){
            System.out.println("Esta volando");
            
        }
        else 
            System.out.println("No esta volando");
                    
    }
    
}


