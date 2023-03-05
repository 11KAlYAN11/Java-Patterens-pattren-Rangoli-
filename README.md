# Java-Patterens-pattren-Rangoli-

Date 02/06/2022 (Tuesday)
public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i = 1; i<=6; i++)
        {
            for(int k = 1; k<=i-1; k++)
            {
             System.out.print(" ");
             }
            for(int j = 1; j<=i ; j++)
            {
                System.out.print(" * ");
            } 
            System.out.println(); 
        }
        for(int x = 6; x >=1; x--)
        {
            for(int y = 1; y <=x-1; y++)
            {
            System.out.print(" ");
            }
            for(int z = 1; z<=x ; z++)
            {
                System.out.print(" * ");
            } 
            System.out.println(); 
        }
    }    
}


o/p:
* 
  *  *
   *  *  *
    *  *  *  *
     *  *  *  *  *
      *  *  *  *  *  *
      *  *  *  *  *  *
     *  *  *  *  *
    *  *  *  *
   *  *  *
  *  *
 *


2..)

public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i = 1; i<=5; i++)
        {
            for(int k = 1; k<= 5-i; k++)
            {
             System.out.print(" ");
             }
            for(int j = 1; j <= i ; j++)
            {
                System.out.print("*");
            } 
            System.out.println(); 
        }
       
    }    
}


o/p:
    *
   **
  ***
 ****
*****


3...)


public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i = 1; i<=5; i++)
        {
            for(int k = 1; k<= 5-i; k++)
            {
             System.out.print(" ");
             }
            for(int j = 1; j <= (i*2)-1 ; j++)
            {
                System.out.print("*");
            } 
            System.out.println(); 
        }
       
    }    
}


o/p:
    *
   ***
  *****
 *******
*********


4..)

public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i=1; i<=5; i++)
        {
            for(int j=1; j<=5 ; j++)
            {
                
                System.out.print(" *");
                if (i == 3 && j == 3)
                System.out.print("\bK");
            } 
            System.out.println(); 
        }
       
    }    
}

o/p:

 * * * * *
 * * * * *
 * * K * *
 * * * * *
 * * * * *

5..)


public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i=1; i<=5; i++)
        {
            for(int j=1; j<=5 ; j++)
            {
                
                System.out.print(" *");
                if (i ==j)
                System.out.print("\bK");
            } 
            System.out.println(); 
        }
       
    }    
}


o/p:

 K * * * *
 * K * * *
 * * K * *
 * * * K *
 * * * * K

6..)


public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i=1; i<=5; i++)
        {
            for(int j=1; j<=5 ; j++)
            {
                if (i ==1 || j ==1 || i == 5 || j ==5)
                System.out.print(" K ");
                else
                System.out.print("   ");
            } 
            System.out.println(); 
        }
       
    }    
}


o/p:
 K  K  K  K  K 
 K           K
 K           K
 K           K
 K  K  K  K  K


7..)


public class KalyanReddy
{
    public static void main(String[] args)
    {
    
        for(int i = 5; i>=1; i--)
        {
            for(int k = 1; k<= 5-i; k++)
            {
             System.out.print(" ");
             }
            for(int j = 1; j <= i ; j++)
            {
                System.out.print("*");
            } 
            System.out.println(); 
        }
       
    }    
}


o/p:
*****
 ****
  ***
   **
    *
