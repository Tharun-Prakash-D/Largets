Class Largest
{
public static void main(String args[])
{
Scanner scan = new Scanner (System.in);
int a=scan.nextInt();
int i=0,lar=0;
for(i=2;i<=3;i++)
{
if(a>lar)
{
lar=a;
}
a=scan.nextInt();
}
System.out.println(lar);
}
}
