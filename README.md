# Assignment-2.6

1.


      import java.util.Scanner;
      public class acad {
      public static void main(String args[])
      {
	    StringBuffer sb1 = new StringBuffer();
		  StringBuffer sb2 = new StringBuffer();
		  Scanner sc =new Scanner(System.in);
		  int x = sc.nextInt(); //Accepting value from user
	  	int y =sc.nextInt();  //Accepting value from user
		  for (int i = x; i <=y; i++) {
			if(i%2==0)
			{
				sb1.append(i); //adding even numbers to String Buffer sb1
				sb1.append(" ");
			}
			else
			{
				sb2.append(i); //adding odd numbers to String Buffer sb2
				sb2.append(" ");
			}
      }
		  System.out.println("The even number are");
		  System.out.println(sb1.toString());
		  System.out.println("The odd number are");
		  System.out.println(sb2.toString());
	    }
      }





2.

    import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();                      //accepting the number from user
    System.out.println("Input: "+n);
    System.out.println("O/p:");
    for(int i=1;i<=10;i++){
    System.out.println(n+" * "+i+" = "+(n*i));     //displaying
    }
    } 
    }
    
    
3.

    import java.util.Scanner;
    public class acad {
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    int x=sc.nextInt();       //Accepting number from the user
    int y=sc.nextInt();       //Accepting number from the user
    int z=sc.nextInt();       //Accepting number from the user
    sum(x,y);
    sum(x,y,z);
    } // method overloading 
    public static void sum(int x,int y)
    {
	  int sum=x+y; 
    System.out.println("Sum of first 2 numbers is:"+sum);
    }
    public static void sum(int x,int y,int z)
    { 
	  int sum=x+y+z; 
	  System.out.println("Sum of all 3 numbers is:"+sum);
	  }
    }
