import java.util.Scanner;
class present{
public static void main(String args[])
{
Scanner input=new Scanner(System.in);
String str=input.nextLine();
char c=input.next().charAt(0);
char arr[]=new char[str.length()];
int len=str.length();
int x=0;
for(int i=0;i<len;i++)
{
 arr[i]=str.charAt(i);
 if(arr[i]==c)
 {
 System.out.println(c+" is found in string at index: "+(i+1));
 x=1;
 }
}
if(x==0)
 System.out.print("character not found");
}
}