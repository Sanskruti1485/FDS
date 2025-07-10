/*class Additon
{
    public static void main(String[] args)
    {
        int a = 4;
        int b = 5;
        int c = a+b;

        System.out.print(c);
    }
}*/
/*public class Array 
{
    public static void main(String[] args)
    {
        
        int n = 5;
        int[] arr = {10,20,30,40,50};

        for(int i = 0; i<n; i++)
        {
            System.out.print(arr[i] + " ");
        }
    }
}*/
/*import java.util.Scanner;
 class Array
 {
     public static void main(Strings[] args)
     {
         Scanner sc = new Scanner(System.in);
         System.out.print(Enter the no. of elements:);
         int n = sc.nextInt();
         
         int[]arr = new int[n];
          System.out.println("Enter " + n + " elements:");
        for(int i = 0; i < n; i++)
        {
            arr[i] = sc.nextInt();
        }
        System.out.println("Array elements are:");
        for(int i = 0; i < n; i++)
        {
           System.out.print(arr[i] + " ");
        }
        sc.close();
        
     }
 }*/
 /*import java.util.Scanner;
   class EvenOdd
   {
     public static void main(String[] args)
     {
        Scanner scanner = new Scanner(System.in);   

        System.out.print("Enter a number: ");
        int n = scanner.nextInt();
        
         if(n % 2 == 0)
         {
             System.out.print("number is even");
         }
         else
         {
              System.out.print("number is odd");
         }
     }
 }*/
 import java.util.Scanner;

class Multiplication {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);   

        System.out.print("Enter a number: ");
        int n = scanner.nextInt();
        
        for (int i = 1; i <=10; i++) {
            System.out.println(n + " x " + i + " = " + (n * i));
        }

        scanner.close();
    }
}
  
