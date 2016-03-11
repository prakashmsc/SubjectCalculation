# SubjectCalculation
package com.java.learning;
import java.util.Scanner;

public class myFirstProgram {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		myFirstProgram myFirstProgram=new myFirstProgram();
		int d=myFirstProgram.add();
		System.out.println("d value is"+d);
		myFirstProgram.subtract(d,10);
		
		

	}

	private void subtract(int d, int i) {
	int c=d-i;
	System.out.println(c);
		
}

	private int add() {
		int total=0;
		System.out.println("How many students");
		Scanner s=new Scanner(System.in);
		int studentsCount=s.nextInt();
		for(int i=1;i<=studentsCount;i++)
		{
			System.out.println("How many subjects for"+i+"student");
			int subjectsCount= s.nextInt();
			for(int j=0;j<subjectsCount;j++)
			{
				// total=total+subjectsCount;
				//System.out.println("Total for"+i+"Student is"+total);
				
			}
		}
		for(int count=0;count<2;count++)
		{
			//Scanner s=new Scanner(System.in);
			System.out.println("Enter the English marks");
			int english=s.nextInt();
			System.out.println("Enter the Tamil marks");
			int tamil=s.nextInt();
			System.out.println("Enter the Maths marks");
			int maths=s.nextInt();
			System.out.println("Enter the Science Marks");
			int science=s.nextInt();
			System.out.println("Enter the Social Marks");
			int social=s.nextInt();
			total=english+tamil+maths+science+social;
			System.out.println("t0"
					+ "he total marks is" + total);
		}
		return total;
	}
}
			


