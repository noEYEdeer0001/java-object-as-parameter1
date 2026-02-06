class sameer
{
    public void sxm(A obj)
    {
        obj.sam();
    }
    public static void main(String[] args)
    {
        sameer c = new sameer();
        c.sxm(new B());
    }
}
class A
{
    public void sam()
    {
        System.out.print("Class A");
    }
}
class B extends A
{
    public void sssm()
    {
        System.out.print("Class B");
    }
}
