# reverse-of-an-array
package firstproject;
import java.util.Scanner;
public class Reverse {
public static void main(String args[]) {
	int size,i;
	Scanner input=new Scanner(System.in);
	System.out.println("Enter size of an array=");
	size=input.nextInt();
	int a[]=new int[size];
	for(i=0;i<size;i++) {
		a[i]=input.nextInt();
	}
	System.out.println("Printing an element=");
	for(i=0;i<size;i++) {
		System.out.println(a[i]+ " ");
	}
	System.out.println("Reverse order of an elemnt=");
	for(i=size-1;i>=0;i--) {
		System.out.println(a[i]+ " ");
	}
}
