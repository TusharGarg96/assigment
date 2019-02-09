# assigment

Question:-1
import java.util.Scanner;
public class digit
{
public static void main(String args[])
{
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
int r;
int sum=0;
int num=Integer.toString(n).length();
for(int i=0;i<=num;i++)
{ r=n%10;
  sum=sum+r;
n=n/10;
}
System.out.println(sum);
}
}




***********************************************************
Question:-2

import java.util.Scanner;
public class odd_even
{
public static void main(String args[])
{

Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
if (n%2!=0)
{
    System.out.println("Weird");
}
else
{
    if(n>=2 && n<=5)
    {
        System.out.println("Not Weird");
    }
    else if(n>=6 && n<=20)
    {
        System.out.println("Weird");
    }
    else if(n>20)
    {
        System.out.println("Not Weird");
}   
 }
}
}
