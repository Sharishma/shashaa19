// Java program to check for even or odd 
// using Bitwise XOR operator


class GFG
{
static boolean isEven(int n )
{
if ((n ^ 1)==n+1))
return true;
else
return false;
}
public static void main (String []args)
{
int n=10;
System.out.println(isEven(n)== true?"Even": "odd");
}
}
