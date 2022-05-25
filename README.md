# Java-Basic-Assignment-1


1) What is a programming language? What is Java and what is Java used for?

Programming language:

In a simple word programming language is a vocabulary and set of grammatical rules for instructing a computer or computing device to perform specific tasks. • The term programming language usually refers to high-level languages. 
A programming language is a type of written language that tells computers what to do. Examples are: Python, Ruby, Java, JavaScript, C, C++, C#, BASIC, COBOL,FORTRAN, Ada, and Pascal.Programming languages are used to write all computer programs and computer software. A programming language is like a set of instructions that the computer follows to do something. such as .

What is Java:

Java is a general-purpose programming language that is class-based and object-oriented. The programming language is structured in such a way that developers can write code anywhere and run it anywhere without worrying about the underlying computer architecture. It is also referred to as write once, run anywhere (WORA).This means Java code compiled once can be run on all platforms that run Java Runtime Environment without the need for recompilation.

Java was developed inside Sun Microsystems (acquired by Oracle) by James Gosling. It was developed to be similar to C++ and shares a lot of syntax with it. Java, currently maintained by Oracle, receives regular updates to accommodate the evolving needs of the developer community.


What is java use for:

What is Java Used for?
Java can be used to build applications for a wide range of platforms. Desktops, servers, mobile phones, tablets, Blu-ray players, televisions, and web browsers all use Java, and developers can write Java-based applications for any of these platforms. Since Java adheres to WORA requirements, the same code can be run on all the platforms having Java Runtime Environment (JRE) without recompiling the code.

Java is used to write applications for different platforms that run JRE and supports applications that run on a single device like a desktop or mobile phone. Java can also be used to develop applications that work in a distributed manner. That means the same application can be distributed between servers or clients in a network and can be executed synchronously. Java can also be used to write application modules or applets as part of web pages.

Java is used for:

GUI applications
Web servers and applications servers
Middleware applications
Web applications
Mobile applications
Embedded systems
Enterprise applications.



2)Which version of Java you are working with? How can you find out the version of Java you are using?

<img width="477" alt="java1" src="https://user-images.githubusercontent.com/102998720/170152312-17708642-8926-4f20-8280-aab40452644b.png">


3)What is IDE? Which IDE you are working with?

The IDE( Integrated Development Environment) is an application that makes programming easier!

An IDE, or Integrated Development Environment, enables programmers to consolidate the different aspects of writing a computer program.

IDEs increase programmer productivity by combining common activities of writing software into a single application: editing source code, building executables, and debugging.

Editing Source Code
Writing code is an important part of programming. We start with a blank file, write a few lines of code, and a program is born! IDEs facilitate this process with features like syntax highlighting and autocomplete.

Syntax Highlighting
An IDE that knows the syntax of your language can provide visual cues. Keywords, words that have special meaning like class in Java, are highlighted with different colors.

Compare these two code samples:

// without syntax highlighting

public class NiceDay {
  public static void main(String[] args) {
    System.out.println("It's a nice day out!");
  }
}
// with syntax highlighting

public class NiceDay {
  public static void main(String[] args) {
    System.out.println("It's a nice day out!");
  }
}
Syntax highlighting makes code easier to read by visually clarifying different elements of language syntax.

Autocomplete
When the IDE knows your programming language, it can anticipate what you’re going to type next!

We’ve seen statements with System.out.println() quite a bit so far. In an IDE, we might see System as an autocomplete option after only typing Sy. This saves keystrokes so the programmer can focus on logic in their code.

Autocompleting a command

Building Executables
Java is a compiled language. Before programs run, the source code of a .java file must be transformed into an executable .class by the compiler. Once compiled, the program can be run from the terminal.

This compilation process is necessary for every program, so why not have the IDE do it for us? IDEs provide automated build processes for languages, so the act of compiling and executing code is abstracted away, like in Codecademy lessons.

Debugging
No programmer avoids writing bugs and programs with errors.

When a program does not run correctly, IDEs provide debugging tools that allow programmers to examine different variables and inspect their code in a deliberate way.

IDEs also provide hints while coding to prevent errors before compilation.

Catching a bug

Coding On Your Computer
The biggest benefit to using an IDE is that it allows you to code and run Java programs on your own computer. We recommend IntelliJ IDEA, which you can download for macOS, Windows, or Linux.

INTellij.


4)What is source code? What is file extension for Java source code?

Source code is the fundamental component of a computer program that is created by a programmer. It can be read and easily understood by a human being.In computing, source code is any collection of code, with or without comments, written using a human-readable programming language, usually as plain text.

What is the extension of a source code in Java?
List of File Extensions
File Extension	File Type
.class	Compiled java source code file.
.cmd	Compiler command file.
.CPP	C++ language file.
.csv	Comma-separated value file.


5) What is the second stage of Java life cycle?

Compiling .

6)Which compiler is used for compiling Java file?

Javac command.


7) What files are the input and output of the compilation stage.

The compilation is the second stage of the program compilation process. The compiler accepts the preprocessed file as input and provides the assembly code as output file with dot s extension. The compiler converts all high level program instructions into its equivalent assembly code instructions.

8)Which command is used to call Java compiler in terminal or CMD?

From the Command Prompt, navigate to the directory containing your.java files, say C:introcshello, by typing the cd command below. C:Usersusername> cd c:introcshello C:introcshello> Assuming the file, say HelloWorld.java, is in the current working directory, type the javac command in boldface below to compile it.

9)What is the third stage of Java Life Cycle?

The third stage of this step involves creating a prototype or mockup of what users need. This includes building a functional version or model that demonstrates how the new system will function and perform tasks similar to those it is expected to do when completed.

10)At which stageclass loader is used and what function does it perform?

Java ClassLoader is an abstract class. It belongs to a java.lang package. It loads classes from different resources. Java ClassLoader is used to load the classes at run time. In other words, JVM performs the linking process at runtime. Classes are loaded into the JVM according to need. If a loaded class depends on another class, that class is loaded as well. When we request to load a class, it delegates the class to its parent. In this way, uniqueness is maintained in the runtime environment. It is essential to execute a Java program.

11)Which unit is responsible for translating bytecodes into machine code?

JVM (Java virtual machine )

12)What is last stage of Java Life Cycle?

Last step is execution. The bytecode generated by the compiler will be executed by Java Virtual Machine (JVM). Input to the JVM is bytecode and output is machine code (0’s and 1’s) which will be executed by the CPU of the local machine.

13)Which command is used to run Java program in terminal or CMD?



To do this, open the Command Prompt (CMD) in Windows, if you are on Mac OS, open Terminal. To compile the program, type the following command and press Enter. javac MyClass.java

14) At what stage bytecode verifier is used?

The bytecode verifier traverses the bytecodes, constructs the type state information, and verifies the types of the parameters to all the bytecode instructions. The illustration shows the flow of data and control from Java.

15) What is JDK? Briefly explain the components of JDK.

The Java Development Kit (JDK) is a software development environment used for developing Java applications and applets. It includes the Java Runtime Environment (JRE), an interpreter/loader (java), a compiler (javac), an archiver (jar), a documentation generator (javadoc) and other tools needed in Java development. Advertisement

16)Name main components present in JVM and write function of each component.


JVM and middle-tier Java business objects can be scaled, even when they have session-long state. The following sections provide an overview of some of the components of the Oracle JVM and the JDBC driver and the SQLJ translator: Library Manager. Compiler. Interpreter. Class Loader. Verifier
Java Virtual Machine Architecture
The JVM consists of three distinct components:

Class Loader
Runtime Memory/Data Area
Execution Engine

In deail below:  ( https://www.freecodecamp.org/news/jvm-tutorial-java-virtual-machine-architecture-explained-for-beginners/ )

Whether you have used Java to develop programs or not, you might have heard about the Java Virtual Machine (JVM) at some point or another.

JVM is the core of the Java ecosystem, and makes it possible for Java-based software programs to follow the "write once, run anywhere" approach. You can write Java code on one machine, and run it on any other machine using the JVM.

JVM was initially designed to support only Java. However, over the time, many other languages such as Scala, Kotlin and Groovy were adopted on the Java platform. All of these languages are collectively known as JVM languages.

In this article, we will learn more about the JVM, how it works, and the various components that it is made of.

What is a Virtual Machine?
Before we jump into the JVM, let's revisit the concept of a Virtual Machine (VM).

A virtual machine is a virtual representation of a physical computer. We can call the virtual machine the guest machine, and the physical computer it runs on is the host machine.

image-37
A single physical machine can run multiple virtual machines, each with their own operating system and applications. These virtual machines are isolated from each other.

What is the Java Virtual Machine?
In programming languages like C and C++, the code is first compiled into platform-specific machine code. These languages are called compiled languages.

On the other hand, in languages like JavaScript and Python, the computer executes the instructions directly without having to compile them. These languages are called interpreted languages.

Java uses a combination of both techniques. Java code is first compiled into byte code to generate a class file. This class file is then interpreted by the Java Virtual Machine for the underlying platform. The same class file can be executed on any version of JVM running on any platform and operating system.

Similar to virtual machines, the JVM creates an isolated space on a host machine. This space can be used to execute Java programs irrespective of the platform or operating system of the machine.

Java Virtual Machine Architecture
The JVM consists of three distinct components:

Class Loader
Runtime Memory/Data Area
Execution Engine
image-39
Let's take a look at each of them in more detail.

Class Loader
When you compile a .java source file, it is converted into byte code as a .class file. When you try to use this class in your program, the class loader loads it into the main memory.

The first class to be loaded into memory is usually the class that contains the main() method.

There are three phases in the class loading process: loading, linking, and initialization.

image-40
Loading
Loading involves taking the binary representation (bytecode) of a class or interface with a particular name, and generating the original class or interface from that.

There are three built-in class loaders available in Java:

Bootstrap Class Loader - This is the root class loader. It is the superclass of Extension Class Loader and loads the standard Java packages like java.lang, java.net, java.util, java.io, and so on. These packages are present inside the rt.jar file and other core libraries present in the $JAVA_HOME/jre/lib directory.
Extension Class Loader - This is the subclass of the Bootstrap Class Loader and the superclass of the Application Class Loader. This loads the extensions of standard Java libraries which are present in the $JAVA_HOME/jre/lib/ext directory.
Application Class Loader - This is the final class loader and the subclass of Extension Class Loader. It loads the files present on the classpath. By default, the classpath is set to the current directory of the application. The classpath can also be modified by adding the -classpath or -cp command line option.
The JVM uses the ClassLoader.loadClass() method for loading the class into memory. It tries to load the class based on a fully qualified name.

If a parent class loader is unable to find a class, it delegates the work to a child class loader. If the last child class loader isn't able to load the class either, it throws NoClassDefFoundError or ClassNotFoundException.

Linking
After a class is loaded into memory, it undergoes the linking process. Linking a class or interface involves combining the different elements and dependencies of the program together.

Linking includes the following steps:

Verification: This phase checks the structural correctness of the .class file by checking it against a set of constraints or rules. If verification fails for some reason, we get a VerifyException.

For example, if the code has been built using Java 11, but is being run on a system that has Java 8 installed, the verification phase will fail.

Preparation: In this phase, the JVM allocates memory for the static fields of a class or interface, and initializes them with default values.

For example, assume that you have declared the following variable in your class:

private static final boolean enabled = true;
During the preparation phase, JVM allocates memory for the variable enabled and sets its value to the default value for a boolean, which is false.

Resolution: In this phase, symbolic references are replaced with direct references present in the runtime constant pool.

For example, if you have references to other classes or constant variables present in other classes, they are resolved in this phase and replaced with their actual references.

Initialization
Initialization involves executing the initialization method of the class or interface (known as <clinit>). This can include calling the class's constructor, executing the static block, and assigning values to all the static variables. This is the final stage of class loading.

For example, when we declared the following code earlier:

private static final boolean enabled = true;
The variable enabled was set to its default value of false during the preparation phase. In the initialization phase, this variable is assigned its actual value of true.

Note: the JVM is multi-threaded. It can happen that multiple threads are trying to initialize the same class at the same time. This can lead to concurrency issues. You need to handle thread safety to ensure that the program works properly in a multi-threaded environment.

Runtime Data Area
There are five components inside the runtime data area:

image-32
Let's look at each one individually.

Method Area
All the class level data such as the run-time constant pool, field, and method data, and the code for methods and constructors, are stored here.

If the memory available in the method area is not sufficient for the program startup, the JVM throws an OutOfMemoryError.

For example, assume that you have the following class definition:

public class Employee {
  
  private String name;
  private int age;
  
  public Employee(String name, int age) {
  
    this.name = name;
    this.age = age;
  }
}
In this code example, the field level data such as name and age and the constructor details are loaded into the method area.

The method area is created on the virtual machine start-up, and there is only one method area per JVM.

Heap Area
All the objects and their corresponding instance variables are stored here. This is the run-time data area from which memory for all class instances and arrays is allocated.

For example assume that you are declaring the following instance:

Employee employee = new Employee();
In this code example, an instance of Employee is created and loaded into the heap area.

The heap is created on the virtual machine start-up, and there is only one heap area per JVM.

Note: Since the Method and Heap areas share the same memory for multiple threads, the data stored here is not thread safe.

Stack Area
Whenever a new thread is created in the JVM, a separate runtime stack is also created at the same time. All local variables, method calls, and partial results are stored in the stack area.

If the processing being done in a thread requires a larger stack size than what's available, the JVM throws a StackOverflowError.

For every method call, one entry is made in the stack memory which is called the Stack Frame. When the method call is complete, the Stack Frame is destroyed.

The Stack Frame is divided into three sub-parts:

Local Variables – Each frame contains an array of variables known as its local variables. All local variables and their values are stored here. The length of this array is determined at compile-time.
Operand Stack – Each frame contains a last-in-first-out (LIFO) stack known as its operand stack. This acts as a runtime workspace to perform any intermediate operations. The maximum depth of this stack is determined at compile-time.
Frame Data – All symbols corresponding to the method are stored here. This also stores the catch block information in case of exceptions.
For example assume that you have the following code:

double calculateNormalisedScore(List<Answer> answers) {
  
  double score = getScore(answers);
  return normalizeScore(score);
}

double normalizeScore(double score) {
  
  return (score – minScore) / (maxScore – minScore);
}
In this code example, variables like answers and score are placed in the Local Variables array. The Operand Stack contains the variables and operators required to perform the mathematical calculations of subtraction and division.

image-36
Note: Since the Stack Area is not shared, it is inherently thread safe.

Program Counter (PC) Registers
The JVM supports multiple threads at the same time. Each thread has its own PC Register to hold the address of the currently executing JVM instruction. Once the instruction is executed, the PC register is updated with the next instruction.

Native Method Stacks
The JVM contains stacks that support native methods. These methods are written in a language other than the Java, such as C and C++. For every new thread, a separate native method stack is also allocated.

Execution Engine
Once the bytecode has been loaded into the main memory, and details are available in the runtime data area, the next step is to run the program. The Execution Engine handles this by executing the code present in each class.

However, before executing the program, the bytecode needs to be converted into machine language instructions. The JVM can use an interpreter or a JIT compiler for the execution engine.

image-33
Interpreter
The interpreter reads and executes the bytecode instructions line by line. Due to the line by line execution, the interpreter is comparatively slower.

Another disadvantage of the interpreter is that when a method is called multiple times, every time a new interpretation is required.

JIT Compiler
The JIT Compiler overcomes the disadvantage of the interpreter. The Execution Engine first uses the interpreter to execute the byte code, but when it finds some repeated code, it uses the JIT compiler.

The JIT compiler then compiles the entire bytecode and changes it to native machine code. This native machine code is used directly for repeated method calls, which improves the performance of the system.

The JIT Compiler has the following components:

Intermediate Code Generator - generates intermediate code
Code Optimizer - optimizes the intermediate code for better performance
Target Code Generator - converts intermediate code to native machine code
Profiler - finds the hotspots (code that is executed repeatedly)
To better understand the difference between interpreter and JIT compiler, assume that you have the following code:

int sum = 10;
for(int i = 0 ; i <= 10; i++) {
   sum += i;
}
System.out.println(sum);
An interpreter will fetch the value of sum from memory for each iteration in the loop, add the value of i to it, and write it back to memory. This is a costly operation because it is accessing the memory each time it enters the loop.

However, the JIT compiler will recognize that this code has a HotSpot, and will perform optimizations on it. It will store a local copy of sum in the PC register for the thread and will keep adding the value of i to it in the loop. Once the loop is complete, it will write the value of sum back to memory.

Note: a JIT compiler takes more time to compile the code than for the interpreter to interpret the code line by line. If you are going to run a program only once, using the interpreter is better.

Garbage Collector
The Garbage Collector (GC) collects and removes unreferenced objects from the heap area. It is the process of reclaiming the runtime unused memory automatically by destroying them.

Garbage collection makes Java memory efficient because because it removes the unreferenced objects from heap memory and makes free space for new objects. It involves two phases:

Mark - in this step, the GC identifies the unused objects in memory
Sweep - in this step, the GC removes the objects identified during the previous phase
Garbage Collections is done automatically by the JVM at regular intervals and does not need to be handled separately. It can also be triggered by calling System.gc(), but the execution is not guaranteed.

The JVM contains 3 different types of garbage collectors:

Serial GC - This is the simplest implementation of GC, and is designed for small applications running on single-threaded environments. It uses a single thread for garbage collection. When it runs, it leads to a "stop the world" event where the entire application is paused. The JVM argument to use Serial Garbage Collector is -XX:+UseSerialGC
Parallel GC - This is the default implementation of GC in the JVM, and is also known as Throughput Collector. It uses multiple threads for garbage collection, but still pauses the application when running. The JVM argument to use Parallel Garbage Collector is -XX:+UseParallelGC.
Garbage First (G1) GC - G1GC was designed for multi-threaded applications that have a large heap size available (more than 4GB). It partitions the heap into a set of equal size regions, and uses multiple threads to scan them. G1GC identifies the regions with the most garbage and performs garbage collection on that region first. The JVM argument to use G1 Garbage Collector is -XX:+UseG1GC
Note: There is another type of garbage collector called Concurrent Mark Sweep (CMS) GC. However, it has been deprecated since Java 9 and completely removed in Java 14 in favour of G1GC.

Java Native Interface (JNI)
At times, it is necessary to use native (non-Java) code (for example, C/C++). This can be in cases where we need to interact with hardware, or to overcome the memory management and performance constraints in Java. Java supports the execution of native code via the Java Native Interface (JNI).

JNI acts as a bridge for permitting the supporting packages for other programming languages such as C, C++, and so on. This is especially helpful in cases where you need to write code that is not entirely supported by Java, like some platform specific features that can only be written in C.

You can use the native keyword to indicate that the method implementation will be provided by a native library. You will also need to invoke System.loadLibrary() to load the shared native library into memory, and make its functions available to Java.

Native Method Libraries
Native Method Libraries are libraries that are written in other programming languages, such as C, C++, and assembly. These libraries are usually present in the form of .dll or .so files. These native libraries can be loaded through JNI.

Common JVM Errors
ClassNotFoundExcecption - This occurs when the Class Loader is trying to load classes using Class.forName(), ClassLoader.loadClass() or ClassLoader.findSystemClass() but no definition for the class with the specified name is found.
NoClassDefFoundError - This occurs when a compiler has successfully compiled the class, but the Class Loader is not able to locate the class file at the runtime.
OutOfMemoryError - This occurs when the JVM cannot allocate an object because it is out of memory, and no more memory could be made available by the garbage collector.
StackOverflowError - This occurs if the JVM runs out of space while creating new stack frames while processing a thread.
Conclusion
In this article, we discussed the Java Virtual Machine's architecture and its various components. Often we do not dig deep into the internal mechanics of the JVM or care about how it works while our code is working.

It is only when something goes wrong, and we need to tweak the JVM or fix a memory leak, that we try to understand its internal mechanics.

This is also a very popular interview question, both at junior and senior levels for backend roles. A deep understanding of the JVM helps you write better code and avoid pitfalls related to stack and memory errors.

17)What is JRE? In which stage of Java life cycle JRE is used?

(JRE)Java runtime Environment. Exection stage 
Java Runtime Environment (JRE) is an open-access software distribution that has a Java class library, specific tools, and a separate JVM. In exection stage JRE takes the Java code, combines it with needed libraries and starts the JVM to execute it. 
 
 
 
What is the syntax? Make a list of rules(you learned in a class) you should always follow while creating your Java application.
How should we name our Java application?
Write a structure of a simple Java application.
What is the importance of comments in the program? Mention different ways in which we can write comments in a program.
Write a simple Java program to print the “Hello World” message. Keeping in mind stages of Java Life Cycle draw a flow chart to show journey of your first program
What is file extension for Java executable code? At which stage of Java Life Cycle we get executable code?
When does compile time starts?
Compile time ends with generation of which file?
Can you run the program without compilation? Try running your first program without compilation and share result.
When does runtime start?
During which phase .class file is loaded into memory runtime or compile time? Who loads .class file into memory?
Assignment 2 (Variable and Data Types)
What do you understand by variable?
Name types of variables.
What is the difference between static and instance variables?
Which type of variable requires a keyword to determine its scope?
Which thing specifies the size and type of variable?
Can we use a variable without declaring it?
How can we declare a variable?
How can we initialize a variable?
Make a list of common Java data types.
Which data types are created by programmers and are not defined by Java?
Java has how many primitive data types?
What data type would you use for storing the number of students in a class?
What data type would you use for storing the average test score in a class?
How would you declare a variable storing the tax rate?
How would you declare a variable that tells the grade (A, B, C, or D) of students?
List the name conventions you learned in class about variables.
Name the Data type used for an object 'Pen'.
Write a program and declare the variable of each data type you learned in class. Initialize each variable with appropriate values and print them.
Write a program to print your name, email, address, phone number, and id.
What do you understand by typecasting?
In which type casting Java automatically converts one data type to another data type?
Write a program to convert int to double and print a message stating which type casting you did?
Write a program to convert double to int and print a message stating which type casting you did?
Write a program to convert int to string and print a message stating which type casting you did?
Write a program to convert string to int and print a message stating which type casting you did?
Write a program to convert float to double and print a message stating which type casting you did?
Write a program to convert byte to float and print a message stating which type casting you did?
Write a Java program to get the character at the 5th index of the String “automation”.
Write a program to find the length of the string "automation".
Write a Java program to concatenate a string “Java” to the end of another string “C#”.
Write a Java program to compare a string “automation” and another string “Automation”.
Write a Java program to check whether a string “Software” ends with the contents of another string “Hardware”.
Write a Java program to replace a character “n” with character “m” in the string “Automation”.
Write a Java program to check whether a string “Java is my favorite programming Lang” starts with the contents of another string “Python is my favorite programming language”.
Write a program to get a substring of the string “Let this be the last year tha you doubt yourself, fear, change or quit. Never give up” starting from index 10 and ending at index 26.
Write a Java program to convert all the characters in a string “YourName” to lowercase.
Write a Java program to convert all the characters in a string “YourName” to uppercase.
Write a program to reverse a string “ Java is my favorite”.
Assignment 3 (Operators)
What are operators?
Write the types of operators you studied in class.
The operators used in Arithmetic expressions can be classified into which type?
Examine the following code. The programmer is not getting the same value for result and result2. Why? double result = (20-10/3); double result = ((20-10)/3);
Write a program to check if the two numbers 23 and 45 are equal.
Write a Java program to find the value of specified expression. a. 301 + 0) / 5 b. 7.0e-6 * 10000000.1 c. true && true d. false && true e. (false && false) || (true && true) f. (false || false) && (true && true)
Length and breadth of a rectangle are 9 and 5 respectively. Write a program to calculate the area and perimeter of the rectangle.
Write a program to calculate the perimeter of a triangle having sides of length 9,6 and 5 units.
Write a program to find if both the conditions 'a < 50' and 'a < b' are true when value of a is 45 and b is 67.
Write a program to find total marks and percentage of students when his marks in three subjects are 87, 39 and 52 respectively (each out of 100 ).
Write a program to convert temperature from Fahrenheit to Celsius degree. (You can take temperature of your choice)
Write a program to find largest number among three numbers: 76,54 and 89.
Write a program to find smallest number among three numbers: 76,54 and 89.
If num1=5 and num2=4 then write a program to swap values of these numbers.
Write a program to convert positive number to negative number. (You can take any number of your choice)
Consider the following code snippet. arrayOfInts[j] > arrayOfInts[j+1] a. Which operators does the code contain?
Consider the following code snippet. int i = 10; int n = i++%5; a. What are the values of i and n after the code is executed? b. What are the final values of i and n if instead of using the postfix increment operator (i++), you use the prefix version (++i))?
To invert the value of a boolean, which operator would you use?
Write a program to show the difference between postfix expr ++ and prefix ++ expr operators. In the comments of your program explain each line of code.
Write a program to show the difference between postfix expr -- and prefix -- expr operators. In the comments of your program explain each line of code.
Which operator is used to compare two values, = or == ?
Explain the following code sample: result = someCondition ? value1 : value2;
Write a program to divide 154 with 7.
Write a program to print the sum, product, difference, divide and remainder of two numbers (First number=579 and second number=17).
Write a Java program to print the area and perimeter of a circle when radius of circle is 4.2 cm.
Write a program that compares two number 13 and 16 are not equal.
Write a program to decrease value of variable by 1 without using arithmetic operator. (Value of variable is 13)
Write a program to increase value of variable by 1 without using arithmetic operator. (Value of variable is 13)
Write a program that shows the message true first number is greater than second number or third number. (First number= 23, Second number = 32 and third number = 15).
Write a program that shows message true first number is greater than second number and third number. (First number= 23, Second number = 32 and third number = 15).

