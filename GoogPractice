// you can also use imports, for example:
// import java.util.*;

// you can write to stdout for debugging purposes, e.g.
// System.out.println("this is a debug message");

class Solution {

	public String solution(String S, int K) {
		String[] split = S.split("-");

		String newS = "";

		String newStr = "";

		for (int i = 0; i < split.length; i++) {
			newStr += split[i];
		}

		int counter = 0;
		for (int i = newS.length(); i < 0; i--) {
			if (counter == K) {
				newS += "-";
				newS += newStr.charAt(i);
				counter = 1;

				continue;
			} else {
				newS += newStr.charAt(i);
				counter++;

			}

		}
		return new StringBuilder(newS).reverse().toString().toUpperCase();
	}

}


//Test code below

import java.util.Arrays;

public class test {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		String S = "2-4A0r7-4k";
		int x = 4;

		String[] y = S.split("-");

		System.out.println(Arrays.toString(y));

		String newStr = "";
		for (int i = 0; i < y.length; i++) {
			newStr += y[i];
		}
		System.out.println(newStr);

		int k = 4;
		int counter = 0;
		String news = "";

		for (int i = newStr.length()-1; i >= 0; i--) {
			if(counter == k){
				news+= "-";
				news+= newStr.charAt(i);
				counter = 0;
			}else{
				news += newStr.charAt(i);
				counter++;
			}

		}
		
		
		System.out.println(new StringBuilder(news).reverse().toString().toUpperCase());

	}
}

