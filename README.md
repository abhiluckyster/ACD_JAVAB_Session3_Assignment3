# ACD_JAVAB_Session3_Assignment3

import java.util.Random;
import java.util.Scanner;
public class RandomNo {
	public void genRanNum(int num)
	{
		Random rn = new Random();
		int ranNum=rn.nextInt(num)+1;
		System.out.print("Random number is "+ranNum);
	}	
	public static void main(String args[])
	{
		RandomNo rno = new RandomNo();
		System.out.println("Enter Input Number");
		Scanner number=new Scanner(System.in);
		int num=number.nextInt();
		rno.genRanNum(num);
		number.close();
	}
}
