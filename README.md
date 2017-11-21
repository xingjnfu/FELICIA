# FELICIA
package T20171025;
//if语句  switch语句
import java.util.Scanner;

public class T20171025 {
	public static void main(String[] args) {
		//if
		Scanner scanner = new Scanner(System.in);
		System.out.println("Input:");
		int num  =2;
		if(num==1)
			System.out.println("Monday");
		else if(num==2)
			System.out.println("Tuesday");
		else
			System.out.println("nono");
		
		//if else if
		int x = 12;
		if(x>12||x<1)
			System.out.println(x+"no month");
		else if(x>=3 && x<=5)
			System.out.println("spring");
		else if(x>=6 && x<=8)
			System.out.println("summer");
		else if(x>=9 && x<=11)
			System.out.println("fall");
		else 
			System.out.println("winter");
	
		
		//swith
		int y = 2;
		switch(y) {
		case 4:
			System.out.println("a");
			break;
		case 5:
			System.out.println("b");
			break;
		case 6:
			System.out.println("c");
			break;
		default:
			System.out.println("d");
			break;
		}
		System.out.println("hello");
		
		
		//while
		int z = 1;
		while(z<=10) {
			System.out.println("z="+z);
			z++;
		}
		//do while\for\while
		int[] score = {90,80,70,60,50};
		int sum1= 0,sum2 = 0,sum3 = 0,i;
		for(i=0;i<score.length;i++)
			sum1 = sum1 + score[i];
		i = 0;
		while(i<score.length) {
			sum2 = sum2 + score[i];
			i++;
		}
		i = 0;
		do {
			sum3 = sum3 + score[i];
			i++;
		}
		while(i<score.length);
		System.out.println("sum1="+sum1+"sum2="+sum2+"sum3="+sum3);
	}
	

}
