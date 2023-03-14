# Java-Pattern
## Name: Someasvar.R
## Register Number: 212221230103
## Program 1:
```
 public class one {
 public static void main(String[] args) {
 // size of the square
 int size = 5;
 // outer loop
 for (int i = 0; i < size; i++) {
 // inner loop
 for (int j = 0; j < size; j++) {
 System.out.print("*");
 }
 System.out.println();
 }
 }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93434149/224884672-ff2a36fc-55df-43f9-8d63-abb240ac1dbe.png)

## Program 2:
```
import java.util.Scanner;
public class two
{
 public static void main(String[] args)
 {
 Scanner sc = new Scanner(System.in);
 System.out.println("Enter the number of rows: ");
 int rows = sc.nextInt();
 for (int i= 0; i<= rows-1 ; i++)
 {
 for (int j=0; j<=i; j++)
 {
 System.out.print(" ");
 }
 for (int k=0; k<=rows-1-i; k++)
 {
 System.out.print("*" + " ");
}
 System.out.println();
 }
 sc.close();
 }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93434149/224884779-d63ef82b-6783-4f96-a7b8-4c6834a6d6d9.png)
## Program 3:
```
public class three {
 public static void main(String[] args) {
 int size = 5;
 for (int i = 1; i <= size; i++) {
 for (int j = 0; j < i; j++) {
 System.out.print("*");
 }
 System.out.println();
 }
 for (int i = 1; i <= size - 1; i++) {
 for (int j = 0; j < size - i; j++) {
 System.out.print("*");
 }
 System.out.println();
 }
 }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93434149/224884870-f982cff0-0701-428e-9652-d16f29b7924b.png)
