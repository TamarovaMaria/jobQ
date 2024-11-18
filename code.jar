import java.awt.*;
import javax.swing.JFrame;
import javax.swing.*;

public class MyFrame extends JFrame {
    MyFrame(){
        JFrame frame = new JFrame();  //create a frame
        frame.setTitle("просчитался но где....");  //sets title of frame
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);  //exit out of application
        //DO_NOTHING_ON_CLOSE - window wont be able to close
        //HIDE_ON_CLOSE - defolt, frame will not stop working
        frame.setResizable(false);  //prevent frame from being resize
        frame.setSize(420,420); //sets the x-dimension and the y-dimension of frame

        ImageIcon photo = new ImageIcon("download.png"); //create an image icon
        frame.setIconImage(photo.getImage());  //change icon
        frame.getContentPane().setBackground(new Color(0x6327281));  //change background color
        //(new Color(r,g,b); from 0 to 255
        //(new Color(0x123456);
        frame.setVisible(true);  //make frame visible
    }
}
