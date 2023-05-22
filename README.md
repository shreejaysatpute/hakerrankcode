Check this code to see how you can leave gaps between the words using make it look like table
using c feature like %-14s to give 15 spaces gap and to then add sting s to it 
and we have alos used %03d to print d and having maximum digit 3 and add 0 when needed.
System.out.printf("%-14s %03d\n",s1,x);
import java.util.Scanner;

public class Solution {

    public static void main(String[] args) {
            Scanner sc=new Scanner(System.in);
            System.out.println("================================");
            for(int i=0;i<3;i++)
            {
                String s1=sc.next();
                int x=sc.nextInt();
                //Complete this line
                
                System.out.printf("%-14s %03d\n",s1,x);
            }
            System.out.println("================================");

    }
}
