
public class Main{

    public static void main(String[] args) {
 
        Persona persona= new Persona();
 
        persona.setNombre ("luis");
        String nombre =persona.getNombre();
        System.out.println(nombre);
 
        persona.setEdad(35);
        int edad=persona.getEdad();
        System.out.println(edad);
 
        persona.setTelefono(1156534122);
        int telefono =persona.getTelefono();
        System.out.println(telefono);
        
    }
 }
 
    class Persona{
 
       private int edad;
       private int telefono;
       private String nombre;
   
    public void setEdad(int edad ){
       this.edad= edad;
    }
    public int getEdad(){
       return edad;
    }
 
 
    public void setNombre( String nombre){
       this.nombre = nombre;
    }
    public String getNombre(){
       return nombre ;
    }
    public void setTelefono(int telefono){
       this.telefono= telefono;
    }
    public int getTelefono(){
       return telefono;
 }
    
 
    }
