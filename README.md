# mainmap
import javax.swing.JFrame;
#window.java
public class Window extends JFrame {
 
    public Window() {
 
        setTitle("Project");
        setSize(500, 400);
        setLocationRelativeTo(null);
        setDefaultCloseOperation(EXIT_ON_CLOSE);
        setResizable(false);
        setVisible(true);
        Panel panel = new Panel(); // Another class
        add(panel);
 
    }
 
    public static void main (String args []){
         
        Window test = new Window();
    }
 
}
