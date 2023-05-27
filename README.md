# EXPERIMENT-5 JAVA PROGRAM TO PRINT THE DETAILS OF THE THREE EMPLOYEES.

# AIM:
  To write a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'. 

# ALGORITHM:
  1. Create a class called 'Emp' and store employee's name, joining year and address.
  2. Create a class called 'Main' and object to store the values.
  3. Now store the three employees detrails in the created object.
  4. Print the details of the employees.
  
# PROGRAM:

  public class Main<br>
  {<br>
    public static void main(String[] args){<br>
    {<br>
        Emp emp1=new Emp();<br>
        Emp emp2=new Emp();<br>
        Emp emp3=new Emp();<br>
        emp1.Name="Robert";<br>
        emp1.year=1994;<br>
        emp1.Address="64-C Walls Street";<br>
        emp2.Name="Sam";<br>
        emp2.year=2000;<br>
        emp2.Address="68-D Walls Street";<br>
        emp3.Name="John";<br>
        emp3.year=1999;<br>
        emp3.Address="26-B Walls Street";<br>
        System.out.println("Name\t\tYear of joining\t\tAddress");<br>
        System.out.println();<br>
        System.out.println(emp1.Name+"\t\t\t"+emp1.year+"\t\t"+emp1.Address);<br>
        System.out.println(emp2.Name+"\t\t\t\t"+emp2.year+"\t\t"+emp2.Address);<br>
        System.out.println(emp3.Name+"\t\t\t"+emp3.year+"\t\t"+emp3.Address);<br>
    }<br>
  }<br>
  
  public class Emp<br>
  {<br>
    String Name;<br>
    int year;<br>
    String Address;<br>
  }
  
# OUTPUT:
  
  <img width="410" alt="java ep 5" src="https://github.com/divvisha/TABLE-CREATION/assets/127508123/befd924d-f416-43ee-92f3-ebba227c757f">

# RESULT:
  Java program to print the details of the three employees has been created and executed successfully.

  
