package projectEuler;

import java.util.ArrayList;

/**
 * By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.
 *@author abhayabasnet
 */

public class problems {
	public static void main(String[] args) {

		ArrayList<Integer> numbers = new ArrayList<Integer>();
		numbers.add(1);
		numbers.add(2);
		
		
		
		for(int i = 1; i < numbers.size(); i++){
			numbers.add(numbers.get(i) + numbers.get(i-1));
			if(numbers.get(numbers.size()-1) >= 4000000){
				break;
			}
		}
		int total = 0;
		for(int j = 0; j < numbers.size(); j++){
			if(numbers.get(j) % 2 == 0){
				total += numbers.get(j);
			}
		}
		
		System.out.println(numbers);
		System.out.println(total);

	}

}
