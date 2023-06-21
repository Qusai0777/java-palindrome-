# java-palindrome-
palindrome program--1 (21- june )


Palindrome Program in Java
Palindrome number in java: A palindrome number is a number that is same after reverse. For example 545, 151, 34543, 343, 171, 48984 are the palindrome numbers. It can also be a string like LOL, MADAM etc.

*Palindrome number algorithm*

-Get the number to check for palindrome
-Hold the number in temporary variable
-Reverse the number
-Compare the temporary number with reversed number
-If both numbers are same, print "palindrome number"
-Else print "not palindrome number"


Let's see the palindrome program in java. In this java program, we will get a number variable and check whether number is palindrome or not.

*CODE*
public class pi {
public static void main(String[] args){
int num=8558;
int rev=0;
int temp=num;

while(num>0)
{
int last =num%10;
rev=(rev*10)+last;
num=num/10;
}
if (temp==rev)
{
System.out.println("It is a palindrome number");
}
else 
{
System.out.println("It is not a palindrome nymber");
}
}
}

 OUTPUT:
 It is a palindrome number

