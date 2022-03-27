- 👋 Hi, I’m @Ivan228Lebedev
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ivan228Lebedev/Ivan228Lebedev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.awt.Component;
import java.awt.Container;
import java.awt.Dimension;
import java.awt.GridBagConstraints;
import java.awt.GridBagLayout;
import java.awt.LayoutManager;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.JTextField;

public class Main {

private static Component b5;

public static void main(String[] args) {
// TODO Auto-generated method stub
JFrame in = new JFrame ( );

in.setVisible(true);
Dimension d=new Dimension();
d.setSize(300,500);
in.setSize(d);
in.setPreferredSize(d);
JPanel panel =new JPanel();
JTextField textField= new JTextField(10);
panel.setLayout(new  GridBagLayout());
GridBagConstraints text1= new GridBagConstraints();
text1.gridwidth=3;//обьединение по длине ячеек
text1.gridheight=1;//обьединение по высоте ячеек
text1.gridx=0;
text1.gridy=0;
//добавляем на панель поле ввода и контейнер
panel.add(textField,text1);

JButton  b7= new JButton ("7");

GridBagConstraints bc7= new GridBagConstraints();
bc7.gridwidth=1;//обьединение по длине ячеек
bc7.gridheight=1;//обьединение по высоте ячеек
bc7.gridx=0;
bc7.gridy=1;
//добавляем на панель поле ввода и контейнер
panel.add(b7,bc7);


JButton  b8= new JButton ("8");

GridBagConstraints bc8= new GridBagConstraints();
bc8.gridwidth=1;//обьединение по длине ячеек
bc8.gridheight=1;//обьединение по высоте ячеек
bc8.gridx=1;
bc8.gridy=1;
//добавляем на панель поле ввода и контейнер
panel.add(b8,bc8);


JButton  b9= new JButton ("9");

GridBagConstraints bc9= new GridBagConstraints();
bc9.gridwidth=1;//обьединение по длине ячеек
bc9.gridheight=1;//обьединение по высоте ячеек
bc9.gridx=2;
bc9.gridy=1;
//добавляем на панель поле ввода и контейнер
panel.add(b9,bc9);

JButton  b4= new JButton ("4");

GridBagConstraints bc4= new GridBagConstraints();
bc4.gridwidth=1;//обьединение по длине ячеек
bc4.gridheight=1;//обьединение по высоте ячеек
bc4.gridx=0;
bc4.gridy=2;
//добавляем на панель поле ввода и контейнер
panel.add(b4,bc4);
in.add(panel);

JButton  b5= new JButton ("5");
GridBagConstraints bc5= new GridBagConstraints();
bc5.gridwidth=1;//обьединение по длине ячеек
bc5.gridheight=1;//обьединение по высоте ячеек
bc5.gridx=1;
bc5.gridy=2;
//добавляем на панель поле ввода и контейнер
panel.add(b5,bc5);


JButton  b6= new JButton ("6");
GridBagConstraints bc6= new GridBagConstraints();
bc6.gridwidth=1;//обьединение по длине ячеек
bc6.gridheight=1;//обьединение по высоте ячеек
bc6.gridx=2;
bc6.gridy=2;
//добавляем на панель поле ввода и контейнер
panel.add(b6,bc6);


JButton  b1= new JButton ("1");
GridBagConstraints bc1= new GridBagConstraints();
bc1.gridwidth=1;//обьединение по длине ячеек
bc1.gridheight=1;//обьединение по высоте ячеек
bc1.gridx=0;
bc1.gridy=3;
//добавляем на панель поле ввода и контейнер
panel.add(b1,bc1);


JButton  b2= new JButton ("2");
GridBagConstraints bc2= new GridBagConstraints();
bc2.gridwidth=1;//обьединение по длине ячеек
bc2.gridheight=1;//обьединение по высоте ячеек
bc2.gridx=1;
bc2.gridy=3;
//добавляем на панель поле ввода и контейнер
panel.add(b2,bc2);


JButton  b3= new JButton ("3");
GridBagConstraints bc3= new GridBagConstraints();
bc3.gridwidth=1;//обьединение по длине ячеек
bc3.gridheight=1;//обьединение по высоте ячеек
bc3.gridx=2;
bc3.gridy=3;
//добавляем на панель поле ввода и контейнер

panel.add(b3,bc3);

JButton  b= new JButton (" ");
GridBagConstraints bc= new GridBagConstraints();
bc.gridwidth=1;//обьединение по длине ячеек
bc.gridheight=1;//обьединение по высоте ячеек
bc.gridx=0;
bc.gridy=4;
//добавляем на панель поле ввода и контейнер
panel.add(b,bc);

JButton  b0= new JButton ("0");
GridBagConstraints bc0= new GridBagConstraints();
bc0.gridwidth=1;//обьединение по длине ячеек
bc0.gridheight=1;//обьединение по высоте ячеек
bc0.gridx=1;
bc0.gridy=4;
//добавляем на панель поле ввода и контейнер
panel.add(b0,bc0);

JButton  by= new JButton (".");
GridBagConstraints bb= new GridBagConstraints();
bb.gridwidth=1;//обьединение по длине ячеек
bb.gridheight=1;//обьединение по высоте ячеек
bb.gridx=2;
bb.gridy=4;
//добавляем на панель поле ввода и контейнер
panel.add(by,bb);


in.add(panel);
}

}
