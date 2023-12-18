# Assignment-Day1

1)create a java program to print welcome message. 

		classname:HelloWorld

	Sample Output:Welcome To Java World
 class HelloWorld
{
    public static void main(String args[])
    {
        System.out.println("Welcome To Java World");
    }
}
2)Write a Java Program to Print whether two number's are equal or not 
		classname:Variables_Example 
		variableNames:
					number1,number2,result
		i)Sample Input :number1=12,number2=13	
		  Sample Output:number1 and number2 values are not equal 

		ii)Sample Input :number1=100,number2=100
		   Sample Output:number1 and number2 values are  equal 	
i)class Variables_Example{
public static void main(String args[]) {
          int number1=12;
          int number2=13;
          if (number1==number2)
          {
           System.out.println("numbers are equal");
          }
          else
          {
              System.out.println("numbers are not equal");
          }
    }
}
ii) class Variables_Example{
public static void main(String args[]) {
          int number1=100;
          int number2=100;
          if (number1==number2)
          {
           System.out.println("numbers are equal");
          }
          else
          {
              System.out.println("numbers are not equal");
          }
    }
}
