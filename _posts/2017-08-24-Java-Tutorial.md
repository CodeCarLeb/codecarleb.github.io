---
title:  "Java Tutorial"
image: java_large.png
tag: [Java, Tutorial]
---


*   Java is a high level, modern programming language designed in the early 1990s by sun Microsystems, and currently owned by Oracle.
*   Java programs are platform independent which means they can be run on any operating system with any type of processor as long as the Java interpreter is available on that system.
*   Java code that runs on one platform does not need to be recompiled to run on another platform, it’s called “write once, run anywhere” (WORA).

## A Hello World Program:

    class MyClass{

    public static void main(String [ ] args){

        System.out.println(“Hello World”);
    }

*   Every line of code in Java that can run should be inside a class.
*   All class names required to start with a capital letter
*   In this example, MyClass is the name of the class already created.
*   The word **Public** means that it is accessible by any other classes.
*   The word **Static** means that it is unique( the method can be run without creating an instance of the class containing the main method)
*   The word **Void** means this main method has no return value.
*   **Main** is a method where the program starts.
*   You will notice that the main method code has been moved to some spaces left. This is called indentation which used to make a program easier to read and understand.

#### Example:

```
    void test();
```

*   This code declares a method called test, which does not return anything and has no parameters.
*   The method’s parameters are declared inside the parentheses that follow the name of the method.

*   The body of the main method, enclosed in curly braces:
    
```
{
    System.out.println(“Hello World”);
}
```
    
*   The println method prints a line of text to the screen.
*   The System class and its out stream are used to access the println method.

**Note:** In java every code statement must end with a semicolon.


### Java Comments:
The purpose of including comments in a code is to explain what the code is doing. 

Java supports both single and multi-line comments. All characters that appear within a comment are ignored by the Java compiler.
*   A single-line comment starts with two forward slashes and continues until it reaches the end of the line. 
*   Java also supports comments that span multiple lines. This type of comment starts with a forward slash followed by an asterisk, and ends with an asterisk followed by a forward slash. 

For example:

```
/* This is also a comment spanning multiple lines */
```

**Note:** Java does not support nested multi-line comments. However, you can nest single-line comments within multi-line comments.

For example:

```
/* This is a single-line comment:
// A single-line comment 
 */
```

### Documentation comments :

Documentation comments are special comments that have the appearance of multi-line comments, with the difference being that they generate external documentation of your source code.

These begin with a forward slash followed by two asterisks, and end with an asterisk followed by a forward slash.

**Javadoc** is a tool which comes with JDK and it is used for generating Java code documentation in HTML format from Java source code which has required documentation in a  predefined format.

When a documentation comment begins with more than two asterisks, Javadoc assumes that you want to create a “box” around the comment in the source code. It simply ignores the extra asterisks.

For example:

```
/*************
 This is the start of a method
 ************/
```

( This will retain just the text “this is the start of a method”  for the documentation).

### Variables:

Variables store data for processing.
A variable is given a name (or identifier), such as area, age, and height. The name uniquely identifies each variable, assigning a value to the variable and retrieving the value stored.
Variable has types. Some examples:

*   **int** : for integer (whole numbers) such as 123 and - 406.
*   **double** : for floating-point or real numbers with optional decimal points and fractional parts in fixed or scientific notations, such as 3.1416, -80.44.
*   **String** : for texts such as “Hello” or “Good morning”. Text strings are enclosed within double quotes. 
*   **Char** : stands for character and holds a single character such as ‘Z’.

You can declare a variable of a type and assign it a value.

For example: string name = "David";

This creates a variable called name of type String, and assigns it the value “David”.

**Note:**  It is important to note that a variable is associated with a type, and is only capable to storing values of that particular type. For example, an int variable can store integer values, such as 123; but it cannot store real numbers such as 13.1416, or texts, such as “Hello”.


 


