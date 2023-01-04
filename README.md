# adani-group-assessment


1. Write a function to create a 2-D List/Array with random integers between 0 to 100. This function should take two arguments - numberOfRows and numberOfColumns and return 2D list.
->

import java.util.*;
public class MyClass {
    public static void main(String args[]) {
        Scanner kb = new Scanner(System.in);
        int Rows = kb.nextInt();
        int Columns = kb.nextInt();
      int newMatrix [][] = new int[Rows][Columns];
      Random rand = new Random();
      for(int i=0;i<Rows;i++)
      for(int j=0;j<Columns;j++)
      newMatrix[i][j]=rand.nextInt(100);
       for(int i=0;i<Rows;i++){
      for(int j=0;j<Columns;j++){
      System.out.print(newMatrix[i][j]+" ");
      }
      System.out.println();
       }
    }
}



