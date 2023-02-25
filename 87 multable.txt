import java.util.Scanner;
class multable{
public static void main(String args[])
{
Scanner input=new Scanner(System.in);
int m= input.nextInt();
int n= input.nextInt();
for(int i=1;i<=n;i++)
System.out.println(m+"*"+i+"="+m*i);
}
}