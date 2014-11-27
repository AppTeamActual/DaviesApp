DaviesApp
=========
/**
 * 	Buchholz_Greyden
 *	Oct 22 2014 
 *	App_Team
 * 	Mr_Davies
 */

	package h;

	import java.util.Scanner;

import javax.swing.JOptionPane;
	
public class Daviesemailsorter 
	
{

	public static void main(String[] args) 
	
	
	{
		
		
		String teacher;
		teacher = JOptionPane.showInputDialog("Enter your last name:");
		
		if(teacher.equals("Davies"))
		
		{ 
			String input;
			input = JOptionPane.showInputDialog("Type in one of the following:\n"
					+ "CHV2O-1 or CHC2D-1");
		
		
		if(input.equals("CHC2D-1"))
		{
			String topic;
			JOptionPane.showInputDialog("The students in this class are:\n"
					+ "Greyden Buchholz\n"
					+ "Alp Turkmen\n"
					+ "Stuart Lillico\n"
					+ "Richard Robinson\n"
					+ "Enter the Title of assignment or topic of email");
					
			
			
		}
	}
	
	}
}
