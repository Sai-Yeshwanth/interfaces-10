
public interface A {
	private void display()
	{
		System.out.println("Im from interface A private");
	}
	public void show()
	{
		display();
		System.out.println("Im from interface A public");
	}
	public void sds();
}


class C implements A
{
	private void sds()
	{
		System.out.println("Im from interface A ");
	}
}
class Jala 
{
	public static void main(String[] args){ 
			 C c = new C();
			 c.sds();
			 c.show();
		
	}
}

