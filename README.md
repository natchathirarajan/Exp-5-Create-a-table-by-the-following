# Exp-5-Create-a-table-using-JAVA.

## AIM:
To write a java program to create a table.

## ALGORITHM: 
### Step 1:
Import the necessary packages.
### Step 2: 
Create a Class named 'Employee' which has data members.
### Step 3: 
Create methods in the class 'Employee'.
### Step 4:  
Print the details of the employees.
### Step 5: 
End the program.
## PROGRAM:

~~~
class Employee{
    String Name;
    int Year;
    String Address;
    Employee(String nam,int years, String addr)
    {
        Name=nam;
        Year=years;
        Address=addr;
    }
    void Sam()
    {
        System.out.println(Name+ "\t" +Year + "\t\t" +Address);
    }
    void Robert()
    {
        System.out.println(Name+ "\t" +Year + "\t\t" +Address);
    }
    void John()
    {
        System.out.println(Name+ "\t"+Year + "\t\t" +Address);
    }
}

public class Main
{
    public static void main(String args[])
    {
        System.out.println("Name  " + " Year of Joining " + "     Address" );
        Employee e1=new Employee("Sam", 2000, "68D-WallsStreet");
        e1.Sam();
        Employee e2=new Employee("Robert", 1994, "64C-WallsStreet");
        e2.Robert();
        Employee e3=new Employee("John", 2002, "70F-WallsStreet");
        e3.John();
    }
}
~~~

## OUTPUT:
![exp5](https://github.com/abdulwasih2003/Exp-5-Create-a-table-using-JAVA/assets/91781810/a655a34d-bc7b-4c5f-8deb-67d6256fa6d5)

## RESULT:
Thus the java program to create a table is successful.

