# java_assignment1

/*
 * Name: Simrandeep Singh
 * Student no. : 200382939
 * Assignment : 1
 */
package lab.week2;
import java.util.Scanner;
 
/**
 *
 * @author Pawandeep
 */
public class LabWeek2 {

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
  String app1,app2,app3;  
  
  Scanner app = new Scanner(System.in);


System.out.print("1.Enter the one of your favourite app:"); 
app1 = app.nextLine(); 

System.out.print("2.Enter the one of your favourite app:"); 
app2 = app.nextLine();

System.out.print("3.Enter the one of your favourite app:"); 
app3 = app.nextLine(); 

System.out.print("Your favourite apps are:" + " " + app1 + ", " + app2 + " and " + app3); 
  }
}
    

