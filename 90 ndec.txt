import java.util.Scanner;
public class binary
{
public static void main(String[] args)
{
int dec=15;
String bin=Integer.toBinaryString(dec);
String oct=Integer.toOctalString(dec);
System.out.println("Binary number = "+bin);
System.out.print("octal number = "+oct);
}
}
