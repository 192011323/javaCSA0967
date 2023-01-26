import java.util.Scanner;
class skipping{
public static void main(String args[])
{
Scanner input = new Scanner(System.in);
int m=input.nextInt();
int n=input.nextInt();
int k=input.nextInt();
for(int i=m;i<=n;i=i+k+1)
{
 System.out.print(i+" ");
}
}}
