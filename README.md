# javaTraining
Udemy Course

class Person {
	String name;
	int age;
	String gender;
	
	void speak() {
		for(int i=0; i<3; i++) {
			System.out.println("Hello, I'm " + name + " and "
						   + "I'm " + age + " years old.");
		}
		System.out.println("---");
	}
}


public class App {

	public static void main(String[] args) {
		Person james = new Person();
		james.name = "James";
		james.age = 27;
		james.gender = "M";
		james.speak();
				
		
		Person nicola = new Person();
		nicola.name = "Nicola";
		nicola.age = 25;
		nicola.gender = "F";
		nicola.speak();
		}	
	}
