import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
         Scanner sc = new Scanner(System.in); 
        int rows = sc.nextInt();
        for (int i= rows; i>= 1; i--)
        {
        for (int j=rows; j>i;j--)
        {
        System.out.print(" ");
        }
        for (int k=1;k<=i;k++)
        {
        System.out.print("*");
        }
        System.out.println("");
        }
            sc.close();
    }
}
