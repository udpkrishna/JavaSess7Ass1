# JavaSess7Ass1

package Session7_1;

import java.util.Scanner;

public class Execption {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int arr[]= {2,4,6,8,9};
		int index;
		
		System.out.println("Enter the array index to be displayed:");
		Scanner read=new Scanner(System.in);
		
		try{
					index=read.nextInt();
		System.out.println("Values is "+arr[index]+" at index "+index);
		}catch(ArrayIndexOutOfBoundsException e){
			System.out.println("Entered index is out to range !!!");
		}
	}

}
