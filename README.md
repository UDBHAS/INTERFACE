interface A1
{
public void sum();
}

class A2 implements A1
{
public void sum()
{
int a=7,b=5;
int c=a+b;
System.out.println(c);
}
}

class Main3
{
public static void main(String X[])
{
A2 a2=new A2();
A1 a1;
a1=a2;
a1.sum();
}
}
