# pattern
# print double pattern
You are given a number N. You need to print the pattern for the given value of N.

For N = 2 the pattern will be 
2 2 1 1
2 1

For N = 3 the pattern will be 
3 3 3 2 2 2 1 1 1
3 3 2 2 1 1
3 2 1


import java.util.*;

public class DoublePattern {


        public static void main (String args [])
    {
       Scanner sc=new Scanner(System.in);
       int num= sc.nextInt();
       int temp=num;
       for(int i=0;i<num;i++)
       {
         temp=num-i;
        for(int j=num;j>0;j--) {
            for (int k = 0; k < temp; k++) {
                System.out.print(j);
            }
        }
        System.out.println();
       }
    }
    
 # output
 5
 
5555544444333332222211111
55554444333322221111
555444333222111
5544332211
54321
}
