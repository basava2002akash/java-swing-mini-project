# java-swing-mini-project
airline system layout page using java swing components
import java.awt.*;  
import java.awt.event.*; 
import javax.swing.*; 

class Project extends JFrame implements ActionListener{    
         JTextField jd1,dt1,fn1,fr1,to1,class1,charge1,na1,nc1,f1,f2,f3,f4,f5,l1,l2,l3,l4,l5,a1,a2,a3,a4,a5,g1,g2,g3,g4,g5;
         JLabel fd,jd,dt,fn,fr,to,classl,charge,pd,na,nc,f,l,a,g,m; 
         JLabel fd9,jd9,dt9,fn9,fr9,to9,classl9,charge9,pd9,na9,nc9,f9,l9,a9,g9,s9,pf1,pf2,pf3,pf4,pf5; 
         JButton con;

Project(){

        fd=new JLabel(); 
        fd.setText("Flight Details");
        fd.setBounds(50,50,200,40);
        jd=new JLabel(); 
        jd.setText("Journey Date");
        jd.setBounds(50,100,150,20);
        jd1=new JTextField();  
        jd1.setBounds(150,100,150,20);
        dt=new JLabel(); 
        dt.setText("Departure Time");
        dt.setBounds(50,150,150,20);
        dt1=new JTextField();  
        dt1.setBounds(150,150,150,20);  
        fn=new JLabel(); 
        fn.setText("Flight number");
        fn.setBounds(50,200,150,20);
        fn1=new JTextField();  
        fn1.setBounds(150,200,150,20);
        fr=new JLabel(); 
        fr.setText("From");
        fr.setBounds(50,250,150,20);
        fr1=new JTextField();  
        fr1.setBounds(150,250,150,20);
        to=new JLabel(); 
        to.setText("To");
        to.setBounds(50,300,150,20);
        to1=new JTextField();  
        to1.setBounds(150,300,150,20);
        classl=new JLabel(); 
        classl.setText("Class");
        classl.setBounds(50,350,150,20);
        class1=new JTextField();  
        class1.setBounds(150,350,150,20);
        charge=new JLabel(); 
        charge.setText("Charge");
        charge.setBounds(50,400,150,20);
        charge1=new JTextField();  
        charge1.setBounds(150,400,150,20);   
        con=new JButton("CONFIRM");  
        con.setBounds(50,450,95,30);

        pd=new JLabel();
        pd.setText("Passenger details");
        pd.setBounds(500,50,200,40);

        na=new JLabel();
        na.setText("No of adults");
        na.setBounds(500,100,200,40);
        na1=new JTextField();  
        na1.setBounds(580,100,30,40);


        nc=new JLabel();
        nc.setText("No of child");
        nc.setBounds(630,100,200,40);
        nc1=new JTextField();  
        nc1.setBounds(700,100,30,40);

        f=new JLabel();
        f.setText("First name");
        f.setBounds(500,150,200,40);
        f1=new JTextField();  
        f1.setBounds(500,200,150,30);
        f2=new JTextField();  
        f2.setBounds(500,250,150,30);
        f3=new JTextField();  
        f3.setBounds(500,300,150,30);
        f4=new JTextField();  
        f4.setBounds(500,350,150,30);
        f5=new JTextField();  
        f5.setBounds(500,400,150,30);


        l=new JLabel();
        l.setText("last name");
        l.setBounds(670,150,200,40);

        l1=new JTextField();  
        l1.setBounds(670,200,150,30);
        l2=new JTextField();  
        l2.setBounds(670,250,150,30);
        l3=new JTextField();  
        l3.setBounds(670,300,150,30);
        l4=new JTextField();  
        l4.setBounds(670,350,150,30);
        l5=new JTextField();  
        l5.setBounds(670,400,150,30);

        a=new JLabel();
        a.setText("age");
        a.setBounds(840,150,200,40);

        a1=new JTextField();  
        a1.setBounds(840,200,40,30);
        a2=new JTextField();  
        a2.setBounds(840,250,40,30);
        a3=new JTextField();  
        a3.setBounds(840,300,40,30);
        a4=new JTextField();  
        a4.setBounds(840,350,40,30);
        a5=new JTextField();  
        a5.setBounds(840,400,40,30);


        g=new JLabel();
        g.setText("gender");
        g.setBounds(890,150,200,40);

        g1=new JTextField();  
        g1.setBounds(890,200,40,30);
        g2=new JTextField();  
        g2.setBounds(890,250,40,30);
        g3=new JTextField();  
        g3.setBounds(890,300,40,30);
        g4=new JTextField();  
        g4.setBounds(890,350,40,30);
        g5=new JTextField();  
        g5.setBounds(890,400,40,30);
       
        m=new JLabel();
        m.setText("MEALS");
        m.setBounds(500,450,40,40);

       JCheckBox rb1=new JCheckBox();
       rb1.setText("yes");
      rb1.setBounds(560,450,60,40);
     JCheckBox rb2=new JCheckBox();
     rb2.setText("no");
   rb2.setBounds(620,450,40,40);



fd9=new JLabel();
fd9.setText("Flight ticket");
 fd9.setBounds(50,500,200,40);
jd9=new JLabel();
jd9.setText("Journey Date");
        jd9.setBounds(50,550,150,20);
       
        dt9=new JLabel(); 
        dt9.setText("Departure Time");
        dt9.setBounds(50,600,150,20);
          
        fn9=new JLabel(); 
        fn9.setText("Flight number");
        fn9.setBounds(50,650,150,20);
        
        fr9=new JLabel(); 
        fr9.setText("From");
        fr9.setBounds(50,700,150,20);
        
        to9=new JLabel(); 
        to9.setText("To");
        to9.setBounds(50,750,150,20);
        
        classl9=new JLabel(); 
        classl9.setText("Class");
        classl9.setBounds(50,800,150,20);
        
        charge9=new JLabel(); 
        charge9.setText("Charge");
        charge9.setBounds(50,850,150,20);


        pd9=new JLabel();
        pd9.setText("Passenger details");
        pd9.setBounds(500,500,200,40);


        f9=new JLabel();
        f9.setText("First name");
        f9.setBounds(500,550,200,40);


        l9=new JLabel();
        l9.setText("last name");
        l9.setBounds(570,550,200,40);



        a9=new JLabel();
        a9.setText("age");
        a9.setBounds(640,550,200,40);
         
        g9=new JLabel();
        g9.setText("gender");
        g9.setBounds(700,550,200,40);
  
        pf1=new JLabel();
        pf1.setText("1.");
        pf1.setBounds(500,600,200,40);

        pf2=new JLabel();
        pf2.setText("2;");
        pf2.setBounds(500,650,200,40);

     pf3=new JLabel();
        pf3.setText("3.");
        pf3.setBounds(500,700,200,40);

     pf4=new JLabel();
        pf4.setText("4.");
        pf4.setBounds(500,750,200,40);

     pf5=new JLabel();
        pf5.setText("5.");
        pf5.setBounds(500,800,200,40);

        s9=new JLabel();
        s9.setText("seat no");
        s9.setBounds(770,550,200,40);
JButton b1=new JButton();
b1.setText("AIRLINE RESEERVATION SYSTEM");
  
con.addActionListener(this);

add(pd9);
add(f9);
add(l9);
add(a9);
add(g9);
add(s9);
add(rb1);
add(rb2);
add(pf1);
add(pf2);
add(pf3);
add(pf4);
add(pf5);

add(b1,BorderLayout.NORTH);

      add(m);
        add(fd);
        add(jd);
        add(jd1);
        add(dt);
        add(dt1);
	  add(fn);
        add(fn1);
        add(fr);
        add(fr1);
        add(to);
        add(to1);
        add(classl);
        add(class1);
        add(charge);
        add(charge1);
        add(con);
        add(pd);
        add(na);
        add(na1);
        add(nc);
        add(nc1);
        add(f);
       add(l);
       add(a);
        add(g);
       add(f1);
add(f2);
add(f3);
add(f4);
add(f5);

 add(l1);
add(l2);
add(l3);
add(l4);
add(l5);
add(a1);
add(a2);
add(a3);
add(a4);
add(a5);


add(g1);
add(g2);
add(g3);
add(g4);
add(g5);
add(fd9);
add(jd9);
add(dt9);
add(fn9);
add(fr9);
add(to9);
add(classl9);
add(charge9);

        setSize(1000,1000);  
        //setLayout(true);  
        setVisible(true);  
           
}
public void actionPerformed(ActionEvent e){  
   String s=jd1.getText(); 
   jd9.setText("Journey Date-"+" "+s);
   String s1=dt1.getText(); 
   dt9.setText("Departure Time-"+" "+s1);
  String s2=fn1.getText(); 
   fn9.setText("Flight number-"+" "+s2);
  String s3=fr1.getText(); 
   fr9.setText("From-"+" "+s3);
  String s4=to1.getText(); 
   to9.setText("To-"+" "+s4);
  String s5=class1.getText(); 
   classl9.setText("Class-"+" "+s5);


String s7=f1.getText(); 
String s8=l1.getText();
String s9=a1.getText(); 
String s10=g1.getText();  
  pf1.setText("1-"+s7+"    "+s8+"     "+s9+"   "+s10+"   "+"s7");



String s11=f2.getText(); 
String s12=l2.getText();
String s13=a2.getText(); 
String s14=g2.getText();  
  pf2.setText("2-"+s11+"    "+s12+"     "+s13+"   "+s14+"   "+"s8");



String s15=f3.getText(); 
String s16=l3.getText();
String s17=a3.getText(); 
String s18=g3.getText();  
  pf3.setText("3-"+s15+"    "+s16+"     "+s17+"   "+s18+"   "+"s9");

String s19=f4.getText(); 
String s20=l4.getText();
String s21=a4.getText(); 
String s22=g4.getText();  
  pf4.setText("4-"+s19+"    "+s20+"     "+s21+"   "+s22+"   "+"s10");
String s23=f1.getText(); 
String s24=l1.getText();
String s25=a1.getText(); 
String s26=g1.getText();  
  pf5.setText("5-"+s23+"    "+s24+"     "+s25+"   "+s26+"   "+"s11");


   System.out.println(s);

   
  
}  
public static void main(String args[]){  
  new Project();  
}  
}  
