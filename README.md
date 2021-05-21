class A
{
	int a;
	A()
	{
		System.out.println("Im default constructor");
	}
	A(int a)
	{
		this();
		System.out.println("Hello");
	}
}

class Jala 
{
	public static void main(String[] args){
			 A b = new A(5);
	}
}
