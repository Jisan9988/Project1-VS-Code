// Project1-VS-Code


import java.awt.Color;
import javax.swing.*;;

public class Main{

   public static void main(String []args){

      JFrame frame = new JFrame();
      frame.setTitle("Jisan X Programming");
      frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
      frame.setResizable(false);
      frame.setSize(420,420);
      frame.setVisible(true);

      ImageIcon image = new ImageIcon("IMG-20250521-WA0003.jpg");
      frame.setIconImage(image.getImage());
      frame.getContentPane().setBackground(new Color(123,50,250));
      
      

   }
  


}
