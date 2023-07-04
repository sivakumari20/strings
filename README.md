# strings


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		String name ="bro";
		int result=name.length();
		char result =name.charAt(0);
		int result =name.indexOf("r");
		System.out.print(result);
	}
}
isempty

package my_first_java_Project;

public class wrapperclasses {

	public static void main(String[] args) {
		// wrapperclasses
		// TODO Auto-generated method stub
		Boolean a=true;
		Character b='@';
		Integer c=123;
		Double d=3.14;
		String e="bro";
		 if(c==123) {
			 System.out.println(" this is true");
		 }
		
		

	}

}


   package my_first_java_Project;
import java.util.ArrayList;

public class ARRAYLIST {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// ARRAY LIST -ELEMENTS CAN BE ADDED AFTER COMPLETION PHASAAE
		// STORE REFERENCE DATA TYPES
		ArrayList<String> food= new ArrayList<String>();
		food.add("pizza");
		food.add("hambur");
		food.add("noodles");
		food.set(0, "sushi");
		food.remove(1);
		//food.clear();
		
		for(int  i=0;i<food.size();i++ )
		{
			System.out.println(food.get(i));
		}
}
}

package my_first_java_Project;
import java.util.ArrayList;

public class ARRAYLIST {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// ARRAY LIST -ELEMENTS CAN BE ADDED AFTER COMPLETION PHASAAE
		// STORE REFERENCE DATA TYPES
		ArrayList<String> food= new ArrayList<String>();
		food.add("pizza");
		food.add("hambur");
		food.add("noodles");
		food.set(0, "sushi");
		food.remove(1);
		//food.clear();
		System.out.println(food);
		
		for(int  i=0;i<food.size();i++ )
		{
			System.out.println(food.get(i));
		}
}
}

[sushi, noodles]
sushi
noodles


package my_first_java_Project;
import java.util.ArrayList;//2d arraylist

public class ARRAYLIST {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// ARRAY LIST -ELEMENTS CAN BE ADDED AFTER COMPLETION PHASAAE
		// STORE REFERENCE DATA TYPES
		
		ArrayList<ArrayList<String>> grocery= new ArrayList();
		ArrayList<String> food= new ArrayList<String>();
		food.add("pizza");
		food.add("hambur");
		food.add("noodles");
		
		ArrayList<String> drink= new ArrayList<String>();
		drink.add("pepsi");
		drink.add("coke");
		drink.add("7up");
		
		ArrayList<String> veg= new ArrayList<String>();
		veg.add("pizza");
		veg.add("hambur");
		veg.add("noodles");
		
		grocery.add(veg);
		grocery.add(drink);
		grocery.add(food);
		
	System.out.println(grocery);
}
}

[[pizza, hambur, noodles], [pepsi, coke, 7up], [pizza, hambur, noodles]]


package my_first_java_Project;

public class foreach {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		// traversing technique to iterate through the elements in an aray
		// it takes less steps
		// it is less flxible
		//
		String[] boys = { "rana","prabhas","mahesh"};
		for (String i :boys) {
			System.out.println(i);
		}

	}

}

package my_first_java_Project;

import java.util.ArrayList;

public class foreach {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		// traversing technique to iterate through the elements in an aray
		// it takes less steps
		// it is less flxible
		//
		//String[] boys = { "rana","prabhas","mahesh"};
		ArrayList<String> drink= new ArrayList<String>();
		drink.add("pepsi");
		drink.add("coke");
		drink.add("7up");
		
		for (String i :drink) {
			System.out.println(i);
		}

	}

}

pepsi
coke
7up


package my_first_java_Project;

public class methods {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//method isa block that gets executed when it is called
		String name="siva";
		hello(name);

	}
	static void hello(String name) {
		System.out.print(name);
	}

}

siva

