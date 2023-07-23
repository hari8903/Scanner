package org.result;
import java.util.Scanner;
public class student {
	public static void main(String[] args) {
		Scanner s= new Scanner(System.in);
		System.out.println("enter the stud id");
		int studentid=s.nextInt();
		System.out.println("stud id is"+studentid);
		System.out.println("enter the stud name");
		String studentName=s.next();
		System.out.println("stud name is"+studentName);
		System.out.println("enter your mark1");
		short mark1=s.nextShort();
		System.out.println("mark1 is"+mark1);
		System.out.println("enter your mark2");
		short mark2=s.nextShort();
		System.out.println(" mark2 is"+mark2);
		System.out.println("enter your mark3");
		short mark3=s.nextShort();
		System.out.println("mark3 is"+mark3);
		System.out.println("enter your mark4");
		short mark4=s.nextShort();
		System.out.println("mark4 is"+mark4);
		System.out.println("enter your mark5");
		short mark5=s.nextShort();
		System.out.println("mark5 is"+mark5);
	    int total=(mark1+mark2+mark3+mark4+mark5);
	    System.out.println("total mark is"+total);
	    int average=total/5;
	    System.out.println("average mark is"+average);
	}
}
