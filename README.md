abstract class A
{
	public void display()
	{
		System.out.println("Im a normal method");
	}
	public abstract void show();  //abstract method
}
class Jala extends A{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 Jala b = new Jala();
			 b.display();
		
	}
}

