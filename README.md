
public interface A {
	private void display();
}


class C implements A
{
	public void display()
	{
		System.out.println("Im from interface A ");
	}
}
class Jala 
{
	public static void main(String[] args){ 
			 C c = new C();
			 c.display();
		
	}
}

