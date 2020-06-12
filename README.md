# assignment1.day2bpackage week1.day2;

import java.util.Arrays;

public class LengthOfTheString {

	public static void main(String[] args) {
		
		String text1 = "stops" ;
		String text2 = "potss" ;
		//char ch;
		
		System.out.println("The length of string1:..."+ text1.length());
		System.out.println("The length of string1:..."+ text2.length());
		System.out.println(text2.contentEquals(text1));
		
		char[] charArray1 = text1.toCharArray();
		char[] charArray2 = text2.toCharArray();
		for(int i=0;i<charArray1.length;i++) {
		System.out.println("Character of String1:"   +charArray1[i]);
			
		}
		for(int j=0;j<charArray2.length;j++) {
			System.out.println("Character of String2:"   +charArray1[j]);		
	    }
		
	Arrays.sort(charArray1);
     System.out.println("Sorting of Array1:");
	 for(char ch1:charArray1){
	       System.out.println(ch1);
	 }   
   Arrays.sort(charArray2);
   
	System.out.println("Sorting of Array2:");
	   	 for(char ch2:charArray2){
	   	     System.out.println(ch2);
	   	 }
	
System.out.println("check both the strings are equal:"+text1.contentEquals(text2));
		
		
		
		
		
		}
	
		
		
		
	 }
