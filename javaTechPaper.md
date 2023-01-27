# Basic Data Types in Java
Before entering the data type first we need to understand what is data. anything that holds information about something that can be used for further work or gives us information is called data. A data type, in the Programming language is that it classified as the specific type of value a variable can hold it can be mathematical, relational, or logical.

# In Java, there are two categories of data types
  1. Primitive data types(Pre-define)
  2. Reference data types(Non-primitive)
   
# Primitive data types:

Primitive types are those which is predefined or (already defined) in Java. 
such as boolean, char, int, short, byte, long, float, double, etc.

**Examples:**
>class JavaDataTypesExample{
>    public static void main(String args[])
>    {
>    byte byteVar = 12;
>    short shortVar = 37;
>    int intVar =80;
>    long longVar =898034892149L;
>    float floatVar = 20.563423424f;
>    double doubleVar = 20.12323423423468326;
>    boolean booleanVar = true;
>    char charVar ='A';
>    System.out.println("Value Of byte Variable is       " + byteVar);
>    System.out.println("Value Of short Variable is      " + shortVar);
>    System.out.println("Value Of int Variable is        " + intVar);
>    System.out.println("Value Of long Variable is       " + longVar);
>    System.out.println("Value Of float Variable is      " + floatVar);
>    System.out.println("Value Of double Variable is     " + doubleVar);
>    System.out.println("Value Of boolean Variable is    " + booleanVar);
>    System.out.println("Value Of char Variable is       " + charVar);
>    }
>    }
**Outputs:**
> Value Of byte Variable is       12
> Value Of short Variable is      37
> Value Of int Variable is        80
> Value Of long Variable is       898034892149
> Value Of float Variable is      20.563423
> Value Of double Variable is     20.123234234234683
> Value Of boolean Variable is    true
> Value Of char Variable is       A

# Reference data types:
Non-Primitive types are those which is created by the programmer and are not defined by java. (except for String )
such as String, Array, classes, etc.

**Examples:**
>class Employee
>{
>  String name;
>  String aadhar;
>  String emailAddress;
>  int yearOfBirth;
>  }
>  class EmpDetail
>  {
>  public static void main(String[] args) {
>       Employee emp1 = new Employee(); // Reference Data type
>       emp 1.name = "Habib";
>       emp 1.aadhar = "4525-4545-4345-3423";
>       emp 1.emailAddress = "habib@abc.com";
>       Employee emp2 = new Employee(); // Reference Data type
>       emp 2.name = "Sachin";
>       emp 2. aadhar = "4563-7384-9031";
>       emp 2.yearOfBirth = 1974;
>       System.out.println("Name: " + emp 1.name);
>       System.out.println("Aadhar: " + emp 1.aadhar);
>       System.out.println("Email Address: " + emp 1.emailAddress);
>       System.out.println("Year Of Birth: " + emp 1.yearOfBirth);
>       System.out.println("Name: " + emp 2.name);
>       System.out.println("Aadhar: " + emp 2.aadhar);
>       System.out.println("Email Address: " + emp2.emailAddress);
>       System.out.println("Year Of Birth: " + emp2.yearOfBirth);
>       }
>       }     
* Here emp1 and emp2 are reference data types

# Data Structures in Java

After knowing about the primary data type let's now understand the basic data structures.
The data structure is the arrangement of data in memory.
They are essential for organizing, processing, retrieving, accessing, and storing data.
Data structures usually work together with algorithms and hold the data while algorithms solve problems using the data.

# The data structure is of 2 type
1. linear data structure
2. Non-linear data structure

**Linear data structure:** In linear data structure data elements are arranged sequentially or linearly where every element is attached to its previous and next adjacent is called a linear data structure.
for example array, stack, queue, linked list, etc. 
 
 **Let's take a look at a basic linear structure code (array code in java)**
 
 **Code:**
 
 >class Main {
 >public static void main(String[] args) {
 >// create an array
 >int[] age = {12, 4, 5, 2, 5};
 >// access each array elements
 >System.out.println("Accessing Elements of Array:");
 >System.out.println("First Element: " + age[0]);
 >System.out.println("Second Element: " + age[1]);
 >System.out.println("Third Element: " + age[2]);
 >System.out.println("Fourth Element: " + age[3]);
 >System.out.println("Fifth Element: " + age[4]);
 >}
 >}

**Output:**

>Accessing Elements of Array:
>First Element: 12
>Second Element: 4
>Third Element: 5
>Fourth Element: 2
>Fifth Element: 5

**Non-linear data structure:** In a non-linear data structure, data elements are attached hierarchically. the best example is trees, graph data structure where data is stored in the form of hierarchically

# Reference section
geeks for geeks- https://www.geeksforgeeks.org/data-types-in-java/
google- www.google.com
youtube- https://www.youtube.com/watch?v=_pfKF0TVpn4&ab_channel=DreamDot
w3schools- https://www.w3schools.com/java/java_data_types.asp#:~:text=Data%20types%20are%20divided%20into,these%20in%20a%20later%20chapter)
programiz- https://www.programiz.com/java-programming/arrays
my great learning- https://www.mygreatlearning.com/blog/data-structures-using-java/

