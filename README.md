# EXPERIMENT-1 JAVA PROGRAM TO PRINT THE DETAILS OF THE THREE EMPLOYEES.

# AIM:
  To write a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'. 

# ALGORITHM:
  1. Create a class called 'Emp' and store employee's name, joining year and address.
  2. Create a class called 'Main' and object to store the values.
  3. Now store the three employees detrails in the created object.
  4. Print the details of the employees.
  
# PROGRAM:

  public class Main
  {
    public static void main(String[] args)
    {
        Emp emp1=new Emp();
        Emp emp2=new Emp();
        Emp emp3=new Emp();
        emp1.Name="Robert";
        emp1.year=1994;
        emp1.Address="64-C Walls Street";
        emp2.Name="Sam";
        emp2.year=2000;
        emp2.Address="68-D Walls Street";
        emp3.Name="John";
        emp3.year=1999;
        emp3.Address="26-B Walls Street";
        System.out.println("Name\t\tYear of joining\t\tAddress");
        System.out.println();
        System.out.println(emp1.Name+"\t\t\t"+emp1.year+"\t\t"+emp1.Address);
        System.out.println(emp2.Name+"\t\t\t\t"+emp2.year+"\t\t"+emp2.Address);
        System.out.println(emp3.Name+"\t\t\t"+emp3.year+"\t\t"+emp3.Address);
    }
  }
  
  public class Emp
  {
    String Name;
    int year;
    String Address;
  }
  
# OUTPUT:
  
  <img width="410" alt="java ep 5" src="https://github.com/divvisha/TABLE-CREATION/assets/127508123/befd924d-f416-43ee-92f3-ebba227c757f">

# RESULT:
  Java program to print the details of the three employees has been created and executed successfully.

  
