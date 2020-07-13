package swingDemo;

import java.awt.FlowLayout;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JTextField;

public class FrameDemo
{
	JFrame jf;
	JLabel lblName,lblpassword;
	JTextField txtName, txtPassword;
	JButton btnSubmit;
	
	public FrameDemo()
	{
		jf=new JFrame("Login Frame: ");
		lblName=new JLabel("UserName: ");
		lblpassword=new JLabel("Password: ");
		txtName=new JTextField(20);
		txtPassword=new JTextField(20);
		btnSubmit=new JButton("Submit");
		
		jf.add(lblName);
		jf.add(txtName);
		jf.add(lblpassword);
		jf.add(txtPassword);
		jf.add(btnSubmit);
		
		jf.setSize(400, 400);
		jf.setLayout(new FlowLayout());
		jf.setVisible(true);
		jf.setDefaultCloseOperation(1);
	}
	public static void main(String[] args) 
	{
		new FrameDemo();
	}
}

