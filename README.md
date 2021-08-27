# Employee-details
Java code to print the employee details
import java.util.*;
class employee
{
     private String employeid;
     private String empname;
     private String empplace;
     public void read()
     {
        Scanner scan= new Scanner(System.in);
        System.out.println("Enter the employee id");//taking all the inputs from the user
        employeid=scan.next();
        System.out.println("Enter the employee name");
        empname=scan.next();
        System.out.println("Enter the place of an employee");
        empplace=scan.next();
        
     }
      public void display()  //displaying the calculating parameters
     {
        System.out.println("Employeeid  :  "+employeid+"n"+"Employename  :  "+empname+"n"+"Employee place :  "+empplace);
     }
 
}
class main //main function
{
     public static void main(String args[])
     {
         employee employeobj=new employee();
         employeobj.read(); //calling read function
         employeobj.display(); //calling display function
     }
}
