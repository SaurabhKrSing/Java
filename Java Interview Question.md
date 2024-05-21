# ` `What is Java (Just Another Virtual Accelerator) ?

è Java is a high level, class based, object-oriented programming language that is designed to have as few implementation dependencies as possible. Java is widely used programming language for coding web application.

# ` `Feature of java ?

è \* [Simple](https://www.javatpoint.com/features-of-java#Simple) \* [Object-Oriented](https://www.javatpoint.com/features-of-java#Object-Oriented) \* [Portable](https://www.javatpoint.com/features-of-java#Portable) \* [Platform independent](https://www.javatpoint.com/features-of-java#Platform-independent) \* [Secured](https://www.javatpoint.com/features-of-java#Secured) \* [Robust](https://www.javatpoint.com/features-of-java#Robust) \* [Architecture neutral](https://www.javatpoint.com/features-of-java#Architecture-neutral) \* [Interpreted](https://www.javatpoint.com/features-of-java#Interpreted)

`       `\* [High Performance](https://www.javatpoint.com/features-of-java#High-Performance) \* [Multithreaded](https://www.javatpoint.com/features-of-java#Multithreaded) \* [Distributed](https://www.javatpoint.com/features-of-java#Distributed) \* [Dynamic](https://www.javatpoint.com/features-of-java#Dynamic)

# ` `Feature of Java 20 ?

è Java 20 provides following features for Java Programming:

- Virtual Threads
- Vector API Proposal
- Structured Concurrency
- Scoped Values
- Foreign Function and Memory (FFM) API
- Record Patterns
- Pattern Matching for Switch Statement and Expressions

# ` `Feature of Java8 ?

è Java 8 provides following features for Java Programming:

- Lambda expressions,
- Method references,
- Functional interfaces,
- Stream API,
- Default methods,
- Base64 Encode Decode,
- Static methods in interface,
- Optional class,
- Collectors class,
- ForEach() method,
- Nashorn JavaScript Engine,
- Parallel Array Sorting,
- Type and Repeating Annotations,
- IO Enhancements,
- Concurrency Enhancements,
- JDBC Enhancements etc.

# ` `What is Platform ?

è Combination of Hardware and Software. Example :- i5 is a processor and Window is an OS. This is Platform.

# ` `What is Platform Independence ?

è Java designed its own complier called Java Compiler which converts HLL into byte code. This byte code is given to Java Virtual Machine (JVM) which convert it to MLL.

# ` `Why java is independent ?

è Java is considered platform-independent due to its "write once, run anywhere" principle. Java programs are compiled into bytecode that can be executed on any platform with a Java Virtual Machine (JVM). This enables developers to write code once and deploy it on various operating systems, making it independent of specific hardware or software configurations.

# ` `What is serialization ?

è Serialization is a mechanism of converting the state of an object into a byte stream.

# ` `What is deserialization ?

è Deserialization is the reverse process where the byte stream is used to recreate the actual Java object in memory.

# ` `Why we use static in Main Method in java ?

è The `static` keyword is used in the `main` method in Java for a few important reasons.

Firstly, it allows the `main` method to be access directly by the Java Virtual Machine (JVM) without requiring an instance of the class.

Secondly, it follows the convention set by Java for the entry point of a program, enabling the JVM to identify and execute it properly.

# ` `Why main method is static ?

è The `main` method in Java is declared as `static` because it needs to be accessed by the Java Virtual Machine (JVM) without creating an instance of the class. This allows the JVM to execute the program without requiring an object to be created first, making it the entry point for the application.

# ` `Why we use void in Main Method in java ?

è In Java, we use the `void` keyword in the `main` method to indicate that the method does not return any value. The `main` method is meant to initiate the program's execution and does not need to return any specific result or value.

# ` `Why we use public in Main Method in java ?

è We use the `public` access modifier in the `main` method in Java to allow the JVM to access and invoke it as the entry point for the program, ensuring its visibility and execution from outside the class.

# ` `What is Access Specifiers in Java?

è In Java, access specifiers are used to specify the access level of a class or its members (data and methods). There are four access specifiers in Java:

- public: When we declare class members as public, they are accessible from outside the class.
- private: When we declare class members as private, they are only accessible within the class and are not accessible from outside the class.
- default: When we declare class members with no access specifier is considered as default, they are only accessible within the package and are not accessible from outside the package.
- protected: When we declare class members as protected, they are only accessible by any class within the same package or by any subclasses of the parent class in which the class members are declared as protected, regardless of whether the subclass is in the same package or a different package.

Note: A package is a container that contains classes in java.

# ` `Why we use String args[] in Main Method in java ?

è In the `main` method of Java, `String args[]` is used to accept command-line arguments passed to the program. It allows the program to receive inputs or parameters from the command line and process them within the program's execution.

` `What is command line argument ?

![](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.001.png)è Command-line arguments are values that are passed to a Java program when it is run from the command line or terminal. These arguments allow you to provide input or configuration options to your Java application without having to modify the source code.

# ` `System.out.println() ? Why we use System, out and println ?

è In Java, System.out.println(); is used to print text or data to the standard output (usually the console). Here's a breakdown of each component:

1. System: This is a predefined class in Java that provides access to various system-related resources and methods. It is part of the java.lang package, so you don't need to import it explicitly.
1. out: out is a public static field (a special variable) within the System class. It is an instance of the PrintStream class, which is used for output operations.
1. println(): println is a method of the PrintStream class that is used to print a line of text to the standard output. It automatically adds a newline character after printing the specified content, so the next output appears on a new line.

# ` `What is print ?

è print function is used to display output on the console or standard output.

# ` `What is println ?

è println is short for “print line”, meaning after the argument is printed then goes to the next line.

# ` `What is printf ?

è printf is short for “print formatter”, this method is used for formatted output, allowing you to specify placeholder and format specifiers to control the appearance of the output.

` `Why pointers are not used in Java ?
è A pointer is a variable which can hold the address of another variable or object but Java does not support pointer due to security reason because if you get the address of any variable you could access it anywhere from the program without any restrictions even wherever is private.

# ` `What is byte code ?

è Bytecode is computer object code that an interpreter converts into binary [machine code](https://www.techtarget.com/whatis/definition/machine-code-machine-language) so it can be read by a computer's hardware processor. Bytecode is a highly optimized set of instructions that is executed by the Java Virtual Machine. Bytecode helps Java achieve both portability and security.

# ` `What is java compiler ?

è A compiler in Java translates the entire source code into a machine-code file or any intermediate code, and that file is then executed. It is platform-independent.

# ` `What is JDK (Java Development Kit) ?

è Java Development Kit (JDK) is a software development kit that contains the tools you need to develop Java programs. It includes the JRE, as well as a compiler, debugger, and other tools that are needed to develop Java applications. If you want to develop Java programs, you will need to install the JDK.

# ` `What is JVM (Java Virtual Machine) ?

è Java Virtual Machine (JVM) acts as a run-time engine to run Java applications. JVM is the one that actually calls the main method present in a java code. JVM is a part of JRE(Java Runtime Environment).

\# The JVM performs following operation:

Loads code

Verifies code

Executes code

Provides runtime environment

\# JVM provides definitions for the:

Memory area

Class file format

Register set

Garbage-collected heap

Fatal error reporting etc.

# ` `What is JRE (Java Runtime Environment) ?

è Java Runtime Environment (JRE) is a software package that contains everything a user needs to run a Java program. It includes the Java Virtual Machine (JVM), the Java class libraries, and the Java application launcher. The JRE is required to run a Java program, but it does not contain any development tools such as a compiler, so you cannot use it to develop Java programs.

# ` `JRE is further divided into four Segment Explain Everything ?

è Code Segment

`	`Static Segment

`	`Heap Segment

`	`Stack Segment

`    `Among these segments, memory for String is allocated on the Heap Segment.

`    `Heap Segment further consists of two pools:

1. Constant Pool
1. Non-Constant Pool

`  `Constant Pool :- Strings that are created without using new keywords are allocated memory in this pool.

`  `Duplicate are not allowed.

`  `Non-Constant Pool :- Strings that are created using new keywords are allocated memory in this pool.

`  `Duplicate are not allowed.

# ` `What is garbage collection in Java ?

è Garbage collection in Java is an automatic memory management process. It identifies and reclaims memory occupied by objects that are no longer reachable or needed by the program. This ensures efficient memory usage, prevents memory leaks, and simplifies memory management for developers.

# ` `Is java call by value or call by reference ?

è Java uses only call by value while passing reference variables as well. It creates a copy of references and passes them as valuable to the methods.

Call by Value means calling a method with a parameter as value. Through this, the argument value is passed to the parameter.

While Call by Reference means calling a method with a parameter as a reference. Through this, the argument reference is passed to the parameter.

# ` `What is Java ClassLoader ?

è Java ClassLoader is an abstract class. It belongs to a java.lang package. It loads classes from different resources. Java ClassLoader is used to load the classes at run time.

Java ClassLoader is based on three principles: Delegation, Visibility, and Uniqueness.

- Delegation principle: It forwards the request for class loading to parent class loader. It only loads the class if the parent does not find or load the class.
- Visibility principle: It allows child class loader to see all the classes loaded by parent ClassLoader. But the parent class loader cannot see classes loaded by the child class loader.
- Uniqueness principle: It allows to load a class once. It is achieved by delegation principle. It ensures that child ClassLoader doesn't reload the class, which is already loaded by the parent.

# ` `Types of ClassLoader ?

è In Java, every ClassLoader has a predefined location from where they load class files. There are following types of ClassLoader in Java:

- Bootstrap Class Loader: It loads standard JDK class files from rt.jar and other core classes. It is a parent of all class loaders. It doesn't have any parent. When we call String.class.getClassLoader() it returns null, and any code based on it throws NullPointerException. It is also called Primordial ClassLoader. It loads class files from jre/lib/rt.jar. For example, java.lang package class.
- Extensions Class Loader: It delegates class loading request to its parent. If the loading of a class is unsuccessful, it loads classes from jre/lib/ext directory or any other directory as java.ext.dirs. It is implemented by sun.misc.Launcher$ExtClassLoader in JVM.
- System Class Loader: It loads application specific classes from the CLASSPATH environment variable. It can be set while invoking program using -cp or classpath command line options. It is a child of Extension ClassLoader. It is implemented by sun.misc.Launcher$AppClassLoader class. All Java ClassLoader implements java.lang.ClassLoader.

![ClassLoader in Java](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.002.png)

# ` `What is ALL (Assemble Level Language)?

è An assembly language is a type of low-level programming language that is intended to communicate directly with a computer's hardware.

ALL are created using symbols such as letters, digits and special characters. Assembly language is an example of middle-level language. In assembly language, we use predefined words called mnemonics.

# ` `What is HLL (High Level Language) ?

è High-level languages are programming languages that are designed to allow humans to write computer programs and interact with a computer system without having to have specific knowledge of the processor or hardware that the program will run on.

Example :- Java, C, C++, Python etc.

# ` `Difference between ALL (Assemble Level Language) and HLL (High Level Language) ?

è

|            **High Level Language**            |       **Low Level Language**        |
| :-------------------------------------------: | :---------------------------------: |
|              Programmer friendly              |          Machine friendly           |
|             Less memory efficient             |       Highly memory efficient       |
|      Easy to understand for programmers       | Tough to understand for programmers |
|                Simple to debug                |   Complex to debug comparatively    |
|              Simple to maintain               |  Complex to maintain comparatively  |
|                   Portable                    |            Non-portable             |
|            Can run on any platform            |          Machine-dependent          |
| Needs compiler or interpreter for translation |   Needs assembler for translation   |
|          Widely used for programming          |  Not commonly used in programming   |

# ` `What is MLL (Machine Level Language) ?

è Low-level language is also known as Machine Level Language. Low-Level language is the only language which can be understood by the computer. The machine language contains only two symbols 1 & 0. All the instructions of machine language are written in the form of binary numbers 1's & 0's. A computer can directly understand the machine language.

# ` `Difference between return and return value ?

è "return" is a keyword used to exit a method and return control to the calling code, while "return value" refers to the actual data or object that is sent back from the method to the caller. The return value is specified after the "return" keyword and provides the result of the method's execution.

# ` `What is Datatype in java ?

è The Data type is a classification of types of data that inform the compiler or interpreter how the programmer intends to use the data.

# ` `What is Difference between Collection and Collections in java ?

è Collection vs Collections:

| `                                  `**Collection**                                                                                     | `                                          `**Collections**                |
| :------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------- |
| It is an interface.                                                                                                                    | It is a utility class.                                                     |
| It is used to represent a group of individual objects as a single unit.                                                                | It defines several utility methods that are used to operate on collection. |
| The Collection is an interface that contains a static method since java8. The Interface can also contain abstract and default methods. | It contains only static methods.                                           |

# ` `What is difference between Iterable and Iterator ?

è the main differences between the Iterable and the Iterator interfaces:

|                               **Iterable**                               |                                    **Iterator**                                     |
| :----------------------------------------------------------------------: | :---------------------------------------------------------------------------------: |
| Represents a collection that can be iterated over using a for-each loop  |        Represents an interface that can be used to iterate over a collection        |
| When implementing an Iterable, we need to override the iterator() method | When implementing an Iterator, we need to override the hasNext() and next() methods |
|                    Doesn't store the iteration state                     |                             Stores the iteration state                              |
|           Removing elements during the iteration isn't allowed           |                  Removing elements during the iteration is allowed                  |

# ` `What is Difference between Comparable and Comparator interfaces ?

èThere are many differences between Comparable and Comparator interfaces that are given below.

|                                                                     **Comparable**                                                                      |                                                                          **Comparator**                                                                           |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Comparable provides a single sorting sequence. In other words, we can sort the collection on the basis of a single element such as id, name, and price. | The Comparator provides multiple sorting sequences. In other words, we can sort the collection on the basis of multiple elements such as id, name, and price etc. |
|                                       Comparable affects the original class, i.e., the actual class is modified.                                        |                                       Comparator doesn't affect the original class, i.e., the actual class is not modified.                                       |
|                                                Comparable provides compareTo() method to sort elements.                                                 |                                                      Comparator provides compare() method to sort elements.                                                       |
|                                                       Comparable is present in java.lang package.                                                       |                                                         A Comparator is present in the java.util package.                                                         |
|                                   We can sort the list elements of Comparable type by Collections.sort(List) method.                                    |                                  We can sort the list elements of Comparator type by Collections.sort(List, Comparator) method.                                   |

# ` `Types of Datatypes in java ?

è There are two type of Data Type :

1. Primitive Data Type : The primitive data types include Boolean, char, byte, short, int, long, float and double.
1. Non-primitive Data Types : The non-primitive data types include [Classes](https://www.javatpoint.com/object-and-class-in-java), [Interfaces](https://www.javatpoint.com/interface-in-java), and [Arrays](https://www.javatpoint.com/array-in-java).

# ` `Difference between primitive datatype and non-primitive datatype ?

è # Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not

`         `defined by Java (except for String).

`     `# Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.

`     `# A primitive type has always a value, while non-primitive types can be null.

`     `# A primitive type starts with a lowercase letter, while non-primitive types start with an uppercase letter.

`     `# The size of primitive type depends upon data type, while non-primitive type has all the same size.

# ` `Size of object ?

è

|          **Data Type**          | **Size** |                                  **Description**                                  |
| :-----------------------------: | :------: | :-------------------------------------------------------------------------------: |
|             boolean             |  1 bit   |                            Stores true or false values                            |
|              byte               |  1 byte  |                       Stores whole numbers from -128 to 127                       |
|              short              | 2 bytes  |                    Stores whole numbers from -32,768 to 32,767                    |
|              char               | 2 bytes  |                 Stores a single character/letter or ASCII values                  |
|               int               | 4 bytes  |             Stores whole numbers from -2,147,483,648 to 2,147,483,647             |
|              float              | 4 bytes  |      Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits      |
|              long               | 8 bytes  | Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
|             double              | 8 bytes  |        Stores fractional numbers. Sufficient for storing 15 decimal digits        |
| Java Reference Consume 4 bytes. |          |                                                                                   |

# ` `What is Type Casting ?

è Type Casting in java is the process of converting a variable from one data type to another data type.

# ` `Type of Type Casting ?

è There are two type of type casting :

1. Implicit Typecasting (Widening or Automatic Typecasting) : This type of typecasting occurs automatically when a smaller data type is converted to a larger data type. For Example, converting an int to a long.
1. Explicit Typecasting (Narrowing or Manual Typecasting) : This type of typecasting converting larger data type to smaller data type. For Example, converting a double to an int using the (int) operator.

# ` `What is class casting ?

è Class casting in Java refers to the process of changing or converting the reference of an object from one class type to another. This is done when you have a superclass reference and want to treat it as a subclass reference.

There are two types of class casting:

1. Upcasting
1. Downcasting

# ` `What is Downcasting ?

è Downcasting is the typecasting of a parent object to a child object. Downcasting cannot be implicit.

# ` `What is Upcasting ?

è Upcasting involves casting an object from a subclass to a superclass. It is implicit and doesn't require explicit casting.

# ` `What is Operator ?

è Operators is a character that represents a specific mathematically or logically action or process this is know as operators.

# ` `Type of Operators ?

è 1. Unary Operators

2\. Arithmetic Operators

3\. Assignment Operators

4\. Logical Operators

5\. Shift Operators

6\. Bitwise Operators

7\. Ternary Operators

8\. Relational Operators

**#** **Unary Operator:** Unary operator requires only a single operand; this operator is used to increment or decrement the value, negating an expression or inverting a boolean value.

|  **Operator**   |                                                             **Description**                                                             |
| :-------------: | :-------------------------------------------------------------------------------------------------------------------------------------: |
| ++ (Increment)  | This operator is used to increment the value by 1. There are two types of increment, i.e., post-increment (a++) and pre-increment (++a) |
| — (Decrement).  |  This operator is used to decrement the value by 1. There are two types of decrement, i.e., post decrement (a–) and pre-decrement (–a)  |
|   ! (Invert)    |                                          This operator is used to invert a boolean value (!a).                                          |

` `**# Arithmetic Operator :** Arithmetic operators are used to performing addition, subtraction, multiplication, division, and modulus. It acts as a mathematical operation.

|     **Operator**      |                                             **Description**                                             |
| :-------------------: | :-----------------------------------------------------------------------------------------------------: |
|    + ( Addition )     |                         This operator is used to add the value of the operands.                         |
|   – ( Subtraction )   |         This operator is used to subtract the right-hand operator with the left hand operator.          |
| \* ( Multiplication ) |                      This operator is used to multiply the value of the operands.                       |
|    / ( Division )     |            This operator is used to divide the left-hand operator with right hand operator.             |
|     % ( Modulus )     | This operator is used to divide the left hand operator with right hand operator and returns remainder.  |

**# Assignment Operator :**  Assignment operator are used to assign new value to a variable. The left side operand of the assignment operator is called variable and the right side operand of the assignment operator is called value.

| **Operator** |                                                     **Description**                                                     |
| :----------: | :---------------------------------------------------------------------------------------------------------------------: |
|      =       |                   This operator is used to assign the value on the right to the operand on the left.                    |
|      +=      |       This operator is used to add right operand to the left operand and assigns the result to the left operand.        |
|      -=      |         This operator subtracts right operand from the left operand and assigns the result to the left operand.         |
|     \*=      |        This operator multiplies right operand with the left operand and assigns the result to the left operand.         |
|      /=      |          This operator divides left operand with the right operand and assigns the result to the left operand.          |
|      ^=      |            This operator performs exponential calculation on operators and assigns value to the left operand            |
|      %=      | This operator is used to divide the left-hand operator with right hand operator and assigns the result to left operand. |

**# Logical Operator :** Logical operators are used to combining two or more conditions or complement the evaluation of the original condition under consideration.

|   **Operator**   |                                         **Description**                                         |
| :--------------: | :---------------------------------------------------------------------------------------------: | ------------ | --------------------------------------------------------------------------------------- |
| && (Logical AND) |     This operator returns True if both the operands are true, otherwise, it returns False.      |
|                  |                                                                                                 | (Logical OR) | This operator returns True if either the operands are true, otherwise it returns False. |
| ! (Logical AND)  | This operator returns True if an operand is False. It reverses the logical state of an operand. |

**# Shift Operator :** The shift operator is used to shift the bits of a number left or right by multiplying or dividing the numbers.

|   **Operator**   |                                                   **Description**                                                   |
| :--------------: | :-----------------------------------------------------------------------------------------------------------------: |
| << (Left Shift)  | This operator left shifts the bits of the first operand; the second operand decides the number of places to shift.  |
| >> (Right Shift) | This operator right shifts the bits of the first operand; the second operand decides the number of places to shift. |

**# Bitwise Operator :** The bitwise operator operates on bit string, binary number, or bit array. It is fast and simple and directly supported by the processor. The bitwise operation is also known as bit-level programming.

|  **Operator**   |                                     **Description**                                     |
| :-------------: | :-------------------------------------------------------------------------------------: | ------------------------------------------------------------------------------------- |
| & (Bitwise AND) | This operator takes two numbers as operands and does AND on every  bit of two numbers.  |
|                 |                                      (Bitwise OR)                                       | This operator takes two numbers as operands and does OR on every  bit of two numbers. |
| ^ (Bitwise XOR) | This operator takes two numbers as operands and does XOR on every  bit of two numbers.  |
| ~ (Bitwise NOT) |  This operator takes one number as an operand and does invert all bits of that number.  |

**# Ternary Operator :** Ternary operator is a conditional operator, it reduces the line of code while performing the conditional or comparisons. It is the replacement of if-else or nested if-else statements. It is also referred to as inline if, conditional operator, or ternary if.

**Syntax :** ( Condition ) ? ( Statement1 ) : ( Statement2 );

**# Relational Operator :** Relational operator compares two numbers and returns a boolean value. This operator is used to define a relation or test between two operands.

|         **Operator**          |                                                                 **Description**                                                                 |
| :---------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: |
|         < (Less than)         |        This operator returns True, if the value of the left operand is less than the value of the right operand, else it returns False.         |
|       > (Greater than)        |       This operator returns True, if the value of the left operand is greater than the value of the right operand, else it returns False.       |
|  <= (Less than or equal to)   |  This operator returns True, if the value of the left operand is less than or equal to the value of the right operand, else it returns False.   |
| >= (Greater than or equal to) | This operator returns True, if the value of the left operand is greater than or equal to the value of the right operand, else it returns False. |
|         == (Equal to)         |                                  This operator returns True, if two operands are equal, else it returns False.                                  |
|       != (Not equal to)       |                                This operator returns True, if two operands are not equal, else it returns False.                                |

**Java Operator Precedence and Associativity**

**# Operator Precedence :** Operator precedence determines which operator is performed first in an expression if there is more than one operator with different precedence.

**# Operator Associativity :** Operator associativity is used when an expression has two operators having same precedence.

|     **Operator**     |        **Precedence**        | **Associativity** |
| :------------------: | :--------------------------: | :---------------: | ------------- | ------------- |
|       Postfix        |        expr++  expr—         |   left to right   |
|        Unary         | ++expr —expr +expr –expr ~ ! |   right to left   |
|    Multiplicative    |            \* / %            |   left to right   |
|       Additive       |             + –              |   left to right   |
|        Shift         |          << >> >>>           |   left to right   |
|      Relational      |    < > <= >= instance of     |   left to right   |
|       Equality       |            == !=             |   left to right   |
|     bitwise AND      |              &               |   left to right   |
| bitwise exclusive OR |              ^               |   left to right   |
| bitwise inclusive OR |                              |                   | left to right |
|     logical AND      |              &&              |   left to right   |
|      logical OR      |                              |                   |               | left to right |
|       Ternary        |             ? :              |   right to left   |
|      Assignment      |   = += -= \*= /= %= &= ^=    |  = <<= >>= >>>=   | right to left |

# ` `What is Loop ?

è Loop Statement are used to execute the set of instruction in a repeated order.

# ` `Type of Loop ?

è There are three type of loop :

1. For loop
1. While loop
1. Do-while loop

# ` `Difference Between for Loop - While Loop - Do-While Loop ?

è Difference between for loop vs while loop vs Do while loop :

|  **Difference**  |                                    **For Loop**                                    |                                    **While Loop**                                    |                                                                                    **Do-While Loop**                                                                                    |
| :--------------: | :--------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Introduction   |        For loop in Java iterates a given set of statements multiple times.         | The Java while loop executes a set of instructions until a boolean condition is met. | The do-while loop executes a set of statements at least once, even if the condition is not met. After the first execution, it repeats the iteration until the boolean condition is met. |
| Best time to use | Use it when you know the exact number of times to execute the part of the program. |     Use it when you don’t know how many times you want the iteration to repeat.      |                                  Use it when you don’t know how many times you want the iteration to repeat, but it should execute at least one time.                                   |
|      Syntax      |  <p>for(init; condition; icr/dcr){</p><p>//statements to be repeated</p><p>}</p>   |             <p>while(condition){</p><p>//statements to be repeated }</p>             |                                                          <p>do{</p><p>//statements to be repeated</p><p>}while(condition);</p>                                                          |
|     Example      |        <p>for(int x=0; x<=5; x++){</p><p>System.out.println(x);</p><p>}</p>        |  <p>int x=0;</p><p>while(x<=5){</p><p>System.out.println(x);</p><p>x++;</p><p>}</p>  |                                                  <p>int x=0;</p><p>do{</p><p>System.out.println(x);</p><p>x++;</p><p>}while(x<=5);</p>                                                  |

# ` `What is break statement ?

è The break statement is used to terminate the loop immediately.

# ` `What is Continue statement ?

è The continue statement is used to skip the current iteration of the loop.

# ` `What is while statement ?

è The while statement is a control flow statement used for creating loops. It repeatedly executes a block of code as long as a specified condition is true.

# ` `What is switch statement ?

è The switch statement is a control flow statement used for making decisions based on the value of an expression. It allows you to select one of several code blocks to execute based on the value of a given expression.

# ` `What is Variable ?

è A variable is a container which holds the value while the [Java program](https://www.javatpoint.com/simple-program-of-java) is executed. A variable is assigned with a data type.

# ` `Type of Variable ?

è There are three type of variable :

\1) Local Variable : A variable declared inside the body of the method is called local variable\. You can use this variable only within that method and the other methods in the class aren't even aware that the variable exists\.

A local variable cannot be defined with "static" keyword.

\2) Instance Variable : A variable declared inside the class but outside the body of the method, is called an instance variable\. It is not declared as [static](https://www.javatpoint.com/static-keyword-in-java)\.

It is called an instance variable because its value is instance-specific and is not shared among instances.

\3) Static variable : A variable that is declared as static is called a static variable\. It cannot be local\. You can create a single copy of the static variable and share it among all the instances of the class\. Memory allocation for static variables happens only once when the class is loaded in the memory\.

# ` `What is Method ?

è A method is a block of code or collection of statements or a set of code grouped together to perform a certain task or operation. It is used to achieve the reusability of code. We write a method once and use it many times. We do not require to write code again and again. It also provides the easy modification and readability of code, just by adding or removing a chunk of code. The method is executed only when we call or invoke it.

` `What is Constructor ?

è Constructor is a special method which is invoked automatically at the time of object creation. It is used to initialize the data members of new objects generally.

\# Constructors have the same name as class or structure.

\# Constructors don’t have a return type. (Not even void)

\# Constructors are only called once, at object creation.

` `Type of Constructor ?

è There can be three types of constructors in Java.

**1.** **Non-Parameterized constructor (Non-Argument Constructor) :** A constructor which has no argument is known as non-parameterized constructor(or no-argument constructor). It is invoked at the time of creating an object. If we don’t create one then it is created by default by Java.

class Student {

`   `String name;

`   `int age;

`   `Student() {

`       `System.out.println("Constructor called");

`   `}

}

**2. Parameterized constructor (Argument Constructor) :** Constructor which has parameters is called a parameterized constructor. It is used to provide different values to distinct objects.

class Student {

`   `String name;

`   `int age;

`   `Student(String name, int age) {

`       `this.name = name;

`       `this.age = age;

`   `}

}

**3. Copy Constructor :** A Copy constructor is an overloaded. constructor used to declare and initialize an object from another object. There is only a user defined copy constructor in Java(C++ has a default one too).

class Student {

`   `String name;

`   `int age;

`   `Student(Student s2) {

`       `this.name = s2.name;

`       `this.age = s2.age;

`   `}

}

**Note : -** Whenever the programmer does not provide a single constructor, then during the object creation when we call the constructor, we are basically calling the default constructor.

` `How to call parent class constructor in a child class ?

è In Java, you can call a parent class constructor in a child class using the super() keyword. This allows you to invoke a specific constructor of the parent class from the constructor of the child class.

` `Difference between Method and Constructor ?

è

|                               **Constructors**                               |                                   **Methods**                                    |
| :--------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
|  A Constructor is a block of code that initializes a newly created object.   | A Method is a collection of statements which returns a value upon its execution. |
|              A Constructor can be used to initialize an object.              |                  A Method consists of Java code to be executed.                  |
|              A Constructor is invoked implicitly by the system.              |                      A Method is invoked by the programmer.                      |
| A Constructor is invoked when a object is created using the keyword **new**. |                    A Method is invoked through method calls.                     |
|                  A Constructor doesn’t have a return type.                   |                        A Method must have a return type.                         |
|            A Constructor initializes a object that doesn’t exist.            |              A Method does operations on an already created object.              |
|         A Constructor’s name must be same as the name of the class.          |                         A Method’s name can be anything.                         |
|  A class can have many Constructors but must not have the same parameters.   |       A class can have many methods but must not have the same parameters.       |
|               A Constructor cannot be inherited by subclasses.               |                     A Method can be inherited by subclasses.                     |

` `What is constructor overloading ?

è Constructor overloading can be defined as having multiple constructors with different parameters so that every constructor can perform a different task.

` `What is default constructor ?

è A default constructor in Java is a constructor that is automatically provided by the Java compiler when a class doesn't explicitly define any constructors. This default constructor has no arguments and doesn't perform any specific initialization tasks. Its purpose is to provide a way to create objects of the class without having to specify constructor arguments.

` `What is Constructor Chaining ?

è Constructor chaining refers to the process of calling one constructor from another constructor within a class. It allows the initialization of class instances with different sets of parameters, while reusing code logic and ensuring that all necessary initialization steps are performed.

` `What is Array ?

è An array is a data structure in Java used to store multiple elements of the same type. It provides a fixed-size container that holds elements sequentially, allowing access to elements through index-based operations. Arrays are useful for organizing and manipulating collections of data efficiently.

` `Type of Array ?

è In Java, there are several types of arrays:

1\. Single-dimensional Array: It is the most common type of array that stores elements in a linear sequence.

2\. Multidimensional Array: It is an array that can store elements in multiple dimensions, such as a 2D array or a 3D array.

3\. Jagged Array: It is a multidimensional array where each row can have a different length, allowing irregularly shaped arrays.

4\. Object Array: It is an array that can store objects of any class, enabling the creation of arrays of custom objects.

5\. Primitive Array: It is an array that can store values of primitive types like int, char, boolean, etc., rather than objects.

` `What is Advantage and Disadvantage of Array ?

è Advantages of arrays: Efficient element access, memory efficiency, easy iteration.

Disadvantages of arrays: Fixed size, lack of flexibility for resizing, overhead for insertion/deletion, potential wasted memory, lack of built-in methods for common operations like sorting or searching.

` `What is String ?

è String is a class that represents a sequence of characters. It is widely used for storing and manipulating textual data. Strings are immutable, meaning their values cannot be changed once created.

` `What is Mutable Strings ?

è Mutable strings are string objects that can be modified or changed after their creation.

` `What is Immutable Strings ?

è Immutable strings are string objects whose values cannot be changed after their creation in Java.

` `What is Advantage and Disadvantage of String ?

è **Advantages of String:**

**1. Immutable:** Strings are immutable, meaning they cannot be changed once created. This property ensures thread safety and simplifies string manipulation.

**2. Wide Usage:** Strings are extensively used in Java and many other programming languages for storing and processing textual data, making them familiar and well-supported.

**3. Built-in Methods:** The String class provides a wide range of built-in methods for string manipulation, making tasks such as concatenation, substring extraction, searching, and replacing efficient and convenient.

**Disadvantages of String:**

**1. Memory Overhead:** Strings in Java consume more memory compared to primitive data types, as they are objects that come with additional overhead for storing metadata.

**2. Inefficient Concatenation:** String concatenation using the '+' operator can be inefficient when performed repeatedly, as it involves creating new string objects each time.

**3. Difficulty in Comparison:** Comparing strings for equality using the '==' operator can lead to unexpected results. It is recommended to use the equals() or equalsIgnoreCase() methods for proper string comparison.

**4. Immutable Limitations:** The immutability of strings can be limiting in scenarios where frequent modifications are required, as it involves creating new string objects, leading to increased memory usage and performance impact.

**5. Security Vulnerability:** Strings being immutable can pose security risks in scenarios where sensitive information, such as passwords, are stored as plain text, as they cannot be easily overwritten or cleared from memory.

` `Name 10 build in Method in String ?

è Here are 10 built-in methods available in the `String` class in Java:

1\. `length()`: Returns the length of the string.

2\. `charAt(int index)`: Returns the character at the specified index.

3\. `concat(String str)`: Concatenates the specified string to the end of the current string.

4\. `substring(int beginIndex)`: Returns a new string that is a substring of the current string, starting from the specified index.

5\. `substring(int beginIndex, int endIndex)`: Returns a new string that is a substring of the current string, starting from the beginIndex and ending at the endIndex.

6\. `toLowerCase()`: Converts the string to lowercase.

7\. `toUpperCase()`: Converts the string to uppercase.

8\. `trim()`: Removes leading and trailing whitespace from the string.

9\. `replace(char oldChar, char newChar)`: Replaces all occurrences of the oldChar with the newChar.

10\. `split(String regex)`: Splits the string into an array of substrings based on the specified regular expression.

There are many more methods available in the `String` class for various string manipulation operations.

` `Difference way to compare String ?

è In Java, there are multiple ways to compare strings:

1\. Using the `**equals()**` method: It compares the content of two strings and returns `true` if they are equal, ignoring case.

2\. Using the `**equalsIgnoreCase()**` method: It compares the content of two strings and returns `true` if they are equal, considering case-insensitivity.

3\. Using the `**compareTo()**` method: It compares two strings lexicographically and returns an integer value indicating the comparison result (-1 if the first string is smaller, 0 if they are equal, 1 if the first string is greater).

4\. Using the `**compareToIgnoreCase()**` method: It compares two strings lexicographically, ignoring case, and returns an integer value indicating the comparison result.

5\. Using the `**==**` operator: It checks if two string references point to the same memory location, rather than comparing the actual content of the strings.

Note: When comparing strings for equality, it is generally recommended to use the `equals()` or `equalsIgnoreCase()` methods instead of the `==` operator.

` `What is StringBuilder ?

è `StringBuilder` is a mutable class in Java that allows efficient manipulation of strings. It provides methods for appending, inserting, replacing, and deleting characters or substrings.

`StringBuilder` is used when there is a need for dynamic modification of strings without creating new objects.

` `What is StringBuffer ?

è `StringBuffer` is a mutable class in Java, similar to `StringBuilder`, that allows efficient manipulation of strings. It provides methods for appending, inserting, replacing, and deleting characters or substrings. `StringBuffer` is thread-safe, making it suitable for use in multi-threaded environments where synchronization is required.

` `Difference between StringBuffer and StringBuilder ?

![String vs StringBuffer vs StringBuilder](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.003.png)è Difference between StringBuffer and StringBuilder :

` `What is String Tokenizer ?

è `StringTokenizer` is a class in Java used for splitting a string into tokens based on a specified delimiter. It provides methods to retrieve and process each token individually. `StringTokenizer` is commonly used for parsing text or breaking down strings into smaller components for further processing or analysis.

**OBJECT ORIENTED PROGRAMMING**

` `What is OOP’s ?

è OOPs is a programming paradigm that organizes code around objects. It emphasizes the concept of objects, which are instances of classes, and their interactions. OOP focuses on structure and modularize code, making it easier to understand, maintain, and reuse.

` `Type of OOP’s ?

è There are four main pillars or principles of Object-Oriented Programming (OOP):

1\. Encapsulation

2\. Inheritance

3\. Polymorphism

4\. Abstraction

` `What are the advantages of OOPS concepts ?

è Object-Oriented Programming (OOP) concepts offer several advantages in software development:

1\. Modularity: Encapsulation and abstraction help create self-contained, reusable components.

2\. Reusability: Inheritance promotes code reuse, reducing redundant code.

3\. Flexibility: Polymorphism allows flexibility in method implementations, improving code extensibility.

4\. Maintainability: OOP enhances code organization and readability, making maintenance easier.

5\. Scalability: OOP supports modular development, enabling scalable and complex applications.

6\. Security: Encapsulation provides data hiding, enhancing security and preventing unauthorized access.

` `What are the disadvantages of OOPS concepts ?

è Some disadvantages of OOP concepts are:

1\. Complexity: Overuse of inheritance and complex class hierarchies can lead to code complexity.

2\. Performance: OOP can result in overhead due to dynamic dispatch and object creation.

3\. Learning Curve: OOP principles may require a steep learning curve for beginners.

4\. Memory Usage: Object-oriented designs can consume more memory compared to procedural programming.

|                  **Advantages**                   |               **Disadvantages**               |
| :-----------------------------------------------: | :-------------------------------------------: |
| We can reuse the code multiple times using class  |      Size is larger than other programs       |
| Inherit the class to subclass for data redundancy |     It required a lot of effort to create     |
|         It is easy to maintain and modify         |       It is slower than other programs        |
|         It maintains the security of data         | It is not suitable for some sorts of problems |
|               Low-cost development                |       It takes time to get used to it.        |

` `Why java is not pure object-oriented programming ?

è Java is not purely object-oriented because it supports primitive data types (such as int, boolean, etc.) that are not objects. Pure object-oriented languages treat everything as objects, including basic data types.

` `What is Class ?

è A class is the blueprint of an object. when you write a class, you are describing how the JVM should make an object of that type. It is a logical entity. It can't be physical.

- A class in Java can contain:
- Fields
- Methods
- Constructors
- Blocks
- Nested class and interface

` `What is Object ?

è An object is an instance of a class that represents a real-world entity. It has state (attributes) and behaviour (methods) defined by its class, allowing it to interact with other objects. It can be physical or logical (tangible and intangible).

- An object has three characteristics:
- State: represents the data (value) of an object.
- Behaviour: represents the behaviour (functionality) of an object such as deposit, withdraw, etc.
- Identity: An object identity is typically implemented via a unique ID. The value of the ID is not visible to the external user. However, it is used internally by the JVM to identify each object uniquely.

` `What is var type in Java ?

è The "var" is a type inference keyword introduced in Java 10. It allows you to declare local variables without explicitly specifying their data types.

` `What is transient keyword ?

è The "transient" keyword is used to indicate that a field should not be serialized when an object is converted into a byte stream, typically for storage or transmission purposes.

` `What is volatile keyword ?

è The "volatile" keyword is used to declare a variable as volatile, indicating that its value may be modified by multiple threads concurrently.

` `What is this keyword ?

è ‘this’ keyword in Java that refers to the current instance of the class. In OOPS it is used to:

1. pass the current object as a parameter to another method
1. refer to the current class instance variable

` `What is this() Method ?

è The this() method in Java is used to call one constructor from another constructor within the same class.

` `Difference between this keyword and this() method ?

è

|                                            **This**                                             |                                                       **this()**                                                        |
| :---------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------: |
|                           this keyword is used with the objects only.                           |                                         this() is used with constructors only.                                          |
|                                It refers to the current object.                                 | It refers to the constructor of the same class whose parameters matches with the parameters passed to this(parameters). |
|       Dot(.) operator is used to access the members. <br>For example, this.variableName;        |                          No Dot(.) operator is used. Only the matching parameters are passed.                           |
| It is used to differentiate between the local variable and the instance variable in the method. |                           It is used to refer to the constructor belonging to the same class.                           |
|                              Can be used anywhere within the class                              |                              Must be used as the first line of code within the constructor                              |
|                           Refer to the current instance of the class                            |                      Refer to the constructor of the same class with a different set of parameters                      |
|           Used to access instance variable or instance methods from within the class.           |                                   Used to invoke another constructor from same class.                                   |
|           Can be used to pass the current instance as an argument to another method.            |                      Cannot be used to pass the current instance as an argument to another method.                      |

` `What is Shadowing problem ?

è The "shadowing problem" occurs when a local variable within a method has the same name as an instance variable in the enclosing class.

` `What is Static ?

è Static is defined class-level members (variables and methods) that belong to the class itself rather than to instances of the class.

` `Why we use Static ?

è Static members in Java serve various purposes:

1. Shared Data: Static variables are shared among all instances of a class, enabling data that's common to all objects.
1. Utility Methods: Static methods provide utility functions that don't depend on object state.
1. Memory Efficiency: They reduce memory usage as only one copy exists for all instances.
1. Global Access: Static members can be accessed without creating instances of the class.

` `What is Static Variable ?

è A static variable in Java is a variable that belongs to the class itself rather than a specific instance of the class. It is shared among all instances of the class and retains its value across multiple object creations. Static variables are declared using the "static" keyword and are commonly used for constants or shared data among objects.

` `Why is use Static Variable ?

è Static variables are useful for storing data that is shared among all instances of a class. They provide a way to maintain a common value across different objects. Static variables are often used for constants, global counters, or shared resources that need to be accessed and modified by multiple objects or methods in a class.

` `What is Static Method ?

è A static method is a function within a class in object-oriented programming that is not associated with an instance of the class. It can be called directly on the class itself and does not have access to instance-specific data.

` `Why is use Static Method ?

` `What is Static Block ?

è A static block in Java is a special block of code within a class that is executed only once when the class is loaded into memory, before any static methods or variables are accessed. It's typically used for performing one-time initialization tasks for the class or loading resources, such as database drivers.

` `Why use Static Block ?

` `What is static keyword ?

è The "static" keyword is used to define class-level members, such as variables and methods, that belong to the class itself rather than to instances of the class.

` `What is difference between static and non-static ?

è Difference between static and non-static member are :

|      **Aspect**       |                          **Static**                          |                  **Non-Static (Instance)**                   |
| :-------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  **Associated with**  |                            Class                             |                     Instances (Objects)                      |
|      **Access**       | Accessed using the class name (e.g., ClassName.methodName()) | Accessed using an instance (e.g., instanceName.methodName()) |
| **Memory Allocation** |    Allocated once for the class, shared by all instances     |            Allocated separately for each instance            |
|    **Can Access**     |         Only static members and other static methods         |    Both static and non-static (instance) members/methods     |
|     **Use Case**      |        Utility functions, constants, shared resources        |        Operations dependent on instance-specific data        |
|      **Example**      |                 Math.sqrt(x) (static method)                 |           myObject.toString() (non-static method)            |

` `What is Encapsulation (Explain one example from real world entity) ?

è Encapsulation is an OOP concept that refers to the bundling of data (attributes) and methods (behaviour’s) within a class, and restricting direct access to the internal data from outside the class. It promotes data hiding, security, and abstraction.

One real-world example of encapsulation is a smartphone. The smartphone's internal components, such as the processor, memory, and sensors, are encapsulated within the phone's casing. Users can interact with the phone's functionalities (e.g., making calls, taking photos) through well-defined interfaces like the touchscreen or buttons, without needing to know the internal details. This encapsulation provides security for the internal components, ensures consistent behaviour, and allows for easy upgrades or modifications to the phone's hardware without affecting the user's experience.

` `What is Advantage and Disadvantage of Encapsulation ?

è Advantages of Encapsulation :

1. Data Protection: The program runner will not be able to identify or see which methods are present in the code.

Therefore he/she doesn’t get any chance to change any specific variable or data and hinder the running of the program.

1. Flexibility: The code which is encapsulated looks cleaner and more flexible, and can be changed as per the needs. We

`            `can change the code read-only or write-only by getter and setter methods. This also helps in debugging the

`            `code if needed.

1. Reusability: The methods can be changed and the code is reusable.

è Disadvantages of Encapsulation :

1. Code Size: The length of the code increases drastically in the case of encapsulation as we need to provide all the

   `                    `methods with the specifiers.

1. More Instructions: As the size of the code increases, therefore, you need to provide additional instructions for every

   `                                  `method.

1. Increased code execution: Encapsulation results in an increase in the duration of the program execution. It is because

   `                                                `more instructions are added to the code therefore they require more time to execute.

` `How to Achieve Encapsulation ?

è Encapsulation in Java can be achieved by:

1. Declaring the variables of a class as private.
1. Providing public setter and getter methods to modify and view the variables values.

Now, let’s look at the code to get a better understanding of encapsulation:

class Person{

`    `private String name;

`    `private int age;

`    `// Setter method for name

`    `public void setname(String name){

`        `this.name = name;

`    `}

`    `// Setter method for age

`    `public void setage(int age){

`        `this.age = age;

`    `}

`    `// Getter method for name

`    `public String getname(){

`        `return name;

`    `}

`    `// Getter method for age

`    `public int getage(){

`        `return age;

`    `}

}

public class Enpasulation{

`    `public static void main(String[] args){

`        `Person person = new Person();

`        `// Set initial values using setter methods

`        `person.setname("Saurabh Kumar");

`        `person.setage(23);

`        `System.out.println("Name: " + person.getname()); // Output: Name: Saurabh Kumar

`        `System.out.println("Age: " + person.getage()); // Output: Age: 23

`        `// Update Name & Age

`        `person.setname("Saurabh Singh");

`        `person.setage(20);

`        `System.out.println("Updated Name: " + person.getname()); // Output: Updated Name: Saurabh Singh

`        `System.out.println("Updated Age: " + person.getage()); // Output: Updated Age: 20

`    `}

}

` `What is Setter method ?

è Setter methods are public methods within a class that allow other classes or code to modify the value of a private attribute.

` `What is Getter method ?

è Getter methods are public methods within a class that allow other classes or code to retrieve the value of a private attribute.

` `Can a getter method modify the object's state ?

è In general, a getter method should not modify the object's state. The primary purpose of a getter method is to provide read-only access to an object's attributes or fields.

How can you make a class immutable in Java ?

` `What are the access modifiers used in encapsulation ?

è There are four type of access modifiers in encapsulation :

1. Private: Used to encapsulate data by restricting access to internal implementation details.
1. Default (Package-Private): Provides encapsulation within a package, allowing controlled access for classes within the same package.
1. Protected: Supports encapsulation by allowing derived classes to access members, but it still provides some level of access control.
1. Public: Provides no encapsulation as it allows unrestricted access from anywhere, but it is used for elements intended to be part of the class's public interface.

` `How can you prevent unauthorized access to an object's attributes ?

è Preventing unauthorized access to an object's attributes in Java is a fundamental aspect of encapsulation. You can achieve this by following these best practices:

1. Use Private Access Modifiers: Declare the attributes (fields) of the class as private. This restricts direct access to the attributes from outside the class.
1. Provide Getter and Setter Methods: Create public getter and setter methods to control access to the attributes. These methods allow controlled read and write access to the attributes.
1. Implement Validation and Error Checking: Inside the setter methods, include validation and error-checking logic to ensure that the data being set is valid and conforms to the class's requirements. This helps maintain data integrity.
1. Consider Making the Class Immutable: In some cases, you can make the class immutable by declaring attributes as final and initializing them in the constructor. This prevents modification of the object's state after creation.
1. Use Access Modifiers Wisely: Employ access modifiers (e.g., private, protected, public) to control the visibility of the class and its members. Limit exposure to what is necessary.
1. Avoid Providing Mutable Objects: If your class contains mutable objects (e.g., lists, arrays), return defensive copies or immutable versions of these objects to prevent external modification.

` `What is data hiding ?

è Data hiding is used to hide or secure the data of a particular from the outside access of the class.

` `What is the difference between abstraction and encapsulation ?

è Difference between Abstraction and Encapsulation:

|                                        **Abstraction**                                        |                                                           **Encapsulation**                                                            |
| :-------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------: |
|               Abstraction is the process or method of gaining the information.                |                                While encapsulation is the process or method to contain the information.                                |
|             In abstraction, problems are solved at the design or interface level.             |                                While in encapsulation, problems are solved at the implementation level.                                |
|                 Abstraction is the method of hiding the unwanted information.                 | Whereas encapsulation is a method to hide the data in a single entity or unit along with a method to protect information from outside. |
|               We can implement abstraction using abstract class and interfaces.               |                 Whereas encapsulation can be implemented using by access modifier i.e. private, protected and public.                  |
| In abstraction, implementation complexities are hidden using abstract classes and interfaces. |                            While in encapsulation, the data is hidden using methods of getters and setters.                            |
|                The objects that help to perform abstraction are encapsulated.                 |                                Whereas the objects that result in encapsulation need not be abstracted.                                |
|                     Abstraction provides access to specific part of data.                     |                            Encapsulation hides data and the user cannot access same directly (data hiding.                             |
|                        Abstraction focus is on “what” should be done.                         |                                           Encapsulation focus is on “How” it should be done.                                           |

` `How do you handle validation and error checking within setter methods ?

è

` `What is Inheritance (Explain one example from real world entity) ?

è Inheritance is a fundamental concept in object-oriented programming, where a new class (subclass) can inherit properties and behaviours from an existing class (superclass). It promotes code reusability and allows for the creation of a hierarchical structure among classes.

For example, in the real world, consider the concept of vehicles. We can have a superclass called "Vehicle" that contains common attributes and methods shared among various types of vehicles. Then, subclasses like "Car," "Motorcycle," and "Truck" can inherit from the "Vehicle" class, gaining access to its properties like "wheels," "engine," and methods like "start" and "stop." This hierarchy models the relationship between different types of vehicles in a well-organized manner.

Note:- A parent class can be inherited using public, protected or private type of inheritance.

` `Type of Inheritance ?

èThe different type of inheritance which are supported in java :

1. Single Inheritance : A subclass can inherit from only one superclass. This is the simplest and most common type of inheritance.
1. Multilevel Inheritance : A subclass can inherit from another subclass, creating a chain of inheritance.
1. Hierarchical Inheritance : Multiple subclasses inherit from the same superclass. Each subclass can have its own unique features while sharing common characteristics from the superclass.
1. Multiple Inheritance : A subclass can inherit from more than one superclass. However, multiple inheritance can lead to the "diamond problem" and can be complex, so some programming languages, like Java, do not support direct multiple inheritance for classes. Instead, multiple inheritance can be achieved through interfaces.
1. Hybrid Inheritance : This is a combination of two or more types of inheritance. For example, a class can exhibit both single and multiple inheritance traits.

` `Rules of Inheritance ?

è Rules of Inheritance are :

1. Multiple inheritance is not permitted in Java as it leads to diamond shaped problem which results in ambiguity.
1. Multilevel inheritance is permitted in Java
1. Cyclic inheritance is not permitted in Java.
1. Private members do not participate in inheritance.
1. Constructor do not participate in inheritance.
1. We assign parents reference to child objects.
1. Constructor get executed because of super() present in the constructor.

` `What is Advantage and Disadvantage of Inheritance ?

è Advantages of inheritance:

1\. Code reusability: Inheritance allows subclasses to reuse the code of the superclass, reducing redundant code and

`                                    `promoting efficiency.

2\. Extensibility: New subclasses can be easily added, expanding the functionality of existing classes without modifying the

`                             `original code.

1. Hierarchical organization: Inheritance creates a structured relationship between classes, making the code more

   `                                                `organized and easier to understand.

1. Polymorphism: It enables polymorphic behaviour, where objects of different subclasses can be treated as objects of

   `                             `their superclass, enhancing flexibility and modularity.

è Disadvantages of inheritance:

1\. Tight coupling: Overuse of inheritance can lead to tight coupling between classes, making the codebase more complex

`                                `and harder to maintain.

2\. Fragile base class problem: Changes in the superclass can unintentionally affect its subclasses, causing unexpected

`                                                      `bugs.

3\. Inherited features might not be relevant: Subclasses may inherit unnecessary attributes or methods, increasing the size

`                                                                                `of the objects unnecessarily.

4\. Difficulty in understanding complex hierarchies: Deep inheritance hierarchies can be challenging to comprehend,

`                                                                                            `making code comprehension difficult for developers.

` `How to Achieve Inheritance ?

![](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.004.png)è In Java, you can achieve inheritance by using the "extends" keyword. Here's an example of inheritance with a "Vehicle" class:

` `What is subclass in java ?

è A class that is derived from another class is called a *subclass* (also a *derived class*, *extended class*, or *child class*).

` `What is superclass in java ?

è The class from which the subclass is derived is called a *superclass* (also a *base class* or a *parent class*).

` `What is uses of extend keyword ?

è Extend keyword is used for inheriting one class to another class.

` `What is Tight Coupling (High Coupling) ?

è  Tight coupling means the two classes often change together. In other words, if A knows more than it should about the way in which B was implemented, then A and B are tightly coupled.

` `What is Loose Coupling (Low Coupling) ?

è In this type, classes are minimally dependent on each other. Each class is independent and can be modified without affecting other classes. Communication between classes is usually through interfaces or abstract classes.

` `What is Super Keywod ?

è

` `What is difference between this and super Keyword ?

è The following table describes the key difference between this and super:

|                                             **this**                                             |                                              **super**                                              |
| :----------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: |
|                The current instance of the class is represented by this keyword.                 |            The current instance of the parent class is represented by the super keyword.            |
|     In order to call the default constructor of the current class, we can use this keyword.      |     In order to call the default constructor of the parent class, we can use the super keyword.     |
| It can be referred to from a static context. It means it can be invoked from the static context. | It can't be referred to from a static context. It means it cannot be invoked from a static context. |
|        We can use it to access only the current class data members and member functions.         |         We can use it to access the data members and member functions of the parent class.          |

` `What is difference between this() and super() Constructor ?

è Difference Between this() and super() Constructor

|                               **this()**                               |                              **super()**                               |
| :--------------------------------------------------------------------: | :--------------------------------------------------------------------: |
|       The this() constructor refers to the current class object.       |     The super() constructor refers immediate parent class object.      |
|           It is used for invoking the current class method.            |             It is used for invoking parent class methods.              |
|       It can be used anywhere in the parameterized constructor.        |      It is always the first line in the child class constructor.       |
| It is used for invoking a super-class version of an overridden method. | It is used for invoking a super-class version of an overridden method. |

` `Name the type of method in inheritance ?

èThere are three type of method in inheritance :

1. Inherited Method : An inherited method is a method that is defined in a superclass (base class) and is automatically made available to its subclasses (derived classes) through the process of inheritance.
1. Overridden Method : An overridden method is a method in a subclass that provides a specific implementation for a method that is already defined in its superclass.
1. Specialized Method : Specialized method typically refers to a method that is specifically designed or customized to perform a particular task or behaviour for a specific subclass.

` `What is method overridden ?

è The method in the parent class that is overridden by the child class method.

` `What is method overriding ?

è The method in child class that is the same as a method in the parent class.

` `Rule of method overriding ?

è Rules for Method Overriding :

- The [access modifier](https://www.edureka.co/blog/access-modifiers-in-java/) can only allow more access for the overridden method.
- A [final](https://www.edureka.co/blog/final-finally-and-finalize-in-java/) method does not support method overriding.
- A static method cannot be overridden.
- Private methods cannot be overridden.
- The return type of the overriding method must be the same.
- We can call the parent class method in the overriding method using the super keyword.
- A [constructor](https://www.edureka.co/blog/constructor-in-java/) cannot be overridden because a child class and a parent class cannot have the constructor with the same name.

` `What is Polymorphism (Explain one example from real world entity) ?

è Polymorphism is the ability of a method to take different forms based on the objects it operates on. It allows objects of different classes to be treated as objects of a common superclass.

One real-world example is the "Animal" superclass with subclasses like "Dog," "Cat," and "Bird." They all have a "makeSound()" method, but each subclass implements it differently. When we call "makeSound()" on an animal object, the appropriate subclass method is invoked, resulting in different sounds, demonstrating polymorphism's versatility and flexibility in handling diverse object types.

` `How to Achieve Polymorphism ?

è class Animal {

`    `void makeSound() {

`        `System.out.println("Animal makes a sound");

`    `}

}

class Dog extends Animal {

`    `@Override

`    `void makeSound() {

`        `System.out.println("Dog barks");

`    `}

}

class Cat extends Animal {

`    `@Override

`    `void makeSound() {

`        `System.out.println("Cat meows");

`    `}

}

public class PolymorphismExample {

`    `public static void main(String[] args) {

`        `Animal myAnimal = new Animal();

`        `Animal myDog = new Dog();

`        `Animal myCat = new Cat();

`        `myAnimal.makeSound(); // Calls Animal's makeSound method

`        `myDog.makeSound(); // Calls Dog's makeSound method

`        `myCat.makeSound(); // Calls Cat's makeSound method

`    `}

}

` `Type of Polymorphism ?

è There are two type of Polymorphism :

1. Compile-Time Polymorphism
   1. Method Overloading :
   1. Operator Overloading :
1. Run-Time Polymorphism
1. Method Overriding :
1. Operator Overriding :

` `What is Advantage and Disadvantage of Polymorphism ?

è Advantage and Disadvantage of Polymorphism :

|                                                                    **Advantage of Polymorphism**                                                                    |                                                                               **Disadvantage of Polymorphism**                                                                               |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 1\. Code Flexibility: Polymorphism allows code to be written in a more flexible and extensible manner. New subclasses can be added without modifying existing code. |                       1\. Abstraction Complexity: Polymorphism can introduce additional abstraction layers, making code more challenging to understand for beginners.                        |
|           2\. Code Reusability: Polymorphism promotes code reusability by enabling the use of common interfaces or base classes for different subclasses.           | 2\. Performance Overhead: Dynamic method resolution at runtime may incur a slight performance overhead compared to static method calls. However, in most cases, this overhead is negligible. |
|       3\. Simplified Interface: Polymorphism simplifies the interaction between objects by allowing them to be treated uniformly, enhancing code readability.       |                  3\. Method Signature Limitation: Method overriding in polymorphism requires the exact same method signature, which may limit certain design possibilities.                  |
|            4\. Runtime Flexibility: The actual method to be executed is determined at runtime based on the object's type, providing runtime flexibility.            |                              4\. Learning Curve: Understanding and implementing polymorphism might require a steeper learning curve, especially for beginners.                               |
|          5\. Reduced Code Duplication: Polymorphism reduces code duplication by sharing common behaviour through inheritance or interface implementation.           |             5\. Potential Errors: Incorrect method overriding or implementation might lead to runtime errors or unexpected behaviour. Careful design and testing are essential.              |

` `What is Runtime Polymorphism ?

è

` `What is Aggregation ?

è Aggregation is a represents a relationship between two classes where one class contains a reference to another class. It is a form of association that implies a "has-a" relationship.

` `What is Composition ?

è Composition is represents a strong relationship between two classes where one class is composed of or contains objects of another class.

` `What is Loose Bound ?

è

` `What is Tight Bound ?

è

` `What is Covariant return type ?

è

` `What is Method Overloading ?

è When a class has more than one method with same name but with different arguments, then we call it as method overloading.

` `What is Method Overriding ?

è When a super class method is modified in the sub class, then we call this as method overriding.

` `Difference between Overloading and Overriding ?

è Overloading and overriding are two important concepts in Java related to methods:

1\. Overloading:

\- Involves having multiple methods in the same class with the same name but different parameter lists (number or type of parameters).

\- The return type may or may not be the same.

\- Overloaded methods provide different ways to perform a similar operation with varying inputs.

\- Decided at compile-time based on the method signature.

2\. Overriding:

\- Occurs when a subclass provides a specific implementation for a method that is already defined in its superclass.

\- The method name, parameter list, and return type must be exactly the same in both the superclass and subclass.

\- Used to provide a specialized implementation of a method for a specific subclass, thus enabling polymorphism.

\- Decided at runtime based on the actual object's type.

` `What is Abstraction (Explain one example from real world entity) ?

è Abstraction in Java refers to the concept of hiding the implementation details of a class while showing only the necessary features to the outside world. It allows programmers to focus on what an object does rather than how it does it.

One real-world example of abstraction is a car. When driving a car, we interact with its high-level functionalities such as steering, acceleration, and braking, without needing to understand the complex internal mechanisms like the combustion engine or transmission system. In Java, a Car class could abstract away these internal details while exposing methods like accelerate(), brake(), and steer().

` `How to achieve abstraction ?

è An interface only stores the method signature and not the method definition. Method Signatures make an Interface achieve complete Abstraction by hiding the method implementation from the user.

` `How to support the functionality of multiple inheritance ?

è Without Interface, the process of multiple inheritances is impossible as the conventional way of inheriting multiple parent classes results in profound ambiguity. This type of ambiguity is known as the Diamond problem. Interface resolves this issue.

` `how to achieve loose coupling in java ?

è The term Coupling describes the dependency of one class for the other. So, while using an interface, we define the method separately and the signature separately.

**INTERFACE**

` `What is Interface ?

è An interface in Java is a mechanism that is used to achieve complete abstraction. It is basically a kind of class that contains only constants and abstract methods.

` `Why use Java interface ?

è There are mainly three reasons to use interface. They are given below.

- It is used to achieve abstraction.
- By interface, we can support the functionality of multiple inheritance.
- It can be used to achieve loose coupling.

` `Rule of Interface ?

è Rule about Interface in Java :

1. Fields in an interface are public, static and final implicitly
1. Methods in an interface are public implicitly
1. A class can implement multiple interfaces
1. The overriding methods cannot have more restrict access specifiers
1. Non-abstract classes must override all methods declared in the super interfaces
1. Abstract classes are not forced to override all methods from their super interfaces. The first concrete class in the inheritance tree must override all methods
1. An interface cannot extend another class
1. An interface can extend from multiple interfaces
1. An interface can be nested within a class
1. An interface can be nested within another interface
1. Methods in an interface cannot be static and final
1. Since Java 8, an interface can have default methods and static methods
1. Functional interface is an interface that has only one method

` `Can we define private and protected modifiers for data members (fields) in interfaces ?

è No, we cannot define private and protected modifiers for variables in interface because the fields (data members) declared in an interface are by default public, static, and final.

` `Which modifiers are allowed for methods in an Interface ?

è Only abstract and public modifiers are allowed for methods in interfaces.

` `Suppose A is an interface. Can we create an object using new A() ?

è No, we cannot create an object of interface using new operator. But we can create a reference of interface type and interface reference refers to objects of its implementation classes.

` `Can we define an interface with a static modifier ?

è Yes, from Java 8 onwards, we can define static and default methods in an interface. Prior to Java 8, it was not allowed.

` `Can an interface extends another interface in Java ?

è Yes, an interface can extend another interface.

` `Can an interface implement another interface ?

è No, an interface cannot implement another interface.

` `Is it possible to define a class inside an interface ?

Ans: Yes, we can define a class inside an interface.

` `Can an interface extend multiple interfaces ?

è Yes, an interface can extend multiple interfaces.

` `Can an interface have instance and static blocks?

è No.

` `Why an interface cannot have a constructor ?

è Inside an interface, a constructor cannot be called using super keyword with hierarchy.

` `Why an Interface method cannot be declared as final in Java ?
Or, Can a method within an interface be marked as final ?

è Not possible. Doing so will result the compilation error problem. This is because a final method cannot be overridden in java. But an interface method should be implemented by another class.

So, the interface method cannot be declared as final. The modifiers such as public and abstract are only applicable for method declaration in an interface.

` `What is Marker interface or tagged interface ?

è An interface without methods, fields and constants is known as marker or tagged interface. This type of interface is an empty interface. It delivers runtime information about an object. This information is delivered to both the JVM and the compiler.

` `Type of Marker Interface ?

è There are 3 type of Marker Interface :

1. Serializable Interface
1. Cloneable Interface
1. Remote Interface

` `What is Serializable Interface ?

è Serializable interface is present in java.io package. It is used to make an object eligible for saving its state into a file. This is called Serialization.

` `What is Cloneable Interface ?

è Cloneable is an interface that is used to create the exact copy of an object. It exists in java.lang package ( import java.lang.Cloneable; ).

` `What is Remote Interface ?

è The remote interface exists in ( import java.rmi.Remote ), Remote interface and declares a set of methods that may be invoked from a remote Java Virtual Machine (JVM).

` `What is the difference between a functional interface and a regular interface in Java ?

è The difference between a functional interface and a regular interface in Java :

|           **Feature**            |                                **Functional Interface**                                 |                                 **Regular Interface**                                 |
| :------------------------------: | :-------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------: |
|         Abstract Methods         |                            Exactly one abstract method (SAM)                            |                          Can have multiple abstract methods                           |
|             Purpose              |                          Primarily for functional programming                           |                       Used for various purposes, including APIs                       |
|        Lambda Expressions        |                           Easily used with lambda expressions                           | Not directly usable with lambda expressions (unless there’s a single abstract method) |
| Predefined Functional Interfaces |    A set of predefined functional interfaces in java.util.function for common tasks     |          Not associated with a specific set of common functional interfaces           |
|         Default Methods          |                            Can have multiple default methods                            |                               Can have default methods                                |
|          Static Methods          |                            Can have multiple static methods                             |                                Can have static methods                                |
|         Constant Fields          |             Can have constant fields (implicitly public, static, and final)             |                               Can have constant fields                                |
| @FunctionalInterface Annotation  | Can be annotated with @FunctionalInterface to ensure single abstract method requirement |                   Not typically annotated with @FunctionalInterface                   |

` `Write the Code for Functional interface.

![](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.005.png)è

` `Write the Code Regular interface.

![](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.006.png)è

` `What is Abstract class ?

è An Abstract class is a class designed with implementation gaps for subclass to fill and is deliberately incomplete.

` `What is differences between abstract class and interface ?

è There are many differences between abstract class and interface that are given below.

|                                   **Abstract class**                                    |                                            **Interface**                                             |
| :-------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: |
|               Abstract class can have abstract and non-abstract methods.                | Interface can have only abstract methods. Since Java 8, it can have default and static methods also. |
|                  Abstract class doesn’t support multiple inheritance.                   |                               Interface supports multiple inheritance.                               |
|       Abstract class can have final, non-final, static and non-static variables.        |                            Interface has only static and final variables.                            |
|               Abstract class can provide the implementation of interface.               |                    Interface can’t provide the implementation of abstract class.                     |
|                 The abstract keyword is used to declare abstract class.                 |                         The interface keyword is used to declare interface.                          |
| An abstract class can extend another Java class and implement multiple Java interfaces. |                         An interface can extend another Java interface only.                         |
|               An abstract class can be extended using keyword “extends”.                |                     An interface can be implemented using keyword “implements”.                      |
|       A Java abstract class can have class members like private, protected, etc.        |                          Members of a Java interface are public by default.                          |
|      Example:<br>public abstract class Shape{<br>public abstract void draw();<br>}      |                     Example:<br>public interface Drawable{<br>void draw();<br>}                      |

`  `What is the difference between class and interface in Java ?

è The difference between class and interface in java :

|     |                                  **Class**                                  |                             **Interface**                              |
| :-- | :-------------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| 1\. |        In class, you can instantiate variables and create an object.        | In an interface, you can’t instantiate variables and create an object. |
| 2\. |           Class can contain concrete(with implementation) methods           |   The interface cannot contain concrete(with implementation) methods   |
| 3\. | The access specifiers used with classes are private, protected, and public. |            In Interface only one specifier is used- Public.            |

**EXCEPTION HANDLING**

` `What is Exception Handling in java ?

è Exception handling in Java allows programmers to handle unexpected errors or exceptional situations that occur during program execution. Example : ClassNotFoundException, IOException, SQLException, RemoteException, etc.

` `What is Advantage and Disadvantage of Exception Handling ?

è Advantage and Disadvantage of Exception Handling :

|               **Advantage of Exception Handling**               |                  **Disadvantage of Exception Handling**                  |
| :-------------------------------------------------------------: | :----------------------------------------------------------------------: |
|       Prevents program crashes and unexpected termination       |             Can lead to inefficient code if used excessively             |
|          Enhances code readability and maintainability          |                 Overuse can obscure actual error sources                 |
|         Separates error handling logic from normal flow         |                       Adds complexity to the code                        |
|        Enables centralized error handling and reporting         |         Can hide coding mistakes and promote lazy error handling         |
|     Facilitates graceful handling of exceptional situations     |     Improperly handled exceptions can cause unpredictable behaviour      |
|   Supports layered exception handling for different contexts    |   May require additional testing and validation for exceptional cases    |
|         Allows developers to focus on normal code logic         | Unchecked exceptions may lead to runtime errors that are harder to debug |
|       Promotes error reporting and logging for debugging        |         Requires proper understanding and usage to be effective          |
| Reduces the need for excessive "if" checks for error conditions |                Can be misused as a flow-control mechanism                |
|           Supports recovery and fall-back strategies            |                Can make code harder to read for beginners                |

` `What is Exception in java ?

è An expectation is an unexpected event that occurs while executing the program, that disturbs the normal flow of the code.

` `How to handle exception in Java ?

è In Java, exceptions are handled using try-catch blocks. Place code that may throw an exception in the try block, and use catch blocks to specify how to handle specific exceptions, providing error-handling logic. Optionally, use a finally block for cleanup code that runs regardless of whether an exception occurred.

` `Types of Exception in java ?

è Java exceptions are broadly categorized into two types:

1. Checked Exceptions (Compile Exceptions): Checked exceptions that the Java compiler requires you to handle explicitly using try-catch blocks or declare them in the method's signature using the throws clause.

   Examples of checked exceptions include IOException, SQLException, and FileNotFoundException.

1. Unchecked Exceptions (Runtime Exceptions): Unchecked exceptions do not need to be explicitly handled or declared, as they are not checked by the compiler during compilation.

   Examples of unchecked exceptions are NullPointerException, ArrayIndexOutOfBoundsException, and ArithmeticException.

![](Aspose.Words.c6d25d3b-0544-4bdd-a96c-58af01bdf1cd.007.png)è There are two type of exception in java:

` `What is major reasons of Exception Occurs ?

è Major reasons why an exception Occurs :

- Invalid user input
- Device failure
- Loss of network connection
- Physical limitations (out of disk memory)
- Code errors
- Opening an unavailable file

` `Type of Scenarios exception may occur ?

è There are 3 Scenarios. Exception may occur :

1. Normal Termination :
1. Abrupt Termination :
1. Normal Termination if an exception occurred :

` `Name the Different ways of Handling the exception ?

è There are mainly three type of handling the exception :

1. Handling the exception (try-catch)
1. Re-throwing the exception (try-catch-throw-throws-finally)
1. Ducking the exception (throws)

` `What is the use of try keyword ?

è The try block is used to enclose a section of code where exceptions might occur.

` `What is the use of catch keyword ?

è The catch block is used to handle exceptions that are thrown within the corresponding try block.

` `What is the use of throw Keyword ?5

è The throw keyword is used to explicitly throw an exception.

` `What is the use of throws keyword ?

è the throws keyword is used in method declarations to indicate that the method might throw exceptions of a specified type.

` `What is the use of finally keyword ?

è The finally block is used to define a section of code that will be executed regardless of whether an exception is thrown or not.

` `What is Difference between Throw and Throws ?

è The Difference between throw and throws are :

|                 **Throw**                 |                 **Throws**                  |
| :---------------------------------------: | :-----------------------------------------: |
|     Used for rethrowing an Exception      |        Used for Ducking an Exception        |
|        Used within body of method         |         Used in signature of method         |
| Lines below throw keyword is not executed | Line below the throws keyword will executed |

` `What is the difference between throw, throws and throwable ?

è Difference between throw, throws and throwable :

- ` `Throw : It's a Java keyword used to explicitly throw an exception within a method or block of code.
- ` `Throws : It's used in method signatures to declare that a method might throw certain exceptions. It indicates that the method may propagate those exceptions to its caller.
- ` `Throwable : It's the root class for all exceptions in Java. Both checked exceptions (direct or indirect subclasses of `Exception`, excluding `RuntimeException`) and unchecked exceptions (subclasses of `RuntimeException`) inherit from `Throwable`. It provides common methods like `getMessage()` and `printStackTrace()`.

` `What is finally Keyword ?

è The finally keyword is used in exception handling to define a block of code that will always be executed, regardless of whether an exception is thrown or not.

` `Difference Between final, finally and finalize ?

è The main difference between final finally and finalize in Java are shown in table below.

| **Basis of Comparison** |                                           **final**                                           |                                                           **finally**                                                            |                                                                   **finalize**                                                                    |
| :---------------------: | :-------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------: |
|     **Definition**      | final is a keyword used in Java to restrict the modification of a variable, method, or class. |       finally is a block used in Java to ensure that a section of code is always executed, even if an exception is thrown.       |                   finalize is a method in Java used to perform clean up processing on an object before it is garbage collected.                   |
|        **Usage**        |            final is used to declare a variable, method, or class as unchangeable.             | finally is used after a try or catch block to execute code that must be run regardless of whether an exception is thrown or not. | finalize is used to perform clean-up operations on an object, such as closing files or releasing other resources, before it is garbage collected. |
|      **Execution**      |                              final is executed at compile-time.                               |                                                 finally is executed at runtime.                                                  |                                   finalize is executed by the garbage collector before an object is destroyed.                                    |
| **Exception handling**  |                           final is not used for exception handling.                           |                                             finally is used for exception handling.                                              |                                                   finalize is not used for exception handling.                                                    |
|       **Syntax**        |              final is used as a keyword to modify a variable, method, or class.               |                                    finally is used as a block to execute a set of statements.                                    |                                           finalize is used as a method to perform clean-up operations.                                            |

` `What is Difference between Fail-Fast Iterator and Fail-Safe Iterator ?

è The main Difference between Fail-Fast Iterator and Fail-Safe Iterator :

| **Base of Comparison** |                                      **Fail Fast Iterator**                                       |                     **Fail Safe Iterator**                      |
| :--------------------: | :-----------------------------------------------------------------------------------------------: | :-------------------------------------------------------------: |
|       Exception        | It throws a ConcurrentModificationException in modifying the object during the iteration process. |                  It does not throw Exception.                   |
|      Clone Object      |                     No clone object is created during the iteration process.                      | A copy or clone object is created during the iteration process. |
|   Memory utilization   |                            It requires low memory during the process.                             |           It requires more memory during the process.           |
|      Modification      |                         It does not allow modification during iteration.                          |      It allows modification during the iteration process.       |
|      Performance       |                                            It is fast.                                            |              It is slightly slower than Fail Fast.              |
|        Examples        |                             HashMap, ArrayList, Vector, HashSet, etc                              |          CopyOnWriteArrayList, ConcurrentHashMap, etc.          |

` `What is Error ?

è An exception will disturb the normal flow of any runnable program. But an error is something that contributes to making a program not capable of executing and sometimes collapse as well.

` `Type of errors that can occur during coding ?

è There are two type of errors that can occur during coding :

1. Syntax Error : These occur during compilation and are caused by faulty coding, such as missing semicolons or

   `                         `incorrect use of syntax.

1. Exception : These occur during exception and are caused by unexceptional input or incorrect logic in the code.

` `Types of Error ?

è There are two types of error :

1. Compile-time Error
1. Run-time Error

` `Difference between Compile-time Error and Run-time Error ?

è Compile-time Error V/S Run-time Error

|                          **Compile-time Error**                           |                                    **Run-time Error**                                     |
| :-----------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: |
|                 Occur during the compilation of the code.                 |                          Occur during the execution of the code.                          |
|          Identified by the compiler before running the program.           |                       Only identified when the program is executed.                       |
| Cannot be ignored, and the code must be fixed before running the program. | Can sometimes be handled through exception handling, and the program may continue to run. |
|    Example include syntax errors, type error and missing dependencies.    |    Example include null pointer exception, division by zero, and out of memory errors.    |
|                 Can be detected without running the code.                 |                       Can only be detected while running the code.                        |
|                    Generally easier to debug and fix.                     |                          Can be more difficult to debug and fix.                          |
|               Can prevent the program from running at all.                |                     Can cause the program to terminate unexpectedly.                      |

` `What is Difference between Runtime and Exception ?

è Difference between Runtime and Exception :

` `What is Difference between Error and Exception ?

è Difference between Error and Exception :

|                              **Error**                               |                                           **Exception**                                           |
| :------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: |
|                       Library: java.lang.Error                       |                                    Library: jav.lang.Exception                                    |
|                     Errors are of Unchecked type                     |                          Exceptions are both Checked and Unchecked type                           |
|                The compiler cannot understand errors                 |                            The compiler identifies checked exceptions                             |
|            Errors are mainly encountered in the run-time             |                     Only the unchecked exceptions are encountered in run-time                     |
|          The program cannot recover from an error by itself          | The program can recover from exceptions as the compilers add “try and catch” blocks automatically |
| The error may be caused by program logic or the run-time environment |                            An exception is caused by the application                              |

` `What is Difference Between Hashmap and Hashtable ?

è The main Difference Between Hashmap and Hashtable :

| **S.L.** |                                        **Hashmap**                                         |                                          **Hashtable**                                           |
| :------: | :----------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------: |
|   1\.    |                                 No method is synchronized.                                 |                                  Every method is synchronized.                                   |
|   2\.    | Multiple threads can operate simultaneously and hence hashmap’s object is not thread-safe. | At a time only one thread is allowed to operate the Hashtable’s object. Hence it is thread-safe. |
|   3\.    |         Threads are not required to wait and hence relatively performance is high.         |            It increases the waiting time of the thread and hence performance is low.             |
|   4\.    |                          Null is allowed for both key and value.                           |   Null is not allowed for both key and value. Otherwise, we will get a null pointer exception.   |
|   5\.    |                            It is introduced in the 1.2 version.                            |                               It is introduced in the 1.0 version.                               |
|   6\.    |                                     It is non-legacy.                                      |                                         It is a legacy.                                          |

` `What is thread ?

` `What is domain thread ?

` `What is difference between user thread and daemon thread ?

` `What are multi thread ?

` `What is thread scheduler ?

` `Explain thread cycle ?

` `What is thread pool ?

` `What is difference between thread and process ?

` `What is thread join ?

` `What is thread synchronization ?

` `Why Use Synchronization ?

è Use of Synchronization :

- To prevent thread interference.
- To prevent consistency problems.

` `What is multithreading ?

**Collections Framework**

` `What is a Framework ?

è A framework is a set of classes and interfaces which provide a ready-made architecture.

` `What is Collection ?

è A "Collection" in Java refers to a group of objects or elements that can be manipulated as a single unit. Collections provide a convenient way to store, retrieve, and manipulate data structures like lists, sets, and maps. These structures offer various functionalities for organizing and processing data efficiently.

` `What is Collections ?

è "Collections," on the other hand, typically refers to the Java class java.util.Collections, which contains utility methods for working with collections. It provides methods for sorting, searching, and synchronizing collections.

` `What is Collection Framework ?

è The "Collection Framework" is a comprehensive set of classes and interfaces in Java, located in the java.util package. It encompasses the entire collection hierarchy, including interfaces like List, Set, and Map, and their respective implementations. The framework standardizes how collections are organized and manipulated, ensuring consistency and ease of use for Java developers.

` `What is Advantage of Collections framework ?

è Advantages of the Collections Framework in Java:

1. Reusable Data Structures: The Collections Framework provides a wide range of reusable data structures (e.g., lists, sets, maps) that are implemented and optimized by Java, saving developers the effort of implementing these structures from scratch.
1. Consistency: It standardizes the way data structures are accessed and manipulated, making the code more consistent and easier to understand. Developers can use similar methods across different data structures.
1. Efficiency: The framework offers efficient implementations of data structures, ensuring good performance for common operations like insertion, deletion, and retrieval.
1. Interoperability: Collections can easily be passed as parameters or returned from methods, promoting code flexibility and reusability.
1. Generics Support: The framework uses generics to ensure type safety, reducing the likelihood of runtime errors.

` `What is Disadvantage of Collections framework ?

è Disadvantages of the Collections Framework in Java:

1. Learning Curve: The Collections Framework can be complex, especially for beginners. Learning all the different data structures and their methods can take time.
1. Memory Overhead: Some collection classes may have higher memory overhead compared to arrays, which can be a concern in memory-constrained environments.
1. Performance Trade-offs: While most operations are efficient, certain operations like searching in a LinkedList can be slower compared to direct array access.
1. Inefficient for Some Use Cases: For specific use cases, a custom data structure might be more efficient than the standard collections. In such cases, developers may need to implement their own data structures.
1. Not Suitable for All Scenarios: Some applications may require specialized data structures or low-level memory management, which the Collections Framework may not cater to.

# ` `Type of Collections framework ?

` `What is root interface of collection framework ?

è Iterable.

# ` `What is Wrapper Class ?

è A wrapper class is a class that provides an object representation for the primitive data types. While Java supports primitive data types like int, char, double, etc.

# ` `What is Generics ?

# ` `What is List ?

Note:- 1. List is Ordered collection. 2. List hold duplicate value

# ` `What is ArrayList ?

# ` `What is LinkedList ?

# ` `What is Vector ?

# ` `What is Stack ?

# ` `What is Queue ?

# ` `Tell some method in Queue ?

# ` `What is Difference between .add and .offer When we use add method and offer method ?

# ` `What is Difference between .remove and .poll When we use remove method and poll method ?

Note : If you are using add method in queue then throw exception error.

#

# ` `What is PriorityQueue ?

# ` `What is Deque ?

# ` `What is ArrayDeque ?

# ` `What is Set ?

# ` `What is HashSet ?

# ` `What is LinkedHashSet ?

# ` `What is SortedSet ?

# ` `What is TreeSet ?

Note: TreeSet arrange in ascending order.

# ` `What is Map ?

# ` `What is SortedMap ?

# ` `What is NavigableMap ?

# ` `What is TreeMap ?

# ` `What is EnumMap ?

# ` `What is HashMap ?

# ` `What is AbstractMap ?

# ` `What is difference between ArrayList and LinkedList ?

# ` `What is difference between ArrayList and Vector ?

# ` `Why we use vector ?

# ` `Which one is faster compare between ArrayList vs Vector and Explain How ?

# ` `What is difference between HashMap and TreeMap ?

# ` `What is difference between HashMap and LinkedHashMap ?

# ` `What is difference between array and arraylist ?

# ` `What is Difference ArrayList and Vector ?

è Difference between ArrayList Vs vector :

| **S.L.** |                                           **ArrayList**                                           |                                                                                                 **Vector**                                                                                                 |
| :------: | :-----------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   1\.    |                                  ArrayList is not synchronized.                                   |                                                                                          Vector is synchronized.                                                                                           |
|   2\.    | ArrayList increments 50% of the current array size if the number of elements exceeds ts capacity. |                                                 Vector increments 100% means doubles the array size if the total number of elements exceeds its capacity.                                                  |
|   3\.    |                   ArrayList is not a legacy class. It is introduced in JDK 1.2.                   |                                                                                         Vector is a legacy class.                                                                                          |
|   4\.    |                         ArrayList is fast because it is non-synchronized.                         | Vector is slow because it is synchronized, i.e., in a multithreading environment, it holds the other threads in a runnable or non-runnable state until the current thread releases the lock of the object. |
|   5\.    |                  ArrayList uses the Iterator interface to traverse the elements.                  |                                                         A Vector can use the Iterator interface or Enumeration interface to traverse the elements.                                                         |
|    6     |                                  ArrayList performance is high                                    |                                                                                         Vector performance is low                                                                                          |
|    7     |                                   Multiple threads is allowed                                     |                                                                                       only one threads are allowed .                                                                                       |

` `What is difference between comparator and comparable ?
