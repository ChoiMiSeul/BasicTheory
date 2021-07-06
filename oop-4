1. 캡슐화
public class AnimalTest { //animal 관련 기능을 모아둔 클래스
	private String animalSounds;
	
	public AnimalTest(String animalSounds) {
		this.animalSounds = animalSounds;
	}
	
	public String getAnimalSounds() {
		return animalSounds;
	}
}


2. 상속
class Dog{
	String sounds = "멍멍";
}

class GoldenRetriever extends Dog{
	private final String name = "Ho";
	
	void bark() {
		System.out.println(name + "는 "+sounds+"이라고 짖는다.");
	}
}

class Pomeranian extends Dog{
	private final String name = "seng";
	
	void bark() {
		System.out.println(name + "은 "+sounds+"이라고 짖는다.");
	}
}

public class AnimalTest { //animal 관련 기능을 모아둔 클래스
	public static void main(String[] args) {
		GoldenRetriever gr = new GoldenRetriever();
		gr.bark();
		
		Pomeranian pome = new Pomeranian();
		pome.bark();
	}
}


3. 다형성
class Dog{
	public void GoldenRetriever(int age) {
		System.out.println(age+"세");
	}
	
	public void GoldenRetriever(String sounds) {
		System.out.println(sounds+"이라고 짖어요.");
	}
}

public class AnimalTest { //animal 관련 기능을 모아둔 클래스
	public static void main(String[] args) {
		Dog dog = new Dog();
		dog.GoldenRetriever(2);
		dog.GoldenRetriever("월월");
	}
}//overloading


4. 추상화
